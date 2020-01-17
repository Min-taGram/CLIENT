<template>
  <div class="div">
    <!-- <login></login>
    <register></register>-->
    <headerbuatankita></headerbuatankita>
    <search-bar></search-bar>
    <!-- <upload></upload> -->
    <gallery></gallery>
    <footerbuatankita></footerbuatankita>
  </div>
</template>


<script>
import login from "./components/login";
import register from "./components/register";
import headerbuatankita from "./components/headerbuatankita";
import searchBar from "./components/search-bar";
import gallery from "./components/gallery";
import upload from "./components/upload";
import footerbuatankita from "./components/footerbuatankita";

export default {
  name: "App",
  data: {},
  components: {
    login,
    register,
    headerbuatankita,
    searchBar,
    gallery,
    upload,
    footerbuatankita
  }
};
</script>




<style>
</style>