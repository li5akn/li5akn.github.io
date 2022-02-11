# li5akn.github.io
<!DOCTYPE html>
<html lang="en">
<head>

    <meta charset="UTF-8">    
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <script src="https://kit.fontawesome.com/cb7a1c7ec9.js" crossorigin="anonymous"></script>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">
    <script src="https://ajax.googleapis.com/ajax/libs/cesiumjs/1.78/Build/Cesium/Cesium.js"></script>
    <link rel="stylesheet" type="text/css" href="css/capstone.css">
    <title>Lisas Kitchen</title>

</head>

<body>
    <header>
        <h1>Lisa's Kitchen</h1>
    </header>

<!-- Carousel -->
<div id="demo" class="carousel slide" data-bs-ride="carousel" data-bs-interval="false">

    <!-- Indicators/dots -->
    <div class="carousel-indicators">
      <button type="button" data-bs-target="#demo" data-bs-slide-to="0" class="active"></button>
      <button type="button" data-bs-target="#demo" data-bs-slide-to="1"></button>
      <button type="button" data-bs-target="#demo" data-bs-slide-to="2"></button>
    </div>
    
    <!-- The slideshow/carousel -->
    <div class="carousel-inner">
      <div class="carousel-item active">
        <img src="imgs/slide_food.jpg" alt="dishes" class="d-block" style="width:100%">
        <div class="carousel-caption">
        </div>
      </div>
      <div class="carousel-item">
        <img src="imgs/slide_breads.jpg" alt="bread" class="d-block" style="width:100%">
        <div class="carousel-caption">
       </div> 
      </div>
      <div class="carousel-item">
        <img src="imgs/slide_sweets.jpg" alt="sweets and cakes" class="d-block" style="width:100%">
        <div class="carousel-caption">
        </div>  
      </div>
    </div>
    
    <!-- Left and right controls/icons -->
    <button class="carousel-control-prev" type="button" data-bs-target="#demo" data-bs-slide="prev">
      <span class="carousel-control-prev-icon"></span>
    </button>
    <button class="carousel-control-next" type="button" data-bs-target="#demo" data-bs-slide="next">
      <span class="carousel-control-next-icon"></span>
    </button>
</div>

<!--navbar-->
<nav class="navbar navbar-expand-lg navbar-dark bg-dark">
  <div class="container-fluid">
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav me-auto mb-2 mb-lg-0">
        <li class="nav-item">
          <a class="nav-link active" aria-current="page" href="index.html">Home</a>
        </li>
        <li class="nav-item dropdown">
          <a class="nav-link dropdown-toggle" id="navbarDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
            Foods
          </a>
          <ul class="dropdown-menu dropdown-menu-dark" aria-labelledby="navbarDropdown">
            <li><a class="dropdown-item" href="dishes.html">Dishes</a></li>
            <li><a class="dropdown-item" href="sweets.html">Sweets & Cakes</a></li>
            <li><a class="dropdown-item" href="bread.html">Breads & Side Dishes</a></li>
          </ul>
          <li class="nav-item">
            <a class="nav-link" href="contact.html">Contact</a>
          </li>
        </ul>
    </div>
  </div>
</nav>

<div class="container-fluid container mt-3">
    <div class="row">

<main class="col-9 d-inline-block col-md-10">
    <h2>Welcome</h2>
    <p>Hi, I'am Lisa and I love food, just like most people. 
      Since I was child I also loved cooking.
      When the covid pandemic hit, I started baking as well. I learned it from going to some online classes.<br>
      Last months I learnd something complete different too: HTML and CSS Coding. Now I'm trying to combine those two hobbies. I wanna show you some of my favorite food creations on the first homepage I've made. But beware! If you're looking for healthy stuff you're totally wrong on this page.
      Hope you enjoy and may find some inspiration.</p>
</main>  

<figure class="col-3 d-inline-block col-md-2"> 
    <img src="imgs/lisa2.jpg" alt="Lisa" id="picLisa" class="img-fluid">
    <figcaption>Summer 2021</figcaption>
</figure>

    </div>
</div>

    <footer>- LisaKn / 2022 -</footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" crossorigin="anonymous"></script>

</body>

</html>
