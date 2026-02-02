<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Family Youth Group</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f8ff;
            color: #333;
        }
        header {
            background-color: #007acc;
            color: white;
            padding: 20px 0;
            text-align: center;
        }
        nav {
            background-color: #005fa3;
            display: flex;
            justify-content: center;
            gap: 20px;
        }
        nav a {
            color: white;
            text-decoration: none;
            padding: 15px;
        }
        nav a:hover {
            background-color: #004080;
            border-radius: 5px;
        }
        section {
            padding: 50px 20px;
            max-width: 1000px;
            margin: auto;
        }
        h2 {
            color: #007acc;
        }
        .activities {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }
        .activity-card {
            background-color: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 2px 8px rgba(0,0,0,0.1);
        }
        footer {
            background-color: #007acc;
            color: white;
            text-align: center;
            padding: 20px;
        }
        form input, form textarea {
            width: 100%;
            padding: 10px;
            margin: 5px 0 15px 0;
            border-radius: 5px;
            border: 1px solid #ccc;
        }
        form button {
            padding: 10px 20px;
            background-color: #007acc;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        form button:hover {
            background-color: #005fa3;
        }
    </style>
</head>
<body>
    <header>
        <h1>Family Youth Group</h1>
        <p>Connecting youth and families for a brighter future</p>
    </header>

    <nav>
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#activities">Activities</a>
        <a href="#contact">Contact</a>
    </nav>

    <section id="home">
        <h2>Welcome to Our Group</h2>
        <p>We are a community-focused youth group aiming to empower young people and build strong family bonds. Join us for events, workshops, and fun activities!</p>
    </section>

    <section id="about">
        <h2>About Us</h2>
        <p>Family Youth Group started in 2024 with a mission to create a safe and inspiring space for youth. We believe in teamwork, learning, and community support.</p>
    </section>

    <section id="activities">
        <h2>Our Activities</h2>
        <div class="activities">
            <div class="activity-card">
                <h3>Workshops</h3>
                <p>Skill-building workshops for leadership, creativity, and personal growth.</p>
            </div>
            <div class="activity-card">
                <h3>Community Service</h3>
                <p>Participate in local community projects and volunteer opportunities.</p>
            </div>
            <div class="activity-card">
                <h3>Sports & Events</h3>
                <p>Fun sports, competitions, and social events to connect with peers.</p>
            </div>
        </div>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <form>
            <input type="text" placeholder="Your Name" required>
            <input type="email" placeholder="Your Email" required>
            <textarea rows="5" placeholder="Your Message" required></textarea>
            <button type="submit">Send Message</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2026 Family Youth Group. All rights reserved.</p>
    </footer>
</body>
</html>
