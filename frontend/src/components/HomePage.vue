<!-- src/components/Home.vue -->
<template>
  <div>
    <h1>Welcome to HotmartGPT</h1>
    <router-link to="/genai">Chat to HotmartGPT</router-link>
  </div>
</template>

<script>
export default {
  name: 'HomePage'
}
</script>

<style scoped>
h3 {
  margin: 40px 0 0;
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
  color: #FF0000;
}
</style>
