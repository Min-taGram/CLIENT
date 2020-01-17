<template>
  <div class="div">
    <!-- <login></login>
    <register></register> -->
    <header></header>
    <search-bar></search-bar>
    <gallery></gallery>
    <!-- <upload></upload> -->
    <footer></footer>
  </div>
</template>


<script>
import login from "./components/login";
import register from "./components/register";
import header from "./components/header";
import searchBar from "./components/search-bar";
import gallery from "./components/gallery";
import upload from "./components/upload";
import footer from "./components/footer"

export default {
  name: "App",
  components: {
    login,
    register,
    header,
    searchBar,
    gallery,
    upload,
    footer
  }
};
</script>




<style>
</style>