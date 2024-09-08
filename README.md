<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Modern Interior Design Portfolio</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        /* CSS styles embedded for convenience */
        body {
            margin: 0;
            font-family: 'Arial', sans-serif;
            color: #333;
            background-color: #f5f5f5;
        }
        header {
            background-color: #000;
            color: #fff;
            padding: 15px 20px;
            position: fixed;
            width: 100%;
            top: 0;
            left: 0;
            z-index: 1000;
            display: flex;
            align-items: center;
            justify-content: space-between;
        }
        .logo {
            font-size: 1.5rem;
            font-weight: bold;
        }
        nav ul {
            list-style: none;
            margin: 0;
            padding: 0;
            display: flex;
        }
        nav ul li {
            margin: 0 15px;
        }
        nav ul li a {
            color: #fff;
            text-decoration: none;
            font-size: 1rem;
        }
        .hero {
            background: url('https://via.placeholder.com/1920x1080') no-repeat center center/cover;
            height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            color: #fff;
            text-align: center;
        }
        .hero h1 {
            font-size: 4rem;
            margin: 0;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.7);
        }
        .section {
            padding: 60px 20px;
            text-align: center;
        }
        .section h2 {
            font-size: 2.5rem;
            margin-bottom: 20px;
        }
        .portfolio-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 20px;
        }
        .portfolio-item {
            background: #fff;
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            position: relative;
            cursor: pointer;
            transition: transform 0.3s ease;
        }
        .portfolio-item img {
            width: 100%;
            height: auto;
            display: block;
        }
        .portfolio-item:hover {
            transform: scale(1.05);
        }
        .portfolio-item .info {
            padding: 15px;
            background: rgba(0, 0, 0, 0.6);
            color: #fff;
            position: absolute;
            bottom: 0;
            width: 100%;
            text-align: left;
            display: flex;
            flex-direction: column;
            justify-content: flex-end;
            height: 100%;
            transition: opacity 0.3s ease;
            opacity: 0;
        }
        .portfolio-item:hover .info {
            opacity: 1;
        }
        .info h3 {
            margin: 0;
            font-size: 1.5rem;
        }
        .info p {
            margin: 10px 0;
        }
        footer {
            background-color: #000;
            color: #fff;
            padding: 20px;
            text-align: center;
        }
    </style>
</head>
<body>
    <header>
        <div class="logo">Interior Design Portfolio</div>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#portfolio">Portfolio</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    
    <div id="home" class="hero">
        <h1>Welcome to My Design Portfolio</h1>
    </div>

    <div id="portfolio" class="section">
        <h2>Featured Projects</h2>
        <div class="portfolio-grid">
            <div class="portfolio-item">
                <img src="https://via.placeholder.com/600x400" alt="Project 1">
                <div class="info">
                    <h3>Project 1</h3>
                    <p>Modern living room with elegant finishes.</p>
                </div>
            </div>
            <div class="portfolio-item">
                <img src="https://via.placeholder.com/600x400" alt="Project 2">
                <div class="info">
                    <h3>Project 2</h3>
                    <p>Contemporary office space with clean lines.</p>
                </div>
            </div>
            <div class="portfolio-item">
                <img src="https://via.placeholder.com/600x400" alt="Project 3">
                <div class="info">
                    <h3>Project 3</h3>
                    <p>Luxurious bedroom design with modern aesthetics.</p>
                </div>
            </div>
        </div>
    </div>

    <div id="about" class="section">
        <h2>About Me</h2>
        <p>Welcome to my portfolio. I specialize in creating modern, elegant spaces that reflect contemporary design trends and client preferences.</p>
    </div>

    <div id="contact" class="section">
        <h2>Contact Me</h2>
        <p>If you would like to discuss a project or have any inquiries, feel free to reach out to me.</p>
        <p>Email: <a href="mailto:your-email@example.com">your-email@example.com</a></p>
    </div>

    <footer>
        &copy; 2024 Interior Design Portfolio. All rights reserved.
    </footer>
</body>
</html>
