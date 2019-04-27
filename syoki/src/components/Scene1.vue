<template>
  <div class="scene1">
    <nickname-header></nickname-header>
    <input-text></input-text>
    <input-button></input-button>
  </div>
</template>

<script>
import Vue from 'vue'
import {NickNameHeader, InputText, InputButton} from './forms/Headers.js'

export default {
  data () {
    return {

    }
  }
}

//  コンポーネントを登録
Vue.component('nickname-header', NickNameHeader)
//  コンポーネントを登録
Vue.component('input-text', InputText)
//  コンポーネントを登録
Vue.component('input-button', InputButton)


</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
