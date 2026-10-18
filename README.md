# TAMA ORDER — Netlify
Website toko digital responsif dengan kartu produk, pilihan harga, modal pembayaran, tombol WhatsApp/Telegram, dan pilihan tema.

## Deploy
Upload isi project ke GitHub. Di Netlify pilih Add new site → Import an existing project → pilih repository. Build command kosongkan dan Publish directory isi `public`.

## Kustomisasi
Edit `public/app.js`: ganti `CONFIG.whatsappNumber`, `CONFIG.telegramUrl`, `CONFIG.qrisImage`, serta array `products`.

Catatan: ini versi frontend statis. Tidak ada backend/login admin, riwayat order tersimpan, atau verifikasi pembayaran otomatis. Pembayaran diverifikasi manual oleh admin. Gunakan hanya untuk produk legal dan aman.
