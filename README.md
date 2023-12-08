<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PokéAPI - README</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            line-height: 1.6;
            margin: 20px;
        }

        h1 {
            color: #E44D26;
        }

        h2 {
            color: #3498db;
        }

        h3 {
            color: #2ecc71;
        }

        p {
            color: #333;
        }

        code {
            background-color: #f8f9fa;
            padding: 2px 5px;
            border: 1px solid #ced4da;
            border-radius: 4px;
        }

        a {
            color: #2980b9;
            text-decoration: none;
        }

        a:hover {
            text-decoration: underline;
        }
    </style>
</head>

<body>
    <h1>PokéAPI</h1>

    <p>Bem-vindo à PokéAPI, sua fonte definitiva para informações abrangentes sobre Pokémon! Esta API foi desenvolvida para fornecer acesso fácil e eficiente a dados sobre Pokémon, incluindo detalhes sobre espécies, tipos, habilidades, movimentos e muito mais.</p>

    <h2>Visão Geral</h2>

    <p>A PokéAPI é uma RESTful API projetada para ser intuitiva e flexível. Ela fornece dados detalhados sobre todos os Pokémon conhecidos, permitindo que desenvolvedores criem aplicativos, jogos e serviços relacionados ao universo Pokémon.</p>

    <h2>Recursos Principais</h2>

    <h3>1. Informações sobre Pokémon</h3>

    <ul>
        <li><strong>Detalhes da Espécie:</strong> Obtenha dados abrangentes sobre cada Pokémon, incluindo altura, peso, tipos, habilidades e estatísticas base.</li>
        <li><strong>Imagens:</strong> Acesse imagens oficiais de cada Pokémon para uso em seu aplicativo.</li>
    </ul>

    <h3>2. Tipos e Habilidades</h3>

    <ul>
        <li><strong>Tipos de Pokémon:</strong> Explore a tabela de tipos para entender as relações de vantagem e desvantagem entre diferentes tipos de Pokémon.</li>
        <li><strong>Habilidades:</strong> Descubra informações sobre as habilidades especiais de Pokémon que podem influenciar batalhas.</li>
    </ul>

    <h3>3. Movimentos</h3>

    <ul>
        <li><strong>Detalhes de Movimentos:</strong> Acesse informações sobre os movimentos de cada Pokémon, incluindo poder, precisão e efeitos especiais.</li>
        <li><strong>Categorias de Movimentos:</strong> Descubra a categoria de cada movimento, como ataque, defesa, status, etc.</li>
    </ul>

    <h2>Como Usar</h2>

    <p>Endpoint Base:</p>

    <code>https://pokeapi.example.com/v1</code>

    <p>Exemplos de Chamadas:</p>

    <ul>
        <li><strong>Detalhes do Pokémon por ID:</strong> <code>GET /pokemon/25</code></li>
        <li><strong>Detalhes do Movimento por ID:</strong> <code>GET /move/15</code></li>
        <li><strong>Lista de Tipos de Pokémon:</strong> <code>GET /types</code></li>
    </ul>

    <p>Consulte a <a href="https://pokeapi.example.com/docs">documentação completa</a> para obter detalhes sobre todos os endpoints disponíveis.</p>

    <h2>Autenticação</h2>

    <p>Atualmente, a PokéAPI é de acesso público e não requer autenticação. No entanto, para fins de monitoramento e controle de acesso, recomendamos que os desenvolvedores registrem suas aplicações e usem uma chave de API.</p>

    <h2>Contribuições</h2>

    <p>A PokéAPI é um projeto de código aberto e aceita contribuições da comunidade. Se você encontrar problemas ou quiser adicionar recursos, sinta-se à vontade para enviar um pull request para nosso <a href="https://github.com/pokeapi">repositório no GitHub</a>.</p>

    <h2>Suporte</h2>

    <p>Para obter suporte ou relatar problemas, entre em contato conosco através do nosso <a href="https://pokeapi.example.com/forum">fórum de discussão</a>.</p>

    <p>Aproveite a PokéAPI e continue explorando o incrível mundo dos Pokémon!</p>
</body>

</html>
