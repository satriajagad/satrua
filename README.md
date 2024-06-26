<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mohamad Satria Jagad</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: rgba(255, 255, 255, 0.5); /* Latar belakang putih dengan transparansi 0.5 */
            position: relative;
            z-index: 1;
        }

        body::before {
            content: "";
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(255, 255, 255, 0.5); /* Latar belakang putih dengan transparansi 0.5 */
            z-index: -1; /* Menempatkan latar belakang di bawah elemen lain */
        }

        section {
            padding: 50px;
            position: relative;
            z-index: 1;
        }

        header {
            background-color: #333;
            color: #fff;
            padding: 20px 0;
            text-align: center;
        }

        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
        }

        nav ul li {
            display: inline;
        }

        nav ul li a {
            color: #fff;
            text-decoration: none;
            padding: 10px 20px;
        }

        nav ul li a:hover {
            background-color: #555;
        }

        footer {
            background-color: transparent;
            color: #fff;
            text-align: center;
            padding: 20px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }

        .slider {
            display: flex;
            overflow-x: auto;
            scrollbar-width: none; /* Firefox */
            -ms-overflow-style: none; /* IE/Edge */
            flex-direction: row; /* Ubah posisi slider ke samping kanan */
        }

        .slide {
            flex: 0 0 auto;
            width: 600px;
            margin-left: 20px; /* Jarak antara gambar */
            cursor: pointer;
            position: relative;
        }

        .slide img {
            max-width: 100%; /* Mengubah ukuran gambar */
            border-radius: 20px;
        }

        .slider::-webkit-scrollbar {
            display: none; /* Chrome, Safari */
        }

        .overlay {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(0, 0, 0, 0.7);
            display: none;
            justify-content: center;
            align-items: center;
            z-index: 999;
        }

        .overlay img {
            max-width: 90%;
            max-height: 90%;
            border-radius: 20px;
        }

        .overlay .close {
            position: absolute;
            top: 10px;
            right: 10px;
            cursor: pointer;
            color: #fff;
            font-size: 20px;
        }

        .overlay .download {
            position: absolute;
            bottom: 10px;
            right: 10px;
            cursor: pointer;
            color: #fff;
            font-size: 20px;
        }

        .bottom-border {
            border-top: 1px solid black;
            margin-top: 20px; /* Sesuaikan margin jika perlu */
            width: 100%; /* Menjadikan lebar 100% */
            position: absolute; /* Mengatur posisi absolut agar menutupi sampai ke tepi */
            bottom: 0; /* Meletakkan garis di bagian paling bawah */
        }

        h2 {
            animation: fadeInUp 1s ease;
            text-shadow: 2px 2px 4px #000000;
            color: #080808;
            transition: color 0.5s ease;
        }

        h2:hover {
            color: #00a2ff; /* Ganti warna saat hover */
        }

        @keyframes fadeImage {
            0% {
                opacity: 1;
            }
            50% {
                opacity: 0.5;
            }
            100% {
                opacity: 1;
            }
        }

        .experience-item img {
            animation: fadeImage 3s infinite;
        }

        .experience-item {
            display: flex;
            flex-direction: column;
            align-items: center;
            margin-bottom: 20px; /* Jarak antar item pengalaman */
        }

        .experience-item img {
            margin-bottom: 10px; /* Jarak antara gambar dan teks */
        }

        .experience-details {
            text-align: center;
        }

        .experience-details h3 {
            margin: 10px 0 5px 0; /* Jarak antara judul dan paragraf */
        }

        .experience-details p {
            margin: 10px; /* Hilangkan margin default dari paragraf */
        }

        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-image: url('Background.jpg');
            background-size: cover;
            background-repeat: no-repeat;
            background-attachment: fixed;
            position: relative;
        }

        canvas {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            pointer-events: none;
            z-index: 9999;
        }

    </style>
