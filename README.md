# SOP Kalkulator Harga HP

Aplikasi web untuk menghitung harga beli HP bekas berdasarkan SOP Margin 25%.

## Fitur
- Form input untuk merek & tipe HP
- Input kapasitas RAM/ROM
- Harga referensi dari marketplace (Shopee/Tokopedia)
- Evaluasi kondisi fisik dengan persentase penalti
- Dokumentasi kelengkapan dan aksesoris
- Integrasi otomatis dengan ChatGPT untuk kalkulasi detail

## Cara Penggunaan
1. Isi formulir dengan data HP yang akan dievaluasi
2. Klik tombol "Hitung & Eksekusi di GPT"
3. Data akan dikirim ke ChatGPT dengan prompt SOP Margin 25%
4. Dapatkan rekomendasi harga beli final dan strategi negosiasi

## Deployment ke Vercel

Repo ini sudah siap untuk di-deploy ke Vercel:

1. **Connect Repository ke Vercel:**
   - Buka [vercel.com](https://vercel.com)
   - Login dengan GitHub
   - Klik "Add New..." → "Project"
   - Pilih repository `hp-pricing-sop`
   - Klik "Deploy"

2. **Auto-deploy:**
   - Setiap push ke repository akan otomatis di-deploy
   - URL akan diberikan oleh Vercel

## Tech Stack
- HTML5
- CSS3 (Custom Properties)
- Vanilla JavaScript
- Vercel (Hosting)

## Lisensi
Proprietary - SOP Internal