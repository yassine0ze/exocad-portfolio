# exocad-portfolio
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Exocad Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #333;
            color: white;
            padding: 1rem;
            text-align: center;
        }
        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            padding: 20px;
        }
        .gallery img {
            width: 100%;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
        .description {
            text-align: center;
            margin-top: 10px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Exocad Portfolio</h1>
        <p>Showcasing my dental CAD designs</p>
    </header>
    <div class="gallery">
        <div>
            <img src="images/design1.png" alt="Design 1">
            <div class="description">Design 1: Full arch restoration</div>
        </div>
        <div>
            <img src="images/design2.png" alt="Design 2">
            <div class="description">Design 2: Crown design</div>
        </div>
        <!-- Add more designs as needed -->
    </div>
</body>
</html>
