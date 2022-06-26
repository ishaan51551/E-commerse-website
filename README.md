<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>E-Commerce_Website</title>
    <link rel="stylesheet" href="project23_E_Commerce.css">
</head>
<body>
    <header>
        <nav>
            <a href="#"><img class="logo" src="logo.png" alt="logo"></a>
            <ul id="navbarList">
                <li><a href="#">Home</a></li>
                <li><a href="products.html">Products</a></li>
                <li><a href="About.html">About</a></li>
                <li><a href="contact.html">Contact</a></li>
                <li><a href="Account.html">Account</a></li>
                <li><a href="cart.html"><img class="cart" src="cart.png" alt="cart"></a></li>
            </ul>
            <div class="hemburger">
                <li><a href="cart.html"><img class="cart" src="cart.png" alt="cart"></a></li>
                <img id="menu" src="menu.png" alt="menu">
            </div>
        </nav>
        <div class="menu" id="menubar">
            <li><a href="#">Home</a></li>
            <li><a href="products.html">Products</a></li>
            <li><a href="About.html">About</a></li>
            <li><a href="contact.html">Contact</a></li>
            <li><a href="Account.html">Account</a></li>
        </div>
        <div class="container">
            <div class="left">
                <h1>Give Your Workout <br> A New Style!</h1>
                <p>Success isn't always about greatness. it's about Consistency. Consistent <br> hard work gains
                    Success.
                    Greatness will come.</p>
                <button id="explore" class="btn">Explore Now &rarr;</button>
            </div>
            <div class="right">
                <img id="homeImage" src="image1.png" alt="image1">
            </div>
        </div>
    </header>
    <div id="category">
        <img class="category" src="category-4.jpg" alt="category-1">
        <img class="category" src="category-5.jpg" alt="category-2">
        <img class="category" src="category-7.jpg" alt="category-3">
    </div>
    <section id="Featured">
        <div class="heading">
            <h2>Featured Products</h2>
            <hr>
        </div>
        <div id="Featured_Products">
            <div class="products">
                <a href="details.html"><img class="products-img" src="product-1.jpg" alt="product-1"></a>
                <h3>Red Printed T-shirt</h3>
                <img class="rating" src="star4.5.jpg" alt="star4.5">
                <h3>$50.00</h3>
            </div>
            <div class="products">
                <img class="products-img" src="product-14.jpg" alt="product-2">
                <h3>Red Sports Shoes</h3>
                <img class="rating" src="star4.5.jpg" alt="star4.5">
                <h3>$75.00</h3>
            </div>
            <div class="products">
                <img class="products-img" src="product-3.jpg" alt="product-3">
                <h3>HRX Gray Trackpants</h3>
                <img class="rating" src="star4.5.jpg" alt="star4.5">
                <h3>$45.00</h3>
            </div>
            <div class="products">
                <img class="products-img" src="product-26.jpg" alt="product-4">
                <h3>Rolex Watch</h3>
                <img class="rating" src="star4.5.jpg" alt="star4.5">
                <h3>$220.00</h3>
            </div>
        </div>
    </section>
    <section id="Latest">
        <div class="heading">
            <h2>Latest Products</h2>
            <hr>
        </div>
        <div class="latest_Products">
            <div class="products">
                <img class="products-img" src="product-6.jpg" alt="product-1">
                <h3>Black Printed T-shirt</h3>
                <img class="rating" src="star4.5.jpg" alt="star4.5">
                <h3>$50.00</h3>
            </div>
            <div class="products">
                <img class="products-img" src="product-7.jpg" alt="product-2">
                <h3>HRX set of 3 Socks</h3>
                <img class="rating" src="star4.5.jpg" alt="star4.5">
                <h3>$60.00</h3>
            </div>
            <div class="products">
                <img class="products-img" src="product-12.jpg" alt="product-3">
                <h3>HRX Black Trackpants</h3>
                <img class="rating" src="star4.5.jpg" alt="star4.5">
                <h3>$45.00</h3>
            </div>
            <div class="products">
                <img class="products-img" src="product-19.jpg" alt="product-4">
                <h3>Full size T-shirt</h3>
                <img class="rating" src="star4.5.jpg" alt="star4.5">
                <h3>$70.00</h3>
            </div>
        </div>
        <div class="latest_Products">
            <div class="products">
                <img class="products-img" src="product-8.jpg" alt="product-1">
                <h3>Fossil branded Watch</h3>
                <img class="rating" src="star4.5.jpg" alt="star4.5">
                <h3>$200.00</h3>
            </div>
            <div class="products">
                <img class="products-img" src="product-10.jpg" alt="product-2">
                <h3>Puma Sports Shoes</h3>
                <img class="rating" src="star4.5.jpg" alt="star4.5">
                <h3>$75.00</h3>
            </div>
            <div class="products">
                <img class="products-img" src="product-24.jpg" alt="product-3">
                <h3>MSD Forever T-shirts</h3>
                <img class="rating" src="star4.5.jpg" alt="star4.5">
                <h3>$50.00</h3>
            </div>
            <div class="products">
                <img class="products-img" src="product-15.jpg" alt="product-4">
                <h3>Bruton Shoes</h3>
                <img class="rating" src="star4.5.jpg" alt="star4.5">
                <h3>$65.00</h3>
            </div>
        </div>
    </section>
    <section id="exclusive">
        <div class="left">
            <img src="exclusive.png" alt="exclusive" id="Smart_band">
        </div>
        <div class="right">
            <h3>Exclusively available on Redstore</h3>
            <h1>Smart Band 4</h1>
            <p>The MI Smart Band 4 features a 39.9% larger(than MI Band 3) AMOLED color <br>full touch display with
                adjustable brightness so everything is clear as can be.</p>
            <button id="buy" class="btn">Buy Now &rarr;</button>
        </div>
    </section>
    <section id="review">
        <div class="box">
            <h1>&#8220</h1>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Officiis, ea labore. Doloribus quis provident
                aspernatur omnis alias quas magnam suscipit consectetur! Ipsa libero illo iste commodi itaque quia
                debitis
                tempora.</p>
            <h3>&starf;&starf;&starf;&starf;&star;</h3>
            <img src="chris_Evans.jpg" alt="user-1" id="user-1" class="user">
            <h4>Chris Evans</h4>
        </div>
        <div class="box">
            <h1>&#8220</h1>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Officiis, ea labore. Doloribus quis provident
                aspernatur omnis alias quas magnam suscipit consectetur! Ipsa libero illo iste commodi itaque quia
                debitis
                tempora.</p>
            <h3>&starf;&starf;&starf;&starf;&star;</h3>
            <img src="tony.jpg" alt="user-2" id="user-2" class="user">
            <h4>Tony Stark</h4>
        </div>
        <div class="box">
            <h1>&#8220</h1>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Officiis, ea labore. Doloribus quis provident
                aspernatur omnis alias quas magnam suscipit consectetur! Ipsa libero illo iste commodi itaque quia
                debitis
                tempora.</p>
            <h3>&starf;&starf;&starf;&starf;&star;</h3>
            <img src="thor.jpg" alt="user-3" id="user-3" class="user">
            <h4>chris Hemsworth</h4>
        </div>
    </section>
    <div id="companies">
        <img src="logo-oppo.png" alt="logo-oppo" class="comapany">
        <img src="logo-philips.png" alt="logo-philips.png" class="comapany">
        <img src="logo-godrej.png" alt="logo-godrej" class="comapany">
        <img src="logo-paypal.png" alt="logo-paypal" class="comapany">
        <img src="logo-coca-cola.png" alt="logo-coca-cola" class="comapany">
    </div>
    <footer>
        <div class="top">
            <div>
                <h2>Download our App</h2>
                <h4>Download App for Android mobile phone.</h4>
                <img src="play-store.png" alt="play-store" class="store">
            </div>
            <div>
                <img class="logo" src="logo-white.png" alt="logo">
                <div>Our Purpose is to Sustainably Make the Pleasure and Benefites of Sports Accessible to the Many.
                </div>
            </div>
            <div>
                <h2>Useful Links</h2>
                <ul>
                    <li>Coupons</li>
                    <li>Blog Spot</li>
                    <li>Return Policy</li>
                    <li>Join Affiliate</li>
                </ul>
            </div>
            <div>
                <h2>Follow Us</h2>
                <ul>
                    <li>Facebook</li>
                    <li>Twitter</li>
                    <li>Instagram</li>
                    <li>Youtube</li>
                </ul>
            </div>
        </div>
        <hr>
        <div class="bottom">Copyright &copy; 2022 &rarr; Sanjay Soni</div>
    </footer>
    <script src="commonjs.js"></script>
</body>
</html>
