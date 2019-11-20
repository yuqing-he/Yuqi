<template>
  <div id="app">
    <a href="https://github.com/yuqing-he" class="logo_h">
      <img src="./assets/logo_h.jpg" class="Header" alt="我的水印">
    </a>
    <img src="./assets/img01.jpg" class="Header" alt="我的头像">
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  font-size: 16px;
}
.logo_h {
  position: fixed;
  z-index: 999;
  top: 0;
  right: 0;
  opacity: 0.8;
}
.Header {
  width: 40vw;
  height: 40vw;
  max-width: 120px;
  max-height: 120px;
  border-radius: 50%;
}
</style>
