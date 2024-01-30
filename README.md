<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        #image-container {
            display: none; /* Initially hide the image container */
            margin-top: 20px;
        }
    </style>
    <script>
        function showImage() {
            // Get the image container
            var imageContainer = document.getElementById('image-container');

            // Set the source attribute of the image
            document.getElementById('my-image').src = '/home/vishishtmk/Desktop/a.png';

            // Show the image container
            imageContainer.style.display = 'block';
        }
    </script>
</head>
<body>
    <h1>Show Image Example</h1>
    
    <!-- Button to trigger the action -->
    <button onclick="showImage()">Show Image</button>

    <!-- Container to hold the image (initially hidden) -->
    <div id="image-container">
        <!-- Image element with an initial empty source -->
        <img id="my-image" src="" alt="Displayed Image">
    </div>

</body>
</html>
