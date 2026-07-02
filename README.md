
<!DOCTYPE html>
<html>

<head>
    <title>Mundial 2026</title>

   <style>
        body {
            background-color: #45A14E;
            text-align: center;
            font-family: Arial, sans-serif;
        }

        h1 {
            color: #black;
        }

        .botao {
            background-color: #FBFF47;
            color: black;
            padding: 10px;
            font-size: 16px;
            border-radius: 5px;
            cursor: pointer;
            margin: 5px;
        }
    </style>
</head>

<body>
    <h1>Copa do mundo 2026</h1>

   <p id="mensagem">Bem-vindo ao jogo!</p>

  <h2>Gols do Brasil: <span id="numero-golos">0</span></h2>
   <button class="botao" onclick="mostrarAlerta()">Aviso</button>

   <button class="botao" onclick="marcarGolo()">Gol!</button>

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
                "Força Brasil! Rumo ao HEXA!";
        }

        function modoEscuro() {
            document.body.style.backgroundColor = "black";
            document.body.style.color = "white";
        }

 
    </script>
<center> <img src="https://www.flagstaffarizona.org/imager/s3-us-west-1_amazonaws_com/flagstaff-2018/craft/Languages/Flag_of_Brazil_694f32bf0e9ef81016789076834d1a45.png" alt="VAI BRASIL!!!"></center>
 
 
</body>

</html>
