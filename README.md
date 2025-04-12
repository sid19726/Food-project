# Food-project
Food project using html css and java script
<!DOCTYPE html>
<html lang="en">


<head>
    <meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Pehla Bites">
    <meta name="keywords" content="Pehla Bites">
    <meta name="author" content="Pehla Bites">
    <link rel="icon" href="assets/images/logo/" type="image/x-icon">
    <title>Pehla Bites- Your cravings partner </title>
    <link rel="apple-touch-icon" href="assets/images/logo/">
    <meta name="theme-color" content="#ff8d2f">
    <meta name="apple-mobile-web-app-capable" content="yes">
    <meta name="apple-mobile-web-app-status-bar-style" content="black">
    <meta name="apple-mobile-web-app-title" content="Pehla Bites">
    <meta name="msapplication-TileImage" content="assets/images/logo/">
    <meta name="msapplication-TileColor" content="#FFFFFF">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">

    <!--Google font-->
    <link rel="preconnect" href="https://fonts.googleapis.com/">
    <link rel="preconnect" href="https://fonts.gstatic.com/" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@100;200;300;400;500;600;700;800;900&amp;display=swap"
        rel="stylesheet">

    <!-- bootstrap css -->
    <link rel="stylesheet" type="text/css" id="rtl-link" href="assets/css/vendors/bootstrap.css">

    <!-- swiper css -->
    <link rel="stylesheet" type="text/css" href="assets/css/vendors/swiper-bundle.min.css">

    <!-- remixicon css -->
    <link rel="stylesheet" type="text/css" href="assets/css/vendors/remixicon.css">

    <!-- Theme css -->
    <link rel="stylesheet" id="change-link" type="text/css" href="assets/css/style.css">





<style>
    .order-btn,
.price-btn {
    padding: 10px 20px;
    border-radius: 5px;
    font-size: 16px;
}

.order-btn {
    background-color: #007bff; /* Primary color */
    color: #fff; /* Text color */
    border: none;
}

.price-btn {
    background-color: transparent;
    color: #007bff; /* Primary color */
    border: 1px solid #007bff; /* Primary color */
}
</style>


</head>

