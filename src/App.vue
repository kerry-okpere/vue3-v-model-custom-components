<template>
  <Text v-model="state.text"/>
  ===>{{state.text}}
  
</template>

<script setup>
import Text from './components/Text.vue'
import { reactive } from 'vue'

const state = reactive({ 
  text: 'kerry' 
})
// This starter template is using Vue 3 experimental <script setup> SFCs
// Check out https://github.com/vuejs/rfcs/blob/script-setup-2/active-rfcs/0000-script-setup.md
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
