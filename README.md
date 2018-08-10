<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <!--Import Google Icon Font-->
    <link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">
    <!-- Compiled and minified CSS -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/materialize/1.0.0-rc.2/css/materialize.min.css">
    <title>Components</title>
</head>
<body style= "background-image: url('https://cdnb.artstation.com/p/assets/images/images/001/689/777/large/peter-gregory-15-12-23-star-wars.jpg?1450930242');background-attachment: fixed;">

<!--Navbar-->

<div class="navbar-fixed">
<nav class="deep-purple darken-4">

    <div class="nav-wrapper container">
        <a href="#" class="brand-logo right">Logo Corporativo</a>
        <a href="#" data-target="menu-r" class="sidenav-trigger">
                <i class="material-icons">menu</i>
        </a>
        <ul class="left hide-on-med-and-down">
            <li><a href="#Buttons">Buttons</a></li>
            <li><a href="#Cards">Cards</a></li>
            <li><a href="#Carousel">Carousel</a></li>
            <li>
                <a href="#" class="dropdown-trigger" data-target="drop">dropdown <i class="material-icons right">arrow_drop_down</i></a>
            </li>
        </ul>
    </div>


</nav>
</div>

<ul class="sidenav" id="menu-r">
    <li><a href="#Buttons">Buttons</a></li>
    <li class="divider"></li>
    <li><a href="#Cards">Cards</a></li>
    <li class="divider"></li>
    <li><a href="#">Enlace</a></li>
    <li class="divider"></li>
    <li><a href="">Enlace dropdown</a></li>
    <li class="divider"></li>
    <li><a href="">Enlace dropdown</a></li>
    <li class="divider"></li>
    <li><a href="">Enlace dropdown</a></li>
</ul>

<ul id="drop" class="dropdown-content">
    <li><a href="#Material-Box">Material Box</a></li>
    <li class="divider"></li>
    <li><a href="#">Enlace</a></li>
    <li class="divider"></li>
    <li><a href="#">Enlace</a></li>
</ul>
<!--Navbar End-->

<!-- Sidenav -->


    <a href="#" class="sidenav-trigger" data-target="menu-side">
        <i class="material-icons white-text">menu</i>
    </a>
<ul class="sidenav" id="menu-side">
    <li>
        <div class="user-view">
            <div class="background">
            <img src="https://images.pexels.com/photos/374844/pexels-photo-374844.jpeg?auto=compress&cs=tinysrgb&h=350" alt="">
            </div>
            <a href="#">
                <img src="https://images.pexels.com/photos/326875/pexels-photo-326875.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260" alt="" class="circle">
            </a>
            <a href=""><span class="name grey-text">Moisés</span></a>
            <a href="">
                <spam class="email white-text">moises@gmail.com</spam>
            </a>
        </div>
    </li>
    <li>
        <a href="">
        <i class="material-icons">cloud</i>
        Elemento 1</a>
    </li>
    <li>
        <div class="divider"></div>
    </li>
    <li>
        <a href="">
        <i class="material-icons">cloud</i>
        Elemento 2</a>
    </li>
    <li>
        <a href="">
            <i class="material-icons">cloud</i>
            Elemento 3</a>
    </li>
</ul>
</div>

<!-- Sidenav End -->

<div class="container blue-grey lighten-5" id="Buttons">

<!--Buttons-->

<h1 class="grey-text text-lighten-5 center light-blue lighten-1">Buttons</h1>

<div class="section">
    <button class="btn">Boton 1</button>
    <a href="#" class="btn">Boton 2</a>
    <button class="btn-flat">Boton 3</button>
</div>

<br>

<div class="section">
    <button class="btn blue darken-3">Boton 4</button>
    <a href="#" class="btn light-blue lighten-3">Boton 5</a>
</div>

<br>

<div class="section">
    <button class="btn-large light-green lighten-2">Boton 6</button>
    <a href="#" class="btn-small lime darken-1">Boton 7</a>
    <a href="#" class="btn lime darken-4">Boton 8</a>
    <a href="#" class="btn disabled teal darken-1">Boton 9</a>
</div>

<br>

<div class="section">
    <button class="btn waves-effect waves-light cyan darken-2">Boton 10</button>
    <a href="#" class="btn waves-effect waves-purple teal darken-2">Boton 11</a>
</div>

