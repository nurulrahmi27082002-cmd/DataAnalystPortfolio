# Project 03 — E-Commerce Business Intelligence

## Business question
Bagaimana tim bisnis dapat memantau performa pesanan, revenue, pembatalan, dan produk melalui satu dashboard?

## Objectives
- Menetapkan definisi KPI yang konsisten.
- Menganalisis tren pesanan dan nilai transaksi.
- Membandingkan performa produk atau kategori.
- Merancang dashboard yang membantu monitoring dan investigasi.

## Tools
SQL, Power BI, data modeling.

## Workflow
1. Dokumentasikan tabel, grain data, dan relasi.
2. Validasi status pesanan, pembatalan, refund, dan tanggal.
3. Definisikan KPI bersama konteks bisnis.
4. Siapkan query atau model data yang dapat diaudit.
5. Bangun dashboard overview dan halaman analisis detail.
6. Uji filter, agregasi, dan konsistensi angka.

## KPI candidates
- Total orders: jumlah order unik dengan status yang dijelaskan.
- Revenue: definisikan perlakuan untuk pembatalan dan refund.
- Average order value: revenue / jumlah order yang memenuhi definisi.
- Cancellation rate: order dibatalkan / order yang memenuhi denominator.
- Product contribution: kontribusi produk berdasarkan metrik yang dipilih.

## Findings
> Isi dengan temuan terverifikasi dari dataset, periode analisis, dan visual pendukung.

## Recommendations
> Rekomendasi harus dapat ditelusuri ke KPI dan temuan, serta menyebutkan keterbatasan analisis.

## Deliverables
- `sql/` — query dan transformasi
- `dashboard/` — file atau tautan dashboard
- `data-dictionary.md` — definisi kolom dan metrik
- Dokumentasi model data dan keterbatasan

## Data source
Tambahkan URL sumber dataset dan ketentuan penggunaannya di sini.
