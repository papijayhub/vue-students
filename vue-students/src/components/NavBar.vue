<template>
  <nav class="navbar navbar-expand-lg navbar-light" style="background-color: #e3f2fd;">
    <div class="container">
        <a class="navbar-brand" href="#">Shop Extreme</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav">
            <li class="nav-item">
                <router-link to="/" class="nav-link">Home</router-link>
            </li>
            <li class="nav-item">
                <router-link to="/about" class="nav-link">About</router-link>
            </li>
         
            <li class="nav-item">
                <router-link to="/shop" class="nav-link">Shop</router-link>
            </li>
            <li class="nav-item">
                <router-link to="/products" class="nav-link">Products</router-link>
            </li>
        </ul>
        </div>
    </div>
  </nav>
</template>

<script>
export default {

}
</script>

<style>

</style>