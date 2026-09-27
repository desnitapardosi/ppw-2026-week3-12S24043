# Portfolio Desnita Pardosi

## Pengembangan Halaman Web Portofolio & Layanan Interaktif Accessible Berbasis HTML5 dan Modern CSS

## Deskripsi

Project ini merupakan pengembangan halaman web portofolio pribadi yang dibuat sebagai bagian dari tugas praktikum Pemrograman dan Pengujian Web.

Project ini merupakan kelanjutan dari tugas praktikum Minggu 2, di mana halaman portofolio yang sebelumnya dibangun menggunakan HTML5 semantik dan CSS murni kemudian dikembangkan dan direfaktor dengan menggunakan framework Bootstrap 5.3 serta Custom CSS.

Website dikembangkan dalam bentuk single-page portfolio untuk menyajikan informasi akademik, kemampuan, proyek, dan layanan konsultasi secara terstruktur dan interaktif.

Pada Minggu 3, pengembangan difokuskan pada integrasi Bootstrap 5.3, responsive navbar, responsive grid untuk project, Bootstrap Modal, Bootstrap Icons, serta integrasi Bootstrap dengan Custom CSS untuk mempertahankan identitas visual website.

Project menggunakan Git dan GitHub sebagai version control serta GitHub Pages sebagai media deployment.

## Tujuan Project

Project ini bertujuan untuk:

- Melanjutkan dan mengembangkan project portofolio dari praktikum Minggu 2.
- Mengintegrasikan framework Bootstrap 5.3 ke dalam halaman web.
- Menerapkan responsive layout menggunakan Bootstrap Grid.
- Membuat responsive navbar dengan fitur collapse.
- Mengembangkan project cards dengan Bootstrap Grid.
- Mengimplementasikan Bootstrap Modal untuk menampilkan detail proyek.
- Menggunakan Bootstrap Icons untuk mendukung tampilan antarmuka.
- Mempertahankan custom design melalui Custom CSS Overrides.
- Menampilkan informasi akademik, proyek, dan keterampilan secara terstruktur.
- Mempertahankan struktur HTML5 semantik dan prinsip accessibility.
- Menggunakan Git dan GitHub untuk pengelolaan source code.
- Melakukan deployment menggunakan GitHub Pages.

## Identitas

| Informasi | Keterangan |
|---|---|
| Nama | Desnita Pardosi |
| NIM | 12S24043 |
| Program Studi | S1 Sistem Informasi |
| Institusi | Institut Teknologi Del |
| Angkatan | 2024 |
| Mata Kuliah | Pemrograman dan Pengujian Web |
| Tahun | 2026 |

## Teknologi yang Digunakan

- HTML5
- CSS3
- Bootstrap 5.3.3
- Bootstrap Icons 1.11.3
- Flexbox
- CSS Grid
- Responsive Design
- JavaScript
- Git
- GitHub
- GitHub Pages

## Pengembangan dari Minggu 2

Project Minggu 3 merupakan refactoring dan pengembangan dari halaman portofolio Minggu 2.

| Aspek | Minggu 2 | Minggu 3 |
|---|---|---|
| Styling | HTML5 + CSS murni | Bootstrap 5.3 + Custom CSS |
| Layout | Flexbox dan CSS Grid | Bootstrap Grid + Custom CSS |
| Navbar | Navbar custom | Responsive Bootstrap Navbar |
| Project | 3 proyek | 5 proyek |
| Project Layout | CSS custom | Bootstrap Responsive Grid |
| Detail Project | Informasi pada halaman | Bootstrap Modal |
| Icons | Terbatas | Bootstrap Icons |
| Responsive | Media Query CSS | Bootstrap Breakpoints + Custom CSS |
| Form | Form HTML5 | Form dengan Bootstrap + HTML5 Validation |
| Interaktivitas | CSS dan HTML | Bootstrap Components + JavaScript |
| Deployment | GitHub Pages | GitHub Pages |

## Implementasi Bootstrap 5.3

Bootstrap 5.3.3 diintegrasikan melalui CDN pada bagian `<head>` untuk membantu membangun layout dan komponen responsive.

Bootstrap digunakan pada beberapa bagian website, yaitu:

- Responsive Navbar.
- Responsive Grid untuk project cards.
- Button dan utility classes.
- Modal untuk detail proyek.
- Bootstrap Icons.
- Responsive spacing dan alignment.

Bootstrap JS Bundle juga digunakan agar komponen interaktif seperti navbar collapse dan modal dapat berfungsi.

## Responsive Navbar

Navbar website dikembangkan menggunakan komponen Bootstrap dengan fitur responsive collapse.

Pada ukuran layar yang lebih kecil, menu navigasi dapat dibuka dan ditutup menggunakan tombol hamburger.

Struktur yang digunakan antara lain:

- `navbar`
- `navbar-expand-lg`
- `navbar-toggler`
- `collapse`
- `navbar-collapse`

## Responsive Project Grid

Project ditampilkan menggunakan Bootstrap Grid dengan konfigurasi:

```html
row row-cols-1 row-cols-md-2 row-cols-lg-3 g-4