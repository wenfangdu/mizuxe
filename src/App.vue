<template>
  <div>
    <!-- main header -->
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
                <a href="#about-section" class="nav-link">About</a>
              </li>
              <li class="nav-item">
                <a href="#authors-section" class="nav-link">Authors</a>
              </li>
              <li class="nav-item">
                <a href="#contact-section" class="nav-link">Contact</a>
              </li>
            </ul>
          </div>
        </div>
      </nav>
    </header>
    <!-- showcase section-->
    <section id="showcase-section">
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
    <!-- newsletter section -->
    <section id="newsletter-section" class="bg-dark text-white">
      <div class="container py-5">
        <form action="post">
          <div class="form-group">
            <input type="text" class="form-control form-control-lg" placeholder="Enter Name">
          </div>
          <div class="form-group">
            <input type="text" class="form-control form-control-lg" placeholder="Enter Email">
          </div>
          <button class="btn btn-primary btn-lg btn-block"><i class="fa fa-envelope-open-o"></i>Subscribe</button>
        </form>
      </div>
    </section>
    <!-- boxes section -->
    <section id="boxes-section">
      <div class="container py-5">
        <div class="card text-center border-primary">
          <div class="card-body">
            <h3 class="text-primary">Be Better</h3>
            <p class="text-muted">Lorem ipsum dolor sit amet consectetur adipisicing elit. Ratione, corrupti?</p>
          </div>
        </div>
        <div class="card text-center bg-primary text-white">
          <div class="card-body">
            <h3>Be Smarter</h3>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ratione, corrupti?</p>
          </div>
        </div>
        <div class="card text-center border-primary">
          <div class="card-body">
            <h3 class="text-primary">Be Stronger</h3>
            <p class="text-muted">Lorem ipsum dolor sit amet consectetur adipisicing elit. Ratione, corrupti?</p>
          </div>
        </div>
        <div class="card text-center bg-primary text-white">
          <div class="card-body">
            <h3>Be Faster</h3>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ratione, corrupti?</p>
          </div>
        </div>
      </div>
    </section>
    <!-- about section -->
    <section id="about" class="text-center bg-light">
      <!-- info-header -->
      <div class="container py-5">
        <div class="info-header mb-5">
          <h1 class="text-primary pb-3">
            Why this book?
          </h1>
          <p class="lead pb-3">Lorem ipsum dolor sit amet consectetur adipisicing elit. Suscipit dolores quia amet numquam architecto dolore!</p>
        </div>
      </div>
      <!-- accordion -->
      <div id="accordion">
        <div class="card">
          <div class="card-header">
            <h5 class="mb-0">
              <a href="#collapse1" data-toggle="collapse" data-parent="#accordion">
              <i class="fa fa-arrow-circle-down"> Get Inspired</i>
              </a>
            </h5>
          </div>
          <div id="collapse1" class="collapse show">
            <div class="card-body">Lorem ipsum dolor sit amet consectetur adipisicing elit. Dicta rerum expedita ut cumque asperiores sint quod.
              Fugiat nobis atque, odit assumenda veniam vitae nisi repellendus minus dolores unde reiciendis aspernatur saepe,
              doloribus, quam maiores necessitatibus delectus incidunt nostrum. Ea quo maiores, molestiae sequi velit neque
              porro inventore dolorem fugiat tenetur! Autem corrupti corporis quaerat magnam eligendi cumque, dicta rerum
              praesentium.
            </div>
          </div>
        </div>
        <div class="card">
          <div class="card-header">
            <h5 class="mb-0"><a href="#collapse2" data-toggle="collapse" data-parent="#accordion"><i class="fa fa-arrow-circle-down"> Gain The knowledge</i></a></h5>
          </div>
          <div id="collapse2" class="collapse">
            <div class="card-body">Lorem ipsum dolor sit amet consectetur adipisicing elit. Debitis ab doloremque ex? Nihil, ullam. Minima ducimus,
              hic sapiente fugiat assumenda laborum consequuntur, perspiciatis dolorem eos dolores deleniti vero error ex
              voluptatibus reiciendis consectetur, iure rem voluptas quidem nemo praesentium. Id illum deleniti itaque at
              atque ex quia molestiae, aspernatur nulla!</div>
          </div>
        </div>
        <div class="card">
          <div class="card-header">
            <h5 class="mb-0"><a href="#collapse3" data-toggle="collapse" data-parent="#accordion"><i class="fa fa-arrow-circle-down"> Open Your Mind</i></a></h5>
          </div>
          <div id="collapse3" class="collapse">
            <div class="card-body">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Enim officia iusto ex tempora sunt architecto ad veniam
              illum, temporibus esse iure molestiae pariatur, laudantium nulla in sequi dicta, quasi aliquid dolorum aspernatur
              doloremque nisi? Officiis architecto magni, velit laboriosam deserunt distinctio eius nihil nisi fugit commodi
              ipsa porro hic non veritatis adipisci voluptatem amet ducimus nulla recusandae nam odio? Qui!</div>
          </div>
        </div>
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