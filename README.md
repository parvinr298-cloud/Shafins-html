<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SideQuest</title>
    <style>
        /* General Reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Arial', sans-serif;
        }

        body {
            background-color: #f5f5f5;
            color: #333;
        }

        .container {
            width: 90%;
            max-width: 1200px;
            margin: 0 auto;
            padding: 40px 0;
        }

        header {
            background: #004080;
            color: white;
            padding: 60px 0;
            text-align: center;
        }

        header h1 {
            font-size: 3em;
            margin-bottom: 10px;
        }

        header p {
            font-size: 1.2em;
        }

        section {
            background: white;
            margin: 20px 0;
            padding: 40px 20px;
            border-radius: 8px;
            box-shadow: 0 4px 10px rgba(0,0,0,0.1);
        }

        h2 {
            color: #004080;
            margin-bottom: 20px;
            opacity: 0;
            transform: translateY(20px);
            animation: fadeInUp 0.8s forwards;
        }

        p {
            line-height: 1.6;
        }

        .button {
            background: #ff6600;
            color: white;
            padding: 15px 30px;
            text-decoration: none;
            display: inline-block;
            border: none;
            border-radius: 5px;
            font-size: 1.2em;
            cursor: pointer;
            transition: background 0.3s;
            text-align: center;
        }

        .button:hover {
            background: #e65c00;
        }

        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 20px 0;
        }

        footer p {
            margin: 5px 0;
        }

        @keyframes fadeInUp {
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        /* Optional: Add image styling inside sections */
        .container img {
            max-width: 100%;
            height: auto;
            display: block;
            margin: 20px auto;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>SideQuest</h1>
            <p>Bridging Education and Opportunity</p>
        </div>
    </header>
    <main>
        <section class="about">
            <div class="container">
                <h2>About SideQuest</h2>
                <p>SideQuest is a student-focused platform that connects young people with part-time jobs, internships, volunteering opportunities, competitions, and skill-building projects. The platform helps students gain real-world experience, develop professional skills, build verified portfolios, and earn income while studying. By bringing opportunities into one accessible ecosystem, SideQuest aims to bridge the gap between education and employability, enabling students to prepare for university and future careers more effectively.</p>
            </div>
        </section>
        <section class="opportunities">
            <div class="container">
                <h2>Opportunities</h2>
                <p>Discover part-time jobs, internships, and volunteer work tailored for students.</p>>
            </div>
        </section>
        <section class="skills">
            <div class="container">
                <h2>Build Your Skills</h2>
                <p>Create verified portfolios, showcase your achievements, and grow your professional network.</p>
            </div>
        </section>
        <section class="cta">
            <div class="container">
                <h2>Ready to Start Your Journey?</h2>
                <a href="#" class="button">Sign Up Now</a>
            </div>
        </section>
    </main>
    <footer>
        <div class="container">
            <p>&copy; 2026 SideQuest. All rights reserved.</p>
            <p>Contact us: info@sidequest.com</p>
        </div>
    </footer>
</body>
</html>
