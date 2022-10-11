<template>
    <div :style="{backgroundColor: 'red', display: 'flex', flexDirection: 'column', alignItems: 'center', justifyContent: 'center'}">
    <div :class="classes">Ironhack Bootcamp</div>
    <div><h2>{{text}}</h2></div>
<img :src="image" :style="{height: '50px', width: '50px'}" />
<button @click='helloWorld()'>Click!</button>
</div>
</template>

<script setup>
import { ref } from 'vue'
const image = 'https://cdn-images-1.medium.com/max/1200/1*69RcxrWXuk385lSxkIYYLA.png'
const classes = ['text, color', 'flex']

const helloWorld = () => {
    console.log('hello world')
    return; 
}



</script>


<style scoped>
.text {
    font-size: 20px; 
}

.color {
    color: blue; 
}

</style>