<body class="position-relative">
    <!-- skeleton loader start -->
    <div class="skeleton-loader">
        <header>
            <div class="container">
                <nav class="navbar navbar-expand-lg p-0">
                    <button class="navbar-toggler" type="button" data-bs-toggle="collapse"
                        data-bs-target="#offcanvasNavbar">
                        <span class="navbar-toggler-icon">
                            <i class="ri-menu-line"></i>
                        </span>
                    </button>
                    <a href="index.html">
                        <img class="img-fluid logo" src="assets/logo2.png" alt="logo">
                    </a>
                    <a target="_blank" href="#!" data-bs-toggle="modal" data-bs-target="#location"
                        class="btn btn-sm theme-btn location-btn mt-0 ms-3 d-flex align-content-center gap-1">
                        <i class="ri-map-pin-line"></i> Location
                    </a>
                    <div class="nav-option order-md-2">
                        <div class="dropdown-button">
                            <div class="cart-button">
                                <span>5</span>
                                <i class="ri-shopping-cart-line text-white cart-bag"></i>
                            </div>
                        </div>
                        <div class="profile-part dropdown-button order-md-2">
                            <img class="img-fluid profile-pic" src="assets/images/icons/p5.png" alt="profile">
                            <div>
                                <h6 class="fw-normal">Hi, Sidharth</h6>
                                <h5 class="fw-medium">My Account</h5>
                            </div>
                        </div>
                    </div>
                    <div class="offcanvas offcanvas-end" tabindex="-1" id="offcanvasSkeleton">
                        <div class="offcanvas-header">
                            <h5 class="offcanvas-title" id="offcanvasSkeletonLabel">
                                Menu
                            </h5>
                            <button class="navbar-toggler btn-close" type="button" data-bs-toggle="collapse"
                                data-bs-target="#offcanvasSkeleton" data-bs-dismiss="offcanvas"></button>
                        </div>
                        <div class="offcanvas-body">
                            <ul class="navbar-nav justify-content-center flex-grow-1">
                                <li class="nav-item dropdown">
                                    <a class="nav-link dropdown-toggle" href="#!" role="button"
                                        data-bs-toggle="dropdown" aria-expanded="false">Home</a>
                                </li>
                               
                                <li class="nav-item">
                                    <a class="nav-link" href="contact.html">Contact</a>
                                </li>
                            </ul>
                        </div>
                    </div>
                </nav>
            </div>
        </header>
        <section class="home-wrapper section-b-space">
            <div class="container text-center">
                <div class="loader-gif">
                    <img src="assets/images/gif/food.gif" alt="food-gif" class="img-fluid">
                </div>
                <h2>Searching the most delicious dish in your area...</h2>
            </div>
        </section>
        <section class="categories-section section-b-space">
            <div class="container">
                <div class="title placeholder-glow">
                    <span class="placeholder col-md-2 col-5"></span>
                    <p class="placeholder col-5 w-50"></p>
                </div>
                <div class="theme-arrow">
                    <div class="swiper categories-slider categories-style">
                        <div class="swiper-wrapper">
                            <div class="swiper-slide placeholder-glow">
                                <a href="restaurant-listing.html" class="food-categories">
                                    <span class="categories-img"></span>
                                    <h4 class="placeholder col-10"></h4>
                                </a>
                            </div>
                            <div class="swiper-slide">
                                <a href="restaurant-listing.html" class="food-categories">
                                    <span class="categories-img"></span>
                                    <h4 class="placeholder col-10"></h4>
                                </a>
                            </div>
                            <div class="swiper-slide">
                                <a href="restaurant-listing.html" class="food-categories">
                                    <span class="categories-img"></span>
                                    <h4 class="placeholder col-10"></h4>
                                </a>
                            </div>
                            <div class="swiper-slide">
                                <a href="restaurant-listing.html" class="food-categories">
                                    <span class="categories-img"></span>
                                    <h4 class="placeholder col-10"></h4>
                                </a>
                            </div>
                            <div class="swiper-slide">
                                <a href="restaurant-listing.html" class="food-categories">
                                    <span class="categories-img"></span>
                                    <h4 class="placeholder col-10"></h4>
                                </a>
                            </div>
                            <div class="swiper-slide">
                                <a href="restaurant-listing.html" class="food-categories">
                                    <span class="categories-img"></span>
                                    <h4 class="placeholder col-10"></h4>
                                </a>
                            </div>
                            <div class="swiper-slide">
                                <a href="restaurant-listing.html" class="food-categories">
                                    <span class="categories-img"></span>
                                    <h4 class="placeholder col-10"></h4>
                                </a>
                            </div>
                            <div class="swiper-slide">
                                <a href="restaurant-listing.html" class="food-categories">
                                    <span class="categories-img"></span>
                                    <h4 class="placeholder col-10"></h4>
                                </a>
                            </div>
                            <div class="swiper-slide">
                                <a href="restaurant-listing.html" class="food-categories">
                                    <span class="categories-img"></span>
                                    <h4 class="placeholder col-10"></h4>
                                </a>
                            </div>
                            <div class="swiper-slide">
                                <a href="restaurant-listing.html" class="food-categories">
                                    <span class="categories-img"></span>
                                    <h4 class="placeholder col-10"></h4>
                                </a>
                            </div>
                            <div class="swiper-slide">
                                <a href="restaurant-listing.html" class="food-categories">
                                    <span class="categories-img"></span>
                                    <h4 class="placeholder col-10"></h4>
                                </a>
                            </div>
                            <div class="swiper-slide">
                                <a href="restaurant-listing.html" class="food-categories">
                                    <span class="categories-img"></span>
                                    <h4 class="placeholder col-10"></h4>
                                </a>
                            </div>
                            <div class="swiper-slide">
                                <a href="restaurant-listing.html" class="food-categories">
                                    <span class="categories-img"></span>
                                    <h4 class="placeholder col-10"></h4>
                                </a>
                            </div>
                            <div class="swiper-slide">
                                <a href="restaurant-listing.html" class="food-categories">
                                    <span class="categories-img"></span>
                                    <h4 class="placeholder col-10"></h4>
                                </a>
                            </div>
                            <div class="swiper-slide">
                                <a href="restaurant-listing.html" class="food-categories">
                                    <span class="categories-img"></span>
                                    <h4 class="placeholder col-10"></h4>
                                </a>
                            </div>
                            <div class="swiper-slide">
                                <a href="restaurant-listing.html" class="food-categories">
                                    <span class="categories-img"></span>
                                    <h4 class="placeholder col-10"></h4>
                                </a>
                            </div>
                            <div class="swiper-slide">
                                <a href="restaurant-listing.html" class="food-categories">
                                    <span class="categories-img"></span>
                                    <h4 class="placeholder col-10"></h4>
                                </a>
                            </div>
                            <div class="swiper-slide">
                                <a href="restaurant-listing.html" class="food-categories">
                                    <span class="categories-img"></span>
                                    <h4 class="placeholder col-10"></h4>
                                </a>
                            </div>
                            <div class="swiper-slide">
                                <a href="restaurant-listing.html" class="food-categories">
                                    <span class="categories-img"></span>
                                    <h4 class="placeholder col-10"></h4>
                                </a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <section class="banner-section section-b-space">
            <div class="container">
                <div class="title placeholder-glow">
                    <span class="placeholder col-md-2 col-5"></span>
                    <p class="placeholder col-5 w-50"></p>
                </div>
                <div class="position-relative">
                    <div class="swiper banner1-slider">
                        <div class="swiper-wrapper">
                            <div class="swiper-slide placeholder-glow">
                                <div class="banner-part">
                                    <a href="offer.html" class="placeholder"></a>
                                </div>
                            </div>
                            <div class="swiper-slide">
                                <div class="banner-part">
                                    <a href="offer.html" class="placeholder"></a>
                                </div>
                            </div>
                            <div class="swiper-slide">
                                <div class="banner-part">
                                    <a href="offer.html" class="placeholder"></a>
                                </div>
                            </div>
                            <div class="swiper-slide">
                                <div class="banner-part">
                                    <a href="offer.html" class="placeholder"></a>
                                </div>
                            </div>
                            <div class="swiper-slide">
                                <div class="banner-part">
                                    <a href="offer.html" class="placeholder"></a>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
    </div>
    <!-- skeleton loader end -->

    <!-- Header section start -->
    <header>
        <div class="container">
            <nav class="navbar navbar-expand-lg p-0">
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse"
                    data-bs-target="#offcanvasNavbar">
                    <span class="navbar-toggler-icon">
                        <i class="ri-menu-line"></i>
                    </span>
                </button>
                <a href="index.html">
                    <img class="img-fluid logo" src="assets/logo2.png" alt="logo" style="width: 150px; height: auto;">
                </a>
                <a target="_blank" href="#!" data-bs-toggle="modal" data-bs-target="#location"
                    class="btn btn-sm theme-btn location-btn mt-0 ms-3 d-flex align-content-center gap-1">
                    <i class="ri-map-pin-line"></i> Location
                </a>
                <div class="nav-option order-md-2">
                    <div class="dropdown-button">
                        <div class="cart-button">
                            <span>5</span>
                            <i class="ri-shopping-cart-line text-white cart-bag"></i>
                        </div>
                        <div class="onhover-box">
                            <ul class="cart-list">
                                <li class="product-box-contain">
                                    <div class="drop-cart">
                                        <a href="#!" class="drop-image">
                                            <img src="assets/images/product/vp-3.png" class="blur-up lazyloaded" alt="">
                                        </a>
                                        <div class="drop-contain">
                                            <a href="#!">
                                                <h5>Egg Sandwich</h5>
                                            </a>
                                            <h6><span>1 x </span> $80.58</h6>
                                            <button class="close-button close_button">
                                                <i class="fa-solid fa-xmark"></i>
                                            </button>
                                        </div>
                                    </div>
                                </li>
                                <li class="product-box-contain">
                                    <div class="drop-cart">
                                        <a href="#!" class="drop-image">
                                            <img src="assets/images/product/vp-2.png" class="blur-up lazyloaded" alt="">
                                        </a>
                                        <div class="drop-contain">
                                            <a href="#!">
                                                <h5>Grilled Chicken Quesadilla</h5>
                                            </a>
                                            <h6><span>1 x </span> $25.64</h6>
                                            <button class="close-button close_button">
                                                <i class="fa-solid fa-xmark"></i>
                                            </button>
                                        </div>
                                    </div>
                                </li>
                                <li class="product-box-contain">
                                    <div class="drop-cart">
                                        <a href="#!" class="drop-image">
                                            <img src="assets/images/product/vp-4.png" class="blur-up lazyloaded" alt="">
                                        </a>
                                        <div class="drop-contain">
                                            <a href="#!">
                                                <h5>Spicy Ahi Roll</h5>
                                            </a>
                                            <h6><span>1 x </span> $12.00</h6>
                                            <button class="close-button close_button">
                                                <i class="fa-solid fa-xmark"></i>
                                            </button>
                                        </div>
                                    </div>
                                </li>
                                <li class="product-box-contain">
                                    <div class="drop-cart">
                                        <a href="#!" class="drop-image">
                                            <img src="assets/images/product/vp-5.png" class="blur-up lazyloaded" alt="">
                                        </a>
                                        <div class="drop-contain">
                                            <a href="#!">
                                                <h5>Spicy Dumplings</h5>
                                            </a>
                                            <h6><span>1 x </span> $16.28</h6>
                                            <button class="close-button close_button">
                                                <i class="fa-solid fa-xmark"></i>
                                            </button>
                                        </div>
                                    </div>
                                </li>
                                <li class="product-box-contain">
                                    <div class="drop-cart">
                                        <a href="#!" class="drop-image">
                                            <img src="assets/images/product/vp-6.png" class="blur-up lazyloaded" alt="">
                                        </a>
                                        <div class="drop-contain">
                                            <a href="#!">
                                                <h5>Chicken Nugget</h5>
                                            </a>
                                            <h6><span>1 x </span> $20.50</h6>
                                            <button class="close-button close_button">
                                                <i class="fa-solid fa-xmark"></i>
                                            </button>
                                        </div>
                                    </div>
                                </li>
                            </ul>
                            <div class="price-box">
                                <h5>Total :</h5>
                                <h4 class="theme-color fw-semibold">$155.00</h4>
                            </div>
                            <div class="button-group">
                                <a href="checkout.html" class="btn btn-sm theme-btn w-100 d-block rounded-2">View
                                    Cart</a>
                            </div>
                        </div>
                    </div>
                    <div class="profile-part dropdown-button order-md-2">
                        <img class="img-fluid profile-pic" src="assets/images/icons/p5.png" alt="profile">
                        <div>
                            <h6 class="fw-normal">Hi, Sekhar</h6>
                            <h5 class="fw-medium">My Account</h5>
                        </div>
                        <div class="onhover-box onhover-sm">
                            <ul class="menu-list">
                                <li>
                                    <a class="dropdown-item" href="profile.html">Profile</a>
                                </li>
                                <li>
                                    <a class="dropdown-item" href="my-order.html">My orders</a>
                                </li>
                                <li>
                                    <a class="dropdown-item" href="saved-address.html">Saved Address</a>
                                </li>
                                <li>
                                    <a class="dropdown-item" href="saved-card.html">Saved cards</a>
                                </li>
                                <li>
                                    <a class="dropdown-item" href="setting.html">Settings</a>
                                </li>
                            </ul>
                            <div class="bottom-btn">
                                <a href="signin.html" class="theme-color fw-medium d-flex"><i
                                        class="ri-login-box-line me-2"></i>Logout</a>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="offcanvas offcanvas-end" tabindex="-1" id="offcanvasNavbar">
                    <div class="offcanvas-header">
                        <h5 class="offcanvas-title" id="offcanvasNavbarLabel">Menu</h5>
                        <button class="navbar-toggler btn-close" id="offcanvas-close"></button>
                    </div>
                    <div class="offcanvas-body">
                        <ul class="navbar-nav justify-content-center flex-grow-1">
                            <li class="nav-item dropdown mega-menu">
                                <a class="nav-link dropdown-toggle" href="#!" id="accountDropdown" role="button"
                                    data-bs-toggle="dropdown" aria-expanded="false">Home</a>
                                
                            </li>
                            
                           
                            </li>
                            <li class="nav-item">
                                <a class="nav-link" href="contact.html">Contact</a>
                            </li>
                        </ul>
                    </div>
                </div>
            </nav>
        </div>
    </header>
    <!-- Header Section end -->

    <!-- home section start -->
    <section id="home" class="home-wrapper section-b-space overflow-hidden">
        <div class="background-effect">
            <div class="main-circle">
                <div class="main-circle circle-1">
                    <div class="main-circle circle-2"></div>
                </div>
            </div>
        </div>
        <div class="container text-center position-relative">
            <h1>Pehla Bites</h1>
            <h2>We love to address your cravings</h2>
            
            <ul class="home-features-list d-md-flex d-none">
                <li>
                    <div class="home-features-box">
                        <img class="img-fluid icon" src="assets/images/svg/routing.svg" alt="routing">
                        <h6>Wide Map</h6>
                    </div>
                </li>
                <li>
                    <div class="home-features-box">
                        <img class="img-fluid icon" src="assets/images/svg/3d-rotate.svg" alt="3d-rotate">
                        <h6>Easiest Order</h6>
                    </div>
                </li>
                <li>
                    <div class="home-features-box">
                        <img class="img-fluid icon" src="assets/images/svg/truck.svg" alt="truck">
                        <h6>Fast Delivery</h6>
                    </div>
                </li>
            </ul>
        </div>
    </section>
    <!-- home section end -->

    <!-- categories section starts -->
    <section class="categories-section section-b-space">
        <img src="assets/images/scooter.png" class="scooter-img img-fluid d-md-inline-block d-none"
            alt="animation-scooter">
        <div class="container">
            <div class="title">
                <h2>Categories</h2>
                <div class="loader-line"></div>
                <div class="sub-title">
                    <p>
                        Browse out top categories here to discover different food cuision.
                    </p>
                </div>
            </div>
            <div class="theme-arrow">
                <div class="swiper categories-slider categories-style">
                    <div class="swiper-wrapper">
                        <div class="swiper-slide">
                            <a href="restaurant-listing.html" class="food-categories">
                                <img class="img-fluid categories-img" src="assets/images/product/p-20.png" alt="p-20">
                                <h4 class="dark-text">Biryani</h4>
                            </a>
                        </div>
                        <div class="swiper-slide">
                            <a href="restaurant-listing.html" class="food-categories">
                                <img class="img-fluid categories-img" src="assets/images/product/p-18.png" alt="p-18">
                                <h4 class="dark-text">Momos</h4>
                            </a>
                        </div>
                        <div class="swiper-slide">
                            <a href="restaurant-listing.html" class="food-categories">
                                <img class="img-fluid categories-img" src="assets/images/product/p-3.png" alt="p-3">
                                <h4 class="dark-text" style="font-size: 17px; position: center;">Chinneese Combo</h4>
                            </a>
                        </div>
                        <div class="swiper-slide">
                            <a href="restaurant-listing.html" class="food-categories">
                                <img class="img-fluid categories-img" src="assets/images/product/p-5.png" alt="p-5">
                                <h4 class="dark-text">Indian Combo</h4>
                            </a>
                        </div>
                        <div class="swiper-slide">
                            <a href="restaurant-listing.html" class="food-categories">
                                <img class="img-fluid categories-img" src="assets/images/product/p-6.png" alt="p-6">
                                <h4 class="dark-text">Gym Diets</h4>
                            </a>
                        </div>
                        <div class="swiper-slide">
                            <a href="restaurant-listing.html" class="food-categories">
                                <img class="img-fluid categories-img" src="assets/images/product/p-7.png" alt="p-7">
                                <h4 class="dark-text">Cafe Bites</h4>
                            </a>
                        </div>
                        <div class="swiper-slide">
                            <a href="restaurant-listing.html" class="food-categories">
                                <img class="img-fluid categories-img" src="assets/images/product/p-8.png" alt="p-8">
                                <h4 class="dark-text">Veg Meal</h4>
                            </a>
                        </div>
                        <div class="swiper-slide">
                            <a href="restaurant-listing.html" class="food-categories">
                                <img class="img-fluid categories-img" src="assets/images/product/p-9.png" alt="p-9">
                                <h4 class="dark-text">Non Veg Meal</h4>
                            </a>
                        </div>
                        <div class="swiper-slide">
                            <a href="restaurant-listing.html" class="food-categories">
                                <img class="img-fluid categories-img" src="assets/images/product/p-10.png" alt="p-5">
                                <h4 class="dark-text">South Indian</h4>
                            </a>
                        </div>
                        <div class="swiper-slide">
                            <a href="restaurant-listing.html" class="food-categories">
                                <img class="img-fluid categories-img" src="assets/images/product/p-11.png" alt="p-11">
                                <h4 class="dark-text">Occassional Special</h4>
                            </a>
                        </div>
                        
                        
                        <div class="swiper-slide">
                            <a href="restaurant-listing.html" class="food-categories">
                                <img class="img-fluid categories-img" src="assets/images/product/p-14.png" alt="p-14">
                                <h4 class="dark-text">Sandwich</h4>
                            </a>
                        </div>
                       
                      
                      
                        <div class="swiper-slide">
                            <a href="restaurant-listing.html" class="food-categories">
                                <img class="img-fluid categories-img" src="assets/images/product/p-19.png" alt="p-19">
                                <h4 class="dark-text">Salad</h4>
                            </a>
                        </div>
                      
                    </div>
                </div>
                <div class="swiper-button-next categories-next"></div>
                <div class="swiper-button-prev categories-prev"></div>
            </div>
        </div>
    </section>
    <!-- categories section end -->

    <!-- banner section starts -->
    <section class="banner-section section-b-space">
        <div class="container">
            <div class="title">
                <h2>Today’s Deal</h2>
                <div class="loader-line"></div>
                <div class="sub-title">
                    <p>Take a benefit from our latest offers.</p>
                </div>
            </div>
            <div class="position-relative">
                <div class="swiper banner1-slider">
                    <div class="swiper-wrapper">
                        <div class="swiper-slide">
                            <div class="banner-part">
                                <a href="offer.html">
                                    <img class="img-fluid banner-img" src="assets/images/banner/banner1.jpg"
                                        alt="banner">
                                </a>
                            </div>
                        </div>
                        <div class="swiper-slide">
                            <div class="banner-part">
                                <a href="offer.html">
                                    <img class="img-fluid banner-img" src="assets/images/banner/banner2.jpg"
                                        alt="banner">
                                </a>
                            </div>
                        </div>
                        <div class="swiper-slide">
                            <div class="banner-part">
                                <a href="offer.html">
                                    <img class="img-fluid banner-img" src="assets/images/banner/banner3.jpg"
                                        alt="banner">
                                </a>
                            </div>
                        </div>
                        <div class="swiper-slide">
                            <div class="banner-part">
                                <a href="offer.html">
                                    <img class="img-fluid banner-img" src="assets/images/banner/banner4.jpg"
                                        alt="banner">
                                </a>
                            </div>
                        </div>
                        <div class="swiper-slide">
                            <div class="banner-part">
                                <a href="offer.html">
                                    <img class="img-fluid banner-img" src="assets/images/banner/banner5.jpg"
                                        alt="banner">
                                </a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    
