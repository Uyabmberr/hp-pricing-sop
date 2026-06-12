# HP Pricing SOP Calculator

Formulir inspeksi dan kalkulator pricing HP second-hand berdasarkan Sistem SOP Margin 25%.

## Fitur

- **Input data unit**: Merek, RAM/ROM, harga pasar
- **Penilaian kondisi fisik**: Dari mulus hingga LCD bermasalah
- **Kalkulasi penalti**: Berdasarkan kondisi kelengkapan dan fisik
- **Integrasi ChatGPT**: Otomatis generate prompt expert untuk negosiasi

## Cara Menggunakan

1. Buka `index.html` di browser
2. Isi data unit HP yang akan dibeli
3. Klik "Hitung & Eksekusi di GPT"
4. Sistem akan membuka ChatGPT dengan prompt lengkap untuk analisis pricing

## SOP Margin

- **Harga Beli Dasar** = Harga Pasar Termurah × 0,75
- **Harga Beli Final** = Harga Dasar - Total Penalti
- **Target Margin** = 25%

## Deployment ke Vercel

```bash
npm install -g vercel
vercel
```

Atau connect repository ke Vercel dashboard untuk auto-deploy.
