<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portafolio Futurista | [Tu Nombre]</title>
    <style>
        :root {
            --neon-blue: #0ff0fc;
            --neon-pink: #ff00ff;
            --dark-bg: #0a0a20;
            --glow: 0 0 10px var(--neon-blue), 0 0 20px var(--neon-pink);
        }
        
        body {
            background-color: var(--dark-bg);
            color: white;
            font-family: 'Courier New', monospace;
            margin: 0;
            padding: 0;
            line-height: 1.6;
            overflow-x: hidden;
        }
        
        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 2rem;
        }
        
        header {
            text-align: center;
            margin-bottom: 3rem;
            animation: fadeIn 2s;
        }
        
        h1 {
            color: var(--neon-blue);
            text-shadow: var(--glow);
            font-size: 2.5rem;
            margin-bottom: 0.5rem;
        }
        
        .subtitle {
            color: var(--neon-pink);
            font-size: 1.2rem;
        }
        
        section {
            margin-bottom: 3rem;
            border-left: 2px solid var(--neon-blue);
            padding-left: 1.5rem;
            transition: all 0.3s;
        }
        
        section:hover {
            border-left: 4px solid var(--neon-pink);
            transform: translateX(10px);
        }
        
        h2 {
            color: var(--neon-blue);
            margin-top: 0;
        }
        
        .contact-info a {
            color: var(--neon-pink);
            text-decoration: none;
            display: inline-block;
            margin: 0.3rem 0;
            transition: all 0.3s;
        }
        
        .contact-info a:hover {
            text-shadow: var(--glow);
            transform: scale(1.05);
        }
        
        footer {
            text-align: center;
            margin-top: 4rem;
            opacity: 0.8;
        }
        
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
        
        /* Efecto futurista para títulos */
        .neon-text {
            animation: flicker 1.5s infinite alternate;
        }
        
        @keyframes flicker {
            0%, 19%, 21%, 23%, 25%, 54%, 56%, 100% {
                text-shadow: var(--glow);
            }
            20%, 24%, 55% {
                text-shadow: none;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1 class="neon-text">¡BIENVENIDO/A A MI PORTAFOLIO!</h1>
            <p class="subtitle">Ingeniero de Sistemas | Innovación Tecnológica</p>
        </header>
        
        <section id="contacto">
            <h2>📌 DATOS DE CONTACTO</h2>
            <div class="contact-info">
                <p><strong>Email:</strong> <a href="mailto:tuemail@dominio.com">tuemail@dominio.com</a></p>
                <p><strong>LinkedIn:</strong> <a href="https://linkedin.com/in/tuperfil" target="_blank">linkedin.com/in/tuperfil</a></p>
                <p><strong>GitHub:</strong> <a href="https://github.com/tuusuario" target="_blank">github.com/tuusuario</a></p>
                <p><strong>Teléfono:</strong> <a href="tel:+51987654321">+51 987 654 321</a></p>
            </div>
        </section>
        
        <section id="sobre-mi">
            <h2>👨‍💻 SOBRE MÍ</h2>
            <p>
                Soy <strong>[Tu Nombre]</strong>, profesional en Ingeniería de Sistemas con especial interés en 
                [tus áreas de expertise, ej: inteligencia artificial, desarrollo web, ciberseguridad]. 
                Combino habilidades técnicas con una visión estratégica para crear soluciones innovadoras 
                que impacten positivamente en el sector [salud, educación, etc.].
            </p>
            <p>
                Actualmente trabajo en [tu puesto actual] donde he logrado [un logro relevante]. 
                Mi objetivo es [tu meta profesional].
            </p>
        </section>
        
        <footer>
            <p class="neon-text">🚀 ¡GRACIAS POR VISITAR MI PORTAFOLIO! 🚀</p>
            <p>© 2024 [Tu Nombre] | Todos los derechos reservados</p>
        </footer>
    </div>
</body>
</html>