<!-- Non veg section starts -->
<section class="popular-restaurant banner-section section-b-space ratio3_2 overflow-hidden">
    <img class="img-fluid item-5" src="assets/images/svg/item5.svg" alt="item-5">
    <div class="container">
        <div class="title">
            <h2>Non Veg Delights</h2>
            <div class="loader-line"></div>
            <div class="sub-title">
                <p></p>
            </div>
        </div>
        <div class="row g-md-4 g-3">
            <!-- Restaurant Items -->
            <div class="col-xl-3 col-lg-4 col-md-6">
                <div class="vertical-product-box">
                    <div class="vertical-product-box-img">
                        <a href="menu-listing.html">
                            <img class="product-img-top w-100 bg-img" src="assets/images/product/vp-123456.png" alt="vp1">
                        </a>
                        <div class="offers">
                            <h6>Real Discount</h6>
                            <div class="d-flex align-items-center justify-content-between">
                                <h4>100 Off</h4>
                            </div>
                        </div>
                    </div>
                    <div class="vertical-product-body">
                        <div class="d-flex align-items-center justify-content-between mt-sm-3 mt-2">
                            <a href="menu-listing.html">
                                <h4 class="vertical-product-title">Chicken Noodles</h4>
                            </a>
                            <h6 class="rating-star">
                                <span class="star"><i class="ri-star-s-fill"></i></span>4.9
                            </h6>
                        </div>
                        <h5 class="product-items">With Chilly Chicken / Chicken Manchurian </h5>
                        <div class="location-distance d-flex align-items-center justify-content-between pt-sm-3 pt-2">
                            <h5 class="place">Infosys</h5>
                            <ul class="distance">
                                <!--<li><i class="ri-map-pin-fill icon"></i> 1.2 km</li>-->
                                <li><i class="ri-time-fill icon"></i> 25 min</li>
                            </ul>
                        </div>
                        <!-- Order and Price Buttons -->
                        <div class="d-flex justify-content-between mt-3">
                            <button class="btn btn-primary order-btn">Order Now</button>
                            <button class="btn btn-outline-secondary price-btn">₹ 179.00</button>
                        </div>
                    </div>
                </div>
            </div>




