# Enlace-a-mis-redes-sociales-
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mis Enlaces Oficiales</title>
    <!-- Iconos de FontAwesome para que se vea profesional -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        :root {
            --bg-color: #0b0b0d;       /* Fondo oscuro profundo */
            --card-bg: #16161c;        /* Fondo de los botones */
            --text-color: #ffffff;     /* Texto blanco */
            --accent-color: #e50914;   /* Rojo vibrante principal */
            --hover-bg: #ff1e27;       /* Rojo más brillante para el cursor */
            --border-color: #2a2a35;   /* Bordes sutiles */
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: var(--bg-color);
            color: var(--text-color);
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            padding: 20px;
        }

        .container {
            width: 100%;
            max-width: 480px;
            text-align: center;
        }

        /* Perfil */
        .profile {
            margin-bottom: 35px;
        }

        .profile-img {
            width: 100px;
            height: 100px;
            border-radius: 50%;
            object-fit: cover;
            border: 3px solid var(--accent-color);
            margin-bottom: 15px;
            box-shadow: 0 0 20px rgba(229, 9, 20, 0.4);
        }

        .profile h1 {
            font-size: 1.6rem;
            font-weight: 700;
            margin-bottom: 6px;
            letter-spacing: 0.5px;
        }

        .profile p {
            font-size: 0.95rem;
            color: #a0a0ab;
            font-weight: 500;
        }

        /* Bloques de Enlaces (Menú Rojo) */
        .links-container {
            display: flex;
            flex-direction: column;
            gap: 16px;
        }

        .link-card {
            display: flex;
            align-items: center;
            justify-content: space-between;
            background-color: var(--card-bg);
            padding: 18px 22px;
            border-radius: 14px;
            text-decoration: none;
            color: var(--text-color);
            font-weight: 600;
            transition: all 0.25s ease;
            border: 1px solid var(--border-color);
        }

        /* Efecto al pasar el dedo o el cursor: Se vuelve Rojo */
        .link-card:hover {
            transform: translateY(-3px);
            background-color: var(--accent-color);
            border-color: transparent;
            box-shadow: 0 10px 25px rgba(229, 9, 20, 0.35);
        }

        /* Cambia el color del icono específico a blanco cuando pasas el cursor */
        .link-card:hover .link-content i {
            color: #ffffff !important;
        }

        .link-content {
            display: flex;
            align-items: center;
            gap: 16px;
        }

        .link-content i {
            font-size: 1.4rem;
            width: 28px;
            text-align: center;
            transition: color 0.2s ease;
        }

        .arrow-icon {
            font-size: 0.9rem;
            opacity: 0.5;
        }

        /* Footer */
        footer {
            margin-top: 50px;
            font-size: 0.8rem;
            color: #52525b;
            letter-spacing: 0.5px;
        }
    </style>
</head>
<body>

    <div class="container">
        
        <!-- Sección de Perfil -->
        <div class="profile">
            <img src="https://via.placeholder.com/150" alt="Foto de Perfil" class="profile-img">
            <h1>Varvatus2616</h1>
            <p>Streamer & Creador de Contenido</p>
        </div>

        <!-- Contenedor de Enlaces -->
        <div class="links-container">

            <!-- Enlace: Twitch -->
            <a href="https://www.twitch.tv/varvatus2616" target="_blank" class="link-card">
                <div class="link-content">
                    <i class="fab fa-twitch" style="color: #a970ff;"></i>
                    <span>Twitch Oficial</span>
                </div>
                <i class="fas fa-chevron-right arrow-icon"></i>
            </a>

            <!-- Enlace: YouTube -->
            <a href="https://m.youtube.com/channel/UCV-s51StUmf2HzZWQYVjDTQ" target="_blank" class="link-card">
                <div class="link-content">
                    <i class="fab fa-youtube" style="color: #ff0000;"></i>
                    <span>YouTube Oficial</span>
                </div>
                <i class="fas fa-chevron-right arrow-icon"></i>
            </a>

            <!-- Enlace: Twitter / X -->
            <a href="https://x.com/Varvatos_black" target="_blank" class="link-card">
                <div class="link-content">
                    <i class="fab fa-x-twitter" style="color: #ffffff;"></i>
                    <span>Twitter (X)</span>
                </div>
                <i class="fas fa-chevron-right arrow-icon"></i>
            </a>

            <!-- Enlace: TikTok -->
            <a href="https://www.tiktok.com/@elchavouchiha?_r=1&_t=ZT-97VoA9NfQL8" target="_blank" class="link-card">
                <div class="link-content">
                    <i class="fab fa-tiktok" style="color: #00f2fe;"></i>
                    <span>TikTok</span>
                </div>
                <i class="fas fa-chevron-right arrow-icon"></i>
            </a>

            <!-- Enlace: Kick (Temporal) -->
            <a href="#" target="_blank" class="link-card">
                <div class="link-content">
                    <i class="fas fa-gamepad" style="color: #53fc18;"></i>
                    <span>Kick Stream</span>
                </div>
                <i class="fas fa-chevron-right arrow-icon"></i>
            </a>

            <!-- Enlace: BandLab -->
            <a href="https://www.bandlab.com/dj_jair2004" target="_blank" class="link-card">
                <div class="link-content">
                    <i class="fas fa-music" style="color: #ff4500;"></i>
                    <span>BandLab (Música)</span>
                </div>
                <i class="fas fa-chevron-right arrow-icon"></i>
            </a>

        </div>

        <!-- Footer -->
        <footer>
            <p>© 2026 Conectando todas las redes oficiales.</p>
        </footer>

    </div>

</body>
</html>
