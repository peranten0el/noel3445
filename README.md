!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Sunnydale School</title>
    <style>
        /* Center the entire content */
        body {
            font-family: 'Arial', sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            flex-direction: column;
            background-color: skyblue;
            padding: 20px;
        }

        /* Style the main title */
        h1 {
            font-size: 24px;
            font-weight: bold;
            color: #1E90FF;
            text-align: center;
        }

        /* Section heading styles */
        h2 {
            font-weight: bold;
        }

        h2#mission {
            color: #32CD32; /* Green */
        }

        h2#upcoming-events {
            color: #FFA07A; /* Light Salmon */
            background-color: skyblue; #FFFFE0; /* Light Yellow background */
            padding: 5px;
        }

        h2#contact {
            color: #20B2AA; /* Light Sea Green */
        }

        /* Style for outdoor events */
        .outdoor {
            background-color: #AFEEEE;
            padding: 5px;
            border: 1px solid #B0E0E6;
        }

        /* Style the contact section */
        .section {
            background-color: skyblue;
            padding: 10px;
            margin-top: 10px;
            width: 300px;
        }

        ul {
            padding-left: 20px;
        }

        li {
            margin-bottom: 5px;
        }
    </style>
</head>
<body>

    <h1>Welcome to Sunnydale School</h1>

    <h2 id="mission">Mission Statement</h2>
    <p>Our mission is to provide a nurturing and inclusive learning environment that empowers students to reach their full potential.</p>

    <h2 id="upcoming-events">Upcoming Events</h2>
    <ul>
        <li data-event-type="indoor" title="Event Type: Indoor">Science Fair - <span style="font-weight: bold; color: red;">June 10</span></li>
        <li class="outdoor" data-event-type="outdoor" title="Event Type: Outdoor">Art Exhibition - <span style="font-weight: bold; color: red;">June 15</span></li>
        <li class="outdoor" data-event-type="outdoor" title="Event Type: Outdoor">Sports Day - <span style="font-weight: bold; color: red;">June 20</span></li>
    </ul>

    <h2 id="contact">Contact Us</h2>
    <div class="section">
        <p>Email: <a href="mailto:info@sunnydaleschool.edu" title="Click to copy email">info@sunnydaleschool.edu</a></p>
        <p>Phone: <a href="tel:+1234567890" title="Click to copy phone number">09262304850</a></p>
        <!-- Imagine clicking here shows a message: 'Thanks for reaching out!' -->
    </div>

    <hr style="width: 100%; margin: 20px 0;">

    <h2>Design Refinement Suggestions</h2>
    <ul>
        <li><strong>Refine the Color Palette:</strong> Switch to a harmonious set of complementary or muted tones to reduce visual overload.</li>
        <li><strong>Background and Font Colors:</strong> Replace bright colors with softer shades to enhance readability and maintain a professional tone.</li>
        <li><strong>Consistency in Headings:</strong> Use a single color for all section headings and vary font style or weight to distinguish them, improving coherence.</li>
    </ul>

</body>
</html>
