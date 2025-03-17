<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Balvatika Playway</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;800&display=swap');
        
        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(45deg, #ff9a9e, #fad0c4, #fad0c4, #ffdde1);
            background-size: 400% 400%;
            animation: gradientBG 8s ease infinite;
            color: #444;
        }
        @keyframes gradientBG {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }
        .container {
            width: 90%;
            max-width: 1200px;
            margin: auto;
            padding: 20px;
        }
        header {
            text-align: center;
            padding: 20px;
            font-size: 36px;
            font-weight: 800;
            color: #fff;
            text-shadow: 2px 2px 5px rgba(0,0,0,0.3);
            background: rgba(0, 0, 0, 0.3);
            border-radius: 15px;
        }
        .button {
            display: block;
            width: max-content;
            margin: 20px auto;
            padding: 15px 30px;
            font-size: 20px;
            font-weight: bold;
            color: white;
            background: #ff6b81;
            border-radius: 50px;
            text-decoration: none;
            box-shadow: 0 4px 6px rgba(0,0,0,0.2);
            transition: 0.3s;
        }
        .button:hover {
            background: #ff4757;
        }
        .facilities, .achievements {
            background: white;
            padding: 30px;
            border-radius: 15px;
            margin-top: 20px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
        }
        h2 {
            text-align: center;
            font-size: 28px;
            font-weight: 800;
            color: #ff4757;
        }
        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }
        .grid div {
            background: #ffdde1;
            padding: 20px;
            text-align: center;
            font-size: 18px;
            font-weight: 600;
            border-radius: 10px;
        }
        .contact {
            background: rgba(0, 0, 0, 0.3);
            padding: 20px;
            text-align: center;
            color: white;
            border-radius: 15px;
            margin-top: 30px;
        }
        footer {
            text-align: center;
            padding: 20px;
            font-weight: 600;
            background: rgba(0, 0, 0, 0.3);
            color: white;
            border-radius: 15px;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            Balvatika Playway - A World of Joyful Learning
        </header>
        <a href="#" class="button">Apply for Admission</a>
        
        <div class="facilities">
            <h2>Our Facilities</h2>
            <div class="grid">
                <div>Smart Classes</div>
                <div>Safe Playground</div>
                <div>Nutritious Meals</div>
                <div>Interactive Learning</div>
                <div>Qualified Teachers</div>
                <div>Fun Activities</div>
            </div>
        </div>

        <div class="achievements">
            <h2>Student Achievements</h2>
            <div class="grid">
                <div>Student of the Month</div>
                <div>Birthday Celebrations</div>
                <div>Test Toppers</div>
                <div>Student of the Year</div>
            </div>
        </div>

        <div class="contact">
            <h2>Contact Us</h2>
            <p>Phone: +91 9876543210</p>
            <p>Email: info@balvatikaplayway.com</p>
            <p>Address: 123, Fun Street, Playtown, India</p>
        </div>
        
        <footer>
            © 2025 Balvatika Playway. All Rights Reserved.
        </footer>
    </div>
</body>
</html>
