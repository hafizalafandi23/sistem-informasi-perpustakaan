# 📚 Sistem Informasi Perpustakaan Berbasis Web

Selamat datang di repository proyek **Sistem Informasi Perpustakaan Berbasis Web**. 
Proyek ini dibuat untuk memenuhi tugas Mata Kuliah **Rancangan Perangkat Lunak (RPL)**.

---

## 📖 Deskripsi Proyek

Sistem Informasi Perpustakaan ini adalah aplikasi berbasis web yang dirancang untuk mempermudah pengelolaan data buku, anggota, serta proses peminjaman dan pengembalian buku secara digital. Aplikasi ini memiliki fitur interaktif yang terintegrasi antara halaman Admin dan Anggota, serta dilengkapi dengan sistem perhitungan denda otomatis.

---

## ✨ Fitur Utama

### 🔐 Fitur Admin
- **Login Admin:** Akses khusus petugas perpustakaan.
- **Dashboard Interaktif:** Menampilkan statistik total buku, anggota, dan buku yang sedang dipinjam.
- **Kelola Data Buku:** Tambah, edit, dan hapus data buku (judul, penulis, tahun, stok).
- **Kelola Data Anggota:** Melihat dan menghapus akun anggota terdaftar.
- **Kelola Peminjaman:** Memproses pengembalian buku dan melihat daftar transaksi.
- **Sistem Denda Otomatis:** Menghitung denda (Rp 1.000/hari) jika pengembalian melewati batas waktu.
- **Lihat Laporan:** Melihat rekapitulasi seluruh transaksi perpustakaan.

### 👤 Fitur Anggota
- **Registrasi & Login:** Anggota dapat mendaftar akun secara mandiri.
- **Katalog Buku:** Melihat daftar buku yang tersedia di perpustakaan.
- **Pencarian Buku:** Mencari buku berdasarkan judul atau nama penulis.
- **Pinjam Buku:** Mengajukan peminjaman buku secara digital.
- **Riwayat Peminjaman:** Melihat status buku yang dipinjam beserta sisa waktu pengembalian.
- **Profil Anggota:** Melihat detail informasi akun pribadi.

---

## 🛠️ Teknologi yang Digunakan

- **HTML5** — Struktur halaman web
- **CSS3** — Desain antarmuka (tema modern & responsif)
- **JavaScript (Vanilla)** — Logika interaktif, integrasi data, dan manipulasi DOM
- **LocalStorage** — Penyimpanan data sementara di sisi browser (sebagai simulasi database)
- **GitHub Pages** — Hosting aplikasi web

---

## 📂 Struktur Folder

```text
sistem-informasi-perpustakaan/
│
├── index.html          # Halaman utama (redirect ke login)
├── login.html          # Halaman Login & Daftar Anggota
├── dashboard.html      # Halaman Dashboard Admin
├── buku.html           # Halaman Kelola Buku (Admin)
├── anggota.html        # Halaman Kelola Anggota (Admin)
├── peminjaman.html     # Halaman Data Peminjaman & Denda (Admin)
├── laporan.html        # Halaman Laporan (Admin)
├── katalog.html        # Halaman Katalog, Riwayat & Profil (Anggota)
├── SRS_System_Informasi_Perpustakaan.docx   # Dokumen SRS
├── UseCase_Perpustakaan.docx                # Dokumen Use Case
└── README.md           # Dokumentasi proyek
