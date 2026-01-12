# Copas

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Website](https://img.shields.io/badge/Website-Live-blueviolet)](https://your-deployed-url.com)

**Copas** — Super lightweight, **serverless**, **no database**, dan **secured** web app untuk menyimpan catatan langsung di browser. Cepat, aman, dan praktis, tanpa perlu backend.

---

## Demo

![Copas Demo](https://media.giphy.com/media/3o7aD6N1a5fE9v5e9w/giphy.gif)  
_Cukup tulis catatan, klik Simpan, dan dapatkan Original & Short URL dalam sekejap._

---

## Fitur Utama

- 💾 **Serverless & No Database**  
  Semua catatan disimpan langsung di browser atau via Short URL menggunakan Cloudflare Worker. Tanpa server, tanpa database.

- 🔐 **Encrypted & Secured**  
  Catatan terenkripsi end-to-end dengan AES-GCM. Hanya orang yang memiliki URL (dan password jika di-set) yang bisa membaca catatan.

- 🌐 **Original URL & Short URL**

  - **Original URL**: Data terenkripsi langsung di URL → buka kapan saja.
  - **Short URL**: Link pendek via Cloudflare Worker → mudah dibagikan.

- 📋 **Copy & QR Code**  
  Salin teks, URL, atau bagikan melalui QR Code.

- 🔑 **Password Optional**  
  Tambahkan kata sandi untuk mengunci catatan.

- 📝 **View-Only Mode**  
  Buka catatan tanpa mengubah data, cocok untuk berbagi.

---

## Cara Pakai

1. Buka halaman Copas di browser.
2. Tulis catatan di textarea.
3. Klik **Simpan** → Original URL muncul langsung, Short URL dibuat otomatis.
4. Salin URL atau bagikan via QR Code.

---

## Teknologi

- **Frontend**: HTML, TailwindCSS, Vanilla JS
- **Crypto**: Web Crypto API (AES-GCM)
- **Kompressi**: LZ-String
- **QR Code**: QRCode.js
- **Short URL**: Cloudflare Workers + KV

---

## Why Copas?

- ⚡ **Super lightweight**: Cepat, minimal, langsung jalan di browser.
- 🌐 **Serverless**: Tidak perlu backend.
- 🔒 **Secure**: End-to-end encryption untuk semua catatan.
- 💡 **Praktis**: Bisa digunakan kapan saja, di mana saja, cukup buka browser.

---

## License

MIT License
