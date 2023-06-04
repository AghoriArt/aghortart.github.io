# aghortart.github.io

<!DOCTYPE html>
<html>
<head>
    <title>Art Portfolio</title>
    <style>
        /* CSS styles */
        body {
            font-family: Arial, sans-serif;
            background-color: #f7f7f7;
            margin: 0;
            padding: 0;
        }
        
        header {
            background-color: #333;
            color: #fff;
            padding: 20px;
            text-align: center;
        }
        
        h1 {
            margin: 0;
        }
        
        .gallery {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            grid-gap: 20px;
            padding: 20px;
        }
        
        .gallery-item {
            border-radius: 5px;
            overflow: hidden;
            box-shadow: 0 0 5px rgba(0, 0, 0, 0.1);
        }
        
        .gallery-item img {
            width: 100%;
            height: auto;
            display: block;
        }
        
        .gallery-item h3 {
            margin: 0;
            padding: 10px;
            background-color: #333;
            color: #fff;
            text-align: center;
        }
    </style>
</head>
<body>
    <header>
        <h1>My Art Portfolio</h1>
    </header>
    
    <div class="gallery">
        <div class="gallery-item">
            <img src="image1.jpg" alt="Image 1">
            <h3>Artwork 1</h3>
        </div>
        
        <div class="gallery-item">
            <img src="image2.jpg" alt="Image 2">
            <h3>Artwork 2</h3>
        </div>
        
        <div class="gallery-item">
            <img src="image3.jpg" alt="Image 3">
            <h3>Artwork 3</h3>
        </div>
        
        <!-- Add more gallery items as needed -->
    </div>
</body>
</html>
