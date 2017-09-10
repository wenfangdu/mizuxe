<template>
  <div>
    <nav class="navbar navbar-expand-sm navbar-light py-4">
      <div class="container">
        <a href="index.html" class="navbar-brand">
          <img src="./assets/img/mlogo.png" width="50" height="50" alt="mlogo">
          <h3 class="d-inline align-middle">BS2</h3>
        </a>
        <button class="navbar-toggler" data-toggle="collapse" data-target="#navbarNav">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav">
            <li class="nav-item">
              <a href="#about" class="nav-link">About</a>
            </li>
            <li class="nav-item">
              <a href="#authors" class="nav-link">Authors</a>
            </li>
            <li class="nav-item">
              <a href="#contact" class="nav-link">Contact</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
    <!-- showcase -->
    <section id="showcase">
      <div class="overlay overlay--primary text-white">

      </div>
    </section>
  </div>
</template>

<script>
  window.jQuery = require("jquery")
  window.Popper = require("popper.js").default
  require('bootstrap')

</script>

<style>
  @import "bootstrap";
  @import "assets/css/main.css";
</style>