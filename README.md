# 🔔 Web Alarm Online

Aplikasi web untuk mengatur alarm otomatis dengan import data dari file Excel. Mendukung alarm berulang harian dan notifikasi suara.

## ✨ Fitur

- **Import Excel**: Upload file Excel (.xlsx, .xls) untuk mengatur multiple alarm sekaligus
- **Alarm Berulang**: Mendukung alarm yang berulang setiap hari
- **Notifikasi Suara**: Beep sound otomatis saat alarm berbunyi
- **Tampilan Real-time**: Jam dan tanggal yang update secara real-time
- **Responsive Design**: Tampilan yang menyesuaikan dengan berbagai ukuran layar
- **Download Template**: Template Excel yang bisa didownload langsung

## 🚀 Demo

[Live Demo](https://your-username.github.io/web-alarm-online)

## 📱 Screenshot

![Web Alarm Screenshot](screenshot.png)

## 🔧 Instalasi

1. **Clone repository**
```bash
git clone https://github.com/your-username/web-alarm-online.git
cd web-alarm-online
```

2. **Buka di browser**
```bash
# Buka file index.html di browser favorit Anda
# atau gunakan live server untuk development
```

## 📊 Format File Excel

File Excel harus mengikuti format berikut:

### Format Lengkap (5 kolom)
| Kolom A | Kolom B | Kolom C | Kolom D | Kolom E |
|---------|---------|---------|---------|---------|
| Tanggal | Waktu | Judul | Deskripsi | Status |
| 2024-01-01 | 08:00 | Meeting Tim | Rapat koordinasi | Aktif |
| 2024-01-01 | 14:30 | Minum Obat | Reminder obat | Aktif |

### Format Sederhana (2 kolom - Alarm Harian)
| Kolom A | Kolom B |
|---------|---------|
| Waktu | Status |
| 08:00 | Aktif |
| 14:30 | Aktif |

## 🎯 Cara Penggunaan

1. **Upload File Excel**
   - Klik tombol "Pilih File Excel"
   - Pilih file Excel yang berisi data alarm
   - File akan diproses otomatis

2. **Template Excel**
   - Klik "Download Template Excel" untuk mendapatkan contoh format
   - Isi data alarm sesuai kebutuhan
   - Upload kembali file yang sudah diisi

3. **Monitoring Alarm**
   - Alarm akan otomatis dicek setiap detik
   - Notifikasi suara akan berbunyi saat alarm aktif
   - Status alarm akan berubah sesuai kondisi

## 🔊 Fitur Suara

- **Beep Sound**: 3x beep otomatis saat alarm berbunyi
- **Web Audio API**: Menggunakan teknologi Web Audio untuk suara yang konsisten
- **Fallback Notification**: Notifikasi visual jika audio tidak tersedia

## 🌐 Teknologi

- **HTML5**: Struktur aplikasi
- **CSS3**: Styling dengan gradient dan animasi
- **JavaScript ES6**: Logika aplikasi
- **SheetJS**: Library untuk membaca file Excel
- **Web Audio API**: Untuk notifikasi suara

## 📁 Struktur Project

```
web-alarm-online/
├── index.html          # File HTML utama
├── style.css           # Stylesheet
├── script.js           # JavaScript logic
├── README.md           # Dokumentasi
└── template_alarm.xlsx # Template Excel (akan didownload)
```

## 🐛 Troubleshooting

### Alarm tidak berbunyi?
- Pastikan browser mengizinkan autoplay audio
- Coba klik di halaman web terlebih dahulu (requirement browser modern)
- Periksa volume sistem

### File Excel tidak terbaca?
- Pastikan format file .xlsx atau .xls
- Periksa struktur kolom sesuai template
- Pastikan tidak ada cell kosong di data penting

### Waktu tidak sesuai?
- Periksa timezone browser
- Pastikan format waktu HH:MM (24 jam)
- Cek format tanggal YYYY-MM-DD

## 🤝 Kontribusi

1. Fork repository
2. Buat feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit perubahan (`git commit -m 'Add AmazingFeature'`)
4. Push ke branch (`git push origin feature/AmazingFeature`)
5. Buat Pull Request

## 📝 License

Distributed under the MIT License. See `LICENSE` for more information.

## 👤 Author

**Your Name**
- GitHub: [@your-username](https://github.com/your-username)
- Email: your.email@example.com

## 🙏 Acknowledgments

- [SheetJS](https://sheetjs.com/) untuk library Excel
- [Web Audio API](https://developer.mozilla
