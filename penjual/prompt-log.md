# Prompt Log - Modul 6 (Figma ke HTML5)

Alat AI yang digunakan adalah Claude (chat), untuk mengerjakan 11 layar hifi peran Seller. Hasil setiap tahap diuji dengan Nu Html Checker.

saya meminta Claude membuat HTML dari hifi seller sesuai ketentuan PDF Modul 6, dengan melampirkan PDF, 11 screenshot hifi, dan `index.html` hasil ekspor Figma. Hasilnya 11 halaman HTML semantik dan 9 aset SVG, tanpa CSS, atribut `style`, maupun framework. Hasil ini lolos validator dengan 0 error. Kode awal hasil ekspor Figma sendiri berupa `div` bersarang dengan class otomatis seperti `v296_*` dan tanpa landmark semantik, sehingga diganti dengan `header`, `nav`, `main`, `section`, dan `footer`.