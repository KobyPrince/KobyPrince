<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Koby Prince - Automotive Sales Professional</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 1em 0;
            text-align: center;
        }
        .container {
            width: 80%;
            margin: 0 auto;
        }
        h1 {
            margin: 0;
        }
        section {
            padding: 2em 0;
        }
        .section-title {
            font-size: 1.5em;
            margin-bottom: 0.5em;
            color: #333;
        }
        .section-content {
            background-color: #fff;
            border-radius: 8px;
            padding: 1em;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 1em 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        a {
            color: #1e90ff;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
        .vehicle {
            display: flex;
            margin-bottom: 1em;
            border: 1px solid #ddd;
            border-radius: 8px;
            overflow: hidden;
        }
        .vehicle img {
            max-width: 200px;
            height: auto;
        }
        .vehicle-details {
            padding: 1em;
            flex: 1;
        }
        .vehicle-title {
            font-size: 1.2em;
            margin: 0;
            color: #333;
        }
        .vehicle-info {
            margin: 0.5em 0;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>Koby Prince</h1>
            <p>Automotive Sales Professional</p>
        </div>
    </header>

    <div class="container">
        <section>
            <div class="section-title">About Me</div>
            <div class="section-content">
                <p>Born and raised Miramichi'er, I have been in the automotive sales business for several years. After graduating college, I started helping people get their dream vehicles at Towne Chrysler. For the past 3 years, I've been working with all types of credit and assisting clients from all over Canada in finding the perfect vehicle.</p>
            </div>
        </section>

        <section>
            <div class="section-title">Services</div>
            <div class="section-content">
                <p>I specialize in automotive sales, providing personalized service to match clients with their ideal vehicles. Whether you're looking for a new car, used car, or financing options, I'm here to help you navigate the process and find the best solution for your needs.</p>
            </div>
        </section>

        <section>
            <div class="section-title">Featured Vehicles</div>
            <div class="section-content">
                <!-- Vehicle 1 -->
                <div class="vehicle">
                    <img src="https://via.placeholder.com/200" alt="Vehicle Image 1">
                    <div class="vehicle-details">
                        <h3 class="vehicle-title">2020 Honda Civic</h3>
                        <p class="vehicle-info">Make: Honda</p>
                        <p class="vehicle-info">Model: Civic</p>
                        <p class="vehicle-info">Mileage: 25,000 km</p>
                    </div>
                </div>
                <!-- Vehicle 2 -->
                <div class="vehicle">
                    <img src="https://via.placeholder.com/200" alt="Vehicle Image 2">
                    <div class="vehicle-details">
                        <h3 class="vehicle-title">2018 Toyota Corolla</h3>
                        <p class="vehicle-info">Make: Toyota</p>
                        <p class="vehicle-info">Model: Corolla</p>
                        <p class="vehicle-info">Mileage: 30,000 km</p>
                    </div>
                </div>
                <!-- Add more vehicles as needed -->
            </div>
        </section>

        <section>
            <div class="section-title">Contact</div>
            <div class="section-content">
                <p>For inquiries or to schedule a consultation, please reach out to me:</p>
                <p>Email: <a href="mailto:koby@townechrysler.ca">koby@townechrysler.ca</a></p>
                <p>Phone: <a href="tel:+15062105700">506-210-5700</a></p>
            </div>
        </section>
    </div>

    <footer>
        <p>&copy; 2024 Koby Prince. All rights reserved.</p>
    </footer>
</body>
</html>
