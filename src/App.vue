<template>
  <div id="app">
    <div id="nav">
      <!-- |
      <router-link to="/about">About</router-link>-->
      <div class="w">
        <div class="header">
          <p class="header_l">欢迎进重庆虎普环保科技有限公司官网！</p>
          <p class="header_r">
            <a href="#" target="_blank">关于我们</a> |
            <a href="#" target="_blank">在线咨询</a>
          </p>
        </div>
        <img class="img_header" src="./assets/img/brt_01.jpg" alt="sasdsf" srcset />
      </div>
      <div class="nav">
        <ul>
          <li><router-link to="/"><i>公司首页</i></router-link></li>
          <li><router-link to="/other"><i>关于我们</i></router-link></li>
          <li><router-link to="/other"><i>服务项目</i></router-link></li>
          <li><router-link to="/other"><i>产品中心</i></router-link></li>
          <li><router-link to="/other"><i>工程案例</i></router-link></li>
          <li><router-link to="/other"><i>新闻中心</i></router-link></li>
          <li><router-link to="/other"><i>联系我们</i></router-link></li>
        </ul>
      </div>
    </div>
    <router-view />
  </div>
</template>

<style lang="less">
@import "./style/common";
@import "./style/base";
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}

.img_header {
  width: 100%;
  margin: 0 auto;
}
</style>
