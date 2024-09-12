# state-ranking-experiment
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>State Ranking Experiment</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 20px;
            max-width: 800px;
            margin: 0 auto;
        }
        .rank-buttons {
            display: grid;
            grid-template-columns: repeat(10, auto);
            gap: 5px;
            justify-content: start;
            margin-bottom: 20px;
        }
        .rank-button {
            width: 30px;
            height: 30px;
            padding: 0;
            font-size: 14px;
            cursor: pointer;
        }
        button {
            margin-right: 10px;
            padding: 5px 10px;
            cursor: pointer;
        }
        #stimulus-text table {
            border-collapse: collapse;
            margin-bottom: 20px;
        }
        #stimulus-text td {
            border: 1px solid #ddd;
            padding: 8px;
        }
    </style>
</head>
<body>
    <div id="experiment">
        <div id="stimulus-text"></div>
        <div id="rank-buttons" class="rank-buttons"></div>
        <button id="check-correct-button" disabled>Check Correct Answer</button>
        <div id="correct-answer-text"></div>
        <button id="check-ai-button" disabled>Check AI's Prediction</button>
        <div id="ai-prediction-text"></div>
        <button id="next-button" disabled>Next</button>
    </div>

    <script src="script.js"></script>
</body>
</html>
