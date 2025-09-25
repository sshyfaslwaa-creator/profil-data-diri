
<html lang="id">
<head>
  <link href="https://fonts.googleapis.com/css2?family=Mea+Culpa&display=swap" rel="stylesheet">
  <link href="https://fonts.googleapis.com/css2?family=Vollkorn&display=swap" rel="stylesheet">
  <link href="https://fonts.googleapis.com/css2?family=Barriecito&display=swap" rel="stylesheet">
  <link href="https://fonts.googleapis.com/css2?family=Amethysta&display=swap" rel="stylesheet">
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Data Diri Shyfa Mannawasalwa</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: 'Segoe UI', sans-serif;
      background: linear-gradient(135deg, #f8e1f4, #e0f0ff, #F990B8);
      color: #333;
      overflow-x: hidden;
      position: relative;
    }

    /* Efek Kilauan */
    body::before {
      content: '';
      position: absolute;
      top: -50%;
      left: -50%;
      width: 200%;
      height: 200%;
      background: radial-gradient(circle, rgba(255,255,255,0.4) 0%, transparent 70%);
      animation: sparkle 10s linear infinite;
      pointer-events: none;
      z-index: 1;
    }

    @keyframes sparkle {
      0% { transform: rotate(0deg) translateX(0); }
      100% { transform: rotate(360deg) translateX(0); }
    }

    .container {
      position: relative;
      z-index: 2;
      max-width: 600px;
      margin: 50px auto;
      padding: 30px;
      /background: white;/
      border-radius: 20px;
      box-shadow: 0 10px 25px rgba(0,0,0,0.1);
    }

    .profile-flex {
      display: flex;
      align-items: center;
      justify-content: center; /* <--- ubah dari flex-start ke center */
      gap: 30px;
      max-width: 600px;
      margin: 0 auto 30px auto;
    }

    .profile-flex .profile-pic {
      margin: 0;      /* Hapus margin auto */
      display: block;
    }

    .profile-flex h1 {
      text-align: left; /* Pastikan teks rata kiri */
      margin: 0;
      font-size: 50px;
      font-family: 'Mea Culpa';
      color: #F990B8;
    }
    
    .profile-pic {
      width: 220px;
      height: 220px;
      border-radius: 50%;
      object-fit: cover;
      border: 4px solid #F990B8;
      box-shadow: 0 0 10px rgba(1,1,1,1);
      margin: 0 auto;
      display: block;
    }
    
    img[alt="Foto Shyfa"] {
     display: block;
     margin-left: auto;
     margin-right: auto;
    }
    
    .section-white {
     background: none;
     box-shadow: none;
     padding: 0;
     border-radius: 0;
     max-width: 600px;
     margin-left: auto;
     margin-right: auto;
    }

    h1 {
     text-align: center;
     color: #F990B8;
     font-family: 'Mea Culpa';
     font-size: 50px;
    }
    
    h2 {
     text-align: center;
     margin-left: 30px; /* atau coba 40px, sesuaikan */
     color: #7d2ae8;
     font-family: 'Vollkorn';
     font-size: 40px;
    }

    h3 {
     text-align: center; 
     color: #F990B8;
     font-family: 'Barriecito', cursive;
     font-size: 50px;
     letter-spacing: 10px;    /* Jarak antar huruf */
     word-spacing: 5px;      /* Jarak antar kata */
     margin-left: auto;
     margin-right: auto;
    }
     
    p {
     text-align: center;
     color: #1E0959 ;
     font-family: 'Amethysta';
     font-size: 20px ;
     max-width: 600px;
     margin-left: auto;
     margin-right: auto;
    }
     
    .info-flex {
     text-align: center;
     display: flex;
     gap: 32px; /* jarak antar kotak */
     max-width: 1000px;
     margin: 0 auto 30px auto;
     align-items: flex-start;
    }
    
    .tentang-box, .pendidikan-box {
     flex: 1 1 0;
     min-width: 0;
     text-align: center;
    }
    
    .pendidikan-item {  
     margin-left: 0;
     text-align: center;
    }
    
    .pendidikan-box h2 {
     margin-left: 0;
     text-align: center;
    }
    
    .pendidikan-box p {
     text-align: center;
     margin-left: 0;
     margin-left: auto;
     margin-right: auto;
    }
    
    .hobi-box {
     flex: 1 1 0;
     min-width: 0;
     text-align: center;
    }
    
    .softskills-box {
     flex: 1 1 0;
     min-width: 0;
     text-align: center;
    }
     
    .nama-box {
     display: block;
     text-align: center;
     margin-left: auto;
     margin-right: auto;
     background: #fff;
     border-radius: 16px;
     box-shadow: 0 4px 16px rgba(0,0,0,0.12);
     padding: 25px 25px;
     max-width: 500px;
     font-family: 'Amethysta';
     font-size: 20px;
     color: #1E0959;
    } 
     
     span {
      text-align: center;
      color:#1E0959 ;
      font-family: 'Amethysta';
      font-size: 20px;
      max-width: 500px;
      margin-left: auto;
      margin-right: auto;
     }
     
     .pendidikan-item {   
      display: block;
      text-align: center;
      margin-left: auto;
  margin-right: auto;
  max-width: 500px;
  background: #fff;
  border-radius: 16px;
  box-shadow: 0 4px 16px rgba(0,0,0,0.12);
  padding: 25px;
  font-family: 'Amethysta';
  font-size: 20px;
  color: #1E0959;
     }

