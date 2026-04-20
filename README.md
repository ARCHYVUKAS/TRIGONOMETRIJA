<!DOCTYPE html>
<html lang="lt">
<head>
    <meta charset="UTF-8">
    <title>Trigonometrijos kartojimas</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 40px;
            background-color: #f4f6f8;
        }
        h1, h2 {
            color: #2c3e50;
        }
        .box {
            background: white;
            padding: 20px;
            margin-bottom: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        button {
            padding: 10px 15px;
            border: none;
            background-color: #3498db;
            color: white;
            border-radius: 5px;
            cursor: pointer;
        }
        .answers {
            display: none;
            margin-top: 10px;
            color: green;
        }
    </style>
</head>
<body>

<h1>Trigonometrijos kartojimas</h1>

<div class="box">
    <h2>Pagrindai</h2>
    <p><b>sin(α)</b> = priešpriešinė / įžambinė</p>
    <p><b>cos(α)</b> = prigludusioji / įžambinė</p>
    <p><b>tan(α)</b> = priešpriešinė / prigludusioji</p>
</div>

<div class="box">
    <h2>Uždaviniai</h2>
    <ol>
        <li>Rask sin(30°)</li>
        <li>Rask cos(60°)</li>
        <li>Rask tan(45°)</li>
        <li>Jei priešpriešinė = 3, įžambinė = 5, rask sin(α)</li>
        <li>Jei prigludusioji = 4, įžambinė = 5, rask cos(α)</li>
        <li>Rask kampą, jei sin(α) = 0.5</li>
        <li>Rask kampą, jei cos(α) = 0.5</li>
        <li>Rask kampą, jei tan(α) = 1</li>
        <li>Rask sin²(α) + cos²(α)</li>
        <li>Jei tan(α) = 2, ką tai reiškia santykiu?</li>
    </ol>

    <button onclick="toggleAnswers()">Rodyti atsakymus</button>

    <div class="answers" id="answers">
        <p>1) 0.5</p>
        <p>2) 0.5</p>
        <p>3) 1</p>
        <p>4) 3/5</p>
        <p>5) 4/5</p>
        <p>6) 30°</p>
        <p>7) 60°</p>
        <p>8) 45°</p>
        <p>9) 1</p>
        <p>10) priešpriešinė = 2 × prigludusioji</p>
    </div>
</div>

<script>
function toggleAnswers() {
    const answers = document.getElementById("answers");
    if (answers.style.display === "none") {
        answers.style.display = "block";
    } else {
        answers.style.display = "none";
    }
}
</script>

</body>
</html># TRIGONOMETRIJA
Šiame puslapyje galėsite pakartoti pagrindines trigonometrijos sąvokas ir įgūdžius. Trigonometrija nagrinėja kampų ir trikampių kraštinių tarpusavio ryšiu
