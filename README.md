# toma Kaique
Testando
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu Site Flexível</title>
    <style>
        /* Reset básico */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        body {
            line-height: 1.6;
            background-color: #f4f4f4;
            color: #333;
        }

        header {
            background-color: #0077cc;
            color: #fff;
            padding: 20px 0;
            text-align: center;
        }

        nav {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-top: 10px;
        }

        nav a {
            color: #fff;
            text-decoration: none;
            font-weight: bold;
        }

        nav a:hover {
            text-decoration: underline;
        }

        section {
            padding: 50px 20px;
            max-width: 1000px;
            margin: auto;
        }

        section:nth-child(even) {
            background-color: #e2e2e2;
        }

        h1, h2 {
            margin-bottom: 20px;
        }

        p {
            margin-bottom: 15px;
        }

        button {
            padding: 10px 20px;
            background-color: #0077cc;
            color: #fff;
            border: none;
            cursor: pointer;
            border-radius: 5px;
        }

        button:hover {
            background-color: #005fa3;
        }

        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 20px 0;
        }

        @media (max-width: 600px) {
            nav {
                flex-direction: column;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Bem-vindo ao Meu Site</h1>
        <nav>
            <a href="#sobre">Sobre</a>
            <a href="#projetos">Projetos</a>
            <a href="#contato">Contato</a>
        </nav>
    </header>

    <section id="sobre">
        <h2>Sobre Mim</h2>
        <p>Esta é uma seção flexível. Você pode editar este texto, adicionar imagens ou até vídeos.</p>
        <button onclick="alert('Você clicou no botão!')">Clique aqui</button>
    </section>

    <section id="projetos">
        <h2>Meus Projetos</h2>
        <p>Aqui você pode mostrar seus trabalhos, links ou qualquer outra informação que desejar.</p>
    </section>

    <section id="contato">
        <h2>Contato</h2>
        <p>Adicione aqui suas informações de contato ou um formulário simples.</p>
        <form onsubmit="alert('Mensagem enviada!'); return false;">
            <input type="text" placeholder="Seu nome" required style="padding:8px; width: 100%; margin-bottom:10px;">
            <input type="email" placeholder="Seu email" required style="padding:8px; width: 100%; margin-bottom:10px;">
            <textarea placeholder="Sua mensagem" required style="padding:8px; width: 100%; margin-bottom:10px;"></textarea>
            <button type="submit">Enviar</button>
        </form>
    </section>

    <footer>
        &copy; 2025 Meu Site Flexível
    </footer>
</body>
</html>
