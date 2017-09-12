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
          <div class="row">
            <div class="col-lg-8">
              <h1 class="py-5 mt-5">
                So What You Dream Of ...
              </h1>
              <p class="lead">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Aliquid, officiis!</p>
              <a href="#" class="btn btn-outline-secondary btn-lg text-white">
                <i class="fa fa-arrow-right"></i>Read More
              </a>
            </div>
            <div class="col-lg-4">
              <img src="./assets/img/book.png" alt="book" class="img-fluid d-none d-lg-block">
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- newsletter section -->
    <section id="newsletter-section" class="bg-dark text-white">
      <div class="container py-5">
        <form action="post">
          <div class="row">
            <div class="col-md-4">
              <div class="form-group">
                <input type="text" class="form-control form-control-lg" placeholder="Enter Name">
              </div>
            </div>
            <div class="col-md-4">
              <div class="form-group">
                <input type="text" class="form-control form-control-lg" placeholder="Enter Email">
              </div>
            </div>
            <div class="col-md-4">
              <button class="btn btn-primary btn-lg btn-block"><i class="fa fa-envelope-open-o"></i> Subscribe</button>
            </div>
          </div>
        </form>
      </div>
    </section>
    <!-- boxes section -->
    <section id="boxes-section">
      <div class="container py-5">
        <div class="row">
          <div class="col-md-3">
            <div class="card text-center border-primary">
              <div class="card-body">
                <h3 class="text-primary">Be Better</h3>
                <p class="text-muted">Lorem ipsum dolor sit amet consectetur adipisicing elit. Ratione, corrupti?</p>
              </div>
            </div>
          </div>
          <div class="col-md-3">
            <div class="card text-center bg-primary text-white">
              <div class="card-body">
                <h3>Be Smarter</h3>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ratione, corrupti?</p>
              </div>
            </div>
          </div>
          <div class="col-md-3">
            <div class="card text-center border-primary">
              <div class="card-body">
                <h3 class="text-primary">Be Stronger</h3>
                <p class="text-muted">Lorem ipsum dolor sit amet consectetur adipisicing elit. Ratione, corrupti?</p>
              </div>
            </div>
          </div>
          <div class="col-md-3">
            <div class="card text-center bg-primary text-white">
              <div class="card-body">
                <h3>Be Faster</h3>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ratione, corrupti?</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- about section -->
    <section id="about-section" class="text-center bg-light ">
      <!-- info-header -->
      <div class="container py-5">
        <div class="info-header mb-5">
          <h1 class="text-primary pb-3">
            Why this book?
          </h1>
          <p class="lead pb-3">Lorem ipsum dolor sit amet consectetur adipisicing elit. Suscipit dolores quia amet numquam architecto dolore!</p>
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
                Fugiat nobis atque, odit assumenda veniam vitae nisi repellendus minus dolores unde reiciendis aspernatur
                saepe, doloribus, quam maiores necessitatibus delectus incidunt nostrum. Ea quo maiores, molestiae sequi
                velit neque porro inventore dolorem fugiat tenetur! Autem corrupti corporis quaerat magnam eligendi cumque,
                dicta rerum praesentium.
              </div>
            </div>
          </div>
          <div class="card">
            <div class="card-header">
              <h5 class="mb-0"><a href="#collapse2" data-toggle="collapse" data-parent="#accordion"><i class="fa fa-arrow-circle-down"> Gain The knowledge</i></a></h5>
            </div>
            <div id="collapse2" class="collapse">
              <div class="card-body">Lorem ipsum dolor sit amet consectetur adipisicing elit. Debitis ab doloremque ex? Nihil, ullam. Minima ducimus,
                hic sapiente fugiat assumenda laborum consequuntur, perspiciatis dolorem eos dolores deleniti vero error
                ex voluptatibus reiciendis consectetur, iure rem voluptas quidem nemo praesentium. Id illum deleniti itaque
                at atque ex quia molestiae, aspernatur nulla!</div>
            </div>
          </div>
          <div class="card">
            <div class="card-header">
              <h5 class="mb-0"><a href="#collapse3" data-toggle="collapse" data-parent="#accordion"><i class="fa fa-arrow-circle-down"> Open Your Mind</i></a></h5>
            </div>
            <div id="collapse3" class="collapse">
              <div class="card-body">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Enim officia iusto ex tempora sunt architecto ad
                veniam illum, temporibus esse iure molestiae pariatur, laudantium nulla in sequi dicta, quasi aliquid dolorum
                aspernatur doloremque nisi? Officiis architecto magni, velit laboriosam deserunt distinctio eius nihil nisi
                fugit commodi ipsa porro hic non veritatis adipisci voluptatem amet ducimus nulla recusandae nam odio? Qui!</div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- authors-section -->
    <section id="authors-section">
      <div class="container py-5 text-center">
        <!-- info-header -->
        <div class="info-header mb-5">
          <h1 class="text-primary mb-3">Meet The Authors</h1>
          <p class="lead mb-5">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ut doloribus iste veniam at architecto iusto, porro hic
            saepe adipisci aut pariatur blanditiis incidunt quo recusandae et tempora sit! Sequi, fugiat!</p>
        </div>
        <div class="row">
          <div class="col-lg-3 col-md-6">
            <!-- info-body -->
            <div class="card">
              <div class="card-body">
                <img src="./assets/img/person1.jpg" alt="Person 1" class="img-fluid rounded-circle w-50 mb-3">
                <h3>Susan Williams</h3>
                <h5 class="text-muted">Lead Writer</h5>
                <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Sapiente illum, asperiores quae recusandae vitae
                  blanditiis unde.
                </p>
                <div class="d-flex justify-content-center">
                  <div class="p-4">
                    <a href="#"><i class="fa fa-facebook"></i></a>
                  </div>
                  <div class="p-4">
                    <a href="#"><i class="fa fa-twitter"></i></a>
                  </div>
                  <div class="p-4">
                    <a href="#"><i class="fa fa-instagram"></i></a>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="col-lg-3 col-md-6">
            <div class="card">
              <div class="card-body">
                <img src="./assets/img/person2.jpg" alt="person 2" class="img-fluid rounded-circle w-50 mb-3">
                <h3>Grace Smith</h3>
                <h5 class="text-muted">Co-Writer</h5>
                <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Error, voluptatum.</p>
                <div class="d-flex justify-content-center">
                  <div class="p-4">
                    <a href="#"><i class="fa fa-facebook"></i></a>
                  </div>
                  <div class="p-4">
                    <a href="#"><i class="fa fa-twitter"></i></a>
                  </div>
                  <div class="p-4">
                    <a href="#"><i class="fa fa-instagram"></i></a>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="col-lg-3 col-md-6">
            <div class="card">
              <div class="card-body">
                <img src="./assets/img/person3.jpg" alt="person 2" class="img-fluid rounded-circle w-50 mb-3">
                <h3>Jane Doe</h3>
                <h5 class="text-muted">Editor</h5>
                <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Error, voluptatum.</p>
                <div class="d-flex justify-content-center">
                  <div class="p-4">
                    <a href="#"><i class="fa fa-facebook"></i></a>
                  </div>
                  <div class="p-4">
                    <a href="#"><i class="fa fa-twitter"></i></a>
                  </div>
                  <div class="p-4">
                    <a href="#"><i class="fa fa-instagram"></i></a>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="col-lg-3 col-md-6">
            <div class="card">
              <div class="card-body">
                <img src="./assets/img/person4.jpg" alt="person 2" class="img-fluid rounded-circle w-50 mb-3">
                <h3>Kevin Swanson</h3>
                <h5 class="text-muted ">Designer</h5>
                <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Error, voluptatum.</p>
                <div class="d-flex justify-content-center">
                  <div class="p-4">
                    <a href="#"><i class="fa fa-facebook"></i></a>
                  </div>
                  <div class="p-4">
                    <a href="#"><i class="fa fa-twitter"></i></a>
                  </div>
                  <div class="p-4">
                    <a href="#"><i class="fa fa-instagram"></i></a>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- contact section -->
    <section id="contact-section" class="bg-light py-5">
      <div class="container">
        <div class="row">
          <div class="col-lg-9">
            <h3>Get In Touch</h3>
            <p class="lead">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Libero, exercitationem?</p>
            <form action="post">
              <div class="form-group">
                <div class="input-group input-group-lg"><span class="input-group-addon"><i class="fa fa-user"></i></span>
                  <input type="text" class="form-control" placeholder="Name">
                </div>
              </div>
              <div class="form-group">
                <div class="input-group input-group-lg"><span class="input-group-addon"><i class="fa fa-envelope"></i></span>
                  <input type="email" name="email" id="email" class="form-control" placeholder="Email">
                </div>
              </div>
              <div class="form-group">
                <div class="input-group input-group-lg"><span class="input-group-addon"><i class="fa fa-pencil"></i></span>
                  <textarea name="msg" id="msg" class="form-control" cols="30" rows="5" placeholder="Message"></textarea>
                </div>
              </div>
              <button class="btn btn-primary btn-block btn-lg">Submit</button>
            </form>
          </div>
          <div class="col-lg-3 align-self-center d-none d-lg-block"><img src="./assets/img/mlogo.png" alt="mlogo" class="img-fluid"></div>
        </div>
      </div>
    </section>
    <!-- main footer -->
    <footer class="py-3 bg-primary text-white">
      <div class="container">
        <div class="text-center">
          <p class="lead"><strong>BS2</strong> Copyright &copy; 2017</p>
        </div>
      </div>
    </footer>
  </div>
</template>

<script>
  window.jQuery = require("jquery")
  window.Popper = require("popper.js").default
  require('bootstrap')
  const SmoothScroll = require("smooth-scroll")
  new SmoothScroll('a[href*="#"]')

</script>

<style>
  @import "bootstrap";
  @import "assets/css/main.css";
</style>