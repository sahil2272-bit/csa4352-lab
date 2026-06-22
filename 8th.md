<img width="1918" height="1078" alt="image" src="https://github.com/user-attachments/assets/8c3f66c9-758a-4678-8b0f-782e87153192" />

```html
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>MedCare Hospital Appointment System</title>

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Segoe UI',sans-serif;
}

body{
background:#f4f8fc;
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
font-size:28px;
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
color:white;
text-decoration:none;
font-weight:bold;
}

.hero{
height:90vh;
background:linear-gradient(rgba(0,0,0,0.5),
rgba(0,0,0,0.5)),
url('https://images.unsplash.com/photo-1519494026892-80bbd2d6fd0d?w=1600');
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
font-size:55px;
margin-bottom:15px;
}

.hero p{
font-size:22px;
margin-bottom:25px;
}

.search-box{
background:white;
padding:20px;
border-radius:10px;
display:grid;
grid-template-columns:repeat(3,1fr);
gap:10px;
width:80%;
max-width:900px;
}

.search-box input,
.search-box select,
.search-box button{
padding:12px;
border:1px solid #ccc;
border-radius:5px;
}

.search-box button{
background:#0d6efd;
color:white;
border:none;
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
box-shadow:0 0 10px rgba(0,0,0,0.1);
text-align:center;
}

.card h3{
margin-bottom:10px;
color:#0d6efd;
}

.hospitals{
padding:50px;
background:#eef5ff;
}

.hospitals h2{
text-align:center;
margin-bottom:30px;
}

.hospital-grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:20px;
}

.hospital-card{
background:white;
padding:20px;
border-radius:10px;
box-shadow:0 0 10px rgba(0,0,0,0.1);
text-align:center;
}

.hospital-card button{
margin-top:10px;
padding:10px 15px;
background:#0d6efd;
color:white;
border:none;
cursor:pointer;
border-radius:5px;
}

footer{
background:#0d6efd;
color:white;
text-align:center;
padding:15px;
margin-top:30px;
}

</style>
</head>

<body>

<header>

<div class="logo">🏥 MedCare Hospital</div>

<nav>
<ul>
<li><a href="#">Home</a></li>
<li><a href="#">Hospitals</a></li>
<li><a href="#">Doctors</a></li>
<li><a href="#">Appointments</a></li>
<li><a href="#">Login</a></li>
<li><a href="#">Register</a></li>
</ul>
</nav>

</header>

<section class="hero">

<h1>Book Doctor Appointments Online</h1>

<p>Search Hospitals, Find Doctors and Schedule Appointments Instantly</p>

<div class="search-box">

<input type="text" placeholder="Enter Location">

<select>
<option>Select Specialty</option>
<option>Cardiology</option>
<option>Dermatology</option>
<option>Orthopedics</option>
<option>Neurology</option>
<option>Pediatrics</option>
</select>

<button>Search Doctors</button>

</div>

</section>

<section class="features">

<div class="card">
<h3>👨‍⚕️ Expert Doctors</h3>
<p>Find experienced doctors from multiple specialties.</p>
</div>

<div class="card">
<h3>📅 Easy Booking</h3>
<p>Book appointments with flexible date and time slots.</p>
</div>

<div class="card">
<h3>📍 Search Hospitals</h3>
<p>Locate hospitals near your area instantly.</p>
</div>

<div class="card">
<h3>📋 Medical History</h3>
<p>Access previous appointments and check-in records.</p>
</div>

</section>

<section class="hospitals">

<h2>Popular Hospitals</h2>

<div class="hospital-grid">

<div class="hospital-card">
<h3>Apollo Hospital</h3>
<p>Hyderabad</p>
<button>View Details</button>
</div>

<div class="hospital-card">
<h3>Care Hospital</h3>
<p>Vijayawada</p>
<button>View Details</button>
</div>

<div class="hospital-card">
<h3>Yashoda Hospital</h3>
<p>Hyderabad</p>
<button>View Details</button>
</div>

</div>

</section>

<footer>
<p>© 2026 MedCare Hospital Appointment Booking System</p>
</footer>

</body>
</html>
```
