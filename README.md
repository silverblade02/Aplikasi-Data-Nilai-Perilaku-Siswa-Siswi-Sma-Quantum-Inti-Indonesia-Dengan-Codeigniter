<h3 style="text-align:center">TUGAS LSP PEMROGRAM (NILAI PERILAKU SISWA/SISWI SMA QUANTUM INTI INDONESIA DENGAN CODEIGNITER)</h3>
<h3 style="text-align:center">ARI ROYANI BIYA</h3>
<h3 style="text-align:center">51418045</h3>
<h3 style="text-align:center">4IA13</h3>

Aplikasi ini mempunyai fitur CRUD (Create Read Update Delete) dan menggunakan database "murid" yang berada di dalam repository tersebut. Terdapat dua buah tabel yang digunakan pada aplikasi ini, yaitu tabel tbl_user dan tbl_nilai. Semua tabel yang disebutkan akan dijelaskan apa saja field serta tipe datanya pada README ini dan saya menggunakan framework CODEIGNITER untuk membuat aplikasi tersebut. 

1. Unit-Unit Reuse yang digunakan :
-	Ini merupakan reuse kodingan tambah yang mana kemudian akan digunakan kembali pada model update :

-	Hal ini juga sama dengan kode program index() dan edit() :\

-	Dan juga berlangsung pada form edit dan tambah :

2. Koneksi Database
Di dalam file database.php saya mengkoneksi database dengan nama "murid" dengan username root tanpa password

3. Tabel-tabel yang digunakan
tbl_nilai

tbl_user

5. Operasi untuk mengakses database
Operasi pengaksesan database ada pada config.php yang digunakan untuk untuk mengisi libraries dengan database yang sudah kita buat

7. Skenario pengujian database
- Jika menambahkan atau mengubah data nilai siswa/siswi apakah data di dalam tabel nilai akan bertambah dan berubah? Ya, akan bertambah dan berubah. Selanjutnya, akan menampilkan baris berwarna kalau nilai tersebut kurang dari 75 dengan keterangannya.

- Apakah data akan tersimpan jika tidak mengisi semua field pada form tambah dan ubah data? Tidak, harus mengisi semua field agar dapat menyimpan ataupun mengubahnya.

- Apakah data akan terhapus jika kita mengklik button hapus pada setiap baris? Ya, akan terhapus jika kita mengklik button hapus pada setiap baris.

-	Apakah dapat login ke dalam program tersebut? Ya, dengan mengisi username dan password akan dapat melogin ke dalam program tersebut


8. Pengunaan komentar pada program

Ini adalah komentar dari semua baris yang ada di dalam program saya. Hal ini digunakan untuk membuat tulisan tanpa terdeteksi oleh Bahasa pemrograman bahwa itu kode program. Cara kerjanya ketika menekan ctrl + shift + / atau ctrl + / pada saat kode program diblok maka akan membentuk sebuah komentar di dalam kode program. Jadi, otomatis tidak akan di deteksi oleh Bahasa pemrograman bahwa itu adalah tulisan biasa bukan kode program.

9. Penggunaan procedure dan function

Ini adalah semua procedure dan function yang terdapat pada program saya. Guna dari procedure dan function ini adalah untuk memberikan fungsi CRUD pada program saya. Cara kerjanya dengan menambahkan <?php defined('BASEPATH') OR exit('No direct script access allowed'); /?> diantara awalan dan akhir procedure pada PHP boleh anda tambahkan function yang sesuai anda inginkan.

10. Cara Kerja Algoritma
![Flowchart Program](https://user-images.githubusercontent.com/108471020/177028456-e9224454-8f7f-425c-bf7e-25b5418fa79c.jpg)
Ini merupakan cara kerja algoritma dengan menggunakan flowchart untuk login dan melakukan CRUD pada program tersebut.
