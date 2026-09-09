# Pulba Digital Tools

Landing page untuk menampilkan kumpulan tools digital yang dibuat oleh Pulba Digital dalam satu halaman.

Website ini menggunakan pendekatan Swiss Style minimalis dengan fokus pada grid, tipografi, whitespace, navigasi yang jelas, dan struktur informasi yang teratur.

## Preview

Landing page menampilkan:

- Identitas Pulba Digital
- Hero section
- Daftar tools
- Deskripsi singkat setiap aplikasi
- Tombol akses langsung ke masing-masing aplikasi
- Bagian visual system
- Footer identitas Pulba Digital

## Tools

### 01. Invoice Generator

Aplikasi untuk membuat invoice secara digital.

Fungsi utama:

- Membuat invoice.
- Mengatur item dan harga.
- Mendukung diskon.
- Mendukung adjustment.
- Menyiapkan hasil invoice untuk PDF atau image.
- Cocok untuk kebutuhan jasa dan transaksi dengan klien.

Akses:

https://innvoice.pages.dev/

### 02. Bagi Uang

Aplikasi untuk membantu mengatur dan membagi pemasukan berdasarkan kebutuhan keuangan.

Akses:

https://bagi-uang.pages.dev/

### 03. WordLayout Pro

Tool untuk membantu proses formatting dokumen Word.

Fungsi yang ditampilkan dalam landing page:

- Preset formatting dokumen.
- Karya ilmiah.
- Buku.
- Skripsi.
- Novel.
- Section break.
- Page break.
- Mirror margins.
- Penomoran halaman.

Akses:

https://wordlayout.pulbagrup.workers.dev/

### 04. PhotoTone Studio

Tool untuk pengolahan tone dan warna foto.

Fungsi yang ditampilkan dalam landing page:

- Preset.
- Tone.
- Detail.
- Warna.
- Vignette.
- Grain.
- Batch processing.
- Export beberapa format.

Akses:

https://phototone.pulbagrup.workers.dev/

### 05. Prompt Vault

Aplikasi untuk menyimpan dan mengelompokkan prompt.

Cocok untuk kebutuhan:

- Desain.
- AI.
- Pembelajaran.
- Coding.
- Pekerjaan digital.
- Koleksi prompt pribadi.

Akses:

https://web-prompt-4pk.pages.dev/

## Teknologi

Landing page dibuat menggunakan teknologi web dasar:

- HTML5.
- CSS3.
- Responsive layout.
- CSS Grid.
- CSS Flexbox.
- Native anchor navigation.
- Tidak menggunakan framework eksternal.
- Tidak menggunakan library JavaScript eksternal.

Logo Pulba Digital disimpan langsung di dalam file HTML sebagai Base64 sehingga halaman dapat digunakan sebagai satu file tanpa dependensi file gambar terpisah.

## Struktur Project

```text
pulba-digital-tools/
├── pulba-digital-tools.html
└── README.md
```

## Menjalankan Secara Lokal

Tidak diperlukan proses build.

Cukup buka file berikut menggunakan browser:

```text
pulba-digital-tools.html
```

Atau jalankan menggunakan local server jika ingin menguji perilaku halaman melalui environment HTTP.

Contoh menggunakan Python:

```bash
python -m http.server 8000
```

Kemudian buka:

```text
http://localhost:8000
```

## Struktur Halaman

### Header

Header berisi:

- Logo Pulba Digital.
- Navigasi Tools.
- Navigasi Prinsip.
- Navigasi Pulba Digital.

### Hero

Hero menggunakan headline:

```text
TOOLS
BY PULBA.
```

Bagian ini menjadi pengenal utama halaman dan memberikan konteks bahwa halaman berisi kumpulan tools buatan Pulba Digital.

### Tool Index

Bagian utama berisi lima aplikasi.

Setiap kartu mempunyai:

- Nomor tool.
- Nama aplikasi.
- Deskripsi.
- Kategori.
- Tombol akses.

Tombol menggunakan simbol `↗` dan membuka aplikasi pada tab baru.

### Visual System

Bagian ini menjelaskan prinsip visual landing page:

- Clear.
- Useful.
- Specific.

### Footer

Footer menampilkan identitas Pulba Digital dan tahun.

## Desain

Konsep visual menggunakan prinsip Swiss Style:

- Grid terstruktur.
- Alignment konsisten.
- Whitespace yang luas.
- Tipografi sans-serif.
- Headline berukuran besar.
- Garis pembatas tipis.
- Penggunaan warna yang terbatas.
- Elemen dekoratif yang minim.
- Fokus pada hierarki informasi.

Warna utama mengikuti identitas logo Pulba Digital.

Variabel CSS yang digunakan:

```css
--ink: #152441;
--ink-2: #263a5d;
--muted: #687080;
--blue: #3ea6e0;
--line: #d9dde5;
--paper: #ffffff;
--soft: #f5f7fa;
```

## Responsive Design

Landing page dirancang agar dapat digunakan pada desktop dan perangkat mobile.

Pada layar yang lebih kecil:

- Grid tools berubah menjadi satu kolom.
- Hero berubah menjadi layout vertikal.
- Navigasi disederhanakan.
- Bagian visual system berubah menjadi satu kolom.
- Footer berubah menjadi layout vertikal.

## Customization

Konten dapat diubah langsung dari file HTML.

Beberapa bagian yang mudah disesuaikan:

- Nama tool.
- Deskripsi tool.
- URL aplikasi.
- Kategori tool.
- Headline.
- Warna.
- Ukuran typography.
- Spacing.
- Navigasi.
- Footer.

URL aplikasi terdapat pada atribut `href`.

Contoh:

```html
<a href="https://innvoice.pages.dev/" target="_blank" rel="noopener noreferrer">
  ↗
</a>
```

Untuk menambahkan tool baru, tambahkan elemen `article` dengan class:

```html
<article class="tool">
  ...
</article>
```

## Deployment

Karena project hanya menggunakan HTML dan CSS, file dapat dideploy ke berbagai static hosting.

Contoh platform:

- Cloudflare Pages.
- GitHub Pages.
- Netlify.
- Vercel.
- Static hosting lainnya.

Tidak diperlukan database atau server-side runtime untuk landing page ini.

## Konten Eksternal

Landing page mengarahkan pengguna ke aplikasi berikut:

| Tool | URL |
|---|---|
| Invoice Generator | https://innvoice.pages.dev/ |
| Bagi Uang | https://bagi-uang.pages.dev/ |
| WordLayout Pro | https://wordlayout.pulbagrup.workers.dev/ |
| PhotoTone Studio | https://phototone.pulbagrup.workers.dev/ |
| Prompt Vault | https://web-prompt-4pk.pages.dev/ |

## Lisensi

Project ini dibuat untuk kebutuhan Pulba Digital.

Penggunaan, modifikasi, dan distribusi project mengikuti kebijakan dan kebutuhan pemilik project.

## Author

Pulba Digital

Indonesia · 2026
