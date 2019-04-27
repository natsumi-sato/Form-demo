<template>
  <div id="app">
    <div class="header">
      <img class="img" src="./assets/logo.png">
      <p class="title">Cat LOVER <span>vue</span></p>
    </div>
    <div class="content">
      <router-view></router-view>
    </div>
    <div class="footer">
      <h2>Cat LOVER Co., Ltd.</h2>
      <ul>
        <li><a href="" target="_blank">TOP</a></li>
        <li><a href="" target="_blank">リクルート</a></li>
        <li><a href="" target="_blank">アクセス</a></li>
        <li><a href="" target="_blank">会社概要</a></li>
      </ul>
    </div>
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
}
</style>
