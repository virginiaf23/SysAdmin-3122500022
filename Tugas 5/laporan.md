<div align="center">
  <h1>Tugas 5 </h1>
 <h2>  Workshop Administrasi Jaringan</h2>
<strong>DEBIAN</strong>

<img src="Logo_PENS.png" alt="Alt teks">

<br><br>

<p>Oleh:</p>
<li>Virginia Faiqoh (3122500022 )</li>


<br>

<p>  Dosen Pembimbing     :  Dr. Ferry Astika Saputra ST, M.Sc</p>

<br>
PROGRAM STUDI D3 TEKNIK INFORMATIKA
POLITEKNIK ELEKTRONIKA NEGERI 
SURABAYA
2023 / 2024



</div>



<br><br><br><br><br><br>


<div>

  <h3>1. Konfigurasi NTP Client</h3>

  1. Instalasi paket <br>
  <img src="gbr1.png"> <br>

  2.  Konfigurasi timezone ke Asia/Jakarta (baris 1),  konfigurasi RTC untuk merefer ke UTC (baris 2), Mengaktifkan NTP Client untuk sinkronisasi waktu
  <br>
  <img src="gbr2.png"> <br>
  
  3. Menyunting file timesyncd.conf untuk mengarah ke NTP server terdekat untuk mendapatkan waktu delay terpendek. <br>
  <img src="gbr3.png">
  Ubah line 16 menjadi NTP=0.id.pool.ntp.org 
  <img src="gbr4.png"> <br>
  
  4. Restart layanan sinkronisasi waktu dan pastikan layanan berjalan dengan benar <br>
  <img src="gbr5.png"> <br><br>
 
  5. Mengecekan kesesuaian tanggal system dengan perintah <br>
  <img src="gbr6.png"><br><br>

  <h3>2. Konfigurasi Web Server Apache 2</h3>

  1. Instalasi paket apache2 <br>
  <img src="gbr7.png"> <br>

  2. Konfigurasi Apache2
  <img src="gbr8.png">
  <img src="gbr9.png">
  <img src="gbr10.png">
  <img src="gbr11.png">
  <img src="gbr12.png">
  <img src="gbr13.png">
  <img src="gbr14.png">
  <img src="gbr15.png"> <br>

  3. Restart dan cek status
  <img src="gbr16.png"> <br><br>

  3. Testing ke web browser <br>
  <img src="gbr17.png"> <br><br>
  
  <h3>3. Konfigurasi PHP</h3>

  1. Instalasi paket PHP 8.2 <br>
  <img src="gbr18.png"> 
  <img src="gbr19.png">
  <img src="gbr20.png"><br>

  2. Instalasi pakaet PHP-FM
  <img src="gbr21.png">

  3. Konfigurasi PHP-FM pada file konfigurasi Apache <br>
  <img src="gbr22.png"> 
  <img src="gbr23.png">
  <img src="gbr24.png"><br><br>
  
  5. Restart
  <img src="gbr25.png"><br><br>

  <h3>4. Konfigurasi Database Server MariaDB</h3>

  1. Instalasi MariaDB
  <img src="gbr26.png"> <br>

  2. Konfigurasi MariaDB 
  <img src="gbr27.png"> 
  <img src="gbr28.png"><br>
  
  3. Inisial Konfigurasi database MariaDB Server
   <img src="gbr29.png">  
   <img src="gbr30.png"> 
   <img src="gbr31.png"> 
   <img src="gbr32.png">
   <img src="gbr33.png">
   <img src="gbr34.png">
   <img src="gbr35.png"> <br>
   
  4. Testing database MariaDB Server
   <img src="gbr36.png"> 
   <img src="gbr37.png">
   <img src="gbr38.png">
   <img src="gbr39.png">
   <img src="gbr40.png"> <br><br>

  <h3>5. Konfigurasi PhpMyAdmin</h3>
  1. Instalasi phpmyadmin
   <img src="gbr41.png"> 
   <img src="gbr42.png">
   <img src="gbr43.png">
   <img src="gbr44.png"><br>

  2. Konfigurasi phpmyadmin pada Apache2 
   <img src="gbr45.png">
   <img src="gbr46.png"> <br>
  
  3. Restart
   <img src="gbr47.png">
    <br><br>  

  <h3>6. Konfigurasi Email Server POSTFIX : SMTP Server (TCP 25)</h3>

  1. Instalasi postfix
  <img src="gbr48.png">
  <img src="gbr49.png">
  <img src="gbr50.png"> <br>

  2. Copy file main.cf
  <img src="gbr51.png"> <br>

  3. Edit file main.cf 
  <img src="gbr52.png"> 
  <img src="gbr53.png">
  <img src="gbr54.png">
  <img src="gbr55.png">
  <img src="gbr56.png">
  <img src="gbr57.png">
  <img src="gbr58.png">
  <img src="gbr59.png">
  <img src="gbr60.png">
  <img src="gbr61.png">
  <img src="gbr62.png">
  <img src="gbr63.png">
  <img src="gbr64.png">
  <img src="gbr65.png"><br>

  4. Restart
  <img src="gbr66.png">
  <img src="gbr67.png"> <br>
  
  5. Menambahkan Konfigurasi Anti spam 
  <img src="gbr68.png"> 
  <img src="gbr69.png"><br><br>

  <h3>7. Konfigurasi DOVECOT : IMAP4 (TCP 143) dan POP3 (TCP 110) server </h3>

  1. Instalasi Dovecot server <br>
  <img src="gbr70.png"> <br>

  2. Konfigurasi Dovecot
  <img src="gbr71.png">
  <img src="gbr72.png">
  <img src="gbr73.png">
  <img src="gbr74.png">
  <img src="gbr75.png">
  <img src="gbr76.png">
  <img src="gbr77.png">
  <img src="gbr78.png">
  <img src="gbr79.png"> <br>

  3. Restart
  <img src="gbr80.png">
  
  4. Final check untuk semua service
  <img src="gbr81.png"> <br><br>

  <h3>8. Konfigurasi Roundcube </h3>

  1. Buat database, user, dan pemberian hak akses <br>
  <img src="gbr82.png"><br>

  2. Install Roundcube
  <img src="gbr83.png">
  <img src="gbr84.png"> <br>

  3. Konfigurasi Roundcube
  <li>Masuk ke direktori konfigurasi cd /usr/share/dbconfig-common/data/roundcube/install/
  <img src="gbr85.png">
  
  <li>import database mysql -u roundcube -D roundcube -p < mysql kemudian masukkan password yang telah dibuat sebelumnya
  <img src="gbr86.png">
  
  <li> Konfigurasi database sudo nano /etc/roundcube/debian-db.php
  <img src="gbr87.png">

  <li> Sesuaikan credential database dengan yang telah dibuat sebelumnya
  <img src="gbr88.png">
  <img src="gbr89.png">
  <img src="gbr90.png">
  <img src="gbr91.png">
  <img src="gbr92.png">
  <img src="gbr93.png"><br>

  <li> Konfigurasi webserver untuk roundcube
  <img src="gbr94.png">
  <img src="gbr95.png">
  
</p>
</div>