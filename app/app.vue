<template>
  <div class="bg-gradient-to-b from-pink-50 via-rose-50/30 to-pink-100/50 text-rose-950 font-sans min-h-screen selection:bg-rose-500 selection:text-white scroll-smooth">
    
    <!-- NAVBAR STICKY -->
    <header class="fixed top-0 left-0 right-0 z-50 bg-white/75 backdrop-blur-md border-b border-pink-200/80 shadow-sm transition-all">
      <div class="max-w-6xl mx-auto px-6 py-4 flex justify-between items-center">
        <a href="#home" class="font-serif font-bold text-2xl tracking-tight text-rose-800 hover:text-rose-600 transition-colors">
          Dhenia<span class="text-pink-500">.</span>
        </a>
        <nav class="hidden md:flex items-center space-x-8 font-medium text-sm text-rose-900">
          <a href="#home" class="hover:text-rose-600 transition-colors py-1">Home</a>
          <a href="#tentang" class="hover:text-rose-600 transition-colors py-1">Tentang Saya</a>
          <a href="#pengalaman" class="hover:text-rose-600 transition-colors py-1">Pengalaman</a>
          <a href="#keahlian" class="hover:text-rose-600 transition-colors py-1">Keahlian</a>
          <a href="#proyek" class="hover:text-rose-600 transition-colors py-1">Proyek</a>
          <a href="#kontak" class="hover:text-rose-600 transition-colors py-1">Kontak</a>
        </nav>
        <a href="#kontak" class="bg-gradient-to-r from-pink-400 via-rose-500 to-rose-600 text-white text-xs font-semibold px-5 py-2.5 rounded-full shadow-md hover:shadow-pink-300/50 hover:scale-105 transition-all duration-300">
          Hubungi Saya ✨
        </a>
      </div>
    </header>

    <!-- HERO SECTION -->
    <section id="home" class="pt-36 pb-24 px-6 max-w-6xl mx-auto flex flex-col md:flex-row items-center justify-between gap-12">
      <div class="md:w-3/5 space-y-6">
        <div class="inline-flex items-center gap-2 bg-pink-100/80 text-rose-800 text-xs font-bold uppercase tracking-wider px-4 py-1.5 rounded-full border border-pink-200 shadow-sm">
          <span>✨ Siswa RPL — SMKN 71 Jakarta</span>
        </div>
        <h1 class="text-4xl md:text-5xl lg:text-6xl font-extrabold text-rose-950 leading-tight">
          Halo, saya <span class="bg-gradient-to-r from-rose-600 via-pink-500 to-rose-700 bg-clip-text text-transparent font-serif italic">Dhenia!</span> 👋
        </h1>
        <p class="text-lg font-semibold text-rose-700">
          Siswa Rekayasa Perangkat Lunak (RPL) & Frontend Developer
        </p>
        <p class="text-rose-900/75 max-w-xl leading-relaxed text-sm md:text-base">
          Saya berfokus dalam pengembangan aplikasi web dan desktop interaktif menggunakan <span class="font-semibold text-rose-800">Nuxt 3, Vue.js, Laravel, PHP, dan Java</span>. Saya terbiasa membangun sistem yang fungsional, terstruktur, serta memiliki antarmuka yang menarik.
        </p>
        <div class="flex flex-wrap gap-4 pt-2">
          <a href="#proyek" class="bg-gradient-to-r from-rose-500 to-pink-600 text-white font-semibold text-sm px-7 py-3.5 rounded-2xl shadow-lg shadow-pink-200 hover:shadow-xl hover:-translate-y-0.5 transition-all flex items-center gap-2">
            <i class="fa-solid fa-briefcase"></i> Lihat Proyek Saya
          </a>
          <a href="#kontak" class="bg-white/80 border-2 border-pink-200 text-rose-800 font-semibold text-sm px-7 py-3.5 rounded-2xl hover:bg-pink-100/60 transition-all shadow-sm">
            Kontak Saya
          </a>
        </div>
      </div>

      <!-- FOTO PROFIL PERMANEN -->
