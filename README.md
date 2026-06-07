<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Your Hotel Name</title>

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Poppins',sans-serif;
}

body{
background:#f8f9fa;
color:#333;
}

header{
background:#0a2342;
color:white;
padding:20px;
text-align:center;
}

header h1{
font-size:45px;
letter-spacing:2px;
}

nav{
background:#12355b;
padding:15px;
text-align:center;
}

nav a{
color:white;
text-decoration:none;
margin:15px;
font-weight:bold;
}

.hero{
height:90vh;
background:
linear-gradient(rgba(0,0,0,.5),rgba(0,0,0,.5)),
url('https://images.unsplash.com/photo-1566073771259-6a8506099945');
background-size:cover;
background-position:center;
display:flex;
justify-content:center;
align-items:center;
flex-direction:column;
text-align:center;
color:white;
}

.hero h2{
font-size:65px;
}

.hero p{
font-size:22px;
margin:20px;
}

.btn{
background:#f4a261;
color:white;
padding:15px 35px;
text-decoration:none;
border-radius:30px;
font-weight:bold;
}

section{
padding:70px 10%;
}

.section-title{
text-align:center;
font-size:38px;
margin-bottom:40px;
color:#0a2342;
}

.rooms{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
gap:25px;
}

.room-card{
background:white;
border-radius:15px;
overflow:hidden;
box-shadow:0 5px 15px rgba(0,0,0,.1);
}

.room-card img{
width:100%;
height:220px;
object-fit:cover;
}

.room-content{
padding:20px;
}

.gallery{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:20px;
}

.gallery img{
width:100%;
height:250px;
object-fit:cover;
border-radius:15px;
}

.price-list{
background:white;
padding:30px;
border-radius:15px;
box-shadow:0 5px 15px rgba(0,0,0,.1);
max-width:700px;
margin:auto;
}

.price-item{
display:flex;
justify-content:space-between;
padding:15px;
border-bottom:1px solid #ddd;
}

.contact{
background:#0a2342;
color:white;
padding:40px;
border-radius:15px;
text-align:center;
}

footer{
background:#081c33;
color:white;
text-align:center;
padding:20px;
}

</style>
</head>

<body>

<header>
<h1>YOUR HOTEL NAME</h1>
<p>Luxury • Comfort • Excellence</p>
</header>

<nav>
<a href="#">Home</a>
<a href="#rooms">Rooms</a>
<a href="#gallery">Gallery</a>
<a href="#prices">Prices</a>
<a href="#contact">Contact</a>
</nav>

<section class="hero">

<h2>Experience Luxury Living</h2>

<p>Your perfect destination for relaxation and comfort.</p>

<a href="#contact" class="btn">
Book Your Stay
</a>

</section>

<section id="rooms">

<h2 class="section-title">Our Rooms</h2>

<div class="rooms">

<div class="room-card">

<img src="https://images.unsplash.com/photo-1590490360182-c33d57733427">

<div class="room-content">
<h3>Standard Room</h3>
<p>Comfortable room with modern facilities.</p>
</div>

</div>

<div class="room-card">

<img src="https://images.unsplash.com/photo-1582719508461-905c673771fd">

<div class="room-content">
<h3>Deluxe Room</h3>
<p>Luxury room with stunning views.</p>
</div>

</div>

<div class="room-card">

<img src="https://images.unsplash.com/photo-1445019980597-93fa8acb246c">

<div class="room-content">
<h3>Executive Suite</h3>
<p>Premium suite for ultimate comfort.</p>
</div>

</div>

</div>

</section>

<section id="gallery">

<h2 class="section-title">Hotel Gallery</h2>

<div class="gallery">

<img src="https://images.unsplash.com/photo-1566073771259-6a8506099945">

<img src="https://images.unsplash.com/photo-1578683010236-d716f9a3f461">

<img src="https://images.unsplash.com/photo-1522708323590-d24dbb6b0267">

<img src="https://images.unsplash.com/photo-1584132967334-10e028bd69f7">

</div>

</section>

<section id="prices">

<h2 class="section-title">Room Prices</h2>

<div class="price-list">

<div class="price-item">
<span>Standard Room</span>
<span>R _____ / Night</span>
</div>

<div class="price-item">
<span>Deluxe Room</span>
<span>R _____ / Night</span>
</div>

<div class="price-item">
<span>Executive Suite</span>
<span>R _____ / Night</span>
</div>

<div class="price-item">
<span>Breakfast</span>
<span>R _____</span>
</div>

</div>

</section>

<section id="contact">

<div class="contact">

<h2>Contact Us</h2>

<p>📞 YOUR PHONE NUMBER</p>

<p>📧 reservations@yourhotel.com</p>

<p>📍 YOUR HOTEL ADDRESS</p>

<br>

<a href="tel:YOURNUMBER" class="btn">
Call Now
</a>

</div>

</section>

<footer>

<p>© 2026 YOUR HOTEL NAME. All Rights Reserved.</p>

</footer>

</body>
</html>
