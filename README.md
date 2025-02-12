# aperfblog
Aperfeiçoamento do Blog com CSS
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Blog Simples</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background: #333;
            color: #fff;
            padding: 15px;
            text-align: center;
        }
        nav ul {
            list-style: none;
            padding: 0;
        }
        nav ul li {
            display: inline;
            margin: 0 10px;
        }
        nav ul li a {
            color: #fff;
            text-decoration: none;
        }
        main {
            width: 80%;
            margin: 20px auto;
            padding: 20px;
            background: #fff;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        article {
            margin-bottom: 20px;
        }
        .date {
            color: gray;
            font-size: 0.9em;
        }
        footer {
            text-align: center;
            padding: 15px;
            background: #333;
            color: #fff;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Meu Blog</h1>
        <nav>
            <ul>
                <li><a href="#">Início</a></li>
                <li><a href="#">Sobre</a></li>
                <li><a href="#">Contato</a></li>
            </ul>
        </nav>
    </header>
    
    <main>
        <article>
            <h2>Título do Post</h2>
            <p class="date">Publicado em 12 de fevereiro de 2025</p>
            <p>Este é um exemplo de post no blog. Aqui você pode escrever sobre diversos temas e compartilhar conhecimento.</p>
            <a href="#">Leia mais...</a>
        </article>
    </main>
    
    <footer>
        <p>&copy; 2025 Meu Blog. Todos os direitos reservados.</p>
    </footer>
</body>
</html>