<!-- Second Item -->


            <div class="col-xl-3 col-lg-4 col-md-6">
                <div class="vertical-product-box">
                    <div class="vertical-product-box-img">
                        <a href="menu-listing.html">
                            <img class="product-img-top w-100 bg-img" src="assets/images/product/vp-12345.png" alt="vp1">
                        </a>
                        <div class="offers">
                            <h6>Real Discount</h6>
                            <div class="d-flex align-items-center justify-content-between">
                                <h4>100 Off</h4>
                            </div>
                        </div>
                    </div>
                    <div class="vertical-product-body">
                        <div class="d-flex align-items-center justify-content-between mt-sm-3 mt-2">
                            <a href="menu-listing.html">
                                <h4 class="vertical-product-title">Chicken Noodles</h4>
                            </a>
                            <h6 class="rating-star">
                                <span class="star"><i class="ri-star-s-fill"></i></span>4.8
                            </h6>
                        </div>
                        <h5 class="product-items">With Dragon Chicken / Chicken Lollypop</h5>
                        <div class="location-distance d-flex align-items-center justify-content-between pt-sm-3 pt-2">
                            <h5 class="place">Infosys</h5>
                            <ul class="distance">
                                <li><i class="ri-map-pin-fill icon"></i> 1.2 km</li>
                                <li><i class="ri-time-fill icon"></i> 25 min</li>
                            </ul>
                        </div>
                        <!-- Order and Price Buttons -->
                        <div class="d-flex justify-content-between mt-3">
                            <button class="btn btn-primary order-btn">Order Now</button>
                            <button class="btn btn-outline-secondary price-btn">₹ 199.00</button>
                        </div>
                    </div>
                </div>
            </div>



