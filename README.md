# Kulon Progo Job Fair 2026 - Official Landing Page

Website resmi pameran bursa kerja **Kulon Progo Job Fair 2026** yang diselenggarakan oleh Pemerintah Kabupaten Kulon Progo melalui Dinas Tenaga Kerja dan SIAPkerja Kementerian Ketenagakerjaan RI.

Fitur utama:
- 🎫 **Registrasi Tiket Masuk Real-Time**: Pembuatan e-pass resmi instan dengan kode QR vektor mandiri (offline & tanpa dependensi eksternal), barcode, dan data peserta.
- 🏢 **Direktori 45+ Perusahaan Exhibitor**: Indomaret, Novotel YIA, ibis YIA, RSU Queen Latifa, QUICK Traktor, PT Anggun Kreasi Garmen, PT Ameya, Citranet, PKSS, PNM, Bina Artha, Mandiri Taspen, dll.
- 💼 **Pencarian & Filter Lowongan Interaktif**: Filter sektor industri, jenjang pendidikan (SMA/SMK, D3, S1/S2), walk-in interview langsung, dan formasi ramah inklusi disabilitas.
- 📅 **Jadwal Acara & Rundown**: Sesi Hari 1 & Hari 2, ekspor kalender (.ics) dan Google Calendar, serta pengingat sesi.
- 🗺️ **Denah Exhibition Hall Interaktif**: Visual tata letak stan stan Zona A, B, C, D di Taman Budaya Kulon Progo.
- 📋 **Panduan "Bring Your CV"**: Checklist dokumen wajib bawa, tips wawancara, dan akses rute dari Stasiun Wates (7 menit) & Bandara YIA (15 menit).

---

## ⚡ Cara Menjalankan di GitHub Codespaces

Repositori ini sudah dilengkapi konfigurasi otomatis `.devcontainer/devcontainer.json` dan `package-lock.json`:

1. Buka repositori ini di GitHub.
2. Klik tombol hijau **Code** > tab **Codespaces** > **Create codespace on main**.
3. Codespaces akan otomatis menginstall dependensi melalui `npm install`.
4. Jalankan perintah server pengembangan:
   ```bash
   npm run dev
   ```
5. Port `3000` akan otomatis diforward dan jendela browser preview akan terbuka.

> **Catatan Penting untuk Codespaces**: File `vite.config.ts` sudah dikonfigurasi dengan `allowedHosts: true` dan `host: "0.0.0.0"`, sehingga URL preview Codespaces (`https://*.app.github.dev`) tidak akan diblokir oleh Vite.

---

## 💻 Cara Menjalankan di Komputer Lokal (Local Machine)

### Kebutuhan:
- Node.js versi 18, 20, atau 22 (Disarankan Node.js LTS v20+)
- npm, yarn, pnpm, atau bun

### Langkah-langkah:
```bash
# 1. Clone repositori
git clone https://github.com/<username>/<repo-name>.git
cd <repo-name>

# 2. Install dependensi
npm install

# 3. Jalankan server lokal
npm run dev
```

Buka browser Anda di: `http://localhost:3000`

---

## 🛠️ Perintah Lainnya

- **Build untuk Production**:
  ```bash
  npm run build
  ```
  Hasil build statis akan tersimpan di folder `dist/` dan siap dideploy ke hosting mana pun (Vercel, Netlify, Cloudflare Pages, GitHub Pages).

- **Preview Hasil Build**:
  ```bash
  npm run preview
  ```

- **Pemeriksaan Type & Linter**:
  ```bash
  npm run lint
  ```

---

## 🌐 Deploy ke Hosting Gratis (Vercel / Netlify / Cloudflare Pages)

1. **Vercel**: Import repository GitHub, pilih framework preset **Vite**, klik **Deploy**.
2. **Netlify**: Connect GitHub repository, set Build Command: `npm run build`, Publish directory: `dist`.
3. **Cloudflare Pages**: Connect GitHub repository, Framework preset **Vite**, Build output directory: `dist`.

---

© 2026 Dinas Tenaga Kerja Kabupaten Kulon Progo. Raih Peluang • Tunjukkan Potensi • Wujudkan Masa Depan.
