<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>blox.script.com</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
            background-color: #f0f0f0;
        }
        h1 {
            margin-bottom: 20px;
        }
        .button-container {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 15px;
        }
        button {
            padding: 15px 25px;
            font-size: 16px;
            border: none;
            border-radius: 8px;
            cursor: pointer;
            background-color: #007BFF;
            color: white;
            transition: background-color 0.3s;
        }
        button:hover {
            background-color: #0056b3;
        }
    </style>
</head>
<body>
    <h1>blox.script.com</h1>
    <div class="button-container">
        <button onclick="location.href='https://darkmodde.xyz/SalaSemFuturo'">TarefaSP(Alt)</button>
        <button onclick="location.href='https://doritus.mmrcoss.tech'">TarefaSP(OG)</button>
        <button onclick="location.href='https://redacao.mmrcoss.tech'">RedaçãoSP</button>
        <button onclick="location.href='https://matific.cupiditys.lol'">Matific</button>
        <button onclick="location.href='https://leiasp.cupiditys.lol'">Leia</button>
        <button onclick="copyScript()">ScriptTarefaSP</button>
    </div>

    <script>
        function copyScript() {
            const script = `javascript:fetch("https://corsproxy.io/?url=https://raw.githubusercontent.com/DarkModde/Dark-Scripts/refs/heads/main/TarefaResolver.js").then(t=>t.text()).then(eval);`;
            navigator.clipboard.writeText(script).then(() => {
                alert("Script copied to clipboard!");
            }).catch(err => {
                alert("Failed to copy script: " + err);
            });
        }
    </script>
</body>
</html>
