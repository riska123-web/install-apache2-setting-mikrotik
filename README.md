# install-apache2-setting-mikrotik
Perbarui indeks paket: Jalankan sudo apt update untuk memperbarui manajer paket. 
 
Instal Apache2: Jalankan Sudo apt install Apache2 untuk menginstal Apache2. Saat diminta untuk mengonfirmasi, ketik y dan tekan Enter. 
 
Sesuaikan pengaturan firewall: Jalankan sudo ufw izinkan 'Apache' untuk mengizinkan lalu lintas pada port 80. 
 
Periksa server web: Jalankan Sudo systemctl status Apache2 untuk memeriksa status Apache2. 
 
Anda juga dapat memulai layanan Apache dengan Sudo systemctl start Apache2. Untuk mengaktifkan Apache agar berjalan saat startup sistem, Anda dapat menggunakan perintah lain. 
 
Apache2 adalah rilis terbaru dari Apache HTTP Server, yang merupakan server web yang umum digunakan pada sistem Linux. Ini sering digunakan sebagai bagian dari konfigurasi LAMP.
 
