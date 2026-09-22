# Loja-de-Lanches-Saud-veis
É uma empresa ,para vende lanche naturais e alimentos saudável ,oferece uma opção de alimentação rápido e saudáveis para pessoas que tem pouco tempo. 
<!DOCTYPE html>
<html lang="pt-BR">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Loja de Lanches Saudáveis</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        body {
            background-color: #f5fff5;
            color: #333;
        }

        header {
            background-color: #2e7d32;
            color: white;
            padding: 25px;
            text-align: center;
        }

        header h1 {
            font-size: 32px;
            margin-bottom: 10px;
        }

        nav {
            background-color: #1b5e20;
            padding: 12px;
            text-align: center;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }

        .banner {
            text-align: center;
            padding: 40px 20px;
            background-color: #e8f5e9;
        }

        .banner img {
            width: 80%;
            max-width: 700px;
            border-radius: 15px;
            margin-bottom: 25px;
        }

        .banner h2 {
            color: #2e7d32;
            font-size: 30px;
            margin-bottom: 15px;
        }

        .banner p {
            font-size: 18px;
            margin-bottom: 25px;
        }

        .botao {
            display: inline-block;
            background-color: #43a047;
            color: white;
            padding: 12px 25px;
            border-radius: 8px;
            text-decoration: none;
            font-weight: bold;
        }

        .produtos {
            padding: 40px 20px;
            text-align: center;
        }

        .produtos h2 {
            color: #2e7d32;
            margin-bottom: 30px;
            font-size: 28px;
        }

        .cards {
            display: flex;
            justify-content: center;
            gap: 25px;
            flex-wrap: wrap;
        }

        .card {
            background-color: white;
            width: 280px;
            padding: 25px;
            border-radius: 12px;
            box-shadow: 0 3px 10px rgba(0,0,0,0.12);
        }

        .card h3 {
            color: #2e7d32;
            margin-bottom: 12px;
        }

        .card p {
            margin-bottom: 15px;
            line-height: 1.5;
        }

        .preco {
            font-size: 20px;
            font-weight: bold;
            color: #1b5e20;
        }

        .sobre {
            background-color: #e8f5e9;
            padding: 40px 20px;
            text-align: center;
        }

        .sobre h2 {
            color: #2e7d32;
            margin-bottom: 15px;
        }

        .sobre p {
            max-width: 700px;
            margin: auto;
            line-height: 1.6;
        }

        footer {
            background-color: #1b5e20;
            color: white;
            text-align: center;
            padding: 20px;
        }
    </style>
</head>

<body>

    <header>
        <h1>🥗 Loja de Lanches Saudáveis</h1>
        <p>Sabor, saúde e qualidade em cada mordida!</p>
    </header>

    <nav>
        <a href="#inicio">Início</a>
        <a href="#produtos">Produtos</a>
        <a href="#sobre">Sobre nós</a>
        <a href="#contato">Contato</a>
    </nav>

    <section class="banner" id="inicio">

        <img src="image_c8e55c.jpg" alt="Lanches saudáveis">

        <h2>Alimente seu corpo com saúde!</h2>

        <p>
            Lanches deliciosos, naturais e preparados
            para deixar seu dia mais saudável.
        </p>

        <a href="#produtos" class="botao">
            Ver nossos produtos
        </a>

    </section>

    <section class="produtos" id="produtos">

        <h2>Nossos Lanches</h2>

        <div class="cards">

            <div class="card">
                <h3>🥪 Sanduíche Natural</h3>

                <p>
                    Pão integral, frango desfiado,
                    alface, tomate e ingredientes frescos.
                </p>

                <p class="preco">R$ 12,00</p>
            </div>

            <div class="card">
                <h3>🍓 Iogurte com Frutas</h3>

                <p>
                    Iogurte natural com frutas frescas
                    e granola.
                </p>

                <p class="preco">R$ 10,00</p>
            </div>

            <div class="card">
                <h3>🍌 Smoothie Natural</h3>

                <p>
                    Bebida preparada com frutas naturais
                    e ingredientes selecionados.
                </p>

                <p class="preco">R$ 11,00</p>
            </div>

            <div class="card">
                <h3>🥗 Salada de Frutas</h3>

                <p>
                    Combinação deliciosa de frutas
                    frescas para qualquer momento do dia.
                </p>

                <p class="preco">R$ 9,00</p>
            </div>

        </div>

    </section>

    <section class="sobre" id="sobre">

        <h2>Sobre Nós</h2>

        <p>
            Nossa loja nasceu com o objetivo de oferecer
            opções de lanches saborosos e mais saudáveis.
            Trabalhamos com ingredientes frescos e buscamos
            oferecer qualidade e praticidade para nossos clientes.
        </p>

    </section>

    <section class="sobre" id="contato">

        <h2>Entre em Contato</h2>

        <p>
            📱 WhatsApp: (00) 00000-0000
        </p>

        <p>
            📧 E-mail: contato@lanchessaudaveis.com
        </p>

    </section>

    <footer>
        <p>
            © 2026 Loja de Lanches Saudáveis
        </p>
    </footer>

</body>

</html>
