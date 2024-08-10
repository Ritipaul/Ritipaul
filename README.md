<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Landing Page</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            text-align: center;
        }

        .container {
            padding: 20px;
            max-width: 600px;
            margin: auto;
        }

        .headline {
            font-size: 2em;
            margin-bottom: 0.5em;
        }

        .cta {
            background-color: #007bff;
            color: #fff;
            padding: 15px 25px;
            text-decoration: none;
            border-radius: 5px;
        }

        .cta:hover {
            background-color: #0056b3;
        }

        .form-group {
            margin: 1em 0;
        }

        input {
            padding: 10px;
            width: 100%;
            max-width: 300px;
            border: 1px solid #ddd;
            border-radius: 5px;
        }
    </style>
</head>

<body>
    <div class="container">
        <h1 class="headline">Welcome to Our Product!</h1>
        <p>Discover the amazing features and benefits we offer.</p>
        <a href="#form" class="cta">Get Started</a>

        <form id="form" action="#" method="post">
            <div class="form-group">
                <input type="text" name="name" placeholder="Your Name" required>
            </div>
            <div class="form-group">
                <input type="email" name="email" placeholder="Your Email" required>
            </div>
            <button type="submit" class="cta">Submit</button>
        </form>
    </div>
</body>

</html>
