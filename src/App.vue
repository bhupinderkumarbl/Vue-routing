<style>
body{
margin:0px; padding:0px
}
.navigation{
background:#2699FB;
padding:10px;
}
.navigation a{ color:#fff; text-decoration:none; font-size:24px; padding:10px 30px 10px 0}
</style>
<template>
<div id="app">
<div class="navigation">
<div class="container">
    <router-link :to="{ name: 'Hello' }">Home</router-link>
    <router-link to="/about">About</router-link>
    <router-link to="/coins/ethereum">Portfolio</router-link>
    <router-link to="/coins/bitcoin">Contact us</router-link>
</div>
</div>
    <router-view></router-view>
  </div>
</template>

<script>
export default {
  name: 'app'
}
</script>
