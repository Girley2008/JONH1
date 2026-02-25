<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Laboratório Web</title>

    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f2f5;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #1f4e79;
            color: white;
            padding: 15px;
            text-align: center;
        }

        main {
            padding: 20px;
        }

        .card {
            background-color: white;
            padding: 15px;
            margin-bottom: 15px;
            border-radius: 8px;
            box-shadow: 0 0 5px rgba(0,0,0,0.2);
        }

        img {
            width: 200px;
            border-radius: 8px;
        }

        a {
            color: #1f4e79;
            text-decoration: none;
            font-weight: bold;
        }

        a:hover {
            color: red;
        }

        button {
            background-color: #1f4e79;
            color: white;
            border: none;
            padding: 10px;
            border-radius: 5px;
            cursor: pointer;
        }

        button:hover {
            background-color: #163a5c;
        }

        footer {
            background-color: #1f4e79;
            color: white;
            text-align: center;
            padding: 10px;
        }
    </style>

</head>
<body>

<header>
    <h1>Laboratório Web</h1>
    <p>Exemplo de página com HTML e CSS</p>
</header>

<main>

    <div class="card">
        <h2>Sobre o aluno</h2>
        <p>Nome: ______</p>
        <p>Turma: ______</p>
        <p>Data: __ / __ / __</p>
    </div>

    <div class="card">
        <h2>Conteúdos aprendidos</h2>
        <ul>
            <li>Estrutura de páginas web</li>
            <li>Criação de sites</li>
            <li>Uso de imagens e links</li>
            <li>Estilização com CSS</li>
        </ul>
    </div>

    <div class="card">
        <h2>Imagem de exemplo</h2>
        <img src="https://via.placeholder.com/200">
    </div>

    <div class="card">
        <h2>Link de exemplo</h2>
        <p>
            <a href="https://www.google.com" target="_blank">
                Abrir o Google
            </a>
        </p>
    </div>

    <div class="card">
        <h2>Interação</h2>
        <button onclick="mostrarMensagem()">Clique aqui</button>
        <p id="mensagem"></p>
    </div>

</main>

<footer>
    Página criada no Laboratório Web
</footer>

<script>
    function mostrarMensagem() {
        document.getElementById("mensagem").innerHTML =
        "Parabéns! Você executou um comando usando JavaScript.";
    }
</script>

</body>
</html>