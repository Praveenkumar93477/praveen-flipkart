<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Flipkart Clone Online Shopping Site for Mobiles, Electronics & More. Best Offers!</title>
    <meta name="og_title" property="og:title" content="Flipkart Clone Online Shopping Site for Mobiles, Electronics &amp; More. Best Offers!">
    <meta name="Keywords" content="Flipkart Clone,Flipkart PHP,Flipkart Jigar Sable,Jigar,Flipkart Clone PHP,ecommerce PHP,PHP Projects,Online Shopping in India,online Shopping store,Online Shopping Site,Buy Online,Shop Online,Online Shopping,Flipkart">
    <meta name="Description" content="Flipkart Clone PHP Online store for Mobiles, Fashion, Electronics, Home Appliances Find the largest selection from all brands at the lowest prices in India. Payment options - Credit card, Debit card & more.">
    <!-- <link rel="canonical" href="https://"> -->
    <meta name="robots" content="index, follow">
    <meta name="language" content="English">
    <meta name="author" content="Jigar Sable">

    <link rel="shortcut icon" href="assets/images/favicon.ico" type="image/x-icon">
    <!-- font awesome cdn -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta2/css/all.min.css" integrity="sha512-YWzhKL2whUzgiheMoBFwW8CKV4qpHQAEuvilg9FAn5VJUDwKZZxkJNuGM4XkWuk94WCrrwslk8yWNGmY1EduTA==" crossorigin="anonymous" referrerpolicy="no-referrer" />

    <!-- material icons cdn -->
    <link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">

    <!-- owl carousel cdn -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/OwlCarousel2/2.3.4/assets/owl.carousel.min.css" integrity="sha512-tS3S5qG0BlhnQROyJXvNjeEM4UpMXHrQfTGmbQ1gKmelCxlSEBUaxhRBj/EFTzpbP4RVSrpEikbmdJobCvhE3g==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/OwlCarousel2/2.3.4/assets/owl.theme.default.min.css" integrity="sha512-sMXtMNL1zRzolHYKEujM2AqCLUR9F2C4/05cdbxjjLSRvMQIciEPCQZo++nk7go3BtSuK9kfa/s+a4f4i5pLkw==" crossorigin="anonymous" referrerpolicy="no-referrer" />

    <!-- custom build css -->
    <link rel="stylesheet" href="./style.css">
</head>
<body class="bg-gray-100">

<!-- header starts -->
<header class="bg-primary-blue fixed top-0 py-2.5 w-full z-10">

    <!-- navbar container -->
    <div class="w-full sm:w-9/12 px-4 m-auto flex justify-between items-center relative">

        <!-- logo & search container -->
        <div class="flex items-center flex-1">
        <a class="h-7 mr-4" href="/Flipkart/public/index.html">
            <img class="h-full w-full object-contain" src="https://static-assets-web.flixcart.com/www/linchpin/fk-cp-zion/img/fk-plus_3b0baa.png" alt="">
        </a>

        <!-- search container -->
        <div class="w-9/12 px-4 py-1.5 hidden sm:flex justify-between items-center shadow-md bg-white rounded-sm">
            <input class="text-sm flex-1 outline-none border-none placeholder-gray-500" type="text" placeholder="Search for products, brands and more">
            <span class="material-icons text-primary-blue">search</span>
        </div>
        <!-- search container -->
        </div>
        <!-- logo & search container -->

        <!-- right navs -->
        <div class="flex items-center justify-between gap-7 relative">
            <span class="userDropDown flex items-center text-white font-medium gap-1 cursor-pointer">Jhon
                <span class="material-icons text-sm transition-transform duration-100">expand_more</span>
            </span>

           <!-- dropdown navbar hover tabs -->
           <div class="userDropDownMenu hidden absolute w-60 -left-16 top-10 -left-24 ml-2 top-9 bg-white shadow-2xl rounded flex-col text-sm">
               <a class="pl-3 py-3.5 border-b flex gap-3 items-center hover:bg-gray-50 rounded-t" href="profile.html">
                    <span class="material-icons md-18 text-primary-blue">account_circle</span>
                    My Profile
               </a>

               <div class="pl-3 py-4 border-b flex justify-between pr-3 items-center text-sm hover:bg-gray-50 rounded-t">
                <span>New Customer?</span>
                <a href="signup.php" class="text-primary-blue hover:underline">Signup</a>
               </div>

               <a class="pl-3 py-3.5 border-b flex gap-3 items-center hover:bg-gray-50" href="#">
                    <span class="material-icons md-18 text-primary-blue">offline_bolt</span>
                    Supercoin Zone
               </a>
               <a class="pl-3 py-3.5 border-b flex gap-3 items-center hover:bg-gray-50" href="https://www.flipkart.com/plus/all-offers">
                    <span class="material-icons md-18 text-primary-blue">add_circle</span>
                    Flipkart Plus Zone
               </a>
               <a class="pl-3 py-3.5 border-b flex gap-3 items-center hover:bg-gray-50" href="orders.html">
                    <span class="material-icons md-18 text-primary-blue">shopping_bag</span>
                    Orders
               </a>
               <a class="pl-3 py-3.5 border-b flex gap-3 items-center hover:bg-gray-50" href="wishlist.html">
                    <span class="material-icons md-18 text-primary-blue">favorite</span>
                    Wishlist
                    <div class="ml-auto mr-3 bg-gray-100 p-0.5 px-2 text-gray-600 rounded">30</div>
               </a>
               <a class="pl-3 py-3.5 border-b flex gap-3 items-center hover:bg-gray-50" href="#">
                    <span class="material-icons md-18 text-primary-blue">chat</span>
                    My Chats
               </a>
               <a class="pl-3 py-3.5 border-b flex gap-3 items-center hover:bg-gray-50" href="https://www.flipkart.com/account/rewards">
                    <span class="material-icons md-18 text-primary-blue">redeem</span>
                    Coupons
               </a>
               <a class="pl-3 py-3.5 border-b flex gap-3 items-center hover:bg-gray-50" href="#">
                    <span class="material-icons md-18 text-primary-blue">account_balance_wallet</span>
                    Gift Cards
               </a>
               <a class="pl-3 py-3.5 border-b flex gap-3 items-center hover:bg-gray-50" href="#">
                    <span class="material-icons md-18 text-primary-blue">notifications</span>
                    Notifications
               </a>
               <a class="pl-3 py-3.5 flex gap-3 items-center hover:bg-gray-50 rounded-b" href="#">
                    <span class="material-icons md-18 text-primary-blue">power_settings_new</span>
                    Logout
               </a>
               <div class="absolute right-1/2 -top-2.5">
                    <div class="arrow_down"></div>
               </div>
           </div>
           <!-- dropdown navbar hover tabs -->

            <span class="moreDropDown hidden sm:flex items-center text-white font-medium gap-1 cursor-pointer">More
                <span class="material-icons text-sm transition-transform duration-100">expand_more</span>
            </span>
            

            <!-- dropdown navbar hover tabs -->
            <div class="moreDropDownMenu hidden absolute w-60 -right-12 -right-2 top-9 bg-white shadow-2xl rounded flex-col text-sm">
            <a class="pl-3 py-3.5 border-b flex gap-3 items-center hover:bg-gray-50 rounded-t" href="https://www.flipkart.com/communication-preferences/push">
                 <span class="material-icons md-18 text-primary-blue">notifications</span>
                 Notification Preferences
            </a>
            <a class="pl-3 py-3.5 border-b flex gap-3 items-center hover:bg-gray-50" href="https://seller.flipkart.com/sell-online">
                 <span class="material-icons md-18 text-primary-blue">business_center</span>
                 Sell on Flipkart
            </a>
            <a class="pl-3 py-3.5 border-b flex gap-3 items-center hover:bg-gray-50" href="https://www.flipkart.com/helpcentre">
                 <span class="material-icons md-18 text-primary-blue">live_help</span>
                 24x7 Customer Care
            </a>
            <a class="pl-3 py-3.5 border-b flex gap-3 items-center hover:bg-gray-50" href="https://advertising.flipkart.com">
                 <span class="material-icons md-18 text-primary-blue">trending_up</span>
                 Advertise
            </a>
            <a class="pl-3 py-3.5 flex gap-3 items-center hover:bg-gray-50 rounded-b" href="https://www.flipkart.com/mobile-apps">
                 <span class="material-icons md-18 text-primary-blue">download</span>
                 Download App
            </a>
            <div class="absolute right-1/2 -top-2.5">
                 <div class="arrow_down"></div>
            </div>
            </div>
            <!-- dropdown navbar hover tabs -->

            <a href="cart.html" class="flex items-center text-white font-medium gap-2 relative">
                <span class="material-icons">shopping_cart</span>
                <!-- badge count -->
                <div class="w-5 h-5 p-2 bg-red-500 text-xs rounded-full absolute -top-2 left-3 flex justify-center items-center border">
                    1
                </div>
                <!-- badge count -->
                Cart
            </a>
        </div>
        <!-- right navs -->

    </div>
    <!-- navbar container -->
