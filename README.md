<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Preggie Govender - Digital Business Card</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #F4F7FC; /* Light grayish blue background */
            margin: 0;
            padding: 0;
            color: #333; /* Dark text color for better readability */
            scroll-behavior: smooth;
        }
        .container {
            width: 90%;
            max-width: 950px;
            margin: 30px auto;
            background: #FFFFFF; /* White background for main container */
            padding: 30px;
            box-shadow: 0px 0px 15px rgba(0, 0, 0, 0.1); /* Light shadow */
            border-radius: 8px;
            text-align: center;
        }
        h1, h2 {
            color: #007BFF; /* Blue for headings */
        }
        p {
            color: #555; /* Darker gray for text */
        }
        .contact-info {
            background: #E9F3FE; /* Light blue background for contact info */
            color: #007BFF; /* Blue text */
            padding: 15px;
            border-radius: 5px;
            margin-bottom: 20px;
        }
        .contact-info a {
            color: #007BFF; /* Blue links */
            text-decoration: none;
            font-weight: bold;
        }
        .section {
            text-align: left;
            margin-bottom: 20px;
            padding: 15px;
            background: #F1F8FF; /* Very light blue background */
            border-radius: 5px;
        }
        .button {
            display: inline-block;
            padding: 10px 20px;
            background-color: #007BFF; /* Blue button background */
            color: #fff;
            border-radius: 5px;
            text-decoration: none;
            margin-top: 10px;
        }
        .button:hover {
            background-color: #0056b3; /* Darker blue on hover */
        }
        .meeting-form {
            background: #E9F3FE; /* Light blue background for form */
            padding: 15px;
            border-radius: 5px;
        }
        input, textarea {
            width: 100%;
            padding: 8px;
            margin: 5px 0;
            border: 1px solid #007BFF; /* Blue border for inputs */
            border-radius: 4px;
            background: #FFFFFF; /* White background for input fields */
            color: #333; /* Dark text for readability */
        }
        button {
            background: #007BFF; /* Blue button */
            color: white;
            padding: 10px;
            border: none;
            cursor: pointer;
            width: 100%;
            border-radius: 4px;
        }
        button:hover {
            background: #0056b3; /* Darker blue on hover */
        }

        /* Smooth scrolling effect */
        html {
            scroll-behavior: smooth;
        }
        .site-map {
            background: #E9F3FE; /* Light blue background for site map */
            color: #007BFF; /* Blue text */
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
            color: #007BFF; /* Blue link color */
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

        <div class="section" id="loans">
            <h2>Loans & Short-Term Funding</h2>
            <p>We offer short-term funding and bridging finance solutions to help you bridge the gap when it’s needed most. Whether you're dealing with cash flow challenges or need a temporary solution to cover costs, we're here to support your business in growing and thriving.</p>
        </div>

        <div class="section" id="stepchain">
            <h2>StepChain</h2>
            <p>Monetize your steps! With StepChain, get paid for walking and playing brain games. It's not only an opportunity to earn passive income but also a way to improve your mental and physical health. Start moving today and make every step count!</p>
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

        <div class="section" id="property">
            <h2>Property: Sales Manager</h2>
            <p>I specialize in sales and rentals, helping clients buy, sell, and rent properties. My experience ensures that your property needs are met with expertise and care, whether you’re looking to purchase your dream home or rent a space that suits your lifestyle.</p>
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
            <a href="#loans">Loans & Short-Term Funding</a>
            <a href="#stepchain">StepChain</a>
            <a href="#property">Property: Sales Manager</a>
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
