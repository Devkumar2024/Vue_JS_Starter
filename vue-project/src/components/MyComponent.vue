<!-- Text Interpolation -->
<!-- <script setup>
const myMessage = "hibrow games"
const myNumber = 100;
function add(x,y){
return x+y
}
</script>
<template>
    <h1>{{myMessage}}</h1>
    <h2>{{ myNumber /* Ths area is js area */ }}</h2>
    <h3>12+3+4+5 = {{ 12+3+4+5 }}</h3>
    <h1>Add Two numbers : {{  add(2,28) }}</h1>
</template> -->

<script setup>
// const myChannel = "https://www.youtube.com/"
const imageinfo = { src :"https://plus.unsplash.com/premium_photo-1683910767532-3a25b821f7ae?q=80&w=808&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D",
 alt: " a random picture",
 width : 400,
 hight : 350,}

</script>
<!-- /*In Vue.js, v-bind is a directive used to dynamically bind HTML attributes to Vue component data or expressions. It allows you to bind attributes like class, style, src, href, and others to variables or computed properties within your component. */
    -->
<template>
  <!-- <a :href="myChannel" target="_blank">Youtube Redirect Link</a> -->
  <img v-bind:="imageinfo" />
</template>
