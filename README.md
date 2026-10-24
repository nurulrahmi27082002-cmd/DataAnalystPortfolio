# Data Analyst Portfolio — GitHub Pages

Portfolio HTML/CSS/JavaScript tanpa framework atau build step. Responsif dan dapat diedit langsung di GitHub.

## Mulai
1. Buat repository publik GitHub bernama `data-analyst-portfolio`.
2. Upload semua isi folder ini ke root repository (bukan folder ZIP-nya).
3. Buka `assets/config.js` melalui GitHub → ikon pensil **Edit**. Ganti nama, email, GitHub, LinkedIn, judul/deskripsi proyek.
4. Buka **Settings → Pages → Build and deployment → Deploy from a branch**. Pilih `main` dan `/ (root)` lalu Save.
5. Situs biasanya muncul di `https://USERNAME.github.io/data-analyst-portfolio/` setelah deployment berhasil.
6. Untuk mengubah warna/tipografi/layout, edit `assets/style.css`. Untuk studi kasus, edit `projects/*.html`.

## Palet
- `#09474b` — primary (target 50%)
- `#467e82` — secondary (15%)
- `#d4d5c5` — sage (20%)
- `#ffffff` — white (15%)

Proporsi adalah panduan desain, bukan ukuran piksel eksak.

## Struktur
- `index.html`: halaman utama
- `assets/config.js`: teks & tautan profil/proyek
- `assets/app.js`: render project cards
- `assets/style.css`: tampilan & responsive design
- `projects/`: tiga halaman studi kasus
- `deliverables/{sales,customer,hr}/`: tempat berkas Excel, Python, SQL, Power BI, Word, PowerPoint

## Format file yang disarankan untuk setiap proyek
- `01_data_cleaning.xlsx`
- `02_analysis.ipynb`
- `03_queries.sql`
- `04_dashboard.pbix`
- `05_analysis_report.docx`
- `06_stakeholder_presentation.pptx`
- `07_dashboard_preview.png`

Tambahkan tautan ke file dari halaman proyek. File Power BI `.pbix` harus dibuka dengan Power BI Desktop; untuk dashboard web gunakan tautan publik yang aman dan tidak memuat data sensitif.

## Penting
Ini adalah **template/blueprint**, bukan tiga proyek analisis yang telah selesai. Jangan menampilkan insight, angka, atau hasil yang belum benar-benar dihitung. Pastikan dataset publik diizinkan untuk digunakan dan hindari mengunggah data rahasia. Tautan CV `assets/CV.pdf` akan berfungsi setelah Anda menambahkan file tersebut. Ganti tautan kontak placeholder sebelum dipublikasikan.
