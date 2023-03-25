# web-perrosgatos
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.6.2/dist/css/bootstrap.min.css"
        integrity="sha384-xOolHFLEh07PJGoPkLv1IbcEPTNtaed2xpHsD9ESMhqIYd0nLMwNLD69Npy4HI+N" crossorigin="anonymous">
   


</head>


<body style="background-color: lightblue;">
<!-- Barra de navegación -->
<nav class="navbar navbar-expand-md navbar-light bg-light" >
    <a class="navbar-brand" href="#" >ADOPTAME</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav"
        aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation" >
        <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav" >
        <ul class="navbar-nav ml-auto" >
            <li class="nav-item">
                <a class="nav-link" href="#" style="color: black;">Inicio</a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="#" style="color: black;">Nosotros</a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="#" style="color: black;">Adopta</a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="#" style="color: black;">Colabora</a>
            </li>
            <li class="nav-item">
                <a class="nav-link"href="#" style="color: black;">Servicio</a>
            </li>
            <li class="nav-item">
                <a class="nav-link"href="#" style="color: black;">Contactanos</a>
            </li>
        </ul>
    </div>
</nav>


 <!-- Carrusel de imágenes -->
 <div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
    <ol class="carousel-indicators">
        <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
        <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
        <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
    </ol>

     <!-- Carrusel de imágenes 1 -->
    
     <div class="carousel-inner">
        <div class="carousel-item active">
            <img src="PERRO Y GATO.avif"width="600"height="800" class="d-block w-100" alt="Imagen 1">
            <div class="carousel-caption d-none d-md-block">
                <h5 style="color: black;">Adopta</h5>
                <p style="color: black;">¡Salva una vida!</p>
                <!-- Indicador -->
                <div id="indicadores">
                    <a href="#" class="activo">CLICK AQUI</a>
                </div>
                <!-- FIN Indicador -->
            </div>
        </div>

     <!-- Carrusel de imágenes 2 -->
        <div class="carousel-item">
            <img src="perroblanco.jpg" width="600"height="800"class="d-block w-100" alt="Imagen 2">
            <div class="carousel-caption d-none d-md-block">
                <h5 style="color: black;">Perros felices en su nuevo hogar</h5>
                <p style="color: black;">¡Ayuda a otros perros a encontrar su hogar ideal!</p>
                <!-- Indicador -->
                <div id="indicadores">
                    <a href="#" class="activo">CLICK AQUI</a>
                </div>
                 <!-- FIN Indicador -->
            </div>
        </div>

    <!-- Carrusel de imágenes 2 -->
        
        <div class="carousel-item">
            <img src="gatoblanco.avif"width="600"height="800" class="d-block w-100" alt="Imagen 3" >
            <div class="carousel-caption d-none d-md-block">
                <h5 style="color: black;">Adopta a tu nuevo mejor amigo</h5>
                <p style="color: black;">Hay muchos perros esperando por ti</p>
                <!-- Indicador -->
                <div id="indicadores">
                    <a href="#" class="activo">CLICK AQUI</a>
                </div>
                <!-- FIN Indicador -->
            </div>
        </div>
    </div>
    <a class="carousel-control-prev" href="#carouselExampleIndicators" role="button" data-slide="prev">
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="sr-only" >Anterior</span>
    </a>
    <a class="carousel-control-next" href="#carouselExampleIndicators" role="button" data-slide="next">
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="sr-only">Siguiente</span>
    </a>
</div>
        <!-- Pie de página -->
        <footer class="bg-light text-center py-3">
            <p>© 2023 Easy Web. Todos los derechos reservados.</p>
        
        </footer>
                
        <!-- Java Scrip-->
    <script src="https://cdn.jsdelivr.net/npm/jquery@3.5.1/dist/jquery.slim.min.js"
        integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj"
        crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.6.2/dist/js/bootstrap.bundle.min.js"
        integrity="sha384-Fy6S3B9q64WdZWQUiU+q4/2Lc9npb8tCaSX9FK7E8HnRr0Jz8D6OP9dO5Vg3Q9ct"
        crossorigin="anonymous"></script>

</body>
</html>