</head>
<body>
    <header>
        <h1>Mohamad Satria Jagad</h1>
        <nav>
            <ul>
                <li><a href="#Profil">My Profil</a></li>
                <li><a href="#Experience">Experience</a></li>
                <li><a href="#Portofolio">Portofolio</a></li>
                <li><a href="#Achievment">Achievment</a></li>
                <li><a href="#certificate">Certificate</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="Profil">
        <h2>My Profil</h2>
        <p> Introduce my name is Mohamad Satria Jagad can be called Jagad. I am an active student of S1 Industrial Engineering, Airlangga University. In my previous work experience, I have been involved in successful process improvement projects, which involved analyzing data, mapping value streams, and implementing effective solutions. In addition, I have in-depth knowledge of system modeling and simulation using software such as Cx Programmer and Cx Designer. I am also skilled in using technical software such as AutoCAD to design and analyze work systems. 
        <br><br>
            I am very enthusiastic to apply my knowledge and skills in the real world and contribute to improving the efficiency and operational performance of the company. I believe that the combination of my education, work experience, and supporting skills such as communication skills, leadership, time management, and problem solving make me a strong candidate in the field of Industrial Engineering. Discipline, responsibility, honesty and good ethics are my priorities at work and I like and am able to learn new things
        </p>
    </section>
    

    <section id="Experience">
        <h2>Experience</h2>
        <!-- Pengalaman Kerja Pertama -->
        <div class="experience-item" style="display: flex; justify-content: center;">
            <div style="text-align: center;">
                <img src="MaritimMuda.png" alt="Logo Perusahaan 1" width="75" height="75">
                <div class="experience-details">
                    <h3>Akselerator Organisasi Daerah Maritim Muda</h3>
                    <p>Blue Economy | Project Management</p>
                </div>
            </div>
            <div style="text-align: center;">
                <img src="DSV.png" alt="Logo Perusahaan 2" width="75" height="75" style="animation: none;">
                <div class="experience-details">
                    <h3>Warehouse Logistic Intern</h3>
                    <p>Inbound | Outbound | Picking | Warehouse Management System | Inventory Control</p>
                </div>
            </div>
            <div style="text-align: center;">
                <img src="Airdrop Counter.png" alt="Logo Perusahaan 3" width="75" height="75">
                <div class="experience-details">
                    <h3>Founder & CEO</h3>
                    <p>Leadership | Crypto Analyst | Market Analyst | Research Management</p>
                </div>
            </div>
        </div>
    </section>
    

    <section id="portofolio" >
        <h2>Portofolio</h2>
        <!-- Isi portofolio Anda -->
        <div class="slider">
            <!-- Gambar 1 -->
            <div class="slide">
                <img src="Portofolio_M Satria Jagad-images-0.jpg" alt="Gambar 1">
            </div>
            <!-- Gambar 2 -->
            <div class="slide">
                <img src="Portofolio_M Satria Jagad-images-1.jpg" alt="Gambar 2">
            </div>
            <!-- Gambar 3 -->
            <div class="slide">
                <img src="Portofolio_M Satria Jagad-images-2.jpg" alt="Gambar 3">
            </div>
            <!-- Gambar 4 -->
            <div class="slide">
                <img src="Portofolio_M Satria Jagad-images-3.jpg" alt="Gambar 4">
            </div>
            <!-- Gambar 5 -->
            <div class="slide">
                <img src="Portofolio_M Satria Jagad-images-4.jpg" alt="Gambar 5">
            </div>
            <!-- Gambar 6 -->
            <div class="slide">
                <img src="Portofolio_M Satria Jagad-images-5.jpg" alt="Gambar 6">
            </div>
            <!-- Gambar 7 -->
            <div class="slide">
                <img src="Portofolio_M Satria Jagad-images-6.jpg" alt="Gambar 7">
            </div>
            <!-- Gambar 8 -->
            <div class="slide">
                <img src="Portofolio_M Satria Jagad-images-7.jpg" alt="Gambar 8">
            </div>
        </div>
    </section>

    
    <section id="Achievement">
        <h2>Achievement</h2>
        <!-- Isi pencapaian Anda -->
        <div class="slider">
            <div class="slide">
                <img src="Achievment.png" alt="Berita 1">
                <div class="news-details">
                    <h3><a href="https://unair.ac.id/borong-medali-unair-juara-umum-kmi-expo-2022/" target="_blank">UNAIR BORONG MEDALI TERBANYAK SEBAGAI JUARA UMUM KMI EXPO 2022</a></h3>
                    <p>Pada akhir tahun 2022 saya berhasil mendapatkan medali harapan 1 bersama kontingen Universitas Airlangga</p>
                </div>
            </div>
            <div class="slide">
                <img src="Achievment.png" alt="Berita 1">
                <div class="news-details">
                    <h3><a href="link_website_2" target="_blank">Judul Berita 2</a></h3>
                    <p>Deskripsi singkat tentang berita 2.</p>   
                </div>
            </div>
            <!-- Tambahkan lebih banyak item berita sesuai kebutuhan -->
        </div>
    </section>
    

    <section id="certificate">
        <h2>Certificate</h2>
        <!-- Isi certificate Anda -->
    </section>

    <section id="contact" style="background-color: black; color: beige; padding-top: 10px; padding-bottom: 10px;">
        <h2 style="margin-top: 0; color: #fff;">Contact</h2>
        <!-- Isi informasi kontak Anda -->
        <div>
            <a href="https://www.instagram.com/msj_jagad" target="_blank"><img src="Instagram.jpg" alt="Instagram" width="25" height="25"></a>
            <br><br>
            <a href="https://www.linkedin.com/in/mohamad-satria-jagad/" target="_blank"><img src="Linkedin.jpg" alt="LinkedIn" width="25" height="25"></a>
        </div>
        <div class="bottom-border"></div> <!-- Ini adalah baris yang ditambahkan -->
    </section>

    <footer>
        <!-- Informasi tambahan footer -->
    </footer>

    <canvas id="fireworksCanvas"></canvas>
    <script>
        document.addEventListener("DOMContentLoaded", function() {
            const canvas = document.getElementById('fireworksCanvas');
            const ctx = canvas.getContext('2d');
            let particles = [];
            let canvasWidth = window.innerWidth;
            let canvasHeight = window.innerHeight;

            canvas.width = canvasWidth;
            canvas.height = canvasHeight;

            window.addEventListener('resize', function() {
                canvasWidth = window.innerWidth;
                canvasHeight = window.innerHeight;
                canvas.width = canvasWidth;
                canvas.height = canvasHeight;
            });

            function random(min, max) {
                return Math.random() * (max - min) + min;
            }

            function Particle(x, y, dx, dy, color, size) {
                this.x = x;
                this.y = y;
                this.dx = dx;
                this.dy = dy;
                this.color = color;
                this.size = size;
                this.alpha = 1;

                this.draw = function() {
                    ctx.globalAlpha = this.alpha;
                    ctx.beginPath();
                    ctx.arc(this.x, this.y, this.size, 0, Math.PI * 2);
                    ctx.fillStyle = this.color;
                    ctx.fill();
                    ctx.closePath();
                };

                this.update = function() {
                    this.x += this.dx;
                    this.y += this.dy;
                    this.alpha -= 0.01;

                    if (this.alpha <= 0) {
                        this.alpha = 0;
                    }

                    this.draw();
                };
            }

            function createFirework() {
                const fireworkX = random(0, canvasWidth);
                const fireworkY = random(0, canvasHeight / 2);
                const particleCount = 100;
                const colors = ['#ff3b3b', '#ff9a3b', '#ffc33b', '#ff573b', '#ffeb3b'];

                for (let i = 0; i < particleCount; i++) {
                    const angle = random(0, Math.PI * 2);
                    const speed = random(2, 10);
                    const dx = Math.cos(angle) * speed;
                    const dy = Math.sin(angle) * speed;
                    const color = colors[Math.floor(Math.random() * colors.length)];
                    const size = random(1, 3);
                    particles.push(new Particle(fireworkX, fireworkY, dx, dy, color, size));
                }
            }

            function animate() {
                ctx.clearRect(0, 0, canvasWidth, canvasHeight);

                particles = particles.filter(particle => particle.alpha > 0);
                particles.forEach(particle => particle.update());

                if (particles.length < 50) {
                    createFirework();
                }

                requestAnimationFrame(animate);
            }

            animate();
        });
    </script>
    <script>
        document.addEventListener("DOMContentLoaded", function() {
            const slides = document.querySelectorAll('.slide');

            slides.forEach(slide => {
                slide.addEventListener('click', function() {
                    const src = this.querySelector('img').src;

                    const overlay = document.createElement('div');
                    overlay.classList.add('overlay');

                    const img = document.createElement('img');
                    img.src = src;

                    const close = document.createElement('span');
                    close.innerHTML = '&times;';
                    close.classList.add('close');
                    close.addEventListener('click', function() {
                        overlay.remove();
                    });

                    const download = document.createElement('span');
                    download.innerHTML = '&#x2b07;';
                    download.classList.add('download');
                    download.addEventListener('click', function() {
                        const a = document.createElement('a');
                        a.href = src;
                        a.download = 'gambar';
                        document.body.appendChild(a);
                        a.click();
                        document.body.removeChild(a);
                    });

                    overlay.appendChild(img);
                    overlay.appendChild(close);
                    overlay.appendChild(download);
                    document.body.appendChild(overlay);
                });
            });
        });
    </script>
</body>
</html>
