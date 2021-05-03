<template>
  <label>
    Text <br>
    <input type="text" :value="modelValue" @input="$emit('update:modelValue', $event.target.value)">
  </label>
</template>

<script>
import { reactive, toRefs } from 'vue'
export default {
  props:{
    modelValue: String
  },
  emits:['update:modelValue'],
  setup(props){
    return{
    }
  }
}
</script>

<style scoped>

</style>
