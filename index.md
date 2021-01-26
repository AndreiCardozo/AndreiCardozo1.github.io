<!DOCTYPE html>
<html>

<head>
  <title>Bootstrap</title>

  <!-- define a viewport -->
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <!-- adicionar CSS Bootstrap -->
  <link href="bootstrap.min.css" rel="stylesheet" media="screen">

  <!-- css personalizado -->
  <link href="estilo.css" rel="stylesheet" media="screen">
</head>

<body data-spy="scroll" data-target="#navbar-example" data-offset="80">

  <!--cabeçalho da aplicação-->
  <nav id="navbar-example" class="navbar fixed-top navbar-expand-lg navbar navbar-dark bg-primary"">

    <a class=" navbar-brand" href="#">Logomarca</a>

    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent"
      aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mr-auto">
        <li class="nav-item active">
          <a class="nav-link" href="#servico">Serviços <span class="sr-only">(current)</span></a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#portifolio">Portifólio</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#quemsomos">Quem Somos</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#localizacao">Localização</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#contato">Contato</a>
        </li>

      </ul>
      <form class="form-inline my-2 my-lg-0">
        <input class="form-control mr-sm-2" type="search" placeholder="Buscar" aria-label="Search">
        <button class="btn btn-outline-success my-2 my-sm-0" type="submit">OK</button>
      </form>
    </div>
  </nav>
  <!--slider-->
  <div class="divslider">
    <div class="container dvslider">
      <div class="col-12">

        <div id="carouselExampleIndicators" class="carousel slide " data-ride="carousel">
          <ol class="carousel-indicators">
            <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
            <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
            <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
          </ol>
          <div class="carousel-inner">

            <div class="carousel-item active">
              <img src="foto1.jpg" class="d-block w-100" alt="...">
            </div>

            <div class="carousel-item">
              <img src="slider2.jpg" class="d-block w-100" alt="...">
            </div>

            <div class="carousel-item">
              <img src="slider3.jpg" class="d-block w-100" alt="...">
            </div>

          </div>
          <a class="carousel-control-prev" href="#carouselExampleIndicators" role="button" data-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="sr-only">Anterior</span>
          </a>
          <a class="carousel-control-next" href="#carouselExampleIndicators" role="button" data-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="sr-only">Próximo</span>
          </a>
        </div>


      </div>

    </div>
  </div>
  <!--Corpo da Aplicação-->

  <!--Serviços-->

  <section id=servico>
    <div class="container">
      <div class="col-12">
        <div class="page-header">
          <h1>SERVIÇOS <small>Conheça o que fazemos</small></h1>
        </div>
      </div>
    </div>

    <br>
    <br>
    <br>
    <br>

    <div class="container">
      <div class="row">
        <div class="col-12 col-sm-3 col-md-3 col-lg-3">
          <img src="imagem01.jpg" class="img-fluid img-thumbnail" alt="Quadro cinza escrito imagem 1">
          <div class="Caption">
            <h4>Titulo da Imagem</h4>
            <p> breve descrição da imagem</p>
            <p><a href="#" class="btn btn-primary">Mais detalhes</a></p>
          </div>
        </div>

        <div class="col-12 col-sm-3 col-md-3 col-lg-3">
          <img src="imagem01.jpg" class="img-fluid img-thumbnail" alt="Quadro cinza escrito imagem 1">
          <div class="Caption">
            <h4>Titulo da Imagem</h4>
            <p> breve descrição da imagem</p>
            <p><a href="#" class="btn btn-primary">Mais detalhes</a></p>
          </div>
        </div>

        <div class="col-12 col-sm-3 col-md-3 col-lg-3">
          <img src="imagem01.jpg" class="img-fluid img-thumbnail" alt="Quadro cinza escrito imagem 1">
          <div class="Caption">
            <h4>Titulo da Imagem</h4>
            <p> breve descrição da imagem</p>
            <p><a href="#" class="btn btn-primary">Mais detalhes</a></p>
          </div>
        </div>

        <div class="col-12 col-sm-3 col-md-3 col-lg-3">
          <img src="imagem01.jpg" class="img-fluid img-thumbnail" alt="Quadro cinza escrito imagem 1">
          <div class="Caption">
            <h4>Titulo da Imagem</h4>
            <p> breve descrição da imagem</p>
            <p><a href="#" class="btn btn-primary">Mais detalhes</a></p>
          </div>
        </div>
      </div>

    </div>


  </section>




  <!-- // serviços -->

  <!--Portifolio-->
  <div class="divslider">
    <section id=portifolio>
      <div class="container">
        <div class="col-12">
          <div class="page-header">
            <h1>PORTIFÓLIO <small>Conheça nossos Trabalhos</small></h1>
          </div>
        </div>
      </div>
    </section>
  </div>





  <!--Quem Somos-->

  <section id=quemsomos>

    <div class="container">
      <div class="col-12">
        <div class="page-header">
          <h1>QUEM SOMOS <small>Conheça nossa História</small></h1>
        </div>
      </div>
    </div>
  </section>


  <!--Localização-->
  <section id="localizacao" class="div_colorida">
    <div class="container">
      <div class="row">
        <div class="col-12">
          <div class="page-header">
            <h1>Localização <small>Veja onde estamos</small></h1>
          </div>
        </div>
      </div>

      <div class="row">
        <div class="col-12 col-md-12 col-lg-12">
          <iframe
            src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3705.567832672844!2d-43.352285785103845!3d-21.758273885607768!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x989c9f379a70b3%3A0xa1f86150ab90b108!2sSolutech%20Sistemas!5e0!3m2!1spt-BR!2sbr!4v1600370526115!5m2!1spt-BR!2sbr"
            width="100%" height="520" frameborder="0" style="border:0;" allowfullscreen="" aria-hidden="false"
            tabindex="0"></iframe>
        </div>
      </div>
    </div>
  </section>


  <!-- // localização -->

  <!-- contato -->

  <section id="contato">
    <div class="container">
      <div class="row">
        <div class="col-12 col-md-12">
          <div class="page-header">
            <h1>Contato <small>Fale conosco agora mesmo!</small></h1>
          </div>
        </div>
      </div>
      <br>
      <br>
      <div class="row contato">
        <div class="col-12 col-md-12">
          <p class="bg-success aviso">Preencha o formulário abaixo para entrar em contato conosco!</p>
        </div>
      </div>

      <div class="row contato">
        <div class="col-12">

          <form name="frmContato" id="formContato">
            <div class="row">
              <div class="col-md-6">

                <div class="form-group">
                  <input type="text" class="form-control input-lg" placeholder="Qual seu nome? *" required />
                </div>

                <div class="form-group">
                  <input type="email" class="form-control input-lg" placeholder="Qual seu e-mail? *" required />
                </div>

                <div class="form-group">
                  <input type="tel" class="form-control input-lg" placeholder="Seu telefone?" />
                </div>

              </div>
              <div class="col-md-6">
                <textarea class="form-control input-lg" placeholder="Sua mensagem! *" required></textarea>
              </div>
            </div>
            <div class="row">
              <div class="col-sm-6">
                <div class="alert alert-success">Envio realizado!</div>
              </div>
              <div class="col-sm-6">
                <button type="submit" class="btn btn-success btn-lg">Enviar Formulário</button>
              </div>
            </div>
          </form>

        </div>
      </div>
    </div>
  </section>
  <!-- // contato -->

  <footer>
    <div class="container">
      <div class="row">
        <div class="col-sm-10">
          Informações gerais sobre a empresa, endereço, e-mail e etc!
        </div>
        <div class="col-sm-2 text-right">
          <small>Desenvolvido por:</small><br />
          <strong>Andrei Cardozo</strong>
        </div>
      </div>
    </div>
  </footer>


  <script src="jquery-3.5.1.min.js"></script>
  <script src=bootstrap.min.js"></script>
  <script src="main.js"></script>
</body>

</html>
