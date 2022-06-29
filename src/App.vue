<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
      <button>login</button>
    </div>
    <router-view/>
  </div>
</template>
<script>
import './assets/sass/main.scss'
export default{
  name:'app',

}
</script>
