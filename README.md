<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Glitch's first public web development project shared on GitHub">
    <meta name="author" content="Glitch">
    <title>Glitch | First Web Project</title>
    <!-- ✨ Perfect Font Combination -->
    <link href="https://fonts.googleapis.com/css2?family=Great+Vibes&family=Playfair+Display:wght@500;600&family=Inter:wght@300;400;500;600&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Inter', sans-serif;
            font-weight: 400;
            min-height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            padding: 3rem 2rem;
            color: #1e293b;
            line-height: 1.8;
            text-align: center;

            background: linear-gradient(rgba(248, 250, 252, 0.92), rgba(224, 231, 255, 0.92)),
                        url('https://www.transparenttextures.com/patterns/cubes.png');
            background-attachment: fixed;
            background-size: 180px 180px;
        }

        .project-card {
            background: rgba(255, 255, 255, 0.96);
            max-width: 720px;
            width: 100%;
            padding: 4rem 3.5rem;
            border-radius: 24px;
            box-shadow: 0 10px 40px rgba(79, 70, 229, 0.15);
            border-top: 4px solid #4f46e5;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            backdrop-filter: blur(6px);
        }

        .project-card:hover {
            transform: translateY(-4px);
            box-shadow: 0 15px 50px rgba(79, 70, 229, 0.2);
        }

        /* ✨ Calligraphy Heading - Perfectly Centered */
        h1 {
            font-family: 'Great Vibes', cursive;
            font-size: 3.5rem;
            color: #4338ca;
            margin-bottom: 0.5rem;
            font-weight: 500;
            letter-spacing: 1px;
            width: 100%;
        }

        /* Subheading - Elegant Serif */
        .intro-lead {
            font-family: 'Playfair Display', serif;
            font-size: 1.3rem;
            color: #334155;
            margin: 0 auto 2rem auto;
            padding-bottom: 1.5rem;
            border-bottom: 1px solid #e2e8f0;
            font-weight: 500;
            max-width: 90%;
        }

        /* Body Text - Clean, Balanced */
        .content-block {
            margin: 0 auto 1.6rem auto;
            font-size: 1.08rem;
            color: #475569;
            max-width: 95%;
        }

        .content-block strong {
            color: #4f46e5;
            font-weight: 600;
        }

        /* Tag - Modern & Bold */
        .tag-container {
            margin-top: 2.8rem;
            width: 100%;
        }

        .challenge-tag {
            font-family: 'Inter', sans-serif;
            display: inline-block;
            padding: 0.9rem 2.2rem;
            background: linear-gradient(90deg, #4f46e5, #7c3aed);
            color: white;
            font-size: 1.05rem;
            font-weight: 600;
            border-radius: 50px;
            box-shadow: 0 4px 15px rgba(79, 70, 229, 0.3);
            letter-spacing: 0.8px;
        }

        /* Footer - Light & Balanced */
        .footer-note {
            margin-top: 2.2rem;
            font-size: 0.92rem;
            color: #94a3b8;
            font-weight: 300;
            width: 100%;
        }

        /* Perfect Mobile Balance */
        @media (max-width: 520px) {
            body {
                padding: 2rem 1.2rem;
            }
            .project-card {
                padding: 2.5rem 1.8rem;
            }
            h1 {
                font-size: 2.6rem;
            }
            .intro-lead {
                font-size: 1.1rem;
            }
            .content-block {
                font-size: 1rem;
                max-width: 100%;
            }
        }
    </style>
</head>
<body>
    <div class="project-card">
        <h1>Hello, I am Glitch</h1>
        
        <p class="intro-lead">Welcome to my first public web development project hosted on GitHub.</p>

        <div class="content-block">
            This repository marks the beginning of my journey into digital skills and software development. I am committed to learning industry standards, following best practices, and building work that is clean, accessible, and reliable.
        </div>

        <div class="content-block">
            I created this project to share my progress, collaborate with the global tech community, and demonstrate my willingness to learn and grow. Every step I take is focused on improving my craft and contributing meaningfully to the projects I join.
        </div>

        <div class="content-block">
            Thank you for reviewing my work. I look forward to building more projects and developing my skills further.
        </div>

        <div class="tag-container">
            <div class="challenge-tag">#ShareMyProject</div>
        </div>

        <div class="footer-note">
            Built with care for the Goodwall Community Challenge
        </div>
    </div>
</body>
</html>
