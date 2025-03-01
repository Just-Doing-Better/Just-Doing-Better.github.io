
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hero Profile</title>
    <style>
        body {
            background-color: #111;
            color: white;
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        .header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px;
            background: black;
        }
        .header h1 {
            color: #a78bfa;
        }
        .container {
            padding: 20px;
        }
        .about-me {
            background: #b5a642;
            padding: 20px;
            display: flex;
            align-items: center;
        }
        .about-me img {
            width: 150px;
            height: 150px;
            border-radius: 10px;
            margin-left: 20px;
        }
        .interests, .thing {
            background: #b5a642;
            padding: 10px;
            margin-top: 20px;
        }
        .footer {
            background: #b5a642;
            padding: 20px;
            margin-top: 20px;
            display: flex;
            justify-content: space-between;
        }
    </style>
</head>
<body>
    <div class="header">
        <h1>JB Hero</h1>
        <div>
            <a href="#">Link to LinkedIn</a> |
            <a href="#">Link to Itch.io</a>
        </div>
    </div>
    <div class="container">
        <div class="about-me">
            <p>I am currently an MSU junior and plan on working in the game industry.</p>
            <img src="profile.jpg" alt="Profile Picture">
        </div>
        <div class="interests">
            <h3>Top 3 Interests</h3>
            <p>Amusement Parks<br>Games<br>Traveling</p>
        </div>
        <div class="thing">
            <h3>Thing</h3>
            <img src="cards.jpg" alt="Cards Collection" width="100%">
        </div>
    </div>
    <div class="footer">
        <div>
            <h3>Contact Info</h3>
            <p>Phone: 248-000-3040</p>
            <p>Email: Jban08@gmail</p>
            <p>Instagram: ???</p>
        </div>
        <div>
            <h3>Links to profiles</h3>
            <p><a href="#">Itch for some games</a></p>
            <p><a href="#">LinkedIn</a></p>
        </div>
    </div>
</body>
</html>