<!-- Second Item  end-->




<!-- third 
    Item -->


<div class="col-xl-3 col-lg-4 col-md-6">
    <div class="vertical-product-box">
        <div class="vertical-product-box-img">
            <a href="menu-listing.html">
                <img class="product-img-top w-100 bg-img" src="assets/images/product/vp-1234.png" alt="vp1">
            </a>
            <div class="offers">
                <h6>Real Discount</h6>
                <div class="d-flex align-items-center justify-content-between">
                    <h4>100 Off</h4>
                </div>
            </div>
        </div>
        <div class="vertical-product-body">
            <div class="d-flex align-items-center justify-content-between mt-sm-3 mt-2">
                <a href="menu-listing.html">
                    <h4 class="vertical-product-title">Chicken Biriyani</h4>
                </a>
                <h6 class="rating-star">
                    <span class="star"><i class="ri-star-s-fill"></i></span>5.0
                </h6>
            </div>
            <h5 class="product-items">With Pepsi/ Thumbsup </h5>
            <div class="location-distance d-flex align-items-center justify-content-between pt-sm-3 pt-2">
                <h5 class="place">Infosys</h5>
                <ul class="distance">
                    <li><i class="ri-map-pin-fill icon"></i> 1.2 km</li>
                    <li><i class="ri-time-fill icon"></i> 25 min</li>
                </ul>
            </div>
            <!-- Order and Price Buttons -->
            <div class="d-flex justify-content-between mt-3">
                <button class="btn btn-primary order-btn">Order Now</button>
                <button class="btn btn-outline-secondary price-btn">₹149.00</button>
            </div>
        </div>
    </div>
</div>



<!-- third Item  end-->





<!-- forth Item -->


<div class="col-xl-3 col-lg-4 col-md-6">
    <div class="vertical-product-box">
        <div class="vertical-product-box-img">
            <a href="menu-listing.html">
                <img class="product-img-top w-100 bg-img" src="assets/images/product/vp-1234567.png" alt="vp1">
            </a>
            <div class="offers">
                <h6>Real Discount</h6>
                <div class="d-flex align-items-center justify-content-between">
                    <h4>100 Off</h4>
                </div>
            </div>
        </div>
        <div class="vertical-product-body">
            <div class="d-flex align-items-center justify-content-between mt-sm-3 mt-2">
                <a href="menu-listing.html">
                    <h4 class="vertical-product-title">Chicken Fried Rice</h4>
                </a>
                <h6 class="rating-star">
                    <span class="star"><i class="ri-star-s-fill"></i></span>4.3
                </h6>
            </div>
            <h5 class="product-items">With Chilly Chicken </h5>
            <div class="location-distance d-flex align-items-center justify-content-between pt-sm-3 pt-2">
                <h5 class="place">Infiosys </h5>
                <ul class="distance">
                    <li><i class="ri-map-pin-fill icon"></i> 1.2 km</li>
                    <li><i class="ri-time-fill icon"></i> 25 min</li>
                </ul>
            </div>
            <!-- Order and Price Buttons -->
            <div class="d-flex justify-content-between mt-3">
                <button class="btn btn-primary order-btn">Order Now</button>
                <button class="btn btn-outline-secondary price-btn">₹ 169.00</button>
            </div>
        </div>
    </div>
