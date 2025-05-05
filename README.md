# personal-portfolio-
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>My Portfolio</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            margin: 0;
            font-family: 'Roboto', sans-serif;
            color: #333;
            background-color: #f9f9f9;
        }
        
        header {
            background: linear-gradient(135deg, #4f46e5, #3b82f6);
            color: white;
            padding: 50px 20px;
            text-align: center;
        }
        
        header img {
            border-radius: 50%;
            width: 150px;
            height: 150px;
            object-fit: cover;
            margin-top: 20px;
        }
        
        header h1 {
            font-size: 3em;
            margin: 20px 0 10px;
        }
        
        header p {
            font-size: 1.2em;
            max-width: 600px;
            margin: 0 auto;
        }
        
        section {
            padding: 40px 20px;
            max-width: 1000px;
            margin: auto;
        }
        
        section h2 {
            font-size: 2em;
            color: #4f46e5;
            margin-bottom: 20px;
        }
        
        .about-section {
            display: flex;
            flex-wrap: wrap;
            align-items: center;
            justify-content: center;
            background: white;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
            border-radius: 12px;
            padding: 30px;
        }
        
        .about-photo {
            flex: 1;
            text-align: center;
            padding: 20px;
        }
        
        .about-photo img {
            max-width: 300px;
            width: 100%;
            border-radius: 12px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
        }
        
        .about-text {
            flex: 2;
            padding: 20px;
        }
        
        .about-text p {
            font-size: 1.1em;
            line-height: 1.6;
        }
        
        .skills,
        .projects {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }
        
        .card {
            background: white;
            padding: 20px;
            border-radius: 12px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
        }
        
        footer {
            text-align: center;
            padding: 20px;
            background: #e5e7eb;
            font-size: 0.9em;
        }
        
        @media (max-width: 768px) {
            .about-section {
                flex-direction: column;
            }
        }
    </style>
</head>

<body>

    <header>
        <h1>Hi, I'm sanjana </h1>
        <p>A passionate Web Developer crafting beautiful and functional digital experiences</p>
        <img src="C:\Users\sanja\Downloads\Sanjana.jpeg" alt="Professional Photo">
    </header>

    <section>
        <h2>About Me</h2>
        <div class="about-section">
            <div class="about-photo">
                <img src="C:\Users\sanja\Downloads\Sanjana.jpeg" alt="My Photo">

            </div>
            <div class="about-text">
                <p>
                    Hello! I'm <strong>sanjana</strong>, passionate about creating clean and user-friendly websites. A student Studying Information Science Engineering from Rajarajeswari University and Focusing on building interactive and dynamic
                    web applications. I love turning complex problems into simple, beautiful designs. My mission is to design solutions that not only meet the client's needs but also create meaningful user experiences.
                </p>
            </div>
        </div>
    </section>

    <section>
        <h2>Skills</h2>
        <div class="skills">
            <div class="card">HTML5 & CSS3</div>
            <div class="card">JavaScript / React</div>
            <div class="card">Node.js & Express</div>
            <div class="card">MongoDB & SQL</div>
            <div class="card">Responsive Design</div>
            <div class="card">Git & GitHub</div>
        </div>
    </section>

    <section>
        <h2>Projects</h2>
        <div class="projects">
            <div class="card">
                <h3>Portfolio Website</h3>
                <p>A personal portfolio site showcasing my projects and skills using HTML, CSS, and JavaScript.</p>
            </div>
            <div class="card">
                <h3>E-Commerce App</h3>
                <p>Developed a responsive shopping app with user authentication and a powerful product management system.</p>
            </div>
            <div class="card">
                <h3>Blog Platform</h3>
                <p>Created a dynamic blog platform using MERN stack with markdown editor and image uploads.</p>
            </div>
        </div>
    </section>

    <footer>
        <p>&copy; 2025 sanajana. All rights reserved.</p>
    </footer>

</body>

</html>
