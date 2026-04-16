# SDG 9 Indonesia — Website Edukasi

Website multi-halaman berbahasa Indonesia tentang Sustainable Development Goals (SDGs) PBB, dengan fokus pada **SDG 9: Industri, Inovasi, dan Infrastruktur** — khususnya **Target 9.c: Perluasan Akses TIK dan Internet Terjangkau** di Indonesia.

## Gambaran Proyek

Website ini dibangun sebagai proyek edukasi berbasis metodologi **Design Thinking** (Empati → Ideasi → Prototipe → Pengujian → Refleksi). Setiap tahap memiliki halaman tersendiri yang saling terhubung melalui navigasi konsisten.

## Struktur Halaman

| File | Halaman | Deskripsi |
|------|---------|-----------|
| `public/index.html` | Beranda | Hero SDGs, grid 17 SDG, fakta & angka Indonesia, Target 9.c |
| `public/empathy.html` | Empati & Riset | Persona pengguna, identifikasi masalah, temuan riset |
| `public/ideation.html` | Ideasi | 6 ide solusi, tabel evaluasi, pertanyaan HMW |
| `public/prototype.html` | Prototipe | Mockup DesaNet, fitur utama, arsitektur teknis |
| `public/testing.html` | Pengujian | Metodologi 3 fase, umpan balik pengguna, perbaikan iteratif |
| `public/reflection.html` | Refleksi | Wawasan, dampak, pelajaran, dan roadmap masa depan |

## Teknologi

- **HTML5** — Semantik dan aksesibel
- **CSS3** — Custom properties, Grid, Flexbox, animasi
- **JavaScript** — Navigasi mobile, IntersectionObserver animasi
- **Google Fonts** — DM Serif Display + DM Sans
- **Desain** — Responsif (mobile-first), tanpa framework eksternal

## Cara Menjalankan Secara Lokal

Karena ini adalah file HTML statis murni, cukup buka langsung di browser:

```bash
# Opsi 1: Buka langsung
open public/index.html

# Opsi 2: Gunakan server lokal sederhana
npx serve public
# atau
python3 -m http.server 8080 --directory public
# Buka: http://localhost:8080
```

### Menggunakan Netlify CLI (untuk proyek ini)

```bash
npm run dev
# Akses: http://localhost:8888
```

## Fitur Desain

- **Palette warna**: Warm off-white (`#F7F4EF`) + oranye SDG 9 (`#FD6925`) sebagai aksen utama
- **Tipografi**: DM Serif Display (judul) + DM Sans (teks)
- **Responsif**: Navbar mobile, layout grid yang kolaps di layar kecil
- **Aksesibel**: Kontras WCAG AA, ukuran tap target minimum 44px
- **Performa**: Animasi berbasis CSS transform/opacity, font dari Google CDN

## Referensi Konten

- APJII (2023). *Laporan Survei Internet Indonesia 2023*
- BPS (2023). *Statistik Telekomunikasi Indonesia 2022*
- ITU (2023). *Measuring Digital Development: Facts and Figures 2023*
- Kominfo (2022). *Peta Jalan Indonesia Digital 2021–2024*
- Sachs et al. (2023). *Sustainable Development Report 2023*
- World Bank (2022). *Indonesia Digital Economy Report*
- UNICEF Indonesia (2022). *Are Children Really Learning?*