</div>



<!-- forth Item  end-->







            
            <!-- orders repeat -->
        </div>
    </div>
</section>
<!-- Non veg section end -->


    <!-- veg  section starts -->
<section class="popular-restaurant banner-section section-b-space ratio3_2 overflow-hidden">
    <img class="img-fluid item-5" src="assets/images/svg/item5.svg" alt="item-5">
    <div class="container">
        <div class="title">
            <h2> Veg Paradise</h2>
            <div class="loader-line"></div>
            <div class="sub-title">
                <p></p>
            </div>
        </div>
        <div class="row g-md-4 g-3">
            <!-- Restaurant Items -->
            <div class="col-xl-3 col-lg-4 col-md-6">
                <div class="vertical-product-box">
                    <div class="vertical-product-box-img">
                        <a href="menu-listing.html">
                            <img class="product-img-top w-100 bg-img" src="assets/images/product/vp-123456711.png" alt="vp1">
                        </a>
                        <div class="offers">
                            <h6>Real Discount</h6>
                <div class="d-flex align-items-center justify-content-between">
                    <h4>50 Off</h4>
                            </div>
                        </div>
                    </div>
                    <div class="vertical-product-body">
                        <div class="d-flex align-items-center justify-content-between mt-sm-3 mt-2">
                            <a href="menu-listing.html">
                                <h4 class="vertical-product-title">Veg Noodles </h4>
                            </a>
                            <h6 class="rating-star">
                                <span class="star"><i class="ri-star-s-fill"></i></span>3.9
                            </h6>
                        </div>
                        <h5 class="product-items"> Chilly Paneer</h5>
                        <div class="location-distance d-flex align-items-center justify-content-between pt-sm-3 pt-2">
                            <h5 class="place">Infosys</h5>
                            <ul class="distance">
                                <li><i class="ri-map-pin-fill icon"></i> 1.2 km</li>
                                <li><i class="ri-time-fill icon"></i> 25 min</li>
                            </ul>
                        </div>
                        <!-- Order and Price Buttons -->
                        <div class="d-flex justify-content-between mt-3">
                            <button class="btn btn-primary order-btn">Order Now</button>
                            <button class="btn btn-outline-secondary price-btn">₹139.99</button>
                        </div>
                    </div>
                </div>
            </div>




<!-- Second Item -->


            <div class="col-xl-3 col-lg-4 col-md-6">
                <div class="vertical-product-box">
                    <div class="vertical-product-box-img">
                        <a href="menu-listing.html">
                            <img class="product-img-top w-100 bg-img" src="assets/images/product/vp-123456710.png" alt="vp1">
                        </a>
                        <div class="offers">
                            <h6>Real Discount</h6>
                            <div class="d-flex align-items-center justify-content-between">
                                <h4>50 Off</h4>
                            </div>
                        </div>
                    </div>
                    <div class="vertical-product-body">
                        <div class="d-flex align-items-center justify-content-between mt-sm-3 mt-2">
                            <a href="menu-listing.html">
                                <h4 class="vertical-product-title">Veg Rolls</h4>
                            </a>
                            <h6 class="rating-star">
                                <span class="star"><i class="ri-star-s-fill"></i></span>3.9
                            </h6>
                        </div>
                        <h5 class="product-items">With Paper Boat</h5>
                        <div class="location-distance d-flex align-items-center justify-content-between pt-sm-3 pt-2">
                            <h5 class="place">Infosys</h5>
                            <ul class="distance">
                                <li><i class="ri-map-pin-fill icon"></i> 1.2 km</li>
                                <li><i class="ri-time-fill icon"></i> 25 min</li>
                            </ul>
                        </div>
                        <!-- Order and Price Buttons -->
                        <div class="d-flex justify-content-between mt-3">
                            <button class="btn btn-primary order-btn">Order Now</button>
                            <button class="btn btn-outline-secondary price-btn"> ₹ 89.99</button>
                        </div>
                    </div>
                </div>
            </div>



<!-- Second Item  end-->




<!-- third 
    Item -->


<div class="col-xl-3 col-lg-4 col-md-6">
    <div class="vertical-product-box">
        <div class="vertical-product-box-img">
            <a href="menu-listing.html">
                <img class="product-img-top w-100 bg-img" src="assets/images/product/vp-12345678.png" alt="vp1">
            </a>
            <div class="offers">
                <h6>Real Discount</h6>
                <div class="d-flex align-items-center justify-content-between">
                    <h4>50 Off</h4>
                </div>
            </div>
        </div>
        <div class="vertical-product-body">
            <div class="d-flex align-items-center justify-content-between mt-sm-3 mt-2">
                <a href="menu-listing.html">
                    <h4 class="vertical-product-title">Paneer Biriyani</h4>
                </a>
                <h6 class="rating-star">
                    <span class="star"><i class="ri-star-s-fill"></i></span>4.9
                </h6>
            </div>
            <h5 class="product-items">With Pepsi</h5>
            <div class="location-distance d-flex align-items-center justify-content-between pt-sm-3 pt-2">
                <h5 class="place">Infosys</h5>
                <ul class="distance">
                    <li><i class="ri-map-pin-fill icon"></i> 1.2 km</li>
                    <li><i class="ri-time-fill icon"></i> 25 min</li>
                </ul>
            </div>
            <!-- Order and Price Buttons -->
            <div class="d-flex justify-content-between mt-3">
                <button class="btn btn-primary order-btn">Order Now</button>
                <button class="btn btn-outline-secondary price-btn">₹ 122.99</button>
            </div>
        </div>
    </div>
