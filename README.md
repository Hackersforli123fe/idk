<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Leibniz Rule - Math Geeks</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
            display: flex;
            flex-direction: column;
            justify-content: space-between; /* Ensures top and bottom sections are spaced */
            align-items: center;
            height: 100vh;
            margin: 0;
        }
        /* Header text */
        p:first-of-type {
            font-size: 3em; /* Large font size for the header */
            font-weight: bold;
            margin-top: 20px; /* Adds space at the top */
        }
        /* Footer text */
        p:last-of-type {
            font-size: 1.2em; /* Smaller font size for the footer */
            font-style: italic; /* Italicizes the footer */
            margin-bottom: 20px; /* Adds space at the bottom */
        }
        .container {
            display: flex;
            gap: 20px;
            justify-content: center;
            flex-wrap: wrap;
        }
        .button {
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            text-decoration: none;
            width: 150px;
            height: 150px;
            background-color: #ffffff;
            border-radius: 15px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            transition: transform 0.2s, box-shadow 0.2s;
        }
        .button:hover {
            transform: scale(1.05);
            box-shadow: 0 6px 8px rgba(0, 0, 0, 0.2);
        }
        .button img {
            width: 80%;
            border-radius: 10px;
        }
        .button span {
            margin-top: 10px;
            font-size: 16px;
            color: #333;
        }
    </style>
    <script>
	function opendino() {
            var win = window.open()
            var url = "dino.html"
            var iframe = win.document.createElement('iframe')
            iframe.style.width = "100%";
            iframe.style.height = "100%";
            iframe.style.border = "none";
            iframe.src = url
            win.document.body.appendChild(iframe)
        }
	function openmc() {
            var win = window.open()
            var url = "https://theult1mateh4ck3r.github.io/games/"
            var iframe = win.document.createElement('iframe')
            iframe.style.width = "100%";
            iframe.style.height = "100%";
            iframe.style.border = "none";
            iframe.src = url
            win.document.body.appendChild(iframe)
        }
	function opentroll() {
            var win = window.open()
            var url = "really.html"
            var iframe = win.document.createElement('iframe')
            iframe.style.width = "100%";
            iframe.style.height = "100%";
            iframe.style.border = "none";
            iframe.src = url
            win.document.body.appendChild(iframe)
        }
	function opengg() {
            var win = window.open()
            var url = "https://theult1mateh4ck3r.github.io/mathematics"
            var iframe = win.document.createElement('iframe')
            iframe.style.width = "100%";
            iframe.style.height = "100%";
            iframe.style.border = "none";
            iframe.src = url
            win.document.body.appendChild(iframe)
        }
	function openbid() {
            var win = window.open()
            var url = "https://hackersforli123fe.github.io/pical/"
            var iframe = win.document.createElement('iframe')
            iframe.style.width = "100%";
            iframe.style.height = "100%";
            iframe.style.border = "none";
            iframe.src = url
            win.document.body.appendChild(iframe)
        }
	function openslop() {
            var win = window.open()
            var url = "https://hackersforli123fe.github.io/pical/slope/"
            var iframe = win.document.createElement('iframe')
            iframe.style.width = "100%";
            iframe.style.height = "100%";
            iframe.style.border = "none";
            iframe.src = url
            win.document.body.appendChild(iframe)
        }
	</script>
</head>
<body>
    <!-- Header Text -->
    <p>Unblocked "Items"</p>
    <!-- Container for buttons -->
    <div class="container">
        <!-- Chrome Dino -->
        <a href="dino.html" class="button" target="_blank" onclick="opendino()">
            <img src="images/dino.png" alt="Chrome Dino">
            <span>Chrome Dino</span>
        </a>
        <!-- Eaglecraft -->
        <a href="https://theult1mateh4ck3r.github.io/games" class="button" target="_blank" onclick="openmc()">
            <img src="images/mc.png" alt="Eaglecraft">
            <span>Eaglecraft</span>
        </a>
        <!-- We LOVE trolls -->
        <a href="really.html" class="button" target="_blank" onclick="opentroll()">
            <img src="images/404-glitch.png" alt="Get trolled lol">
            <span>FOR DEVS ONLY</span>
        </a>
        <!-- MonkeyGG2 -->
        <a href="https://theult1mateh4ck3r.github.io/mathematics" class="button" target="_blank" onclick="opengg()">
            <img src="images/monkeygg2.ico" alt="MonkeyGG2">
            <span>MonkeyGG2</span>
        </a>
        <!-- Bidoofery -->
        <a href="https://hackersforli123fe.github.io/pical/" class="button" target="_blank" onclick="openbid()">
            <img src="images/favicon.png" alt="Bidoofery">
            <span>Bidoofery</span>
        </a>
        <!-- Slope -->
        <a href="https://hackersforli123fe.github.io/pical/slope/" class="button" target="_blank" onclick="openslop()">
            <img src="images/slope.png" alt="Slope">
            <span>Slope</span>
        </a>
    </div>
    <!-- Footer Text -->
    <p>Made By A Classmate Of Yours</p>
</body>
</html>
