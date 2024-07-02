<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>História de um Jogador Universitário</title>
    <style>
        /* Estilos gerais */
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }

        .container {
            width: 300px; /* Largura dos quadrados */
            height: 400px; /* Altura dos quadrados */
            margin: 20px;
            padding: 20px;
            background-color: #fff;
            border: 1px solid #ccc;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
            text-align: center;
            display: flex;
            flex-direction: column;
            justify-content: center; /* Centraliza conteúdo verticalmente */
            animation: fadeIn 1s ease-out;
        }

        @keyframes fadeIn {
            0% {
                opacity: 0;
                transform: translateY(-20px);
            }
            100% {
                opacity: 1;
                transform: translateY(0);
            }
        }

        header {
            background-color: #333;
            color: #fff;
            padding: 10px 0;
            text-align: center;
            width: 100%;
        }

        header h1 {
            margin: 0;
            padding: 10px 0;
            font-weight: bold;
        }

        nav ul {
            list-style-type: none;
            padding: 0;
            text-align: center;
        }

        nav ul li {
            display: inline;
            margin-right: 20px;
        }

        nav ul li a {
            color: #fff;
            text-decoration: none;
            font-weight: bold;
        }

        nav ul li a:hover {
            text-decoration: underline;
        }

        section {
            width: 100%;
            padding: 20px;
            flex-grow: 1;
            display: flex;
            flex-direction: column;
            justify-content: center; /* Centraliza conteúdo verticalmente */
            text-align: center;
        }

        section h2 {
            margin-top: 0;
        }

        section img {
            max-width: 100%;
            height: auto;
            margin-bottom: 20px;
        }

        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px 0;
            width: 100%;
        }

        footer p {
            margin: 0;
        }

        /* Responsividade */
        @media (max-width: 768px) {
            .container {
                width: 90%; /* Largura dos quadrados em dispositivos menores */
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>História de um Jogador Universitário</h1>
            <nav>
                <ul>
                    <li><a href="#biografia">Biografia</a></li>
                    <li><a href="#conquistas">Conquistas</a></li>
                    <li><a href="#contato">Contato</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section id="biografia" class="container">
        <h2>Biografia</h2>
        <a href="https://ibb.co/dQZQpFc"><img src="https://i.ibb.co/vJ9JdpB/Ka-que-Vargas.jpg" alt="Ka-que-Vargas" border="0"></a>
        <p>Kaíque Vargas sempre amou futebol desde criança e dentro da Atlética Raposa conseguiu mostrar seu futebol e ser campeões de diversos campeonatos.</p>
    </section>

    <section id="conquistas" class="container">
        <h2>Conquistas</h2>
        <p>Engenhariadas Paranaense, Taça Universitária de Toledo, Quadrangular de Palotina, Joia Oeste, Copa Inter Atléticas.</p>
    </section>

    <section id="contato" class="container">
        <h2>Contato</h2>
        <p>Rede social: Instagram: vargasbfr.</p>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2024 História de um Jogador Universitário. Todos os direitos reservados.</p>
        </div>
    </footer>
</body>
</html>
