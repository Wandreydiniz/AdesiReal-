# AdesiReal👑 
# Seja Bem Vindo!!
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AdesiReal</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            color: white; /* Texto branco */
            overflow-y: auto; /* Permite rolagem vertical */
            height: 100vh;
            display: flex;
            flex-direction: column;
        }
        .background {
            position: fixed; /* Mantém o fundo fixo */
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(255, 255, 255, 0.2); /* Tom branco com opacidade */
            filter: blur(8px) brightness(0.8); /* Ajusta o filtro para um efeito mais cinza claro */
            z-index: -1; /* Garante que o fundo esteja atrás do conteúdo */
        }
        .header {
            position: relative;
            z-index: 2;
            display: flex;
            align-items: center;
            padding: 20px 40px;
            background-color: transparent; /* Fundo transparente para manter o efeito de água */
            box-shadow: none; /* Remove a sombra */
        }
        h1 {
            color: white; /* Texto branco */
            font-size: 2.5em;
            margin: 0;
            font-weight: bold;
            text-shadow: 0 0 10px rgba(0, 0, 0, 0.5); /* Sombra para destacar o texto */
        }
        .search-bar {
            margin-left: auto;
            max-width: 400px;
            width: 100%;
        }
        .search-bar input[type="text"] {
            width: 100%;
            padding: 12px;
            border: 1px solid #ddd;
            border-radius: 50px;
            font-size: 1em;
            box-shadow: inset 0 2px 4px rgba(0, 0, 0, 0.1);
            transition: all 0.3s ease;
        }
        .search-bar input[type="text"]:focus {
            border-color: #7B1FA2;
            outline: none;
            box-shadow: 0 0 8px rgba(123, 31, 162, 0.2);
        }
        .content {
            position: relative;
            z-index: 2;
            padding: 40px;
            flex: 1; /* Permite que o conteúdo ocupe o espaço disponível e permita rolagem */
        }
        .category-container {
            margin-bottom: 40px;
        }
        .category-title {
            font-size: 2em;
            margin-bottom: 10px;
            color: #7B1FA2; /* Cor das categorias */
            font-weight: bold;
            text-shadow: 0 0 8px rgba(0, 0, 0, 0.4); /* Sombra para destacar o texto */
        }
        .gallery-container {
            overflow-x: auto; /* Permite rolar horizontalmente */
            padding: 10px 0;
            white-space: nowrap; /* Mantém os itens em linha */
            display: flex;
            gap: 20px;
        }
        .gallery {
            display: flex;
            gap: 20px;
        }
        .gallery img {
            max-width: 300px;
            height: auto;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3);
            transition: transform 0.3s ease;
        }
        .gallery img:hover {
            transform: scale(1.05);
        }
        .social-icons {
            position: fixed;
            bottom: 20px;
            right: 20px;
            display: flex;
            flex-direction: column;
            gap: 10px;
            z-index: 2;
        }
        .social-icons a {
            display: flex;
            align-items: center;
            justify-content: center;
            width: 50px;
            height: 50px;
            border-radius: 50%;
            background-color: white;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3);
            transition: background-color 0.3s ease;
        }
        .social-icons a:hover {
            background-color: #7B1FA2; /* Cor ao passar o mouse */
        }
        .social-icons img {
            width: 24px;
            height: 24px;
        }
    </style>
</head>
<body>
    <div class="background"></div> <!-- Efeito de fundo de água fixo e cinza claro -->
    <header class="header">
        <h1>AdesiReal</h1>
        <div class="search-bar">
            <input type="text" placeholder="Pesquisar adesivos 3D...">
        </div>
    </header>
    <div class="content">
        <!-- Categoria A -->
        <div class="category-container">
            <div class="category-title">Categoria A</div>
            <div class="gallery-container">
                <div class="gallery">
                    <!-- Adicione imagens da Categoria A aqui -->
                    <img src="https://via.placeholder.com/300x200.png?text=Adesivo+A1" alt="Adesivo A1">
                    <img src="https://via.placeholder.com/300x200.png?text=Adesivo+A2" alt="Adesivo A2">
                    <img src="https://via.placeholder.com/300x200.png?text=Adesivo+A3" alt="Adesivo A3">
                    <!-- Adicione mais imagens conforme necessário -->
                </div>
            </div>
        </div>

        <!-- Categoria B -->
        <div class="category-container">
            <div class="category-title">Categoria B</div>
            <div class="gallery-container">
                <div class="gallery">
                    <!-- Adicione imagens da Categoria B aqui -->
                    <img src="https://via.placeholder.com/300x200.png?text=Adesivo+B1" alt="Adesivo B1">
                    <img src="https://via.placeholder.com/300x200.png?text=Adesivo+B2" alt="Adesivo B2">
                    <img src="https://via.placeholder.com/300x200.png?text=Adesivo+B3" alt="Adesivo B3">
                    <!-- Adicione mais imagens conforme necessário -->
                </div>
            </div>
        </div>

        <!-- Categoria C -->
        <div class="category-container">
            <div class="category-title">Categoria C</div>
            <div class="gallery-container">
                <div class="gallery">
                    <!-- Adicione imagens da Categoria C aqui -->
                    <img src="https://via.placeholder.com/300x200.png?text=Adesivo+C1" alt="Adesivo C1">
                    <img src="https://via.placeholder.com/300x200.png?text=Adesivo+C2" alt="Adesivo C2">
                    <img src="https://via.placeholder.com/300x200.png?text=Adesivo+C3" alt="Adesivo C3">
                    <!-- Adicione mais imagens conforme necessário -->
                </div>
            </div>
        </div>

        <!-- Adicione mais categorias conforme necessário -->
    </div>
    <!-- Ícones de redes sociais -->
    <div class="social-icons">
        <a href="https://wa.me/64992999550" target="_blank" aria-label="WhatsApp">
            <img src="https://upload.wikimedia.org/wikipedia/commons/6/6b/WhatsApp.svg" alt="WhatsApp">
        </a>
        <a href="https://www.instagram.com/adesireal_oficial?igsh=MXNra3Ixc2Vsa2oxZw==" target="_blank" aria-label="Instagram">
            <img src="https://upload.wikimedia.org/wikipedia/commons/a/a5/Instagram_icon.png" alt="Instagram">
        </a>
    </div>
</body>
</html>
