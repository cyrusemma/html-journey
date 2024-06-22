# html-journey
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Personal Page</title>
    <style>
        /* Basic CSS for better visuals */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
        }
        .container {
            padding: 20px;
            max-width: 800px;
            margin: auto;
            background-color: white;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .section {
            margin-bottom: 20px;
        }
        h3 {
            color: #333;
        }
        img {
            max-width: 100%;
            height: auto;
        }
        button {
            background-color: #4CAF50;
            color: white;
            padding: 10px 20px;
            border: none;
            cursor: pointer;
            margin-top: 10px;
        }
        button:hover {
            background-color: #45a049;
        }
        hr {
            margin-top: 20px;
            border: none;
            border-top: 2px solid #ccc;
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- Welcome Section -->
        <div class="section">
            <h3>WELCOME</h3>
            <p>TO MY PERSONAL PAGE</p>
            <button onclick="alert('Thank you for visiting!')">Click Here</button>
            <img src="./output/images/cyrus_photography_sign.jpg" alt="Cyrus himself">
        </div>

        <!-- Photography Section -->
        <div class="section">
            <h3>MY PHOTOGRAPHY JOURNEY</h3>
            <p>Welcome to my photography gallery. I have a passion for capturing moments that tell a story. Here is my photography signature:</p>
            <img src="./output/images/cyrus_photography_sign.jpg" alt="This is me again">
            <h3>GALLERY UPDATES</h3>
            <p>Stay tuned for more photos and updates. I regularly add new content to my gallery.</p>
            <button onclick="alert('More content coming soon!')">Tap Here</button>
        </div>

        <!-- Interactive Section -->
        <div class="section">
            <h3>EXPLORING NEW HORIZONS</h3>
            <p>Join me on my adventures as I explore new places and experiences. Here are some recent highlights:</p>
            <button onclick="alert('Explore more adventures!')">Explore</button>
            <h3>CONNECT WITH ME</h3>
            <p>Feel free to reach out for collaborations or just to say hello. I’d love to connect with fellow enthusiasts.</p>
            <button onclick="alert('Let’s connect!')">Connect</button>
            <h3>FOLLOW MY JOURNEY</h3>
            <p>Follow me on social media for the latest updates and behind-the-scenes content.</p>
            <button onclick="alert('Thanks for following!')">Follow</button>
            <h3>START A NEW CHAPTER</h3>
            <p>Every day is a new opportunity to start something amazing. Begin your journey today.</p>
            <button onclick="alert('Begin your new chapter!')">Start</button>
        </div>

        <!-- Additional Image -->
        <div class="section">
            <img src="./output/images/IMG-20240310-WA0100.jpg" alt="That's me">
            <p>Here’s a snapshot from my recent travels. Adventure awaits!</p>
        </div>

        <!-- Inspirational Quote Section -->
        <div class="section">
            <h2>FIND YOUR FIRE</h2>
            <p>“The only way to do great work is to love what you do.” – Steve Jobs</p>
        </div>

        <!-- Numbered List Section -->
        <div class="section">
            <h3>GOALS AND ACHIEVEMENTS</h3>
            <ul>
                <li>Completed my first marathon – <strong>2023</strong></li>
                <li>Published a photo book – <strong>2022</strong></li>
                <li>Graduated with honors – <strong>2021</strong></li>
                <li>Started my personal blog – <strong>2020</strong></li>
            </ul>
        </div>

        <!-- Footer -->
        <div>
            <hr>
            <p><b>gAT</b> back line</p>
        </div>
    </div>
</body>
</html>
