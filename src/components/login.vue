<template>
   <div class="container">
         <div class="row">
            <div class="col-sm-9 col-md-7 col-lg-5 mx-auto my-auto">
               <div class="card card-signin my-5">
                  <div class="card-body">
                     <!-- bawah ini login -->
                     <div class="login">
                        <div class="logo text-center">
                           <h3 class="logo-sub">Peace, love, and gawl</h3>
                        </div>
                        <form class="form-signin">
                           <div class="form-label-group mb-4">
                              <input type="email" id="inputEmail" class="form-control" placeholder="Email address"
                                 required autofocus>
                              <!-- <label for="inputEmail">Email address</label> -->
                           </div>

                           <div class="form-label-group mb-4">
                              <input type="password" id="inputPassword" class="form-control" placeholder="Password"
                                 required>
                              <!-- <label for="inputPassword">Password</label> -->
                           </div>
                           <button type="button" class="btn btn-dark px-5 btn-block"
                              style="font-family: 'Playfair Display SC', serif;">Sign in</button>
                           <hr class="my-4">
                           <!-- <button class="btn btn-lg btn-danger btn-block" type="submit"><i
                                 class="fab fa-google mr-2"></i>
                              Sign in with Google</button> -->
                           <p class="text-center mt-4" style="cursor: pointer;">
                              Don't have an account yet? Click here to Register</p>
                        </form>
                     </div>
                     <!-- login sampai sini -->
                  </div>
               </div>
            </div>
         </div>
      </div>
</template>

<script>
export default {
  data() {
    return {
    };
  },
  methods: {
     
  }
};
</script>

<style lang="css" scoped>
</style>