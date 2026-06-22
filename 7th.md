<img width="1918" height="957" alt="image" src="https://github.com/user-attachments/assets/4dbbbcd1-4d44-433c-8e09-cee478beab6c" />

```html
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Beauty Parlour Appointment Booking</title>

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial,sans-serif;
}

body{
background:#fff8f8;
}

header{
background:#d63384;
color:white;
padding:15px 40px;
display:flex;
justify-content:space-between;
align-items:center;
}

.logo{
font-size:28px;
font-weight:bold;
}

nav ul{
display:flex;
list-style:none;
}

nav ul li{
margin-left:20px;
}

nav ul li a{
color:white;
text-decoration:none;
font-weight:bold;
}

.hero{
height:85vh;
display:flex;
justify-content:center;
align-items:center;
flex-direction:column;
text-align:center;
color:white;
background:linear-gradient(rgba(0,0,0,.4),
rgba(0,0,0,.4)),
url('https://images.unsplash.com/photo-1521590832167-7bcbfaa6381f');
background-size:cover;
background-position:center;
}

.hero h1{
font-size:55px;
margin-bottom:15px;
}

.hero p{
font-size:22px;
margin-bottom:25px;
}

.hero button{
padding:15px 25px;
background:#d63384;
border:none;
color:white;
font-size:18px;
cursor:pointer;
border-radius:5px;
}

.services{
padding:50px;
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:20px;
}

.card{
background:white;
border-radius:10px;
overflow:hidden;
box-shadow:0 0 10px rgba(0,0,0,.1);
}

.card img{
width:100%;
height:220px;
object-fit:cover;
}

.card-content{
padding:15px;
text-align:center;
}

.card-content h3{
margin-bottom:10px;
}

.card-content p{
margin-bottom:10px;
}

.card-content button{
padding:10px 15px;
background:#d63384;
border:none;
color:white;
cursor:pointer;
}

footer{
background:#d63384;
color:white;
text-align:center;
padding:15px;
}

</style>
</head>

<body>

<header>

<div class="logo">💄 Beauty Parlour</div>

<nav>
<ul>
<li><a href="#">Home</a></li>
<li><a href="#">Services</a></li>
<li><a href="#">Stylists</a></li>
<li><a href="#">Appointments</a></li>
<li><a href="#">Login</a></li>
</ul>
</nav>

</header>

<section class="hero">

<h1>Book Your Beauty Appointment</h1>

<p>Choose Services, Select Stylist & Reserve Instantly</p>

<button>Book Appointment</button>

</section>

<section class="services">

<div class="card">
<img src="https://images.unsplash.com/photo-1560066984-138dadb4c035">
<div class="card-content">
<h3>Hair Styling</h3>
<p>Professional Hair Care Services</p>
<button>Book Now</button>
</div>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1522335789203-aabd1fc54bc9">
<div class="card-content">
<h3>Facial Treatment</h3>
<p>Glow & Skin Care Packages</p>
<button>Book Now</button>
</div>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1515377905703-c4788e51af15">
<div class="card-content">
<h3>Bridal Makeup</h3>
<p>Premium Bridal Beauty Services</p>
<button>Book Now</button>
</div>
</div>

</section>

<footer>
<p>© 2026 Beauty Parlour Booking System | All Rights Reserved</p>
</footer>

</body>
</html>
```
