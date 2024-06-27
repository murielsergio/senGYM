<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sengym - Prototipo Navegable</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="logo">
            <img src="logo.png" alt="Logo Sengym">
        </div>
        <nav>
            <ul>
                <li><a href="#inicio">Inicio</a></li>
                <li><a href="#horarios">Horarios</a></li>
                <li><a href="#dietas">Dietas</a></li>
                <li><a href="#videos">Videos</a></li>
                <li><a href="#perfil">Perfil</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="inicio" class="section">
            <h1>Bienvenido a Sengym</h1>
            <p>La plataforma para gestionar tus horarios, dietas y más en el gimnasio.</p>
            <button>Iniciar Sesión</button>
        </section>

        <section id="horarios" class="section">
            <h2>Horarios</h2>
            <p>Aquí puedes ver y gestionar tus horarios de entrenamiento.</p>
            <ul>
                <li>Lunes - 8:00 AM</li>
                <li>Martes - 10:00 AM</li>
                <li>...</li>
            </ul>
        </section>

        <section id="dietas" class="section">
            <h2>Dietas</h2>
            <p>Descubre las dietas recomendadas según tu tipo de cuerpo.</p>
            <div class="dieta">
                <h3>Tipo de Cuerpo A</h3>
                <p>Descripción de la dieta...</p>
            </div>
            <div class="dieta">
                <h3>Tipo de Cuerpo B</h3>
                <p>Descripción de la dieta...</p>
            </div>
        </section>

        <section id="videos" class="section">
            <h2>Videos</h2>
            <p>Observa los videos instructivos para aprender el uso correcto de las máquinas del gimnasio.</p>
            <div class="video">
                <h3>Video 1: Uso de la Cinta de Correr</h3>
                <p>Descripción del video...</p>
            </div>
            <div class="video">
                <h3>Video 2: Uso de las Pesas</h3>
                <p>Descripción del video...</p>
            </div>
        </section>

        <section id="perfil" class="section">
            <h2>Perfil de Usuario</h2>
            <p>Administra tu perfil y tus preferencias.</p>
            <form action="#">
                <label for="nombre">Nombre:</label>
                <input type="text" id="nombre" name="nombre" required>
                <label for="correo">Correo Electrónico:</label>
                <input type="email" id="correo" name="correo" required>
                <button>Guardar Cambios</button>
            </form>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 Sengym. Todos los derechos reservados.</p>
    </footer>
</body>
</html>
