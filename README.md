<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="./bootstrap-5.3.0-dist/css/bootstrap.min.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css"
        integrity="sha512-iecdLmaskl7CVkqkXNQ/ZH/XLlvWZOJyj7Yy7tcenmpD1ypASozpmT/E0iPtmFIB46ZmdtAc9eNBvH0H/ZpiBw=="
        crossorigin="anonymous" referrerpolicy="no-referrer" />
    <title>Document</title>
    <style>

        .carousel-caption {
    bottom: 1.25rem;
    padding-top: 1.25rem;
    color: #fff;
    text-align: right !important;
    width: 80% !important;
    
}
i {
    font-size: 30px;
}
.ready{
    background-image: linear-gradient(to top, rgba(0, 0, 0, 0.516), rgba(0, 0, 0, 0.507)), url("./img/lights.jpg");
            background-position: center;
            padding: 3%;
}
.do{
    background-image: linear-gradient(to top, rgba(0, 0, 0, 0.516), rgba(0, 0, 0, 0.507)), url("./img/media.jpg");
    background-position: center;
    padding: 1%;


}
.accordion-button , .accordion-item , .accordion-button:not(.collapsed) {
    background-color: black !important;
    color: #fff;
    width: 100%;
}
.carousel-control-next, .carousel-control-prev {
    width: auto !important;
}
.countainer{
    margin: auto 1%;

}

    </style>
</head>
<body>
    <nav class="navbar navbar-expand-lg bg-body-tertiary p-0 m-0">
        <div class="container-fluid bg-dark">
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
                <span class="bg-light navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
                <a class="nav-link text-light offset-1" href="#">GLOZZOM</a>

                <div class="navbar-nav offset-6">
                    <a class="nav-link active text-light" aria-current="page" href="#">Home</a>
                    <a class="nav-link text-light" href="#">ABOUT US</a>
                    <a class="nav-link text-light" href="#">Pricing</a>
                    <a class="nav-link text-light" href="#">Contact</a>
                </div>
            </div>
        </div>
    </nav>

    <div id="carouselExampleCaptions" class="carousel slide">
        <div class="carousel-indicators">
            <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
            <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1" aria-label="Slide 2"></button>
            <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2" aria-label="Slide 3"></button>
        </div>
        <div class="carousel-inner" style="height: 60vh !important;">
            <div class="carousel-item active h-100">
                <img class="w-100 d-block" src="./img/image1.jpg">
                <div class="carousel-caption d-none d-md-block">
                    <h2 class="display-3">Heading One </h2>
                    <p>
                        Lorem ipsum dolor sit, amet consectetur adipisicing elit. Ad sit ipsum quasi eaque labore! Reiciendis esse laboriosam ab alias soluta, minima amet debitis asperiores ea deserunt consequatur distinctio, ipsum obcaecati!
                    </p>
                    <button class="btn bg-danger text-light" data-bs-toggle="modal" data-bs-target="#exampleModal" data-bs-whatever="@getbootstrap">Sign up</button>
                </div>
            </div>
            <div class="carousel-item h-100">
                <img class="w-100 d-block" src="./img/image2.jpg">
                <div class="carousel-caption d-none d-md-block">
                    <h2 class="display-3">Heading Two </h2>
                    <p>
                        Lorem ipsum dolor sit, amet consectetur adipisicing elit. Ad sit ipsum quasi eaque labore! Reiciendis esse laboriosam ab alias soluta, minima amet debitis asperiores ea deserunt consequatur distinctio, ipsum obcaecati!
                    </p>
                    <button class="btn bg-danger text-light" data-bs-toggle="modal" data-bs-target="#exampleModal" data-bs-whatever="@getbootstrap">Sign up</button>
                </div>
            </div>
            <div class="carousel-item h-100">
                <img class="w-100 d-block" src="./img/image3.jpg">
                <div class="carousel-caption d-none d-md-block">
                    <h2 class="display-3">Heading Three</h2>
                    <p>
                        Lorem ipsum dolor sit, amet consectetur adipisicing elit. Ad sit ipsum quasi eaque labore! Reiciendis esse laboriosam ab alias soluta, minima amet debitis asperiores ea deserunt consequatur distinctio, ipsum obcaecati!
                    </p>
                    <button class="btn bg-danger text-light" data-bs-toggle="modal" data-bs-target="#exampleModal" data-bs-whatever="@getbootstrap">Sign up</button>
                </div>
            </div>
        </div>
        <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Previous</span>
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Next</span>
        </button>
    </div>
