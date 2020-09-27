<template>

  <wired-search-input id="search" placeholder=""></wired-search-input>
  <!-- <div v-show="value">
    <wired-search-input id="search" placeholder="Ищите как хотите"></wired-search-input>
  </div> -->
</template>

<script>
/* import "wired-search-input" */
import "wired-elements";

export default {
  name: "Search",
  props: {
    name: String
  },
};
</script>

<style lang="stylus" scoped>
input
  width 100%
  font-size 16px
  text-align center
</style>

<style>
  #search{
    margin-top: 200px;
    width: 500px;
  }
</style>
