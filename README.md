
# 🚀 Panduan Instalasi Laragon, Composer, dan Laravel (Windows)
=======


Dokumen ini menjelaskan langkah-langkah untuk menginstal XAMPP, Composer, dan Laravel 11 pada sistem operasi **Windows**, lengkap dengan gambar pendukung. Seluruh gambar disimpan di dalam folder [`images/`](./images/) dalam struktur repository GitHub.

---




# Instalisasi Laragon

1.Buka website resmi laragon https://laragon.org 
 
 ![Website Laragon](./images/weblaragon.png)
Klik Dowloadad

# 2.Install PhpMyAdmin terlebih dahulu
 
![Install PhpMyAdmin](./images/phpmyadmin.png)




# 3.Jika Sudah terinstall aplikasi laragon,buka aplikasi laragon
![Website Laragon](./images/startlaragon.png)
 
Klik Start All untuk menjalankan apache dan MySql

# 4.Jika berhasil instalisasi laragon muncul seperti gambar dibawah ini
 ![Laragon](./images/stoplaragon.png)
Laragon berhasil di install dan siap di gunakan









# cara menambahkan path file PHP ke dalam Environment Variables di Windows
1.	Cari Folder PHP Dan Copy Path PHP
 ![PATH](./images/filepath.png)
2.	Buka Environment Variables
•  Tekan tombol Windows + S, ketik: environment variables
Klik Edit the system environment variables
•  Di jendela System Properties, klik: Environment Variables

3.	Edit Path
1)	Di bawah bagian System Variables (atau User jika kamu mau lokal):
•	Cari dan klik Path
•	Klik Edit...
2)	Klik New → Paste path PHP tadi
3)	Klik OK semua sampai keluar.

4.	Cek Lewat Terminal Apakah Sudah Terpasang File PHP Di Path
 ![PATH1](./images/startterminal.png)
Jika Muncul PHP 8.1.10 (cli) ...Berarti Sudah Terpasang Dan Berhasil

# Cara Instalisasi Laravel Di Terminal

1.	Buka Terminal di aplikasi Laragon
 ![Laragon](./images/larag.png)
2.	Install Laravel (dengan Composer)
Ketik composer create-project laravel/laravel Project-Ahmad di Terminal lalu hasilnya seperti di bawah ini
  ![Laravel](./images/installaravel.png)
Ini akan buat folder Proeject-Ahmad di C:\laragon\www







3.	Cek Ke Folder Apakah Sudah Muncul File nya
  ![Project](./images/fileproject.png)

4.	Cek Laravel apakah berhasil terinstall


  ![Laravel Version](./images/versionframework.png)





5.	Jalankan Laravel




  ![Laravel Running](./images/phpartisanserve.png)


6.	Ketik Project-Ahmad.test di google apakah sudah aktif
  ![Laragon](./images/endlaravel.png)
Laravel sudah aktif dan siap dipakai.
