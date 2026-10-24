# Project 02 — Customer Behavior & Retention

## Business question
Bagaimana pola pembelian pelanggan, dan segmen mana yang menunjukkan peluang peningkatan retensi?

## Objectives
- Mengukur pelanggan aktif dan pelanggan yang melakukan pembelian berulang.
- Memahami frekuensi dan nilai pembelian.
- Melakukan cohort analysis jika data tanggal transaksi mendukung.
- Menyusun rekomendasi retensi yang dapat diuji.

## Tools
SQL, Python, Pandas, Matplotlib.

## Workflow
1. Periksa customer ID, tanggal transaksi, refund, dan transaksi duplikat.
2. Definisikan pelanggan aktif dan repeat purchase secara eksplisit.
3. Hitung metrik pelanggan dan tren cohort.
4. Visualisasikan pola, periksa bias periode observasi.
5. Tulis temuan beserta batasan data.

## Potential metrics
- Repeat purchase rate dengan denominator yang didefinisikan jelas.
- Purchase frequency per customer.
- Cohort retention berdasarkan bulan transaksi pertama.
- Recency: waktu sejak transaksi terakhir pada tanggal snapshot.

## Findings
> Isi setelah analisis aktual. Jangan mengasumsikan pelanggan yang tidak bertransaksi pada periode singkat pasti churn.

## Recommendations
> Buat rekomendasi yang spesifik terhadap segmen dan dukung dengan temuan.

## Deliverables
- `notebooks/` — notebook analisis yang dapat dijalankan ulang
- `sql/` — query untuk membangun tabel analisis
- `visuals/` — grafik dan hasil utama
- Dokumentasi dataset dan asumsi

## Data source
Tambahkan URL sumber dataset dan ketentuan penggunaannya di sini.
