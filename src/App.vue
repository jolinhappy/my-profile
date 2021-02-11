<template>
  <div id="app">
    <!-- <div id="nav">
      <router-link to="/">Home</router-link> |
    </div> -->
    <router-view />
  </div>
</template>
<script lang="ts">
import Vue from "vue";
export default Vue.extend({});
</script>

<style lang="scss">
//reset
@import "src/scss/style.scss";
* {
  width: 100%;
  margin: 0;
  padding: 0;
}
a {
  text-decoration: none; /* 拿掉底線 */
}
</style>
