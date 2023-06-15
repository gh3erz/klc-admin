# KLC Admin
KLC Admin adalah sebuah aplikasi yang memungkinkan administrator untuk mengelola konten dan fitur yang ada dalam sebuah platform. Dengan webpanel ini, administrator dapat mengatur beasiswa, referensi, banner, dan kutipan dengan mudah.

## Fitur

- **Beasiswa**: Fitur ini memungkinkan administrator untuk menambah, mengedit, dan menghapus informasi beasiswa. Pengguna juga dapat mencari beasiswa dan mengajukan aplikasi.
- **Referensi**: Modul referensi memungkinkan administrator mengelola dan mempublikasikan referensi.
- **Banner**: Fitur ini memungkinkan administrator untuk memperbarui tampilan banner di KLC User dengan gambar atau banner yang relevan.
- **Quotes**: Modul quotes memungkinkan administrator untuk menambahkan kutipan inspiratif yang akan ditampilkan di KLC User.

## Teknologi yang Digunakan

- [React](https://reactjs.org/): Library JavaScript untuk membangun antarmuka pengguna (UI) yang interaktif.
- [Material UI](https://mui.com/): Framework UI untuk React yang mengimplementasikan desain Material Design dari Google.
- [Tailwind CSS](https://tailwindcss.com/): Framework CSS utility-first yang memungkinkan penulisan kode CSS yang cepat dan fleksibel dengan menggunakan kelas utilitas.

## Cara Menggunakan

1. Clone repositori ini ke mesin lokal Anda.
2. Buka terminal dan arahkan ke direktori proyek.
3. Jalankan perintah `npm install` untuk menginstal semua dependensi.
4. Ubah file konfigurasi sesuai kebutuhan Anda.
5. Jalankan perintah `npm start` untuk menjalankan KLC Admin di lokal Anda.

## Penambahan Swalalert2

Untuk menambahkan Swalalert2 ke dalam proyek KLC Admin, ikuti langkah-langkah berikut:

1. Instal Swalalert2: Jalankan perintah `npm install sweetalert2` dalam terminal proyek untuk menginstal library Swalalert2.
2. Impor library: Di file JavaScript yang ingin Anda gunakan Swalalert2, impor library dengan menambahkan baris berikut di bagian atas file:

   ```javascript
   import Swal from 'sweetalert2';
   
3. Gunakan Swalalert2: Anda dapat menggunakan Swalalert2 untuk menampilkan kotak dialog yang menarik dan interaktif. Berikut adalah contoh penggunaan Swalalert2:

   ```javascript
    Swal.fire({
    icon: 'success',
    title: 'Sukses',
    text: 'Data berhasil disimpan.',
    });

    
4.   Anda juga dapat menyesuaikan pesan dengan menambahkan tombol, ikon, atau elemen lainnya. Swalalert2 menyediakan banyak opsi dan metode yang dapat Anda       gunakan untuk mengubah tampilan dan perilaku kotak dialog.

     ```javascript
     Swal.fire({
       icon: 'warning',
       title: 'Konfirmasi',
       text: 'Apakah Anda yakin ingin menghapus data ini?',
       showCancelButton: true,
       confirmButtonText: 'Ya',
       cancelButtonText: 'Batal',
     }).then((result) => {
       if (result.isConfirmed) {
         // Tindakan yang akan dijalankan jika pengguna menekan tombol 'Ya'
       }
     });

Pastikan untuk mengikuti petunjuk instalasi dan konfigurasi yang tepat sebelum menjalankan aplikasi ini. Pastikan juga untuk memperbarui file README.md dengan informasi yang lebih detail sesuai dengan kebutuhan.


