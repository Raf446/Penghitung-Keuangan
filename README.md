# 💸 Pengelola Keuangan (Money Tracker)

Aplikasi web progresif (PWA) pencatat keuangan modern, ringan, dan responsif dengan pengalaman pengguna setara aplikasi native. Terinspirasi dari alur kerja *Money Manager*, aplikasi ini dirancang untuk memudahkan pelacakan pengeluaran, pemasukan, serta transfer antar-dompet secara instan dan aman tanpa pelacak pihak ketiga.

🌐 **Demo Langsung:** [raf446.github.io/Penghitung-Keuangan](https://raf446.github.io/Penghitung-Keuangan/)

---

## ✨ Fitur Unggulan

- **💼 Manajemen Multi-Akun (Multi-Wallet)**
  Kelola saldo terpisah untuk Uang Tunai (Cash), Rekening Bank, Dompet Digital (E-Wallet), maupun Utang/Piutang secara *real-time*.
- **📊 Visualisasi Data & Statistik Interaktif**
  Pantau proporsi alokasi dana menggunakan diagram lingkaran interaktif (*Donut/Pie Chart*) yang dikelompokkan berdasarkan kategori pengeluaran dan pemasukan.
- **📅 Kalender Riwayat Transaksi**
  Tinjau arus kas harian secara visual langsung di kalender bulanan, lengkap dengan indikator pemasukan (hijau) dan pengeluaran (merah).
- **🧮 Smart Keypad / Built-in Calculator**
  Input transaksi lebih cepat dengan numpad terintegrasi yang mendukung perhitungan langsung tanpa perlu membuka aplikasi kalkulator terpisah.
- **⚡ Dukungan PWA & Mode Offline Penuh**
  Dapat dipasang (*Install*) langsung ke layar utama Android/iOS/Desktop. Berjalan lancar tanpa koneksi internet berkat dukungan Service Worker.
- **🔒 Privasi Terjamin (Local Storage)**
  Data keuangan 100% tersimpan secara lokal di peramban pengguna; tidak ada data yang dikirim ke peladen luar.

---

## 🛠️ Tech Stack

| Komponen | Teknologi |
| :--- | :--- |
| **Markup & Struktur** | HTML5 Semantik |
| **Styling** | [Tailwind CSS](https://tailwindcss.com/) (CDN) |
| **Visualisasi Grafik** | [Chart.js](https://www.chartjs.org/) |
| **Logika & State** | Vanilla JavaScript (ES6+) |
| **PWA Engine** | Web App Manifest & Service Worker API |
| **Penyimpanan Data** | Browser `localStorage` |

---

## 📱 Panduan Pemasangan di Perangkat

### Opsi A: Pasang via Browser (PWA Resmi)
1. Buka tautan demo di browser smartphone (Google Chrome / Brave / Safari).
2. Ketuk ikon titik tiga (⋮) atau menu **Share**.
3. Pilih **"Tambahkan ke Layar Utama"** atau **"Instal Aplikasi"**.

### Opsi B: Pemasangan Paket Mandiri (Android APK)
Jika menggunakan paket rilis APK yang telah dikonversi melalui PWABuilder:
1. Pastikan izin instalasi dari sumber tidak dikenal (*Install Unknown Apps*) telah aktif pada File Manager.
2. Pasang berkas `.apk` bertanda tangan digital terbaru.

---

## 🚀 Pengembangan Lokal (Local Development)

Jika ingin menjalankan atau memodifikasi kode di komputer lokal:

1. **Klon Repositori:**
   ```bash
   git clone [https://github.com/Raf446/Penghitung-Keuangan.git](https://github.com/Raf446/Penghitung-Keuangan.git)
   cd Penghitung-Keuangan
