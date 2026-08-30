<div align="center">
  <div style="display: flex; justify-content: center; align-items: center; gap: 30px;">
    <img src="logo-bumn.png" alt="Logo BUMN" height="70">
    <img src="logo-pln.png" alt="Logo PLN" height="70">
    <img src="logo-banda-aceh.png" alt="Logo Banda Aceh" height="70">
  </div>
  
  <br />
  
  <img src="logo.png" alt="Desa Berdaya PLN Aceh Logo" height="150">

  <h1>Desa Berdaya PLN Aceh</h1>
  
  <p>
    <strong>Sistem Informasi & Manajemen Program Desa Berdaya PLN di Wilayah Aceh</strong>
  </p>

  <p>
    <a href="#-tentang-proyek">Tentang</a> •
    <a href="#-fitur-utama">Fitur</a> •
    <a href="#-tech-stack">Tech Stack</a> •
    <a href="#-instalasi">Instalasi</a> •
    <a href="#-kontributor">Kontributor</a>
  </p>
</div>

---

## 📖 Tentang Proyek
**Desa Berdaya PLN Aceh** adalah sebuah platform digital yang dikembangkan untuk mendukung, memonitor, dan mengelola program *Corporate Social Responsibility (CSR)* dari PT PLN (Persero) di wilayah Aceh. Aplikasi ini bertujuan untuk memberdayakan masyarakat desa melalui digitalisasi administrasi desa, pemantauan program ekonomi lokal, serta transparansi bantuan.

Proyek ini dibangun sebagai bentuk sinergi dan kontribusi nyata dalam memajukan desa-desa di Aceh, sejalan dengan visi BUMN, PLN, dan Pemerintah Kota Banda Aceh.

## ✨ Fitur Utama
- **Manajemen Profil Desa:** Pencatatan dan pembaruan data potensi ekonomi, infrastruktur, dan demografi desa.
- **Monitoring Program CSR:** Pelacakan progres bantuan dan program pemberdayaan PLN secara *real-time*.
- **Sistem Pelaporan Berbasis Digital:** Pembuatan laporan kegiatan dan penggunaan dana secara otomatis dan transparan.
- **Dashboard Analitik Interaktif:** Visualisasi data statistik perkembangan desa dan keberhasilan program dengan grafik informatif.
- **Akses Multi-Role (RBAC):** Sistem *login* yang terintegrasi untuk Admin PLN, Perangkat Desa, dan Masyarakat Umum.

## 💻 Tech Stack
*(Catatan: Anda dapat menyesuaikan stack di bawah ini sesuai dengan teknologi aktual yang Anda gunakan di repositori)*

**Frontend:**
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB) ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)

**Backend:**
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white)

**Tools & Environment:**
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white) ![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white) ![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=Postman&logoColor=white)

## 🚀 Instalasi

Ikuti langkah-langkah di bawah ini untuk menjalankan proyek secara lokal:

1. **Clone repository ini:**
   ```bash
   git clone https://github.com/dappahsn/Desa-Berdaya-PLN-ACEH.git
   ```

2. **Pindah ke direktori proyek:**
   ```bash
   cd Desa-Berdaya-PLN-ACEH
   ```

3. **Install Dependensi:**
   ```bash
   npm install
   # Jika menggunakan framework PHP/Laravel:
   composer install
   ```

4. **Konfigurasi Environment:**
   - Duplikasi file `.env.example` menjadi `.env`
   - Sesuaikan konfigurasi kredensial database Anda di dalam file `.env`

5. **Setup Database:**
   ```bash
   php artisan migrate --seed
   ```

6. **Jalankan Server Lokal:**
   ```bash
   npm run dev
   # dan
   php artisan serve
   ```

## 📂 Struktur Logo & Aset
Proyek ini mengintegrasikan logo resmi institusi terkait. Pastikan file logo berikut tersedia di dalam *root directory* atau folder aset Anda (sesuaikan *path* gambar di bagian atas README ini jika logo disimpan dalam folder seperti `public/assets/images/`):
- `logo-bumn.png` - Kementerian BUMN
- `logo-pln.png` - PT PLN (Persero)
- `logo-banda-aceh.png` - Pemerintah Kota Banda Aceh
- `logo.png` - Logo Utama Aplikasi

## 👨‍💻 Kontributor
- **Muhammad Daffa Husen** - Teknik Komputer, Universitas Syiah Kuala
- GitHub: [@dappahsn](https://github.com/dappahsn)

## 📄 Lisensi
Proyek ini didistribusikan di bawah lisensi **MIT License**. Lihat file `LICENSE` untuk informasi lebih lanjut.

---
<p align="center">
  Dibuat dengan ❤️ di Banda Aceh, Aceh, Indonesia.
</p>
