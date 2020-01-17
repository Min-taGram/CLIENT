<template>
  <section class="search-bar">
    <div class="container h-100">
      <div class="d-flex justify-content-center h-100">
        <div class="searchbar">
          <input
            v-model="searchKeyword"
            class="search_input"
            type="text"
            name
            placeholder="Search tag..."
          />
          <a v-on:click.prevent="searchThis()" href="#" class="search_icon">
            <i class="fas fa-search"></i>
          </a>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  data() {
    return {
      searchKeyword: "",
      tags: []
    };
  },
  methods: {
    searchThis() {
      this.tags.push("tag1");
      this.tags.push("tag2");
      this.tags.push("tag3");

      console.log(this.tags);
    }
  }
};
</script>

<style lang="css" scoped>
</style>