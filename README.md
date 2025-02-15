<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Virtual Laboratory</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Virtual Physics Laboratory</h1>
    </header>
    <main>
        <section id="experiment">
            <h2>Current Experiment: Pendulum</h2>
            <canvas id="pendulumCanvas" width="800" height="400"></canvas>
        </section>
        <section id="controls">
            <h2>Controls</h2>
            <label for="length">Length: </label>
            <input type="range" id="length" name="length" min="10" max="200" value="100">
            <label for="angle">Initial Angle: </label>
            <input type="range" id="angle" name="angle" min="0" max="90" value="45">
            <button id="start">Start Experiment</button>
        </section>
    </main>
    <script src="script.js"></script>
</body>
</html>