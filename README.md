<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Joji's Ice Cream Heaven</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Welcome to Joji's Ice Cream Heaven</h1>
        <p>Explore our delicious and creamy ice cream flavors!</p>
    </header>

    <section id="flavors">
        <h2>Our Flavors</h2>
        <div class="flavor">
            <h3>Vanilla</h3>
            <p>Classic, smooth, and rich vanilla flavor.</p>
        </div>
        <div class="flavor">
            <h3>Chocolate</h3>
            <p>Rich, creamy chocolate goodness.</p>
        </div>
        <div class="flavor">
            <h3>Strawberry</h3>
            <p>Fresh strawberry flavor with real fruit chunks.</p>
        </div>
        <div class="flavor">
            <h3>Mint Chocolate Chip</h3>
            <p>Cool mint with decadent chocolate chips.</p>
        </div>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <form id="contact-form">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="message">Message:</label>
            <textarea id="message" name="message" required></textarea>

            <button type="submit">Send Message</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2025 Joji's Ice Cream Heaven. All Rights Reserved.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
