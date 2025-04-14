<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>UTS Sistem Multimedia</title>
  <style>
    html {
      scroll-behavior: smooth;
    }

    body {
      font-family: Arial, sans-serif;
      margin: 0;
    }

    nav {
      background-color: #333;
      padding: 10px;
      position: sticky;
      top: 0;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin-right: 15px;
      font-weight: bold;
    }

    nav a:hover {
      text-decoration: underline;
    }

    section {
      padding: 60px 20px;
      border-bottom: 1px solid #ddd;
    }

    h2 {
      margin-top: 0;
    }

    /* Styling untuk tombol Spotify */
    .spotify-btn {
      background-color: #1DB954;
      color: white;
      padding: 10px 20px;
      border: none;
      border-radius: 5px;
      font-size: 16px;
      text-decoration: none;
    }
    .spotify-btn:hover {
      background-color: #1ed760;
    }
  </style>
</head>
<body>

<!-- NAVIGASI -->
<nav>
  <a href="#gambar">Gambar</a>
  <a href="#suara">Suara</a>
  <a href="#dokumen">Makalah</a>
  <a href="#spotify">Spotify</a>
</nav>

<!-- BAGIAN Gambar -->
<section id="gambar">
  <h2>📷 Gambar</h2>
  <img src="assets/images/ur.jpg" alt="Foto Profil" width="300">
</section>

<!-- BAGIAN Suara -->
<section id="suara">
  <h2>🔊 Suara</h2>
  <audio controls>
    <source src="assets/audio/suara-pembukaan.mp3" type="audio/mpeg">
    Browser tidak mendukung audio.
  </audio>
</section>

<!-- BAGIAN Dokumen -->
<section id="dokumen">
  <h2>📄 Makalah</h2>
  <embed src="assets/docs/SISMUL_UTS.pdf" type="application/pdf" width="100%" height="500px" />
  <p><a href="assets/docs/SISMUL_UTS.pdf" download>Download Makalah</a></p>
</section>

<!-- BAGIAN Spotify -->
<section id="spotify">
  <h2>🎧 Spotify</h2>
  <!-- Embed Spotify Track -->
 <iframe style="border-radius:12px" src="https://open.spotify.com/embed/track/44qlcokPO2RjD8791ohJFR?utm_source=generator" width="100%" height="352" frameBorder="0" allowfullscreen="" allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture" loading="lazy"></iframe>

  <!-- Tombol untuk buka Spotify -->
  <br><br>
  <a href="https://open.spotify.com/track/4cOdyWpLr2l5OmlsREigxk" target="_blank" class="spotify-btn">Dengarkan di Spotify</a>
</section>

</body>
</html>
