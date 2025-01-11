<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="GitHub Workshop Blog - Learn Git and GitHub">
    <meta name="author" content="Your Name">
    <title>GitHub Workshop Blog</title>
    
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
    
    <!-- Basic Styles -->
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Poppins', sans-serif;
        }
        body {
            background-color: #f4f4f4;
            color: #333;
            padding: 20px;
        }
        header {
            background-color: #24292e;
            color: white;
            padding: 20px 0;
            text-align: center;
            margin-bottom: 20px;
        }
        header h1 {
            font-size: 2.5em;
        }
        nav a {
            margin: 0 15px;
            color: #fff;
            text-decoration: none;
            font-weight: 600;
        }
        section {
            background-color: #fff;
            padding: 20px;
            margin-bottom: 20px;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        h2 {
            color: #0366d6;
            margin-bottom: 10px;
        }
        ul {
            margin-left: 20px;
        }
        footer {
            text-align: center;
            padding: 10px;
            background-color: #24292e;
            color: white;
            margin-top: 20px;
        }
        .btn {
            background-color: #28a745;
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
        }
        .btn:hover {
            background-color: #218838;
        }
        input, textarea {
            width: 100%;
            padding: 10px;
            margin-top: 5px;
            margin-bottom: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
    </style>
</head>

<body>

    <!-- Header Section -->
    <header>
        <h1>GitHub Workshop Blog</h1>
        <nav>
            <a href="#about">About</a>
            <a href="#agenda">Agenda</a>
            <a href="#prerequisites">Prerequisites</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <!-- About Section -->
    <section id="about">
        <h2>About the Workshop</h2>
        <p>Welcome to our hands-on GitHub Workshop! This event is designed for beginners and intermediate developers looking to improve their skills in version control and collaborative development.</p>
        <p>In this workshop, you'll learn how to:</p>
        <ul>
            <li>Understand the basics of Git and GitHub</li>
            <li>Initialize repositories and manage branches</li>
            <li>Collaborate on projects using pull requests</li>
            <li>Deploy projects through GitHub Pages</li>
        </ul>
    </section>

    <!-- Agenda Section -->
    <section id="agenda">
        <h2>Workshop Agenda</h2>
        <ul>
            <li><strong>10:00 AM:</strong> Introduction to Git and GitHub</li>
            <li><strong>11:00 AM:</strong> Hands-on with Repositories and Branches</li>
            <li><strong>12:00 PM:</strong> Lunch Break</li>
            <li><strong>1:00 PM:</strong> Collaboration with Pull Requests</li>
            <li><strong>2:30 PM:</strong> GitHub Pages Deployment</li>
            <li><strong>4:00 PM:</strong> Q&A and Closing Remarks</li>
        </ul>
    </section>

    <!-- Prerequisites Section -->
    <section id="prerequisites">
        <h2>Prerequisites</h2>
        <p>To get the most out of this workshop, please ensure you have the following set up:</p>
        <ul>
            <li>Git installed on your computer: <a href="https://git-scm.com/downloads" target="_blank">Download Git</a></li>
            <li>A GitHub account: <a href="https://github.com/" target="_blank">Sign up here</a></li>
            <li>A code editor (e.g., VS Code): <a href="https://code.visualstudio.com/" target="_blank">Download VS Code</a></li>
        </ul>
    </section>

    <!-- Contact Form Section -->
    <section id="contact">
        <h2>Contact Us</h2>
        <p>Have any questions or suggestions? Reach out to us below:</p>
        <form action="https://example.com/submit" method="POST">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="message">Message:</label>
            <textarea id="message" name="message" rows="5" required></textarea>

            <button type="submit" class="btn">Send Message</button>
        </form>
    </section>

    <!-- Footer Section -->
    <footer>
        <p>&copy; 2024 GitHub Workshop Blog | Designed by Your Name</p>
    </footer>

</body>
</html>
