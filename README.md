# Warungku

Aplikasi mobile manajemen toko ritel untuk pemilik UMKM yang dibangun menggunakan Flutter dan SQLite. Mendukung mode offline penuh untuk kemudahan pengelolaan produk, kasir, dan laporan penjualan.

---

## 🔗 Link Akses Aplikasi

| Nama File / Platform | Tautan (Link) |
|---|---|
| **Source Code** | [GitHub Repository](https://github.com/siradiamrin/Warungku) |
| **Download APK** | [Google Drive / GitHub Release](https://drive.google.com/file/d/1f4Asvb-3X_NXN6OF8Tbpf-0Y5q5Ju6_W/view?usp=sharing) |
|  |

---

## 🚀 Tech Stack

- **Framework:** React.js
- **Mobile Wrapper:** Capacitor
- **Language:** javaScript 
- **Database:** SQLite (Capacitor-cpmmunity-sqite)
- **storage:** Capacitor Filesystem

---

## 🧪 Pengujian Kualitas Aplikasi (Daily Project 6)

Pengujian ini dilakukan berdasarkan aspek kualitas perangkat lunak (ISO 25010) untuk memastikan sistem berjalan sesuai spesifikasi teknis.

| Aspek Kualitas | Skenario Pengujian | Hasil yang Diharapkan | Hasil Aktual | Status |
|---|---|---|---|---|
| **Functional Suitability** | Melakukan scan barcode produk di halaman Kasir. | Sistem berhasil menampilkan detail produk (nama, harga, stok) secara otomatis. | Sesuai Harapan | ✅ Pass |
| **Usability** | Navigasi menu utama dan pencarian produk berdasarkan kategori. | Pengguna dapat menemukan produk spesifik dalam kurang dari 3 klik. | Sesuai Harapan | ✅ Pass |
| **Performance Efficiency** | Memuat data Dashboard (pendapatan, transaksi, stok menipis). | Data muncul di dashboard dalam waktu kurang dari 2 detik. | Sesuai Harapan | ✅ Pass |
| **Security** | Mengakses halaman Gudang dan Laporan tanpa sesi login yang valid. | Sistem menolak akses dan mengarahkan kembali ke halaman Login. | Sesuai Harapan | ✅ Pass |
| **Maintainability** | Integrasi data antar modul Kasir dan Gudang setelah transaksi selesai. | Penambahan transaksi di Kasir otomatis memperbarui stok produk di Gudang. | Sesuai Harapan | ✅ Pass |

---

## 🛠️ Cara Menjalankan Secara Lokal

1. Clone repository ini:

```bash
git clone https://github.com/siradiamrin/warungku.git
cd warungku
```

2. Install dependencies:

```bash
npm install
```

3. build projek:

```bash
npm run build
```

4. sinkronisasi ke android:

```bash
npx cap sync
```
5. jalankan aplikasi:
  -jalan di browser: npx start
  -untuk membuka di andorid studio: npx cap open android (ini agar bisa liat bagaimana tampilan apk di hp)
   

---



Dikembangkan untuk keperluan tugas **Rekayasa Kebutuhan D** — Universitas Muhammadiyah Malang.  
**Laode Siradi Amrin** — NIM 202310370311016
