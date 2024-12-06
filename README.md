<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Parking Space Monitoring System</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
            color: #333;
        }
        header {
            background: #007bff;
            color: #fff;
            padding: 20px 0;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 2.5em;
        }
        .container {
            max-width: 800px;
            margin: 20px auto;
            padding: 20px;
            background: #fff;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            border-radius: 8px;
        }
        h2 {
            color: #007bff;
        }
        ul {
            list-style: square inside;
        }
        footer {
            text-align: center;
            padding: 10px 0;
            background: #333;
            color: #fff;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Parking Space Monitoring System</h1>
    </header>
    <div class="container">
        <h2>About the Project</h2>
        <p>
            The Parking Space Monitoring System is a real-time application designed to monitor and track parking spaces in a lot. Using video feed and advanced image processing techniques, it detects and counts available parking spots.
        </p>

        <h2>Key Features</h2>
        <ul>
            <li>Real-time monitoring of parking spaces.</li>
            <li>Detection and classification of free or occupied spots.</li>
            <li>Accurate vehicle counting using predefined parking spaces.</li>
            <li>Utilizes OpenCV for video analysis and frame processing.</li>
        </ul>

        <h2>Technology Stack</h2>
        <ul>
            <li><strong>Programming Language:</strong> Python</li>
            <li><strong>Image Processing Library:</strong> OpenCV</li>
            <li><strong>Techniques Used:</strong> Thresholding, Blurring, Dilation</li>
        </ul>

        <h2>How It Works</h2>
        <p>
            The system processes frames from a video feed to detect vehicles. It identifies the occupancy status of predefined parking spaces by:
        </p>
        <ul>
            <li>Analyzing video frames in real-time.</li>
            <li>Applying image processing techniques such as thresholding, blurring, and dilation.</li>
            <li>Highlighting parking spaces as either <strong>occupied</strong> or <strong>vacant</strong>.</li>
        </ul>

        <h2>Getting Started</h2>
        <ol>
            <li>Install Python and OpenCV.</li>
            <li>Set up the video feed and define parking space coordinates.</li>
            <li>Run the script to start monitoring the parking lot in real-time.</li>
        </ol>
    </div>
    <footer>
        <p>© 2024 Parking Space Monitoring System. All Rights Reserved.</p>
    </footer>
</body>
</html>

