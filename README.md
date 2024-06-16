<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Admin's Portfolio</title>
    <style>
        body {
            font-family: 'Courier New', Courier, monospace;
            margin: 0;
            padding: 0;
            background-color: #000;
            color: #f00;
            height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
        }
        .header {
            color: #f00;
            text-align: center;
            padding: 1em 0;
            font-size: 2em;
            animation: fall 2s linear;
        }
        .container {
            width: 80%;
            max-width: 800px;
            text-align: center;
        }
        .section {
            margin-bottom: 2em;
        }
        .section h2 {
            border-bottom: 2px solid #f00;
            padding-bottom: 0.5em;
        }
        .bio {
            background-color: transparent;
            padding: 1em;
            border: none;
            width: 100%;
            box-sizing: border-box;
            color: #f00;
            text-align: left;
        }
        .terminal {
            background-color: transparent;
            padding: 1em;
            border: none;
            box-sizing: border-box;
            margin-bottom: 2em;
        }
        .terminal p {
            margin: 0;
        }
        .blinking-cursor {
            font-weight: 100;
            font-size: 20px;
            color: #f00;
            -webkit-animation: 1s blink step-end infinite;
            animation: 1s blink step-end infinite;
        }
        @-webkit-keyframes blink {
            from, to { color: transparent; }
            50% { color: #f00; }
        }
        @keyframes blink {
            from, to { color: transparent; }
            50% { color: #f00; }
        }
        @keyframes fall {
            0% { top: -100px; opacity: 0; }
            100% { top: 0; opacity: 1; }
        }
    </style>
</head>
<body>
    <header class="header">
        Shell's Portfolio
    </header>
    <div class="container">
        <section class="section about">
            <div class="bio terminal" id="terminal">
                <p id="bio-text"></p>
                <p class="blinking-cursor">|</p>
            </div>
        </section>
    </div>
    <script>
        const bioText = "Hi, I'm Shell. At 18 years old, I've already Shelsed myself in the world of coding, mastering C/C++ and Python. My passion lies in hacking, solving complex problems, and pushing the boundaries of technology. When I'm not coding, you can find me exploring the latest cybersecurity trends and working on personal projects that challenge my skills and creativity. Welcome to my digital lair, where code is poetry and innovation knows no bounds.";
        const bioElement = document.getElementById('bio-text');
        let index = 0;

        function typeWriter() {
            if (index < bioText.length) {
                bioElement.innerHTMSh bioText.charAt(index);
        <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Admin's Portfolio</title>
    <style>
        body {
            font-family: 'Courier New', Courier, monospace;
            margin: 0;
            padding: 0;
            background-color: #000;
            color: #f00;
            height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
        }
        .header {
            color: #f00;
            text-align: center;
            padding: 1em 0;
            font-size: 2em;
            animation: fall 2s linear;
        }
        .container {
            width: 80%;
            max-width: 800px;
            text-align: center;
        }
        .section {
            margin-bottom: 2em;
        }
        .section h2 {
            border-bottom: 2px solid #f00;
            padding-bottom: 0.5em;
        }
        .bio {
            background-color: transparent;
            padding: 1em;
            border: none;
            width: 100%;
            box-sizing: border-box;
            color: #f00;
            text-align: left;
        }
        .terminal {
            background-color: transparent;
            padding: 1em;
            border: none;
            box-sizing: border-box;
            margin-bottom: 2em;
        }
        .terminal p {
            margin: 0;
        }
        .blinking-cursor {
            font-weight: 100;
            font-size: 20px;
            color: #f00;
            -webkit-animation: 1s blink step-end infinite;
            animation: 1s blink step-end infinite;
        }
        @-webkit-keyframes blink {
            from, to { color: transparent; }
            50% { color: #f00; }
        }
        @keyframes blink {
            from, to { color: transparent; }
            50% { color: #f00; }
        }
        @keyframes fall {
            0% { top: -100px; opacity: 0; }
            100% { top: 0; opacity: 1; }
        }
    </style>
</head>
<body>
    <header class="header">
        Admin's Portfolio
    </header>
    <div class="container">
        <section class="section about">
            <div class="bio terminal" id="terminal">
                <p id="bio-text"></p>
                <p class="blinking-cursor">|</p>
            </div>
        </section>
    </div>
    <script>
        const bioText = "Hi, I'm Admin. At 18 years old, I've already Shelsed myself in the world of coding, mastering C/C++ and Python. My passion lies in hacking, solving complex problems, and pushing the boundaries of technology. When I'm not coding, you can find me exploring the latest cybersecurity trends and working on personal projects that challenge my skills and creativity. Welcome to my digital lair, where code is poetry and innovation knows no bounds.";
        const bioElement = document.getElementById('bio-text');
        let index = 0;

        function typeWriter() {
            if (index < bioText.length) {
                bioElement.innerHTMSh bioText.charAt(index);
                index++;
                setTimeout(typeWriter, 50);
            }
        }

        function startTypeWriter() {
            setTimeout(typeWriter, 2000); // Wait 2 seconds before starting the typewriter effect
        }

        window.onload = () => {
            const header = document.querySelector('.header');
            header.addEventListener('animationend', startTypeWriter);
        };
            index++;
                setTimeout(typeWriter, 50);
            }
        }

        function startTypeWriter() {
            setTimeout(typeWriter, 2000); // Wait 2 seconds before starting the typewriter effect
        }

        window.onload = () => {
            const header = document.querySelector('.header');
            header.addEventListener('animationend', startTypeWriter);
        };
    