<div class="modal fade" id="exampleModal" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
  <div class="modal-dialog">
    <div class="modal-content">
      <div class="modal-header">
        <h1 class="modal-title fs-5" id="exampleModalLabel">New message</h1>
        <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
      </div>
      <div class="modal-body">
        <form>
          <div class="mb-3">
            <label for="E-mail" class="col-form-label">E-mail:</label>
            <input type="email" class="form-control" id="email">
          </div>
          <div class="mb-3">
            <label for="text" class="col-form-label">password:</label>
            <input type="password" class="form-control" id="password">
          </div>
        </form>
      </div>
      <div class="modal-footer">
        <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button>
        <button type="button" class="btn btn-primary">Send message</button>
      </div>
    </div>
  </div>
</div>
<div class="countainer">
    <div class="row align-items-center my-5 text-center" style="margin-left: 3%;">
        <div class="col-md-6 col-lg-3 col-m-6 offset-1">
            <i class="fa-solid fa-gear"></i>
            <h6>
                Turning Gears
            </h6>
            <p>
                Lorem ipsum dolor sit amet, consectetur adipisicing elit. Perferendis eum quae veniam, numquam
                necessitatibus cumque.
            </p>
        </div>
        <div class="col-md-6 col-lg-3 col-m-6">
            <i class="fa-solid fa-cloud"></i>
            <h6>
                Sending Data
            </h6>
            <p>
                Lorem ipsum dolor sit amet, consectetur adipisicing elit. Perferendis eum quae veniam, numquam
                necessitatibus cumque.
            </p>
        </div>
        <div class="col-md-6 col-lg-3 col-m-6">
            <i class="fa-solid fa-cart-plus"></i>
            <h6>
                Making Mony
            </h6>
            <p>
                Lorem ipsum dolor sit amet, consectetur adipisicing elit. Perferendis eum quae veniam, numquam
                necessitatibus cumque.
            </p>
        </div>
    </div>
</div>
    <div class="ready">
        <div class="countainer text-center text-light">
            <h2>
                Are you ready to get started
            </h2>
            <p>
                Lorem ipsum dolor sit amet, consectetur adipisicing elit. Sequi aperiam labore voluptates non earum dolorem perspiciatis accusantium officiis totam iste beatae modi
            </p>
        </div>
    </div>

    <div class="countainer offset-2">
        <div class="row align-items-center m-5">
            <div class="col-md-6 col-lg-5">
                <h6>
                    Lorem, ipsum.
                </h6>
                <p>
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Earum ipsam natus repudiandae? Et ratione hic sapiente aliquid quos perspiciatis, ut porro officiis est quae ab fuga provident omnis consequatur impedit?
                </p>
            </div>
            <div class="col-md-6 col-lg-5 ">
                <img class="w-100" src="./img/laptop.png">
            </div>
        </div>
        </div>
