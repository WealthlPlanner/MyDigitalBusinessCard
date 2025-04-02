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
            animation: fadeIn 3s ease-in-out;
        }

        /* Split the page into two halves */
        .left-side, .right-side {
            flex: 1;
            color: white;
            padding: 20px;
            animation: fadeInUp 4s ease-in-out;
        }

        .left-side {
            background-color: #000000; /* Black side */
            display: flex;
            justify-content: center;
            align-items: center;
            flex-direction: column;
        }

        .right-side {
            background-color: #001f3d; /* Dark Blue side */
        }

        .container {
            background: #002b53; /* Dark blue for main container */
            padding: 30px;
            box-shadow: 0px 0px 15px rgba(0, 0, 0, 0.3);
            border-radius: 8px;
            text-align: center;
            max-width: 950px;
            margin: 0 auto;
            animation: fadeInUp 4s ease-in-out;
        }

        h1, h2 {
            color: #e0e0e0;
            animation: fadeInUp 4s ease-in-out;
        }

        p {
            color: #dcdcdc;
            animation: fadeInUp 4s ease-in-out;
        }

        .contact-info {
            background: #004785;
            color: #ffffff;
            padding: 15px;
            border-radius: 5px;
            margin-bottom: 20px;
            animation: fadeInUp 4s ease-in-out;
        }

        .contact-info a {
            color: #ffffff;
            text-decoration: none;
            font-weight: bold;
            animation: fadeInUp 4s ease-in-out;
        }

        .section {
            text-align: left;
            margin-bottom: 20px;
            padding: 15px;
            background: #003b5c;
            border-radius: 5px;
            animation: fadeInUp 4s ease-in-out;
        }

        /* Flexbox for services */
        .services-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
            gap: 20px;
            animation: fadeInUp 4s ease-in-out;
        }

        .service-item {
            flex: 1;
            background: #004785;
            padding: 20px;
            border-radius: 5px;
            color: #ffffff;
            box-sizing: border-box;
            min-width: 280px;
            animation: fadeInUp 4s ease-in-out;
        }

        .button {
            display: inline-block;
            padding: 10px 20px;
            background-color: #006b97;
            color: #ffffff;
            border-radius: 5px;
            text-decoration: none;
            margin-top: 10px;
            animation: fadeInUp 4s ease-in-out;
        }

        .button:hover {
            background-color: #005f87;
        }

        .meeting-form {
            background: #004785;
            padding: 15px;
            border-radius: 5px;
            animation: fadeInUp 4s ease-in-out;
        }

        input, textarea {
            width: 100%;
            padding: 8px;
            margin: 5px 0;
            border: 1px solid #004785;
            border-radius: 4px;
            background: #003e58;
            color: #f0f0f0;
            animation: fadeInUp 4s ease-in-out;
        }

        button {
            background: #006b97;
            color: white;
            padding: 10px;
            border: none;
            cursor: pointer;
            width: 100%;
            border-radius: 4px;
            animation: fadeInUp 4s ease-in-out;
        }

        button:hover {
            background: #005f87;
        }

        .site-map {
            background: #003b5c;
            color: #ffffff;
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
            animation: fadeInUp 4s ease-in-out;
        }

        .site-map a {
            color: #ffffff;
            text-decoration: none;
            font-weight: bold;
            display: block;
            margin: 5px 0;
            opacity: 0;
            transform: translateY(20px);
            animation: fadeInUp 6s ease-in-out infinite;
        }

        .site-map a:hover {
            text-decoration: underline;
        }

        @keyframes slowMotion {
            0% {
                opacity: 0;
                transform: translateY(50px);
            }
            50% {
                opacity: 1;
                transform: translateY(0);
            }
            100% {
                opacity: 0;
                transform: translateY(50px);
            }
        }

        @keyframes fadeInUp {
            0% {
                opacity: 0;
                transform: translateY(20px);
            }
            50% {
                opacity: 1;
                transform: translateY(0);
            }
            100% {
                opacity: 0;
                transform: translateY(20px);
            }
        }

        /* Flexbox container for the two new sections */
        .what-i-do-container {
            display: flex;
            justify-content: space-between;
            gap: 20px;
            margin-top: 20px;
        }

        /* Style for individual blocks */
        .block {
            background: #003b5c;
            padding: 20px;
            border-radius: 5px;
            color: #ffffff;
            flex: 1;
            min-width: 45%;
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
            <hr>

            <div class="contact-info" id="contact">
                <p><strong>Contact Me</strong></p>
                <p>Email: <a href="mailto:preggie@preggiegovender.com">preggie@preggiegovender.com</a></p>
                <p>Cell: <a href="tel:+27825511433">082 551 1433</a></p>
            </div>

            <div class="what-i-do-container">
                <!-- What I Do Block -->
                <div class="block" id="what-i-do">
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

                <!-- Sales & Rental Property Block -->
                <div class="block" id="sales-rental-property">
                    <h2>Sales & Rental Property</h2>
                    <p>Offering expert assistance in the sale and rental of residential and commercial properties. Whether buying, selling, or renting, I provide comprehensive guidance to ensure the best possible outcome.</p>
                    <ul>
                        <li>Property Sales</li>
                        <li>Rental Management</li>
                        <li>Property Investment Advice</li>
                        <li>Market Analysis</li>
                    </ul>
                </div>
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
                        <p>We help you map out a plan for sustainable growth, covering short-term loans, long-loans and bridging finance without disrupting operations.</p>
                    </div>
                    <div class="service-item">
                        <h3>Leadership Development</h3>
                        <p>We focus on developing strong leadership within organizations to drive success and foster a positive company culture.</p>
                    </div>
                    <!-- New StepChain service item -->
                    <div class="service-item">
                        <h3>StepChain</h3>
                        <p>Monetize your steps. Get paid for walking and playing brain games. Improve your mental and physical health.</p>
                    </div>
                </div>
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
