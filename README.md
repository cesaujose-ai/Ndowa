<!DOCTYPE html>
<html lang="pt">
<head>
    <meta charset="UTF-8">
    <title>Minha Primeira Página</title>
    <style>
        /* ===== Estilo Geral ===== */
        body {
            background-color: #f0f0f0;
            font-family: Arial, sans-serif;
            color: #333;
            padding: 20px;
            margin: 0;
        }

        /* Título principal */
        h1 {
            color: #1E90FF;
            font-size: 36px;
            text-align: center;
            margin-bottom: 20px;
        }

        /* Subtítulos */
        h2 {
            color: #FF8C00;
            margin-top: 30px;
            margin-bottom: 10px;
        }

        /* Parágrafos */
        p {
            color: #555;
            font-size: 18px;
            line-height: 1.6;
        }

        /* Listas */
        ul li, ol li {
            color: #4B0082;
            margin-bottom: 5px;
        }

        /* Links */
        a {
            color: #008000;
            text-decoration: none;
            font-weight: bold;
        }

        a:hover {
            color: #FF0000;
        }

        /* Imagem */
        img {
            border: 3px solid #1E90FF;
            border-radius: 10px;
            display: block;
            margin: 10px 0;
            max-width: 100%;
        }

        /* Botão */
        button {
            background-color: #1E90FF;
            color: white;
            border: none;
            padding: 10px 20px;
            border-radius: 8px;
            cursor: pointer;
            font-size: 16px;
            margin-top: 15px;
        }

        button:hover {
            background-color: #104E8B;
        }
    </style>
</head>
<body>
    <h1>Olá, eu sou Esaú!</h1>

    <h2>Sobre mim</h2>
    <p>Eu estou aprendendo HTML, CSS e JavaScript e quero criar páginas incríveis para a internet.</p>

    <h2>Coisas que gosto:</h2>
    <ul>
        <li>Design gráfico</li>
        <li>Vestir bem</li>
        <li>Programação web</li>
    </ul>

    <h2>Minha rotina de aprendizado:</h2>
    <ol>
        <li>Estudar HTML</li>
        <li>Praticar CSS</li>
        <li>Explorar JavaScript</li>
    </ol>

    <p>Quer aprender junto comigo? Visite <a href="https://www.devpratico.com/" target="_blank">este site de estudos</a>.</p>

    <h2>Minha imagem favorita</h2>
    <img src="https://via.placeholder.com/300" alt="Exemplo de imagem">

    <p>Aprender HTML é <strong>importante</strong> e também <em>divertido</em>!</p>

    <!-- Botão com JavaScript -->
    <button onclick="mostrarMensagem()">Clique aqui para uma surpresa!</button>

    <script>
        // Função simples em JavaScript
        function mostrarMensagem() {
            alert("Parabéns! Você está aprendendo HTML, CSS e JavaScript 😎");
        }
    </script>
</body>
</html>
