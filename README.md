# Site
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Class16</title>
    <link rel="stylesheet" href="assets/css/all.min.css">
    <link rel="stylesheet" href="assets/css/fontawesome.min.css">
    <link rel="stylesheet" href="assets/css/bootstrap.min.css">
    <link rel="stylesheet" href="style.css">
    <style>
        .our-header-area{
    background-color: rgb(254, 217, 217);
}
.nav-item{
    margin-top: 25px;
    padding-left: 15px;
}
.nav-link{
    color: rgb(99, 20, 65);
    font-size: 18px;
    font-weight: 600;
}
.our-hero-area{
    background: url('assets/images/image.jpg');
    height: 600px;
    width: 100%;
    background-repeat: no-repeat;
    background-position: center;
    background-size: cover;
    color: white;
    text-align: center;
    padding-top: 80px;
}
.hero-heading{
    font-size: 60px;
}
.our-card-area{
    margin: 70px;
}
    </style>
</head>
<body>
    <header>
        <div class="our-header-area">
            <div class="container">
                <div class="row">
                    <div class="col-xl-3 col-sm-5">
                        <div class="our-logo">
                            <img src="assets/images/logo.jpg" alt="logo">
                        </div>
                    </div>
                    <div class="col-xl-9 col-sm-7">
                        <nav class="navbar navbar-expand-lg">
                            <div class="container">
                                <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                                  <li class="nav-item"><a class="nav-link" href="#">Home</a></li>
                                  <li class="nav-item"><a class="nav-link" href="#">Collections</a></li>
                                  <li class="nav-item"><a class="nav-link" href="#">About</a></li>
                                  <li class="nav-item"><a class="nav-link" href="#">Service</a></li>
                                  <li class="nav-item"><a class="nav-link" href="#">contact</a></li>
                                </ul>
                            </div>
                        </nav>
                    </div>
                </div>
            </div>
        </div>
    </header>
    <main>
        <div class="our-hero-area">
            <span class="hero-span">Choose your princess dress</span>
            <h2 class="hero-heading">Princess Dress</h2>
            <p class="hero-para">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Quae velit eius, minima, optio accusantium fugiat<br> illum qui id distinctio fugit deleniti impedit reprehenderit itaque? Corrupti at aperiam<br> temporibus ipsam vel quae odio ex nobis dolorem voluptate, odit, ut explicabo non accusantium, maxime dolores ratione nostrum laborum magnam<br> voluptatem mollitia itaque!</p>
        </div>
        <div class="our-card-area">
            <div class="container">
                <div class="row">
                    <div class="col-xl-4">
                        <div class="card" style="width: 288px;">
                            <img src="assets/images/image1.jpg" class="card-img-top" alt="image1">
                            <div class="card-body">
                                <h5 class="card-title">Cindrella Blue Dress</h5>
                                <p class="card-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Repellat, consequatur?</p>
                                <a href="#" class="btn btn-primary">See details</a>
                            </div>
                        </div>
                    </div>
                    <div class="col-xl-4">
                        <div class="card" style="width: 288px;">
                            <img src="assets/images/image2.jpg" class="card-img-top" alt="image2">
                            <div class="card-body">
                                <h5 class="card-title">Andrea and Leo Dress</h5>
                                <p class="card-text">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Fuga, provident.</p>
                                <a href="#" class="btn btn-primary">See details</a>
                            </div>
                        </div>
                    </div>
                    <div class="col-xl-4">
                        <div class="card" style="width: 288px;">
                            <img src="assets/images/image3.jpg" class="card-img-top" alt="image3">
                            <div class="card-body">
                                <h5 class="card-title">Yellow Cotton Dress</h5>
                                <p class="card-text">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Voluptates, quos?</p>
                                <a href="#" class="btn btn-primary">See details</a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </main>
    <script src="assets/js/all.min.js"></script>
    <script src="assets/js/fontawesome.min.js"></script>
    <script src="assets/js/bootstrap.bundle.min.js"></script>
    <script src="assets/js/custom.js"></script>
    <footer></footer>
</body>
</html>
