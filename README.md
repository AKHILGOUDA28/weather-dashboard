<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Swetha Rani's Portfolio</title>
    <style>
        /* General Styles */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
            text-align: center;
        }

        h1 {
            color: #333;
            font-size: 2.5em;
            margin-top: 50px;
        }

        p {
            color: #555;
            font-size: 1.2em;
        }

        a {
            display: inline-block;
            margin-top: 20px;
            padding: 15px 30px;
            font-size: 18px;
            text-decoration: none;
            color: white;
            background-color: #007BFF;
            border-radius: 5px;
            transition: background-color 0.3s;
        }

        a:hover {
            background-color: #0056b3;
        }

        /* Responsive Design */
        .container {
            width: 100%;
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }

        /* Mobile First Approach */
        @media (max-width: 600px) {
            h1 {
                font-size: 1.8em;
            }

            p {
                font-size: 1em;
            }

            a {
                padding: 10px 20px;
                font-size: 16px;
            }
        }

        /* Tablets and Small Screens */
        @media (min-width: 601px) and (max-width: 1024px) {
            h1 {
                font-size: 2.2em;
            }

            p {
                font-size: 1.1em;
            }

            a {
                padding: 12px 25px;
                font-size: 17px;
            }
        }

        /* Desktop */
        @media (min-width: 1025px) {
            h1 {
                font-size: 3em;
            }

            p {
                font-size: 1.3em;
            }

            a {
                padding: 15px 30px;
                font-size: 18px;
            }
        }
    </style>
</head>

<body>
    <div class="container">
        <h1>Welcome to My Portfolio</h1>
        <p>Hi, I'm Swetha Rani. You can view and download my resume below:</p>
        <a href="https://swetha-rani-portfolio.s3.amazonaws.com/resume.pdf" target="_blank">Download My Resume</a>
    </div>
</body>

</html>
