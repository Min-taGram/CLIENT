<template>
  <div class="div">
    <br />
    <search-bar></search-bar>
    <br />
    <upload></upload>
    <gallery></gallery>
    <gallery></gallery>
  </div>
</template>


<script>
import searchBar from "./components/search-bar";
import gallery from "./components/gallery";
import upload from "./components/upload";

export default {
  name: "App",
  components: {
    searchBar,
    gallery,
    upload
  }
};
</script>




<style>
</style>