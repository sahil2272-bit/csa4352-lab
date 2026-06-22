<img width="1915" height="1078" alt="image" src="https://github.com/user-attachments/assets/69d97b39-570d-4eda-a483-893eb0f1765d" />

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Wanderlust Travels</title>

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Segoe UI',sans-serif;
}

body{
background:#f5f7fa;
}

header{
background:#0d6efd;
padding:15px 50px;
display:flex;
justify-content:space-between;
align-items:center;
color:white;
}

.logo{
font-size:30px;
font-weight:bold;
}

nav ul{
display:flex;
list-style:none;
}

nav ul li{
margin-left:25px;
}

nav ul li a{
text-decoration:none;
color:white;
font-weight:bold;
}

.hero{
height:90vh;
background:linear-gradient(rgba(0,0,0,.5),
rgba(0,0,0,.5)),
url('https://images.unsplash.com/photo-1507525428034-b723cf961d3e?w=1600');
background-size:cover;
background-position:center;
display:flex;
justify-content:center;
align-items:center;
flex-direction:column;
text-align:center;
color:white;
}

.hero h1{
font-size:60px;
margin-bottom:15px;
}

.hero p{
font-size:22px;
margin-bottom:20px;
}

.search-box{
background:white;
padding:20px;
border-radius:10px;
display:flex;
gap:10px;
width:80%;
max-width:900px;
}

.search-box input{
flex:1;
padding:12px;
border:1px solid #ccc;
border-radius:5px;
}

.search-box button{
padding:12px 20px;
background:#0d6efd;
color:white;
border:none;
border-radius:5px;
cursor:pointer;
}

.features{
padding:60px;
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:20px;
}

.card{
background:white;
padding:25px;
border-radius:10px;
text-align:center;
box-shadow:0 0 10px rgba(0,0,0,.1);
}

.card h3{
color:#0d6efd;
margin-bottom:10px;
}

.destinations{
background:#eef5ff;
padding:60px;
}

.destinations h2{
text-align:center;
margin-bottom:30px;
}

.destination-grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:20px;
}

.place{
background:white;
padding:20px;
border-radius:10px;
text-align:center;
box-shadow:0 0 10px rgba(0,0,0,.1);
}

.place button{
margin-top:10px;
padding:10px 15px;
background:#0d6efd;
color:white;
border:none;
border-radius:5px;
cursor:pointer;
}

footer{
background:#0d6efd;
color:white;
text-align:center;
padding:15px;
}

</style>
</head>

<body>

<header>

<div class="logo">✈ Wanderlust Travels</div>

<nav>
<ul>
<li><a href="#">Home</a></li>
<li><a href="#">Destinations</a></li>
<li><a href="#">Hotels</a></li>
<li><a href="#">Routes</a></li>
<li><a href="#">Login</a></li>
<li><a href="#">Register</a></li>
</ul>
</nav>

</header>

<section class="hero">

<h1>Explore The World</h1>

<p>Book Hotels, Discover Routes & Plan Your Dream Trip</p>

<div class="search-box">
<input type="text" placeholder="Enter Destination">
<input type="text" placeholder="Check-in Date">
<button>Search</button>
</div>

</section>

<section class="features">

<div class="card">
<h3>🏨 Hotels</h3>
<p>Find the best accommodation deals.</p>
</div>

<div class="card">
<h3>🍽 Food Guide</h3>
<p>Discover famous local cuisines.</p>
</div>

<div class="card">
<h3>🗺 Travel Routes</h3>
<p>Explore routes and travel plans.</p>
</div>

<div class="card">
<h3>📖 Travel Guides</h3>
<p>Get recommendations and tips.</p>
</div>

</section>

<section class="destinations">

<h2>Popular Destinations</h2>

<div class="destination-grid">

<div class="place">
<h3>Goa</h3>
<p>Beaches, Resorts & Nightlife</p>
<button>View Details</button>
</div>

<div class="place">
<h3>Manali</h3>
<p>Mountains & Adventure Sports</p>
<button>View Details</button>
</div>

<div class="place">
<h3>Jaipur</h3>
<p>Historic Palaces & Culture</p>
<button>View Details</button>
</div>

</div>

</section>

<footer>
<p>© 2026 Wanderlust Travels | All Rights Reserved</p>
</footer>

</body>
</html>
