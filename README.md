# Local Media Editor

**Editor Video & Audio 100% Lokal di Browser**

Tidak ada upload ke server. Semua proses berjalan di perangkat kamu menggunakan FFmpeg.wasm.

## ⚠️ Cara Pakai yang Benar (PENTING)

Error `origin 'null'` terjadi kalau kamu **membuka file HTML langsung**.

### Cara yang benar:

#### 1. Di komputer (paling mudah)

Buka terminal di folder `local-media-editor`, lalu jalankan:

```bash
python -m http.server 8080
# atau
python3 -m http.server 8080
```

Lalu buka browser dan kunjungi:
**http://localhost:8080**

#### 2. Di Android

- Install aplikasi **HTTP Server** / **Simple HTTP Server** / **KSWEB** dari Play Store
- Atau gunakan **Termux** + perintah `python -m http.server 8080`
- Atau upload `index.html` ke **GitHub Pages** / **Netlify** / **Vercel** (gratis)

#### 3. Extension Chrome (alternatif)

Install extension **"Web Server for Chrome"** → pilih folder ini → Start → buka URL yang muncul.

---

## Fitur

- ✅ Potong video/audio (trim)
- ✅ Ekstrak audio dari video
- ✅ Atur volume
- ✅ Ubah kecepatan (0.5× – 2×)
- ✅ Rotasi video (90° / 180° / 270°)
- ✅ Konversi format (MP4, WebM, MKV, MOV, MP3, WAV...)
- ✅ Kompres video (CRF)
- ✅ Preview sebelum & sesudah
- ✅ Unduh hasil langsung ke perangkat

## Privasi
File media **tidak pernah** dikirim ke internet.  
Hanya core FFmpeg (~31 MB) yang diunduh sekali dari CDN saat pertama kali dipakai.

## Catatan
- Butuh browser modern (Chrome / Edge / Firefox terbaru)
- Proses encoding cukup berat di perangkat lemah / video panjang
- Untuk potong cepat, gunakan tab **Potong**
