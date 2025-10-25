<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Eco Enzyme: Solusi Alami & Berkelanjutan 🌿</title>

  <meta name="description" content="Pelajari Eco Enzyme, solusi alami untuk mengubah limbah dapur menjadi cairan ramah lingkungan. Tutorial lengkap & manfaatnya di sini.">
  <meta name="keywords" content="eco enzyme, cara membuat eco enzyme, manfaat eco enzyme, fermentasi alami, ramah lingkungan">
  <meta name="author" content="Eco Enzyme Nusantara">

  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css" integrity="sha512-Fo3rlrZj/k7ujTnHg4C9m4pA4B8/I1z611L+q8h5M14H0rQe1gD17M5p8rGqXh/pB+2c5hG/QGvE5/v/1g==" crossorigin="anonymous" referrerpolicy="no-referrer" />

  <style>
    /* RESET & FONT */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Poppins', sans-serif;
      line-height: 1.7; /* Sedikit ditingkatkan untuk keterbacaan */
      color: #2f3e46;
      background-color: #f8f9fa;
      scroll-behavior: smooth;
    }

    /* UTILITY CLASSES */
    .container {
      max-width: 1100px;
      margin: auto;
      padding: 0 15px; /* Menambahkan padding horizontal untuk responsivitas */
    }

    /* NAVBAR */
    .navbar {
      background-color: #1b5e20; /* Warna hijau yang lebih gelap */
      color: white;
      position: sticky;
      top: 0;
      z-index: 1000;
      box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
    }

    .navbar .container {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 1rem 1rem;
    }

    .navbar h1 {
      font-size: 1.6rem;
      font-weight: 700;
    }

    .navbar ul {
      list-style: none;
      display: flex;
      gap: 1.8rem;
    }

    .navbar a {
      color: white;
      text-decoration: none;
      font-weight: 500;
      transition: color 0.3s;
      position: relative;
    }

    .navbar a:hover {
      color: #a5d6a7;
    }

    /* Hamburger Menu (New Feature for Mobile) */
    .menu-toggle {
        display: none;
        font-size: 1.5rem;
        cursor: pointer;
    }

    /* HERO SECTION */
    .hero-section {
      /* GAMBAR LATAR BELAKANG BARU */
      background: url('https://images.unsplash.com/photo-1549487922-811c79c29af0?auto=format&fit=crop&q=80&w=1600&h=900') center/cover no-repeat; 
      height: 90vh;
      display: flex;
      justify-content: center;
      align-items: center;
      text-align: center;
      color: white;
      overflow: hidden;
      position: relative;
    }

    .hero-overlay {
      position: absolute;
      top: 0; left: 0; right: 0; bottom: 0;
      background: rgba(0, 0, 0, 0.5); /* Overlay lebih gelap */
      backdrop-filter: blur(1px); /* Efek blur ringan */
    }

    .hero-content {
      position: relative;
      z-index: 2;
      max-width: 800px;
      padding: 0 20px;
      animation: fadeUp 1.5s ease-out;
    }

    .hero-content h2 {
      font-size: clamp(2rem, 5vw, 3.5rem); /* Ukuran responsif */
      margin-bottom: 1.5rem;
      font-weight: 700;
      text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
    }

    .hero-content p {
      margin-bottom: 2rem;
      font-weight: 400;
      font-size: 1.1rem;
    }

    .cta-button {
      background: #81c784;
      color: #fff;
      padding: 1rem 2.2rem;
      border-radius: 50px;
      font-weight: 600;
      transition: all 0.4s ease;
      text-decoration: none;
      display: inline-block;
      box-shadow: 0 4px 15px rgba(0, 150, 0, 0.3);
    }

    .cta-button:hover {
      background: #4caf50;
      transform: translateY(-3px) scale(1.02);
      box-shadow: 0 6px 20px rgba(0, 150, 0, 0.5);
    }

    /* CONTENT SECTIONS */
    .content-section {
      padding: 100px 0; /* Padding vertikal ditingkatkan */
    }

    .alternate-bg {
      background-color: #e8f5e9;
    }

    h3 {
      text-align: center;
      margin-bottom: 40px;
      color: #1b5e20;
      font-size: 2rem;
      font-weight: 600;
    }

    p {
      text-align: justify;
      margin-bottom: 15px;
    }
    
    .text-center {
        text-align: center;
    }

    /* MANFAAT GRID */
    .manfaat-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 30px;
      margin-top: 20px;
    }

    .manfaat-item {
      background: white;
      border-radius: 18px;
      padding: 30px;
      box-shadow: 0 5px 20px rgba(0,0,0,0.08);
      transition: transform 0.4s ease, box-shadow 0.4s ease;
      border-left: 5px solid #4caf50;
    }

    .manfaat-item:hover {
      transform: translateY(-10px);
      box-shadow: 0 10px 30px rgba(0,0,0,0.15);
    }

    .manfaat-item h4 {
        font-size: 1.25rem;
        margin-bottom: 10px;
        color: #2e7d32;
    }

    .italic {
      font-style: italic;
      text-align: center;
      margin-bottom: 30px;
      font-size: 1.1rem;
      color: #4caf50;
    }

    /* CARA BUAT LIST */
    .langkah-list {
      max-width: 800px;
      margin: 0 auto;
      list-style: none; /* Menghapus bullet default */
      padding-left: 0;
      line-height: 1.8;
      counter-reset: step-counter; /* Mengatur counter */
    }
    
    .langkah-list li {
        margin-bottom: 20px;
        position: relative;
        padding-left: 45px;
    }

    .langkah-list li::before {
        counter-increment: step-counter;
        content: counter(step-counter);
        position: absolute;
        left: 0;
        top: 0;
        width: 30px;
        height: 30px;
        background-color: #2e7d32;
        color: white;
        border-radius: 50%;
        display: flex;
        justify-content: center;
        align-items: center;
        font-weight: bold;
        font-size: 1.1rem;
    }

    /* VIDEO SECTION */
    .video-container {
      position: relative;
      padding-bottom: 56.25%;
      height: 0;
      max-width: 800px;
      margin: 0 auto;
    }

    .video-container iframe {
      position: absolute;
      width: 100%;
      height: 100%;
      border-radius: 15px;
      box-shadow: 0 10px 30px rgba(0, 0, 0, 0.15);
    }

    /* FOOTER */
    footer {
      background: #1b5e20;
      color: white;
      text-align: center;
      padding: 30px 10px;
      font-size: 0.95rem;
    }

    /* BACK TO TOP BUTTON (New Feature) */
    #back-to-top {
        position: fixed;
        bottom: 30px;
        right: 30px;
        background-color: #4caf50;
        color: white;
        border: none;
        border-radius: 50%;
        width: 50px;
        height: 50px;
        font-size: 1.5rem;
        cursor: pointer;
        opacity: 0;
        visibility: hidden;
        transition: opacity 0.3s, visibility 0.3s, transform 0.3s;
        box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
    }

    #back-to-top.show {
        opacity: 1;
        visibility: visible;
        transform: translateY(0);
    }
    
    #back-to-top:hover {
        background-color: #2e7d32;
        transform: scale(1.1);
    }

    /* ANIMATIONS */
    @keyframes fadeUp {
      from { opacity: 0; transform: translateY(40px); }
      to { opacity: 1; transform: translateY(0); }
    }

    /* Enhanced Fade-in Animation */
    .fade-in {
      opacity: 0;
      transform: translateY(30px); /* Jarak pergerakan lebih pendek */
      transition: opacity 1.2s cubic-bezier(0.175, 0.885, 0.32, 1.275), transform 1.2s cubic-bezier(0.175, 0.885, 0.32, 1.275); /* Transisi lebih halus dan 'bouncy' */
    }

    .fade-in.visible {
      opacity: 1;
      transform: translateY(0);
    }

    /* RESPONSIVE */
    @media (max-width: 768px) {
      .navbar .container {
        flex-direction: row;
      }
      
      .navbar ul {
          display: none; /* Sembunyikan menu navigasi di mobile */
          flex-direction: column;
          width: 100%;
          text-align: center;
          background-color: #1b5e20;
          position: absolute;
          top: 60px; /* Di bawah navbar */
          left: 0;
          padding-bottom: 10px;
      }
      
      .navbar ul.active {
          display: flex; /* Tampilkan saat aktif */
      }
      
      .navbar ul li {
          margin: 10px 0;
      }

      .menu-toggle {
          display: block; /* Tampilkan tombol hamburger */
      }

      .hero-section {
          height: 70vh;
      }

      .hero-content h2 {
        font-size: 2rem;
      }
      
      .content-section {
          padding: 60px 0;
      }

      h3 {
          font-size: 1.5rem;
      }
      
      .langkah-list li {
          padding-left: 35px;
      }
      
      .langkah-list li::before {
          width: 25px;
          height: 25px;
          font-size: 1rem;
      }
    }
  </style>
