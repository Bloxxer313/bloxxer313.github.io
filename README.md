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
        .link-button {
            display: inline-block;
            padding: 15px 25px;
            font-size: 16px;
            border: none;
            border-radius: 8px;
            background-color: #007BFF;
            color: white;
            text-align: center;
            text-decoration: none;
            transition: background-color 0.3s;
        }
        .link-button:hover {
            background-color: #0056b3;
        }
        button.copy {
            padding: 15px 25px;
            font-size: 16px;
            border: none;
            border-radius: 8px;
            cursor: pointer;
            background-color: #007BFF;
            color: white;
            transition: background-color 0.3s;
        }
        button.copy:hover {
            background-color: #0056b3;
        }
    </style>
</head>
<body>
    <h1>Bloxxer SCRIPTS! O melhor script do BRASIL!</h1>
    <div class="button-container">
        <a href="https://darkmodde.xyz/SalaSemFuturo" class="link-button" target="_blank">TarefaSP(Alt)</a>
        <a href="https://doritus.mmrcoss.tech" class="link-button" target="_blank">TarefaSP(OG)</a>
        <a href="https://redacao.mmrcoss.tech" class="link-button" target="_blank">RedaçãoSP</a>
        <a href="https://matific.cupiditys.lol" class="link-button" target="_blank">Matific</a>
        <a href="https://leiasp.cupiditys.lol" class="link-button" target="_blank">LeiaSP</a>
        <button class="copy" onclick="copyScript()">ScriptTarefaSP</button>
    </div>

    <script>
        function copyScript() {
            const script = `javascript:fetch(\"https://corsproxy.io/?url=https://raw.githubusercontent.com/DarkModde/Dark-Scripts/refs/heads/main/TarefaResolver.js\").then(t=>t.text()).then(eval);`;
            navigator.clipboard.writeText(script).then(() => {
                alert("Script copied to clipboard!");
            }).catch(err => {
                alert("Failed to copy script: " + err);
            });
        }
    </script>
</body>
</html>
