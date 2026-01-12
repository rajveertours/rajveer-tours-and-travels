<!DOCTYPE html>
<!-- saved from url=(0082)file:///C:/Users/acer/Downloads/New%20folder/Rajveer%20Tour's%20and%20Travels.html -->
<html lang="en"><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
    
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rajveer Tour's and Travels</title>
    <style>
        /* General Styles */
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.6;
            color: #333;
        }

        /* Header & Navigation */
        header {
            background: #2c3e50;
            color: #fff;
            padding: 1rem 5%;
            display: flex;
            justify-content: space-between;
            align-items: center;
            position: sticky;
            top: 0;
            z-index: 1000;
        }

        .logo {
            font-size: 1.5rem;
            font-weight: bold;
            color: #f1c40f;
        }

        nav a {
            color: #fff;
            text-decoration: none;
            margin-left: 20px;
            font-weight: 500;
        }

        /* Hero Section */
        .hero {
            background: #f4f4f4;
            height: 60vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            padding: 0 20px;
            /* Placeholder for Hero Image background */
            background-image: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)), url('hero-bg.jpg');
            background-size: cover;
            background-position: center;
            color: white;
        }

        /* Image Containers */
        .image-box {
            width: 100%;
            max-width: 400px;
            height: 250px;
            background: #ddd;
            display: flex;
            align-items: center;
            justify-content: center;
            margin: 10px auto;
            border-radius: 8px;
            overflow: hidden;
        }

        .image-box img {
            width: 100%;
            height: 100%;
            object-fit: cover; /* C:\Users\acer\Downloads\New folder/qaa.jpeg */
        }

        /* Grid Layout for Services */
        .container {
            width: 90%;
            max-width: 1200px;
            margin: 2rem auto;
        }

        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
        }

        .card {
            border: 1px solid #ddd;
            padding: 1.5rem;
            border-radius: 10px;
            text-align: center;
        }

        /* Contact Section */
        .contact-section {
            background: #ecf0f1;
            padding: 3rem 5%;
        }

        .contact-flex {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
            gap: 20px;
        }

        .contact-card {
            background: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
            flex: 1;
            min-width: 280px;
        }

        .contact-card h3 {
            color: #2c3e50;
            border-bottom: 2px solid #f1c40f;
            padding-bottom: 10px;
        }

        footer {
            background: #2c3e50;
            color: white;
            text-align: center;
            padding: 2rem;
            margin-top: 2rem;
        }

        .btn {
            background: #f1c40f;
            color: #2c3e50;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
            font-weight: bold;
        }
    </style>
</head>
<body>

    <header>
        <div class="logo">RAJVEER TOUR'S AND TRAVELS</div>
        <nav>
            <a href="file:///C:/Users/acer/Desktop/anand.html#home">Home</a>
            <a href="file:///C:/Users/acer/Desktop/anand.html#services">Services</a>
            <a href="file:///C:/Users/acer/Desktop/anand.html#contact">Contact</a>
        </nav>
    </header>

    <section class="hero" id="home">
        <h1>Explore The World With Us</h1>
        <p>Premium travel services tailored for your comfort.</p>
        <br>
        <a href="file:///C:/Users/acer/Desktop/anand.html#contact" class="btn">Book Now</a>
    </section>

    <section class="container" id="services">
        <h2 style="text-align: center;">Our Services</h2>
        <div class="grid">
            <div class="card">
                <div class="image-box">
                    <img src="./Rajveer Tour&#39;s and Travels_files/55.jpeg" alt="Luxury Car Rental">
                </div>
                <h3>Luxury Car Rentals</h3>
                <p>Top-tier vehicles for your business or leisure trips.</p>
            </div>
            <div class="card">
                <div class="image-box">
                    <img src="./Rajveer Tour&#39;s and Travels_files/qaa.jpeg" alt="Tour Packages">

                </div>
                <h3>Holiday Packages</h3>
                <p>Customized tour packages across the country.</p>
            </div>
        </div>
    </section>

    <section class="contact-section" id="contact">
        <h2 style="text-align: center;">Contact Our Experts</h2>
        <div class="contact-flex">
            
            <div class="contact-card">
                <h3>BHIKHUBHA SODHA</h3>
                <p>📞 9664782852</p>
                <p>📞 9586574902</p>
            </div>

            <div class="contact-card">
                <h3>NARPALSINH JADEJA</h3>
                <p>📞 9687213791</p>
                <p>📞 9723697117</p>
                <p>✉️ <a href="mailto:Narpalsinhjadeja86@gmail.com">Narpalsinhjadeja86@gmail.com</a></p>
            </div>

        </div>
    </section>

    <footer>
        <p>© 2024 Rajveer Tour's and Travels. All rights reserved.</p>
    </footer>


</body></html>