</header>
<!-- header ends -->


    <!-- categories container header -->
    <section class="hidden sm:block bg-white mt-10 mb-4 min-w-full px-12 py-1 shadow overflow-hidden">

        <!-- categories container -->
        <div class="flex items-center justify-between mt-4">
            
        <!-- category -->
        <a class="flex flex-col gap-1 items-center p-2 group" href="#">
            <div class="h-16 w-16">
                <img class="h-full w-full object-contain" src="https://rukminim1.flixcart.com/flap/128/128/image/f15c02bfeb02d15d.png" alt="">
            </div>
            <span class="text-sm text-gray-800 font-medium group-hover:text-primary-blue">Top Offers</span>
        </a>
        <!-- category -->

        <!-- category -->
        <a class="flex flex-col gap-1 items-center p-2 group" href="#">
            <div class="h-16 w-16">
                <img class="h-full w-full object-contain" src="https://rukminim1.flixcart.com/flap/128/128/image/29327f40e9c4d26b.png" alt="">
            </div>
            <span class="text-sm text-gray-800 font-medium group-hover:text-primary-blue">Grocery</span>
        </a>
        <!-- category -->

        <!-- category -->
        <a class="flex flex-col gap-1 items-center p-2 group" href="#">
            <div class="h-16 w-16">
                <img class="h-full w-full object-contain" src="https://rukminim1.flixcart.com/flap/128/128/image/22fddf3c7da4c4f4.png" alt="">
            </div>
            <span class="text-sm text-gray-800 font-medium group-hover:text-primary-blue">Mobiles</span>
        </a>
        <!-- category -->

        <!-- category -->
        <a class="flex flex-col gap-1 items-center p-2 group" href="#">
            <div class="h-16 w-16">
                <img class="h-full w-full object-contain" src="https://rukminim1.flixcart.com/flap/128/128/image/82b3ca5fb2301045.png" alt="">
            </div>
            <span class="text-sm text-gray-800 font-medium group-hover:text-primary-blue flex items-center gap-0.5">Fashion <span class="material-icons md-16 group-hover:text-primary-blue">expand_more</span></span>
        </a>
        <!-- category -->

        <!-- category -->
        <a class="flex flex-col gap-1 items-center p-2 group" href="#">
            <div class="h-16 w-16">
                <img class="h-full w-full object-contain" src="https://rukminim1.flixcart.com/flap/128/128/image/69c6589653afdb9a.png" alt="">
            </div>
            <span class="text-sm text-gray-800 font-medium group-hover:text-primary-blue flex items-center gap-0.5">Electronics <span class="material-icons md-16 group-hover:text-primary-blue">expand_more</span></span>
        </a>
        <!-- category -->

        <!-- category -->
        <a class="flex flex-col gap-1 items-center p-2 group" href="#">
            <div class="h-16 w-16">
                <img class="h-full w-full object-contain" src="https://rukminim1.flixcart.com/flap/128/128/image/ab7e2b022a4587dd.jpg" alt="">
            </div>
            <span class="text-sm text-gray-800 font-medium group-hover:text-primary-blue flex items-center gap-0.5">Home <span class="material-icons md-16 group-hover:text-primary-blue">expand_more</span></span>
        </a>
        <!-- category -->

        <!-- category -->
        <a class="flex flex-col gap-1 items-center p-2 group" href="#">
            <div class="h-16 w-16">
                <img class="h-full w-full object-contain" src="https://rukminim1.flixcart.com/flap/128/128/image/0ff199d1bd27eb98.png" alt="">
            </div>
            <span class="text-sm text-gray-800 font-medium group-hover:text-primary-blue flex items-center gap-0.5">Appliances <span class="material-icons md-16 group-hover:text-primary-blue">expand_more</span></span>
        </a>
        <!-- category -->

        <!-- category -->
        <a class="flex flex-col gap-1 items-center p-2 group" href="#">
            <div class="h-16 w-16">
                <img class="h-full w-full object-contain" src="https://rukminim1.flixcart.com/flap/128/128/image/71050627a56b4693.png" alt="">
            </div>
            <span class="text-sm text-gray-800 font-medium group-hover:text-primary-blue">Travel</span>
        </a>
        <!-- category -->

        <!-- category -->
        <a class="flex flex-col gap-1 items-center p-2 group" href="#">
            <div class="h-16 w-16">
                <img class="h-full w-full object-contain" src="https://rukminim1.flixcart.com/flap/128/128/image/dff3f7adcf3a90c6.png" alt="">
            </div>
            <span class="text-sm text-gray-800 font-medium group-hover:text-primary-blue flex items-center gap-0.5">Beauty, Toys & More <span class="material-icons md-16 group-hover:text-primary-blue">expand_more</span></span>
        </a>
        <!-- category -->
        </div>
    </section>
    <!-- categories container header -->

    <!-- main sections starts -->
    <main class="flex flex-col gap-3 px-2 mt-2">

    <!-- banner section -->
    <section class="h-44 sm:h-72 w-full rounded-sm shadow owl-carousel owl-theme relative overflow-hidden" id="banner">
        <img class="h-44 sm:h-72 w-full object-cover" src="https://rukminim1.flixcart.com/flap/1688/280/image/9d50c7626a973408.jpg" alt="">
        <img class="h-44 sm:h-72 w-full object-cover" src="https://rukminim1.flixcart.com/flap/1688/280/image/9d50c7626a973408.jpg" alt="">
        <img class="h-44 sm:h-72 w-full object-cover" src="https://rukminim1.flixcart.com/flap/1688/280/image/9d50c7626a973408.jpg" alt="">
        <img class="h-44 sm:h-72 w-full object-cover" src="https://rukminim1.flixcart.com/flap/1688/280/image/9d50c7626a973408.jpg" alt="">
        <img class="h-44 sm:h-72 w-full object-cover" src="https://rukminim1.flixcart.com/flap/1688/280/image/9d50c7626a973408.jpg" alt="">
    </section>
    <!-- banner section -->
    

    <!-- top selection section -->
    <section id="topSelection" class="bg-white w-full shadow overflow-hidden">
        <!-- header -->
        <div class="flex px-6 py-3 justify-between items-center">
            <h1 class="text-xl font-medium">Top Selection</h1>
            <a href="#" class="bg-primary-blue text-xs font-medium text-white px-5 py-2.5 rounded-sm shadow-lg">VIEW ALL</a>
        </div>
        <hr>
        <!-- header -->
        
        <!-- products container -->
        <div class="flex items-center justify-between owl-carousel owl-theme relative">

            <!-- one product -->
            <a class="flex flex-col items-center gap-2 p-6" href="#">
                <div class="w-36 h-36 transform hover:scale-110 transition-transform duration-100 ease-out">
                    <img class="w-full h-full object-contain" src="https://rukminim1.flixcart.com/image/150/150/ki3gknk0-0/backpack/t/n/i/spacy-unisex-backpack-with-rain-cover-and-reflective-strip-p-041-original-imafxyypsycttkeb.jpeg" alt="">
                </div>
                <h2 class="font-medium text-sm mt-2">Kitchen Appliances</h2>
                <span class="text-primary-green text-sm">Grab Now</span>
            </a>
            
            <!-- one product -->
            <a class="flex flex-col items-center gap-2 p-6" href="#">
                <div class="w-36 h-36 transform hover:scale-110 transition-transform duration-100 ease-out">
                    <img class="w-full h-full object-contain" src="https://rukminim1.flixcart.com/image/150/150/ki3gknk0-0/backpack/t/n/i/spacy-unisex-backpack-with-rain-cover-and-reflective-strip-p-041-original-imafxyypsycttkeb.jpeg" alt="">
                </div>
                <h2 class="font-medium text-sm mt-2">Kitchen Appliances</h2>
                <span class="text-primary-green text-sm">Grab Now</span>
            </a>
            <!-- one product -->
            <a class="flex flex-col items-center gap-2 p-6" href="#">
                <div class="w-36 h-36 transform hover:scale-110 transition-transform duration-100 ease-out">
                    <img class="w-full h-full object-contain" src="https://rukminim1.flixcart.com/image/150/150/ki3gknk0-0/backpack/t/n/i/spacy-unisex-backpack-with-rain-cover-and-reflective-strip-p-041-original-imafxyypsycttkeb.jpeg" alt="">
                </div>
                <h2 class="font-medium text-sm mt-2">Kitchen Appliances</h2>
                <span class="text-primary-green text-sm">Grab Now</span>
            </a>
            <!-- one product -->
            <a class="flex flex-col items-center gap-2 p-6" href="#">
                <div class="w-36 h-36 transform hover:scale-110 transition-transform duration-100 ease-out">
                    <img class="w-full h-full object-contain" src="https://rukminim1.flixcart.com/image/150/150/ki3gknk0-0/backpack/t/n/i/spacy-unisex-backpack-with-rain-cover-and-reflective-strip-p-041-original-imafxyypsycttkeb.jpeg" alt="">
                </div>
                <h2 class="font-medium text-sm mt-2">Kitchen Appliances</h2>
                <span class="text-primary-green text-sm">Grab Now</span>
            </a>
            <!-- one product -->
            <a class="flex flex-col items-center gap-2 p-6" href="#">
                <div class="w-36 h-36 transform hover:scale-110 transition-transform duration-100 ease-out">
                    <img class="w-full h-full object-contain" src="https://rukminim1.flixcart.com/image/150/150/ki3gknk0-0/backpack/t/n/i/spacy-unisex-backpack-with-rain-cover-and-reflective-strip-p-041-original-imafxyypsycttkeb.jpeg" alt="">
                </div>
                <h2 class="font-medium text-sm mt-2">Kitchen Appliances</h2>
                <span class="text-primary-green text-sm">Grab Now</span>
            </a>
            <!-- one product -->
            <a class="flex flex-col items-center gap-2 p-6" href="#">
                <div class="w-36 h-36 transform hover:scale-110 transition-transform duration-100 ease-out">
                    <img class="w-full h-full object-contain" src="https://rukminim1.flixcart.com/image/150/150/ki3gknk0-0/backpack/t/n/i/spacy-unisex-backpack-with-rain-cover-and-reflective-strip-p-041-original-imafxyypsycttkeb.jpeg" alt="">
                </div>
                <h2 class="font-medium text-sm mt-2">Kitchen Appliances</h2>
                <span class="text-primary-green text-sm">Grab Now</span>
            </a>
            <!-- one product -->
            <a class="flex flex-col items-center gap-2 p-6" href="#">
                <div class="w-36 h-36 transform hover:scale-110 transition-transform duration-100 ease-out">
                    <img class="w-full h-full object-contain" src="https://rukminim1.flixcart.com/image/150/150/ki3gknk0-0/backpack/t/n/i/spacy-unisex-backpack-with-rain-cover-and-reflective-strip-p-041-original-imafxyypsycttkeb.jpeg" alt="">
                </div>
                <h2 class="font-medium text-sm mt-2">Kitchen Appliances</h2>
                <span class="text-primary-green text-sm">Grab Now</span>
            </a>
            <!-- one product -->
            <a class="flex flex-col items-center gap-2 p-6" href="#">
                <div class="w-36 h-36 transform hover:scale-110 transition-transform duration-100 ease-out">
                    <img class="w-full h-full object-contain" src="https://rukminim1.flixcart.com/image/150/150/ki3gknk0-0/backpack/t/n/i/spacy-unisex-backpack-with-rain-cover-and-reflective-strip-p-041-original-imafxyypsycttkeb.jpeg" alt="">
                </div>
                <h2 class="font-medium text-sm mt-2">Kitchen Appliances</h2>
                <span class="text-primary-green text-sm">Grab Now</span>
            </a>
            <!-- one product -->
            <a class="flex flex-col items-center gap-2 p-6" href="#">
                <div class="w-36 h-36 transform hover:scale-110 transition-transform duration-100 ease-out">
                    <img class="w-full h-full object-contain" src="https://rukminim1.flixcart.com/image/150/150/ki3gknk0-0/backpack/t/n/i/spacy-unisex-backpack-with-rain-cover-and-reflective-strip-p-041-original-imafxyypsycttkeb.jpeg" alt="">
                </div>
                <h2 class="font-medium text-sm mt-2">Kitchen Appliances</h2>
                <span class="text-primary-green text-sm">Grab Now</span>
            </a>
        </div>
        <!-- products container -->
    </section>
    <!-- top selection section -->

    <!-- recommended items section -->
    <section id="recommended" class="bg-white w-full shadow overflow-hidden">
        <!-- header -->
        <div class="flex px-6 py-4 justify-between items-center">
            <div class="title flex flex-col gap-0.5">
                <h1 class="text-xl font-medium">Recommended Items</h1>
                <p class="text-sm text-gray-400">Inspired by Your Interest</p>
            </div>
            <a href="#" class="bg-primary-blue text-xs font-medium text-white px-5 py-2.5 rounded-sm shadow-lg">VIEW ALL</a>
        </div>
        <hr>
        <!-- header -->
        
        <!-- products container -->
        <div class="flex items-center justify-between owl-carousel owl-theme p-1 relative">

            <!-- one product -->
            <div class="flex flex-col items-center gap-2 px-2 py-6 relative">
                <!-- image & product title -->
                <a href="#" class="flex flex-col items-center text-center group">
                <div class="w-36 h-36">
                    <img class="w-full h-full object-contain" src="https://rukminim1.flixcart.com/image/312/312/kk1h5e80/refrigerator-new/g/y/y/rt28a3021s8-hl-1-2021-samsung-original-imafzhedkazavggn.jpeg" alt="">
                </div>
                <h2 class="text-sm mt-4 group-hover:text-primary-blue">SAMSUNG 230 L Direct Cool Single Door 3 Star Refrigerator</h2>
                </a>
                <!-- image & product title -->

                <!-- product description -->
                <div class="flex flex-col gap-2 items-center">
                        <!-- rating badge -->
                        <span class="text-sm text-gray-500 font-medium flex gap-2 items-center">
                            <span class="text-xs px-1.5 py-0.5 bg-primary-green rounded-sm text-white flex items-center gap-0.5">4.3 <i class="material-icons md-12">star</i></span>
                            <span>(7,345)</span>
                        </span>
                        <!-- rating badge -->

                        <!-- price container -->
                        <div class="flex items-center gap-1.5 text-md font-medium">
                            <span>₹16,790</span>
                            <span class="text-gray-500 line-through text-xs">₹18,890</span>
                            <span class="text-xs text-primary-green">15%&nbsp;off</span>
                        </div>
                        <!-- price container -->
                </div>
                <!-- product description -->

                <!-- wishlist badge -->
                <i class="material-icons absolute top-5 right-2 text-gray-300 cursor-pointer hover:text-red-500 md-16">favorite</i>
                <!-- wishlist badge -->

            </div>

            <!-- one product -->
            <div class="flex flex-col items-center gap-2 px-2 py-6 relative">
                <!-- image & product title -->
                <a href="#" class="flex flex-col items-center text-center group">
                <div class="w-36 h-36">
                    <img class="w-full h-full object-contain" src="https://rukminim1.flixcart.com/image/312/312/kk1h5e80/refrigerator-new/g/y/y/rt28a3021s8-hl-1-2021-samsung-original-imafzhedkazavggn.jpeg" alt="">
                </div>
                <h2 class="text-sm mt-4 group-hover:text-primary-blue">SAMSUNG 230 L Direct Cool Single Door 3 Star Refrigerator</h2>
                </a>
                <!-- image & product title -->

                <!-- product description -->
                <div class="flex flex-col gap-2 items-center">
                        <!-- rating badge -->
                        <span class="text-sm text-gray-500 font-medium flex gap-2 items-center">
                            <span class="text-xs px-1.5 py-0.5 bg-primary-green rounded-sm text-white flex items-center gap-0.5">4.3 <i class="material-icons md-12">star</i></span>
                            <span>(7,345)</span>
                        </span>
                        <!-- rating badge -->

                        <!-- price container -->
                        <div class="flex items-center gap-1.5 text-md font-medium">
                            <span>₹16,790</span>
                            <span class="text-gray-500 line-through text-xs">₹18,890</span>
                            <span class="text-xs text-primary-green">15%&nbsp;off</span>
                        </div>
                        <!-- price container -->
                </div>
                <!-- product description -->

                <!-- wishlist badge -->
                <i class="material-icons absolute top-5 right-2 text-gray-300 cursor-pointer hover:text-red-500 md-16">favorite</i>
                <!-- wishlist badge -->

            </div>

            <!-- one product -->
            <div class="flex flex-col items-center gap-2 px-2 py-6 relative">
                <!-- image & product title -->
                <a href="#" class="flex flex-col items-center text-center group">
                <div class="w-36 h-36">
                    <img class="w-full h-full object-contain" src="https://rukminim1.flixcart.com/image/312/312/kk1h5e80/refrigerator-new/g/y/y/rt28a3021s8-hl-1-2021-samsung-original-imafzhedkazavggn.jpeg" alt="">
                </div>
                <h2 class="text-sm mt-4 group-hover:text-primary-blue">SAMSUNG 230 L Direct Cool Single Door 3 Star Refrigerator</h2>
                </a>
                <!-- image & product title -->

                <!-- product description -->
                <div class="flex flex-col gap-2 items-center">
                        <!-- rating badge -->
                        <span class="text-sm text-gray-500 font-medium flex gap-2 items-center">
                            <span class="text-xs px-1.5 py-0.5 bg-primary-green rounded-sm text-white flex items-center gap-0.5">4.3 <i class="material-icons md-12">star</i></span>
                            <span>(7,345)</span>
                        </span>
                        <!-- rating badge -->

                        <!-- price container -->
                        <div class="flex items-center gap-1.5 text-md font-medium">
                            <span>₹16,790</span>
                            <span class="text-gray-500 line-through text-xs">₹18,890</span>
                            <span class="text-xs text-primary-green">15%&nbsp;off</span>
                        </div>
                        <!-- price container -->
                </div>
                <!-- product description -->

                <!-- wishlist badge -->
                <i class="material-icons absolute top-5 right-2 text-gray-300 cursor-pointer hover:text-red-500 md-16">favorite</i>
                <!-- wishlist badge -->

            </div>

            <!-- one product -->
            <div class="flex flex-col items-center gap-2 px-2 py-6 relative">
                <!-- image & product title -->
                <a href="#" class="flex flex-col items-center text-center group">
                <div class="w-36 h-36">
                    <img class="w-full h-full object-contain" src="https://rukminim1.flixcart.com/image/312/312/kk1h5e80/refrigerator-new/g/y/y/rt28a3021s8-hl-1-2021-samsung-original-imafzhedkazavggn.jpeg" alt="">
                </div>
                <h2 class="text-sm mt-4 group-hover:text-primary-blue">SAMSUNG 230 L Direct Cool Single Door 3 Star Refrigerator</h2>
                </a>
                <!-- image & product title -->

                <!-- product description -->
                <div class="flex flex-col gap-2 items-center">
                        <!-- rating badge -->
                        <span class="text-sm text-gray-500 font-medium flex gap-2 items-center">
                            <span class="text-xs px-1.5 py-0.5 bg-primary-green rounded-sm text-white flex items-center gap-0.5">4.3 <i class="material-icons md-12">star</i></span>
                            <span>(7,345)</span>
                        </span>
                        <!-- rating badge -->

                        <!-- price container -->
                        <div class="flex items-center gap-1.5 text-md font-medium">
                            <span>₹16,790</span>
                            <span class="text-gray-500 line-through text-xs">₹18,890</span>
                            <span class="text-xs text-primary-green">15%&nbsp;off</span>
                        </div>
                        <!-- price container -->
                </div>
                <!-- product description -->

                <!-- wishlist badge -->
                <i class="material-icons absolute top-5 right-2 text-gray-300 cursor-pointer hover:text-red-500 md-16">favorite</i>
                <!-- wishlist badge -->

            </div>

            <!-- one product -->
            <div class="flex flex-col items-center gap-2 px-2 py-6 relative">
                <!-- image & product title -->
                <a href="#" class="flex flex-col items-center text-center group">
                <div class="w-36 h-36">
                    <img class="w-full h-full object-contain" src="https://rukminim1.flixcart.com/image/312/312/kk1h5e80/refrigerator-new/g/y/y/rt28a3021s8-hl-1-2021-samsung-original-imafzhedkazavggn.jpeg" alt="">
                </div>
                <h2 class="text-sm mt-4 group-hover:text-primary-blue">SAMSUNG 230 L Direct Cool Single Door 3 Star Refrigerator</h2>
                </a>
                <!-- image & product title -->

                <!-- product description -->
                <div class="flex flex-col gap-2 items-center">
                        <!-- rating badge -->
                        <span class="text-sm text-gray-500 font-medium flex gap-2 items-center">
                            <span class="text-xs px-1.5 py-0.5 bg-primary-green rounded-sm text-white flex items-center gap-0.5">4.3 <i class="material-icons md-12">star</i></span>
                            <span>(7,345)</span>
                        </span>
                        <!-- rating badge -->

                        <!-- price container -->
                        <div class="flex items-center gap-1.5 text-md font-medium">
                            <span>₹16,790</span>
                            <span class="text-gray-500 line-through text-xs">₹18,890</span>
                            <span class="text-xs text-primary-green">15%&nbsp;off</span>
                        </div>
                        <!-- price container -->
                </div>
                <!-- product description -->

                <!-- wishlist badge -->
                <i class="material-icons absolute top-5 right-2 text-gray-300 cursor-pointer hover:text-red-500 md-16">favorite</i>
                <!-- wishlist badge -->

            </div>

            <!-- one product -->
            <div class="flex flex-col items-center gap-2 px-2 py-6 relative">
                <!-- image & product title -->
                <a href="#" class="flex flex-col items-center text-center group">
                <div class="w-36 h-36">
                    <img class="w-full h-full object-contain" src="https://rukminim1.flixcart.com/image/312/312/kk1h5e80/refrigerator-new/g/y/y/rt28a3021s8-hl-1-2021-samsung-original-imafzhedkazavggn.jpeg" alt="">
                </div>
                <h2 class="text-sm mt-4 group-hover:text-primary-blue">SAMSUNG 230 L Direct Cool Single Door 3 Star Refrigerator</h2>
                </a>
                <!-- image & product title -->

                <!-- product description -->
                <div class="flex flex-col gap-2 items-center">
                        <!-- rating badge -->
                        <span class="text-sm text-gray-500 font-medium flex gap-2 items-center">
                            <span class="text-xs px-1.5 py-0.5 bg-primary-green rounded-sm text-white flex items-center gap-0.5">4.3 <i class="material-icons md-12">star</i></span>
                            <span>(7,345)</span>
                        </span>
                        <!-- rating badge -->

                        <!-- price container -->
                        <div class="flex items-center gap-1.5 text-md font-medium">
                            <span>₹16,790</span>
                            <span class="text-gray-500 line-through text-xs">₹18,890</span>
                            <span class="text-xs text-primary-green">15%&nbsp;off</span>
                        </div>
                        <!-- price container -->
                </div>
                <!-- product description -->

                <!-- wishlist badge -->
                <i class="material-icons absolute top-5 right-2 text-gray-300 cursor-pointer hover:text-red-500 md-16">favorite</i>
                <!-- wishlist badge -->

            </div>

            <!-- one product -->
            <div class="flex flex-col items-center gap-2 px-2 py-6 relative">
                <!-- image & product title -->
                <a href="#" class="flex flex-col items-center text-center group">
                <div class="w-36 h-36">
                    <img class="w-full h-full object-contain" src="https://rukminim1.flixcart.com/image/312/312/kk1h5e80/refrigerator-new/g/y/y/rt28a3021s8-hl-1-2021-samsung-original-imafzhedkazavggn.jpeg" alt="">
                </div>
                <h2 class="text-sm mt-4 group-hover:text-primary-blue">SAMSUNG 230 L Direct Cool Single Door 3 Star Refrigerator</h2>
                </a>
                <!-- image & product title -->

                <!-- product description -->
                <div class="flex flex-col gap-2 items-center">
                        <!-- rating badge -->
                        <span class="text-sm text-gray-500 font-medium flex gap-2 items-center">
                            <span class="text-xs px-1.5 py-0.5 bg-primary-green rounded-sm text-white flex items-center gap-0.5">4.3 <i class="material-icons md-12">star</i></span>
                            <span>(7,345)</span>
                        </span>
                        <!-- rating badge -->

                        <!-- price container -->
                        <div class="flex items-center gap-1.5 text-md font-medium">
                            <span>₹16,790</span>
                            <span class="text-gray-500 line-through text-xs">₹18,890</span>
                            <span class="text-xs text-primary-green">15%&nbsp;off</span>
                        </div>
                        <!-- price container -->
                </div>
                <!-- product description -->

                <!-- wishlist badge -->
                <i class="material-icons absolute top-5 right-2 text-gray-300 cursor-pointer hover:text-red-500 md-16">favorite</i>
                <!-- wishlist badge -->

            </div>

            <!-- one product -->
            <div class="flex flex-col items-center gap-2 px-2 py-6 relative">
                <!-- image & product title -->
                <a href="#" class="flex flex-col items-center text-center group">
                <div class="w-36 h-36">
                    <img class="w-full h-full object-contain" src="https://rukminim1.flixcart.com/image/312/312/kk1h5e80/refrigerator-new/g/y/y/rt28a3021s8-hl-1-2021-samsung-original-imafzhedkazavggn.jpeg" alt="">
                </div>
                <h2 class="text-sm mt-4 group-hover:text-primary-blue">SAMSUNG 230 L Direct Cool Single Door 3 Star Refrigerator</h2>
                </a>
                <!-- image & product title -->

                <!-- product description -->
                <div class="flex flex-col gap-2 items-center">
                        <!-- rating badge -->
                        <span class="text-sm text-gray-500 font-medium flex gap-2 items-center">
                            <span class="text-xs px-1.5 py-0.5 bg-primary-green rounded-sm text-white flex items-center gap-0.5">4.3 <i class="material-icons md-12">star</i></span>
                            <span>(7,345)</span>
                        </span>
                        <!-- rating badge -->

                        <!-- price container -->
                        <div class="flex items-center gap-1.5 text-md font-medium">
                            <span>₹16,790</span>
                            <span class="text-gray-500 line-through text-xs">₹18,890</span>
                            <span class="text-xs text-primary-green">15%&nbsp;off</span>
                        </div>
                        <!-- price container -->
                </div>
                <!-- product description -->

                <!-- wishlist badge -->
                <i class="material-icons absolute top-5 right-2 text-gray-300 cursor-pointer hover:text-red-500 md-16">favorite</i>
                <!-- wishlist badge -->

            </div>

        </div>
        <!-- products container -->
    </section>
    <!-- recommended items section -->

    <!-- discounts for you section -->
    <section id="topSelection" class="bg-white w-full shadow overflow-hidden">
        <!-- header -->
        <div class="flex px-6 py-3 justify-between items-center">
            <h1 class="text-xl font-medium">Discounts for You</h1>
            <a href="#" class="bg-primary-blue text-xs font-medium text-white px-5 py-2.5 rounded-sm shadow-lg">VIEW ALL</a>
        </div>
        <hr>
        <!-- header -->
        
        <!-- products container -->
        <div class="flex items-center justify-between owl-carousel owl-theme relative">

            <!-- one product -->
            <a class="flex flex-col items-center gap-1.5 p-6" href="#">
                <div class="w-36 h-36 transform hover:scale-110 transition-transform duration-100 ease-out">
                    <img class="w-full h-full object-contain" src="https://rukminim1.flixcart.com/image/150/150/k0wqwsw0/electric-kettle/g/t/d/butterfly-rapid-kettle-1-5-litre-wave-750-ml-water-bottle-rapid-original-imafkfy7zaekbubs.jpeg" alt="">
                </div>
                <h2 class="font-medium text-sm mt-2">Kitchen Appliances</h2>
                <span class="text-primary-green text-sm">Min 40% Off</span>
                <span class="text-gray-500 text-sm">Buy Now!</span>
            </a>

            <!-- one product -->
            <a class="flex flex-col items-center gap-1.5 p-6" href="#">
                <div class="w-36 h-36 transform hover:scale-110 transition-transform duration-100 ease-out">
                    <img class="w-full h-full object-contain" src="https://rukminim1.flixcart.com/image/150/150/k0wqwsw0/electric-kettle/g/t/d/butterfly-rapid-kettle-1-5-litre-wave-750-ml-water-bottle-rapid-original-imafkfy7zaekbubs.jpeg" alt="">
                </div>
                <h2 class="font-medium text-sm mt-2">Kitchen Appliances</h2>
                <span class="text-primary-green text-sm">Min 40% Off</span>
                <span class="text-gray-500 text-sm">Buy Now!</span>
            </a>

            <!-- one product -->
            <a class="flex flex-col items-center gap-1.5 p-6" href="#">
                <div class="w-36 h-36 transform hover:scale-110 transition-transform duration-100 ease-out">
                    <img class="w-full h-full object-contain" src="https://rukminim1.flixcart.com/image/150/150/k0wqwsw0/electric-kettle/g/t/d/butterfly-rapid-kettle-1-5-litre-wave-750-ml-water-bottle-rapid-original-imafkfy7zaekbubs.jpeg" alt="">
                </div>
                <h2 class="font-medium text-sm mt-2">Kitchen Appliances</h2>
                <span class="text-primary-green text-sm">Min 40% Off</span>
                <span class="text-gray-500 text-sm">Buy Now!</span>
            </a>

            <!-- one product -->
            <a class="flex flex-col items-center gap-1.5 p-6" href="#">
                <div class="w-36 h-36 transform hover:scale-110 transition-transform duration-100 ease-out">
                    <img class="w-full h-full object-contain" src="https://rukminim1.flixcart.com/image/150/150/k0wqwsw0/electric-kettle/g/t/d/butterfly-rapid-kettle-1-5-litre-wave-750-ml-water-bottle-rapid-original-imafkfy7zaekbubs.jpeg" alt="">
                </div>
                <h2 class="font-medium text-sm mt-2">Kitchen Appliances</h2>
                <span class="text-primary-green text-sm">Min 40% Off</span>
                <span class="text-gray-500 text-sm">Buy Now!</span>
            </a>

            <!-- one product -->
            <a class="flex flex-col items-center gap-1.5 p-6" href="#">
                <div class="w-36 h-36 transform hover:scale-110 transition-transform duration-100 ease-out">
                    <img class="w-full h-full object-contain" src="https://rukminim1.flixcart.com/image/150/150/k0wqwsw0/electric-kettle/g/t/d/butterfly-rapid-kettle-1-5-litre-wave-750-ml-water-bottle-rapid-original-imafkfy7zaekbubs.jpeg" alt="">
                </div>
                <h2 class="font-medium text-sm mt-2">Kitchen Appliances</h2>
                <span class="text-primary-green text-sm">Min 40% Off</span>
                <span class="text-gray-500 text-sm">Buy Now!</span>
            </a>

            <!-- one product -->
            <a class="flex flex-col items-center gap-1.5 p-6" href="#">
                <div class="w-36 h-36 transform hover:scale-110 transition-transform duration-100 ease-out">
                    <img class="w-full h-full object-contain" src="https://rukminim1.flixcart.com/image/150/150/k0wqwsw0/electric-kettle/g/t/d/butterfly-rapid-kettle-1-5-litre-wave-750-ml-water-bottle-rapid-original-imafkfy7zaekbubs.jpeg" alt="">
                </div>
                <h2 class="font-medium text-sm mt-2">Kitchen Appliances</h2>
                <span class="text-primary-green text-sm">Min 40% Off</span>
                <span class="text-gray-500 text-sm">Buy Now!</span>
            </a>

            <!-- one product -->
            <a class="flex flex-col items-center gap-1.5 p-6" href="#">
                <div class="w-36 h-36 transform hover:scale-110 transition-transform duration-100 ease-out">
                    <img class="w-full h-full object-contain" src="https://rukminim1.flixcart.com/image/150/150/k0wqwsw0/electric-kettle/g/t/d/butterfly-rapid-kettle-1-5-litre-wave-750-ml-water-bottle-rapid-original-imafkfy7zaekbubs.jpeg" alt="">
                </div>
                <h2 class="font-medium text-sm mt-2">Kitchen Appliances</h2>
                <span class="text-primary-green text-sm">Min 40% Off</span>
                <span class="text-gray-500 text-sm">Buy Now!</span>
            </a>

            <!-- one product -->
            <a class="flex flex-col items-center gap-1.5 p-6" href="#">
                <div class="w-36 h-36 transform hover:scale-110 transition-transform duration-100 ease-out">
                    <img class="w-full h-full object-contain" src="https://rukminim1.flixcart.com/image/150/150/k0wqwsw0/electric-kettle/g/t/d/butterfly-rapid-kettle-1-5-litre-wave-750-ml-water-bottle-rapid-original-imafkfy7zaekbubs.jpeg" alt="">
                </div>
                <h2 class="font-medium text-sm mt-2">Kitchen Appliances</h2>
                <span class="text-primary-green text-sm">Min 40% Off</span>
                <span class="text-gray-500 text-sm">Buy Now!</span>
            </a>

            <!-- one product -->
            <a class="flex flex-col items-center gap-1.5 p-6" href="#">
                <div class="w-36 h-36 transform hover:scale-110 transition-transform duration-100 ease-out">
                    <img class="w-full h-full object-contain" src="https://rukminim1.flixcart.com/image/150/150/k0wqwsw0/electric-kettle/g/t/d/butterfly-rapid-kettle-1-5-litre-wave-750-ml-water-bottle-rapid-original-imafkfy7zaekbubs.jpeg" alt="">
                </div>
                <h2 class="font-medium text-sm mt-2">Kitchen Appliances</h2>
                <span class="text-primary-green text-sm">Min 40% Off</span>
                <span class="text-gray-500 text-sm">Buy Now!</span>
            </a>

            <!-- one product -->
            <a class="flex flex-col items-center gap-1.5 p-6" href="#">
                <div class="w-36 h-36 transform hover:scale-110 transition-transform duration-100 ease-out">
                    <img class="w-full h-full object-contain" src="https://rukminim1.flixcart.com/image/150/150/k0wqwsw0/electric-kettle/g/t/d/butterfly-rapid-kettle-1-5-litre-wave-750-ml-water-bottle-rapid-original-imafkfy7zaekbubs.jpeg" alt="">
                </div>
                <h2 class="font-medium text-sm mt-2">Kitchen Appliances</h2>
                <span class="text-primary-green text-sm">Min 40% Off</span>
                <span class="text-gray-500 text-sm">Buy Now!</span>
            </a>

        </div>
        <!-- products container -->
    </section>
    <!-- discounts for you section -->

    <!-- you may like section -->
    <section id="recommended" class="bg-white w-full shadow overflow-hidden">
        <!-- header -->
        <div class="flex px-6 py-4 justify-between items-center">
            <div class="title flex flex-col gap-0.5">
                <h1 class="text-xl font-medium">You May Like...</h1>
                <p class="text-sm text-gray-400">Based on Your Interest</p>
            </div>
            <a href="#" class="bg-primary-blue text-xs font-medium text-white px-5 py-2.5 rounded-sm shadow-lg">VIEW ALL</a>
        </div>
        <hr>
        <!-- header -->
        
        <!-- products container -->
        <div class="flex items-center justify-between owl-carousel owl-theme p-1 relative">

            <!-- one product -->
            <div class="flex flex-col items-center gap-2 px-2 py-6 relative">
                <!-- image & product title -->
                <a href="#" class="flex flex-col items-center text-center group">
                <div class="w-36 h-36">
                    <img class="w-full h-full object-contain" src="https://rukminim1.flixcart.com/image/312/312/kh0vonk0/sauce-ketchup/h/b/z/450-tomato-pouch-ketchup-surabhi-original-imafx4qktzguhhwy.jpeg" alt="">
                </div>
                <h2 class="text-sm mt-4 group-hover:text-primary-blue">SAMSUNG 230 L Direct Cool Single Door 3 Star Refrigerator</h2>
                </a>
                <!-- image & product title -->

                <!-- product description -->
                <div class="flex flex-col gap-2 items-center">
                        <!-- rating badge -->
                        <span class="text-sm text-gray-500 font-medium flex gap-2 items-center">
                            <span class="text-xs px-1.5 py-0.5 bg-primary-green rounded-sm text-white flex items-center gap-0.5">4.3 <i class="material-icons md-12">star</i></span>
                            <span>(7,345)</span>
                        </span>
                        <!-- rating badge -->

                        <!-- price container -->
                        <div class="flex items-center gap-1.5 text-md font-medium">
                            <span>₹16,790</span>
                            <span class="text-gray-500 line-through text-xs">₹18,890</span>
                            <span class="text-xs text-primary-green">15%&nbsp;off</span>
                        </div>
                        <!-- price container -->
                </div>
                <!-- product description -->

                <!-- wishlist badge -->
                <i class="material-icons absolute top-5 right-2 text-gray-300 cursor-pointer hover:text-red-500 md-16">favorite</i>
                <!-- wishlist badge -->

            </div>

            <!-- one product -->
            <div class="flex flex-col items-center gap-2 px-2 py-6 relative">
                <!-- image & product title -->
                <a href="#" class="flex flex-col items-center text-center group">
                <div class="w-36 h-36">
                    <img class="w-full h-full object-contain" src="https://rukminim1.flixcart.com/image/312/312/kh0vonk0/sauce-ketchup/h/b/z/450-tomato-pouch-ketchup-surabhi-original-imafx4qktzguhhwy.jpeg" alt="">
                </div>
                <h2 class="text-sm mt-4 group-hover:text-primary-blue">SAMSUNG 230 L Direct Cool Single Door 3 Star Refrigerator</h2>
                </a>
                <!-- image & product title -->

                <!-- product description -->
                <div class="flex flex-col gap-2 items-center">
                        <!-- rating badge -->
                        <span class="text-sm text-gray-500 font-medium flex gap-2 items-center">
                            <span class="text-xs px-1.5 py-0.5 bg-primary-green rounded-sm text-white flex items-center gap-0.5">4.3 <i class="material-icons md-12">star</i></span>
                            <span>(7,345)</span>
                        </span>
                        <!-- rating badge -->

                        <!-- price container -->
                        <div class="flex items-center gap-1.5 text-md font-medium">
                            <span>₹16,790</span>
                            <span class="text-gray-500 line-through text-xs">₹18,890</span>
                            <span class="text-xs text-primary-green">15%&nbsp;off</span>
                        </div>
                        <!-- price container -->
                </div>
                <!-- product description -->

                <!-- wishlist badge -->
                <i class="material-icons absolute top-5 right-2 text-gray-300 cursor-pointer hover:text-red-500 md-16">favorite</i>
                <!-- wishlist badge -->

            </div>

            <!-- one product -->
            <div class="flex flex-col items-center gap-2 px-2 py-6 relative">
                <!-- image & product title -->
                <a href="#" class="flex flex-col items-center text-center group">
                <div class="w-36 h-36">
                    <img class="w-full h-full object-contain" src="https://rukminim1.flixcart.com/image/312/312/kh0vonk0/sauce-ketchup/h/b/z/450-tomato-pouch-ketchup-surabhi-original-imafx4qktzguhhwy.jpeg" alt="">
                </div>
                <h2 class="text-sm mt-4 group-hover:text-primary-blue">SAMSUNG 230 L Direct Cool Single Door 3 Star Refrigerator</h2>
                </a>
                <!-- image & product title -->

                <!-- product description -->
                <div class="flex flex-col gap-2 items-center">
                        <!-- rating badge -->
                        <span class="text-sm text-gray-500 font-medium flex gap-2 items-center">
                            <span class="text-xs px-1.5 py-0.5 bg-primary-green rounded-sm text-white flex items-center gap-0.5">4.3 <i class="material-icons md-12">star</i></span>
                            <span>(7,345)</span>
                        </span>
                        <!-- rating badge -->

                        <!-- price container -->
                        <div class="flex items-center gap-1.5 text-md font-medium">
                            <span>₹16,790</span>
                            <span class="text-gray-500 line-through text-xs">₹18,890</span>
                            <span class="text-xs text-primary-green">15%&nbsp;off</span>
                        </div>
                        <!-- price container -->
                </div>
                <!-- product description -->

                <!-- wishlist badge -->
                <i class="material-icons absolute top-5 right-2 text-gray-300 cursor-pointer hover:text-red-500 md-16">favorite</i>
                <!-- wishlist badge -->

            </div>

            <!-- one product -->
            <div class="flex flex-col items-center gap-2 px-2 py-6 relative">
                <!-- image & product title -->
                <a href="#" class="flex flex-col items-center text-center group">
                <div class="w-36 h-36">
                    <img class="w-full h-full object-contain" src="https://rukminim1.flixcart.com/image/312/312/kh0vonk0/sauce-ketchup/h/b/z/450-tomato-pouch-ketchup-surabhi-original-imafx4qktzguhhwy.jpeg" alt="">
                </div>
                <h2 class="text-sm mt-4 group-hover:text-primary-blue">SAMSUNG 230 L Direct Cool Single Door 3 Star Refrigerator</h2>
                </a>
                <!-- image & product title -->

                <!-- product description -->
                <div class="flex flex-col gap-2 items-center">
                        <!-- rating badge -->
                        <span class="text-sm text-gray-500 font-medium flex gap-2 items-center">
                            <span class="text-xs px-1.5 py-0.5 bg-primary-green rounded-sm text-white flex items-center gap-0.5">4.3 <i class="material-icons md-12">star</i></span>
                            <span>(7,345)</span>
                        </span>
                        <!-- rating badge -->

                        <!-- price container -->
                        <div class="flex items-center gap-1.5 text-md font-medium">
                            <span>₹16,790</span>
                            <span class="text-gray-500 line-through text-xs">₹18,890</span>
                            <span class="text-xs text-primary-green">15%&nbsp;off</span>
                        </div>
                        <!-- price container -->
                </div>
                <!-- product description -->

                <!-- wishlist badge -->
                <i class="material-icons absolute top-5 right-2 text-gray-300 cursor-pointer hover:text-red-500 md-16">favorite</i>
                <!-- wishlist badge -->

            </div>

            <!-- one product -->
            <div class="flex flex-col items-center gap-2 px-2 py-6 relative">
                <!-- image & product title -->
                <a href="#" class="flex flex-col items-center text-center group">
                <div class="w-36 h-36">
                    <img class="w-full h-full object-contain" src="https://rukminim1.flixcart.com/image/312/312/kh0vonk0/sauce-ketchup/h/b/z/450-tomato-pouch-ketchup-surabhi-original-imafx4qktzguhhwy.jpeg" alt="">
                </div>
                <h2 class="text-sm mt-4 group-hover:text-primary-blue">SAMSUNG 230 L Direct Cool Single Door 3 Star Refrigerator</h2>
                </a>
                <!-- image & product title -->

                <!-- product description -->
                <div class="flex flex-col gap-2 items-center">
                        <!-- rating badge -->
                        <span class="text-sm text-gray-500 font-medium flex gap-2 items-center">
                            <span class="text-xs px-1.5 py-0.5 bg-primary-green rounded-sm text-white flex items-center gap-0.5">4.3 <i class="material-icons md-12">star</i></span>
                            <span>(7,345)</span>
                        </span>
                        <!-- rating badge -->

                        <!-- price container -->
                        <div class="flex items-center gap-1.5 text-md font-medium">
                            <span>₹16,790</span>
                            <span class="text-gray-500 line-through text-xs">₹18,890</span>
                            <span class="text-xs text-primary-green">15%&nbsp;off</span>
                        </div>
                        <!-- price container -->
                </div>
                <!-- product description -->

                <!-- wishlist badge -->
                <i class="material-icons absolute top-5 right-2 text-gray-300 cursor-pointer hover:text-red-500 md-16">favorite</i>
                <!-- wishlist badge -->

            </div>

            <!-- one product -->
            <div class="flex flex-col items-center gap-2 px-2 py-6 relative">
                <!-- image & product title -->
                <a href="#" class="flex flex-col items-center text-center group">
                <div class="w-36 h-36">
                    <img class="w-full h-full object-contain" src="https://rukminim1.flixcart.com/image/312/312/kh0vonk0/sauce-ketchup/h/b/z/450-tomato-pouch-ketchup-surabhi-original-imafx4qktzguhhwy.jpeg" alt="">
                </div>
                <h2 class="text-sm mt-4 group-hover:text-primary-blue">SAMSUNG 230 L Direct Cool Single Door 3 Star Refrigerator</h2>
                </a>
                <!-- image & product title -->

                <!-- product description -->
                <div class="flex flex-col gap-2 items-center">
                        <!-- rating badge -->
                        <span class="text-sm text-gray-500 font-medium flex gap-2 items-center">
                            <span class="text-xs px-1.5 py-0.5 bg-primary-green rounded-sm text-white flex items-center gap-0.5">4.3 <i class="material-icons md-12">star</i></span>
                            <span>(7,345)</span>
                        </span>
                        <!-- rating badge -->

                        <!-- price container -->
                        <div class="flex items-center gap-1.5 text-md font-medium">
                            <span>₹16,790</span>
                            <span class="text-gray-500 line-through text-xs">₹18,890</span>
                            <span class="text-xs text-primary-green">15%&nbsp;off</span>
                        </div>
                        <!-- price container -->
                </div>
                <!-- product description -->

                <!-- wishlist badge -->
                <i class="material-icons absolute top-5 right-2 text-gray-300 cursor-pointer hover:text-red-500 md-16">favorite</i>
                <!-- wishlist badge -->

            </div>

            <!-- one product -->
            <div class="flex flex-col items-center gap-2 px-2 py-6 relative">
                <!-- image & product title -->
                <a href="#" class="flex flex-col items-center text-center group">
                <div class="w-36 h-36">
                    <img class="w-full h-full object-contain" src="https://rukminim1.flixcart.com/image/312/312/kh0vonk0/sauce-ketchup/h/b/z/450-tomato-pouch-ketchup-surabhi-original-imafx4qktzguhhwy.jpeg" alt="">
                </div>
                <h2 class="text-sm mt-4 group-hover:text-primary-blue">SAMSUNG 230 L Direct Cool Single Door 3 Star Refrigerator</h2>
                </a>
                <!-- image & product title -->

                <!-- product description -->
                <div class="flex flex-col gap-2 items-center">
                        <!-- rating badge -->
                        <span class="text-sm text-gray-500 font-medium flex gap-2 items-center">
                            <span class="text-xs px-1.5 py-0.5 bg-primary-green rounded-sm text-white flex items-center gap-0.5">4.3 <i class="material-icons md-12">star</i></span>
                            <span>(7,345)</span>
                        </span>
                        <!-- rating badge -->

                        <!-- price container -->
                        <div class="flex items-center gap-1.5 text-md font-medium">
                            <span>₹16,790</span>
                            <span class="text-gray-500 line-through text-xs">₹18,890</span>
                            <span class="text-xs text-primary-green">15%&nbsp;off</span>
                        </div>
                        <!-- price container -->
                </div>
                <!-- product description -->

                <!-- wishlist badge -->
                <i class="material-icons absolute top-5 right-2 text-gray-300 cursor-pointer hover:text-red-500 md-16">favorite</i>
                <!-- wishlist badge -->

            </div>

            <!-- one product -->
            <div class="flex flex-col items-center gap-2 px-2 py-6 relative">
                <!-- image & product title -->
                <a href="#" class="flex flex-col items-center text-center group">
                <div class="w-36 h-36">
                    <img class="w-full h-full object-contain" src="https://rukminim1.flixcart.com/image/312/312/kh0vonk0/sauce-ketchup/h/b/z/450-tomato-pouch-ketchup-surabhi-original-imafx4qktzguhhwy.jpeg" alt="">
                </div>
                <h2 class="text-sm mt-4 group-hover:text-primary-blue">SAMSUNG 230 L Direct Cool Single Door 3 Star Refrigerator</h2>
                </a>
                <!-- image & product title -->

                <!-- product description -->
                <div class="flex flex-col gap-2 items-center">
                        <!-- rating badge -->
                        <span class="text-sm text-gray-500 font-medium flex gap-2 items-center">
                            <span class="text-xs px-1.5 py-0.5 bg-primary-green rounded-sm text-white flex items-center gap-0.5">4.3 <i class="material-icons md-12">star</i></span>
                            <span>(7,345)</span>
                        </span>
                        <!-- rating badge -->

                        <!-- price container -->
                        <div class="flex items-center gap-1.5 text-md font-medium">
                            <span>₹16,790</span>
                            <span class="text-gray-500 line-through text-xs">₹18,890</span>
                            <span class="text-xs text-primary-green">15%&nbsp;off</span>
                        </div>
                        <!-- price container -->
                </div>
                <!-- product description -->

                <!-- wishlist badge -->
                <i class="material-icons absolute top-5 right-2 text-gray-300 cursor-pointer hover:text-red-500 md-16">favorite</i>
                <!-- wishlist badge -->

            </div>

        </div>
        <!-- products container -->
    </section>
    <!-- you may like section -->

    <!-- top rated section -->
    <section id="topSelection" class="bg-white w-full shadow overflow-hidden">
        <!-- header -->
        <div class="flex px-6 py-3 justify-between items-center">
            <h1 class="text-xl font-medium">Top Rated</h1>
            <a href="#" class="bg-primary-blue text-xs font-medium text-white px-5 py-2.5 rounded-sm shadow-lg">VIEW ALL</a>
        </div>
        <hr>
        <!-- header -->
        
        <!-- products container -->
        <div class="flex items-center justify-between owl-carousel owl-theme relative">

            <!-- one product -->
            <a class="flex flex-col items-center gap-2 p-6" href="#">
                <div class="w-36 h-36 transform hover:scale-110 transition-transform duration-100 ease-out">
                    <img class="w-full h-full object-contain" src="https://rukminim1.flixcart.com/image/150/150/ksdjma80/headphone/a/u/p/airdopes-131-airdopes-138-boat-original-imag5yz9sfz9bzq8.jpeg" alt="">
                </div>
                <h2 class="font-medium text-sm mt-2">Audio & Video</h2>
                <span class="text-primary-green text-sm">New Collection</span>
            </a>
            <!-- one product -->
            <a class="flex flex-col items-center gap-2 p-6" href="#">
                <div class="w-36 h-36 transform hover:scale-110 transition-transform duration-100 ease-out">
                    <img class="w-full h-full object-contain" src="https://rukminim1.flixcart.com/image/150/150/ksdjma80/headphone/a/u/p/airdopes-131-airdopes-138-boat-original-imag5yz9sfz9bzq8.jpeg" alt="">
                </div>
                <h2 class="font-medium text-sm mt-2">Audio & Video</h2>
                <span class="text-primary-green text-sm">New Collection</span>
            </a>
            <!-- one product -->
            <a class="flex flex-col items-center gap-2 p-6" href="#">
                <div class="w-36 h-36 transform hover:scale-110 transition-transform duration-100 ease-out">
                    <img class="w-full h-full object-contain" src="https://rukminim1.flixcart.com/image/150/150/ksdjma80/headphone/a/u/p/airdopes-131-airdopes-138-boat-original-imag5yz9sfz9bzq8.jpeg" alt="">
                </div>
                <h2 class="font-medium text-sm mt-2">Audio & Video</h2>
                <span class="text-primary-green text-sm">New Collection</span>
            </a>
            <!-- one product -->
            <a class="flex flex-col items-center gap-2 p-6" href="#">
                <div class="w-36 h-36 transform hover:scale-110 transition-transform duration-100 ease-out">
                    <img class="w-full h-full object-contain" src="https://rukminim1.flixcart.com/image/150/150/ksdjma80/headphone/a/u/p/airdopes-131-airdopes-138-boat-original-imag5yz9sfz9bzq8.jpeg" alt="">
                </div>
                <h2 class="font-medium text-sm mt-2">Audio & Video</h2>
                <span class="text-primary-green text-sm">New Collection</span>
            </a>
            <!-- one product -->
            <a class="flex flex-col items-center gap-2 p-6" href="#">
                <div class="w-36 h-36 transform hover:scale-110 transition-transform duration-100 ease-out">
                    <img class="w-full h-full object-contain" src="https://rukminim1.flixcart.com/image/150/150/ksdjma80/headphone/a/u/p/airdopes-131-airdopes-138-boat-original-imag5yz9sfz9bzq8.jpeg" alt="">
                </div>
                <h2 class="font-medium text-sm mt-2">Audio & Video</h2>
                <span class="text-primary-green text-sm">New Collection</span>
            </a>
            <!-- one product -->
            <a class="flex flex-col items-center gap-2 p-6" href="#">
                <div class="w-36 h-36 transform hover:scale-110 transition-transform duration-100 ease-out">
                    <img class="w-full h-full object-contain" src="https://rukminim1.flixcart.com/image/150/150/ksdjma80/headphone/a/u/p/airdopes-131-airdopes-138-boat-original-imag5yz9sfz9bzq8.jpeg" alt="">
                </div>
                <h2 class="font-medium text-sm mt-2">Audio & Video</h2>
                <span class="text-primary-green text-sm">New Collection</span>
            </a>
            <!-- one product -->
            <a class="flex flex-col items-center gap-2 p-6" href="#">
                <div class="w-36 h-36 transform hover:scale-110 transition-transform duration-100 ease-out">
                    <img class="w-full h-full object-contain" src="https://rukminim1.flixcart.com/image/150/150/ksdjma80/headphone/a/u/p/airdopes-131-airdopes-138-boat-original-imag5yz9sfz9bzq8.jpeg" alt="">
                </div>
                <h2 class="font-medium text-sm mt-2">Audio & Video</h2>
                <span class="text-primary-green text-sm">New Collection</span>
            </a>
            <!-- one product -->
            <a class="flex flex-col items-center gap-2 p-6" href="#">
                <div class="w-36 h-36 transform hover:scale-110 transition-transform duration-100 ease-out">
                    <img class="w-full h-full object-contain" src="https://rukminim1.flixcart.com/image/150/150/ksdjma80/headphone/a/u/p/airdopes-131-airdopes-138-boat-original-imag5yz9sfz9bzq8.jpeg" alt="">
                </div>
                <h2 class="font-medium text-sm mt-2">Audio & Video</h2>
                <span class="text-primary-green text-sm">New Collection</span>
            </a>
            <!-- one product -->
            <a class="flex flex-col items-center gap-2 p-6" href="#">
                <div class="w-36 h-36 transform hover:scale-110 transition-transform duration-100 ease-out">
                    <img class="w-full h-full object-contain" src="https://rukminim1.flixcart.com/image/150/150/ksdjma80/headphone/a/u/p/airdopes-131-airdopes-138-boat-original-imag5yz9sfz9bzq8.jpeg" alt="">
                </div>
                <h2 class="font-medium text-sm mt-2">Audio & Video</h2>
                <span class="text-primary-green text-sm">New Collection</span>
            </a>
            <!-- one product -->
            <a class="flex flex-col items-center gap-2 p-6" href="#">
                <div class="w-36 h-36 transform hover:scale-110 transition-transform duration-100 ease-out">
                    <img class="w-full h-full object-contain" src="https://rukminim1.flixcart.com/image/150/150/ksdjma80/headphone/a/u/p/airdopes-131-airdopes-138-boat-original-imag5yz9sfz9bzq8.jpeg" alt="">
                </div>
                <h2 class="font-medium text-sm mt-2">Audio & Video</h2>
                <span class="text-primary-green text-sm">New Collection</span>
            </a>

        </div>
        <!-- products container -->
    </section>
    <!-- top rated section -->

    <!-- suggested for you section -->
    <section id="recommended" class="bg-white w-full shadow overflow-hidden">
        <!-- header -->
        <div class="flex px-6 py-4 justify-between items-center">
            <div class="title flex flex-col gap-0.5">
                <h1 class="text-xl font-medium">Suggested for You</h1>
                <p class="text-sm text-gray-400">Based on Your Interest</p>
            </div>
            <a href="#" class="bg-primary-blue text-xs font-medium text-white px-5 py-2.5 rounded-sm shadow-lg">VIEW ALL</a>
        </div>
        <hr>
        <!-- header -->
        
        <!-- products container -->
        <div class="flex items-center justify-between owl-carousel owl-theme p-1 relative">

            <!-- one product -->
            <div class="flex flex-col items-center gap-2 px-2 py-6 relative">
                <!-- image & product title -->
                <a href="#" class="flex flex-col items-center text-center group">
                <div class="w-36 h-36">
                    <img class="w-full h-full object-contain" src="https://rukminim1.flixcart.com/image/312/312/jxp08sw0/water-purifier/r/z/s/eureka-forbes-aquasure-from-aquaguard-desire-ro-mc-original-imafg3hwgn8p7brg.jpeg" alt="">
                </div>
                <h2 class="text-sm mt-4 group-hover:text-primary-blue">Eureka Forbes Aquasure Desire Water Purifier Aquagaurd</h2>
                </a>
                <!-- image & product title -->

                <!-- product description -->
                <div class="flex flex-col gap-2 items-center">
                        <!-- rating badge -->
                        <span class="text-sm text-gray-500 font-medium flex gap-2 items-center">
                            <span class="text-xs px-1.5 py-0.5 bg-primary-green rounded-sm text-white flex items-center gap-0.5">4.3 <i class="material-icons md-12">star</i></span>
                            <span>(7,345)</span>
                        </span>
                        <!-- rating badge -->

                        <!-- price container -->
                        <div class="flex items-center gap-1.5 text-md font-medium">
                            <span>₹16,790</span>
                            <span class="text-gray-500 line-through text-xs">₹18,890</span>
                            <span class="text-xs text-primary-green">15%&nbsp;off</span>
                        </div>
                        <!-- price container -->
                </div>
                <!-- product description -->

                <!-- wishlist badge -->
                <i class="material-icons absolute top-5 right-2 text-gray-300 cursor-pointer hover:text-red-500 md-16">favorite</i>
                <!-- wishlist badge -->

            </div>

            <!-- one product -->
            <div class="flex flex-col items-center gap-2 px-2 py-6 relative">
                <!-- image & product title -->
                <a href="#" class="flex flex-col items-center text-center group">
                <div class="w-36 h-36">
                    <img class="w-full h-full object-contain" src="https://rukminim1.flixcart.com/image/312/312/jxp08sw0/water-purifier/r/z/s/eureka-forbes-aquasure-from-aquaguard-desire-ro-mc-original-imafg3hwgn8p7brg.jpeg" alt="">
                </div>
                <h2 class="text-sm mt-4 group-hover:text-primary-blue">Eureka Forbes Aquasure Desire Water Purifier Aquagaurd</h2>
                </a>
                <!-- image & product title -->

                <!-- product description -->
                <div class="flex flex-col gap-2 items-center">
                        <!-- rating badge -->
                        <span class="text-sm text-gray-500 font-medium flex gap-2 items-center">
                            <span class="text-xs px-1.5 py-0.5 bg-primary-green rounded-sm text-white flex items-center gap-0.5">4.3 <i class="material-icons md-12">star</i></span>
                            <span>(7,345)</span>
                        </span>
                        <!-- rating badge -->

                        <!-- price container -->
                        <div class="flex items-center gap-1.5 text-md font-medium">
                            <span>₹16,790</span>
                            <span class="text-gray-500 line-through text-xs">₹18,890</span>
                            <span class="text-xs text-primary-green">15%&nbsp;off</span>
                        </div>
                        <!-- price container -->
                </div>
                <!-- product description -->

                <!-- wishlist badge -->
                <i class="material-icons absolute top-5 right-2 text-gray-300 cursor-pointer hover:text-red-500 md-16">favorite</i>
                <!-- wishlist badge -->

            </div>

            <!-- one product -->
            <div class="flex flex-col items-center gap-2 px-2 py-6 relative">
                <!-- image & product title -->
                <a href="#" class="flex flex-col items-center text-center group">
                <div class="w-36 h-36">
                    <img class="w-full h-full object-contain" src="https://rukminim1.flixcart.com/image/312/312/jxp08sw0/water-purifier/r/z/s/eureka-forbes-aquasure-from-aquaguard-desire-ro-mc-original-imafg3hwgn8p7brg.jpeg" alt="">
                </div>
                <h2 class="text-sm mt-4 group-hover:text-primary-blue">Eureka Forbes Aquasure Desire Water Purifier Aquagaurd</h2>
                </a>
                <!-- image & product title -->

                <!-- product description -->
                <div class="flex flex-col gap-2 items-center">
                        <!-- rating badge -->
                        <span class="text-sm text-gray-500 font-medium flex gap-2 items-center">
                            <span class="text-xs px-1.5 py-0.5 bg-primary-green rounded-sm text-white flex items-center gap-0.5">4.3 <i class="material-icons md-12">star</i></span>
                            <span>(7,345)</span>
                        </span>
                        <!-- rating badge -->

                        <!-- price container -->
                        <div class="flex items-center gap-1.5 text-md font-medium">
                            <span>₹16,790</span>
                            <span class="text-gray-500 line-through text-xs">₹18,890</span>
                            <span class="text-xs text-primary-green">15%&nbsp;off</span>
                        </div>
                        <!-- price container -->
                </div>
                <!-- product description -->

                <!-- wishlist badge -->
                <i class="material-icons absolute top-5 right-2 text-gray-300 cursor-pointer hover:text-red-500 md-16">favorite</i>
                <!-- wishlist badge -->

            </div>

            <!-- one product -->
            <div class="flex flex-col items-center gap-2 px-2 py-6 relative">
                <!-- image & product title -->
                <a href="#" class="flex flex-col items-center text-center group">
                <div class="w-36 h-36">
                    <img class="w-full h-full object-contain" src="https://rukminim1.flixcart.com/image/312/312/jxp08sw0/water-purifier/r/z/s/eureka-forbes-aquasure-from-aquaguard-desire-ro-mc-original-imafg3hwgn8p7brg.jpeg" alt="">
                </div>
                <h2 class="text-sm mt-4 group-hover:text-primary-blue">Eureka Forbes Aquasure Desire Water Purifier Aquagaurd</h2>
                </a>
                <!-- image & product title -->

                <!-- product description -->
                <div class="flex flex-col gap-2 items-center">
                        <!-- rating badge -->
                        <span class="text-sm text-gray-500 font-medium flex gap-2 items-center">
                            <span class="text-xs px-1.5 py-0.5 bg-primary-green rounded-sm text-white flex items-center gap-0.5">4.3 <i class="material-icons md-12">star</i></span>
                            <span>(7,345)</span>
                        </span>
                        <!-- rating badge -->

                        <!-- price container -->
                        <div class="flex items-center gap-1.5 text-md font-medium">
                            <span>₹16,790</span>
                            <span class="text-gray-500 line-through text-xs">₹18,890</span>
                            <span class="text-xs text-primary-green">15%&nbsp;off</span>
                        </div>
                        <!-- price container -->
                </div>
                <!-- product description -->

                <!-- wishlist badge -->
                <i class="material-icons absolute top-5 right-2 text-gray-300 cursor-pointer hover:text-red-500 md-16">favorite</i>
                <!-- wishlist badge -->

            </div>

            <!-- one product -->
            <div class="flex flex-col items-center gap-2 px-2 py-6 relative">
                <!-- image & product title -->
                <a href="#" class="flex flex-col items-center text-center group">
                <div class="w-36 h-36">
                    <img class="w-full h-full object-contain" src="https://rukminim1.flixcart.com/image/312/312/jxp08sw0/water-purifier/r/z/s/eureka-forbes-aquasure-from-aquaguard-desire-ro-mc-original-imafg3hwgn8p7brg.jpeg" alt="">
                </div>
                <h2 class="text-sm mt-4 group-hover:text-primary-blue">Eureka Forbes Aquasure Desire Water Purifier Aquagaurd</h2>
                </a>
                <!-- image & product title -->

                <!-- product description -->
                <div class="flex flex-col gap-2 items-center">
                        <!-- rating badge -->
                        <span class="text-sm text-gray-500 font-medium flex gap-2 items-center">
                            <span class="text-xs px-1.5 py-0.5 bg-primary-green rounded-sm text-white flex items-center gap-0.5">4.3 <i class="material-icons md-12">star</i></span>
                            <span>(7,345)</span>
                        </span>
                        <!-- rating badge -->

                        <!-- price container -->
                        <div class="flex items-center gap-1.5 text-md font-medium">
                            <span>₹16,790</span>
                            <span class="text-gray-500 line-through text-xs">₹18,890</span>
                            <span class="text-xs text-primary-green">15%&nbsp;off</span>
                        </div>
                        <!-- price container -->
                </div>
                <!-- product description -->

                <!-- wishlist badge -->
                <i class="material-icons absolute top-5 right-2 text-gray-300 cursor-pointer hover:text-red-500 md-16">favorite</i>
                <!-- wishlist badge -->

            </div>

            <!-- one product -->
            <div class="flex flex-col items-center gap-2 px-2 py-6 relative">
                <!-- image & product title -->
                <a href="#" class="flex flex-col items-center text-center group">
                <div class="w-36 h-36">
                    <img class="w-full h-full object-contain" src="https://rukminim1.flixcart.com/image/312/312/jxp08sw0/water-purifier/r/z/s/eureka-forbes-aquasure-from-aquaguard-desire-ro-mc-original-imafg3hwgn8p7brg.jpeg" alt="">
                </div>
                <h2 class="text-sm mt-4 group-hover:text-primary-blue">Eureka Forbes Aquasure Desire Water Purifier Aquagaurd</h2>
                </a>
                <!-- image & product title -->

                <!-- product description -->
                <div class="flex flex-col gap-2 items-center">
                        <!-- rating badge -->
                        <span class="text-sm text-gray-500 font-medium flex gap-2 items-center">
                            <span class="text-xs px-1.5 py-0.5 bg-primary-green rounded-sm text-white flex items-center gap-0.5">4.3 <i class="material-icons md-12">star</i></span>
                            <span>(7,345)</span>
                        </span>
                        <!-- rating badge -->

                        <!-- price container -->
                        <div class="flex items-center gap-1.5 text-md font-medium">
                            <span>₹16,790</span>
                            <span class="text-gray-500 line-through text-xs">₹18,890</span>
                            <span class="text-xs text-primary-green">15%&nbsp;off</span>
                        </div>
                        <!-- price container -->
                </div>
                <!-- product description -->

                <!-- wishlist badge -->
                <i class="material-icons absolute top-5 right-2 text-gray-300 cursor-pointer hover:text-red-500 md-16">favorite</i>
                <!-- wishlist badge -->

            </div>

            <!-- one product -->
            <div class="flex flex-col items-center gap-2 px-2 py-6 relative">
                <!-- image & product title -->
                <a href="#" class="flex flex-col items-center text-center group">
                <div class="w-36 h-36">
                    <img class="w-full h-full object-contain" src="https://rukminim1.flixcart.com/image/312/312/jxp08sw0/water-purifier/r/z/s/eureka-forbes-aquasure-from-aquaguard-desire-ro-mc-original-imafg3hwgn8p7brg.jpeg" alt="">
                </div>
                <h2 class="text-sm mt-4 group-hover:text-primary-blue">Eureka Forbes Aquasure Desire Water Purifier Aquagaurd</h2>
                </a>
                <!-- image & product title -->

                <!-- product description -->
                <div class="flex flex-col gap-2 items-center">
                        <!-- rating badge -->
                        <span class="text-sm text-gray-500 font-medium flex gap-2 items-center">
                            <span class="text-xs px-1.5 py-0.5 bg-primary-green rounded-sm text-white flex items-center gap-0.5">4.3 <i class="material-icons md-12">star</i></span>
                            <span>(7,345)</span>
                        </span>
                        <!-- rating badge -->

                        <!-- price container -->
                        <div class="flex items-center gap-1.5 text-md font-medium">
                            <span>₹16,790</span>
                            <span class="text-gray-500 line-through text-xs">₹18,890</span>
                            <span class="text-xs text-primary-green">15%&nbsp;off</span>
                        </div>
                        <!-- price container -->
                </div>
                <!-- product description -->

                <!-- wishlist badge -->
                <i class="material-icons absolute top-5 right-2 text-gray-300 cursor-pointer hover:text-red-500 md-16">favorite</i>
                <!-- wishlist badge -->

            </div>

            <!-- one product -->
            <div class="flex flex-col items-center gap-2 px-2 py-6 relative">
                <!-- image & product title -->
                <a href="#" class="flex flex-col items-center text-center group">
                <div class="w-36 h-36">
                    <img class="w-full h-full object-contain" src="https://rukminim1.flixcart.com/image/312/312/jxp08sw0/water-purifier/r/z/s/eureka-forbes-aquasure-from-aquaguard-desire-ro-mc-original-imafg3hwgn8p7brg.jpeg" alt="">
                </div>
                <h2 class="text-sm mt-4 group-hover:text-primary-blue">Eureka Forbes Aquasure Desire Water Purifier Aquagaurd</h2>
                </a>
                <!-- image & product title -->

                <!-- product description -->
                <div class="flex flex-col gap-2 items-center">
                        <!-- rating badge -->
                        <span class="text-sm text-gray-500 font-medium flex gap-2 items-center">
                            <span class="text-xs px-1.5 py-0.5 bg-primary-green rounded-sm text-white flex items-center gap-0.5">4.3 <i class="material-icons md-12">star</i></span>
                            <span>(7,345)</span>
                        </span>
                        <!-- rating badge -->

                        <!-- price container -->
                        <div class="flex items-center gap-1.5 text-md font-medium">
                            <span>₹16,790</span>
                            <span class="text-gray-500 line-through text-xs">₹18,890</span>
                            <span class="text-xs text-primary-green">15%&nbsp;off</span>
                        </div>
                        <!-- price container -->
                </div>
                <!-- product description -->

                <!-- wishlist badge -->
                <i class="material-icons absolute top-5 right-2 text-gray-300 cursor-pointer hover:text-red-500 md-16">favorite</i>
                <!-- wishlist badge -->

            </div>

            <!-- one product -->
            <div class="flex flex-col items-center gap-2 px-2 py-6 relative">
                <!-- image & product title -->
                <a href="#" class="flex flex-col items-center text-center group">
                <div class="w-36 h-36">
                    <img class="w-full h-full object-contain" src="https://rukminim1.flixcart.com/image/312/312/jxp08sw0/water-purifier/r/z/s/eureka-forbes-aquasure-from-aquaguard-desire-ro-mc-original-imafg3hwgn8p7brg.jpeg" alt="">
                </div>
                <h2 class="text-sm mt-4 group-hover:text-primary-blue">Eureka Forbes Aquasure Desire Water Purifier Aquagaurd</h2>
                </a>
                <!-- image & product title -->

                <!-- product description -->
                <div class="flex flex-col gap-2 items-center">
                        <!-- rating badge -->
                        <span class="text-sm text-gray-500 font-medium flex gap-2 items-center">
                            <span class="text-xs px-1.5 py-0.5 bg-primary-green rounded-sm text-white flex items-center gap-0.5">4.3 <i class="material-icons md-12">star</i></span>
                            <span>(7,345)</span>
                        </span>
                        <!-- rating badge -->

                        <!-- price container -->
                        <div class="flex items-center gap-1.5 text-md font-medium">
                            <span>₹16,790</span>
                            <span class="text-gray-500 line-through text-xs">₹18,890</span>
                            <span class="text-xs text-primary-green">15%&nbsp;off</span>
                        </div>
                        <!-- price container -->
                </div>
                <!-- product description -->

                <!-- wishlist badge -->
                <i class="material-icons absolute top-5 right-2 text-gray-300 cursor-pointer hover:text-red-500 md-16">favorite</i>
                <!-- wishlist badge -->

            </div>

        </div>
        <!-- products container -->
    </section>
    <!-- suggested for you section -->

    <!-- top selection section -->
    <section id="topSelection" class="bg-white w-full shadow overflow-hidden">
        <!-- header -->
        <div class="flex px-6 py-3 justify-between items-center">
            <h1 class="text-xl font-medium">Top Selection</h1>
            <a href="#" class="bg-primary-blue text-xs font-medium text-white px-5 py-2.5 rounded-sm shadow-lg">VIEW ALL</a>
        </div>
        <hr>
        <!-- header -->
        
        <!-- products container -->
        <div class="flex items-center justify-between owl-carousel owl-theme relative">

            <!-- one product -->
            <a class="flex flex-col items-center gap-2 p-6" href="#">
                <div class="w-36 h-36 transform hover:scale-110 transition-transform duration-100 ease-out">
                    <img class="w-full h-full object-contain" src="https://rukminim1.flixcart.com/image/150/150/ki3gknk0-0/backpack/t/n/i/spacy-unisex-backpack-with-rain-cover-and-reflective-strip-p-041-original-imafxyypsycttkeb.jpeg" alt="">
                </div>
                <h2 class="font-medium text-sm mt-2">Kitchen Appliances</h2>
                <span class="text-primary-green text-sm">Grab Now</span>
            </a>
            
            <!-- one product -->
            <a class="flex flex-col items-center gap-2 p-6" href="#">
                <div class="w-36 h-36 transform hover:scale-110 transition-transform duration-100 ease-out">
                    <img class="w-full h-full object-contain" src="https://rukminim1.flixcart.com/image/150/150/ki3gknk0-0/backpack/t/n/i/spacy-unisex-backpack-with-rain-cover-and-reflective-strip-p-041-original-imafxyypsycttkeb.jpeg" alt="">
                </div>
                <h2 class="font-medium text-sm mt-2">Kitchen Appliances</h2>
                <span class="text-primary-green text-sm">Grab Now</span>
            </a>
            <!-- one product -->
            <a class="flex flex-col items-center gap-2 p-6" href="#">
                <div class="w-36 h-36 transform hover:scale-110 transition-transform duration-100 ease-out">
                    <img class="w-full h-full object-contain" src="https://rukminim1.flixcart.com/image/150/150/ki3gknk0-0/backpack/t/n/i/spacy-unisex-backpack-with-rain-cover-and-reflective-strip-p-041-original-imafxyypsycttkeb.jpeg" alt="">
                </div>
                <h2 class="font-medium text-sm mt-2">Kitchen Appliances</h2>
                <span class="text-primary-green text-sm">Grab Now</span>
            </a>
            <!-- one product -->
            <a class="flex flex-col items-center gap-2 p-6" href="#">
                <div class="w-36 h-36 transform hover:scale-110 transition-transform duration-100 ease-out">
                    <img class="w-full h-full object-contain" src="https://rukminim1.flixcart.com/image/150/150/ki3gknk0-0/backpack/t/n/i/spacy-unisex-backpack-with-rain-cover-and-reflective-strip-p-041-original-imafxyypsycttkeb.jpeg" alt="">
                </div>
                <h2 class="font-medium text-sm mt-2">Kitchen Appliances</h2>
                <span class="text-primary-green text-sm">Grab Now</span>
            </a>
            <!-- one product -->
            <a class="flex flex-col items-center gap-2 p-6" href="#">
                <div class="w-36 h-36 transform hover:scale-110 transition-transform duration-100 ease-out">
                    <img class="w-full h-full object-contain" src="https://rukminim1.flixcart.com/image/150/150/ki3gknk0-0/backpack/t/n/i/spacy-unisex-backpack-with-rain-cover-and-reflective-strip-p-041-original-imafxyypsycttkeb.jpeg" alt="">
                </div>
                <h2 class="font-medium text-sm mt-2">Kitchen Appliances</h2>
                <span class="text-primary-green text-sm">Grab Now</span>
            </a>
            <!-- one product -->
            <a class="flex flex-col items-center gap-2 p-6" href="#">
                <div class="w-36 h-36 transform hover:scale-110 transition-transform duration-100 ease-out">
                    <img class="w-full h-full object-contain" src="https://rukminim1.flixcart.com/image/150/150/ki3gknk0-0/backpack/t/n/i/spacy-unisex-backpack-with-rain-cover-and-reflective-strip-p-041-original-imafxyypsycttkeb.jpeg" alt="">
                </div>
                <h2 class="font-medium text-sm mt-2">Kitchen Appliances</h2>
                <span class="text-primary-green text-sm">Grab Now</span>
            </a>
            <!-- one product -->
            <a class="flex flex-col items-center gap-2 p-6" href="#">
                <div class="w-36 h-36 transform hover:scale-110 transition-transform duration-100 ease-out">
                    <img class="w-full h-full object-contain" src="https://rukminim1.flixcart.com/image/150/150/ki3gknk0-0/backpack/t/n/i/spacy-unisex-backpack-with-rain-cover-and-reflective-strip-p-041-original-imafxyypsycttkeb.jpeg" alt="">
                </div>
                <h2 class="font-medium text-sm mt-2">Kitchen Appliances</h2>
                <span class="text-primary-green text-sm">Grab Now</span>
            </a>
            <!-- one product -->
            <a class="flex flex-col items-center gap-2 p-6" href="#">
                <div class="w-36 h-36 transform hover:scale-110 transition-transform duration-100 ease-out">
                    <img class="w-full h-full object-contain" src="https://rukminim1.flixcart.com/image/150/150/ki3gknk0-0/backpack/t/n/i/spacy-unisex-backpack-with-rain-cover-and-reflective-strip-p-041-original-imafxyypsycttkeb.jpeg" alt="">
                </div>
                <h2 class="font-medium text-sm mt-2">Kitchen Appliances</h2>
                <span class="text-primary-green text-sm">Grab Now</span>
            </a>
            <!-- one product -->
            <a class="flex flex-col items-center gap-2 p-6" href="#">
                <div class="w-36 h-36 transform hover:scale-110 transition-transform duration-100 ease-out">
                    <img class="w-full h-full object-contain" src="https://rukminim1.flixcart.com/image/150/150/ki3gknk0-0/backpack/t/n/i/spacy-unisex-backpack-with-rain-cover-and-reflective-strip-p-041-original-imafxyypsycttkeb.jpeg" alt="">
                </div>
                <h2 class="font-medium text-sm mt-2">Kitchen Appliances</h2>
                <span class="text-primary-green text-sm">Grab Now</span>
            </a>
        </div>
        <!-- products container -->
    </section>
    <!-- top selection section -->

    </main>
    <!-- main sections starts -->


    <!-- long desc links -->
    <div class="w-full bg-white p-6 flex flex-col mt-10 border-t text-gray-500 text-sm">
        <h3 class="font-medium mb-3">Top Stories: <span class="text-gray-700">Brand Directory</span></h3>

        <p class="">MOST SEARCHED FOR ON FLIPKART:
            <span class="text-xxs text-gray-700">
                <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> |
                <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> |
                <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> |
                <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> |
                <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> |
                <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a>
            </span>
        </p>

        <p>LARGE APPLIANCES:
            <span class="text-xxs text-gray-700">
                <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> |
                <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> |
                <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> |
                <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> |
           </span>
        </p>

        <p>BEST SELLING ON FLIPKART:
            <span class="text-xxs text-gray-700">
                <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> |
                <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> | <a href="#">Ray Ban Sunglasses</a> |
            </span>
        </p>
    </div>
    <!-- long desc links -->


    <!-- long description section -->
    <div class="w-full bg-white p-6 flex flex-col gap-3 text-gray-500">
            <h2 class=" font-bold">Flipkart: The One-stop Shopping Destination</h2>
            <p class="text-xxs">E-commerce is revolutionizing the way we all shop in India. Why do you want to hop from one store to another in search of the latest phone when you can find it on the Internet in a single click? Not only mobiles. Flipkart houses everything you can possibly imagine, from trending electronics like laptops, tablets, smartphones, and mobile accessories to in-vogue fashion staples like shoes, clothing and lifestyle accessories; from modern furniture like sofa sets, dining tables, and wardrobes to appliances that make your life easy like washing machines, TVs, ACs, mixer grinder juicers and other time-saving kitchen and small appliances; from home furnishings like cushion covers, mattresses and bedsheets to toys and musical instruments, we got them all covered. You name it, and you can stay assured about finding them all here. For those of you with erratic working hours, Flipkart is your best bet. Shop in your PJs, at night or in the wee hours of the morning. This e-commerce never shuts down.</p>
            <p class="text-xxs">What's more, with our year-round shopping festivals and events, our prices are irresistible. We're sure you'll find yourself picking up more than what you had in mind. If you are wondering why you should shop from Flipkart when there are multiple options available to you, well, the below will answer your question.</p>
            <h2 class=" font-bold">Flipkart: The One-stop Shopping Destination</h2>
            <p class="text-xxs">E-commerce is revolutionizing the way we all shop in India. Why do you want to hop from one store to another in search of the latest phone when you can find it on the Internet in a single click? Not only mobiles. Flipkart houses everything you can possibly imagine, from trending electronics like laptops, tablets, smartphones, and mobile accessories to in-vogue fashion staples like shoes, clothing and lifestyle accessories; from modern furniture like sofa sets, dining tables, and wardrobes to appliances that make your life easy like washing machines, TVs, ACs, mixer grinder juicers and other time-saving kitchen and small appliances; from home furnishings like cushion covers, mattresses and bedsheets to toys and musical instruments, we got them all covered. You name it, and you can stay assured about finding them all here. For those of you with erratic working hours, Flipkart is your best bet. Shop in your PJs, at night or in the wee hours of the morning. This e-commerce never shuts down.</p>
            <p class="text-xxs">What's more, with our year-round shopping festivals and events, our prices are irresistible. We're sure you'll find yourself picking up more than what you had in mind. If you are wondering why you should shop from Flipkart when there are multiple options available to you, well, the below will answer your question.</p>
            <h2 class=" font-bold">Flipkart: The One-stop Shopping Destination</h2>
            <p class="text-xxs">E-commerce is revolutionizing the way we all shop in India. Why do you want to hop from one store to another in search of the latest phone when you can find it on the Internet in a single click? Not only mobiles. Flipkart houses everything you can possibly imagine, from trending electronics like laptops, tablets, smartphones, and mobile accessories to in-vogue fashion staples like shoes, clothing and lifestyle accessories; from modern furniture like sofa sets, dining tables, and wardrobes to appliances that make your life easy like washing machines, TVs, ACs, mixer grinder juicers and other time-saving kitchen and small appliances; from home furnishings like cushion covers, mattresses and bedsheets to toys and musical instruments, we got them all covered. You name it, and you can stay assured about finding them all here. For those of you with erratic working hours, Flipkart is your best bet. Shop in your PJs, at night or in the wee hours of the morning. This e-commerce never shuts down.</p>
            <p class="text-xxs">What's more, with our year-round shopping festivals and events, our prices are irresistible. We're sure you'll find yourself picking up more than what you had in mind. If you are wondering why you should shop from Flipkart when there are multiple options available to you, well, the below will answer your question.</p>
            <h2 class=" font-bold">Flipkart: The One-stop Shopping Destination</h2>
            <p class="text-xxs">E-commerce is revolutionizing the way we all shop in India. Why do you want to hop from one store to another in search of the latest phone when you can find it on the Internet in a single click? Not only mobiles. Flipkart houses everything you can possibly imagine, from trending electronics like laptops, tablets, smartphones, and mobile accessories to in-vogue fashion staples like shoes, clothing and lifestyle accessories; from modern furniture like sofa sets, dining tables, and wardrobes to appliances that make your life easy like washing machines, TVs, ACs, mixer grinder juicers and other time-saving kitchen and small appliances; from home furnishings like cushion covers, mattresses and bedsheets to toys and musical instruments, we got them all covered. You name it, and you can stay assured about finding them all here. For those of you with erratic working hours, Flipkart is your best bet. Shop in your PJs, at night or in the wee hours of the morning. This e-commerce never shuts down.</p>
            <p class="text-xxs">What's more, with our year-round shopping festivals and events, our prices are irresistible. We're sure you'll find yourself picking up more than what you had in mind. If you are wondering why you should shop from Flipkart when there are multiple options available to you, well, the below will answer your question.</p>
            <h2 class=" font-bold">Flipkart: The One-stop Shopping Destination</h2>
            <p class="text-xxs">E-commerce is revolutionizing the way we all shop in India. Why do you want to hop from one store to another in search of the latest phone when you can find it on the Internet in a single click? Not only mobiles. Flipkart houses everything you can possibly imagine, from trending electronics like laptops, tablets, smartphones, and mobile accessories to in-vogue fashion staples like shoes, clothing and lifestyle accessories; from modern furniture like sofa sets, dining tables, and wardrobes to appliances that make your life easy like washing machines, TVs, ACs, mixer grinder juicers and other time-saving kitchen and small appliances; from home furnishings like cushion covers, mattresses and bedsheets to toys and musical instruments, we got them all covered. You name it, and you can stay assured about finding them all here. For those of you with erratic working hours, Flipkart is your best bet. Shop in your PJs, at night or in the wee hours of the morning. This e-commerce never shuts down.</p>
            <p class="text-xxs">What's more, with our year-round shopping festivals and events, our prices are irresistible. We're sure you'll find yourself picking up more than what you had in mind. If you are wondering why you should shop from Flipkart when there are multiple options available to you, well, the below will answer your question.</p>
            <h2 class=" font-bold">Flipkart: The One-stop Shopping Destination</h2>
            <p class="text-xxs">E-commerce is revolutionizing the way we all shop in India. Why do you want to hop from one store to another in search of the latest phone when you can find it on the Internet in a single click? Not only mobiles. Flipkart houses everything you can possibly imagine, from trending electronics like laptops, tablets, smartphones, and mobile accessories to in-vogue fashion staples like shoes, clothing and lifestyle accessories; from modern furniture like sofa sets, dining tables, and wardrobes to appliances that make your life easy like washing machines, TVs, ACs, mixer grinder juicers and other time-saving kitchen and small appliances; from home furnishings like cushion covers, mattresses and bedsheets to toys and musical instruments, we got them all covered. You name it, and you can stay assured about finding them all here. For those of you with erratic working hours, Flipkart is your best bet. Shop in your PJs, at night or in the wee hours of the morning. This e-commerce never shuts down.</p>
            <p class="text-xxs">What's more, with our year-round shopping festivals and events, our prices are irresistible. We're sure you'll find yourself picking up more than what you had in mind. If you are wondering why you should shop from Flipkart when there are multiple options available to you, well, the below will answer your question.</p>

    </div>
    <!-- long description section -->


    <!-- footer starts -->
    <footer class="w-full py-1 sm:py-4 px-4 sm:px-12 bg-primary-darkBlue text-white text-xs border-b border-gray-600 flex flex-col sm:flex-row overflow-hidden">
        <div class="w-full sm:w-7/12 flex flex-col sm:flex-row">
        <!-- about column -->
        <div class="w-full sm:w-1/5 flex flex-col gap-2 my-3 sm:my-6 ml-5">
            <h2 class="text-primary-grey mb-2">ABOUT</h2>
            <!-- links -->
            <a href="https://www.flipkart.com/helpcentre" class="hover:underline">Contact Us</a>
            <a href="https://www.flipkart.com/about-us" class="hover:underline">About Us</a>
            <a href="https://www.flipkartcareers.com" class="hover:underline">Careers</a>
            <a href="https://stories.flipkart.com" class="hover:underline">Flipkart Stories</a>
            <a href="https://stories.flipkart.com/category/top-stories/news" class="hover:underline">Press</a>
            <a href="https://www.flipkartwholesale.com" class="hover:underline">Flipkart Wholesale</a>
            <a href="https://www.flipkart.com/corporate-information" class="hover:underline">Corporate Information</a>
            <!-- links -->
        </div>
        <!-- about column -->

        <!-- help column -->
        <div class="w-full sm:w-1/5 flex flex-col gap-2 my-3 sm:my-6 ml-5">
            <h2 class="text-primary-grey mb-2">HELP</h2>
            <!-- links -->
            <a href="https://www.flipkart.com/pages/payments" class="hover:underline">Payments</a>
            <a href="https://www.flipkart.com/pages/shipping" class="hover:underline">Shipping</a>
            <a href="https://www.flipkart.com/helpcentre?catalog=55c9c6edb000002e002c1701&view=CATALOG" class="hover:underline">Cancellation & Returns</a>
            <a href="https://www.flipkart.com/helpcentre?catalog=55c9c8e2b0000023002c1702&view=CATALOG" class="hover:underline">FAQ</a>
            <a href="https://seller.flipkart.com/fiv" class="hover:underline">Report Infringement</a>
            <!-- links -->
        </div>
        <!-- help column -->

        <!-- policy column -->
        <div class="w-full sm:w-1/5 flex flex-col gap-2 my-3 sm:my-6 ml-5">
            <h2 class="text-primary-grey mb-2">POLICY</h2>
            <!-- links -->
            <a href="https://www.flipkart.com/pages/returnpolicy" class="hover:underline">Return Policy</a>
            <a href="https://www.flipkart.com/pages/terms" class="hover:underline">Terms Of Use</a>
            <a href="https://www.flipkart.com/pages/paymentsecurity" class="hover:underline">Security</a>
            <a href="https://www.flipkart.com/pages/privacypolicy" class="hover:underline">Privacy</a>
            <a href="https://www.flipkart.com/sitemap" class="hover:underline">Sitemap</a>
            <a href="https://www.flipkart.com/pages/ewaste-compliance-tnc" class="hover:underline">EPR Compliance</a>
            <!-- links -->
        </div>
        <!-- policy column -->

        <!-- socials column -->
        <div class="w-full sm:w-1/5 flex flex-col gap-2 my-3 sm:my-6 ml-5">
            <h2 class="text-primary-grey mb-2">SOCIAL</h2>
            <!-- links -->
            <a href="https://www.facebook.com/flipkart" class="hover:underline">Facebook</a>
            <a href="https://twitter.com/flipkart" class="hover:underline">Twitter</a>
            <a href="https://www.youtube.com/flipkart" class="hover:underline">YouTube</a>
            <!-- links -->
        </div>
        <!-- socials column -->
        </div>


        <div class="border-gray-600 h-36 w-1 border-l mr-5 mt-6 hidden sm:block"></div>
        <div class="w-full sm:w-5/12 my-6 mx-5 sm:mx-0 flex flex-col sm:flex-row gap-2 sm:gap-0 justify-between">
            <div class="w-full sm:w-1/2">
                <h2 class="text-primary-grey">Mail Us:</h2>
                <p class="mt-2 leading-5">Flipkart Internet Private Limited,<br>
                    Buildings Alyssa, Begonia &<br>                  
                    Clove Embassy Tech Village,<br>           
                    Outer Ring Road, Devarabeesanahalli Village,<br>             
                    Bengaluru, 560103,<br>
                    Karnataka, India
                </p>
            </div>

            <div class="w-full sm:w-1/2">
                <h2 class="text-primary-grey">Registered Office Address:</h2>
                <p class="mt-2 leading-5">Flipkart Internet Private Limited,<br>
                    Buildings Alyssa, Begonia &<br>                   
                    Clove Embassy Tech Village,<br>                   
                    Outer Ring Road, Devarabeesanahalli Village,<br>                  
                    Bengaluru, 560103,<br>                  
                    Karnataka, India <br>               
                    CIN : U51109KA2012PTC066107<br>                
                    Telephone: <a class="text-primary-blue" href="tel:18002029898">1800 202 9898</a>
                </p>
            </div>
        </div>

    </footer>
    <!-- footer ends -->

    <!-- copyright cards footer -->
    <div class="px-16 py-6 w-full bg-primary-darkBlue hidden sm:flex justify-between items-center text-sm text-white">
        <a href="https://seller.flipkart.com/sell-online" class="flex items-center gap-2">
           <i class="material-icons text-yellow-400 md-20">work</i> Sell On Flipkart
        </a>
        <a href="https://brands.flipkart.com" class="flex items-center gap-2">
            <i class="material-icons text-yellow-400 md-20">stars</i> Advertise
         </a>
         <a href="https://www.flipkart.com/the-gift-card-store" class="flex items-center gap-2">
            <i class="material-icons text-yellow-400 md-20">card_giftcard</i> Gift Cards
         </a>
         <a href="https://www.flipkart.com/helpcentre" class="flex items-center gap-2">
            <i class="material-icons text-yellow-400 md-20">help</i> Help Center
         </a>

         <div class="">
            &copy; 2007-2021 Flipkart.com
         </div>
         <img src="https://static-assets-web.flixcart.com/www/linchpin/fk-cp-zion/img/payment-method_69e7ec.svg" alt="">
    </div>
    <!-- copyright cards footer -->

    <!-- jquery cdn -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.6.0/jquery.min.js" integrity="sha512-894YE6QWD5I59HgZOGReFYm4dnWc1Qt5NtvYSaNcOP+u1T9qYdvdihz0PPSiiqn/+/3e7Jo4EaG7TubfWGUrMQ==" crossorigin="anonymous" referrerpolicy="no-referrer"></script>

    <!-- owl carousel cdn -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/OwlCarousel2/2.3.4/owl.carousel.min.js" integrity="sha512-bPs7Ae6pVvhOSiIcyUClR7/q2OAsRiovw4vAkX+zJbw3ShAeeqezq50RIIcIURq7Oa20rW2n2q+fyXBNcU9lrw==" crossorigin="anonymous" referrerpolicy="no-referrer"></script>

    <!-- js-image-zoom cdn -->
    <script src="https://cdn.jsdelivr.net/npm/js-image-zoom/js-image-zoom.min.js"></script>

    <!-- custom js -->
    <script src="./script.js"></script>
</body>
</html>
