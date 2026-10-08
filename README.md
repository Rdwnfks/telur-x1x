# Kas Telur & Warung (PWA)

Aplikasi catatan keuangan usaha telur bebek dan warung. Bisa dipasang di layar utama HP dan jalan tanpa internet.

## Cara pasang di GitHub Pages
1. Buat repository baru di GitHub (mis. `kas-telur`), set **Public**.
2. Upload semua file: `index.html`, `manifest.webmanifest`, `sw.js`, `icon-192.png`, `icon-512.png`, `icon-maskable-512.png`.
3. Buka **Settings → Pages → Build and deployment**, pilih **Deploy from a branch**, branch `main`, folder `/ (root)`, lalu **Save**.
4. Tunggu 1–2 menit. Alamatnya: `https://USERNAME.github.io/kas-telur/`.
5. Buka alamat itu di HP: Android Chrome → menu ⋮ → **Install app / Tambahkan ke layar utama**. iPhone Safari → **Bagikan → Add to Home Screen**.

## Catatan penting
- Data disimpan di browser perangkat itu (localStorage). HP dan PC **tidak otomatis sinkron**.
- Gunakan tombol **Backup** (tab Bulanan) secara rutin, dan **Pulihkan** untuk memindahkan data ke perangkat lain.
- Setelah mengubah `index.html`, naikkan versi cache di `sw.js` (`kas-telur-v1` → `v2`) agar pengguna mendapat versi baru.
