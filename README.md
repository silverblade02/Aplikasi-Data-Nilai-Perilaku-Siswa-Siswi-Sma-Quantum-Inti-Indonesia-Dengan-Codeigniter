<h3 style="text-align:center">TUGAS LSP PEMROGRAM (NILAI PERILAKU SISWA/SISWI SMA QUANTUM INTI INDONESIA DENGAN CODEIGNITER)</h3>
<h3 style="text-align:center">ARI ROYANI BIYA</h3>
<h3 style="text-align:center">51418045</h3>
<h3 style="text-align:center">4IA13</h3>

Aplikasi ini mempunyai fitur CRUD (Create Read Update Delete) dan menggunakan database "murid" yang berada di dalam repository tersebut. Terdapat dua buah tabel yang digunakan pada aplikasi ini, yaitu tabel tbl_user dan tbl_nilai. Semua tabel yang disebutkan akan dijelaskan apa saja field serta tipe datanya pada README ini dan saya menggunakan framework CODEIGNITER untuk membuat aplikasi tersebut. 

1. Unit-Unit Reuse yang digunakan :
-	Ini merupakan reuse kodingan tambah yang mana kemudian akan digunakan kembali pada model update :
![1](https://user-images.githubusercontent.com/108471020/177028624-e5a93da8-4377-4add-8d07-d216e3cdd1f7.png)
![2](https://user-images.githubusercontent.com/108471020/177028564-264c4a2b-7150-4031-b206-ac62d01a2926.png)

- Hal ini juga ada dapat kodingan index :

![image](https://user-images.githubusercontent.com/108471020/177028807-9d06627e-ea18-482f-864f-4f6666055160.png)
![image](https://user-images.githubusercontent.com/108471020/177028797-e85097b9-3534-4cc9-bba5-7167288042b9.png)

-	Dan juga berlangsung pada form edit dan tambah :

![5](https://user-images.githubusercontent.com/108471020/177028543-a5d3dfe2-4f09-453d-9a7f-c6510c9f0a70.png)
![6](https://user-images.githubusercontent.com/108471020/177028546-e249cab9-edf8-4044-8630-3ed9f8c9b3ab.png)

2. Tampilan program per halaman :
- Home
![image](https://user-images.githubusercontent.com/108471020/177030083-7f16bedc-55be-4cb5-adfb-d800308416fd.png)

- Login
![image](https://user-images.githubusercontent.com/108471020/177030086-1a3c14b0-11b4-46aa-8e2a-5b00e3ec078e.png)

- Tambah Data
![image](https://user-images.githubusercontent.com/108471020/177030087-b41151b7-820c-4688-943c-bdd8db3d8562.png)

- Edit Data
![image](https://user-images.githubusercontent.com/108471020/177030096-e1ca7f96-a4ba-475d-b85f-1d2d02744bb0.png)

3. Koneksi Database
Di dalam file database.php saya mengkoneksi database dengan nama "murid" dengan username root tanpa password

![7](https://user-images.githubusercontent.com/108471020/177028539-622d294a-6b8d-46cb-a36a-959e68c02ffd.png)

4. Tabel-tabel yang digunakan

tbl_nilai

![8](https://user-images.githubusercontent.com/108471020/177028534-465c2ce9-ac14-4c22-83e6-e7677d71f36a.png)

tbl_user

![9](https://user-images.githubusercontent.com/108471020/177028533-53b12131-0584-4e01-bb39-67c4c3449bcd.png)

5. Operasi untuk mengakses database
Operasi pengaksesan database ada pada config.php yang digunakan untuk untuk mengisi libraries dengan database yang sudah kita buat

![10](https://user-images.githubusercontent.com/108471020/177028531-ab88ce35-6f09-43e6-bc0f-c3fb7455d79e.png)

7. Skenario pengujian database
- Jika menambahkan atau mengubah data nilai siswa/siswi apakah data di dalam tabel nilai akan bertambah dan berubah? Ya, akan bertambah dan berubah. Selanjutnya, akan menampilkan baris berwarna kalau nilai tersebut kurang dari 75 dengan keterangannya.
![11](https://user-images.githubusercontent.com/108471020/177028527-57a91ad5-ffe9-4bdc-bc9a-530932bab4cd.png)

- Apakah data akan tersimpan jika tidak mengisi semua field pada form tambah dan ubah data? Tidak, harus mengisi semua field agar dapat menyimpan ataupun mengubahnya.

![12](https://user-images.githubusercontent.com/108471020/177028512-44b9d26b-2da8-4eef-ad8d-5645d81b0070.png)

- Apakah data akan terhapus jika kita mengklik button hapus pada setiap baris? Ya, akan terhapus jika kita mengklik button hapus pada setiap baris.

![image](https://user-images.githubusercontent.com/108471020/177030038-b3069533-95ef-49d4-9cf6-d47469f3d275.png)

-	Apakah dapat login ke dalam program tersebut? Ya, dengan mengisi username dan password akan dapat melogin ke dalam program tersebut

![14](https://user-images.githubusercontent.com/108471020/177028501-48be6165-24ff-46e0-9a44-60058dfb5cca.png)


8. Pengunaan komentar pada program
Ini adalah komentar dari semua baris yang ada di dalam program saya. Hal ini digunakan untuk membuat tulisan tanpa terdeteksi oleh Bahasa pemrograman bahwa itu kode program. Cara kerjanya ketika menekan ctrl + shift + / atau ctrl + / pada saat kode program diblok maka akan membentuk sebuah komentar di dalam kode program. Jadi, otomatis tidak akan di deteksi oleh Bahasa pemrograman bahwa itu adalah tulisan biasa bukan kode program.
![15](https://user-images.githubusercontent.com/108471020/177028498-6e9d7f90-9b97-4de8-b26a-b08fd29fdb73.png)


9. Penggunaan procedure dan function
Ini adalah semua procedure dan function yang terdapat pada program saya. Guna dari procedure dan function ini adalah untuk memberikan fungsi CRUD pada program saya. Cara kerjanya dengan menambahkan <?php defined('BASEPATH') OR exit('No direct script access allowed'); /?> diantara awalan dan akhir procedure pada PHP boleh anda tambahkan function yang sesuai anda inginkan.
![16](https://user-images.githubusercontent.com/108471020/177028488-2a734d23-e70e-4c8b-aba9-6f2b8656ff15.png)
![17](https://user-images.githubusercontent.com/108471020/177028489-9a8feed9-5d80-4db4-9864-896e44871f0b.png)

10. Cara Kerja Algoritma
Ini merupakan cara kerja algoritma dengan menggunakan flowchart untuk login dan melakukan CRUD pada program tersebut.

![Flowchart Program](https://user-images.githubusercontent.com/108471020/177028456-e9224454-8f7f-425c-bf7e-25b5418fa79c.jpg)
