<template>
  <section id="gallery" class="py-5">
    <!-- jangan lupa tambah padding -->
    <div class="container">
      <div class="gallery-heading text-center mb-5">
        <h1>MINTAGRAM</h1>
        <h3>&hearts;</h3>
        <!-- <h1><i class="fas fa-camera-retro"></i></h1> -->
      </div>

      <div class="row">
        <div class="lightbox-content col-3 mb-4">
          <a
            href="./assets/img/1.jpg"
            data-lightbox="art"
            data-title="Tags: hahaha | hohoho | hehehe | hihi"
          >
            <img src="./assets/img/1.jpg" class="img-fluid" alt />
          </a>
          <p
            class="mt-2"
            style="color: white; font-family: 'Gelasio', cursive;"
          >Tags : haha | hihi | huhu | hehe</p>
        </div>
        <div class="lightbox-content col-3">
          <a
            href="./assets/img/2.jpg"
            data-lightbox="art"
            data-title="Tags: hahaha | hohoho | hehehe | hihi"
          >
            <img src="./assets/img/2.jpg" class="img-fluid" alt />
          </a>
          <p
            class="mt-2"
            style="color: white; font-family: 'Gelasio', cursive;"
          >Tags : haha | hihi | huhu | hehe</p>
        </div>
        <div class="lightbox-content col-3">
          <a
            href="./assets/img/3.jpg"
            data-lightbox="art"
            data-title="Tags: hahaha | hohoho | hehehe | hihi"
          >
            <img src="./assets/img/3.jpg" class="img-fluid" alt />
          </a>
          <p
            class="mt-2"
            style="color: white; font-family: 'Gelasio', cursive;"
          >Tags : haha | hihi | huhu | hehe</p>
        </div>
        <div class="lightbox-content col-3">
          <a
            href="./assets/img/4.jpg"
            data-lightbox="art"
            data-title="Tags: hahaha | hohoho | hehehe | hihi"
          >
            <img src="./assets/img/4.jpg" class="img-fluid" alt />
          </a>
          <p
            class="mt-2"
            style="color: white; font-family: 'Gelasio', cursive;"
          >Tags : haha | hihi | huhu | hehe</p>
        </div>
        <div class="lightbox-content col-3">
          <a
            href="./assets/img/5.jpg"
            data-lightbox="art"
            data-title="Tags: hahaha | hohoho | hehehe | hihi"
          >
            <img src="./assets/img/5.jpg" class="img-fluid" alt />
          </a>
          <p
            class="mt-2"
            style="color: white; font-family: 'Gelasio', cursive;"
          >Tags : haha | hihi | huhu | hehe</p>
        </div>
        <div class="lightbox-content col-3">
          <a
            href="./assets/img/6.jpg"
            data-lightbox="art"
            data-title="Tags: hahaha | hohoho | hehehe | hihi"
          >
            <img src="./assets/img/6.jpg" class="img-fluid" alt />
          </a>
          <p
            class="mt-2"
            style="color: white; font-family: 'Gelasio', cursive;"
          >Tags : haha | hihi | huhu | hehe</p>
        </div>
        <div class="lightbox-content col-3">
          <a
            href="./assets/img/7.jpg"
            data-lightbox="art"
            data-title="Tags: hahaha | hohoho | hehehe | hihi"
          >
            <img src="./assets/img/7.jpg" class="img-fluid" alt />
          </a>
          <p
            class="mt-2"
            style="color: white; font-family: 'Gelasio', cursive;"
          >Tags : haha | hihi | huhu | hehe</p>
        </div>
        <div class="lightbox-content col-3">
          <a
            href="./assets/img/8.jpg"
            data-lightbox="art"
            data-title="Tags: hahaha | hohoho | hehehe | hihi"
          >
            <img src="./assets/img/8.jpg" class="img-fluid" alt />
          </a>
          <p
            class="mt-2"
            style="color: white; font-family: 'Gelasio', cursive;"
          >Tags : haha | hihi | huhu | hehe</p>
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
  methods: {}
};
</script>

<style lang="css" scoped>
</style>