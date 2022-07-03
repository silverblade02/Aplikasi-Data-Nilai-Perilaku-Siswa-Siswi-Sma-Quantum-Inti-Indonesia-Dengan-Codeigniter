<h3 style="text-align:center">TUGAS LSP PEMROGRAM (NILAI PERILAKU SISWA/SISWI SMA QUANTUM INTI INDONESIA DENGAN CODEIGNITER)</h3>
<h3 style="text-align:center">ARI ROYANI BIYA</h3>
<h3 style="text-align:center">51418045</h3>
<h3 style="text-align:center">4IA13</h3>

Aplikasi ini mempunyai fitur CRUD (Create Read Update Delete) dan menggunakan database "murid" yang berada di dalam repository tersebut. Terdapat dua buah tabel yang digunakan pada aplikasi ini, yaitu tabel tbl_user dan tbl_nilai. Semua tabel yang disebutkan akan dijelaskan apa saja field serta tipe datanya pada README ini dan saya menggunakan framework CODEIGNITER untuk membuat aplikasi tersebut. 

1. Unit-Unit Reuse yang digunakan :
-	Ini merupakan reuse kodingan tambah yang mana kemudian akan digunakan kembali pada model update :
<img src='![image](https://user-images.githubusercontent.com/108471020/177027697-903d8d9e-b29d-4dae-aec6-b7720c0a6897.png)'></img>
<img src='![image](https://user-images.githubusercontent.com/108471020/177027701-dbc8eaaf-3d6b-4d27-b3b1-8ec06fe2e095.png)'></img>

-	Hal ini juga sama dengan kode program index() dan edit() :
<img src='![image](https://user-images.githubusercontent.com/108471020/177027709-1abff292-39a8-48cf-94a9-26d9770edb84.png)'></img>
<img src='![image](https://user-images.githubusercontent.com/108471020/177027735-7e4f5689-9183-4133-b2ad-15451a42c911.png)'></img>

-	Dan juga berlangsung pada form edit dan tambah :
<img src='![image](https://user-images.githubusercontent.com/108471020/177027762-e9fef56c-08aa-4c47-bb79-1b1e51492839.png)'></img>
<img src='![image](https://user-images.githubusercontent.com/108471020/177027767-a82b5b5f-33c3-4cc9-b341-63bcb501fcf9.png)'></img>

2. Koneksi Database
Di dalam file database.php saya mengkoneksi database dengan nama "murid" dengan username root tanpa password
<img src='![image](https://user-images.githubusercontent.com/108471020/177027770-49423bf7-f610-46ae-9ea2-36d3c130ed0f.png)'></img>

3. Tabel-tabel yang digunakan
tbl_nilai
<img src='![image](https://user-images.githubusercontent.com/108471020/177027853-39692f2d-2866-4206-8a20-7030427db7cd.png)'></img>

tbl_user
<img src='![image](https://user-images.githubusercontent.com/108471020/177027856-41000512-ee58-4655-9e27-73d8cb112bcb.png)'></img>

5. Operasi untuk mengakses database
Operasi pengaksesan database ada pada config.php yang digunakan untuk untuk mengisi libraries dengan database yang sudah kita buat
<img src='![image](https://user-images.githubusercontent.com/108471020/177027869-72ed94a7-2ee5-4c05-afdb-81580f70995a.png)'></img>

7. Skenario pengujian database
- Jika menambahkan atau mengubah data nilai siswa/siswi apakah data di dalam tabel nilai akan bertambah dan berubah? Ya, akan bertambah dan berubah. Selanjutnya, akan menampilkan baris berwarna kalau nilai tersebut kurang dari 75 dengan keterangannya.
<img src='![image](https://user-images.githubusercontent.com/108471020/177027921-f7f6e0d2-28f1-4aed-99c5-54f44f77b0c7.png)'></img>
- Apakah data akan tersimpan jika tidak mengisi semua field pada form tambah dan ubah data? Tidak, harus mengisi semua field agar dapat menyimpan ataupun mengubahnya.
<img src='![image](https://user-images.githubusercontent.com/108471020/177027899-ace8f7a0-a9ce-4fd7-a580-b545e71843ed.png)'></img>
- Apakah data akan terhapus jika kita mengklik button hapus pada setiap baris? Ya, akan terhapus jika kita mengklik button hapus pada setiap baris.
<img src='![image](https://user-images.githubusercontent.com/108471020/177027894-24448789-95aa-45aa-be55-511baa515378.png)'></img>
-	Apakah dapat login ke dalam program tersebut? Ya, dengan mengisi username dan password akan dapat melogin ke dalam program tersebut
<img src='![image](https://user-images.githubusercontent.com/108471020/177027636-97ce5d26-a95c-4983-a8dd-57808273e2cb.png)'></img>

8. Pengunaan komentar pada program
<img src='![image](https://user-images.githubusercontent.com/108471020/177027624-4cb81e37-069e-4c0d-b04a-7f01f122f7d5.png)'></img>
Ini adalah komentar dari semua baris yang ada di dalam program saya. Hal ini digunakan untuk membuat tulisan tanpa terdeteksi oleh Bahasa pemrograman bahwa itu kode program. Cara kerjanya ketika menekan ctrl + shift + / atau ctrl + / pada saat kode program diblok maka akan membentuk sebuah komentar di dalam kode program. Jadi, otomatis tidak akan di deteksi oleh Bahasa pemrograman bahwa itu adalah tulisan biasa bukan kode program.

9. Penggunaan procedure dan function
<img src='![image](https://user-images.githubusercontent.com/108471020/177027613-5d8dcd90-e0be-4b5b-abf4-c4d838d57fc2.png)'></img>
<img src='![image](https://user-images.githubusercontent.com/108471020/177027615-021c0e93-4f6f-4306-8b66-434888e299bb.png)'></img>
Ini adalah semua procedure dan function yang terdapat pada program saya. Guna dari procedure dan function ini adalah untuk memberikan fungsi CRUD pada program saya. Cara kerjanya dengan menambahkan <?php defined('BASEPATH') OR exit('No direct script access allowed'); /?> diantara awalan dan akhir procedure pada PHP boleh anda tambahkan function yang sesuai anda inginkan.

10. Cara Kerja Algoritma
<img src='![image](https://user-images.githubusercontent.com/108471020/177028313-df78e6c0-84e1-400c-9731-6f6eae1d444d.png)'></img>
Ini merupakan cara kerja algoritma dengan menggunakan flowchart untuk login dan melakukan CRUD pada program tersebut.
