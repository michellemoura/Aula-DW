<template>
  <div>
    <h1>{{info}}</h1>
    <router-link to="/">
    <spam>home</spam>
    </router-link>
    <br>
    <router-link :to="{name:'home'}">
     <spam>home</spam>
    </router-link>
    
  </div>
</template>

<script>
export default {
  data() {
    return {
      info: "Eu sou linda"
    };
  }
};
</script>

<style scope>
</style>