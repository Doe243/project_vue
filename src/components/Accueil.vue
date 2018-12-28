<template>
  <div class="accueil">
    <h1 class="container">{{ msg }}</h1>

  </div>
</template>

<script>
export default {
  name: 'Accueil',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

@font-face {
   font-family: 'SMB';
   src:  local('SuperMarioBros.'),
   url('/assets/fonts/SuperMarioBros.ttf') format('truetype');
   font-weight: normal;
  font-style: normal;
   }

h1 {
  text-decoration: none;
  font-weight: bold;
  font-family: 'SMB';
  color:#ff5050;
  font-size: 100px;
}
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
  color: #42b983;
}
</style>