</head>
<body>
  <header class="navbar">
    <nav class="container">
      <h1>🌿 Eco Enzyme</h1>
      <button class="menu-toggle" aria-label="Toggle Navigation">
        <i class="fas fa-bars"></i>
      </button>
      <ul id="nav-menu">
        <li><a href="#tentang">Tentang</a></li>
        <li><a href="#manfaat">Manfaat</a></li>
        <li><a href="#cara-buat">Cara Membuat</a></li>
        <li><a href="#video">Video</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <section id="hero" class="hero-section">
      <div class="hero-overlay"></div>
      <div class="hero-content">
        <h2>Eco Enzyme: Keajaiban dari Sisa Dapur 🌎</h2>
        <p>Ubah **limbah organik** menjadi cairan multiguna yang **ramah lingkungan**. Langkah kecil Anda, dampak besar bagi Bumi.</p>
        <a href="#cara-buat" class="cta-button">Pelajari Proses Pembuatan</a>
      </div>
    </section>

    <section id="tentang" class="content-section">
      <div class="container fade-in">
        <h3><i class="fas fa-seedling"></i> Apa Itu Eco Enzyme?</h3>
        <p>Eco Enzyme (EE) adalah hasil **fermentasi** dari sisa kulit buah/sayuran, gula (gula merah/molase), dan air. Ditemukan oleh Dr. Rosukon Poompanvong di Thailand, cairan ini merupakan solusi alami untuk mengurangi polusi udara, air, dan tanah.</p>
        <p>Cairan ini bekerja sebagai **katalisator alami** yang membantu mendegradasi zat kimia dan racun di lingkungan, mengubahnya menjadi bahan yang bermanfaat dan aman. Proses ini tidak hanya mengurangi sampah, tetapi juga menghasilkan produk pembersih dan pupuk yang **bebas bahan kimia berbahaya**.</p>
      </div>
    </section>

    <section id="manfaat" class="content-section alternate-bg">
      <div class="container fade-in">
        <h3><i class="fas fa-hand-holding-heart"></i> Segudang Manfaat Eco Enzyme</h3>
        <div class="manfaat-grid">
          <div class="manfaat-item">
            <h4>♻️ Mengurangi Sampah</h4>
            <p>Mengurangi beban TPA dengan memanfaatkan hingga **90% sisa organik dapur** menjadi cairan bermanfaat.</p>
          </div>
          <div class="manfaat-item">
            <h4>💧 Pembersih Rumah Tangga</h4>
            <p>Aman menggantikan deterjen, sabun cuci piring, dan cairan pembersih lantai komersial tanpa meninggalkan residu kimia.</p>
          </div>
          <div class="manfaat-item">
            <h4>🌱 Penyubur Tanaman</h4>
            <p>Sebagai **pupuk cair organik** yang menyuburkan tanah, melindungi tanaman dari hama, dan meningkatkan hasil panen alami.</p>
          </div>
          <div class="manfaat-item">
            <h4>🌬️ Terapi Udara & Air</h4>
            <p>Menjernihkan udara dari bau tak sedap dan membantu **menjernihkan air limbah** rumah tangga saat dialirkan ke saluran air.</p>
          </div>
        </div>
      </div>
    </section>

    <section id="cara-buat" class="content-section">
      <div class="container fade-in">
        <h3><i class="fas fa-flask"></i> Langkah Praktis Membuat Eco Enzyme di Rumah</h3>
        <p class="italic">**Rasio Emas:** Gula : Sisa Organik : Air = **1 : 3 : 10** (berdasarkan berat)</p>
        <ol class="langkah-list">
          <li><strong>Siapkan Bahan:</strong> 1 bagian Gula Merah (Molase), 3 bagian Sisa Kulit Buah/Sayur (harus bersih dan tidak berminyak), 10 bagian Air Bersih.</li>
          <li><strong>Campurkan ke Wadah:</strong> Larutkan gula dalam air di **wadah plastik** tertutup (jangan gunakan wadah kaca, karena gas dapat memecahkannya).</li>
          <li><strong>Masukkan Sampah:</strong> Tambahkan kulit buah/sayur dan pastikan **sisakan ruang $\frac{1}{3}$** wadah untuk gas fermentasi.</li>
          <li><strong>Tutup Rapat & Label:</strong> Tulis tanggal pembuatan dan tanggal panen (**3 bulan** kemudian).</li>
          <li><strong>Buka Tutup Minggu Pertama:</strong> Buka sedikit setiap hari (atau setiap beberapa hari) untuk **membuang gas** yang terbentuk.</li>
          <li><strong>Fermentasi 3 Bulan:</strong> Simpan di tempat sejuk, teduh, dan memiliki ventilasi yang baik. Jangan dibuka selama proses fermentasi, kecuali untuk pengecekan.</li>
          <li><strong>Panen:</strong> Saring cairan—itulah **Eco Enzyme**! Ampasnya bisa dikeringkan dan menjadi pupuk padat alami.</li>
        </ol>
      </div>
    </section>

    <section id="video" class="content-section alternate-bg">
      <div class="container fade-in">
        <h3><i class="fas fa-video"></i> Video Tutorial Pembuatan Eco Enzyme</h3>
        <p class="text-center">Tonton video di bawah ini untuk panduan visual yang jelas dan mudah diikuti dalam membuat Eco Enzyme.</p>
        <div class="video-container">
          <iframe 
            src="https://www.youtube.com/embed/3zAoGn2T4WY?si=HqS92oG4J1TjNlWz"
            title="YouTube video player"
            frameborder="0"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
            allowfullscreen
          ></iframe>
        </div>
      </div>
    </section>
  </main>

  <footer>
    <div class="container">
      <p>&copy; 2025 Eco Enzyme Nusantara. Dibuat dengan semangat berkelanjutan. 🌿 | <a href="#" style="color: #a5d6a7;">Kebijakan Privasi</a></p>
    </div>
  </footer>

  <button id="back-to-top" aria-label="Kembali ke Atas">
      <i class="fas fa-arrow-up"></i>
  </button>

  <script>
    // Smooth scroll
    document.querySelectorAll('a[href^="#"]').forEach(anchor => {
      anchor.addEventListener('click', function(e) {
        e.preventDefault();
        const targetId = this.getAttribute('href');
        document.querySelector(targetId).scrollIntoView({
          behavior: 'smooth'
        });
        
        // Close mobile menu after clicking a link
        if (window.innerWidth <= 768) {
            document.getElementById('nav-menu').classList.remove('active');
        }
      });
    });

    // Enhanced Fade-in animation on scroll
    const fadeInElements = document.querySelectorAll('.fade-in');

    const observer = new IntersectionObserver(entries => {
      entries.forEach(entry => {
        // Hanya tambahkan kelas 'visible' sekali saat elemen terlihat
        if (entry.isIntersecting) {
            entry.target.classList.add('visible');
            observer.unobserve(entry.target); // Hentikan observasi setelah terlihat
        }
      });
    }, {
        rootMargin: '0px 0px -100px 0px' // Mulai animasi 100px sebelum elemen masuk viewport
    });

    fadeInElements.forEach(el => observer.observe(el));

    // Back to Top Button Logic (New Feature)
    const backToTopButton = document.getElementById('back-to-top');

    window.addEventListener('scroll', () => {
        if (window.scrollY > 300) { // Tampilkan tombol setelah menggulir 300px
            backToTopButton.classList.add('show');
        } else {
            backToTopButton.classList.remove('show');
        }
    });

    backToTopButton.addEventListener('click', () => {
        window.scrollTo({
            top: 0,
            behavior: 'smooth'
        });
    });

    // Mobile Menu Toggle (New Feature)
    const menuToggle = document.querySelector('.menu-toggle');
    const navMenu = document.getElementById('nav-menu');

    menuToggle.addEventListener('click', () => {
        navMenu.classList.toggle('active');
        // Ganti ikon hamburger menjadi ikon close (opsional)
        const icon = menuToggle.querySelector('i');
        if (navMenu.classList.contains('active')) {
            icon.classList.remove('fa-bars');
            icon.classList.add('fa-times');
        } else {
            icon.classList.remove('fa-times');
            icon.classList.add('fa-bars');
        }
    });
  </script>
</body>
</html>
