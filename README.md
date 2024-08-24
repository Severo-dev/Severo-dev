<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Advocacia [Seu Nome]</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
            color: #333;
        }
        header {
            background-color: #00264d;
            color: white;
            padding: 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #004080;
            padding: 10px;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
        }
        section {
            padding: 20px;
            max-width: 1200px;
            margin: auto;
        }
        h2 {
            color: #00264d;
        }
        footer {
            background-color: #00264d;
            color: white;
            text-align: center;
            padding: 20px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        .contact-form {
            background-color: #e6e6e6;
            padding: 20px;
            border-radius: 5px;
        }
        .contact-form input, .contact-form textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        .contact-form button {
            background-color: #004080;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        .contact-form button:hover {
            background-color: #00264d;
        }
    </style>
</head>
<body>

<header>
    <h1>Advocacia [Seu Nome]</h1>
</header>

<nav>
    <a href="#about">Sobre</a>
    <a href="#services">Serviços</a>
    <a href="#testimonials">Depoimentos</a>
    <a href="#contact">Contato</a>
</nav>

<section id="about">
    <h2>Sobre Mim</h2>
    <p>Sou advogado especializado em [Suas Áreas de Especialização], com experiência em [Resumo da Experiência]. Estou comprometido em oferecer serviços jurídicos de alta qualidade e soluções eficientes para meus clientes.</p>
</section>

<section id="services">
    <h2>Serviços</h2>
    <ul>
        <li>[Serviço 1]</li>
        <li>[Serviço 2]</li>
        <li>[Serviço 3]</li>
        <li>[Serviço 4]</li>
    </ul>
</section>

<section id="testimonials">
    <h2>Depoimentos</h2>
    <p>"[Depoimento de um Cliente]"</p>
    <p>"[Depoimento de outro Cliente]"</p>
</section>

<section id="contact">
    <h2>Contato</h2>
    <div class="contact-form">
        <form action="#" method="post">
            <label for="name">Nome:</label>
            <input type="text" id="name" name="name" required>

            <label for="email">E-mail:</label>
            <input type="email" id="email" name="email" required>

            <label for="message">Mensagem:</label>
            <textarea id="message" name="message" rows="5" required></textarea>

            <button type="submit">Enviar</button>
        </form>
    </div>
</section>

<footer>
    <p>&copy; 2024 Advocacia [Seu Nome] | <a href="https://www.linkedin.com" style="color:white;">LinkedIn</a> | <a href="https://www.twitter.com" style="color:white;">Twitter</a></p>
</footer>

</body>
</html>
