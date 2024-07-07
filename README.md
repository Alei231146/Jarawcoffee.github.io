<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>JARAW Coffee Shop</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css" integrity="sha512-J+JUy1Us5tGptZHv7brWl3W8kma0g7vFbERp+Y3EiQO1nG0sWbh2O2hjDrW5Fk1+6QHXnDwuN/nDEfQggrm/9A==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <style>
        /* Reset default browser styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        /* Basic styling */
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            background-color: #f5f5f5; /* Light background */
            color: #333; /* Dark text color */
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        .container {
            width: 80%;
            padding: 20px;
        }

        header {
            background-color: #8d6e63; /* Darker coffee color for header */
            color: #fff; /* White text color */
            padding: 20px 0;
            text-align: center;
            margin-bottom: 20px;
            width: 100%;
        }

        header h1 {
            font-size: 3rem;
            font-weight: bold;
            margin-bottom: 10px;
        }

        section {
            background-color: #fff; /* White background for sections */
            margin-bottom: 20px;
            padding: 30px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1); /* Soft shadow */
            width: 100%;
            max-width: 800px;
        }

        section h2 {
            font-size: 2.5rem;
            margin-bottom: 20px;
            color: #333; /* Dark text color */
            text-align: center;
        }

        section p {
            font-size: 1.2rem;
            line-height: 1.8;
            color: #666; /* Lighter text color */
            text-align: justify;
        }

        .contact-info {
            font-weight: bold;
            color: #333; /* Dark text color */
        }

        footer {
            background-color: #8d6e63; /* Darker coffee color for footer */
            color: #fff; /* White text color */
            text-align: center;
            padding: 10px 0;
            width: 100%;
            position: fixed;
            bottom: 0;
        }

        /* Coffee icons styling */
        .coffee-icon {
            position: absolute;
            top: 10px;
            right: 10px;
            color: rgba(0, 0, 0, 0.1); /* Light coffee color for icons */
            font-size: 80px;
            pointer-events: none;
        }

        /* Responsive image styling */
        .coffee-images {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
            margin-top: 30px;
        }

        .coffee-images img {
            width: 100%;
            max-width: 200px;
            height: auto;
            border-radius: 8px;
            box-shadow: 0 0 8px rgba(0, 0, 0, 0.2); /* Soft shadow */
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>JARAW Coffee Shop</h1>
        </div>
    </header>

    <section id="about" class="container">
        <h2>About Us</h2>
        <p>At JARAW Coffee Shop, we're passionate about serving you the finest coffee experience. From carefully selected beans to expertly brewed beverages, we ensure every cup is crafted with love and precision.</p>
        <i class="fas fa-coffee coffee-icon"></i>
    </section>

    <section id="menu" class="container">
        <h2>Our Menu</h2>
        <p>Explore our diverse menu featuring a range of specialty coffees, teas, and delicious pastries. Whether you prefer a rich espresso or a soothing herbal tea, we have something to satisfy every palate.</p>
        <i class="fas fa-coffee coffee-icon"></i>
    </section>

    <section id="commitment" class="container">
        <h2>Our Commitment</h2>
        <p>We are committed to quality, sustainability, and community. Our beans are sourced responsibly, and we strive to minimize our environmental footprint. Join us in supporting local initiatives and enjoying exceptional coffee.</p>
        <i class="fas fa-coffee coffee-icon"></i>
    </section>

    <section id="visit" class="container">
        <h2>Visit Us</h2>
        <p>Come visit us at:<br>
        <span class="contact-info">Address:</span> No.44/In front of CIty Park/YuZaNa/Myitkyina<br>
        <span class="contact-info">Phone:</span> <a href="tel:+959700787822" class="contact-info">09700787822</a><br>
        <span class="contact-info">Gmail:</span> <a href="mailto:jarawcoffee20@gmail.com" class="contact-info">jarawcoffee20@gmail.com</a><br>
        <span class="contact-info">Telegram:</span> <a href="https://t.me/jarawcoffee20" class="contact-info">t.me/jarawcoffee20</a></p>
        <i class="fas fa-coffee coffee-icon"></i>
    </section>

    <!-- Coffee cup images -->
    <div class="container">
        <h2>Our Coffee</h2>
        <div class="coffee-images">
            <img src="https://i.imgur.com/gtao7xy.jpeg" alt="Coffee Cup 1">
            <img src="https://i.imgur.com/ohF33VB.jpeg" alt="Coffee Cup 2">
            <img src="https://i.imgur.com/BH0l38Q.jpeg" alt="Coffee Cup 3">
            <img src="https://i.imgur.com/BNvHlvY.jpeg" alt="Coffee Cup 4">
        </div>
    </div>

    <footer>
        <div class="container">
            <p>&copy; 2024 JARAW Coffee Shop. All rights reserved.</p>
        </div>
    </footer>
</body>
</html>
