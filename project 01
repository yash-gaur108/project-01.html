
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Personal Portfolio</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            scroll-behavior: smooth;
        }

        body {
            font-family: Arial, sans-serif;
            background: #f4f4f4;
            color: #333;
        }

        /* HEADER */
        header {
            background: #252525;
            color: white;
            padding: 20px 8%;
            display: flex;
            justify-content: space-between;
            align-items: center;
            position: sticky;
            top: 0;
            z-index: 100;
        }

        .logo h2 {
            font-size: 25px;
        }

        .logo p {
            font-size: 12px;
            color: #ccc;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin-left: 20px;
            font-size: 13px;
            font-weight: bold;
        }

        nav a:hover {
            color: #4285f4;
        }

        /* HOME SECTION */
        .home {
            background: #444;
            color: white;
            min-height: 480px;
            display: flex;
            align-items: center;
            padding: 60px 10%;
            position: relative;
            overflow: hidden;
        }

        .home-content {
            max-width: 600px;
            position: relative;
            z-index: 2;
        }

        .home h1 {
            font-size: 40px;
            margin-bottom: 25px;
        }

        .home p {
            font-size: 18px;
            line-height: 1.7;
            margin-bottom: 25px;
        }

        .home img {
            position: absolute;
            right: 5%;
            bottom: 0;
            width: 42%;
            max-height: 100%;
            object-fit: cover;
            object-position: top;
            opacity: 0.75;
        }

        .btn {
            display: inline-block;
            background: #3478ed;
            color: white;
            padding: 13px 25px;
            text-decoration: none;
            border-radius: 5px;
            margin: 5px;
            transition: 0.3s;
        }

        .btn:hover {
            background: #1555bd;
        }

        /* COMMON SECTION */
        section {
            padding: 70px 10%;
        }

        .section-title {
            text-align: center;
            font-size: 30px;
            margin-bottom: 35px;
        }

        .section-title::after {
            content: "";
            display: block;
            width: 55px;
            height: 3px;
            background: #3478ed;
            margin: 12px auto;
        }

        /* ABOUT SECTION */
        .about {
            background: white;
            display: flex;
            align-items: center;
            gap: 50px;
        }

        .about img {
            width: 35%;
            max-width: 350px;
            border-radius: 10px;
        }

        .about-content {
            flex: 1;
        }

        .about-content h2 {
            font-size: 30px;
            margin-bottom: 20px;
        }

        .about-content p {
            line-height: 1.8;
            margin-bottom: 15px;
            color: #555;
        }

        /* SKILLS */
        .skills {
            background: #f4f4f4;
        }

        .skill-container {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 20px;
        }

        .skill-box {
            background: white;
            padding: 25px;
            text-align: center;
            border-radius: 8px;
            box-shadow: 0 3px 10px #ddd;
        }

        .skill-box h3 {
            color: #3478ed;
            margin-bottom: 10px;
        }

        /* PROJECTS */
        .projects {
            background: white;
        }

        .project-container {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 25px;
        }

        .project-card {
            background: #f7f7f7;
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 3px 10px #ddd;
        }

        .project-card img {
            width: 100%;
            height: 180px;
            object-fit: cover;
        }

        .project-card div {
            padding: 20px;
        }

        .project-card h3 {
            margin-bottom: 10px;
        }

        .project-card p {
            line-height: 1.6;
            color: #555;
        }

        /* RESUME */
        .resume {
            background: #333;
            color: white;
            text-align: center;
        }

        .resume p {
            margin-bottom: 20px;
            line-height: 1.6;
        }

        /* CONTACT */
        .contact {
            background: #f4f4f4;
            text-align: center;
        }

        .contact p {
            margin: 15px;
            font-size: 17px;
        }

        .contact a {
            color: #3478ed;
            text-decoration: none;
        }

        /* FOOTER */
        footer {
            background: #252525;
            color: white;
            text-align: center;
            padding: 25px;
        }

        /* RESPONSIVE DESIGN */
        @media (max-width: 900px) {
            header {
                flex-direction: column;
                gap: 15px;
            }

            nav {
                display: flex;
                flex-wrap: wrap;
                justify-content: center;
                gap: 12px;
            }

            nav a {
                margin: 0;
            }

            .home img {
                opacity: 0.25;
                width: 70%;
            }

            .about {
                flex-direction: column;
                text-align: center;
            }

            .about img {
                width: 65%;
            }

            .skill-container,
            .project-container {
                grid-template-columns: repeat(2, 1fr);
            }
        }

        @media (max-width: 600px) {
            .home h1 {
                font-size: 30px;
            }

            .home p {
                font-size: 16px;
            }

            .skill-container,
            .project-container {
                grid-template-columns: 1fr;
            }

            section {
                padding: 50px 7%;
            }
        }
    </style>
