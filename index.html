<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>¡Feliz Cumpleaños! ❤️</title>
    <style>
        /* RESET & BASE STYLES */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            -webkit-tap-highlight-color: transparent;
        }

        body {
            font-family: 'Georgia', serif;
            background: #060713;
            color: #f1f5f9;
            min-height: 100vh;
            overflow-x: hidden;
            position: relative;
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        /* CANVAS BACKGROUND */
        #bg-canvas {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            pointer-events: none;
            z-index: 1;
        }

        /* TELA DE BLOQUEIO / LOCKSCREEN */
        #lock-screen {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: #060713;
            z-index: 999;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            padding: 20px;
            text-align: center;
            transition: opacity 1.2s ease, visibility 1.2s ease;
        }

        .door-container {
            position: relative;
            width: 160px;
            height: 250px;
            margin: 15px auto;
            perspective: 1000px;
        }

        /* MOLDURA E PORTA TIPO CORALINE */
        .door-frame {
            width: 100%;
            height: 100%;
            border: 8px solid #c5a880;
            border-radius: 4px;
            background: #000;
            box-shadow: 0 0 25px rgba(168, 85, 247, 0.3), inset 0 0 15px rgba(0,0,0,0.9);
            position: relative;
            overflow: hidden;
        }

        .door {
            width: 100%;
            height: 100%;
            background: #f4eee6;
            border: 3px solid #7c5c3e;
            transform-origin: left;
            transition: transform 1.6s cubic-bezier(0.4, 0, 0.2, 1);
            display: flex;
            flex-direction: column;
            justify-content: space-around;
            align-items: center;
            padding: 20px 10px;
            position: absolute;
            top: 0;
            left: 0;
            z-index: 2;
            box-shadow: inset 0 0 12px rgba(0,0,0,0.2);
        }

        .door-panel {
            width: 85%;
            height: 42%;
            border: 3px solid #c5a880;
            background: #fffdfa;
            box-shadow: inset 2px 2px 6px rgba(0,0,0,0.12);
            border-radius: 2px;
        }

        .door-knob {
            width: 14px;
            height: 14px;
            background: radial-gradient(circle, #facc15 40%, #b45309 100%);
            border: 1px solid #78350f;
            border-radius: 50%;
            position: absolute;
            left: 10px;
            top: 52%;
            box-shadow: 2px 2px 5px rgba(0,0,0,0.4);
        }

        /* ESPIRAL ANIMAÇÃO */
        .tunnel-effect {
            position: absolute;
            width: 140px;
            height: 140px;
            top: 50%;
            left: 50%;
            margin-top: -70px;
            margin-left: -70px;
            background: conic-gradient(
                #1d4ed8 0deg, 
                #3b82f6 40deg, 
                #a855f7 90deg, 
                #ec4899 150deg, 
                #1e1b4b 210deg, 
                #38bdf8 280deg, 
                #1d4ed8 360deg
            );
            border-radius: 50%;
            z-index: 1;
            opacity: 0;
            transform: scale(0.1);
            transition: transform 2s cubic-bezier(0.2, 0.8, 0.2, 1), opacity 0.6s ease;
            filter: blur(2px);
            animation: spinTunnel 4s linear infinite;
        }

        @keyframes spinTunnel {
            0% { transform: scale(0.1) rotate(0deg); }
            100% { transform: scale(0.1) rotate(360deg); }
        }

        .door-open .door {
            transform: rotateY(-115deg);
        }

        .door-open .tunnel-effect {
            opacity: 1;
            animation: spinAndGrow 2s cubic-bezier(0.2, 0.8, 0.2, 1) forwards;
        }

        @keyframes spinAndGrow {
            0% { transform: scale(0.1) rotate(0deg); }
            100% { transform: scale(22) rotate(720deg); }
        }

        /* INPUT DE SENHA */
        .password-box {
            margin-top: 15px;
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 10px;
            z-index: 10;
        }

        .hint-text {
            color: #fde047;
            font-size: 0.9rem;
            font-family: 'Segoe UI', sans-serif;
            font-style: italic;
            background: rgba(250, 204, 21, 0.12);
            padding: 8px 16px;
            border-radius: 20px;
            border: 1px dashed rgba(250, 204, 21, 0.5);
        }

        .password-input {
            background: rgba(255, 255, 255, 0.08);
            border: 2px solid #facc15;
            border-radius: 25px;
            padding: 10px 20px;
            color: #fde047;
            font-size: 1.2rem;
            text-align: center;
            letter-spacing: 4px;
            outline: none;
            width: 160px;
        }

        .btn-unlock {
            background: #facc15;
            color: #0d1117;
            border: none;
            padding: 10px 24px;
            border-radius: 20px;
            font-weight: bold;
            font-size: 0.95rem;
            cursor: pointer;
            box-shadow: 0 4px 15px rgba(250, 204, 21, 0.4);
        }

        .forgot-link {
            color: #38bdf8;
            font-size: 0.82rem;
            font-family: 'Segoe UI', sans-serif;
            text-decoration: underline;
            cursor: pointer;
            margin-top: 5px;
        }

        .error-msg {
            color: #ef4444;
            font-size: 0.85rem;
            min-height: 20px;
            font-family: 'Segoe UI', sans-serif;
        }

        /* CONTAINER STRUCTURE */
        .container {
            position: relative;
            z-index: 3;
            width: 100%;
            max-width: 600px;
            padding: 30px 15px 50px 15px;
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        header {
            text-align: center;
            margin-bottom: 25px;
            width: 100%;
        }

        h1 {
            font-size: 1.8rem;
            font-weight: 700;
            background: linear-gradient(135deg, #facc15 0%, #38bdf8 50%, #c084fc 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            text-shadow: 0 0 20px rgba(250, 204, 21, 0.35);
            margin-bottom: 12px;
            line-height: 1.3;
        }

        .subtitle-container {
            min-height: 40px;
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 0 10px;
        }

        .typewriter {
            font-size: 0.95rem;
            color: #fde047;
            border-right: 2px solid #facc15;
            white-space: normal;
            letter-spacing: 0.5px;
            animation: blinkCursor 0.75s step-end infinite;
            font-style: italic;
            font-family: 'Segoe UI', sans-serif;
            text-shadow: 0 0 8px rgba(250, 204, 21, 0.5);
            text-align: center;
        }

        /* CARD DE TEXTO PRINCIPAL */
        .card {
            background: rgba(10, 15, 30, 0.85);
            backdrop-filter: blur(15px);
            -webkit-backdrop-filter: blur(15px);
            border: 1px solid rgba(250, 204, 21, 0.35);
            border-radius: 20px;
            padding: 25px 18px;
            box-shadow: 0 15px 35px rgba(0, 0, 0, 0.8);
            margin-bottom: 25px;
            width: 100%;
            position: relative;
        }

        .card p {
            font-family: 'Segoe UI', sans-serif;
            font-size: 0.98rem;
            line-height: 1.65;
            color: #f1f5f9;
            margin-bottom: 16px;
            font-weight: 300;
            text-align: left;
        }

        .card p:last-child {
            margin-bottom: 0;
        }

        /* BOTOES INTERATIVOS */
        .interactive-section {
            margin-top: 25px;
            text-align: center;
            border-top: 1px dashed rgba(250, 204, 21, 0.3);
            padding-top: 20px;
        }

        .question-title {
            font-size: 1.05rem;
            color: #facc15;
            font-weight: 600;
            margin-bottom: 18px;
            line-height: 1.4;
        }

        .btn-container {
            display: flex;
            flex-direction: row;
            justify-content: center;
            align-items: center;
            gap: 15px;
            min-height: 55px;
            width: 100%;
        }

        .btn-action {
            padding: 12px 28px;
            font-size: 1rem;
            font-weight: bold;
            font-family: 'Segoe UI', sans-serif;
            border-radius: 25px;
            cursor: pointer;
            border: 2px solid #facc15;
            box-shadow: 0 4px 12px rgba(0,0,0,0.4);
            touch-action: manipulation;
        }

        .btn-sim {
            background-color: #4b0082;
            color: #facc15;
        }

        .btn-nao {
            background-color: #1e293b;
            color: #94a3b8;
            border-color: #475569;
        }

        /* CARTÃO DA FOTO NO FINAL */
        .photo-card {
            background: rgba(10, 15, 30, 0.85);
            backdrop-filter: blur(15px);
            -webkit-backdrop-filter: blur(15px);
            border: 1px solid rgba(250, 204, 21, 0.35);
            border-radius: 20px;
            padding: 20px 18px;
            margin-bottom: 25px;
            width: 100%;
            display: flex;
            flex-direction: column;
            align-items: center;
            box-shadow: 0 10px 25px rgba(0,0,0,0.6);
        }

        .photo-box-small {
            width: 160px;
            border-radius: 12px;
            overflow: hidden;
            border: 2px solid rgba(250, 204, 21, 0.6);
            box-shadow: 0 4px 15px rgba(0,0,0,0.5);
            margin-bottom: 14px;
        }

        .photo-box-small img {
            width: 100%;
            height: auto;
            display: block;
        }

        .photo-card p {
            font-family: 'Segoe UI', sans-serif;
            font-size: 0.95rem;
            line-height: 1.6;
            color: #f1f5f9;
            text-align: center;
            font-weight: 300;
        }

        /* BOTÃO DE VÍDEO */
        .video-section {
            width: 100%;
            margin-bottom: 25px;
            text-align: center;
        }

        .btn-video {
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 10px;
            width: 100%;
            padding: 14px 20px;
            font-size: 1rem;
            font-weight: 650;
            font-family: 'Segoe UI', sans-serif;
            color: #0d1117;
            background: linear-gradient(135deg, #facc15 0%, #eab308 100%);
            border: 1px solid rgba(250, 204, 21, 0.8);
            border-radius: 30px;
            text-decoration: none;
            box-shadow: 0 8px 20px rgba(250, 204, 21, 0.3);
        }

        /* SPOTIFY */
        .spotify-section {
            width: 100%;
            margin-bottom: 25px;
        }

        .spotify-card {
            width: 100%;
            border-radius: 16px;
            overflow: hidden;
            background: rgba(15, 23, 42, 0.8);
            border: 1px solid rgba(250, 204, 21, 0.3);
            padding: 4px;
        }

        .spotify-card iframe {
            border-radius: 12px;
            width: 100%;
            height: 352px;
            border: none;
            display: block;
        }

        /* FOOTER */
        footer {
            position: relative;
            z-index: 3;
            width: 100%;
            padding: 18px 15px;
            text-align: center;
            background: rgba(6, 7, 19, 0.95);
            border-top: 1px solid rgba(250, 204, 21, 0.2);
            margin-top: auto;
        }

        footer p {
            font-size: 0.88rem;
            color: #94a3b8;
            font-family: 'Segoe UI', sans-serif;
        }

        footer span {
            color: #facc15;
        }

        @keyframes blinkCursor {
            from, to { border-color: transparent; }
            50% { border-color: #facc15; }
        }
    </style>

    <script src="https://cdn.jsdelivr.net/npm/canvas-confetti@1.6.0/dist/confetti.browser.min.js"></script>
</head>
<body>

    <audio id="musicaFundo" loop preload="auto">
        <source src="exploration.mp3" type="audio/mpeg">
    </audio>

    <!-- TELA DE BLOQUEIO -->
    <div id="lock-screen">
        <h2 style="color: #facc15; font-size: 1.3rem; margin-bottom: 5px;">La Puerta Secreta 🗝️</h2>
        <p style="color: #94a3b8; font-size: 0.85rem; font-family: 'Segoe UI', sans-serif;">Ingresa la clave para abrir el portal...</p>

        <div class="door-container" id="doorContainer">
            <div class="door-frame">
                <div class="tunnel-effect"></div>
                <div class="door">
                    <div class="door-panel"></div>
                    <div class="door-panel"></div>
                    <div class="door-knob"></div>
                </div>
            </div>
        </div>

        <div class="password-box">
            <div class="hint-text">💡 Pista: Es la contraseña de mi celular 📱🗝️</div>
            <input type="password" id="passInput" class="password-input" maxlength="4" placeholder="••••" pattern="[0-9]*" inputmode="numeric">
            <button class="btn-unlock" onclick="verificarSenha()">Desbloquear 🗝️</button>
            <span class="forgot-link" onclick="esqueciSenha()">¿Olvidaste la clave? 🗝️</span>
            <div class="error-msg" id="errorMsg"></div>
        </div>
    </div>

    <canvas id="bg-canvas"></canvas>

    <div class="container">
        <header>
            <h1>¡Feliz Cumpleaños! ❤️</h1>
            <div class="subtitle-container">
                <span id="typewriter" class="typewriter"></span>
            </div>
        </header>

        <!-- CARTÃO PRINCIPAL -->
        <section class="card">
            <p>Hola. ❤️</p>
            <p>Conocerte ha sido una de las mejores cosas que me han pasado en la vida. Nunca voy a olvidar la primera vez que te vi y cómo desde entonces nos fuimos acercando poco a poco.</p>
            <p>Hoy, en tu cumpleaños, quiero que sepas lo especial que eres para mí. Gracias por tu cariño, por tu compañía y por estar siempre ahí.</p>
            <p>Espero que este nuevo año de vida esté lleno de alegría, salud, sueños cumplidos y muchos momentos bonitos.</p>
            <p>Siempre estaré a tu lado para apoyarte, cuidarte y valorar la hermosa amistad y conexión que tenemos.</p>
            <p>Espero que te guste este pequeño detalle. Lo hice con todo mi cariño para ti.</p>
            <p>También espero que te guste este pequeño ramo de girasoles. 🌻 Sé cuánto te gustan y quise regalártelos como un símbolo de la luz que traes a mi vida.</p>
            <p>Y, por cierto... ¿Recuerdas la primera vez que te invité a salir y me dijiste "en mi próximo cumpleaños"? Bueno... ese "próximo cumpleaños" por fin llegó. ❤️ Espero que disfrutes mucho este día y espero que aceptes mi invitación. Si es un sí, tienes el botón "SÍ" aquí abajo (o el "NO", si te atreves a intentarlo).</p>

            <div class="interactive-section">
                <p class="question-title">¿Aceptas abrir la pequeña puerta conmigo hoy? 🗝️✨</p>
                <div class="btn-container">
                    <button class="btn-action btn-sim" onclick="respostaSim()">¡SÍ! ❤️</button>
                    <button class="btn-action btn-nao" id="btnNao" onclick="desviar()" onmouseover="desviar()" ontouchstart="desviar(event)">NO</button>
                </div>
            </div>
        </section>

        <!-- FOTO DE INFÂNCIA NO SEU PRÓPRIO QUADRO -->
        <section class="photo-card">
            <div class="photo-box-small">
                <img src="IMG-20260727-WA0020.jpg" alt="Foto especial">
            </div>
            <p>¿Quién diría que esta niña tan pequeña se convertiría en esta mujer tan increíble? Creo que tuve mucha suerte de conocerte y espero de corazón que esta amistad nunca se acabe. ✨</p>
        </section>

        <!-- BOTÃO DE VÍDEO -->
        <section class="video-section">
            <a href="https://www.instagram.com/reel/DbOpWbKi3Ri/?igsh=MXhlOG81eGs0aWlyMw==" target="_blank" rel="noopener noreferrer" class="btn-video">
                🎥 Mira este video ❤️
            </a>
        </section>

        <!-- SPOTIFY -->
        <section class="spotify-section">
            <div class="spotify-card">
                <iframe src="https://open.spotify.com/embed/playlist/2u7hAgL7NegOZq3F2k0Ehm?utm_source=generator&theme=0" allowfullscreen="" allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture" loading="lazy"></iframe>
            </div>
        </section>
    </div>

    <footer>
        <p>A través de la pequeña puerta y más allá de las estrellas... <span>🗝️ 🧵 ❤️</span></p>
    </footer>

    <script>
        function verificarSenha() {
            const input = document.getElementById("passInput").value;
            const error = document.getElementById("errorMsg");
            const container = document.getElementById("doorContainer");
            const lockScreen = document.getElementById("lock-screen");

            if (input === "0423") {
                error.textContent = "";
                container.classList.add("door-open");

                const audio = document.getElementById("musicaFundo");
                if (audio) {
                    audio.volume = 0.5;
                    audio.play().catch(e => console.log("Áudio aguardando interação"));
                }

                setTimeout(() => {
                    lockScreen.style.opacity = "0";
                    lockScreen.style.visibility = "hidden";
                    setTimeout(typeEffect, 300);
                }, 1800);
            } else {
                error.textContent = "Clave incorrecta. ¡La llave no encaja! 🗝️❌";
                document.getElementById("passInput").value = "";
            }
        }

        function esqueciSenha() {
            const meuNumero = "5592994205721";
            const mensagem = encodeURIComponent("¡Se me olvidó la clave de la puerta secreta! 🗝️ ¿Me das una pista?");
            window.open(`https://wa.me/${meuNumero}?text=${mensagem}`, '_blank');
        }

        document.getElementById("passInput").addEventListener("keypress", function(e) {
            if (e.key === 'Enter') verificarSenha();
        });

        const textToType = "Detrás de la puerta secreta, un regalo hecho especialmente para ti... 🗝️✨";
        const typewriterElement = document.getElementById("typewriter");
        let charIndex = 0;

        function typeEffect() {
            if (charIndex < textToType.length) {
                typewriterElement.textContent += textToType.charAt(charIndex);
                charIndex++;
                setTimeout(typeEffect, 50);
            }
        }

        function desviar(e) {
            if (e && e.type === 'touchstart') e.preventDefault();
            const btn = document.getElementById("btnNao");

            const larguraJanela = window.innerWidth - btn.offsetWidth - 20;
            const alturaJanela = window.innerHeight - btn.offsetHeight - 20;

            const novaPosicaoX = Math.max(10, Math.floor(Math.random() * larguraJanela));
            const novaPosicaoY = Math.max(10, Math.floor(Math.random() * alturaJanela));

            btn.style.position = "fixed";
            btn.style.left = `${novaPosicaoX}px`;
            btn.style.top = `${novaPosicaoY}px`;
        }

        function respostaSim() {
            confetti({ particleCount: 100, spread: 70, origin: { y: 0.6 } });
            setTimeout(() => {
                const meuNumero = "5592994205721";
                const mensagem = encodeURIComponent("¡SÍ! Acepto abrir la pequeña puerta contigo hoy... 🗝️❤️");
                window.location.href = `https://wa.me/${meuNumero}?text=${mensagem}`;
            }, 2500);
        }

        // CANVAS ANIMATION
        const canvas = document.getElementById("bg-canvas");
        const ctx = canvas.getContext("2d");
        let width, height;

        function resizeCanvas() {
            width = canvas.width = window.innerWidth;
            height = canvas.height = window.innerHeight;
        }
        window.addEventListener("resize", resizeCanvas);
        resizeCanvas();

        class Star {
            constructor() { this.reset(); }
            reset() {
                this.x = Math.random() * width;
                this.y = Math.random() * height;
                this.size = Math.random() * 1.2 + 0.4;
                this.alpha = Math.random();
                this.speed = Math.random() * 0.015 + 0.005;
                this.increasing = Math.random() > 0.5;
            }
            update() {
                if (this.increasing) {
                    this.alpha += this.speed;
                    if (this.alpha >= 1) this.increasing = false;
                } else {
                    this.alpha -= this.speed;
                    if (this.alpha <= 0.15) this.increasing = true;
                }
            }
            draw() {
                ctx.save();
                ctx.globalAlpha = this.alpha;
                ctx.fillStyle = "#ffffff";
                ctx.beginPath();
                ctx.arc(this.x, this.y, this.size, 0, Math.PI * 2);
                ctx.fill();
                ctx.restore();
            }
        }

        const stars = Array.from({ length: 40 }, () => new Star());
        function animate() {
            ctx.clearRect(0, 0, width, height);
            stars.forEach(s => { s.update(); s.draw(); });
            requestAnimationFrame(animate);
        }
        animate();
    </script>
</body>
</html>