<div class="do">
        <div class="countainer text-center text-light">
            <i class="fa-solid fa-play" style="color: white;"></i>
            <h2>
                See What We DO
            </h2>
        </div>
        </div>

        <div class="countainer align-items-center text-center m-5">
            <h2>
                Photo Galary
            </h2>
            <p>
                check our photo
            </p>
            <div class="row align-items-center offset-2">
                <div class="col-md-5 col-lg-3 m-1">
                    <img class=" w-100 h-100"  src="./photo-1685893181722-2dbebbb399c9.jpg">
            </div>
            <div class="col-md-5 col-lg-3 m-1">
                <img class=" w-100 h-100"  src="./premium_photo-1673795752049-a71fbdd313fe.jpg">
            </div>
            <div class="col-md-5 col-lg-3 m-1">
                <img class=" w-100 h-100"  src="./photo-1689181304449-41c7d134b82f.jpg">
            </div>
            <div class="col-md-5 col-lg-3 m-1">
                 <img class=" w-100 h-100"  src="./4.jpg">
            </div>
            <div class="col-md-5 col-lg-3 m-1">
                <img class=" w-100 h-100"  src="./5.jpg">
            </div>
            <div class="col-md-5 col-lg-3 m-1">
                <img class=" w-100 h-100"  src="./6.jpg">
            </div>
            </div>
        </div>

        <div class="consequatur bg-dark text-light text-center mb-0">
            <h2>
                Frequantly Asked Questions
            </h2>
            <div class="row align-items-center m-5 text-center mb-0">
                <div class="col-md-11 col-lg-6">

            <div class="accordion accordion-flush" id="accordionFlushExample">
                <div class="accordion-item bg-dark text-light">
                  <h2 class="accordion-header">
                    <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#flush-collapseOne" aria-expanded="false" aria-controls="flush-collapseOne ">
                      Accordion Item #1
                    </button>
                  </h2>
                  <div id="flush-collapseOne" class="accordion-collapse collapse" data-bs-parent="#accordionFlushExample ">
                    <div class="accordion-body">Placeholder content for this accordion, which is intended to demonstrate the <code>.accordion-flush</code> class. This is the first item's accordion body.</div>
                  </div>
                </div>
                <div class="accordion-item">
                  <h2 class="accordion-header">
                    <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#flush-collapseTwo" aria-expanded="false" aria-controls="flush-collapseTwo">
                      Accordion Item #2
                    </button>
                  </h2>
                  <div id="flush-collapseTwo" class="accordion-collapse collapse" data-bs-parent="#accordionFlushExample">
                    <div class="accordion-body">Placeholder content for this accordion, which is intended to demonstrate the <code>.accordion-flush</code> class. This is the second item's accordion body. Let's imagine this being filled with some actual content.</div>
                  </div>
                </div>
                <div class="accordion-item">
                  <h2 class="accordion-header">
                    <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#flush-collapseThree" aria-expanded="false" aria-controls="flush-collapseThree">
                      Accordion Item #3
                    </button>
                  </h2>
                  <div id="flush-collapseThree" class="accordion-collapse collapse" data-bs-parent="#accordionFlushExample">
                    <div class="accordion-body">Placeholder content for this accordion, which is intended to demonstrate the <code>.accordion-flush</code> class. This is the third item's accordion body. Nothing more exciting happening here in terms of content, but just filling up the space to make it look, at least at first glance, a bit more representative of how this would look in a real-world application.</div>
                  </div>
                </div>
              </div>
              </div>

              <div class="col-md-11 col-lg-6">

                <div class="accordion accordion-flush" id="accordionFlushExample">
                    <div class="accordion-item bg-dark text-light">
                      <h2 class="accordion-header">
                        <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#flush-collapse4" aria-expanded="false" aria-controls="flush-collapse4 ">
                          Accordion Item #4
                        </button>
                      </h2>
                      <div id="flush-collapse4" class="accordion-collapse collapse" data-bs-parent="#accordionFlushExample ">
                        <div class="accordion-body">Placeholder content for this accordion, which is intended to demonstrate the <code>.accordion-flush</code> class. This is the first item's accordion body.</div>
                      </div>
                    </div>
                    <div class="accordion-item">
                      <h2 class="accordion-header">
                        <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#flush-collapse5" aria-expanded="false" aria-controls="flush-collapse5">
                          Accordion Item #5
                        </button>
                      </h2>
                      <div id="flush-collapse5" class="accordion-collapse collapse" data-bs-parent="#accordionFlushExample">
                        <div class="accordion-body">Placeholder content for this accordion, which is intended to demonstrate the <code>.accordion-flush</code> class. This is the second item's accordion body. Let's imagine this being filled with some actual content.</div>
                      </div>
                    </div>
                    <div class="accordion-item">
                      <h2 class="accordion-header">
                        <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#flush-collapse6" aria-expanded="false" aria-controls="flush-collapse6">
                          Accordion Item #6
                        </button>
                      </h2>
                      <div id="flush-collapse6" class="accordion-collapse collapse" data-bs-parent="#accordionFlushExample">
                        <div class="accordion-body">Placeholder content for this accordion, which is intended to demonstrate the <code>.accordion-flush</code> class. This is the third item's accordion body. Nothing more exciting happening here in terms of content, but just filling up the space to make it look, at least at first glance, a bit more representative of how this would look in a real-world application.</div>
                      </div>
                    </div>
                  </div>
                  </div>
</div>
        </div>
    <script src="./bootstrap-5.3.0-dist/js/bootstrap.bundle.js"></script>
</body>
</html>
