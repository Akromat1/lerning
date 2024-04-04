<script setup>
import { ref } from 'vue'


let name = ref(123)
defineProps ({
  msg: String,
})

</script>

<template>
  {{ msg }}
  <span class="qq" @click="name+=1"> {{ name }}</span>
  

 
</template>

<style scoped>
.qq{
  cursor: pointer;
}
</style>
