# Tugas1_Pemrograman-web-dasar_41246929


  <!-- 1. Struktur Dasar -->
  
  <p><em>Halaman ini dibuat untuk memenuhi tugas praktikum sesi 1–14.</em></p>

  <!-- 2. Heading & Paragraf -->
  <h2>Tujuan</h2>
  <p>Mahasiswa dapat membuat tabel data yang terstruktur menggunakan elemen HTML.</p>

  <!-- 3. Teks Khusus -->
  <p>Contoh dalam kimia: H₂O, NaCl.
  <p>Teks <u>garis bawah</u> untuk contoh.</p>

  <!-- 4. Pemisah Konten -->
  <hr>

  <!-- 5. Penekanan & Kutipan -->
  <p><strong>Penting:</strong> Struktur HTML harus rapi agar website mudah dipahami.</p>
  <blockquote>“Ngoding HTML kadang monoton, tapi hasilnya bikin lega.”</blockquote>

  <!-- 6. Extra Tags -->
  <section>
    <p>Waktu dibuat: <time datetime="2025-08-28">1 September 2025</time></p>
    <code>&lt;html&gt; &lt;/html&gt;</code>
  </section>

  <!-- 7. List -->
  <h2>Daftar Materi</h2>
  <ul>
    <li>Struktur Dasar</li>
    <li>Heading</li>
    <li>Paragraf</li>
  </ul>

  <!-- 8. Link & Multipage -->
  <h2>Link</h2>
  <p>Kunjungi <a href="https://www.wikipedia.org" target="_blank" rel="noopener">Wikipedia</a>.</p>
  <nav>
    <a href="#gambar">Gambar</a> | 
    <a href="#video">Video</a> | 
    <a href="#audio">Audio</a>
  </nav>

  <!-- 9. Atribut -->
  <p title="Tooltip contoh">Arahkan kursor ke teks ini untuk melihat atribut <code>title</code>.</p>

  <!-- 10. Tabel -->
  <h2>Daftar Buku Perpustakaan</h2>
  <table>
    <tr><th>Judul</th><th>Penulis</th><th>Tahun</th></tr>
    <tr><td>Pemrograman Python</td><td>Nedd</td><td>2023</td></tr>
    <tr><td>Pemrograman Java</td><td>Jill</td><td>2022</td></tr>
  </table>

  <!-- 11. Form -->
  <h2>Formulir Pendaftaran</h2>
  <form>
    <label for="nama">Nama:</label> <input type="text" id="nama" name="nama" placeholder="Masukkan nama Anda" title="Nama lengkap"><br><br>
    <label for="email">Email:</label> <input type="email" id="email" name="email" title="Masukkan alamat email Anda" placeholder="Masukkan email Anda"><br><br>
    Gender: 
      <input type="radio" id="genderL" name="gender" value="L" title="Pilih Laki-laki">
      <label for="genderL">Laki-laki</label>
      <input type="radio" id="genderP" name="gender" value="P" title="Pilih Perempuan">
      <label for="genderP">Perempuan</label><br><br>
    <input type="submit" value="Submit">
    <input type="reset" value="Reset">
  </form>

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
 
</head>
<body>

  <div class="header">
    <h1>History of Python</h1>
    <p>Directed by Guido van Rossum (Father of Python)</p>
  </div>

  <div class="section">
    <h2>Movie Synopsis</h2>
    <div class="synopsis">
      <p>
        In the early 1990s, Guido van Rossum, a Dutch programmer,
        decided to create a new programming language during Christmas holidays.
        His goal was to design a language that was simple, readable,
        and could help developers write code more efficiently.
        This is how Python was born — a language that combined power and simplicity.
      </p>
      <p>
        Over the years, Python grew rapidly, being used for web development,
        data science, artificial intelligence, and education.
        Its philosophy of readability and ease of use
        made it one of the most popular programming languages in the world today.
      </p>
      <img src="https://www.python.org/static/community_logos/python-logo.png" alt="Python Logo">
    </div>

   <div class="info">
      <p>First Released: February 20, 1991</p>
      <p>Creator: Guido van Rossum</p>
      <p>Genres: Programming, Open Source, Community</p>
    </div>

  <div class="characters">
      <div>
        <img src="https://gvanrossum.github.io/images/guido-headshot-2019.jpg">
        <p>Guido van Rossum</p>
      </div>
      <div>
        <img src="https://www.python.org/static/community_logos/python-powered-h-140x182.png" alt="Python">
        <p>Python Language</p>
      </div>
    </div>
  </div>

</body>
</html>



<!-- 13. Video -->
<h2 id="video">Video</h2>
<iframe width="400" height="225" class="custom-iframe"
    src="https://youtu.be/J0Aq44Pze-w?si=vFrv0FGsbU-FXqNT"
    title="Kisah Python, oleh Penciptanya, Guido van Rossum"
    frameborder="0"
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
    allowfullscreen>
  </iframe>
<div class="video-container">
  </div>
</div>

  <!-- 14. Audio -->
  <h2 id="audio">Audio</h2>
  <audio controls>
    <source src="https://youtu.be/xxpg9_2on3I?si=fK0IGzrHr_LPGqhX">
  </audio>

</body>
</html>
