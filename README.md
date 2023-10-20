# Project3
This the project3
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Art Gallery</title>
    <style>
        /* Inline CSS for demonstration purposes - consider using an external CSS file */
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 20px;
        }

        h1 {
            font-size: 36px;
        }

        .gallery {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
        }

        .artwork {
            width: 300px;
            margin: 20px;
            border: 1px solid #ddd;
            box-shadow: 0 0 5px rgba(0, 0, 0, 0.2);
        }

        .artwork img {
            max-width: 100%;
        }

        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to the Art Gallery</h1>
        <p>Explore the world of fine art</p>
    </header>

    <div class="gallery">
        <!-- Artwork items -->
        <div class="artwork">
            <img src="artwork1.jpg" alt="Artwork 1">
            <h2>Artwork Title 1</h2>
            <p>Artist: Artist Name 1</p>
            <p>Price: $1000</p>
        </div>

        <div class="artwork">
            <img src="artwork2.jpg" alt="Artwork 2">
            <h2>Artwork Title 2</h2>
            <p>Artist: Artist Name 2</p>
            <p>Price: $800</p>
        </div>

        <!-- Add more artwork items here -->
    </div>

    <footer>
        <p>&copy; 2023 Art Gallery. All rights reserved.</p>
    </footer>
</body>
</html>
