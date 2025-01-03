
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Design and Analysis of Algorithms - Portfolio</title>
    <style>
        /* General Reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        /* Body Styling */
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            color: #e0e0e0; /* Brighter text for better readability */
            background-image: linear-gradient(rgba(0, 0, 0, 0.85), rgba(0, 0, 0, 0.85)), url('background.png');
            background-size: cover;
            background-position: center;
            background-attachment: fixed;
            line-height: 1.6;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            text-align: center;
            flex-direction: column;
            overflow-x: hidden; /* Prevent horizontal scrolling */
            width: 100%; /* Ensure the body is full width */
            margin: 0; /* Remove any default margin */
        }

        /* Header Styling */
        header {
            margin-bottom: 20px;
        }

        header h1 {
            font-size: 3rem;
            font-weight: bold;
            color: #ffffff;
            text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.7);
        }

        header p {
            font-size: 1.4rem;
            color: #f5f5f5;
        }

        /* Footer Styling */
        footer {
            background-color: rgba(44, 62, 80, 0.95);
            color: #ffffff;
            text-align: center;
            padding: 20px 0;
            position: absolute;
            bottom: 0;
            width: 100%;
        }

        footer p {
            font-size: 1rem;
        }

        /* Top-right Horizontal Buttons */
        .top-buttons {
            position: fixed;
            top: 20px;
            right: 20px;
            display: flex;
            gap: 15px;
        }

        .top-buttons a {
            background-color: rgba(0, 123, 255, 0.8);
            color: #ffffff;
            padding: 12px 20px;
            text-decoration: none;
            border-radius: 8px;
            font-size: 1rem;
            text-align: center;
            transition: background-color 0.3s ease;
            white-space: nowrap;
        }

        .top-buttons a:hover {
            background-color: rgba(0, 123, 255, 1);
        }

        /* Mobile Responsiveness */
        @media (max-width: 768px) {
            header h1 {
                font-size: 2.4rem;
            }

            header p {
                font-size: 1.2rem;
            }

            .top-buttons {
                top: 10px;
                right: 10px;
                gap: 8px;
            }

            .top-buttons a {
                padding: 10px 15px;
                font-size: 0.9rem;
            }
        }
    </style>
</head>
<body>
    <!-- Top-right Horizontal Buttons -->
    <div class="top-buttons">
        <!-- Buttons that link to different sections/pages -->
        <a href="my.html">My Profile</a>
        <a href="course.html" id="course-reflection">Course Reflection</a>
        <a href="team.html">Team</a>
        <a href="businesscase.html" id="business-cases">Business Cases</a>
        <a href="city.html">City Design</a>
    </div>

    <header>
        <h1>Design and Analysis of Algorithms</h1>
        <p>A Comprehensive Learning Portfolio</p>
    </header>

    <footer>
        <p>&copy; 2024 Design and Analysis of Algorithms Learning Portfolio</p>
    </footer>
</body>
</html>
