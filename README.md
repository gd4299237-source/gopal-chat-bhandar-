<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gopal Chat Bhandar - Authentic Chaat & Snacks</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 0; padding: 0; background-color: #f4f4f4; color: #333; }
        header { background-color: #ff5722; color: white; padding: 20px; text-align: center; }
        nav { margin-top: 10px; }
        nav a { color: white; margin: 0 15px; text-decoration: none; font-weight: bold; }
        .hero { background-image: url('hero.jpg'); background-size: cover; height: 400px; display: flex; align-items: center; justify-content: center; text-align: center; color: white; }
        .hero h1 { font-size: 3em; margin: 0; }
        .section { padding: 40px; max-width: 1200px; margin: auto; }
        .menu { display: flex; flex-wrap: wrap; justify-content: space-around; }
        .menu-item { background: white; border-radius: 8px; box-shadow: 0 2px 5px rgba(0,0,0,0.1); margin: 10px; padding: 20px; width: 300px; text-align: center; }
        .menu-item img { width: 100%; height: 200px; object-fit: cover; border-radius: 8px; }
        .contact { background-color: #333; color: white; text-align: center; padding: 20px; }
        footer { text-align: center; padding: 10px; background-color: #222; color: white; }
        form { max-width: 400px; margin: auto; }
        input, textarea { width: 100%; padding: 10px; margin: 10px 0; border: 1px solid #ccc; border-radius: 4px; }
        button { background-color: #ff5722; color: white; padding: 10px; border: none; border-radius: 4px; cursor: pointer; }
    </style>
</head>
<body>
    <header>
        <h1>Gopal Chat Bhandar</h1>
        <nav>
            <a href="#home">COOCHBEHAR</a>
            <a href="#menu"> Golgappa</a>
            <a href="#contact">7679653009</a>
        </nav>
    </header>
    
    <section id="home" class="hero">
        <div>
            <h1>Welcome to Gopal Chat Bhandar</h1>
            <p>Authentic Indian chaat, snacks, and street food made fresh daily. Serving the best flavors since 1995!</p>
        </div>
    </section>
    
    <section id="menu" class="section">
        <h2>Our Menu</h2>
        <div class="menu">
            <div class="menu-item">
                <img src="menu1.jpg" alt="Pani Puri">
                <h3>Pani Puri</h3>
                <p>₹50 - Crispy puris filled with spiced water, potatoes, and chutneys.</p>
            </div>
            <div class="menu-item">
                <img src="menu2.jpg" alt="Bhel Puri">
                <h3>Bhel Puri</h3>
                <p>₹60 - A mix of puffed rice, veggies, and tangy tamarind sauce.</p>
            </div>
            <div class="menu-item">
                <img src="menu3.jpg" alt="Samosa">
                <h3>Samosa</h3>
                <p>₹40 - Golden-fried pastries stuffed with spiced potatoes.</p>
            </div>
            <!-- Add more items as needed -->
        </div>
    </section>
    
    <section id="contact" class="contact">
        <h2>Contact Us</h2>
        <p>Address: BC road, Shyama Prasad colony,Coochbehar ,India</p>
        <p>Phone: +91-7679653009 | Email: info@gopalchatbhandar.com</p>
        <form id="inquiryForm">
            <input type="text" placeholder="Your Name" required>
            <input type="email" placeholder="Your Email" required>
            <textarea placeholder="Your Message" required></textarea>
            <button type="submit">Send Inquiry</button>
        </form>
    </section>
    
    <footer>
        <p>&copy; 2023 Gopal Chat Bhandar. All rights reserved.</p>
    </footer>
    
    <script>
        document.getElementById('inquiryForm').addEventListener('submit', function(e) {
            e.preventDefault();
            alert('Thank you for your inquiry! We will get back to you soon.');
            // In a real site, integrate with a backend like EmailJS or Formspree for actual sending.
        });
    </script>
</body>
</html>