<div class="md:w-2/5 flex justify-center w-full">
  <div class="relative bg-white/90 p-7 rounded-3xl shadow-xl shadow-pink-200/50 border border-pink-200 text-center w-80 backdrop-blur-sm hover:shadow-2xl transition-all">
    
    <!-- FRAME FOTO PROFIL -->
    <div class="relative w-44 h-44 mx-auto mb-4 rounded-2xl overflow-hidden border-4 border-pink-200 shadow-md bg-pink-100 flex items-center justify-center">
      <img 
        src="/dh.jpeg" 
        alt="Foto Profil Dhenia" 
        class="w-full h-full object-cover"
        onerror="this.onerror=null; this.src='/dh.jpg'; this.onerror=function(){ this.style.display='none'; this.nextElementSibling.style.display='flex'; };"
      />
      <!-- Fallback Avatar Jika Gambar Belum Ada di Folder Public -->
      <div class="hidden w-full h-full bg-gradient-to-tr from-pink-400 to-rose-500 items-center justify-center text-white font-bold text-5xl font-serif">
        D
      </div>
    </div>

    <h3 class="font-bold text-xl text-rose-950">Dhenia</h3>
    <p class="text-xs font-semibold text-pink-600 mt-0.5">Software Engineering Student</p>
    <p class="text-xs text-rose-700/70 italic mt-2">"Belajar, Berkarya, Berkembang"</p>
  </div>
