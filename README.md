# Portfolio Website — Aviev Avivy

Single-file static portfolio (`index.html`). No build step, no dependencies. Just upload.

## Isi
- `index.html` — seluruh website (HTML + CSS + JS inline). Fitur: dark/light mode, responsive, smooth scroll, scroll-reveal animation.

## Yang perlu dilengkapi (edit di `index.html`)
Cari & ganti placeholder ini:
- `your.email@example.com` → email kamu
- `https://www.linkedin.com/in/your-handle` → URL LinkedIn kamu
- `https://github.com/Battlewolf317` → cek/ganti username GitHub
- `https://wa.me/62xxxxxxxxxx` → nomor WhatsApp (format internasional, tanpa +/0 depan, mis. 628123456789)
- (opsional) foto/OG image, judul, teks hero

## Cara Upload / Deploy (pilih salah satu)

### 1. GitHub Pages (gratis)
1. Buat repo baru di GitHub, mis. `portfolio` (atau `username.github.io`).
2. Upload `index.html` ke root repo.
3. Settings → Pages → Source: `main` / root → Save.
4. Live di `https://username.github.io/portfolio/`.

### 2. Netlify (drag & drop, gratis)
1. Buka app.netlify.com → "Add new site" → "Deploy manually".
2. Drag folder `web/` (yang berisi `index.html`) ke area upload.
3. Langsung dapat URL (bisa diganti custom domain).

### 3. Vercel (gratis)
1. Import repo GitHub, atau `vercel` CLI di folder ini.
2. Framework preset: "Other" (static). Deploy.

### 4. Hosting biasa (cPanel/shared)
Upload `index.html` ke folder `public_html/`. Selesai.

## Tips
- Ganti nama file ke `index.html` (jangan diubah) supaya jadi halaman utama.
- Untuk custom domain, arahkan DNS sesuai instruksi host (Netlify/Vercel/Pages).
- Test lokal: cukup double-click `index.html` atau jalankan `python -m http.server` di folder ini lalu buka `http://localhost:8000`.
