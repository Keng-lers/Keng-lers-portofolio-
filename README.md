<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Website Pertama Yang Di Buat Oleh @Keng-lers</title>
    <link rel="stylesheet" href="dark-blue-style.css">
</head>
<body>
    <header>
        <div class="container">
            <h1 class="logo">Dayzz_Creator<span class="highlight">.ID</span></h1>
            <nav>
                <ul>
                    <li><a href="#home">Beranda</a></li>
                    <li><a href="#about">Tentang</a></li>
                    <li><a href="#services">Layanan</a></li>
                    <li><a href="#portfolio">Filosofi</a></li>
                    <li><a href="#contact">Kontak</a></li>
                </ul>
            </nav>
            <div class="menu-toggle">
                <span></span>
                <span></span>
                <span></span>
            </div>
        </div>
    </header>

    <main>
        <section id="home" class="hero">
            <div class="container">
                <div class="hero-content">
                    <h2>Website yang di buat oleh Keng-lers</h2>
                    <p>Website yang di buat dengan keseriusan ku><</p>
                    <div class="hero-buttons">
                        <a href="#about" class="cta-button primary">Pelajari Lebih Lanjut</a>
                        <a href="#contact" class="cta-button secondary">Hubungi Kami</a>
                    </div>
                </div>
            </div>
        </section>

        <section id="about" class="about">
            <div class="container">
                <h2>Tentang Saya Sebagai Developer</h2>
                <div class="about-content">
                    <div class="about-text">
                        <p>Saya adalah pengembang Website pemula yang baru belajar ,saya tidak sendiri saya di bantu oleh teman saya.</p>
                        <p>Motivasi saya adalah, HALAH NYOCOT.</p>
                    </div>
                    <div class="about-stats">
                        <div class="stat-card">
                            <h3>0</h3>
                            <p>Proyek Selesai</p>
                        </div>
                        <div class="stat-card">
                            <h3>0</h3>
                            <p>Belum Ada Klayen</p>
                        </div>
                        <div class="stat-card">
                            <h3>0</h3>
                            <p>Support</p>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <section id="services" class="services">
            <div class="container">
                <h2>Layanan Kami</h2>
                <div class="services-grid">
                    <div class="service-card">
                        <div class="service-icon">💻</div>
                        <h3>Desain Web</h3>
                        <p>Desain website modern dan responsif dengan tema MODEREN dan simpel</p>
                    </div>
                    <div class="service-card">
                        <div class="service-icon">🎨</div>
                        <h3>Melayani</h3>
                        <p>Pembuatab website Dan juga melayani DESAINGRAFIS</p>
                    </div>
                    <div class="service-card">
                        <div class="service-icon">⚙️</div>
                        <h3>Pengembangan</h3>
                        <p>Pengembangan Website adalah suatu ilmu yang harus di pelajari.</p>
                    </div>
                    <div class="service-card">
                        <div class="service-icon">📱</div>
                        <h3>Mobile Friendly</h3>
                        <p>Website yang tampil sempurna di semua perangkat dengan tema moderen dan konsisten.</p>
                    </div>
                </div>
            </div>
        </section>

        <section id="portfolio" class="portfolio">
            <div class="container">
                <h2>Filosofi</h2>
                <div class="portfolio-grid">
                    <div class="portfolio-item">
                        <div class="portfolio-overlay">
                            <h3>"Be Yourself"</h3>
                            <p>Milenial cenderung menghargai keunikan dan jati diri.</p>
                        </div>
                    </div>
                    <div class="portfolio-item">
                        <div class="portfolio-overlay">
                            <h3>"Think Global. Act Local"</h3>
                            <p>Tidak hanya fokus pada kesuksesan materi, taoi juga kesejahteraan batin.</p>
                        </div>
                    </div>
                    <div class="portfolio-item">
                        <div class="portfolio-overlay">
                            <h3>"Digital Firs"</h3>
                            <p>Teknologi sebagai bagian hidup tak bisa lepas dari internet</p>
                        </div>
                    </div>
                    <div class="portfolio-item">
                        <div class="portfolio-overlay">
                            <h3>"Porpose Over Profit"</h3>
                            <p>Banyak milenial memilig pekerjaan atau bisnis yang bermakna sosial.</p>
                        </div>
                    </div>
                </div>
            </div>
        </section>
    </main>

    <footer id="contact">
        <div class="container">
            <div class="footer-content">
                <div class="footer-section">
                    <h3>Keng-lers</h3>
                    <p>Tetap semangat,jangan menyerah.</p>
                    <div class="social-links">
                        <a href="#" class="social-icon">📘</a>
                        <a href="#" class="social-icon">🐦</a>
                        <a href="#" class="social-icon">📸</a>
                        <a href="#" class="social-icon">▶️</a>
                    </div>
                </div>
                <div class="footer-section">
                    <h3>Kontak</h3>
                    <p>Email: barokbarok882@gmail.com</p>
                    <p>Telepon: +62 81316447919</p>
                </div>
                <div class="footer-section">
                    <h3>Lokasi</h3>
                    <p>KalimantanTimur</p>
                </div>
            </div>
            <div class="footer-bottom">
                <p>&copy; 2025 Keng-ler. Hak Cipta Dilindungi.</p>
            </div>
        </div>
    </footer>

    <script>
        // Toggle mobile menu
        const menuToggle = document.querySelector('.menu-toggle');
        const nav = document.querySelector('nav ul');
        
        menuToggle.addEventListener('click', () => {
            nav.classList.toggle('active');
        });
    </script>
</body>
</html>
