# HECATRONIC-S-
mkdir -p src/static src/templates
touch src/app.py src/templates/register.html src/static/style.css README.md
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Register</title>
    <link rel="stylesheet" href="/static/style.css">
</head>
<body>
    <div class="container">
        <h1>Register</h1>
        <form action="/register" method="POST">
            <label for="username">Username:</label>
            <input type="text" id="username" name="username" required>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>  
        <button type="submit">Register</button>
        </form>
    </div>
</body>
</html>
