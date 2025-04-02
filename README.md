body {
    font-family: Arial, sans-serif;
    background-color: #001f3d; /* Darker background */
    margin: 0;
    padding: 0;
    color: #f0f0f0; /* Light gray text for contrast */
    scroll-behavior: smooth;
    position: relative;
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
    position: relative; /* For watermark positioning */
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

/* White watermark styling */
.container::after {
    content: "Preggie Govender"; /* Text for watermark */
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%); /* Center the watermark */
    font-size: 6rem; /* Adjust size to your preference */
    color: rgba(255, 255, 255, 0.1); /* White with transparency for subtle watermark effect */
    z-index: -1; /* Ensure watermark is behind the content */
    font-weight: bold;
    text-transform: uppercase;
}
