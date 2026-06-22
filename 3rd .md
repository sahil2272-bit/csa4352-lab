<img width="1917" height="1078" alt="image" src="https://github.com/user-attachments/assets/ac64aeea-3f06-492c-bf3f-6083508229c9" />

<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">

<title>Bus Ticket Booking System</title>

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial,sans-serif;
}

body{
background:#f4f4f4;
}

header{
background:#0f172a;
color:white;
padding:15px;
display:flex;
justify-content:space-between;
align-items:center;
}

nav ul{
display:flex;
list-style:none;
}

nav ul li{
margin-left:20px;
}

nav ul li a{
text-decoration:none;
color:white;
font-weight:bold;
}

.hero{
height:85vh;
background:linear-gradient(rgba(0,0,0,.6),
rgba(0,0,0,.6)),
url('bus.jpg');
background-size:cover;
display:flex;
justify-content:center;
align-items:center;
flex-direction:column;
color:white;
}

.hero h1{
font-size:50px;
margin-bottom:20px;
}

.search-box{
background:white;
padding:20px;
border-radius:10px;
display:grid;
grid-template-columns:repeat(5,1fr);
gap:10px;
width:80%;
}

.search-box input,
.search-box select,
.search-box button{
padding:12px;
}

.search-box button{
background:#2563eb;
color:white;
border:none;
cursor:pointer;
}

.features{
padding:50px;
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:20px;
}

.card{
background:white;
padding:20px;
border-radius:10px;
box-shadow:0 0 10px rgba(0,0,0,.1);
text-align:center;
}

footer{
background:#0f172a;
color:white;
text-align:center;
padding:15px;
}

</style>
</head>

<body>

<header>

<h2>Bus Booking Portal</h2>

<nav>
<ul>
<li><a href="#">Home</a></li>
<li><a href="#">Search Bus</a></li>
<li><a href="#">Bookings</a></li>
<li><a href="#">Login</a></li>
<li><a href="#">Register</a></li>
<li><a href="#">Contact</a></li>
</ul>
</nav>

</header>

<section class="hero">

<h1>Book Bus Tickets Online</h1>

<div class="search-box">

<input type="text" placeholder="From">

<input type="text" placeholder="To">

<input type="date">

<select>
<option>Bus Type</option>
<option>Volvo</option>
<option>Sleeper</option>
<option>AC Coach</option>
<option>Non AC</option>
</select>

<button>Search Bus</button>

</div>

</section>

<section class="features">

<div class="card">
<h3>Easy Booking</h3>
<p>Book tickets instantly.</p>
</div>

<div class="card">
<h3>Seat Selection</h3>
<p>Select your preferred seat.</p>
</div>

<div class="card">
<h3>Secure Payment</h3>
<p>Safe online transactions.</p>
</div>

<div class="card">
<h3>Booking History</h3>
<p>Track all your tickets.</p>
</div>

</section>

<footer>

<p>© 2026 Bus Ticket Booking System</p>

</footer>

Functional Requirements
User Module
Registration
User Registration
Login
Forgot Password
Change Password
Bus Search
Search Bus by Source
Destination
Travel Date
Bus Type
Departure Time
Ticket Booking
Check Seat Availability
Select Seats
Enter Passenger Details
Online Payment
Ticket Confirmation
Booking Management
View Booking History
Download Ticket
Cancel Ticket
Comments & Reviews
Post Comments
Rate Bus Service</body>
</html>
