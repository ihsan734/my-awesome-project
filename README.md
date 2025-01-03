<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Explore The World</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Arial', sans-serif;
            background-color: #f4f4f4;
            color: #333;
            line-height: 1.6;
            margin: 0;
        }

        main {
            width: 80%;
            margin: 20px auto;
            padding: 20px;
            background-color: #ffffff;
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.1);
        }

        h1 {
            text-align: center;
            color: #2c3e50;
            font-size: 3em;
            margin-bottom: 20px;
        }

        .section {
            margin-bottom: 30px;
        }

        .section h2 {
            font-size: 2em;
            color: #2980b9;
            margin-bottom: 10px;
        }

        .section p {
            font-size: 1.1em;
            color: #7f8c8d;
        }

        ul, ol {
            margin: 10px 0 20px 30px;
            line-height: 1.6;
        }

        ul li, ol li {
            font-size: 1.1em;
        }

        a {
            color: #2980b9;
            text-decoration: none;
        }

        a:hover {
            color: #3498db;
        }

        .gallery img {
            width: 100%;
            max-width: 90%;
            display: block;
            margin: 15px auto;
            border-radius: 10px;
        }

        @media (max-width: 768px) {
            main {
                width: 95%;
            }

            h1 {
                font-size: 2em;
            }

            .section h2 {
                font-size: 1.8em;
            }
        }
    </style>
</head>
<body>
    <main>
        <h1>Explore The World</h1>

        <div class="section">
            <h2>About Us</h2>
            <p>Welcome to our travel site! We are passionate about discovering new places, learning about different cultures, and sharing the beauty of our planet with the world.</p>
        </div>

        <div class="section">
            <h2>Quick Facts</h2>

            <h3>Famous Landmarks</h3>
            <ul>
                <li>The Great Wall of China</li>
                <li>Mount Everest</li>
                <li>Eiffel Tower</li>
                <li>Taj Mahal</li>
            </ul>

            <a href="https://www.lonelyplanet.com/"><h3>Best Travel Destinations</h3></a>
            <ol>
                <li><strong>Paris, France</strong></li>
                <li>Tokyo, Japan</li>
                <li>New York City, USA</li>
                <li>Sydney, Australia</li>
                <li>Barcelona, Spain</li>
            </ol>
        </div>

        <div class="gallery">
            <h2>Gallery</h2>
            <img src="https://via.placeholder.com/800x400" alt="Beautiful Landscape">
            <img src="https://via.placeholder.com/800x400" alt="City Skyline">
            <img src="https://via.placeholder.com/800x400" alt="Mountain View">
        </div>

    </main>
</body>
</html>
