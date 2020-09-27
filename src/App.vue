<template>
  <div>
    <router-link to="/"><img src="./assets/logo.png" id="ru_site"></router-link>
    <!-- <router-link to="/">Russian</router-link> |
    <router-link to="/about">English</router-link> -->

  </div>
  <router-view/>
</template>

<script>

</script>

<style>

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#main-header {
  margin-top: 100px;
}

#nav {
  padding: 30px;
  margin-left: 800px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}

#ru_site {
  width: 50px;
  height: 35px;

}
</style>
