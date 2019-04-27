<template>
  <div class="scene2">
    <h2>シーン２だよ</h2>
    <nickname-header></nickname-header>

  </div>
</template>

<script>
import Vue from 'vue'
import {NickNameHeader} from './forms/Headers.js'

Vue.component('nickname-header', NickNameHeader)
</script>