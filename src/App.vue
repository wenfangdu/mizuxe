<template>
  <div>
    <header>
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
    </header>
    <!-- showcase -->
    <section id="showcase">
      <div class="overlay overlay--primary text-white">
        <div class="container text-center">
          <h1 class="py-5 mt-5">
            So What You Dream Of ...
          </h1>
          <p class="lead">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Aliquid, officiis!</p>
          <a href="#" class="btn btn-outline-secondary btn-lg text-white">
            <i class="fa fa-arrow-right"></i>Read More
          </a>
        </div>
      </div>
    </section>
    <section id="newsletter" class="bg-dark text-white">
      <div class="container py-5">
        <form action="post">
          <input type="text" class="form-control form-control-lg mb-2" placeholder="Enter Name">
          <input type="text" class="form-control form-control-lg mb-2" placeholder="Enter Email">
          <button class="btn btn-primary btn-lg btn-block"><i class="fa fa-envelope-open-o"></i>Subscribe</button>
        </form>
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