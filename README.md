Panduan Menjalankan Cypress:
Ini adalah panduan singkat untuk menjalankan pengujian menggunakan Cypress di proyek yang telah Anda atur. Pastikan Anda telah mengikuti langkah-langkah di bawah ini untuk menjalankan pengujian dengan benar.


Persyaratan
Sebelum menjalankan pengujian Cypress, pastikan Anda telah memenuhi persyaratan berikut:


 - Node.js terinstal di komputer Anda
 - Proyek Cypress sudah dikonfigurasi dengan file cypress.json
 - Node_modules sudah ada di dalam proyek, meskipun diabaikan oleh Git (tercantum di dalam file .gitignore)

Langkah-langkah:

1. Instal Dependensi Cypress:
Pastikan Anda telah menginstal Cypress di dalam proyek Anda. Jalankan perintah berikut di terminal atau command prompt untuk menginstal Cypress dan dependensinya:

Copy code
npm install cypress
Inisialisasi Cypress:
Setelah instalasi selesai, inisialisasikan Cypress di dalam proyek Anda dengan menjalankan perintah:

**npx cypress open**

Jalankan Pengujian:
Setelah jendela Cypress terbuka, Anda dapat menjalankan pengujian dengan mengklik pada nama berkas pengujian yang ingin Anda jalankan di jendela Cypress. (form.cy.js)

Melihat Hasil Pengujian:
Setelah pengujian selesai dijalankan, Anda dapat melihat hasilnya di jendela Cypress. Laporan pengujian akan ditampilkan di sana bersama dengan detail tentang pengujian yang dilakukan.

Catatan Penting
Pastikan untuk memperbarui dan menjaga dependensi Cypress Anda tetap terbaru dengan menjalankan npm install cypress secara berkala.
Jika Anda mengalami masalah atau kesulitan, periksa dokumentasi resmi Cypress atau tanyakan pertanyaan Anda di komunitas Cypress.
