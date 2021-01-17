<template>
  <div class="home">
    <div class="navbar">
      <div class="navbar-icon">
        <img src="" class="icon" alt="" />
      </div>
      <div class="navbar-item-group">
        <a href="" class="navbar-item">關於文科</a>
        <a href="" class="navbar-item">文科會的技能</a>
        <a href="" class="navbar-item">文科的作品</a>
        <a href="" class="navbar-item">文科的經歷</a>
        <a href="" class="navbar-item">了解更多文科</a>
      </div>
      <div class="navbar-contect-group">
        <a href="" class="contect">git</a>
        <a href="" class="contect">med</a>
        <a href="" class="contect">mail</a>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";
import HelloWorld from "@/components/HelloWorld.vue"; // @ is an alias to /src

@Component({
  components: {
    HelloWorld,
  },
})
export default class Home extends Vue {}
</script>

<style lang="scss" scoped>
.home {
  width: 100%;
  height: 100vh;
  // background: red;
}
</style>