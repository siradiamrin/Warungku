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

- **Framework:** Flutter
- **Language:** Dart
- **State Management:** Provider / Riverpod
- **Navigation:** go_router
- **Database:** SQLite (sqflite) — lokal, offline
- **Export:** excel, pdf, printing

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
git clone https://github.com/username/warungku.git
cd warungku
```

2. Install dependencies:

```bash
flutter pub get
```

3. Jalankan aplikasi:

```bash
flutter run
```

4. Build APK (opsional):

```bash
flutter build apk --release
```

> **Minimum:** Flutter SDK 3.0.0 | Dart 3.0.0

---



Dikembangkan untuk keperluan tugas **Rekayasa Kebutuhan D** — Universitas Muhammadiyah Malang.  
**Laode Siradi Amrin** — NIM 202310370311016
