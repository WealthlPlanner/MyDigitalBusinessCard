<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Preggie Govender - Digital Business Card</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            color: #f0f0f0;
            display: flex;
            height: 100vh;
            overflow: hidden;
        }

        /* Slow Motion Fade-in Animation */
        @keyframes slowFadeIn {
            0% {
                opacity: 0;
                transform: translateY(50px);
            }
            100% {
                opacity: 1;
                transform: translateY(0);
            }
        }

        /* Apply the animation to the entire container */
        .container {
            animation: slowFadeIn 3s ease-in-out; /* Slow fade-in over 3 seconds */
        }

        .left-side {
            background-color: #000000;
            flex: 1;
            color: white;
            padding: 20px;
            display: flex;
            justify-content: center;
            align-items: center;
            flex-direction: column;
        }

        .right-side {
            background-color: #001f3d;
            flex: 1;
            color: white;
            padding: 20px;
        }

        .contact-info {
            background: #004785;
            color: #ffffff;
            padding: 15px;
            border-radius: 5px;
            margin-bottom: 20px;
            animation: slowFadeIn 4s ease-in-out; /* Slow fade-in for contact info */
        }

        .service-item {
            animation: slowFadeIn 5s ease-in-out; /* Slow fade-in for services */
            background: #004785;
            padding: 20px;
            border-radius: 5px;
            color: #ffffff;
            box-sizing: border-box;
            min-width: 280px;
        }

        /* Flexbox for services */
        .services-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
            gap: 20px;
        }

        /* Smooth scrolling */
        html {
            scroll-behavior: smooth; /* Standard smooth scrolling */
        }

        /* Site map and footer animations */
        .site-map {
            background: #003b5c;
            color: #ffffff;
            padding: 20px;
            border-radius: 5px;
            margin-top: 30px;
            text-align: center;
            animation: slowFadeIn 6s ease-in-out infinite;
        }

        footer {
            animation: slowFadeIn 7s ease-in-out infinite; /* Slow fade-in for footer */
        }

        /* General link styling */
        a {
            color: #fff;
            text-decoration: none;
            margin: 0 15px;
            transition: color 0.3s;
        }

        a:hover {
            color: #ffcc00; /* Hover effect */
        }

        .button {
            padding: 10px 20px;
            background-color: #004785;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            display: inline-block;
            transition: background-color 0.3s;
        }

        .button:hover {
            background-color: #ffcc00;
        }
    </style>
</head>
<body>
    <div class="left-side">
        <!-- Left side content goes here -->
        <h1>Preggie Govender</h1>
        <h2>Chief Inspiration Officer</h2>
    </div>

    <div class="right-side">
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
                <div class="services-container">
                    <div class="service-item">
                        <h3>Sales Coaching</h3>
                        <p>We offer personalized coaching for sales teams to improve their skills, performance, and mindset for long-term growth.</p>
                    </div>
                    <div class="service-item">
                        <h3>Business Growth Planning</h3>
                        <p>We help you map out a plan for sustainable growth, covering everything from funding to scaling without disrupting operations.</p>
                    </div>
                    <div class="service-item">
                        <h3>Leadership Development</h3>
                        <p>We focus on developing strong leadership within organizations to drive success and foster a positive company culture.</p>
                    </div>
                    <div class="service-item">
                        <h3>StepChain</h3>
                        <p>Monetize your steps. Get paid for walking and playing brain games. Improve your mental and physical health.</p>
                    </div>
                </div>
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
    </div>
</body>
</html>
