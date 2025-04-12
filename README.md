<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Freelance Academy | Freelance Training</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        /* Custom Blue & White Theme */
        :root {
            --primary-blue: #1a4a72;
            --secondary-blue: #3498db;
            --white: #ffffff;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Arial', sans-serif;
        }

        body {
            line-height: 1.6;
            background-color: var(--white);
        }

        header {
            background: var(--primary-blue);
            color: var(--white);
            padding: 1.5rem;
            text-align: center;
        }

        nav {
            background: var(--secondary-blue);
            padding: 1rem;
            text-align: center;
        }

        nav a {
            color: var(--white);
            text-decoration: none;
            margin: 0 20px;
            font-weight: bold;
            transition: opacity 0.3s;
        }

        nav a:hover {
            opacity: 0.8;
        }

        .hero {
            background: linear-gradient(rgba(26, 74, 114, 0.8), rgba(26, 74, 114, 0.8)),
                        url('https://images.unsplash.com/photo-1454165804606-c3d57bc86b40?ixlib=rb-1.2.1&auto=format&fit=crop&w=1950&q=80');
            background-size: cover;
            height: 500px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: var(--white);
            text-align: center;
        }

        .hero h2 {
            font-size: 2.5rem;
            margin-bottom: 1rem;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 3rem 1rem;
        }

        .courses, .about, .contact {
            padding: 3rem 0;
        }

        .course-card {
            background: var(--white);
            border: 1px solid #e0e0e0;
            padding: 1.5rem;
            margin: 1.5rem 0;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }

        .course-card h3 {
            color: var(--primary-blue);
        }

        footer {
            background: var(--primary-blue);
            color: var(--white);
            text-align: center;
            padding: 2rem;
        }

        .contact-form {
            max-width: 600px;
            margin: 0 auto;
        }

        input, textarea {
            width: 100%;
            padding: 0.8rem;
            margin: 0.8rem 0;
            border: 1px solid #ddd;
            border-radius: 4px;
        }

        button {
            background: var(--secondary-blue);
            color: var(--white);
            border: none;
            padding: 1rem 2rem;
            border-radius: 4px;
            cursor: pointer;
            font-size: 1rem;
            transition: background 0.3s;
        }

        button:hover {
            background: var(--primary-blue);
        }

        .social-icons {
            margin-top: 1rem;
        }

        .social-icons a {
            color: var(--white);
            margin: 0 10px;
            font-size: 1.5rem;
        }

        @media (max-width: 768px) {
            nav a {
                display: block;
                margin: 10px 0;
            }

            .hero h2 {
                font-size: 2rem;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>SkillBridge Academy</h1>
        <p>Master Freelance Skills, Build Your Future</p>
    </header>

    <nav>
        <a href="#home">Home</a>
        <a href="#courses">Courses</a>
        <a href="#about">About</a>
        <a href="#contact">Contact</a>
    </nav>

    <div class="hero">
        <div class="hero-content">
            <h2>Launch Your Freelance Career</h2>
            <p>Learn in-demand skills from industry experts</p>
        </div>
    </div>

    <div class="container">
        <section id="about" class="about">
            <h2>About SkillBridge Academy</h2>
            <p>We empower aspiring freelancers with practical skills in content writing, graphic design, web development, and digital marketing. Our courses are designed by top freelancers with 10+ years of experience.</p>
        </section>

        <section id="courses" class="courses">
            <h2>Popular Courses</h2>
            <div class="course-card">
                <h3>🚀 Freelance Writing Mastery</h3>
                <p>Learn SEO writing, client pitching, and content strategy. Duration: 8 weeks | Price: $299</p>
            </div>
            <div class="course-card">
                <h3>🎨 Graphic Design Pro</h3>
                <p>Master Adobe tools and build a standout portfolio. Duration: 12 weeks | Price: $499</p>
            </div>
            <div class="course-card">
                <h3>💻 Web Development Bootcamp</h3>
                <p>HTML/CSS, JavaScript, and freelance project management. Duration: 10 weeks | Price: $599</p>
            </div>
        </section>

        <section id="contact" class="contact">
            <h2>Get Started Today</h2>
            <div class="contact-form">
                <form action="https://formspree.io/f/YOUR_FORMSPREE_ID" method="POST">
                    <input type="text" name="name" placeholder="Your Name" required>
                    <input type="email" name="email" placeholder="Your Email" required>
                    <textarea name="message" placeholder="Your Career Goals" rows="5" required></textarea>
                    <button type="submit">Send Application</button>
                </form>
            </div>
        </section>
    </div>

    <footer>
        <p>© 2023 SkillBridge Academy. All rights reserved.</p>
        <p>📧 contact@skillbridgeacademy.com | 📍 123 Freelance Street, Digital City</p>
        <div class="social-icons">
            <a href="#"><i class="fab fa-facebook"></i></a>
            <a href="#"><i class="fab fa-twitter"></i></a>
            <a href="#"><i class="fab fa-linkedin"></i></a>
        </div>
    </footer>
</body>
</html>
