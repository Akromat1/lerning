<script setup>
defineProps ({
    placeholder: String,
    type:String
})
</script>
<template>
    <div>
  
        <input type="text" v-bind:placeholder="placeholder" v-bind:type="type"  class="input-text"/>
    </div>
   
</template>
<style scoped>

.input-text {
    max-width: 350px;
    width: 100%;
    height: 54px;
    padding-left: 16px;
    padding-right: 16px;
} 
</style>