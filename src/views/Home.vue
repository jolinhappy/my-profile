<template>
  <div class="home">
    <!-- navbar -->
    <div class="navbar">
      <div class="navbar-icon">
        <img src="https://picsum.photos/30/30/?random=30" class="icon" alt="" />
      </div>
      <input
        type="checkbox"
        class="navbar-item-toggle"
        id="toggle-navbar-item"
      />
      <div class="navbar-contect-group">
        <a href="" class="contect">git</a>
        <a href="" class="contect">med</a>
        <a href="" class="contect">mail</a>
      </div>
      <div class="navbar-item-group">
        <a href="" class="navbar-item">關於文科</a>
        <a href="" class="navbar-item">文科的技能</a>
        <a href="" class="navbar-item">文科的作品</a>
        <a href="" class="navbar-item">文科的經歷</a>
        <a href="" class="navbar-item">了解更多文科</a>
      </div>
    </div>
    <label class="navbar-toggle-label" for="toggle-navbar-item">
      <span class="hamburger"></span>
    </label>
    <!-- summary -->
    <div class="summary">
      <div class="picture">
        <img
          src="https://picsum.photos/250/250/?random=231"
          alt=""
          class="my-picture"
        />
      </div>
      <div class="text-section">
        <h3 class="name">Phoebe Hsu</h3>
        <div class="text">
          Lorem ipsum dolor sit amet consectetur, adipisicing elit. Corporis
          illum recusandae in! In ab consectetur at quia! Similique, quas eius
          cum odit natus exercitationem voluptatem. Tempore quibusdam eos ad
          possimus.
        </div>
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
@import "src/scss/style.scss";
.home {
  width: 100%;
  height: auto;
  .navbar-toggle-label {
    position: absolute;
    right: 20px;
    top: 30px;
    height: 30px;
    width: 30px;
    display: flex;
    .hamburger {
      width: 30px;
      height: 4px;
      background: red;
      position: relative;
      &::before,
      &::after {
        content: "";
        width: 30px;
        height: 4px;
        background: red;
        position: absolute;
      }
      &::before {
        top: 10px;
      }
      &::after {
        bottom: 10px;
      }
    }
  }
  .navbar {
    width: 100%;
    height: 60px;
    background: $main-orange;
    -webkit-box-shadow: 0px 5px 16px 0px rgba(0, 0, 0, 0.1);
    -moz-box-shadow: 0px 5px 16px 0px rgba(0, 0, 0, 0.1);
    box-shadow: 0px 5px 16px 0px rgba(0, 0, 0, 0.1);
    position: relative;
    .navbar-icon {
      width: 60px;
      height: 55px;
      margin-left: 20px;
    }
    .navbar-item-toggle {
      display: none;
      &:checked ~ .navbar-item-group {
        transform: scale(1, 1);
      }
      &:checked ~ .navbar-item-group .navbar-item {
        opacity: 1;
        transition: opacity 0.2s ease-out 0.35s;
      }
    }
    .navbar-item-group {
      display: flex;
      flex-direction: column;
      background: $main-orange;
      height: 260px;
      transform-origin: top;
      transform: scale(1, 0);
      transition: transform 0.5s ease-out;
      padding-top: 25px;
      .navbar-item {
        text-align: center;
        margin: 13px 0;
        font-weight: bold;
        color: white;
        opacity: 0;
        &:hover {
          color: $main-blue;
        }
      }
    }
    .navbar-contect-group {
      position: absolute;
      top: 0;
      right: 100px;
      width: 100px;
      height: 100%;
      margin-right: 30px;
      .contect {
        height: 100%;
        line-height: 60px;
        margin: 0 10px;
      }
    }
  }
  .summary {
    height: 400px;
    background: $main-pink;
    padding-top: 40px;
    display: flex;
    flex-direction: column;
    align-items: center;
    .picture {
      width: 200px;
      height: 200px;
      margin-bottom: 30px;
      .my-picture {
        border-radius: 50%;
      }
    }
    .text-section {
      width: calc(100% - 40px);
    }
  }
}

@media screen and (min-width: 675px) {
  .home {
    .navbar-toggle-label {
      display: none;
    }
    .navbar {
      display: grid;
      grid-template-columns: 2fr 120px minmax(600px, 1fr);
      .navbar-contect-group {
        all: unset;
        grid-column: 2 / 3;
      }
      .navbar-item-group {
        all: unset;
        grid-column: 3 / 4;
        margin-left: 30px;
        .navbar-item {
          opacity: 1;
          margin: 0 15px;
          line-height: 60px;
        }
      }
    }
    //summary
    .summary {
      flex-direction: row;
      justify-content: center;
      .picture {
        width: 200px;
        height: 200px;
        margin-right: 30px;
        .my-picture {
          border-radius: 50%;
        }
      }
      .text-section {
        width: 50%;
      }
    }
  }
}
</style>