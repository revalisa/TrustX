# Prompt Log - Modul 6 TrusX

## Tujuan
Memisahkan halaman HTML5 menjadi tiga halaman: beranda, daftar, dan masuk.

## Struktur
- index.html: halaman utama TrusX, pengecekan reputasi dan laporan komunitas.
- daftar.html: halaman pendaftaran akun.
- login.html: halaman masuk akun.

## Ketentuan Modul 6 yang diterapkan
- HTML5 semantik.
- Tidak menggunakan CSS eksternal, tag style, inline style, Bootstrap, atau Tailwind.
- Form menggunakan label, input, fieldset, legend, dan button.
- Gambar menggunakan path relatif ./assets/images/ dan alt text.
- Navigasi antarsitus menggunakan anchor.


# Prompt Log - Modul 6 TrusX: Formulir Laporan

## Tujuan
Membuat halaman HTML5 untuk formulir laporan transaksi berdasarkan referensi desain yang diberikan.

## Berkas
- `07-formulir-laporan.html`: halaman formulir laporan.
- `assets/images/trusx-logo.svg`: logo TrusX dalam format SVG.

## Struktur Konten
1. Header dengan tautan logo dan navigasi.
2. Pemberitahuan ketentuan laporan.
3. Form identitas akun transaksi.
4. Pilihan status transaksi.
5. Isian kronologi.
6. Unggah bukti pendukung.
7. Tabel contoh bukti yang dapat disertakan.
8. Pernyataan kebenaran data dan tombol lanjut ke verifikasi OTP.

## Ketentuan Modul 6 yang diterapkan
- Menggunakan HTML5 semantik: `header`, `nav`, `main`, `section`, `aside`, dan `footer`.
- Tidak menggunakan CSS eksternal, tag `style`, atribut `style`, Bootstrap, atau Tailwind.
- Input dikelompokkan memakai `fieldset` dan `legend`.
- Setiap input memiliki `label` yang terhubung melalui `for` dan `id`.
- Menggunakan elemen `table`, `ul`, `img`, `form`, `input`, dan `button`.
- Aset dipanggil melalui jalur relatif `./assets/images/`.
- Heading tersusun secara hierarkis.

## Catatan
Form menggunakan `action="#"` sebagai kerangka HTML. Pengiriman laporan, autentikasi pengguna, penyimpanan berkas, dan verifikasi OTP memerlukan backend atau implementasi tambahan; file HTML ini belum mengirim laporan sungguhan.
