<script>
  export default {
    name: "AppTitle",
    data(){
      return{
        title: "La mia prima app con Vite!"
      }
    }
  }
</script>
<template>
  <div>

    <h1>{{title}}</h1>
  </div>
</template>


<style scoped>
div{
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
}
h1{
  background-color: aqua;
}
</style>