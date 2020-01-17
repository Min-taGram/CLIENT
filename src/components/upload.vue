<template>
  <section id="upload-image">
    <div class="container">
      <div class="row justify-content-center">
        <div class="card text-white bg-dark mb-3 text-center pb-3" style="max-width: 40%;">
          <div class="card-header">
            <span style="font-family: 'Playfair Display SC', serif">Upload Image</span>
          </div>
          <div class="card-body">
            <h5 class="card-title"></h5>
            <input type="text" class="form-control" placeholder="Input your tags here..." />
            <div class="custom-file">
              <input type="file" class="custom-file-input" id="customFile" />
              <label class="custom-file-label my-3" for="customFile">Choose pic</label>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style lang="css" scoped>
</style>