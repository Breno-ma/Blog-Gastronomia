<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rumo ao Mundo</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
            color: #333;
        }
        header {
            background-color: #0077b6;
            color: white;
            padding: 20px 0;
            text-align: center;
        }
        nav {
            background-color: #023e8a;
            text-align: center;
            padding: 10px 0;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
        }
        nav a:hover {
            text-decoration: underline;
        }
        main {
            padding: 20px;
            text-align: center;
        }
        .destaque {
            display: flex;
            justify-content: center;
            gap: 20px;
            flex-wrap: wrap;
            margin-top: 20px;
        }
        .destaque div {
            border: 1px solid #ddd;
            border-radius: 10px;
            overflow: hidden;
            width: 250px;
            background-color: white;
        }
        .destaque img {
            width: 100%;
            height: auto;
        }
        .destaque p {
            margin: 10px 0;
            padding: 0 10px;
        }
        footer {
            background-color: #023e8a;
            color: white;
            text-align: center;
            padding: 10px 0;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Rumo ao Mundo</h1>
        <p>Explorando o mundo um destino por vez</p>
    </header>
    <nav>
        <a href="index.html">Home</a>
        <a href="destinos.html">Destinos Incríveis</a>
        <a href="dicas.html">Dicas de Planejamento</a>
        <a href="experiencias.html">Experiências de Viagem</a>
        <a href="curiosidades.html">Curiosidades Culturais</a>
        <a href="contatos.html">Contatos</a>
    </nav>
    <main>
        <h2>Descubra, Explore, Viva!</h2>
        <p>Bem-vindo ao blog **Rumo ao Mundo**, sua fonte de inspiração para viagens. Aqui você encontrará dicas, histórias e informações para tornar sua próxima viagem inesquecível.</p>
        <section class="destaque">
            <div>
                <a href="destinos.html">
                    <img src="destinos.jpg" alt="Destinos Incríveis">
                    <p>Descubra lugares fascinantes ao redor do mundo.</p>
                </a>
            </div>
            <div>
                <a href="dicas.html">
                    <img src="dicas.jpg" alt="Dicas de Planejamento">
                    <p>Planeje sua viagem com eficiência.</p>
                </a>
            </div>
            <div>
                <a href="experiencias.html">
                    <img src="experiencias.jpg" alt="Experiências de Viagem">
                    <p>Leia relatos de aventuras inesquecíveis.</p>
                </a>
            </div>
            <div>
                <a href="curiosidades.html">
                    <img src="curiosidades.jpg" alt="Curiosidades Culturais">
                    <p>Conheça tradições e costumes ao redor do mundo.</p>
                </a>
            </div>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Rumo ao Mundo. Todos os direitos reservados.</p>
    </footer>
</body>
</html>
