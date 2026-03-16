# minicafe
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Bean Haven Café</title>

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial, Helvetica, sans-serif;
}

body{
background:#f7f3ef;
color:#333;
}

/* NAVBAR */

nav{
display:flex;
justify-content:space-between;
align-items:center;
padding:20px 8%;
background:#3e2723;
color:white;
}

nav h1{
font-size:24px;
}

nav ul{
display:flex;
list-style:none;
gap:20px;
}

nav ul li a{
color:white;
text-decoration:none;
font-size:16px;
}

/* HERO */

.hero{
height:90vh;
background:url("https://images.unsplash.com/photo-1509042239860-f550ce710b93") center/cover;
display:flex;
align-items:center;
justify-content:center;
text-align:center;
color:white;
}

.hero h2{
font-size:48px;
margin-bottom:20px;
}

.hero p{
font-size:18px;
margin-bottom:25px;
}

.hero button{
padding:12px 25px;
border:none;
background:#ff9800;
color:white;
font-size:16px;
border-radius:5px;
cursor:pointer;
}

/* ABOUT */

.about{
padding:80px 10%;
text-align:center;
}

.about h2{
font-size:32px;
margin-bottom:20px;
}

.about p{
max-width:700px;
margin:auto;
font-size:17px;
line-height:1.6;
}

/* MENU */

.menu{
padding:80px 10%;
background:white;
text-align:center;
}

.menu h2{
font-size:32px;
margin-bottom:40px;
}

.menu-items{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(200px,1fr));
gap:25px;
}

.item{
background:#f4f4f4;
padding:25px;
border-radius:10px;
}

.item h3{
margin-bottom:10px;
}

/* CONTACT */

.contact{
padding:80px 10%;
text-align:center;
}

.contact h2{
font-size:32px;
margin-bottom:20px;
}

.contact p{
margin:10px 0;
}

/* FOOTER */

footer{
background:#3e2723;
color:white;
text-align:center;
padding:20px;
margin-top:40px;
}

/* MOBILE */

@media(max-width:768px){

.hero h2{
font-size:36px;
}

nav ul{
display:none;
}

}

</style>
</head>

<body>

<!-- NAVBAR -->

<nav>
<h1>Bean Haven</h1>
<ul>
<li><a href="#">Home</a></li>
<li><a href="#about">About</a></li>
<li><a href="#menu">Menu</a></li>
<li><a href="#contact">Contact</a></li>
</ul>
</nav>

<!-- HERO -->

<section class="hero">
<div>
<h2>Fresh Coffee Everyday</h2>
<p>Your perfect place for coffee, snacks and relaxation</p>
<button>View Menu</button>
</div>
</section>

<!-- ABOUT -->

<section class="about" id="about">
<h2>About Our Café</h2>
<p>
At Bean Haven Café, we serve freshly brewed coffee made from premium beans. 
Our cozy atmosphere is the perfect place to relax, work, or meet friends. 
Enjoy delicious pastries, sandwiches, and desserts with every cup.
</p>
</section>

<!-- MENU -->

<section class="menu" id="menu">
<h2>Popular Menu</h2>

<div class="menu-items">

<div class="item">
<h3>Espresso</h3>
<p>Strong and rich coffee shot</p>
</div>

<div class="item">
<h3>Cappuccino</h3>
<p>Espresso with steamed milk foam</p>
</div>

<div class="item">
<h3>Latte</h3>
<p>Smooth coffee with creamy milk</p>
</div>

<div class="item">
<h3>Chocolate Cake</h3>
<p>Delicious sweet dessert</p>
</div>

</div>

</section>

<!-- CONTACT -->

<section class="contact" id="contact">
<h2>Visit Us</h2>
<p>📍 123 Coffee Street, Your City</p>
<p>📞 +91 9876543210</p>
<p>⏰ Open Daily: 8 AM – 10 PM</p>
</section>

<!-- FOOTER -->

<footer>
<p>© 2026 Bean Haven Café | All Rights Reserved</p>
</footer>

</body>
</html>
