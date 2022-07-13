<template>
 <div id="site_app">
    <header id="site_header_app">
      
    </header>
    <!-- /#site_header_app -->
    <main id="site_main_app">
      <router-view></router-view>
    </main>
    <!-- /#site_main_app -->
    <footer id="site_footer_app" class="text-center my-5">Copyrigth©</footer>
    <!-- /#site_footer_app -->
  </div>
</template>

<script>
export default {
  name: "App",
  data() {
    return {};
  },
  methods: {},
  mounted() {},
};
</script>

<style lang='scss' scoped>
</style>