<br>

<div class="section">
    <button class="btn waves-effect waves-light red lighten-1">
        <i class="material-icons left">android</i>
    Boton 12
    </button>
    <a href="#" class="btn waves-effect waves-yellow red accent-4">
        <i class="material-icons right">delete_outline</i>
        Boton 13
    </a>
</div>

<br>

<div class="section">
    <a class="btn-floating btn-large waves-effect waves-light red">
        <i class="material-icons">add</i>
    </a>
</div>

<!--buttons End-->
</div>

<br>

<div class="container cyan lighten-5" id="Cards">

    <!--Cards-->
<h1 class=" saction grey-text text-lighten-5 center light-blue lighten-1">Cards</h1>

<div class="row">

    <div class="col s4">
        <div class="card">
            <div class="card-content">
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Tempore ipsum quidem facere, soluta ab consequuntur! Eligendi neque porro molestias necessitatibus.</p>
            </div>
        </div>
    </div>

    <div class="col s4">
        <div class="card teal darken-4">
            <div class="card-content white-text">
                <span class="card-title">Lorem, ipsum dolor.</span>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Modi molestiae et sunt ipsam ea libero! Sapiente hic accusamus sunt quaerat.</p>
            </div>
        </div>
    </div>

    <div class="col s4">
        <div class="card">
            <div class="card-title center">Lorem, ipsum dolor.</div>
            <div class="card-content">
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ratione nisi voluptatibus, officiis voluptas aliquam explicabo.</p>
            </div>
            <div class="card-action">
                <a href="#">Enlace</a>
                <a href="#">Enlace</a>
            </div>
        </div>
    </div>

    <div class="col s4">
        <div class="card">
            <div class="card-image">
                <img class="responsive-img" src="https://imgcp.aacdn.jp/img-a/1720/auto/global-aaj-front/article/2017/06/595048184fa06_5950474045019_1189093891.jpg" alt="">
            </div>
            <div class="card-content">
                <span class="card-title">Lorem, ipsum dolor.</span>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Corrupti, amet.</p>
            </div>
            <div class="card-action">
                <a href="#">Enlace</a>
                <a href="#">Enlace</a>
            </div>
        </div>
    </div>

    <div class="col s4">
        <div class="card">
            <div class="card-image">
                <img class="responsive-img" src="https://images.pexels.com/photos/1303640/pexels-photo-1303640.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260" alt="">
                <span class="card-title  white-text">Lorem, ipsum dolor.</span>
            </div>
            <div class="card-content">
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Corrupti, amet.</p>
            </div>
            <div class="card-action">
                <a href="#">Enlace</a>
                <a href="#">Enlace</a>
            </div>
        </div>
    </div>

    <div class="col s4">
        <div class="card">
            <div class="card-image">
                <img src="https://images.pexels.com/photos/788193/pexels-photo-788193.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260" alt="">
                <span class="card-title">Lorem, ipsum dolor.</span>
                <a class="btn-floating halfway-fab waves-effect waves-light blue darken-3">
                    <i class="material-icons">add</i>
                </a>
            </div>
            <div class="card-content">
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ipsa magnam repellat dolores minus labore perferendis.</p>
            </div>
            <div class="card-action">
                <a href="#">Enlace</a>
                <a href="#">Enlace</a>
            </div>
        </div>
    </div>

    <div class="col s12">
    <div class="card horizontal">
        <div class="card-image">
            <img src="https://images.pexels.com/photos/638412/pexels-photo-638412.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260" alt="">
            <span class="card-title">Lorem, ipsum dolor.</span>
        </div>
    <div class="card-stacked">
        <div class="card-content">
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Expedita non eum hic corrupti? Eaque totam iste voluptatem omnis sit quas beatae voluptates quia, cumque voluptatibus temporibus nobis, quisquam quos possimus, quae repellat ab tenetur ratione. Magni iusto nobis facere accusantium?</p>
        </div>
        <div class="card-action">
            <a href="#">Enlace</a>
            <a href="#">Enlace</a>
        </div>
    </div>
    </div>
    </div>

    <div class="col s4">
        <div class="card">
            <div class="card-image waves-effect waves-block waves-green">
                <img class="activator" src="https://images.pexels.com/photos/923548/pexels-photo-923548.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260" alt="">
            </div>
        <div class="card-content">
            <span class="card-title activator">Lorem, ipsum dolor.
                    <i class="material-icons right">more_vert</i>
            </span>
        </div>
            <div class="card-reveal">
                    <span class="card-title grey-text text-darken-4">Card Title<i class="material-icons right">close</i></span>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Animi dignissimos incidunt quidem temporibus voluptatem doloremque.</p>
            </div>
        </div>
    </div>

    <div class="col s4">
            <div class="card">
                <div class="card-image waves-effect waves-block waves-green">
                    <img class="activator" src="https://images.pexels.com/photos/923548/pexels-photo-923548.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260" alt="">
                </div>
            <div class="card-content">
                <span class="card-title activator">Lorem, ipsum dolor.
                        <i class="material-icons right">more_vert</i>
                </span>
            </div>
            <div class="card sticky-action">
                <div class="card-action">
                <a href="#">Enlace</a>
                <a href="#">Enlace</a>
            </div>
            </div>
                <div class="card-reveal">
                    <span class="card-title grey-text text-darken-4">Card Title<i class="material-icons right">close</i></span>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Animi dignissimos incidunt quidem temporibus voluptatem doloremque.</p>
                </div>

        </div>
    </div>

