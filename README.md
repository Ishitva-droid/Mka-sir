<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rocket Launch Simulation</title>
    <style>
        body {
            background: linear-gradient(to bottom, #001f3f, #87CEEB);
            text-align: center;
            overflow: hidden;
            font-family: Arial, sans-serif;
        }
        .launch-pad {
            position: absolute;
            bottom: 50px;
            left: 50%;
            transform: translateX(-50%);
            width: 100px;
        }
        .rocket {
            width: 80px;
            position: absolute;
            bottom: 50px;
            left: 50%;
            transform: translateX(-50%);
            transition: bottom 3s ease-in-out;
        }
        .flames {
            width: 30px;
            height: 50px;
            background: orange;
            position: absolute;
            bottom: -50px;
            left: 50%;
            transform: translateX(-50%);
            display: none;
            border-radius: 50% 50% 0 0;
        }
        button {
            padding: 15px;
            margin: 20px;
            font-size: 18px;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <h1>🚀 Rocket Launch Simulator 🚀</h1>
    <img src="rocket.png" alt="Rocket" class="rocket" id="rocket">
    <div class="flames" id="flames"></div>
    <img src="launchpad.png" alt="Launch Pad" class="launch-pad">
    
    <button onclick="fuelRocket()">Fuel Rocket ⛽</button>
    <button onclick="launchRocket()">Launch Rocket 🚀</button>
    
    <script>
        let fueled = false;

        function fuelRocket() {
            fueled = true;
            alert("Rocket is fueled and ready to launch!");
        }

        function launchRocket() {
            if (!fueled) {
                alert("Please fuel the rocket first!");
                return;
            }
            document.getElementById("flames").style.display = "block";
            document.getElementById("rocket").style.bottom = "100vh";
            setTimeout(() => {
                alert("Rocket has successfully launched into space!");
            }, 3000);
        }
    </script>
</body>
</html>
