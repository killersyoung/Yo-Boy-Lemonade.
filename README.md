
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>YO BOY LEMONADE</title>
    <link rel="icon" type="image/png" href="image/13.png">
    <link href="https://fonts.googleapis.com/css2?family=Bebas+Neue&family=Roboto&display=swap" rel="stylesheet">
    <style>
        html {
            scroll-behavior: smooth;
        }
        body {
            margin: 0;
            font-family: 'Roboto', sans-serif;
            background-color: #121212;
            color: #eee;
            line-height: 1.6;
        }
        header {
            background-color: #1e1e1e;
            padding: 1rem 0;
            position: sticky;
            top: 0;
            z-index: 100;
        }
        header .container {
            max-width: 1200px;
            margin: auto;
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 0 20px;
        }
        header h1 {
            font-family: 'Bebas Neue', cursive;
            font-size: 2rem;
            color: #ff7b00;
            margin: 0;
        }
        nav ul {
            list-style: none;
            display: flex;
            padding: 0;
            margin: 0;
        }
        nav ul li {
            margin-left: 20px;
        }
        nav ul li a {
            color: #eee;
            text-decoration: none;
            font-weight: bold;
            transition: color 0.3s;
        }
        nav ul li a:hover {
            color: #ff7b00;
        }
        .hero {
            background: url('image/jj.jpg') no-repeat center/cover;
            height: 500px;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            
        }
        .hero h2 {
            font-size: 2.5rem;
            color: #ff7b00;
        }
        .hero p {
            max-width: 600px;
            margin: 20px auto;
            font-size: 1.1rem;
        }
        .button {
            display: inline-block;
            background-color: #ff7b00;
            color: #121212;
            padding: 10px 20px;
            border-radius: 5px;
            text-decoration: none;
            transition: background 0.3s;
        }
        .button:hover {
            background-color: #e06900;
        }
        section {
            max-width: 1200px;
            margin: auto;
            padding: 3rem 20px;
        }
        .portfolio-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 20px;
        }
        .project {
            background: #1e1e1e;
            padding: 15px;
            border-radius: 8px;
        }
        .project img {
            width: 100%;
            border-radius: 5px;
        }
        .project h3 {
            margin-top: 10px;
            color: #ff7b00;
        }
        
        .about {
    padding: 4rem 0;
}

.about-content {
    display: flex;
    align-items: center;
    gap: 30px;
    max-width: 900px;
    margin: 0 auto;
}

.about-content img {
    width: 200px;
    height: 200px;
    border-radius: 50%;
    object-fit: cover;
}

.about-content p {
    flex-grow: 1;
        }
        form {
            background: #1e1e1e;
            padding: 20px;
            border-radius: 8px;
        }
        input, textarea {
            width: 100%;
            padding: 10px;
            margin-bottom: 15px;
            border-radius: 4px;
            border: none;
        }
        button {
            background: #ff7b00;
            border: none;
            padding: 10px 20px;
            color: #121212;
            cursor: pointer;
            border-radius: 5px;
            font-weight: bold;
        }
        button:hover {
            background: #e06900;
        }
        footer {
            background-color: #1e1e1e;
            text-align: center;
            padding: 1rem 0;
            color: #aaa;
            margin-top: 30px;
        }
    </style>
</head>
<body>

<header>
    <div class="container">
        <h1>YO BOY LEMONADE</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#portfolio">Portfolio</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </div>
</header>

<section id="home" class="hero">
    <h2>Feel the Beat, Live the Music</h2>
    <p>Professional music artist  bringing rhythm, melody, and soul together.
	</p>
    <a href="#portfolio" class="button">Listen Now</a>
</section>

<section id="portfolio">
    <h2>Portfolio</h2>
    <div class="portfolio-grid" width="100%" height="50%">
        <div class="project">
            <img src="image/9.jpg" alt="Song 1" width="100%" height="50%">
            <h3>CINDERELLA by LEMONADE</h3>
            <audio controls>
                <source src="music/CINDERELLA by LEMONADE.mp3" type="audio/mpeg">
            </audio>
        </div>
        <div class="project">
            <img src="image/11.jpg" alt="Song 2" width="100%" height="50%">
            <h3>SORRY LEMONADE mrlemonade2564</h3>
            <audio controls>
                <source src="music/SORRY LEMONADE mrlemonade2564.mp3" type="audio/mpeg">
            </audio>
        </div>
	</div>	
	
	<div class="portfolio-grid" width="100%" height="50%">
        <div class="project">
            <img src="image/6.jpg" alt="Song 1" width="100%" height="50%" >
            <h3>ONDI WALA by YO BOY LEMONADE</h3>
            <audio controls>
                <source src="music/ONDI WALA by YO BOY LEMONADE.mp3" type="audio/mpeg">
            </audio>
        </div>
        <div class="project">
            <img src="image/8.jpg" alt="Song 2" width="100%" height="50%" >
            <h3>WEDDING DAY</h3>
            <audio controls>
                <source src="music/WEDDING DAY.mp3" type="audio/mpeg">
            </audio>
        </div>	
		
    </div>
</section>



<section id="about">
    <div class="container">
        <h2>About Me</h2>
        <div class="about-content">
            <img src="image/1.jpg" >
            <p>Hi, I'm <strong>Yo Boy Lemonade</strong>, a passionate music artist with a love for music that make people move. 
            With over 5 years in the industry, I specialize EDM, working with artists to 
            create unforgettable soundscapes.Music is the drug that makes me high</p>
        </div>
    </div>
</section>

<section id="contact">
    <h2>Contact Me</h2>
    <form action="mailto:youremail@example.com" method="post" enctype="text/plain">
        <input type="text" name="name" placeholder="Your Name" required>
        <input type="email" name="email" placeholder="Your Email" required>
        <textarea name="message" rows="5" placeholder="Your Message" required></textarea>
        <button type="submit">Send</button>
    </form>
</section>

<footer>
    <p>&copy; 2025 YO BOY LEMONADE. All rights reserved.</p>
</footer>

</body>
</html>
