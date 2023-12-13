<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Convite Especial</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #f4f4f4;
            text-align: center;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #333;
            color: #fff;
            padding: 1em;
        }

        section {
            margin: 2em;
        }

        button {
            background-color: #4CAF50;
            color: #fff;
            padding: 10px 20px;
            font-size: 16px;
            border: none;
            cursor: pointer;
            margin: 0 10px;
        }

        button:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>

    <header>
        <h1>Convite Especial</h1>
    </header>

    <section>
        <h2>Olá Mayara,</h2>
        <p>Gostaria de sair comigo?</p>

        <button onclick="responderConvite('sim')">Sim</button>
        <button onclick="responderConvite('nao')">Não</button>

        <div id="resposta"></div>

        <script>
            function responderConvite(resposta) {
                var respostaDiv = document.getElementById('resposta');

                if (resposta === 'sim') {
                    respostaDiv.innerHTML = '<p>Ótimo! Aguardo ansiosamente pelo nosso encontro.</p>';
                } else if (resposta === 'nao') {
                    respostaDiv.innerHTML = '<p>Tudo bem, talvez em outra ocasião. 😊</p>';
                }
            }
        </script>
    </section>

</body>
</html>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
