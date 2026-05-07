<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple Webpage</title>

    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 40px;
        }

        .image-section {
            display: flex;
            align-items: center;
            gap: 20px;
            margin-top: 20px;
        }

        .image-section img {
            width: 250px;
            height: auto;
            border-radius: 10px;
        }
    </style>
</head>
<body>

    <!-- Header -->
    <h1>Welcome to My Website</h1>

    <!-- Paragraph -->
    <p>
        This is a simple example of an HTML webpage that contains
        a header, a paragraph, and an image with text beside it.
    </p>

    <!-- Image with text beside it -->
    <div class="image-section">
        <img src="https://via.placeholder.com/250" alt="Sample Image">

        <p>
            This text appears beside the image. You can write
            descriptions, introductions, or any information here.
        </p>
    </div>

</body>
</html>
