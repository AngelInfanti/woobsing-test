<template>
  <div id="app" class="flex flex-col h-screen justify-between">
    <header-view></header-view>
    <router-view />
    <footer-view></footer-view>
  </div>
</template>

<script>
import HeaderView from "./views/layouts/HeaderView.vue";
import FooterView from "./views/layouts/FooterView.vue";
export default {
  components: {
    HeaderView,
    FooterView,
  },
  data() {
    return {};
  },
};
</script>
