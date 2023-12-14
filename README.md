p<!DOCTYPE html>
<html lang="en">
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Document</title>
  <head>
    <!-- <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-T3c6CoIi6uLrA9TneNEoa7RxnatzjcDSCmG1MXxSR1GAsXEV/Dwwykc2MPK8M2HN" cros22sorigin="anonymous"></link> -->

    <link rel="stylesheet" href="./css/bootstrap.min.css" />
  </head>

  <body>
    <div class="container"></div>

    <script src="./js/bootstrap.min.js"></script>
    <nav class="navbar navbar-expand-lg bg-body-tertiary">
        <div class="container-fluid">
          <a class="navbar-brand" href="#">Café do Zé pica mole</a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav">
              <li class="nav-item">
                <a class="nav-link active" aria-current="page" href="#">Home</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">Cafés</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">Contatos</a>
              </li>
              <li class="nav-item">
                <a class="nav-link disabled" aria-disabled="true">Trabalhe Conosco</a>
              </li>
            </ul>
          </div>
        </div>
      </nav>
    <div id="carouselExampleCaptions" class="carousel carousel-dark slide">
        <div class="carousel-indicators">
          <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
          <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1" aria-label="Slide 2"></button>
          <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2" aria-label="Slide 3"></button>
        </div>
        <div class="carousel-inner">
          <div class="carousel-item active">
            <img src="img/cafe.jpg" class="d-block w-100" alt="...">
            <div class="carousel-caption d-none d-md-block bg-light">
              <h5>Cafeteria das amigas</h5>
              <p>Venha conhecer a nossa nova loja!!</p>
            </div>
          </div>
          <div class="carousel-item">
            <img src="img/cafeteria.jpg" class="d-block w-100" alt="...">
            <div class="carousel-caption d-none d-md-block bg-light">
              <h5>Ambiente Feliz!!</h5>
              <p>Apenas para o meu patrão</p>
            </div>
          </div>
          <div class="carousel-item">
            <img src="img/pexels-michaela-290975 (1).jpg" class="d-block w-100" alt="...">
            <div class="carousel-caption d-none d-md-block bg-light">
              <h5>Cafezinho de Qualidade!</h5>
              <p>(Ou não kkkk)</p>
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

        <div class="container text-center">
        
        <div class="row">
          <div class="col-sm-12 col-md-6 col-x1-4 col-lg-6 float-start p-5 ">
            <p class="fs-5 m-0"> Cofee das prima</p>
            <h4 class="display-6"> Melhor café da cidade</h4>
            <hr>
            <p class="fst-normal"> 

              Dentre todas as cafeterias de niterói, somos a mais querida.
            </p>
            <div id="carouselEsquerda" class="carousel slide carousel-fade">
              <div class="carousel-inner">
                <div class="carousel-item active">
                  <img src="img/divertindo1.jpg" class="d-block w-100" alt="...">
                </div>
                <div class="carousel-item">
                  <img src="img/divertindo2.jpg" class="d-block w-100" alt="...">
                </div>
                <div class="carousel-item">
                  <img src="img/divertindo3.jpg" class="d-block w-100" alt="...">
                </div>
              </div>
              <button class="carousel-control-prev" type="button" data-bs-target="#carouselEquerda" data-bs-slide="prev">
                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Previous</span>
              </button>
              <button class="carousel-control-next" type="button" data-bs-target="#carouselEsquerda" data-bs-slide="next">
                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Next</span>
              </button>
            </div>
          </div>

          <div class="col-sm-12 col-md-6 col-x1-4 col-lg-6 float-start p-5 ">
            <p class="fs-5 m-0"> Estamos de cara nova</p>
            <h4 class="display-6">Conheça nossa loja! </h4>
            <hr>
            <p class="fst-normal">

              Plazza Shopping Niterói. Loja 109 1º andar.
              
            </p>
            <div id="carouselDireita" class="carousel slide carousel-fade">
              <div class="carousel-inner">
                <div class="carousel-item active">
                  <img src="img/Plaza1.jpg" class="d-block w-100" alt="...">
                </div>
                <div class="carousel-item">
                  <img src="img/shopping2.jpg" class="d-block w-100" alt="...">
                </div>
                <div class="carousel-item">
                  <img src="img/shopping3.jpg" class="d-block w-100" alt="...">
                </div>
              </div>
              <button class="carousel-control-prev" type="button" data-bs-target="#carouselDireita" data-bs-slide="prev">
                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Previous</span>
              </button>
              <button class="carousel-control-next" type="button" data-bs-target="#carouselDireita" data-bs-slide="next">
                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Next</span>
              </button>
            </div>
          </div>
          
          <div class="col-sm-12 col-md-6 col-x1-4 ">
            <p></p>
            <p>.</p>
            <p>.</p>
          </div>
        </div>
      </div>
    
    </div>
  </body>
</html>
