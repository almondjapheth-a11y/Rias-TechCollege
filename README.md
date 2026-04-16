<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Rias Technical College</title>

<style>
body {
  margin: 0;
  font-family: 'Segoe UI', sans-serif;
  background: #0f172a;
  color: white;
}

/* NAVBAR */
nav {
  display: flex;
  justify-content: space-between;
  padding: 15px 30px;
  background: rgba(0,0,0,0.6);
  position: sticky;
  top: 0;
}

nav h2 { color: #38bdf8; }
nav a {
  color: white;
  margin-left: 15px;
  text-decoration: none;
}

/* HERO */
.hero {
  text-align: center;
  padding: 100px 20px;
  background: linear-gradient(to right, #0f172a, #1e3a8a);
}

.hero h1 {
  font-size: 45px;
}

.hero p {
  font-size: 18px;
  opacity: 0.8;
}

.btn {
  display: inline-block;
  margin-top: 15px;
  padding: 12px 25px;
  background: #38bdf8;
  color: black;
  text-decoration: none;
  border-radius: 6px;
}

/* COURSES */
section {
  padding: 40px 20px;
  text-align: center;
}

.courses {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
}

.card {
  background: #1e293b;
  margin: 15px;
  padding: 20px;
  width: 250px;
  border-radius: 10px;
  transition: 0.3s;
}

.card:hover {
  transform: scale(1.05);
}

/* FORM */
form {
  max-width: 400px;
  margin: auto;
}

input, textarea {
  width: 100%;
  padding: 10px;
  margin: 10px 0;
  border: none;
  border-radius: 5px;
}

/* FOOTER */
footer {
  background: #020617;
  text-align: center;
  padding: 20px;
}
</style>
</head>

<body>

<!-- NAV -->
<nav>
<h2>RiasTech 🎓</h2>
<div>
<a href="#">Home</a>
<a href="#courses">Courses</a>
<a href="#apply">Apply</a>
<a href="#contact">Contact</a>
</div>
</nav>

<!-- HERO -->
<div class="hero">
<h1>Build Your Future with Skills</h1>
<p>Join a leading technical college focused on real-world training</p>
<a class="btn" href="#apply">Apply Now</a>
</div>

<!-- COURSES -->
<section id="courses">
<h2>Our Courses</h2>
<div class="courses">

<div class="card">
<h3>💻 Computer Studies</h3>
<p>Programming, networking & IT skills</p>
</div>

<div class="card">
<h3>⚡ Electrical Engineering</h3>
<p>Installation & maintenance training</p>
</div>

<div class="card">
<h3>🔧 Mechanical Engineering</h3>
<p>Machine operation & repair</p>
</div>

<div class="card">
<h3>📊 Business Studies</h3>
<p>Entrepreneurship & management</p>
</div>

</div>
</section>

<!-- APPLY -->
<section id="apply">
<h2>Apply Now</h2>

<form>
<input type="text" placeholder="Full Name" required>
<input type="email" placeholder="Email" required>
<input type="text" placeholder="Phone Number" required>
<textarea placeholder="Course Interested In"></textarea>
<button class="btn">Submit Application</button>
</form>
</section>

<!-- CONTACT -->
<section id="contact">
<h2>Contact Us</h2>
<p>Phone: 0712345678</p>
<p>Email: info@elitetech.ac.ke</p>

<a class="btn" href="https://wa.me/254712345678">Chat on WhatsApp</a>
</section>

<footer>
© 2026 Rias Technical College
</footer>

</body>
</html>
