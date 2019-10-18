<template>
  <div>
    <div class="container">
      <div class="row mt-4">
        <div class="col-md-12">
          <div class="container">
            <div class="row">
              <div class="col-md-4">
                <nuxt-link to="/">TACOX</nuxt-link>
              </div>
              <div class="col-md-8 pb-2 text-right">
                <nuxt-link to="/about" class="pr-3">About</nuxt-link>
                <nuxt-link to="/profile" class="pr-3">Profile</nuxt-link>
                <nuxt-link to="/login" class="pr-3">Login</nuxt-link>
                <nuxt-link to="/signup">Sign Up</nuxt-link>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- Search Input -->
    <div class="container">
      <div class="row py-2">
        <div class="col-md-12">
          <input type="text" placeholder="Search for a global Product or Service..." class="p-2 w-100" />
        </div>
      </div>
    </div>

    <nuxt />

    <div class="row">
      <div class="col-md-12 text-center pt-3">
        Footer © 2019
      </div>
    </div>
  </div>
</template>

<style></style>
