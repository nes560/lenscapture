# LensCapture

Website penyedia jasa fotografi profesional, penjualan kamera, dan sewa smartphone flagship untuk kebutuhan dokumentasi momen (pre-wedding, wedding, wisuda, dan konten kreator).

🔗 **Repository:** https://github.com/nessanovianti/LENSCAPTURE
🔗 **Live Demo (Hosting):** https://lenscapturenow.infinityfreeapp.com

---

## 📖 Tentang Project

LensCapture adalah website statis (HTML, CSS, JavaScript) yang menampilkan informasi layanan, katalog produk, dan formulir kontak. Bagian artikel/blog dikelola secara terpisah menggunakan **Joomla CMS** yang diinstall di subfolder `/artikel1` pada hosting.

Project ini dibuat sebagai tugas mata kuliah semester 4, dikerjakan oleh Kelompok 5.

## ✨ Fitur

- **Home** — ringkasan layanan unggulan LensCapture
- **Katalog Kamera** — daftar kamera yang dijual beserta spesifikasi lengkap
- **Sewa HP Flagship** — layanan sewa smartphone untuk kebutuhan event/konten kreator
- **Jasa Fotografi** — Pre-Wedding, Wedding Session, Wisuda/Graduation
- **Artikel** — preview artikel, terintegrasi dengan Joomla CMS
- **Kontak & Formulir Hubungi** — informasi lokasi dan formulir pemesanan
- **Tentang Kami** — profil anggota tim pengembang
- Navbar responsif dengan dropdown menu "Jasa Foto"
- Notifikasi konfirmasi interaktif pada tombol pemesanan (JavaScript)

## 🛠️ Teknologi yang Digunakan

- HTML5
- CSS3 (Bootstrap 3, dimodifikasi dengan tema gelap kustom)
- JavaScript (vanilla + jQuery untuk navbar & dropdown)
- Joomla CMS (untuk manajemen artikel, di-hosting terpisah pada subfolder)
- Hosting: InfinityFree

## 📁 Struktur Folder

```
LENSCAPTURE/
├── index.html              # Halaman utama
├── home.html                # Halaman utama (versi alternatif)
├── kamera.html                # Katalog kamera
├── sewa-hp.html                # Sewa smartphone
├── fotografi.html                # Layanan pre-wedding
├── wedding.html                    # Layanan wedding session
├── wisuda.html                      # Layanan wisuda/graduation
├── Artikel1.html                      # Preview artikel
├── kontak.html                          # Info kontak & lokasi
├── hubungi.html                          # Formulir hubungi/booking
├── tentang-kami.html                      # Profil tim
├── css/
│   └── bootstrap.css                        # Stylesheet utama
├── js/
│   ├── jquery.js
│   ├── bootstrap.js
│   └── notifikasi.js                           # Validasi & notifikasi interaktif
└── images/                                        # Aset gambar produk & tim
```

## 🚀 Cara Menjalankan di Local

1. Clone repository:
   ```bash
   git clone https://github.com/nessanovianti/LENSCAPTURE.git
   ```
2. Buka `index.html` langsung di browser, atau jalankan lewat local server (disarankan pakai ekstensi Live Server di VS Code)

## ☁️ Cara Deploy ke Hosting (InfinityFree)

1. Upload seluruh isi folder ke `htdocs` (pastikan struktur `css/`, `js/`, `images/` ikut terupload)
2. Install Joomla via Softaculous di subfolder `artikel1` untuk bagian artikel
3. Pastikan path CSS/JS/gambar di setiap file HTML sesuai dengan struktur folder di server (case-sensitive)

## 👥 Tim Pengembang — Kelompok 5

| Nama | NIM |
|---|---|
| Nessa Novianti | 24104410007 |
| Muhammad Azkarmin Muhusini | 24104410037 |
| Faizal Ramadhan | 24104410033 |
| Hoki Kayana Qusyairi | 24104410035 |
| Nedy Bagus Lisdiono | 24104410010 |

## 📄 Lisensi

Project ini dibuat untuk keperluan pembelajaran/tugas kuliah semester 4.
