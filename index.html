<%@page contentType="text/html" pageEncoding="UTF-8"%>
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Para mi Futura Abogada Favorita ⚖️❤️</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body, html {
            width: 100vw;
            height: 100vh;
            overflow: hidden;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #0b0b10;
            color: #fff;
        }

        /* Pantalla de Inicio Principal */
        #welcome-screen {
            position: fixed;
            top: 0;
            left: 0;
            width: 100vw;
            height: 100vh;
            background: radial-gradient(circle, #2b091e 0px, #0b0b10 100vh);
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            z-index: 100;
            cursor: pointer;
            transition: opacity 1s ease;
            text-align: center;
            padding: 20px;
        }

        .welcome-card {
            background: rgba(255, 255, 255, 0.05);
            border: 2px solid #ff758c;
            padding: 20px;
            border-radius: 20px;
            box-shadow: 0 0 30px rgba(255, 117, 140, 0.4);
            width: 320px;
            max-width: 90vw;
            animation: pulseCard 2s infinite ease-in-out;
        }

        /* Proporción fija para la foto principal */
        .welcome-card img {
            width: 280px;
            height: 350px;
            object-fit: cover;
            border-radius: 12px;
            margin-bottom: 15px;
            border: 2px solid #d4af37;
        }

        .welcome-card h1 {
            font-size: 1.3rem;
            color: #ff9a9e;
            margin-bottom: 8px;
        }

        .welcome-card p {
            font-size: 0.9rem;
            color: #fce4ec;
            margin-bottom: 12px;
        }

        .tap-button {
            background: linear-gradient(135deg, #ff758c 0px, #ff7eb3 100px);
            color: white;
            border: none;
            padding: 10px 22px;
            font-size: 0.95rem;
            border-radius: 25px;
            cursor: pointer;
            font-weight: bold;
            box-shadow: 0 4px 15px rgba(255, 117, 140, 0.5);
        }

        /* Animación sin porcentajes para compatibilidad JSP en NetBeans */
        @keyframes pulseCard {
            from { transform: scale(1); box-shadow: 0 0 20px rgba(255, 117, 140, 0.3); }
            to { transform: scale(1.02); box-shadow: 0 0 35px rgba(255, 117, 140, 0.6); }
        }

        /* Escenario 3D */
        #canvas-container {
            width: 100vw;
            height: 100vh;
            position: absolute;
            top: 0;
            left: 0;
            visibility: hidden;
        }

        /* Capa de Control e Interfaz */
        .ui-layer {
            position: absolute;
            top: 0;
            left: 0;
            width: 100vw;
            height: 100vh;
            z-index: 10;
            pointer-events: none;
            display: flex;
            flex-direction: column;
            justify-content: space-between;
            padding: 20px;
            opacity: 0;
            transition: opacity 1s ease;
        }

        .nav-buttons {
            position: absolute;
            top: 50vh;
            width: 100vw;
            left: 0;
            display: flex;
            justify-content: space-between;
            padding: 0 25px;
            transform: translateY(-50%);
            pointer-events: auto;
        }

        .nav-btn {
            background: rgba(0, 0, 0, 0.5);
            border: 2px solid #ff758c;
            color: white;
            font-size: 1.8rem;
            width: 50px;
            height: 50px;
            border-radius: 50%;
            cursor: pointer;
            display: flex;
            align-items: center;
            justify-content: center;
            backdrop-filter: blur(5px);
            transition: transform 0.2s, background 0.2s;
        }

        .nav-btn:hover {
            background: rgba(255, 117, 140, 0.7);
            transform: scale(1.1);
        }

        .top-bar {
            text-align: center;
            width: 100%;
        }

        .top-bar h2 {
            font-size: 1.4rem;
            color: #ff9a9e;
            text-shadow: 0 0 10px rgba(255, 154, 158, 0.6);
            background: rgba(0,0,0,0.5);
            display: inline-block;
            padding: 8px 22px;
            border-radius: 20px;
            border: 1px solid rgba(255,117,140,0.4);
        }

        .bottom-bar {
            text-align: center;
            padding-bottom: 15px;
            pointer-events: auto;
        }

        .action-btn {
            background: linear-gradient(135deg, #ff758c 0px, #ff7eb3 100px);
            border: none;
            color: white;
            padding: 12px 28px;
            border-radius: 30px;
            font-size: 1rem;
            font-weight: bold;
            cursor: pointer;
            box-shadow: 0 5px 20px rgba(255, 117, 140, 0.5);
        }

        .music-toggle {
            position: absolute;
            top: 20px;
            right: 20px;
            background: rgba(0, 0, 0, 0.5);
            border: 1px solid #ff758c;
            color: white;
            padding: 8px 14px;
            border-radius: 20px;
            cursor: pointer;
            pointer-events: auto;
            backdrop-filter: blur(5px);
            font-size: 0.85rem;
        }
    </style>
</head>
<body>

    <!-- 1. PANTALLA PRINCIPAL CON foto1.jpg -->
    <div id="welcome-screen" onclick="startExperience()">
        <div class="welcome-card">
            <img src="imagenes/foto1.jpg" alt="Foto Principal">
            <h1>Para mi Abogada Favorita ⚖️✨</h1>
            <p>Toca aquí para iniciar el recorrido de recuerdos...</p>
            <button class="tap-button">Entrar 💖</button>
        </div>
    </div>

    <!-- 2. ESCENARIO 3D -->
    <div id="canvas-container"></div>

    <!-- 3. INTERFAZ Y NAVEGACIÓN -->
    <div class="ui-layer" id="ui-layer">
        <button class="music-toggle" id="music-btn" onclick="toggleMusic()">🎵 Música: OFF</button>
        
        <div class="top-bar">
            <h2>Estudio Jurídico del Amor ⚖️❤️</h2>
        </div>

        <div class="nav-buttons">
            <button class="nav-btn" onclick="prevSlide()">&#10094;</button>
            <button class="nav-btn" onclick="nextSlide()">&#10095;</button>
        </div>

        <div class="bottom-bar">
            <button class="action-btn" onclick="triggerFireworks()">¡Lanzar Magia ✨!</button>
        </div>
    </div>

    <!-- Cargar tu archivo de audio local exacto -->
    <audio id="bg-audio" loop>
        <source src="imagenes/musica 1_mezcla.mp3" type="audio/mpeg">
    </audio>

    <script src="https://cdnjs.cloudflare.com/ajax/libs/three.js/r128/three.min.js"></script>
    <script>
        let scene, camera, renderer, particles;
        let photoMeshes = [];
        let currentIndex = 0;
        let isStarted = false;
        let audioPlaying = false;

        // Las 5 fotos secundarias dispuestas tras la entrada
        const photosData = [
            { url: 'imagenes/foto2.png', title: 'Mirada Incomparable', quote: 'Sin objeción alguna: Tienes la sonrisa más bella y justa del universo. ✨⚖️' },
            { url: 'imagenes/foto3.png', title: 'Código del Corazón', quote: 'En el código de mi corazón, no hay apelación posible: te elijo todos los días. ❤️📜' },
            { url: 'imagenes/foto4.png', title: 'Futura Magistrada', quote: 'Tu determinación, inteligencia y hermosa sonrisa iluminan mi vida entera. 🌟' },
            { url: 'imagenes/foto5.png', title: 'Sentencia de Amor', quote: 'Sentencia definitiva: Te amaré hoy, mañana y siempre sin excepciones. ⚖️💘' },
            { url: 'imagenes/foto6.png', title: 'Paz y Ternura', quote: 'Eres la prueba viviente de que los sueños más hermosos sí se hacen realidad. 🥰🌸' }
        ];

        function startExperience() {
            if (isStarted) return;
            isStarted = true;

            // Iniciar la canción al hacer clic en la pantalla de bienvenida
            const audio = document.getElementById('bg-audio');
            const btn = document.getElementById('music-btn');
            audio.play().then(() => {
                audioPlaying = true;
                btn.innerText = "🎵 Música: ON";
            }).catch(error => {
                console.log("Reproducción automática esperando interacción.");
            });

            const welcome = document.getElementById('welcome-screen');
            welcome.style.opacity = '0';
            setTimeout(() => {
                welcome.style.display = 'none';
                document.getElementById('canvas-container').style.visibility = 'visible';
                document.getElementById('ui-layer').style.opacity = '1';
                init3D();
            }, 1000);
        }

        function toggleMusic() {
            const audio = document.getElementById('bg-audio');
            const btn = document.getElementById('music-btn');
            if (audioPlaying) {
                audio.pause();
                btn.innerText = "🎵 Música: OFF";
            } else {
                audio.play();
                btn.innerText = "🎵 Música: ON";
            }
            audioPlaying = !audioPlaying;
        }

        // Renderizado uniforme de la imagen con su frase debajo en HD
        function createCardTexture(title, quote, imgUrl) {
            const canvas = document.createElement('canvas');
            canvas.width = 800;
            canvas.height = 1100;
            const ctx = canvas.getContext('2d');

            ctx.fillStyle = '#140f18';
            ctx.fillRect(0, 0, canvas.width, canvas.height);

            ctx.strokeStyle = '#d4af37';
            ctx.lineWidth = 14;
            ctx.strokeRect(15, 15, canvas.width - 30, canvas.height - 30);

            return new Promise((resolve) => {
                const img = new Image();
                img.crossOrigin = "anonymous";
                img.src = imgUrl;
                img.onload = () => {
                    const imgSize = 680;
                    const xPos = (canvas.width - imgSize) / 2;
                    ctx.drawImage(img, xPos, 50, imgSize, imgSize);

                    ctx.fillStyle = '#ff9a9e';
                    ctx.font = 'bold 42px sans-serif';
                    ctx.textAlign = 'center';
                    ctx.fillText(title, canvas.width / 2, 780);

                    ctx.fillStyle = '#fce4ec';
                    ctx.font = '28px sans-serif';
                    wrapText(ctx, quote, canvas.width / 2, 850, 700, 40);

                    const texture = new THREE.CanvasTexture(canvas);
                    resolve(texture);
                };
                img.onerror = () => {
                    resolve(null);
                };
            });
        }

        function wrapText(context, text, x, y, maxWidth, lineHeight) {
            const words = text.split(' ');
            let line = '';
            for(let n = 0; n < words.length; n++) {
                let testLine = line + words[n] + ' ';
                let metrics = context.measureText(testLine);
                if (metrics.width > maxWidth && n > 0) {
                    context.fillText(line, x, y);
                    line = words[n] + ' ';
                    y += lineHeight;
                } else {
                    line = testLine;
                }
            }
            context.fillText(line, x, y);
        }

        async function init3D() {
            const container = document.getElementById('canvas-container');
            scene = new THREE.Scene();
            camera = new THREE.PerspectiveCamera(55, window.innerWidth / window.innerHeight, 0.1, 1000);
            camera.position.set(0, 0, 7);

            renderer = new THREE.WebGLRenderer({ antialias: true, alpha: true });
            renderer.setSize(window.innerWidth, window.innerHeight);
            renderer.setPixelRatio(window.devicePixelRatio);
            container.appendChild(renderer.domElement);

            const ambientLight = new THREE.AmbientLight(0xffffff, 1.3);
            scene.add(ambientLight);

            const particleGeo = new THREE.BufferGeometry();
            const particleCount = 600;
            const posArray = new Float32Array(particleCount * 3);
            for(let i = 0; i < particleCount * 3; i++) {
                posArray[i] = (Math.random() - 0.5) * 30;
            }
            particleGeo.setAttribute('position', new THREE.BufferAttribute(posArray, 3));
            const particleMat = new THREE.PointsMaterial({ size: 0.04, color: 0xff758c });
            particles = new THREE.Points(particleGeo, particleMat);
            scene.add(particles);

            const total = photosData.length;
            const cardWidth = 2.2;
            const cardHeight = 3.0;

            for (let i = 0; i < total; i++) {
                const t = (i - (total - 1) / 2);
                const x = Math.sin(t * 1.2) * 3.2;
                const y = -t * 0.4;
                const z = -Math.abs(t) * 1.5;

                const texture = await createCardTexture(photosData[i].title, photosData[i].quote, photosData[i].url);
                const geometry = new THREE.PlaneGeometry(cardWidth, cardHeight);
                const material = new THREE.MeshStandardMaterial({ 
                    map: texture, 
                    side: THREE.DoubleSide,
                    roughness: 0.2
                });

                const mesh = new THREE.Mesh(geometry, material);
                mesh.position.set(x, y, z);
                mesh.userData = { basePos: new THREE.Vector3(x, y, z) };
                
                scene.add(mesh);
                photoMeshes.push(mesh);
            }

            focusCard(currentIndex);
            animate();
            window.addEventListener('resize', onWindowResize);
        }

        function focusCard(index) {
            photoMeshes.forEach((mesh, i) => {
                const base = mesh.userData.basePos;
                if (i === index) {
                    mesh.position.set(0, 0, 2.2);
                    mesh.rotation.set(0, 0, 0);
                    mesh.scale.set(1.15, 1.15, 1.15);
                } else {
                    mesh.position.copy(base);
                    mesh.rotation.set(0, (i < index ? 0.3 : -0.3), 0);
                    mesh.scale.set(0.85, 0.85, 0.85);
                }
            });
        }

        function animate() {
            requestAnimationFrame(animate);

            if(particles) {
                particles.rotation.y += 0.0006;
            }

            renderer.render(scene, camera);
        }

        function nextSlide() {
            currentIndex = (currentIndex + 1) % photosData.length;
            focusCard(currentIndex);
        }

        function prevSlide() {
            currentIndex = (currentIndex - 1 + photosData.length) % photosData.length;
            focusCard(currentIndex);
        }

        function triggerFireworks() {
            const pLight = new THREE.PointLight(0xff1493, 6, 25);
            pLight.position.set((Math.random()-0.5)*4, (Math.random()-0.5)*4, 3);
            scene.add(pLight);
            setTimeout(() => scene.remove(pLight), 600);
        }

        function onWindowResize() {
            camera.aspect = window.innerWidth / window.innerHeight;
            camera.updateProjectionMatrix();
            renderer.setSize(window.innerWidth, window.innerHeight);
        }
    </script>
</body>
</html>