.hobi-box { 
  display: block;
     text-align: center;
     margin-left: auto;
     margin-right: auto;
     background: #fff;
     border-radius: 16px;
     box-shadow: 0 2px 16px rgba(0,0,0,0.12);
     padding: 25px 25px;
     max-width: 500px;
     font-family: 'Amethysta';
     font-size: 20px;
     color: #1E0959;
    } 

.softskills-box {
display: block;
     text-align: center;
     margin-left: auto;
     margin-right: auto;
     background: #fff;
     border-radius: 16px;
     box-shadow: 0 2px 16px rgba(0,0,0,0.12);
     padding: 25px 25px;
     max-width: 500px;
     font-family: 'Amethysta';
     font-size: 20px;
     color: #1E0959;
    } 

  


.quote {
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  font-style: italic;
  color: #555;
  max-width: 600px;
  margin-left: auto; 
  margin-right: auto;;
  height: 80px; /* opsional */
}
     
    .contact-title {
  text-align: center;
  margin-left: auto;
  margin-right: auto;
}

    .info {
      margin-top: 10px;
      line-height: 1.2;
      font-size: 15px;
    }

    .footer {
      text-align: center;
      margin-top: 30px;
      font-size: 14px;
      color: #777;
    }

    @media (max-width: 600px) {
      .info strong {
        display: block;
        width: auto;
        margin-top: 10px;
      }
    }
  </style>
</head>
<body>
  
  <div class="profile-flex">
  <img src="https://uploads.onecompiler.io/43w7wuzdj/43xp6335j/cici.jpg" class="profile-pic">
  <div>
    <h1>hi, i'm Shyfa!</h1>
    <div class="section-white">
      <p>orangnya ceria dan optimis, tapi kadang-kadang terlalu perfeksionis. Meskipun begitu, selalu berusaha belajar dan berkembang menjadi lebih baik. Senang mencoba hal-hal baru dan mudah berbaur.</p>
    </div>
  </div>
</div>
  
  <div class="info-flex">
  <div class="tentang-box">
    <h2>tentang saya</h2>
    <span class="nama-box">
      nama saya
      <span style="color:#1E095;"><b>Shyfa Mannawasalwa</b></span>, biasanya dipanggil 
      <span style="color:#1E095;"><b>Shyfa</b></span> lahir di 
      <span style="color:#1E095;"><b>Batam, 30 Mei 2009</b></span>. 
      saya tinggal di Nongsa, Sambau. Seorang siswi  SMK Negeri 7 jurusan 
      <span style="color:#1E095;"><b>Rekayasa Perangkat Lunak</b></span> yang tertarik pada teknologi dan digital khususnya pada bidang pemrograman, data analis, dan keamaan digital.
</span>
  </div>
</div>

  <div class="info-flex">
  <div class="pendidikan-box">
    <h2>📚 Pendidikan 📚</h2>
    <p class="pendidikan-item">SD Negeri 001 Batam (2016-2022)</p>
    <p class="pendidikan-item">SMP Negeri 8 Batam (2022-2025)</p>
    <p class="pendidikan-item">SMK Negeri 7 Batam (2025-sekarang)</p>

  </div>
</div>

<div class="info-flex">
  <div class="tentang-box">
    <h2>pengalaman organisasi</h2>
    <span class="nama-box">
      Ketua divisi Dokumentasi & Publikasi PIK-R SPENDELCARE (2024-2025)
</span>
  </div>
</div>

<div class="info-flex">
  <div class="hobi-box">
    <h2>Hobi</h2>
    <p>🎧 mendengarkan musik</p>
    <p>🎬 menonton film</p>
    <p>🎣 memancing</p>
    <p>🎨 menggambar</p>
  </div>
</div>

<div class="info-flex">
  <div class="softskills-box">
    <h2>Soft Skills</h2>
    <p>✓ communication     ✓ teamwork</p>
    <p>✓ leadership        ✓ time management</p>
    <p>✓ creativity        ✓ adaptability</p>
    <p>✓ basic canva, capcut, word, wps office, coding</p>
  </div>
</div>
      
    <p class="quote">"Belajar bukan tentang menjadi yang terbaik, tetapi tentang menjadi lebih baik dari dirimu yang kemarin."</p>

      
    <h2 class="contact-title">contact</h2>
<p>
  <a href="https://wa.me/6282392996788" target="_blank" style="color:#25D366; text-decoration:none; font-size:22px;">
    WhatsApp
  </a>
  &nbsp;|&nbsp;
  <a href="https://instagram.com/shyfamslwaa" target="_blank" style="color:#BE27F5; text-decoration:none; font-size:22px;">
    Instagram
  </a>
  &nbsp;|&nbsp;
  <a href="https://www.tiktok.com/@bipb1pp" target="_blank" style="color:#010101; text-decoration:none; font-size:22px;">
    TikTok
  </a>
  &nbsp;|&nbsp;
  <a href="mailto:mannawasalwashyfa@gmail.com" style="color:#0072C6; text-decoration:none; font-size:22px;">
    Email
  </a>
</p>  
    

    <div class="footer">
      salam kenal ya! 🌸
    </div>

</body>
</html>
