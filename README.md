# Analytics Studio — Data Analyst Portfolio V2

Website portfolio statis yang bisa diedit langsung di GitHub dan dihosting gratis melalui GitHub Pages.

## Mengganti website lama
1. Buka repository GitHub kamu.
2. Upload **isi folder** portfolio-v2 (bukan folder pembungkusnya) ke root repository. Pilih overwrite/replace jika diminta.
3. Pastikan `index.html`, `assets/`, dan `projects/` berada langsung di root repository.
4. Commit changes. Jika GitHub Pages sudah aktif (main / root), tunggu deployment dan refresh website dengan Ctrl+F5.
5. Hapus file lama yang tidak terpakai hanya setelah memastikan tidak digunakan.

## Edit identitas
- `assets/config.js`: nama, email, GitHub, LinkedIn.
- `index.html`: headline, bio, deskripsi proyek, judul, teks dan visual demo.
- `assets/style.css`: warna, spacing, layout, animasi.
- `projects/sales.html`, `customer.html`, `hr.html`: detail case study.
- `projects/project.css`: tampilan halaman studi kasus.

## Warna
- Deep teal `#09474b` (dominan)
- Muted teal `#467e82`
- Sage `#d4d5c5`
- White `#ffffff`
- Aksen mint `#b2f4d4` hanya untuk kontras.

## Penting
Grafik dan KPI pada halaman utama adalah **ilustrasi**, bukan hasil analisis nyata. Jangan mengklaim angka tersebut sebagai hasil proyek. Isi halaman studi kasus setelah analisis nyata selesai. Ganti `emailkamu@example.com` dan URL LinkedIn.

## Struktur
```
index.html
README.md
assets/
  config.js
  script.js
  style.css
projects/
  project.css
  sales.html
  customer.html
  hr.html
```

Tanpa build tools, framework, atau API key. Font Google opsional (fallback tersedia).
