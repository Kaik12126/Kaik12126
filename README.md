<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Minha Loja Online</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            color: #333;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #FF5733;
            color: white;
            padding: 20px;
            text-align: center;
        }
        nav {
            background-color: #333;
            overflow: hidden;
        }
        nav a {
            float: left;
            display: block;
            color: white;
            text-align: center;
            padding: 14px 20px;
            text-decoration: none;
        }
        nav a:hover {
            background-color: #FF5733;
            color: white;
        }
        section {
            padding: 20px;
        }
        .products {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
        }
        .product {
            background-color: white;
            border: 1px solid #ddd;
            margin: 10px;
            padding: 10px;
            width: 300px;
            text-align: center;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Bem-vindo à Minha Loja Online!</h1>
        <p>Os melhores produtos para você, direto da internet.</p>
    </header>
    <nav>
        <a href="#inicio">Início</a>
        <a href="#produtos">Produtos</a>
        <a href="#como-comprar">Como Comprar</a>
        <a href="#contato">Contato</a>
    </nav>
    <section id="inicio">
        <h2>Sobre a Minha Loja</h2>
        <p>Oferecemos uma seleção exclusiva de produtos de alta qualidade. Confira nossa coleção abaixo e aproveite as melhores ofertas!</p>
    </section>
    <section id="produtos" class="products">
        <h2>Nossos Produtos</h2>
        <div class="product">
            <h3>Produto 1</h3>
            <img src="imagem_produto1.jpg" alt="Produto 1" style="width:100%;">
            <p>Descrição incrível do Produto 1. Ele faz isso, aquilo e mais!</p>
            <p><strong>Preço: R$99,99</strong></p>
        </div>
        <div class="product">
            <h3>Produto 2</h3>
            <img src="imagem_produto2.jpg" alt="Produto 2" style="width:100%;">
            <p>Descrição incrível do Produto 2. Ele faz isso, aquilo e mais!</p>
            <p><strong>Preço: R$149,99</strong></p>
        </div>
        <!-- Adicione mais produtos aqui -->
    </section>
    <section id="como-comprar">
        <h2>Como Comprar</h2>
        <p>Para comprar, entre em contato através das informações abaixo ou clique no link direto para nossa loja online. Oferecemos diferentes métodos de pagamento e entrega rápida em todo o Brasil.</p>
    </section>
    <section id="contato">
        <h2>Contato</h2>
        <p>Email: <a href="mailto:contato@minhaloja.com">contato@minhaloja.com</a></p>
        <p>Telefone: (XX) XXXX-XXXX</p>
    </section>
    <footer>
        <p>&copy; 2024 Minha Loja Online. Todos os direitos reservados.</p>
    </footer>
</body>
</html>
