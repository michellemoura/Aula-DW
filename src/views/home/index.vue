<template>
  <div>
    <h1>{{info}}</h1>
    <router-link to="/michelle">
    <spam>About me </spam>
    </router-link>
  </div>

</template>

<script>
export default {
  data() {
    return {
      info: "Michele Moura"
    };
  }
};
</script>

<style scope>
</style>