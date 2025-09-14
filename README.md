
 <!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Poster Berita Banjarmasin</title>
  <style>
    body {
      font-family: 'Poppins', sans-serif;
      background: linear-gradient(to bottom, #023e8a, #0096c7);
      color: white;
      margin: 0;
      padding: 0;
      overflow-x: hidden;
    }

    .container {
      max-width: 900px;
      margin: auto;
      padding: 20px;
    }

    .headline {
      text-align: center;
      font-size: 2.8rem;
      font-weight: bold;
      color: #ffd60a;
      margin: 10px 0;
    }

    .subheadline {
      text-align: center;
      font-size: 1.2rem;
      margin-bottom: 30px;
    }

    .card {
      background: rgba(255, 255, 255, 0.15);
      border-radius: 15px;
      padding: 20px;
      margin-bottom: 20px;
      box-shadow: 0 4px 15px rgba(0,0,0,0.3);
      cursor: pointer;
      transition: all 0.3s ease;
    }

    .card:hover {
      transform: scale(1.02);
      box-shadow: 0 6px 25px rgba(255, 214, 10, 0.5);
    }

    .card h2 {
      font-size: 1.5rem;
      margin-bottom: 10px;
      color: #ffdd00;
    }

    .extra {
      max-height: 0;
      overflow: hidden;
      transition: max-height 0.5s ease, opacity 0.5s ease;
      opacity: 0;
      margin-top: 10px;
      font-size: 0.95rem;
      line-height: 1.4;
    }

    .card.active .extra {
      max-height: 200px; /* bisa diubah sesuai panjang konten */
      opacity: 1;
    }

    .tagline {
      text-align: center;
      font-size: 1.3rem;
      font-weight: bold;
      margin-top: 30px;
      color: #ffd60a;
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="headline">BANJARMASIN MANTAPKAN AGENDA</div>
    <div class="headline" style="color: white;">SMART RIVER CITY 2030</div>
    <div class="subheadline">
      Pemkot, DPRD, dan warga kompak atasi banjir rob demi kota sungai modern yang ramah lingkungan.
    </div>

    <div class="card">
      <h2>📍 Fakta Lapangan</h2>
      <p>>300 rumah terdampak rob tiap siklus pasang (Data BPBD)<br>
      Titik rawan: Banjarmasin Utara & Selatan</p>
      <div class="extra">
        <p>Menurut data BPBD, banjir rob paling sering terjadi pada bulan Januari–Maret.  
        Pemerintah telah menyiapkan peta rawan banjir digital untuk memudahkan evakuasi warga.</p>
      </div>
    </div>

    <div class="card">
      <h2>🏛 Langkah Pemerintah</h2>
      <p>Pemasangan pompa air baru<br>
      Normalisasi sungai & drainase<br>
      Program Smart River City 2030 disahkan dalam APBD-P 2025</p>
      <div class="extra">
        <p>Program ini juga melibatkan kerjasama dengan universitas lokal untuk riset sungai.  
        Target utama: mengurangi 50% genangan dalam 5 tahun.</p>
      </div>
    </div>

    <div class="card">
      <h2>👥 Dukungan Publik & DPRD</h2>
      <p>Musrenbang tematik banjir: warga ikut gotong royong<br>
      DPRD setuju anggaran khusus mitigasi banjir</p>
      <div class="extra">
        <p>Warga diberikan pelatihan manajemen bencana.  
        DPRD juga menekan percepatan pembangunan kanal darurat di tiga kecamatan.</p>
      </div>
    </div>

    <div class="card">
      <h2>📰 Citra Positif</h2>
      <p>Media lokal menyorot turunnya genangan<br>
      Publik menilai Pemkot responsif & visioner</p>
      <div class="extra">
        <p>Media nasional juga mulai menyoroti inovasi Banjarmasin, menjadikannya model kota sungai tangguh di Indonesia.</p>
      </div>
    </div>

    <div class="tagline">✨ Banjarmasin Menuju Kota Sungai Modern & Tangguh Banjir ✨
        <h1>Created kelompok 1</h1>
    </div>
  </div>

  <script>
    const cards = document.querySelectorAll('.card');
    cards.forEach(card => {
      card.addEventListener('click', () => {
        card.classList.toggle('active');
      });
    });
  </script>
</body>
</html>
