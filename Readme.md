<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Avalanche.gg - Valorant community and esports">
    <title>Avalanche.gg - Valorant</title>
    <style>
        /* Basic CSS for centering and styling */
        body {
            font-family: 'Orbitron', sans-serif;
            margin: 0;
            padding: 0;
            background: url('https://plus.unsplash.com/premium_photo-1673859054724-d3ce699da39d?fm=jpg&q=60&w=3000&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8MXx8c25vd3klMjBtb3VudGFpbnxlbnwwfHwwfHx8MA%3D%3D') no-repeat center center fixed;
            background-size: cover;
            color: #fff;
            scroll-behavior: smooth;
            background-attachment: fixed;
        }

        /* Overlay to darken the background and ensure content is visible */
        .background-overlay {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0, 0, 0, 0.7); /* Dark overlay */
            z-index: -1; /* To make sure content is above */
        }

        header {
            background-color: rgba(0, 0, 0, 0.7);
            color: #fff;
            text-align: center;
            padding: 30px 0;
            border-bottom: 2px solid #00e5ff;
        }

        header h1 {
            margin: 0;
            font-size: 48px;
            font-weight: 700;
            letter-spacing: 5px;
            color: #00e5ff;
            text-transform: uppercase;
        }

        nav ul {
            list-style-type: none;
            padding: 0;
            margin: 0;
            display: flex;
            justify-content: center;
            gap: 30px;
        }

        nav ul li {
            display: inline-block;
        }

        nav ul li a {
            color: #fff;
            text-decoration: none;
            font-weight: bold;
            font-size: 18px;
            padding: 12px 20px;
            transition: background-color 0.3s ease, transform 0.3s ease;
            border-radius: 5px;
            letter-spacing: 1px;
        }

        nav ul li a:hover {
            background-color: #00e5ff;
            color: #111;
            transform: scale(1.1);
        }

        main {
            padding: 80px 20px;
            text-align: center;
            background: rgba(0, 0, 0, 0.6);
            border-radius: 10px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.6);
        }

        section {
            margin: 40px 0;
            padding: 30px;
            background: rgba(0, 0, 0, 0.7);
            border-radius: 10px;
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.6);
            transition: transform 0.3s ease;
        }

        section:hover {
            transform: scale(1.02);
        }

        h2 {
            font-size: 36px;
            font-weight: bold;
            color: #00e5ff;
            text-transform: uppercase;
        }

        p {
            font-size: 18px;
            line-height: 1.6;
            color: #ccc;
        }

        .service-item, .team-member {
            margin: 20px;
            display: inline-block;
            width: 300px;
            background-color: #222;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .service-item:hover, .team-member:hover {
            transform: scale(1.05);
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.5);
        }

        .team-member h3, .service-item h3 {
            font-size: 22px;
            font-weight: bold;
            color: #00e5ff; /* Neon blue color for emphasis */
        }

        .team-member p, .service-item p {
            font-size: 16px;
            color: #ccc;
        }

        button {
            background-color: #00e5ff;
            color: white;
            padding: 15px 30px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 20px;
            transition: background-color 0.3s ease, transform 0.3s ease;
        }

        button:hover {
            background-color: #009ee3;
            transform: scale(1.05);
        }

        form {
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        label, input, textarea {
            margin: 10px 0;
            padding: 12px;
            font-size: 16px;
            border: 1px solid #333;
            border-radius: 5px;
            width: 100%;
            max-width: 400px;
            background-color: #222;
            color: #fff;
        }

        input[type="submit"] {
            background-color: #00e5ff;
            color: white;
            cursor: pointer;
            font-weight: bold;
        }

        input[type="submit"]:hover {
            background-color: #009ee3;
        }

        footer {
            background-color: #111;
            color: white;
            text-align: center;
            padding: 20px 0;
            margin-top: 40px;
        }

        .social-links a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-size: 18px;
        }

        .social-links a:hover {
            text-decoration: underline;
        }

        /* Animation for smooth scroll */
        html {
            scroll-behavior: smooth;
        }
    </style>
    <!-- Google font for modern look -->
    <link href="https://fonts.googleapis.com/css2?family=Orbitron&display=swap" rel="stylesheet">
</head>
<body>

    <!-- Background Overlay -->
    <div class="background-overlay"></div>

    <!-- Website Header -->
    <header>
        <h1>Avalanche.gg</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About Us</a></li>
                <li><a href="#roster">Our Roster</a></li>
                <li><a href="#events">Upcoming Events</a></li>
                <li><a href="#join">Join Us</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Main Content Section -->
    <main>
        <section id="home">
            <h2>Welcome to Avalanche.gg!</h2>
            <p>Your one-stop destination for all things Valorant. Join the best community, check out our roster, and participate in exclusive events!</p>
        </section>

        <section id="about">
            <h2>About Avalanche.gg</h2>
            <p>Avalanche.gg is a passionate Valorant community and esports organization dedicated to supporting players, hosting events, and showcasing talent from around the world. Whether you're a casual player or a competitive gamer, Avalanche is the place to be!</p>
        </section>

        <section id="roster">
            <h2>Meet Our Roster</h2>
            <!-- Updated to show 7 team members as "Player 1", "Player 2", etc. -->
            <div class="team-member">
                <h3>Player 1</h3>
                <p>Team Captain</p>
            </div>
            <div class="team-member">
                <h3>Player 2</h3>
                <p>Lead Strategist</p>
            </div>
            <div class="team-member">
                <h3>Player 3</h3>
                <p>Sharpshooter</p>
            </div>
            <div class="team-member">
                <h3>Player 4</h3>
                <p>Assault Specialist</p>
            </div>
            <div class="team-member">
                <h3>Player 5</h3>
                <p>Support Player</p>
            </div>
            <div class="team-member">
                <h3>Player 6</h3>
                <p>Recon Specialist</p>
            </div>
            <div class="team-member">
                <h3>Player 7</h3>
                <p>Fragger</p>
            </div>
        </section>

        <section id="events">
            <h2>Upcoming Events</h2>
            <div class="service-item">
                <h3>Valorant Tournament - 2025</h3>
                <p>Join us for the biggest Valorant tournament of the year, featuring top-tier teams and exciting gameplay!</p>
            </div>
            <div class="service-item">
                <h3>Community Night - January 2025</h3>
                <p>Get ready for a fun-filled community night with custom games and giveaways. Bring your friends!</p>
            </div>
        </section>

        <section id="join">
            <h2>Join the Avalanche.gg Discord server</h2>
            <p>We're always looking for passionate Valorant players to join our roster. Whether you're a seasoned pro or a rising star, we want to hear from you!</p>
            <button onclick="window.location.href='https://discord.gg/BMJPYzqF'">Apply Now</button>
        </section>

        <section id="contact">
            <h2>Contact Us</h2>
            <p>If you have any questions or want to get in touch, feel free to contact us.</p>
            <form action="#" method="post">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>
                
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>
                
                <label for="message">Message:</label>
                <textarea id="message" name="message" rows="4" required></textarea>
                
                <input type="submit" value="Send">
            </form>
        </section>
    </main>

    <!-- Footer Section -->
    <footer>
        <p>&copy; 2025 Avalanche.gg | All rights reserved</p>
        <div class="social-links">
            <a href="https://www.tiktok.com/@avalancheggofficial" target="_blank">Tiktok</a>
            <a href="https://x.com/avalancheggoff" target="_blank">Twitter</a>
            <a href="https://www.instagram.com/avalanche.ggofficial?igsh=ZjM3YjE4cnhjYzVu" target="_blank">Instagram</a>
        </div>
    </footer>

</body>
</html>