</div>
    </section>

    <!-- TENTANG SAYA -->
    <section id="tentang" class="py-20 px-6 max-w-6xl mx-auto">
      <div class="bg-white/80 backdrop-blur-md rounded-3xl p-8 md:p-12 border border-pink-200 shadow-xl shadow-pink-100">
        <div class="text-center max-w-2xl mx-auto space-y-2 mb-10">
          <span class="text-xs font-extrabold text-pink-600 uppercase tracking-widest">BIODATA LENGKAP</span>
          <h2 class="text-3xl font-bold text-rose-950">Tentang Saya</h2>
        </div>
        <div class="grid md:grid-cols-2 gap-8 text-rose-900/80 text-sm md:text-base leading-relaxed">
          <div class="space-y-4">
            <p>
              Saya adalah siswi jurusan <strong>Rekayasa Perangkat Lunak (RPL)</strong> di <strong>SMKN 71 Jakarta</strong> kelas MKK-XI RPL 2. Saya memiliki minat dalam pengembangan web, mulai dari merancang antarmuka yang menarik hingga mengelola alur program di bagian <em>backend</em> .
            </p>
            <p>
              Selain menulis kode, saya juga terbiasa membuat desain <em>mockup</em> antarmuka di Figma, menyusun struktur diagram sistem di draw.io, serta mengelola basis data menggunakan MySQL dan HeidiSQL.
            </p>
          </div>
          
          <!-- KOTAK INFORMASI SEBELAH KANAN -->
          <div class="space-y-3 bg-pink-50/60 p-6 rounded-2xl border border-pink-200/80">
            
            <!-- Sekolah / Kelas -->
            <div class="flex items-center gap-3.5">
              <div class="w-10 h-10 rounded-xl bg-white border border-pink-200 p-1 flex items-center justify-center shadow-sm shrink-0 overflow-hidden">
                <img src="/logo-smk.png" alt="SMKN 71" class="w-full h-full object-contain" onerror="this.onerror=null; this.parentElement.innerHTML='<span class=\'text-rose-700 font-bold text-base\'>🏫</span>';">
              </div>
              <div>
                <p class="text-xs text-rose-600 font-bold">Sekolah / Kelas</p>
                <p class="text-sm font-semibold text-rose-950">SMKN 71 Jakarta (MKK-XI RPL 2)</p>
              </div>
            </div>

            <!-- Fokus Keahlian -->
            <div class="flex items-center gap-3.5">
              <div class="w-10 h-10 rounded-xl bg-pink-200/80 flex items-center justify-center text-rose-700 text-base shadow-sm shrink-0">
                💻
              </div>
              <div>
                <p class="text-xs text-rose-600 font-bold">Fokus Keahlian</p>
                <p class="text-sm font-semibold text-rose-950">Nuxt 3, Vue.js, Laravel & Java</p>
              </div>
            </div>

            <!-- Environment -->
            <div class="flex items-center gap-3.5">
              <div class="w-10 h-10 rounded-xl bg-pink-200/80 flex items-center justify-center text-rose-700 text-base shadow-sm shrink-0">
                🛠️
              </div>
              <div>
                <p class="text-xs text-rose-600 font-bold">Environment</p>
                <p class="text-sm font-semibold text-rose-950">Laragon, NetBeans, VS Code</p>
              </div>
            </div>

          </div>
        </div>
      </div>
    </section>

    <!-- PENGALAMAN & REKAM JEJAK -->
    <section id="pengalaman" class="py-20 px-6 max-w-6xl mx-auto">
      <div class="text-center max-w-2xl mx-auto space-y-2 mb-12">
        <span class="text-xs font-extrabold text-pink-600 uppercase tracking-widest">Rekam Jejak Akademik & Proyek</span>
        <h2 class="text-3xl font-bold text-rose-950">Pengalaman Saya</h2>
      </div>
      <div class="space-y-6 max-w-4xl mx-auto">
        
        <div class="bg-white p-6 md:p-8 rounded-3xl border border-pink-200 shadow-md flex flex-col md:flex-row gap-6 items-start">
          <div class="w-12 h-12 rounded-2xl bg-pink-100 flex items-center justify-center text-rose-600 font-bold shrink-0 text-xl">🛒</div>
          <div class="space-y-2">
            <span class="text-[10px] font-bold text-rose-600 bg-pink-100 px-3 py-1 rounded-full">Proyek Aplikasi Kasir Web</span>
            <h3 class="font-bold text-lg text-rose-950">Pengembangan POS Web "DENA Beauty Corner"</h3>
            <p class="text-xs text-rose-800/80 leading-relaxed">
              Membangun aplikasi kasir toko kecantikan berbasis API Laravel dan frontend Nuxt 3. Mengimplementasikan fitur riwayat transaksi, cetak struk belajar thermal, dan manajemen data produk.
            </p>
          </div>
        </div>

        <div class="bg-white p-6 md:p-8 rounded-3xl border border-pink-200 shadow-md flex flex-col md:flex-row gap-6 items-start">
          <div class="w-12 h-12 rounded-2xl bg-pink-100 flex items-center justify-center text-rose-600 font-bold shrink-0 text-xl">✨</div>
          <div class="space-y-2">
            <span class="text-[10px] font-bold text-rose-600 bg-pink-100 px-3 py-1 rounded-full">Desain & Slicing Landing Page</span>
            <h3 class="font-bold text-lg text-rose-950">Slicing Website "Lunéa SKIN" dari Figma ke PHP</h3>
            <p class="text-xs text-rose-800/80 leading-relaxed">
              Merancang wireframe & UI landing page kecantikan Lunéa SKIN di Figma, lalu melakukan <em>slicing</em> kodingan ke HTML, CSS, dan PHP menggunakan Laragon dan VS Code.
            </p>
          </div>
        </div>

        <div class="bg-white p-6 md:p-8 rounded-3xl border border-pink-200 shadow-md flex flex-col md:flex-row gap-6 items-start">
          <div class="w-12 h-12 rounded-2xl bg-pink-100 flex items-center justify-center text-rose-600 font-bold shrink-0 text-xl">📊</div>
          <div class="space-y-2">
            <span class="text-[10px] font-bold text-rose-600 bg-pink-100 px-3 py-1 rounded-full">Perancangan Arsitektur Sistem</span>
            <h3 class="font-bold text-lg text-rose-950">Penyusunan Diagram UML & Basis Data Sekolah</h3>
            <p class="text-xs text-rose-800/80 leading-relaxed">
              Membuat hirarki sistem, Entity Relationship Diagram (ERD), Data Flow Diagram (DFD Multi-level), Use Case Diagram, dan Activity Diagram untuk Sistem Parkir, eCar Rent, serta Registrasi Siswa SMKN 71 menggunakan draw.io & PlantUML.
            </p>
          </div>
        </div>

      </div>
    </section>

    <!-- KEAHLIAN / TECH STACK -->
    <section id="keahlian" class="py-20 px-6 max-w-6xl mx-auto">
      <div class="text-center max-w-2xl mx-auto space-y-2 mb-12">
        <span class="text-xs font-extrabold text-pink-600 uppercase tracking-widest">Tech Stack & Tools</span>
        <h2 class="text-3xl font-bold text-rose-950">Keahlian Dhenia</h2>
      </div>
      <div class="grid grid-cols-2 md:grid-cols-4 gap-6">
        <div class="bg-white p-6 rounded-2xl border border-pink-200 text-center shadow-md hover:shadow-xl hover:-translate-y-1 transition-all">
          <div class="text-3xl mb-2">🟢</div>
          <h4 class="font-bold text-rose-950 text-base">Nuxt 3 & Vue.js</h4>
          <p class="text-xs text-rose-600/80 mt-1">Frontend Development</p>
        </div>
        <div class="bg-white p-6 rounded-2xl border border-pink-200 text-center shadow-md hover:shadow-xl hover:-translate-y-1 transition-all">
          <div class="text-3xl mb-2">🔴</div>
          <h4 class="font-bold text-rose-950 text-base">Laravel & PHP</h4>
          <p class="text-xs text-rose-600/80 mt-1">Backend REST API & Web</p>
        </div>
        <div class="bg-white p-6 rounded-2xl border border-pink-200 text-center shadow-md hover:shadow-xl hover:-translate-y-1 transition-all">
          <div class="text-3xl mb-2">☕</div>
          <h4 class="font-bold text-rose-950 text-base">Java Swing</h4>
          <p class="text-xs text-rose-600/80 mt-1">NetBeans Desktop App</p>
        </div>
        <div class="bg-white p-6 rounded-2xl border border-pink-200 text-center shadow-md hover:shadow-xl hover:-translate-y-1 transition-all">
          <div class="text-3xl mb-2">🎨</div>
          <h4 class="font-bold text-rose-950 text-base">Figma & UI/UX</h4>
          <p class="text-xs text-rose-600/80 mt-1">Mockup & Wireframe</p>
        </div>
        <div class="bg-white p-6 rounded-2xl border border-pink-200 text-center shadow-md hover:shadow-xl hover:-translate-y-1 transition-all">
          <div class="text-3xl mb-2">🗄️</div>
          <h4 class="font-bold text-rose-950 text-base">MySQL & HeidiSQL</h4>
          <p class="text-xs text-rose-600/80 mt-1">Database Management</p>
        </div>
        <div class="bg-white p-6 rounded-2xl border border-pink-200 text-center shadow-md hover:shadow-xl hover:-translate-y-1 transition-all">
          <div class="text-3xl mb-2">🌐</div>
          <h4 class="font-bold text-rose-950 text-base">Laragon & Server</h4>
          <p class="text-xs text-rose-600/80 mt-1">Local Development</p>
        </div>
        <div class="bg-white p-6 rounded-2xl border border-pink-200 text-center shadow-md hover:shadow-xl hover:-translate-y-1 transition-all">
          <div class="text-3xl mb-2">📐</div>
          <h4 class="font-bold text-rose-950 text-base">draw.io & PlantUML</h4>
          <p class="text-xs text-rose-600/80 mt-1">Diagram ERD / DFD / UML</p>
        </div>
        <div class="bg-white p-6 rounded-2xl border border-pink-200 text-center shadow-md hover:shadow-xl hover:-translate-y-1 transition-all">
          <div class="text-3xl mb-2">💨</div>
          <h4 class="font-bold text-rose-950 text-base">Tailwind CSS</h4>
          <p class="text-xs text-rose-600/80 mt-1">Aesthetic Styling</p>
        </div>
      </div>
    </section>

    <!-- PROYEK SAYA -->
    <section id="proyek" class="py-20 px-6 max-w-6xl mx-auto">
      <div class="text-center max-w-2xl mx-auto space-y-2 mb-12">
        <span class="text-xs font-extrabold text-pink-600 uppercase tracking-widest">Karya Pilihan</span>
        <h2 class="text-3xl font-bold text-rose-950">Proyek Portofolio</h2>
        <p class="text-xs md:text-sm text-rose-700/80">Klik tombol detail untuk melihat spesifikasi lengkap proyek.</p>
      </div>

      <div class="grid md:grid-cols-3 gap-8">
        <!-- PROYEK 1 -->
        <div class="bg-white rounded-3xl overflow-hidden border border-pink-200 shadow-md hover:shadow-xl transition-all duration-300 flex flex-col justify-between group">
          <div>
            <div class="relative h-52 bg-pink-100 overflow-hidden">
              <img src="/beuty.png" alt="Proyek DENA Beauty Corner POS" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500">
            </div>
            <div class="p-6 space-y-2">
              <span class="text-[10px] font-bold text-rose-600 bg-pink-100 px-3 py-1 rounded-full uppercase tracking-wider">Web Application</span>
              <h3 class="font-bold text-lg text-rose-950">DENA Beauty Corner POS</h3>
              <p class="text-xs text-rose-800/70 leading-relaxed">Aplikasi kasir toko kecantikan berbasis Laravel REST API & Nuxt 3 frontend dengan pencetakan struk thermal[cite: 1].</p>
            </div>
          </div>
          <div class="p-6 pt-0">
            <button @click="openModal('DENA Beauty Corner POS', 'Laravel API, Nuxt 3, Tailwind CSS, MySQL', 'Proyek kasir Point of Sale ini dilengkapi fitur manajemen stok, pencatatan transaksi, cetak struk belanja thermal, serta state management lokal[cite: 1].')" class="w-full bg-gradient-to-r from-rose-500 to-pink-600 text-white text-xs font-semibold py-3 rounded-xl shadow-md hover:shadow-lg transition-all">
              Detail Proyek →
            </button>
          </div>
        </div>

        <!-- PROYEK 2 -->
        <div class="bg-white rounded-3xl overflow-hidden border border-pink-200 shadow-md hover:shadow-xl transition-all duration-300 flex flex-col justify-between group">
          <div>
            <div class="relative h-52 bg-pink-100 overflow-hidden">
              <img src="/lunea-skin.png" alt="Landing page Lunéa SKIN" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500">
            </div>
            <div class="p-6 space-y-2">
              <span class="text-[10px] font-bold text-rose-600 bg-pink-100 px-3 py-1 rounded-full uppercase tracking-wider">UI/UX & Web Slicing</span>
              <h3 class="font-bold text-lg text-rose-950">Lunéa SKIN Landing Page</h3>
              <p class="text-xs text-rose-800/70 leading-relaxed">Konversi desain mockup Figma menjadi landing page produk kecantikan responsif dengan PHP & Laragon[cite: 1].</p>
            </div>
          </div>
          <div class="p-6 pt-0">
            <button @click="openModal('Lunéa SKIN Landing Page', 'Figma, PHP, HTML5, CSS3, Laragon', 'Merancang tata letak dan wireframe di Figma lalu mengimplementasikannya ke kodingan web interaktif berbasis PHP di lingkungan lokal Laragon[cite: 1].')" class="w-full bg-gradient-to-r from-rose-500 to-pink-600 text-white text-xs font-semibold py-3 rounded-xl shadow-md hover:shadow-lg transition-all">
              Detail Proyek →
            </button>
          </div>
        </div>

        <!-- PROYEK 3 -->
        <div class="bg-white rounded-3xl overflow-hidden border border-pink-200 shadow-md hover:shadow-xl transition-all duration-300 flex flex-col justify-between group">
          <div>
            <div class="relative h-52 bg-pink-100 overflow-hidden">
              <img src="/biodata.png" alt="Sistem Informasi Biodata Siswa" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500">
            </div>
            <div class="p-6 space-y-2">
              <span class="text-[10px] font-bold text-rose-600 bg-pink-100 px-3 py-1 rounded-full uppercase tracking-wider">Web Application</span>
              <h3 class="font-bold text-lg text-rose-950">Sistem Informasi Biodata Siswa (PHP & MySQL)</h3>
              <p class="text-xs text-rose-800/70 leading-relaxed">Aplikasi pengelolaan data biodata siswa interaktif menggunakan PHP dan MySQL. Dilengkapi fitur tambah data, tampilkan tabel siswa, edit biodata, serta hapus data secara dinamis.</p>
            </div>
          </div>
          <div class="p-6 pt-0">
            <button @click="openModal('Java Student CRUD System', 'Java Swing, NetBeans IDE, MySQL JDBC', 'Aplikasi desktop untuk verifikasi input biodata siswa, penambahan, edit, dan hapus data terhubung langsung ke database MySQL[cite: 1].')" class="w-full bg-gradient-to-r from-rose-500 to-pink-600 text-white text-xs font-semibold py-3 rounded-xl shadow-md hover:shadow-lg transition-all">
              Detail Proyek →
            </button>
          </div>
        </div>
      </div>
    </section>

    <!-- KONTAK & MEDSOS -->
    <section id="kontak" class="py-20 px-6 max-w-4xl mx-auto text-center">
      <div class="bg-white/90 backdrop-blur-md rounded-3xl p-8 md:p-12 border border-pink-200 shadow-xl shadow-pink-100">
        <span class="text-xs font-extrabold text-pink-600 uppercase tracking-widest">Mari Terhubung</span>
        <h2 class="text-3xl font-bold text-rose-950 mt-1 mb-2">Kontak & Media Sosial</h2>
        <p class="text-xs md:text-sm text-rose-700/70 mb-8 max-w-md mx-auto">Temukan Dhenia di media sosial.</p>

        <div class="grid grid-cols-1 sm:grid-cols-2 gap-4 max-w-2xl mx-auto text-left">
          <a href="https://www.instagram.com/username_kamu" target="_blank" rel="noopener noreferrer" class="flex items-center gap-4 rounded-2xl border border-pink-200 bg-pink-50/60 p-5 text-rose-900 transition-colors hover:bg-pink-100">
            <span class="flex h-12 w-12 shrink-0 items-center justify-center rounded-xl bg-white text-rose-600 shadow-sm" aria-hidden="true">
              <svg viewBox="0 0 24 24" class="h-7 w-7" fill="none" stroke="currentColor" stroke-width="1.8"><rect x="3" y="3" width="18" height="18" rx="5"/><circle cx="12" cy="12" r="4"/><circle cx="17.5" cy="6.5" r=".8" fill="currentColor" stroke="none"/></svg>
            </span>
            <span><span class="block text-xs font-semibold text-rose-600">Instagram</span><span class="block font-bold">natalia_dhenia</span></span>
          </a>
          <a href="https://www.tiktok.com/@username_kamu" target="_blank" rel="noopener noreferrer" class="flex items-center gap-4 rounded-2xl border border-pink-200 bg-pink-50/60 p-5 text-rose-900 transition-colors hover:bg-pink-100">
            <span class="flex h-12 w-12 shrink-0 items-center justify-center rounded-xl bg-white text-rose-600 shadow-sm" aria-hidden="true">
              <svg viewBox="0 0 24 24" class="h-7 w-7" fill="currentColor"><path d="M19.6 7.1a5.7 5.7 0 0 1-3.5-1.2v8.3a5.6 5.6 0 1 1-4.8-5.5v3a2.7 2.7 0 1 0 1.8 2.5V2.5h3a5.7 5.7 0 0 0 3.5 3.2v1.4Z"/></svg>
            </span>
            <span><span class="block text-xs font-semibold text-rose-600">TikTok</span><span class="block font-bold">nataliaadheniaaa</span></span>
          </a>
          <a href="https://github.com/dhenia" target="_blank" rel="noopener noreferrer" class="flex items-center gap-4 rounded-2xl border border-pink-200 bg-pink-50/60 p-5 text-rose-900 transition-colors hover:bg-pink-100">
            <span class="flex h-12 w-12 shrink-0 items-center justify-center rounded-xl bg-white text-rose-600 shadow-sm" aria-hidden="true">
              <svg viewBox="0 0 24 24" class="h-7 w-7" fill="currentColor"><path d="M12 .9a11.1 11.1 0 0 0-3.5 21.6c.6.1.8-.3.8-.6v-2.1c-3.1.7-3.8-1.3-3.8-1.3-.5-1.3-1.2-1.6-1.2-1.6-1-.7.1-.7.1-.7 1.1.1 1.7 1.1 1.7 1.1 1 .1.8 2.2 3.9 1.6.1-.8.4-1.3.7-1.6-2.5-.3-5.1-1.3-5.1-5.5 0-1.2.4-2.1 1.1-2.9-.1-.3-.5-1.4.1-2.9 0 0 .9-.3 3 1.1a10.4 10.4 0 0 1 5.5 0c2.1-1.4 3-1.1 3-1.1.6 1.5.2 2.6.1 2.9.7.8 1.1 1.7 1.1 2.9 0 4.2-2.6 5.2-5.1 5.5.4.3.8 1 .8 2v3c0 .3.2.7.8.6A11.1 11.1 0 0 0 12 .9Z"/></svg>
            </span>
            <span><span class="block text-xs font-semibold text-rose-600">GitHub</span><span class="block font-bold">github.com/dhenia</span></span>
          </a>
          <div class="flex items-center gap-4 rounded-2xl border border-pink-200 bg-pink-50/60 p-5 text-rose-900">
            <span class="flex h-12 w-12 shrink-0 items-center justify-center rounded-xl bg-white text-rose-600 shadow-sm" aria-hidden="true">
              <svg viewBox="0 0 24 24" class="h-7 w-7" fill="currentColor"><path d="M12 2a9.8 9.8 0 0 0-8.4 14.8L2.3 22l5.4-1.4A9.8 9.8 0 1 0 12 2Zm0 17.8a8 8 0 0 1-4.1-1.1l-.3-.2-3.2.8.9-3.1-.2-.3A8 8 0 1 1 12 19.8Zm4.4-6c-.2-.1-1.5-.8-1.8-.9s-.4-.1-.6.1-.7.9-.9 1-.3.2-.6.1a7.4 7.4 0 0 1-2.2-1.4 8 8 0 0 1-1.5-1.9c-.2-.3 0-.4.1-.6l.4-.5.3-.5c.1-.2 0-.4 0-.5s-.6-1.5-.9-2c-.2-.5-.5-.4-.6-.4h-.5c-.2 0-.5.1-.8.4s-1 1-1 2.3 1 2.7 1.1 2.9 2 3 4.9 4.2c.7.3 1.3.4 1.7.5.7.2 1.4.2 1.9.1.6-.1 1.5-.6 1.7-1.2s.2-1.1.2-1.2-.2-.2-.4-.3Z"/></svg>
            </span>
            <span><span class="block text-xs font-semibold text-rose-600">WhatsApp</span><span class="block font-bold">+62 812-xxxx-xxxx</span></span>
          </div>
        </div>
      </div>
    </section>

    <!-- MODAL DETAIL PROYEK -->
    <div v-if="isModalOpen" class="fixed inset-0 z-50 bg-rose-950/40 backdrop-blur-sm flex items-center justify-center p-4">
      <div class="bg-white rounded-3xl max-w-md w-full p-6 border border-pink-200 shadow-2xl relative">
        <button @click="isModalOpen = false" class="absolute top-4 right-4 text-rose-600 font-bold text-lg hover:text-rose-800">✕</button>
        <h3 class="font-bold text-xl text-rose-950 mb-1">{{ modalData.title }}</h3>
        <p class="text-xs text-rose-600 font-semibold mb-4">Tech Stack: {{ modalData.tech }}</p>
        <p class="text-xs text-rose-800/80 leading-relaxed mb-6">{{ modalData.desc }}</p>
        <button @click="isModalOpen = false" class="w-full bg-pink-100 text-rose-700 font-bold text-xs py-2.5 rounded-xl hover:bg-pink-200 transition-colors">Tutup</button>
      </div>
    </div>

    <!-- FOOTER -->
    <footer class="py-8 text-center text-xs text-rose-900/60 border-t border-pink-200/80">
      <p>© 2026 Dhenia (MKK-XI RPL 2 SMKN 71 Jakarta). Dibuat menggunakan Nuxt 3 & Tailwind CSS.</p>
    </footer>

  </div>
</template>

<script setup>
import { ref } from 'vue'

const isModalOpen = ref(false)
const modalData = ref({ title: '', tech: '', desc: '' })

const openModal = (title, tech, desc) => {
  modalData.value = { title, tech, desc }
  isModalOpen.value = true
}
</script>