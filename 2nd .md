<img width="1918" height="1078" alt="image" src="https://github.com/user-attachments/assets/3f149904-72ea-4fca-b5fc-31f4db20fe55" />
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">

<title>Hotel Booking System</title>

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial,sans-serif;
}

body{
background:#f5f5f5;
}

header{
background:#003566;
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
color:white;
text-decoration:none;
font-weight:bold;
}

.hero{
height:90vh;
background:url('hotel.jpg');
background-size:cover;
display:flex;
justify-content:center;
align-items:center;
flex-direction:column;
color:white;
background-color:#00000080;
}

.hero h1{
font-size:50px;
margin-bottom:15px;
}

.search-box{
background:white;
padding:20px;
border-radius:10px;
width:80%;
display:grid;
grid-template-columns:repeat(5,1fr);
gap:10px;
}

.search-box input,
.search-box select,
.search-box button{
padding:12px;
}

.search-box button{
background:#003566;
color:white;
border:none;
cursor:pointer;
}

.rooms{
padding:50px;
display:grid;
grid-template-columns:repeat(auto-fit,minmax(300px,1fr));
gap:20px;
}

.room-card{
background:white;
padding:20px;
border-radius:10px;
box-shadow:0 0 10px rgba(0,0,0,.1);
}

.room-card img{
width:100%;
height:200px;
object-fit:cover;
}

footer{
background:#003566;
color:white;
text-align:center;
padding:15px;
}

</style>
</head>

<body>

<header>

<h2>Hotel Booking</h2>

<nav>
<ul>
<li><a href="#">Home</a></li>
<li><a href="#">Rooms</a></li>
<li><a href="#">About</a></li>
<li><a href="#">Contact</a></li>
<li><a href="#">Login</a></li>
</ul>
</nav>

</header>

<section class="hero">

<h1>Find Your Perfect Stay</h1>

<div class="search-box">

<input type="text" placeholder="Destination">

<input type="date">

<input type="date">

<select>
<option>Guests</option>
<option>1</option>
<option>2</option>
<option>3</option>
<option>4</option>
</select>

<button>Search Rooms</button>

</div>

</section>

<section class="rooms">

<div class="room-card">
<img src="room1.jpg">
<h3>Standard Room</h3>
<p>₹2500/Night</p>
</div>

<div class="room-card">
<img src="room2.jpg">
<h3>Deluxe Room</h3>
<p>₹4000/Night</p>
</div>

<div class="room-card">
<img src="room3.jpg">
<h3>Suite Room</h3>
<p>₹6500/Night</p>
</div>

<div class="room-card">
<img src="room4.jpg">
<h3>Luxury Suite</h3>
<p>₹10000/Night</p>
</div>

</section>

<footer>

<p>© 2026 Hotel Booking System</p>

</footer>

</body>
</html>

Project Requirements
User Functionalities
Authentication
Register
Login
Logout
Update Profile
Room Booking
Search Rooms
Check Availability
View Room Details
Book Room
Secure Payment
Booking Management
View Booking History
Modify Booking (3 days before arrival)
Cancel Booking (3 days before arrival)
Reviews
Give Ratings
Write Reviews
Administrator Functionalities
Room Management
Add Room
Update Room Details
Delete Room
Change Room Quantity
Change Room Price
Booking Management
View All Bookings
Modify Any Booking
Cancel Any Booking
Website Content Management
About Us
Contact Us
Room Information
Customer Service Q&A
Local Travel Guide
Privacy Policy
User Management
View Users
Edit Users
Delete Users
