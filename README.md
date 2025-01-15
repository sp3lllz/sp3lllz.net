<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Landing Page</title>
    <style>
        /* General Reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            color: #333;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
            margin: 0;
        }

        header {
            text-align: center;
            margin-bottom: 20px;
        }

        header h1 {
            font-size: 2.5rem;
            font-weight: bold;
            color: #444;
        }

        header p {
            font-size: 1rem;
            color: #666;
        }

        .button-container {
            display: flex;
            gap: 10px;
            margin-top: 20px;
        }

        .button-container a {
            text-decoration: none;
            padding: 10px 20px;
            font-size: 1rem;
            color: #fff;
            background-color: #007BFF;
            border-radius: 5px;
            transition: background-color 0.3s ease;
        }

        .button-container a:hover {
            background-color: #0056b3;
        }

        footer {
            position: absolute;
            bottom: 10px;
            font-size: 0.875rem;
            color: #888;
        }

        footer a {
            color: #007BFF;
            text-decoration: none;
        }

        footer a:hover {
            text-decoration: underline;
        }

        @media (max-width: 600px) {
            header h1 {
                font-size: 2rem;
            }

            .button-container a {
                font-size: 0.9rem;
                padding: 8px 16px;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to Our Website</h1>
        <p>Discover amazing content and resources here.</p>
    </header>

    <div class="button-container">
        <a href="#">Get Started</a>
        <a href="#">Learn More</a>
    </div>

    <footer>
        <p>&copy; 2025 Your Company Name. All rights reserved.</p>
    </footer>
</body>
</html>
