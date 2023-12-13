# UAS-Cyber-17
A03 2022-Injection Serka Saa Nur Fadli

TUGAS UAS A3 2022 INJECTION (OWASP 10 JUICE SHOP)

Laporan.

SQL Injection (SQLi) merupakan jenis serangan injeksi yang memungkinkan untuk mengeksekusi statement SQL yang berbahaya. Statement yang digunakan ini dapat mengontrol server database di belakang aplikasi web.
Hacker dapat melakukan otentikasi dan otorisasi halaman web atau aplikasi web dan mengambil konten dari seluruh database SQL. Mereka juga dapat menggunakan SQL Injection untuk menambah, mengubah, dan menghapus catatan dalam database.
Serangan SQL Injection ini dapat menarget semua website yang memanfaatkan SQL database, seperti MySQL, PostgreSQL, SQL Server, dan lainnya.

A.  Download OWASP
Mengunduh rilis terbaru OWASP Juice Shop dari halaman resmi Github.
![image](https://github.com/Fadly117/UAS-Cyber-17/assets/149048105/d67e9481-6e4e-49bb-ae18-66aed3e0f5a5)

Kita perlu mengekstrak isinya karena kita mengunduh file dalam format zip.
![image](https://github.com/Fadly117/UAS-Cyber-17/assets/149048105/723507ec-f010-4975-b9c3-402ce004ea5a)

B.	Install NodeJS Dan NPM
Menyalin Alamat tautan untuk “NodeJS untuk sistem Linux x64” dan menggunakan syntax dibawah ini untuk mengunduh film disistem.
![image](https://github.com/Fadly117/UAS-Cyber-17/assets/149048105/45978a61-4fe3-4213-90cc-377df3454fc5)

Ekstrak file yang kita download menggunakan perintah tar.
![image](https://github.com/Fadly117/UAS-Cyber-17/assets/149048105/a0805be3-5df5-4670-836f-0d82487df092)

Menyalin file dari folder yang baru diekstrak ke directori /usr untuk menginstal nodeJS dan NPM disistem kita.
![image](https://github.com/Fadly117/UAS-Cyber-17/assets/149048105/a2875cd1-0f32-4c21-b61d-d1ac16816e65)

NodeJS dan NPM sudah diinstal kemudian untuk melihat versi dengan perintah sbb:
![image](https://github.com/Fadly117/UAS-Cyber-17/assets/149048105/fa9a1d3b-d514-49e9-b146-30c5e3d8ce0a)

C.	Install Ketergantungan Node
Kembali ke OWASP Juice Shope yang di ekstrak. Gunaka cd perintah untuk  mengubah directori ke folder tersebut dan jalankan perintah untuk menginstal paketNode yang diperlukan untuk menjalankan OWASP Juice Shop.
![image](https://github.com/Fadly117/UAS-Cyber-17/assets/149048105/51d794f2-d33c-48e3-91ac-f594db256248)

Jalankan perintah dibawah ini untuk menjalankan OWASP Juice Shop
![image](https://github.com/Fadly117/UAS-Cyber-17/assets/149048105/1de41a05-bb2d-4795-84a6-72b17e149d70)
Perintah ini akan memulai aplikasi web pada port 3000. Namun jika ada aplikasi lain yang berjalan pada port tersebut, anda akan melihat opsi untuk menggunakan port lain seperti 3001. Lucurkan brouser dengan URL http://localhost:3000/ untuk mengakses aplikasi web.

D.	Bender Login
Bender login adalah login menggunakan akun email alyufa@juice-sh.op menggunakan injection.
1.	Masuk kehalaman login dengan melakukan klik account pada bagian navbar lalu klik login
![image](https://github.com/Fadly117/UAS-Cyber-17/assets/149048105/7a91e23f-c3e3-4eff-a2a0-4fba8117d19d)

2.	Selanjutnya pada halaman login ini masukkan email alyufa@juice-sh.op dan dengan password diisi dengan inputan acak. Untuk melakukan injection tambahkan ' -- yang dimana maksud dari inputan tersebut adalah digunakan untuk menonaktifkan argumen query sql setelahnya atau melakukan comment jadi kita dapat menonaktifkan kondisi pengecekan passwordnya.
![image](https://github.com/Fadly117/UAS-Cyber-17/assets/149048105/4faa7ad1-85d3-4e8a-9d75-ca01da0f436a)

3.		Submit login form, maka kita akan berhasil masuk sebagai user bender.
![image](https://github.com/Fadly117/UAS-Cyber-17/assets/149048105/475460e8-b866-4e3d-a5f5-9a3d5db8127e)