</div>



<!-- third Item  end-->





<!-- forth Item -->


<div class="col-xl-3 col-lg-4 col-md-6">
    <div class="vertical-product-box">
        <div class="vertical-product-box-img">
            <a href="menu-listing.html">
                <img class="product-img-top w-100 bg-img" src="assets/images/product/vp-12345679.png" alt="vp1">
            </a>
            <div class="offers">
                <h6>Real Discount</h6>
                <div class="d-flex align-items-center justify-content-between">
                    <h4>50 Off</h4>
                </div>
            </div>
        </div>
        <div class="vertical-product-body">
            <div class="d-flex align-items-center justify-content-between mt-sm-3 mt-2">
                <a href="menu-listing.html">
                    <h4 class="vertical-product-title">Veg Fried Rice</h4>
                </a>
                <h6 class="rating-star">
                    <span class="star"><i class="ri-star-s-fill"></i></span>3.9
                </h6>
            </div>
            <h5 class="product-items">With Paneer Manchurian</h5>
            <div class="location-distance d-flex align-items-center justify-content-between pt-sm-3 pt-2">
                <h5 class="place">Infosys</h5>
                <ul class="distance">
                    <li><i class="ri-map-pin-fill icon"></i> 1.2 km</li>
                    <li><i class="ri-time-fill icon"></i> 25 min</li>
                </ul>
            </div>
            <!-- Order and Price Buttons -->
            <div class="d-flex justify-content-between mt-3">
                <button class="btn btn-primary order-btn">Order Now</button>
                <button class="btn btn-outline-secondary price-btn">₹ 102.99</button>
            </div>
        </div>
    </div>
</div>



<!-- forth Item  end-->







            
            <!-- orders repeat -->
        </div>
    </div>
