<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <title>Ana Iris - Personal Webpage</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background-color: #ffb3b3;
            padding: 20px;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 2.5em;
            color: #333;
        }
        nav {
            margin: 20px 0;
            text-align: center;
        }
        nav a {
            margin: 0 15px;
            color: #333;
            text-decoration: none;
            font-weight: bold;
        }
        nav a:hover {
            color: #ff6666;
        }
        section {
            padding: 20px;
            max-width: 800px;
            margin: auto;
            background-color: #fff;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        h2 {
            color: #ff6666;
        }
        .skills ul {
            list-style-type: none;
            padding: 0;
        }
        .skills ul li {
            background-color: #ffcccc;
            padding: 10px;
            margin: 5px 0;
            border-radius: 5px;
        }
        footer {
            background-color: #ffb3b3;
            text-align: center;
            padding: 20px;
            margin-top: 20px;
        }
        footer a {
            color: #333;
            text-decoration: none;
            font-weight: bold;
            margin: 0 10px;
        }
        .contact-form {
            margin-top: 20px;
        }
        .contact-form input, .contact-form textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        .contact-form button {
            padding: 10px 20px;
            background-color: #ff6666;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        .contact-form button:hover {
            background-color: #e60000;
        }
    </style>
</head>
<body>

    <header>
        <h1>Ana Iris</h1>
        <nav>
            <a href="#bio">Bio</a>
            <a href="#skills">Skills</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <section id="bio">
        <h2>Bio</h2>
        <p>Hello, I'm Ana Iris! I'm passionate about helping women, particularly those who have struggled with self-esteem issues, to find their purpose in life. My goal is to empower others by reminding them that they are loved and sustained by Jesus, and that they have the strength to keep going no matter what. With a background in therapy and coaching, I work to help people renew their minds and live abundantly by overcoming limiting belief systems.</p>
    </section>

    <section id="skills">
        <h2>Skills</h2>
        <div class="skills">
            <ul>
                <li>Mental Health Counseling</li>
                <li>Life Coaching</li>
                <li>Public Speaking</li>
                <li>Christian Ministry</li>
                <li>Content Creation (Social Media)</li>
            </ul>
        </div>
    </section>

    <section id="contact">
        <h2>Contact</h2>
        <p>You can reach me via social media or send me a message through the form below!</p>
        <footer>
            <a href="https://www.instagram.com/">Instagram</a>
            <a href="https://www.linkedin.com/">LinkedIn</a>
        </footer>

        <div class="contact-form">
            <h2>Get in Touch</h2>
            <form action="https://formspree.io/f/{your-form-id}" method="POST">
                <input type="email" name="email" placeholder="Your Email" required>
                <textarea name="message" rows="4" placeholder="Your Message"></textarea>
                <button type="submit">Send Message</button>
            </form>
        </div>
    </section>

</body>
</html>