</head>

<body>

    <!-- HEADER -->
    <header>
        <div class="logo">
            <h2>My Portfolio</h2>
            <p>Personal Website</p>
        </div>

        <nav>
            <a href="#home">HOME</a>
            <a href="#about">ABOUT ME</a>
            <a href="#skills">SKILLS</a>
            <a href="#projects">PROJECTS</a>
            <a href="#resume">RESUME</a>
            <a href="#contact">CONTACT</a>
        </nav>
    </header>

    <!-- HOME SECTION -->
    <section class="home" id="home">

        <div class="home-content">
            <h1>HELLO, I'M YOUR NAME</h1>

            <p>
                Hi, I am a passionate Web Developer and
                Computer Science student. I enjoy creating
                modern, responsive and user-friendly websites
                using HTML, CSS and JavaScript.
            </p>

            <a href="#contact" class="btn">Hire Me</a>
        </div>

        <img src="profile.jpg" alt="My Profile Picture">

    </section>

    <!-- ABOUT SECTION -->
    <section class="about" id="about">

        <img src="profile.jpg" alt="About Me">

        <div class="about-content">
            <h2>ABOUT ME</h2>

            <p>
                I am a dedicated and enthusiastic Computer
                Science student with an interest in web
                development and modern technologies.
            </p>

            <p>
                I have knowledge of HTML, CSS, JavaScript
                and programming fundamentals. I enjoy
                learning new technologies and developing
                creative solutions to real-world problems.
            </p>

            <a href="#resume" class="btn">Download Resume</a>
        </div>

    </section>

    <!-- SKILLS SECTION -->
    <section class="skills" id="skills">

        <h2 class="section-title">MY SKILLS</h2>

        <div class="skill-container">

            <div class="skill-box">
                <h3>HTML</h3>
                <p>Creating structured web pages.</p>
            </div>

            <div class="skill-box">
                <h3>CSS</h3>
                <p>Designing attractive websites.</p>
            </div>

            <div class="skill-box">
                <h3>JavaScript</h3>
                <p>Adding interactive features.</p>
            </div>

            <div class="skill-box">
                <h3>Python</h3>
                <p>Programming and problem solving.</p>
            </div>

            <div class="skill-box">
                <h3>Java</h3>
                <p>Object-oriented programming.</p>
            </div>

            <div class="skill-box">
                <h3>Responsive Design</h3>
                <p>Building mobile-friendly websites.</p>
            </div>

        </div>

    </section>

    <!-- PROJECTS SECTION -->
    <section class="projects" id="projects">

        <h2 class="section-title">MY PROJECTS</h2>

        <div class="project-container">

            <div class="project-card">
                <img src="https://placehold.co/600x350?text=Portfolio+Website"
                     alt="Portfolio Project">

                <div>
                    <h3>Personal Portfolio</h3>
                    <p>
                        A personal website developed using
                        HTML and CSS to showcase my skills,
                        projects and experience.
                    </p>
                </div>
            </div>

            <div class="project-card">
                <img src="https://placehold.co/600x350?text=Ecommerce+Website"
                     alt="Ecommerce Project">

                <div>
                    <h3>E-Commerce Website</h3>
                    <p>
                        An online shopping website where
                        users can explore products and
                        view product details.
                    </p>
                </div>
            </div>

            <div class="project-card">
                <img src="https://placehold.co/600x350?text=Recommendation+System"
                     alt="Recommendation Project">

                <div>
                    <h3>Book Recommendation System</h3>
                    <p>
                        A recommendation system that
                        suggests books based on user
                        interests and preferences.
                    </p>
                </div>
            </div>

        </div>

    </section>

    <!-- RESUME SECTION -->
    <section class="resume" id="resume">

        <h2 class="section-title">MY RESUME</h2>

        <p>
            Interested in knowing more about my education,
            technical skills and experience?
        </p>

        <a href="resume.pdf" download class="btn">
            Download Resume
        </a>

    </section>

    <!-- CONTACT SECTION -->
    <section class="contact" id="contact">

        <h2 class="section-title">CONTACT ME</h2>

        <p>Email:
            <a href="mailto:yourname@gmail.com">
                yourname@gmail.com
            </a>
        </p>

        <p>Phone: +91 9876543210</p>

        <p>Location: India</p>

        <p>
            LinkedIn:
            <a href="https://www.linkedin.com/" target="_blank">
                Visit My Profile
            </a>
        </p>

    </section>

    <!-- FOOTER -->
    <footer>
        <p>
            © 2026 My Personal Portfolio.
            All Rights Reserved.
        </p>
    </footer>

</body>
</html>