</section>
<!-- Veg section  end -->

    <!-- app section starts -->
    <section class="app-section">
        <div class="container">
            <div class="d-flex align-items-center">
                <div class="app-img">
                    <img class="img-fluid phone" src="assets/images/service-phone.png" alt="app-phone">
                </div>
                <div class="app-content">
                    <h2>Pehla Bites Food : Online & Mobile Ordering</h2>
                    <h5>
                        Get the app for free and place takeout orders online whenever you
                        want.
                    </h5>
                    <div class="app-buttons d-flex align-items-center gap-3">
                        <a href="https://www.apple.com/in/app-store/">
                            <img class="img-fluid app-btn" src="assets/images/svg/app-store.svg" alt="app-store">
                        </a>
                        <a href="https://play.google.com/store/apps">
                            <img class="img-fluid app-btn" src="assets/images/svg/google-play.svg" alt="google-play">
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- app section end -->

    <!-- footer section starts -->
    <footer class="footer-section section-t-space">
        <div class="subscribe-section">
            <div class="container">
                <div class="row">
                    <div class="col-lg-12">
                        <div class="subscribe-part">
                            <h5>
                                Don't pass up our fantastic discounts. email offers from all
                                of our best eateries
                            </h5>
                            <div class="position-relative w-100">
                                <input type="email" class="form-control subscribe-form-control"
                                    placeholder="Enter your Email">
                                <a href="#" class="btn theme-btn subscribe-btn mt-0">Subscribe Now</a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="container">
            <div class="main-footer">
                <div class="row g-3">
                    <div class="col-xl-4 col-lg-12">
                        <div class="footer-logo-part">
                            <img class="img-fluid logo" src="assets/logo2.png" alt="logo">
                            <p>
                                Welcome to our Pehla Bites ! Here, you can browse our
                                wide selection of products and place orders from the comfort
                                of your own home.
                            </p>
                            <div class="social-media-part">
                                <ul class="social-icon">
                                    <li>
                                        <a href="https://www.facebook.com/login/">
                                            <i class="ri-facebook-fill icon"></i>
                                        </a>
                                    </li>
                                    <li>
                                        <a href="https://twitter.com/i/flow/login">
                                            <i class="ri-twitter-fill icon"></i>
                                        </a>
                                    </li>
                                    <li>
                                        <a href="https://www.linkedin.com/login/">
                                            <i class="ri-linkedin-fill icon"></i>
                                        </a>
                                    </li>
                                    <li>
                                        <a href="https://www.instagram.com/accounts/login/">
                                            <i class="ri-instagram-fill icon"></i>
                                        </a>
                                    </li>
                                    <li>
                                        <a href="https://www.youtube.com/">
                                            <i class="ri-youtube-fill icon"></i>
                                        </a>
                                    </li>
                                </ul>
                            </div>
                        </div>
                    </div>
                    <div class="col-xl-8">
                        <div class="row g-3">
                            <div class="col-xl-3 col-lg-3 col-md-3 col-sm-6 col-12">
                                <div>
                                    <h5 class="footer-title">Company</h5>
                                    <ul class="content">
                                        <li>
                                            <a class="nav-links" href="about.html">
                                                <h6>About us</h6>
                                            </a>
                                        </li>
                                        <li>
                                            <a class="nav-links" href="contact.html">
                                                <h6>Contact us</h6>
                                            </a>
                                        </li>
                                        <li>
                                            <a class="nav-links" href="offer.html">
                                                <h6>Offer</h6>
                                            </a>
                                        </li>
                                        <li>
                                            <a class="nav-links" href="faq.html">
                                                <h6>FAQs</h6>
                                            </a>
                                        </li>
                                    </ul>
                                </div>
                            </div>
                            <div class="col-xl-3 col-lg-3 col-md-3 col-sm-6 col-12">
                                <div>
                                    <h5 class="footer-title">Account</h5>
                                    <ul class="content">
                                        <li>
                                            <a class="nav-links" href="my-order.html">
                                                <h6>My orders</h6>
                                            </a>
                                        </li>
                                        <li>
                                            <a class="nav-links" href="wishlist.html">
                                                <h6>Wishlist</h6>
                                            </a>
                                        </li>
                                        <li>
                                            <a class="nav-links" href="checkout.html">
                                                <h6>Shopping Cart</h6>
                                            </a>
                                        </li>
                                        <li>
                                            <a class="nav-links" href="saved-address.html">
                                                <h6>Saved Address</h6>
                                            </a>
                                        </li>
                                    </ul>
                                </div>
                            </div>
                            <div class="col-xl-3 col-lg-3 col-md-3 col-sm-6 col-12">
                                <div>
                                    <h5 class="footer-title">Useful links</h5>
                                    <ul class="content">
                                        <li>
                                            <a class="nav-links" href="blog-grid-left-sidebar.html">
                                                <h6>Blogs</h6>
                                            </a>
                                        </li>
                                        <li>
                                            <a class="nav-links" href="signin.html">
                                                <h6>Login</h6>
                                            </a>
                                        </li>
                                        <li>
                                            <a class="nav-links" href="signup.html">
                                                <h6>Register</h6>
                                            </a>
                                        </li>
                                        <li>
                                            <a class="nav-links" href="profile.html">
                                                <h6>Profile</h6>
                                            </a>
                                        </li>
                                        <li>
                                            <a class="nav-links" href="setting.html">
                                                <h6>Settings</h6>
                                            </a>
                                        </li>
                                    </ul>
                                </div>
                            </div>
                            <div class="col-xl-3 col-lg-3 col-md-3 col-sm-6 col-12">
                                <div>
                                    <h5 class="footer-title">Top Brands</h5>
                                    <ul class="content">
                                        <li>
                                            <a class="nav-links" href="menu-listing.html">
                                                <h6>PizzaBoy</h6>
                                            </a>
                                        </li>
                                        <li>
                                            <a class="nav-links" href="menu-listing.html">
                                                <h6>Saladish</h6>
                                            </a>
                                        </li>
                                        <li>
                                            <a class="nav-links" href="menu-listing.html">
                                                <h6>IcePops</h6>
                                            </a>
                                        </li>
                                        <li>
                                            <a class="nav-links" href="menu-listing.html">
                                                <h6>Maxican Hoy</h6>
                                            </a>
                                        </li>
                                        <li>
                                            <a class="nav-links" href="menu-listing.html">
                                                <h6>La Foodie</h6>
                                            </a>
                                        </li>
                                    </ul>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <div class="bottom-footer-part">
                <div class="d-flex align-items-center justify-content-between flex-wrap gap-2">
                    <h6>@ Copyright 2025 Pehla Bites. All rights Reserved.</h6>
                    <img class="img-fluid cards" src="assets/images/icons/footer-card.png" alt="card">
                </div>
            </div>
        </div>
    </footer>
    <!-- footer section end -->

    <!-- mobile fix menu start -->
    <div class="mobile-menu d-md-none d-block mobile-cart">
        <ul>
            <li class="active">
                <a href="index.html" class="menu-box">
                    <i class="ri-home-4-line"></i>
                    <span>Home</span>
                </a>
            </li>
            <li>
                <a href="wishlist.html" class="menu-box">
                    <i class="ri-heart-3-line"></i>
                    <span>Wishlist</span>
                </a>
            </li>
            <li>
                <a href="checkout.html" class="menu-box">
                    <i class="ri-shopping-cart-2-line"></i>
                    <span>Cart</span>
                </a>
            </li>
            <li>
                <a href="index.html" class="menu-box">
                    <i class="ri-user-line"></i>
                    <span>Profile</span>
                </a>
            </li>
        </ul>
    </div>
    <!-- mobile fix menu end -->

    <!-- theme btn start -->
   

    <!-- tap to top start -->
    <button class="scroll scroll-to-top">
        <i class="ri-arrow-up-s-line arrow"></i>
    </button>
    <!-- tap to top end -->

    <!-- location offcanvas start -->
    <div class="modal fade location-modal" id="location" data-bs-backdrop="static" data-bs-keyboard="false"
        tabindex="-1">
        <div class="modal-dialog modal-dialog-centered">
            <div class="modal-content">
                <div class="modal-header">
                    <div class="modal-title">
                        <h5 class="fw-semibold">Select a Location</h5>
                        <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
                    </div>
                </div>
                <div class="modal-body">
                    <div class="search-section">
                        <form class="form_search" role="form">
                            <input type="search" placeholder="Search Location" class="nav-search nav-search-field">
                        </form>
                    </div>
                    <a href="#!" class="current-location">
                        <div class="current-address">
                            <i class="ri-focus-3-line focus"></i>
                            <div>
                                <h5>Use current-location</h5>
                                <h6>Infosys , Patia , Bhubaneswar</h6>
                            </div>
                        </div>
                        <i class="ri-arrow-right-s-line arrow"></i>
                    </a>
                    <h5 class="mt-sm-3 mt-2 fw-medium recent-title dark-text">
                        Recent Location
                    </h5>
                    <a href="#!" class="recent-location">
                        <div class="recant-address">
                            <i class="ri-map-pin-line theme-color"></i>
                            <div>
                                <h5>Bhubaneswar</h5>
                                <h6>Trident, Patia, Bhubaneswar</h6>
                            </div>
                        </div>
                    </a>
                </div>
                <div class="modal-footer">
                    <a href="#" class="btn gray-btn" data-bs-dismiss="modal">Close</a>
                    <a href="#" class="btn theme-btn mt-0" data-bs-dismiss="modal">Save</a>
                </div>
            </div>
        </div>
    </div>
    <!-- location offcanvas end -->

    <!-- responsive space -->
    <div class="responsive-space"></div>
    <!-- responsive space -->

    <!-- bootstrap js -->
    <script src="assets/js/bootstrap.bundle.min.js"></script>

    <!-- footer accordion js -->
    <script src="assets/js/footer-accordion.js"></script>

    <!-- loader js -->
    <script src="assets/js/loader.js"></script>

    <!-- swiper js -->
    <script src="assets/js/swiper-bundle.min.js"></script>
    <script src="assets/js/custom-swiper.js"></script>

    <!-- menu offcanvas js -->
    <script src="assets/js/menu-offcanvas.js"></script>

    <!-- script js -->
    <script src="assets/js/script.js"></script>
</body>


</html>
