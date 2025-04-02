<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Preggie Govender - Digital Business Card</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #001f3d; /* Darker background */
            margin: 0;
            padding: 0;
            color: #f0f0f0; /* Light gray text for contrast */
            scroll-behavior: smooth;
        }
        .container {
            width: 90%;
            max-width: 950px;
            margin: 30px auto;
            background: #002b53; /* Dark blue for main container */
            padding: 30px;
            box-shadow: 0px 0px 15px rgba(0, 0, 0, 0.3); /* Darker shadow for depth */
            border-radius: 8px;
            text-align: center;
        }
        h1, h2 {
            color: #e0e0e0; /* Very light gray for headings */
        }
        p {
            color: #dcdcdc; /* Lighter gray text for general content */
        }
        .contact-info {
            background: #004785; /* Dark blue for contact info section */
            color: #ffffff; /* White text */
            padding: 15px;
            border-radius: 5px;
            margin-bottom: 20px;
        }
        .contact-info a {
            color: #ffffff; /* White text links */
            text-decoration: none;
            font-weight: bold;
        }
        .section {
            text-align: left;
            margin-bottom: 20px;
            padding: 15px;
            background: #003b5c; /* Darker blue background for sections */
            border-radius: 5px;
        }

        /* Flexbox for services */
        .services-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
            gap: 20px; /* Space between items */
        }

        .service-item {
            flex: 1;
            background: #004785;
            padding: 20px;
            border-radius: 5px;
            color: #ffffff;
            box-sizing: border-box;
            min-width: 280px; /* Ensures that each item has a minimum width */
        }

        .button {
            display: inline-block;
            padding: 10px 20px;
            background-color: #006b97; /* Rich dark blue button */
            color: #ffffff; /* White text */
            border-radius: 5px;
            text-decoration: none;
            margin-top: 10px;
        }
        .button:hover {
            background-color: #005f87; /* Slightly darker blue on hover */
        }
        .meeting-form {
            background: #004785; /* Dark blue background for form */
            padding: 15px;
            border-radius: 5px;
        }
        input, textarea {
            width: 100%;
            padding: 8px;
            margin: 5px 0;
            border: 1px solid #004785; /* Dark blue borders for inputs */
            border-radius: 4px;
            background: #003e58; /* Dark background for inputs */
            color: #f0f0f0; /* Light gray text in inputs */
        }
        button {
            background: #006b97; /* Dark blue button */
            color: white;
            padding: 10px;
            border: none;
            cursor: pointer;
            width: 100%;
            border-radius: 4px;
        }
        button:hover {
            background: #005f87; /* Slightly darker blue on hover */
        }

        /* Smooth scrolling effect */
        html {
            scroll-behavior: smooth;
        }
        .site-map {
            background: #003b5c; /* Dark blue background for site map */
            color: #ffffff; /* White text */
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
            color: #ffffff; /* White links */
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
</body>
</html>