</div>

<h1 class=" section grey-text text-lighten-5 center light-blue lighten-1">Tabs in Cards</h1>

<div class="row">

<div class="col s12">
    <div class="card">
        <div class="card-content">
            <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Delectus, beatae.</p>
        </div>
        <div class="card-tabs">
            <ul class="tabs tabs-fixed-width">
                <li class="tab"><a href="#TestUno" class="active">Test Uno</a></li>
                <li class="tab"><a href="#TestDos">Test Dos</a></li>
                <li class="tab"><a href="#TestTres">Test Tres</a></li>
            </ul>
        </div>

        <div class="card-content green white-text">
            <div class="div" id="TestUno">Lorem Uno</div>
            <div class="div" id="TestDos">Lorem Dos</div>
            <div class="div" id="TestTres">Lorem Tres</div>
        </div>
    </div>
</div>

</div>

<!--Cardss Ends-->

<!-- Floating button -->

<div class="fixed-action-btn toolbar">
    <a class="btn-floating btn-large red">
        <i class="large material-icons">mode_edit</i>
    </a>
    <ul>
        <li><a class="btn-floating "><i class="material-icons">casino</i></a></li>
        <li><a class="btn-floating "><i class="material-icons">center_focus_strong</i></a></li>
        <li><a class="btn-floating "><i class="material-icons">fingerprint</i></a></li>
        <li><a class="btn-floating "><i class="material-icons">gamepad</i></a></li>
    </ul>
</div>
</div>
<!-- End Floating Button -->

<!--End Cards-->
    
<div class="container black" id="Carousel">
    <h1 class=" saction grey-text text-lighten-5 center light-green darken-3" id="Carousel">Carousel</h1>
<!-- Carousel -->

<div class="section container">
    <div class="row">

<div class="col s12"></div>

    <div class="carousel carousel-slider">

        <div class="carousel-fixed-item center">
            <a class="btn waves-effect white grey-text darken-text-2">button</a>
        </div>

            <a href="" class="carousel-item">
                <img src="https://images.pexels.com/photos/1308280/pexels-photo-1308280.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260" alt="">
            </a>
            <a href="" class="carousel-item">
                    <img src="https://images.pexels.com/photos/1020816/pexels-photo-1020816.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260" alt="">
                </a>
                <a href="" class="carousel-item">
                        <img src="https://images.pexels.com/photos/751670/pexels-photo-751670.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260" alt="">
                    </a>
        </div>
    </div>
</div>

<!--  Carousel End -->



<!-- Carousel mejorado -->

