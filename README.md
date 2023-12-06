<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>1st Grade Music Classroom</title>
    <link href="https://fonts.googleapis.com/css2?family=Fredoka+One&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Fredoka One', cursive;
            margin: 0;
            padding: 0;
            color: #333;
            background-color: #ffcb05; /* Updated background color */
        }

        header {
            background-color: #ff6f61;
            color: #fff;
            padding: 20px;
            text-align: center;
            border-radius: 10px 10px 0 0;
        }

        nav {
            background-color: #ffcb05;
            color: #333;
            text-align: center;
            padding: 10px;
            border-radius: 0 0 10px 10px;
        }

        section {
            padding: 20px;
            background-color: #ffcb05; /* Updated background color */
            margin: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        form {
            margin-top: 20px;
        }

        input,
        textarea {
            width: 100%;
            padding: 10px;
            margin-bottom: 10px;
            border: 1px solid #ff6f61;
            border-radius: 4px;
            box-sizing: border-box;
        }

        footer {
            background-color: #ffcb05;
            color: #333;
            text-align: center;
            padding: 10px;
            border-radius: 0 0 10px 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>

<body>
    <header>
        <h1>1st Grade Music Classroom</h1>
    </header>

    <nav>
        <ul>
            <li><a href="#communication">Communication</a></li>
            <li><a href="#community-engagement">Community Engagement</a></li>
            <li><a href="#links-navigation">Links and Navigation</a></li>
            <li><a href="#visual-elements">Visual Elements</a></li>
        </ul>
    </nav>

    <section id="communication">
        <h2>Communication Section</h2>
        <p>Dedicated section on the website for communication. Easily accessible means of messaging me.</p>
        <form>
            <label for="contactMessage">Message Me:</label>
            <textarea id="contactMessage" name="contactMessage" rows="4" placeholder="Type your message here..."></textarea>
            <br>
            <label for="contactEmail">Your Email:</label>
            <input type="email" id="contactEmail" name="contactEmail" placeholder="YourEmail@example.com">
        </form>
    </section>

    <section id="community-engagement">
        <h2>Community Engagement</h2>
        <p>Designated section for community engagement. "Meet the Teacher" events, monthly/bi-monthly meetings, family engagement activities.</p>
        <!-- Add your community engagement elements here -->
    </section>

    <section id="links-navigation">
        <h2>Links and Navigation</h2>
        <p>Newsletters, Updates, online resources.</p>
        <!-- Add your links and navigation elements here -->
    </section>

    <section id="visual-elements">
        <h2>Visual Elements</h2>
        <p>Pictures of the classroom, artwork, events, classroom music video, music and art performances.</p>
        <form>
            <label for="classroomPhotos">Upload Classroom Photos:</label>
            <input type="file" id="classroomPhotos" name="classroomPhotos" accept="image/*" multiple>
        </form>
    </section>

    <footer>
        <p>&copy; 2023 1st Grade Music Classroom</p>
    </footer>
</body>

</html>
