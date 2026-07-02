# web2.2
<!DOCTYPE html>
<html>

<head>
    <title>Mundial 2026</title>

    <style>
        body {
            background-color: #e0f7fa;
            text-align: center;
            font-family: Arial, sans-serif;
        }

        h1 {
            color: #8b0000;
        }

        .botao {
            background-color: #006600;
            color: white;
            padding: 10px;
            font-size: 16px;
            border-radius: 5px;
            cursor: pointer;
            margin: 5px;
        }
    </style>
</head>

<body>

    <h1>Mundial 2026</h1>

    <p id="mensagem">Bem-vindo ao jogo!</p>

    <h2>Golos de Portugal: <span id="numero-golos">0</span></h2>

    <button class="botao" onclick="mostrarAlerta()">Aviso</button>

    <button class="botao" onclick="marcarGolo()">Golo!</button>

    <button class="botao" onclick="terminarJogo()">Fim do Jogo</button>

    <button class="botao" onclick="animarTorcida()">Animar Torcida</button>

    <button class="botao" onclick="modoEscuro()">Modo Escuro</button>

    <script>

        var totalGolos = 0;

        function mostrarAlerta() {
            alert("O jogo vai começar!");
        }

        function marcarGolo() {
            totalGolos = totalGolos + 1;
            document.getElementById("numero-golos").innerHTML = totalGolos;
        }

        function terminarJogo() {
            alert("O jogo terminou! Grande partida!");
        }

        function animarTorcida() {
            document.getElementById("mensagem").innerHTML =
                "Força Portugal! Rumo à vitória!";
        }

        function modoEscuro() {
            document.body.style.backgroundColor = "black";
            document.body.style.color = "white";
        }

    </script>

</body>

</html>
