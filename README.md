<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Preggie Govender - Digital Business Card</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #2E2E2E;
            margin: 0;
            padding: 0;
            color: #D3D3D3;
            scroll-behavior: smooth;
        }
        .container {
            width: 90%;
            max-width: 950px;
            margin: 50px auto;
            background: #3A3A3A;
            padding: 50px;
            box-shadow: 0px 0px 10px #555;
            border-radius: 7px;
            text-align: center;
        }
        h1, h2 {
            color: #1E90FF;
        }
        p {
            color: white;
        }
        .contact-info {
            background: #444;
            color: white;
            padding: 15px;
            border-radius: 5px;
            margin-bottom: 20px;
        }
        .contact-info a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }
        .section {
            text-align: left;
            margin-bottom: 20px;
            padding: 15px;
            background: #4A4A4A;
            border-radius: 5px;
        }
        .button {
            display: inline-block;
            padding: 10px 20px;
            background-color: #666;
            color: #fff;
            border-radius: 5px;
            text-decoration: none;
            margin-top: 10px;
        }
        .button:hover {
            background-color: #555;
        }
        .meeting-form {
            background: #4A4A4A;
            padding: 15px;
            border-radius: 5px;
        }
        input, textarea {
            width: 100%;
            padding: 8px;
            margin: 5px 0;
            border: 1px solid #777;
            border-radius: 4px;
            background: #555;
            color: white;
        }
        button {
            background: #666;
            color: white;
            padding: 10px;
            border: none;
            cursor: pointer;
            width: 100%;
            border-radius: 4px;
        }
        button:hover {
            background: #555;
        }
        
        /* Smooth scrolling effect */
        html {
            scroll-behavior: smooth;
        }
        .site-map {
            background: #444;
            color: white;
            padding: 20px;
            border-radius: 5px;
            margin-top: 30px;
            text-align: center;
            animation: slowMotion 6s ease-in-out infinite;
        }
        .site-map h2 {
            margin-bottom: 15px;
            font-size: 22px;
            text-decoration: underline;
        }
        .site-map a {
            color: white;
            text-decoration: none;
            font-weight: bold;
            display: block;
            margin: 5px 0;
        }
        .site-map a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1 id="home">Preggie Govender</h1>
        <h2>Chief Inspiration Officer</h2>
        <hr>

        <div class="contact-info" id="contact">
            <p><strong>Contact Me</strong></p>
            <p>Email: <a href="mailto:preggie@preggiegovender.com">preggie@preggiegovender.com</a></p>
            <p>Cell: <a href="tel:+27825511433">082 551 1433</a></p>
        </div>

        <div class="section" id="services">
            <h2>What We Do</h2>
            <p>If your business is ready to grow, it’s time to forecast. We carefully map out your goals, growth engines, and targets. We give you access to affordable business funding that empowers business owners to prioritize sustainable growth, scale without jeopardizing day-to-day operations, and achieve long-term success.</p>
        </div>

        <div class="section" id="about">
            <h2>What I Do</h2>
            <ul>
                <li>Sales/ Skills Coach</li>
                <li>Mentorship</li>
                <li>Motivational Speaker</li>
                <li>Business Coach</li>
                <li>Life Coach</li>
                <li>Business Restructuring & Planning</li>
            </ul>
        </div>

        <div class="section meeting-form" id="book-meeting">
            <h2>Book a Meeting</h2>
            <form action="mailto:preggie@preggiegovender.com" method="post" enctype="text/plain">
                <label for="name">Name:</label>
                <input type="text" id="name" name="Name" required>

                <label for="surname">Surname:</label>
                <input type="text" id="surname" name="Surname" required>

                <label for="email">Email:</label>
                <input type="email" id="email" name="Email" required>

                <label for="contact">Contact Number:</label>
                <input type="tel" id="contact" name="Contact" required>

                <label for="message">Additional Details (Optional):</label>
                <textarea id="message" name="Message" rows="4"></textarea>

                <button type="submit">Send Meeting Request</button>
            </form>
        </div>

        <div class="linkedin">
            <h2>Connect with Me</h2>
            <p><a href="https://www.linkedin.com/in/preggie-govender-mr-g-30a97040/" target="_blank" class="button">Connect on LinkedIn</a></p>
        </div>

        <div class="site-map">
            <h2>Site Map</h2>
            <a href="#home">Home</a>
            <a href="#contact">Contact</a>
            <a href="#services">What We Do</a>
            <a href="#about">What I Do</a>
            <a href="#book-meeting">Book a Meeting</a>
        </div>

        <footer>
            <p>&copy; 2025 Preggie Govender. All rights reserved.</p>
            <p>Disclaimer: This website is for informational purposes only and does not constitute professional financial or real estate advice.</p>
        </footer>
    </div>
</body>
</html>
