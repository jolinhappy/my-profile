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
    <!-- skill -->
    <div class="skill">
      <div class="skill-title">文科的技能</div>
      <div class="skill-content">
        <div class="skill-card">
          <h3 class="title-text">前端</h3>
          <ul class="skill-group">
            <li class="skill-item">HTML</li>
            <li class="skill-item">css</li>
          </ul>
        </div>
        <div class="skill-card">
          <h3 class="title-text">後端</h3>
          <ul class="skill-group">
            <li class="skill-item">HTML</li>
            <li class="skill-item">css</li>
          </ul>
        </div>
        <div class="skill-card">
          <h3 class="title-text">其他</h3>
          <ul class="skill-group">
            <li class="skill-item">HTML</li>
            <li class="skill-item">css</li>
          </ul>
        </div>
      </div>
    </div>
    <!-- project -->
    <div class="project">
      <div class="project-title">文科的作品</div>
      <div class="project-content">
        <div class="project-item">
          <div class="project-photo">
            <img src="https://picsum.photos/300/300/?random=123" alt="" />
          </div>
          <div class="project-detail">
            <div class="project-item-title">XXXX</div>
            <div class="project-description">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Veritatis
              recusandae expedita dolorum? Error atque repudiandae laudantium
              ipsum quia voluptatum aspernatur illo doloribus provident,
              veritatis praesentium corporis molesti
            </div>
          </div>
        </div>
        <div class="project-item">
          <div class="project-photo">
            <img src="https://picsum.photos/300/300/?random=329" alt="" />
          </div>
          <div class="project-detail">
            <div class="project-item-title">XXXX</div>
            <div class="project-description">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Veritatis
              recusandae expedita dolorum? Error atque repudiandae laudantium
              ipsum quia voluptatum aspernatur illo doloribus provident,
              veritatis praesentium corporis molesti
            </div>
          </div>
        </div>
        <div class="project-item">
          <div class="project-photo">
            <img src="https://picsum.photos/300/300/?random=245" alt="" />
          </div>
          <div class="project-detail">
            <div class="project-item-title">XXXX</div>
            <div class="project-description">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Veritatis
              recusandae expedita dolorum? Error atque repudiandae laudantium
              ipsum quia voluptatum aspernatur illo doloribus provident,
              veritatis praesentium corporis molesti
            </div>
          </div>
        </div>
        <div class="project-item">
          <div class="project-photo">
            <img src="https://picsum.photos/300/300/?random=165" alt="" />
          </div>
          <div class="project-detail">
            <div class="project-item-title">XXXX</div>
            <div class="project-description">
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Veritatis
              recusandae expedita dolorum? Error atque repudiandae laudantium
              ipsum quia voluptatum aspernatur illo doloribus provident,
              veritatis praesentium corporis molesti
            </div>
          </div>
        </div>
      </div>
    </div>
    <!-- experience -->
    <div class="experience">
      <div class="experience-title">文科的經歷</div>
      <div class="experience-content">
        <div class="experience-item">
          <div class="experience-bar">
            <div class="circle"></div>
            <div class="bar"></div>
          </div>
          <div class="experience-detail">
            <div class="experience-item-title">XXX公司</div>
            <div class="experience-description">
              dekowfkopweffkoe wfoko fewfopewkopfkf eowfko
            </div>
          </div>
        </div>
        <div class="experience-item">
          <div class="experience-bar">
            <div class="circle"></div>
            <div class="bar"></div>
          </div>
          <div class="experience-detail">
            <div class="experience-item-title">XXX公司</div>
            <div class="experience-description">
              dekowfkopweffkoe wfoko fewfopewkopfkf eowfko
            </div>
          </div>
        </div>
        <div class="experience-item">
          <div class="experience-bar">
            <div class="circle"></div>
            <div class="bar"></div>
          </div>
          <div class="experience-detail">
            <div class="experience-item-title">XXX公司</div>
            <div class="experience-description">
              dekowfkopweffkoe wfoko fewfope
            </div>
          </div>
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
    height: calc(100vh - 80px);
    background: $main-pink;
    padding-top: 60px;
    display: flex;
    flex-direction: column;
    align-items: center;
    .picture {
      width: 150px;
      height: 150px;
      margin-bottom: 30px;
      .my-picture {
        border-radius: 50%;
      }
    }
    .text-section {
      width: calc(100% - 120px);
    }
  }
  .skill {
    width: 100%;
    height: auto;
    background: $main-green;
    padding-top: 60px;
    padding-bottom: 30px;
    display: flex;
    flex-direction: column;
    align-items: center;
    .skill-title {
      width: 200px;
      height: 60px;
      line-height: 60px;
      font-size: 30px;
      font-weight: bold;
      background: hsl(16, 100%, 66%);
      text-align: center;
      border-radius: 20px;
    }
    .skill-content {
      display: flex;
      flex-direction: column;
      align-items: center;
      margin-top: 25px;
      .skill-card {
        width: calc(100% - 100px);
        height: 300px;
        background: $main-blue;
        margin: 30px;
        display: flex;
        flex-direction: column;
        align-items: center;
        transform: scale(1, 1);
        transition: transform 0.35s ease-out;

        &:hover {
          transform: scale(1.03, 1.03);
          color: white;
          //背景色更改
        }
        .title-text {
          text-align: center;
          font-size: 25px;
          margin: 20px 0;
        }
        .skill-group {
          width: 65%;
          font-size: 25px;
        }
      }
    }
  }
  .project {
    width: 100%;
    height: auto;
    background: $main-blue;
    padding-top: 60px;
    padding-bottom: 30px;
    display: flex;
    flex-direction: column;
    align-items: center;
    .project-title {
      width: 200px;
      height: 60px;
      line-height: 60px;
      font-size: 30px;
      font-weight: bold;
      background: hsl(16, 100%, 66%);
      text-align: center;
      border-radius: 20px;
    }
    .project-content {
      margin-top: 25px;
      .project-item {
        margin: 30px auto;
        width: calc(100% - 100px);
        padding-bottom: 20px;
        background: $main-green;
        height: auto;
        display: flex;
        flex-direction: column;
        align-items: center;
        .project-photo {
          width: 180px;
          height: 180px;
          margin-top: 20px;
        }
        .project-detail {
          text-align: center;
          width: 85%;
          margin-top: 25px;
          font-size: 20px;
          .project-item-title {
            margin-bottom: 10px;
            font-weight: bold;
          }
        }
      }
    }
  }
  .experience {
    width: 100%;
    height: auto;
    background: $main-pink;
    padding-top: 60px;
    padding-bottom: 30px;
    display: flex;
    flex-direction: column;
    align-items: center;
    .experience-title {
      width: 200px;
      height: 60px;
      line-height: 60px;
      font-size: 30px;
      font-weight: bold;
      background: hsl(16, 100%, 66%);
      text-align: center;
      border-radius: 20px;
    }
    .experience-content {
      margin: 25px 0;
      .experience-item {
        display: flex;
        width: calc(100% - 100px);
        margin: 0 auto;
        .experience-bar {
          width: 80px;
          position: relative;
          .circle {
            width: 30px;
            height: 30px;
            background: crimson;
            border-radius: 50%;
            position: absolute;
          }
          .bar {
            height: auto;
            &::after {
              content: "";
              position: absolute;
              width: 10px;
              min-height: 200px;
              background: crimson;
              left: 10px;
              top: 5px;
            }
          }
        }
        .experience-detail {
          min-height: 200px;
          .experience-item-title {
            font-size: 20px;
            font-weight: bold;
            margin-bottom: 15px;
          }
        }
      }
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
      padding-top: 100px;
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
    .skill {
      height: 700px;
      .skill-content {
        flex-direction: row;
        justify-content: center;
        .skill-card {
          width: 325px;
          height: 450px;
          background: $main-blue;
          margin: 30px;
          display: flex;
          flex-direction: column;
          align-items: center;
          transform: scale(1, 1);
          transition: transform 0.35s ease-out;

          &:hover {
            transform: scale(1.03, 1.03);
            color: white;
            //背景色更改
          }
          .title-text {
            text-align: center;
            font-size: 25px;
            margin: 20px 0;
          }
          .skill-group {
            width: 65%;
            font-size: 25px;
          }
        }
      }
    }
    .project {
      .project-content {
        margin-top: 25px;
        display: flex;
        flex-wrap: wrap;
        justify-items: center;
        .project-item {
          margin: 30px auto;
          width: 460px;
          padding-bottom: 40px;
          .project-photo {
            width: 240px;
            height: 240px;
            margin-top: 40px;
          }
        }
      }
    }
    .experience {
      .experience-item {
        display: flex;
        max-width: 600px;
        margin: 0 auto;
      }
    }
  }
}
</style>