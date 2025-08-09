<!doctype html>
<html lang="id">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Soeharto — Profil Singkat</title>
  <style>
    :root{--bg:#0f1724;--card:#0b1220;--muted:#9aa4b2;--accent:#f59e0b;--glass:rgba(255,255,255,0.04)}
    *{box-sizing:border-box}
    body{margin:0;font-family:Inter,system-ui,Segoe UI,Arial;background:linear-gradient(180deg,var(--bg),#071022);color:#e6eef6;line-height:1.5}
    .container{max-width:980px;margin:36px auto;padding:20px}
    header{display:flex;gap:18px;align-items:center}
    .avatar{width:120px;height:120px;border-radius:12px;background:linear-gradient(135deg,#1f2937,#111827);display:flex;align-items:center;justify-content:center;color:var(--muted);font-weight:700}
    h1{margin:0;font-size:28px}
    p.lead{color:var(--muted);margin-top:6px}
    .grid{display:grid;grid-template-columns:1fr 320px;gap:20px;margin-top:22px}

    .card{background:var(--card);padding:18px;border-radius:12px;box-shadow:0 6px 18px rgba(2,6,23,0.6);border:1px solid rgba(255,255,255,0.02)}
    .facts li{margin:8px 0;color:var(--muted)}
    .timeline{list-style:none;padding:0;margin:0}
    .timeline li{padding:12px 0;border-bottom:1px dashed rgba(255,255,255,0.03)}
    .tag{display:inline-block;padding:6px 10px;border-radius:999px;background:var(--glass);color:var(--muted);font-size:13px}
    a{color:var(--accent);text-decoration:none}
    footer{margin-top:28px;color:var(--muted);font-size:14px;text-align:center}

    /* responsive */
    @media (max-width:880px){.grid{grid-template-columns:1fr}.avatar{width:96px;height:96px}}
    .btn{display:inline-block;padding:8px 12px;border-radius:10px;background:linear-gradient(180deg,#f7c948,#f59e0b);color:#061023;font-weight:600;text-decoration:none}

    /* small interactive timeline controls */
    .controls{display:flex;gap:8px;margin-bottom:10px}
    .muted{color:var(--muted)}
  </style>
</head>
<body>
  <div class="container">
    <header>
      <div class="avatar">S H</div>
      <div>
        <h1>Soeharto (1921–2008)</h1>
        <p class="lead">Presiden kedua Republik Indonesia, memimpin negara selama lebih dari tiga dekade (1967–1998). Kepemimpinannya menandai era pembangunan ekonomi sekaligus kontroversi politik dan HAM.</p>
        <div style="margin-top:10px"><span class="tag">Kelahiran: 8 Juni 1921</span> <span style="margin-left:8px" class="tag">Wafat: 27 Januari 2008</span></div>
      </div>
    </header>

    <div class="grid">
      <main>
        <section class="card" id="overview">
          <h2 style="margin-top:0">Ringkasan</h2>
          <p class="muted">Soeharto adalah tokoh militer yang naik ke puncak kekuasaan pada akhir 1960-an setelah pergolakan politik besar pada pertengahan 1960-an. Masa pemerintahannya (dikenal sebagai Orde Baru) fokus pada stabilitas politik, pembangunan ekonomi, sentralisasi kekuasaan, dan kebijakan pro-pembangunan yang mengundang investasi asing. Namun, rezimnya juga dikritik karena korupsi, nepotisme, pembatasan kebebasan politik, dan pelanggaran hak asasi manusia.</p>
        </section>

        <section class="card" id="timeline-section" style="margin-top:16px">
          <div style="display:flex;justify-content:space-between;align-items:center">
            <h2 style="margin:0">Linimasa Singkat</h2>
            <div class="controls">
              <button class="btn" onclick="filterEra('semua')">Semua</button>
              <button class="btn" onclick="filterEra('sebelum')">Sebelum 1967</button>
              <button class="btn" onclick="filterEra('orde-baru')">Orde Baru</button>
            </div>
          </div>
          <ul class="timeline" id="timelineList">
            <li data-era="sebelum"><strong>1921</strong> — Lahir di Kemusuk, Yogyakarta.</li>
            <li data-era="sebelum"><strong>1940-an</strong> — Karier militer awal; terlibat dalam perjuangan kemerdekaan dan dinas militer kala kemerdekaan.</li>
            <li data-era="sebelum"><strong>1965–1966</strong> — Peristiwa Gerakan 30 September 1965, periode pergolakan politik dan naiknya kekuasaan militer.</li>
            <li data-era="orde-baru"><strong>1967</strong> — Secara resmi menjadi Pejabat Presiden, kemudian Presiden pada 1968; memulai era Orde Baru.</li>
            <li data-era="orde-baru"><strong>1970-an–1990-an</strong> — Pembangunan infrastruktur, stabilisasi ekonomi, tetapi juga sentralisasi kekuasaan, pembatasan kebebasan politik, dan munculnya praktik korupsi terstruktur.</li>
            <li data-era="orde-baru"><strong>1997–1998</strong> — Krisis moneter Asia berdampak besar; gelombang protes mahasiswa dan rakyat; akhirnya Soeharto mengundurkan diri pada 21 Mei 1998.</li>
            <li data-era="orde-baru"><strong>2008</strong> — Wafat di Jakarta pada 27 Januari.</li>
          </ul>
        </section>

        <section class="card" id="controversies" style="margin-top:16px">
          <h2 style="margin-top:0">Kontroversi utama</h2>
          <ul class="muted">
            <li>Isu pelanggaran HAM dalam operasi militer di berbagai daerah (mis. Timor Timur dan operasi dalam negeri lain).</li>
            <li>Praktik korupsi dan nepotisme — keluarga dan kroni yang mendapatkan kontrak dan posisi strategis.</li>
            <li>Pembatasan kebebasan pers, politik, dan tokoh oposisi selama masa Orde Baru.</li>
            <li>Sentralisasi kekuasaan yang mengurangi peran lembaga-demokrasi dan memperkuat pemerintahan eksekutif.</li>
          </ul>
        </section>

        <section class="card" id="legacy" style="margin-top:16px">
          <h2 style="margin-top:0">Warisan & Pandangan Sejarah</h2>
          <p class="muted">Penilaian terhadap Soeharto masih kompleks dan berlapis: sebagian melihat era Orde Baru sebagai periode pembangunan ekonomi dan stabilitas setelah kekacauan 1960-an; pihak lain menekankan biaya sosial, politik, dan etika dari stabilitas tersebut — khususnya pelanggaran HAM dan korupsi sistemik. Debat publik dan akademik terus berlangsung mengenai bagaimana mengukur pencapaian ekonomi versus dampak terhadap demokrasi dan hak asasi manusia.</p>
        </section>

        <section class="card" id="further" style="margin-top:16px">
          <h2 style="margin-top:0">Bacaan & Sumber</h2>
          <p class="muted">Untuk bacaan lebih lanjut, kunjungi halaman-halaman ensiklopedi dan karya akademik tentang Orde Baru, sejarah Indonesia pasca-kemerdekaan, dan studi HAM. Contoh (mulai dari sumber umum):</p>
          <ul class="muted">
            <li><a href="https://id.wikipedia.org/wiki/Soeharto" target="_blank">Wikipedia — Soeharto (bahasa Indonesia)</a></li>
            <li><a href="https://en.wikipedia.org/wiki/Suharto" target="_blank">Wikipedia — Suharto (English)</a></li>
          </ul>
        </section>
      </main>

      <aside>
        <div class="card">
          <h3 style="margin-top:0">Fakta Cepat</h3>
          <ul class="facts muted">
            <li>Nama lengkap: Haji Mohammad Soeharto</li>
            <li>Jabatan: Presiden RI (1967–1998)</li>
            <li>Latar belakang: Militer</li>
            <li>Periode populer disebut: Orde Baru</li>
            <li>Pengunduran diri: 21 Mei 1998</li>
          </ul>
          <div style="margin-top:12px"><a class="btn" href="#overview">Pelajari Lebih Lanjut</a></div>
        </div>

        <div class="card" style="margin-top:16px">
          <h3 style="margin-top:0">Catatan</h3>
          <p class="muted">Halaman ini disusun sebagai ringkasan netral untuk tujuan informasi. Jika ingin konten lebih rinci (artikel panjang, galeri gambar, atau sumber akademik terperinci), beritahu saya — saya bisa tambahkan.</p>
        </div>
      </aside>
    </div>

    <footer>
      Dibuat otomatis — ingin versi PDF atau tambahan gambar? Balas "tambah gambar" atau "eksport PDF".
    </footer>
  </div>

  <script>
    function filterEra(era){
      const items = document.querySelectorAll('#timelineList li');
      items.forEach(it => {
        if(era === 'semua') it.style.display = '';
        else it.style.display = (it.dataset.era === era) ? '' : 'none';
      });
    }
  </script>
</body>
</html>


