<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Aesthetic Clinic</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 10px 0;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #333;
        }
        nav a {
            color: white;
            padding: 14px 20px;
            text-decoration: none;
            text-align: center;
        }
        nav a:hover {
            background-color: #ddd;
            color: black;
        }
        .container {
            width: 80%;
            margin: 20px auto;
        }
        .section {
            padding: 20px 0;
            border-bottom: 1px solid #ccc;
        }
        .section h2 {
            color: #4CAF50;
        }
        form {
            background-color: white;
            padding: 20px;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        form div {
            margin-bottom: 15px;
        }
        form label {
            display: block;
            margin-bottom: 5px;
        }
        form input, form select, form textarea {
            width: 100%;
            padding: 10px;
            margin: 5px 0 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        form button {
            background-color: #4CAF50;
            color: white;
            border: none;
            padding: 10px 20px;
            border-radius: 5px;
            cursor: pointer;
        }
        form button:hover {
            background-color: #45a049;
        }
        footer {
            text-align: center;
            padding: 20px;
            background-color: #333;
            color: white;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to Our Aesthetic Clinic</h1>
    </header>
    <nav>
        <a href="#hours">Clinic Hours</a>
        <a href="#services">Services</a>
        <a href="#contact">Contact</a>
        <a href="#booking">Booking</a>
    </nav>
    <div class="container">
        <div id="hours" class="section">
            <h2>Clinic Hours</h2>
            <p>Monday - Friday: 9:00 AM - 6:00 PM</p>
            <p>Saturday: 10:00 AM - 4:00 PM</p>
            <p>Sunday: Closed</p>
        </div>
        <div id="services" class="section">
            <h2>Services</h2>
            <ul>
                <li>Facial Treatments</li>
                <li>Body Contouring</li>
                <li>Laser Hair Removal</li>
                <li>Botox and Fillers</li>
                <li>Skin Rejuvenation</li>
            </ul>
        </div>
        <div id="contact" class="section">
            <h2>Contact Information</h2>
            <p>Address: 123 Aesthetic Lane, Beauty City, BC 12345</p>
            <p>Phone: (123) 456-7890</p>
            <p>Email: contact@aestheticclinic.com</p>
        </div>
        <div id="booking" class="section">
            <h2>Book an Appointment</h2>
            <form>
                <div>
                    <label for="name">Name:</label>
                    <input type="text" id="name" name="name" required>
                </div>
                <div>
                    <label for="email">Email:</label>
                    <input type="email" id="email" name="email" required>
                </div>
                <div>
                    <label for="phone">Phone:</label>
                    <input type="tel" id="phone" name="phone" required>
                </div>
                <div>
                    <label for="service">Service:</label>
                    <select id="service" name="service" required>
                        <option value="facial">Facial Treatments</option>
                        <option value="body">Body Contouring</option>
                        <option value="laser">Laser Hair Removal</option>
                        <option value="botox">Botox and Fillers</option>
                        <option value="skin">Skin Rejuvenation</option>
                    </select>
                </div>
                <div>
                    <label for="date">Preferred Date:</label>
                    <input type="date" id="date" name="date" required>
                </div>
                <div>
                    <label for="time">Preferred Time:</label>
                    <input type="time" id="time" name="time" required>
                </div>
                <div>
                    <label for="message">Additional Information:</label>
                    <textarea id="message" name="message" rows="4"></textarea>
                </div>
                <button type="submit">Submit</button>
            </form>
        </div>
    </div>
    <footer>
        <p>&copy; 2024 Aesthetic Clinic. All rights reserved.</p>
    </footer>
</body>
</html>
