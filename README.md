# starlight-hotel
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Starlight Hotel Pabo</title>
    <style>
        /* Resetting some default styles */
        body, h1, h2, p, input, button {
            margin: 0;
            padding: 0;
            font-family: 'Arial', sans-serif;
        }

        body {
            background-color: #f8f9fa;
            color: #333;
            line-height: 1.6;
            padding: 0 20px;
        }

        header {
            background-color: #1e2a47;
            color: white;
            text-align: center;
            padding: 40px 0;
        }

        header h1 {
            font-size: 50px;
            margin-bottom: 10px;
        }

        header p {
            font-size: 18px;
        }

        section {
            margin: 40px 0;
        }

        h2 {
            color: #1e2a47;
            margin-bottom: 20px;
            text-align: center;
        }

        .service-list {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
        }

        .service-item {
            background-color: #fff;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            margin: 20px;
            padding: 20px;
            width: 280px;
            text-align: center;
            transition: transform 0.3s ease;
        }

        .service-item:hover {
            transform: translateY(-10px);
        }

        .service-item h3 {
            margin-bottom: 10px;
            color: #1e2a47;
        }

        .service-item p {
            font-size: 16px;
            color: #555;
            margin-bottom: 15px;
        }

        .price {
            font-size: 18px;
            font-weight: bold;
            color: #d35400;
        }

        .contact, .booking-form {
            background-color: #fff;
            padding: 20px;
            margin-top: 40px;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        .contact h3, .booking-form h3 {
            color: #1e2a47;
        }

        .contact p, .contact ul {
            font-size: 16px;
            color: #555;
        }

        .contact ul {
            list-style-type: none;
            padding: 0;
        }

        .contact ul li {
            margin: 10px 0;
        }

        .booking-form input, .booking-form select, .booking-form button {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 2px solid #ddd;
            border-radius: 5px;
            font-size: 16px;
        }

        .booking-form button {
            background-color: #1e2a47;
            color: white;
            border: none;
            cursor: pointer;
        }

        .booking-form button:hover {
            background-color: #34495e;
        }

        footer {
            background-color: #1e2a47;
            color: white;
            text-align: center;
            padding: 15px;
            margin-top: 40px;
        }

        footer p {
            font-size: 14px;
        }

        .key-info {
            background-color: #2c3e50;
            color: white;
            padding: 30px;
            border-radius: 8px;
            text-align: center;
            margin-bottom: 40px;
        }

        .key-info h3 {
            font-size: 28px;
            margin-bottom: 15px;
        }

        .key-info p {
            font-size: 18px;
        }

    </style>
</head>
<body>

<header>
    <h1>Starlight Hotel Pabo</h1>
    <p>Your Comfort, Our Priority</p>
</header>

<section class="key-info">
    <h3>Why Choose Starlight Hotel Pabo?</h3>
    <p>At Starlight Hotel Pabo, we offer exceptional hospitality, comfortable rooms, and a wide range of services to make your stay unforgettable. Whether you're here for business or pleasure, we ensure you feel at home every moment.</p>
</section>

<section>
    <h2>Our Hotel Rooms</h2>
    <div class="service-list">
        <div class="service-item">
            <h3>Single Room</h3>
            <p>Cozy and private room, perfect for solo travelers.</p>
            <p class="price">12,000 UGX per night</p>
        </div>
        <div class="service-item">
            <h3>Self-Contained Room</h3>
            <p>Comfortable room with a private bathroom for more convenience.</p>
            <p class="price">20,000 UGX per night</p>
        </div>
    </div>
</section>

<section>
    <h2>Other Services Provided</h2>
    <div class="service-list">
        <div class="service-item">
            <h3>Tents</h3>
            <p>High-quality tents for your outdoor events and parties.</p>
        </div>
        <div class="service-item">
            <h3>Decorations for Weddings</h3>
            <p>Beautiful decorations to make your special day even more memorable.</p>
        </div>
        <div class="service-item">
            <h3>Party Decorations</h3>
            <p>We provide a wide range of decoration items for all types of parties.</p>
        </div>
    </div>
</section>

<section class="contact">
    <h3>Contact Us</h3>
    <p>If you have any questions or need assistance, don't hesitate to reach out to us:</p>
    <ul>
        <li>Phone: +256778754632</li>
        <li>Phone: +256740460544</li>
        <li>Email: info@starlightpabo.com</li>
    </ul>
</section>

<section class="booking-form">
    <h3>Book Your Room Online</h3>
    <p>Fill out the form below to book your room at Starlight Hotel Pabo.</p>
    <form action="#" method="POST">
        <label for="roomType">Room Type</label>
        <select id="roomType" name="roomType">
            <option value="single">Single Room (12,000 UGX)</option>
            <option value="selfContained">Self-Contained Room (20,000 UGX)</option>
        </select>

        <label for="checkInDate">Check-in Date</label>
        <input type="date" id="checkInDate" name="checkInDate" required>

        <label for="checkOutDate">Check-out Date</label>
        <input type="date" id="checkOutDate" name="checkOutDate" required>

        <button type="submit">Book Now</button>
    </form>
</section>

<footer>
    <p>&copy; 2025 Starlight Hotel Pabo | All rights reserved</p>
</footer>

</body>
</html>
