# AI
AI about me (Indonesia)

# Modern Answer Bot

![License](https://img.shields.io/badge/license-MIT-blue.svg)

Bot cerdas sederhana berbasis HTML, CSS, dan JavaScript dengan fitur interaktif seperti:

- 💬 Chatbot yang menjawab pertanyaan spesifik
- 🖼️ Menampilkan gambar saat menjawab `"punya istri"` atau `"musisi favorit"`
- 🎵 Memainkan musik otomatis saat menanyakan `"musisi favorit"`
- 🔊 Efek suara notifikasi saat bot merespons
- 🧩 Tombol saran pertanyaan
- 🌙 Mode gelap (opsional)
- 📱 Tampilan responsif untuk desktop dan mobile

---

## 📁 Struktur Folder

```
project-folder/
├── aii/
│   ├── istri.jpg
│   ├── istri1.jpg
│   ├── istri2.jpg
│   ├── istri3.jpg
│   ├── istri4.jpg
│   ├── istri5.jpg
│   ├── Kendrick.jpg
│   └── Kendrick.mp3
├── sounds/
│   └── notification.mp3
├── index.html
├── README.md
└── LICENSE
```

---

## ✅ Fitur Utama

| Fitur | Deskripsi |
|-------|-----------|
| 💬 Chat Responsif | Menjawab pertanyaan spesifik secara otomatis |
| 🖼️ Gambar Respons | Menampilkan gambar saat menjawab `"punya istri"` atau `"istri"` |
| 🎵 Musik Otomatis | Memainkan lagu `Kendrick.mp3` saat bertanya `"musisi favorit"` |
| ⏸ Stop Lagu Otomatis | Lagu berhenti ketika pengguna bertanya sesuatu selain `"musisi favorit"` |
| 🔊 Efek Suara Notifikasi | Memberikan notifikasi suara saat bot merespons |
| 🧩 Tombol Saran Pertanyaan | Membantu pengguna memulai percakapan |
| 📱 Responsif | Tampilan tetap rapi di perangkat mobile dan desktop |
| 🎨 Desain Minimalis & Estetik | Warna lembut dan animasi halus untuk pengalaman pengguna yang nyaman |

---
| 🔊 Efek Suara Notifikasi | Memberikan notifikasi suara saat bot merespons |
| 🧩 Tombol Saran Pertanyaan | Membantu pengguna memulai percakapan |
| 📱 Responsif | Tampilan tetap rapi di perangkat mobile dan desktop |
| 🎨 Desain Minimalis & Estetik | Warna lembut dan animasi halus untuk pengalaman pengguna yang nyaman |

---

## 🚀 Cara Menjalankan

1. Clone atau ekstrak semua file ke dalam satu folder.
2. Pastikan semua aset tersedia:
   - Gambar: `aii/istri.jpg`, `aii/Kendrick.jpg`
   - Musik: `aii/Kendrick.mp3`
   - Efek Suara: `sounds/notification.mp3`
3. Jalankan server lokal:

```bash
npx serve .
```

4. Buka browser dan kunjungi:
👉 `http://localhost:5000`

---

## 📝 Panduan Penggunaan

### Pertanyaan Spesifik yang Didukung:
- `makan dengan?`
- `genre musik favorit?`
- `musisi favorit?` *(akan memicu pemutaran lagu)*
- `ultah?`
- `hobby?`
- `punya istri?` *(akan menampilkan opsi istri 1–5)*
- `pernah pacaran?`

### Interaksi Tambahan:
- Klik tombol angka setelah bertanya `"punya istri?"` untuk melihat foto istri ke-n
- Lagu akan berhenti otomatis jika pengguna bertanya selain `"musisi favorit"`

---

## 📌 Catatan Penting

- Pastikan file audio (`notification.mp3`, `Kendrick.mp3`) tersedia di lokasi yang benar.
- Browser mungkin memblokir autoplay audio tanpa interaksi pengguna pertama kali.
- Gunakan server lokal untuk memastikan path relatif bekerja dengan baik (tidak akan berjalan optimal jika dibuka langsung via `file:///`).

---

## 🧩 Customisasi Lanjutan (Opsional)

Kamu bisa mengembangkan proyek ini lebih lanjut dengan:

- 🔁 Mengganti musik/konten gambar
- 🧠 Menambahkan jawaban AI menggunakan API (OpenAI, Gemini, dll.)
- 🎯 Menambahkan dark mode toggle
- 📱 Optimisasi tata letak untuk mobile app

---

## 📄 Lisensi

Proyek ini dilisensikan di bawah MIT License – lihat file [LICENSE](LICENSE) untuk detailnya.

---

## 👤 Dibuat oleh

[Your Name]  
📧 Email: prandika775@gmail.com  
🔗 GitHub: [github.com/andikagithub1](https://github.com/andikagithub1)

---

## 📦 Versi

v1.0.0

---
