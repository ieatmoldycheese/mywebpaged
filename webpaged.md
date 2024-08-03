<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Amy's Personal Webpage</title>
    <style>
        body {
            background-color: #ffe4e6;
            color: #4a4a4a;
            font-family: 'Brush Script MT', cursive;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #ffb6c1;
            padding: 20px;
            text-align: center;
        }
        header h1 {
            margin: 0;
            color: #fff;
        }
        section {
            padding: 20px;
        }
        .gallery {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
            justify-content: center;
        }
        .gallery img {
            width: 150px;
            height: 150px;
            object-fit: cover;
            border-radius: 10px;
            border: 2px solid #ff69b4;
        }
        footer {
            background-color: #ffb6c1;
            padding: 10px;
            text-align: center;
            color: #fff;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>

<header>
    <h1>Welcome to Amy's Page</h1>
</header>

<section>
    <h2>About Me</h2>
    <p>I like cats.</p>
</section>

<section>
    <h2>Gallery</h2>
    <div class="gallery">
        <img src="https://via.placeholder.com/150/ffb6c1/000000?text=Coquette+1" alt="Coquette Image 1">
        <img src="https://via.placeholder.com/150/ffb6c1/000000?text=Coquette+2" alt="Coquette Image 2">
        <img src="https://via.placeholder.com/150/ffb6c1/000000?text=Coquette+3" alt="Coquette Image 3">
        <img src="https://via.placeholder.com/150/ffb6c1/000000?text=Coquette+4" alt="Coquette Image 4">
        <img src="https://via.placeholder.com/150/ffb6c1/000000?text=Coquette+5" alt="Coquette Image 5">
    </div>
</section>

<footer>
    &copy; 2024 Amy's Personal Webpage
</footer>

</body>
</html>