<div class="container section">
    <div class="row">
        <div class="col s12">


            <div class="slider">
                <ul class="slides">
                    <li>
                        <img src="https://images.pexels.com/photos/804181/pexels-photo-804181.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260" alt="">
                        <div class="caption center-align">
                            <h3>
                                Lorem, ipsum dolor.
                                <h5>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Assumenda sunt vero ipsa aliquid? Minima, accusantium.</h5>
                            </h3>
                        </div>
                    </li>
                    <li>
                        <img src="https://images.pexels.com/photos/34809/loro-park-orca-fish.jpg?auto=compress&cs=tinysrgb&h=350" alt="">
                        <div class="caption left-align">
                            <h3>
                                Cum, cupiditate adipisci!
                                <h5>Fugit atque, vero excepturi doloremque quo explicabo. Expedita rerum quae magni cum alias sint tempore?</h5>
                            </h3>
                        </div>
                    </li>
                    <li>
                        <img src="https://images.pexels.com/photos/289324/pexels-photo-289324.jpeg?auto=compress&cs=tinysrgb&h=350" alt="">
                        <div class="caption right-align">
                            <h3>
                                Quibusdam, beatae dolores.
                                <h5>Reprehenderit delectus, quia possimus nihil nobis quidem accusantium repellat recusandae, harum minus debitis vitae atque.</h5>
                            </h3>
                        </div>
                    </li>
                    <li>
                            <img src="https://images.pexels.com/photos/51964/humpback-whale-natural-spectacle-nature-mammal-51964.jpeg?auto=compress&cs=tinysrgb&h=350" alt="">
                            <div class="caption center-align">
                                <h3>
                                    Quibusdam, beatae dolores.
                                    <h5>Reprehenderit delectus, quia possimus nihil nobis quidem accusantium repellat recusandae, harum minus debitis vitae atque.</h5>
                                </h3>
                            </div>
                        </li>
                </ul>
            </div>
        </div>
    </div>
</div>

<!-- Fin Carousel Mejorado -->

<h1 class=" saction grey-text text-lighten-5 center light-green darken-4" id="Material-Box">Material Box</h1>

<!-- Material Box -->

<div class="row">
    <div class="col s6">
        <div class="section">

        <img src="https://images.pexels.com/photos/167699/pexels-photo-167699.jpeg?auto=compress&cs=tinysrgb&h=350" alt="" class="materialboxed responsive-img">
        </div>
    </div>
    <div class="col s6">
            <div class="section">
    
            <img src="https://images.pexels.com/photos/849835/pexels-photo-849835.jpeg?auto=compress&cs=tinysrgb&h=350" alt="" class="materialboxed responsive-img" data-caption="Un carro pues...en la nieve. ¿Dònde màs?">
            </div>
        </div>
</div>

<!-- End Materia Box -->




<!-- Javascript -->

    <!-- Compiled and minified JavaScript -->
<script src="https://cdnjs.cloudflare.com/ajax/libs/materialize/1.0.0-rc.2/js/materialize.min.js"></script>

<!-- Auton In -->
<script>
        document.addEventListener('DOMContentLoaded', function() {
            M.AutoInit();
        });
</script>

<!-- Floatting Button -->

<script>
        document.addEventListener('DOMContentLoaded', function() {
            var elems = document.querySelectorAll('.fixed-action-btn');
            var instances = M.FloatingActionButton.init(elems,{
                toolbarEnabled:true
            });
        });
</script>

<!-- <script> Alternativo (no barra)
        document.addEventListener('DOMContentLoaded', function() {
            var elems = document.querySelectorAll('.fixed-action-btn');
            var instances = M.FloatingActionButton.init(elems,{
            direction: 'left',
            hoverEnabled: false,
            });
        });
</script> -->

<!-- End FLoatin Button -->

<!-- Carousel -->

<script>
        document.addEventListener('DOMContentLoaded', function() {
            var elems = document.querySelectorAll('.carousel');
            var instances = M.Carousel.init(elems, {
                duration: 100,
                indicators: true,
            });
        });
</script>

<!-- Fin Carousel -->


<!-- Carousel Mejorado -->

<script>
        document.addEventListener('DOMContentLoaded', function() {
            var elems = document.querySelectorAll('.slider');
            var instances = M.Slider.init(elems,{
                indicators: false,
                height:500,
                interval:1000
            });
        });
</script>

<!-- Fin Carousel Mejorado -->

<!-- Material Box -->

<script>
        document.addEventListener('DOMContentLoaded', function() {
            var elems = document.querySelectorAll('.materialboxed');
            var instances = M.Materialbox.init(elems,{
                height:500,
            });
        });
</script>

<!-- Sidenav -->

<script>
        document.addEventListener('DOMContentLoaded', function() {
            var elems = document.querySelectorAll('.sidenav');
            var instances = M.Sidenav.init(elems);
        });
</script>
</body>
</html>
