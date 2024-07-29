- 👋 Hi, I’m @shruti14-web
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
shruti14-web/shruti14-web is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
---><!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Learning Kits for Autistic Children</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background-color: #4CAF50;
            color: white;
            text-align: center;
            padding: 1em 0;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #333;
        }
        nav a {
            color: white;
            padding: 14px 20px;
            text-decoration: none;
            text-align: center;
        }
        nav a:hover {
            background-color: #ddd;
            color: black;
        }
        section {
            padding: 20px;
        }
        section h2 {
            color: #4CAF50;
        }
        footer {
            text-align: center;
            padding: 1em 0;
            background-color: #333;
            color: white;
        }
        .container {
            max-width: 1200px;
            margin: auto;
            padding: 20px;
        }
        .card {
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            padding: 20px;
            margin: 20px 0;
        }
        .card img {
            max-width: 100%;
            border-radius: 8px;
        }
        .contact-form {
            display: flex;
            flex-direction: column;
        }
        .contact-form input, .contact-form textarea {
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ddd;
            border-radius: 4px;
        }
        .contact-form button {
            background-color: #4CAF50;
            color: white;
            padding: 10px;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }
        .contact-form button:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>

<header>
    <h1>Learning Kits for Autistic Children</h1>
    <p>Helping children learn and grow</p>
</header>

<nav>
    <a href="#home">Home</a>
    <a href="#about">About Us</a>
    <a href="#challenges">Challenges</a>
    <a href="#kits">Activity Learning Kits</a>
    <a href="#prototype">Prototype & Solutions</a>
    <a href="#empathy">Empathy Map</a>
    <a href="#resources">Resources</a>
    <a href="#contact">Contact Us</a>
</nav>

<div class="container">
    <section id="home">
        <div class="card">
            <h2>Welcome to Our Website</h2>
            <p>We provide learning kits and resources to help autistic children overcome challenges and succeed.</p>
            <img src="welcome-image.jpg" alt="Welcome Image">
        </div>
    </section>

    <section id="about">
        <div class="card">
            <h2>About Us</h2>
            <p>Our mission is to support autistic children in their learning journey. Meet our team and learn about our story.</p>
            <img src="about-us.jpg" alt="About Us Image">
        </div>
    </section>

    <section id="challenges">
        <div class="card">
            <h2>Challenges Faced by Autistic Children</h2>
            <p>Understanding the common challenges faced by autistic children can help us create better solutions.</p>
            <img src="challenges.jpg" alt="Challenges Image">
        </div>
    </section>

    <section id="kits">
        <div class="card">
            <h2>Activity Learning Kits</h2>
            <p>Discover our range of activity learning kits designed to engage and educate autistic children.</p>
            <img src="kits.jpg" alt="Learning Kits Image">
        </div>
    </section>

    <section id="prototype">
        <div class="card">
            <h2>Prototype & Solutions</h2>
            <p>Explore our prototypes and the innovative solutions we have developed to address specific challenges.</p>
            <img src="prototype.jpg" alt="Prototype Image">
        </div>
    </section>

    <section id="empathy">
        <div class="card">
            <h2>Empathy Map</h2>
            <p>Understanding the thoughts, feelings, and needs of autistic children through empathy mapping.</p>
            <img src="empathy-map.jpg" alt="Empathy Map Image">
        </div>
    </section>

    <section id="resources">
        <div class="card">
            <h2>Resources</h2>
            <p>Access articles, research papers, and other helpful resources for parents, educators, and caregivers.</p>
            <img src="resources.jpg" alt="Resources Image">
        </div>
    </section>

    <section id="contact">
        <div class="card">
            <h2>Contact Us</h2>
            <form class="contact-form">
                <input type="text" name="name" placeholder="Your Name">
                <input type="email" name="email" placeholder="Your Email">
                <textarea name="message" rows="4" placeholder="Your Message"></textarea>
                <button type="submit">Submit</button>
            </form>
        </div>
    </section>
</div>

<footer>
    <p>&copy; 2024 Learning Kits for Autistic Children. All rights reserved.</p>
</footer>

<script>
    document.querySelector('.contact-form').addEventListener('submit', function(e) {
        e.preventDefault();
        alert('Thank you for contacting us!');
    });
</script>

</body>
</html>

