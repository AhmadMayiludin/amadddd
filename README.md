<<<<<<< HEAD
# 🚀 Panduan Instalasi XAMPP, Composer, dan Laravel (Windows)
=======
# 🚀 Panduan Instalasi XAMPP, Composer, dan Laravel 11 (Windows)
>>>>>>> 4612482d17f12f1ce4f7f792ad38ffe398ad4afa

Dokumen ini menjelaskan langkah-langkah untuk menginstal XAMPP, Composer, dan Laravel 11 pada sistem operasi **Windows**, lengkap dengan gambar pendukung. Seluruh gambar disimpan di dalam folder [`images/`](./images/) dalam struktur repository GitHub.

---

<<<<<<< HEAD


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


  ![Laravel Version](./images/Versionframework.png)





5.	Jalankan Laravel




  ![Laravel Running](./images/phpartisanserve.png)


6.	Ketik Project-Ahmad.test di google apakah sudah aktif
  ![Laragon](./images/endlaravel.png)
Laravel sudah aktif dan siap dipakai.
=======
## 1. 🔧 Instalasi LARAGON

### Langkah-langkah:

1. Unduh XAMPP dari situs resmi:  
   ➡️ https://www.apachefriends.org/download.html

2. Jalankan installer dan ikuti proses instalasi hingga selesai.

3. Buka **XAMPP Control Panel** dan aktifkan:
   - **Apache**
   - **MySQL**

4. Tampilan XAMPP Control Panel:

   ![XAMPP Control Panel](./images/xampp-control-panel.png)

5. Buka browser dan akses:

   ```
   http://localhost/dashboard/
   ```

   Jika muncul tampilan seperti gambar di bawah, berarti Apache berhasil dijalankan:

   ![XAMPP Localhost](./images/xampp-localhost.png)

---

## 2. 💡 Instalasi Composer

### Langkah-langkah:

1. Unduh Composer dari:  
   ➡️ https://getcomposer.org/download/

2. Jalankan installer dan arahkan ke `php.exe` milik XAMPP (contoh: `C:\xampp\php\php.exe`).

   ![Composer Setup](./images/composer-setup.png)

3. Verifikasi instalasi melalui Command Prompt:

   ```bash
   composer -V
   ```

   ![Composer CMD](./images/composer-version.png)

---

## 3. ⚙️ Instalasi Laravel 11

### Langkah-langkah:

1. Buka terminal (CMD, PowerShell, atau Git Bash).

2. Jalankan perintah untuk membuat proyek Laravel 11:

   ```bash
   composer create-project laravel/laravel:^11.0 nama-proyek
   ```

   Contoh:

   ```bash
   composer create-project laravel/laravel:^11.0 laravel-app
   ```

   ![Install Laravel](./images/install-laravel11.png)

3. Masuk ke folder proyek:

   ```bash
   cd laravel-app
   ```

4. Jalankan server Laravel:

   ```bash
   php artisan serve
   ```

5. Akses Laravel di browser:

   ```
   http://127.0.0.1:8000
   ```

   ![Laravel 11 Welcome](./images/laravel11-welcome.png)

---

## 4. ⚠️ Konfigurasi Database

1. Buka `http://localhost/phpmyadmin` untuk membuat database baru.
2. Buka file `.env` di folder Laravel dan sesuaikan:

   ```dotenv
   DB_CONNECTION=mysql
   DB_HOST=127.0.0.1
   DB_PORT=8111
   DB_DATABASE=laravel-app
   DB_USERNAME=root
   DB_PASSWORD=
   ```

   ![Env File Setup](./images/env-setup.png)

---

## 📚 Referensi

- Laravel 11 Docs: https://laravel.com/docs/11.x
- Composer: https://getcomposer.org
- XAMPP: https://www.apachefriends.org

---

📅 **Selesai!**
>>>>>>> 4612482d17f12f1ce4f7f792ad38ffe398ad4afa

