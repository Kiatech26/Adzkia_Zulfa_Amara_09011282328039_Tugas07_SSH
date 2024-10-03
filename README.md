# Adzkia_Zulfa_Amara_09011282328039_Tugas07_SSH
# 1. Masuk Ke Seting dan pilih Network. 
# Lalu PIlih NAT, Klik Advance, pilih port Forwading untuk mengatur Host.

<img width="600" alt="Perintah1benar" src="https://github.com/user-attachments/assets/d1ea628a-2a0f-422c-b5e9-2f3b8db38d89">

##  NAT (Network Address Translation) adalah sebuah metode yang digunakan untuk mengubah alamat IP di header paket data saat melewati router atau perangkat jaringan lainnya. 
##  NAT memungkinkan beberapa perangkat dalam jaringan lokal (LAN) dengan alamat IP pribadi untuk berkomunikasi dengan jaringan publik,
##  seperti internet, menggunakan satu alamat IP publik.

# 2. Tambah port Forwading Atur Host Port dan guest port.

<img width="318" alt="perintah2 benar" src="https://github.com/user-attachments/assets/77067fe0-6a72-4aab-a07e-94756f2cf587">

##  Host Port 2222: Ini adalah port pada komputer host (mesin utama) yang akan kamu gunakan untuk mengakses layanan di guest (mesin virtual/container). 
##  Dengan kata lain, ketika kamu mengakses localhost atau IP host menggunakan port 2222, komputer host akan meneruskan permintaan tersebut ke guest.

##  Guest Port 22: Ini adalah port di mesin virtual/container di mana layanan yang dituju (misalnya SSH) berjalan. 
##  Port 22 adalah port default untuk SSH di mesin guest.


# 3. Masuk ke Network Setting atur Enterhet 2 Virtual box.
<img width="601" alt="perintah3benar" src="https://github.com/user-attachments/assets/c27b3699-29a0-408b-98b1-5a961f6bf7de">

<img width="301" alt="perintah4a" src="https://github.com/user-attachments/assets/5a322389-3217-466d-bdc3-8ceb71a396ca">

##  klik kanan pilih properties atur IP addres dan gate away 
##  atur internet protocol version 4 (TCP/IPv4)
##  Misalkan menjalankan server web di mesin virtual dengan alamat 192.168.56.2 dan
##  ingin mengaksesnya dari host Mesin virtual akan mengirimkan permintaan ke 192.168.56.1 (default gateway) untuk menghubungi host, 
##  dan host akan meneruskan permintaan tersebut ke mesin virtual.

# 4. Jalankan Linuxnya, sebelum itu check terlebih dahulu koneksi dari windows ke linux.
##  lihat Ip Addres dengan ipconfig, atau dengan IP yang telah dibuat
 <img width="736" alt="langkah 4 benar juga dengan NAT" src="https://github.com/user-attachments/assets/b163c96e-3f5b-4f0d-9834-57d3558a887b">

##  cek koneksinya  

# 5. jalankan langkah 1 Upgraded
<img width="411" alt="Perintah 1 Update" src="https://github.com/user-attachments/assets/ab1c53fa-2697-4e13-9e04-69eea2fd30fa">

# 6. Install SSH
<img width="355" alt="langkah 2 hostman" src="https://github.com/user-attachments/assets/d2d5216c-74d4-4c33-8168-70a2637c867d">

# 7. Start SSH 
##  mengaktifkan layanan

<img width="390" alt="langkah 3a di hostman" src="https://github.com/user-attachments/assets/1b2960ae-552c-402a-9d09-786cfb9053f9">

## Kunci tersebut --nowmembantu Anda meluncurkan layanan dan sekaligus mengaturnya untuk memulai saat sistem di-boot.

## Untuk memverifikasi bahwa layanan diaktifkan dan berjalan dengan sukses,
<img width="393" alt="langkah 3b benar hostman" src="https://github.com/user-attachments/assets/cd929cb7-8395-4c7e-9caf-5689cbae0198">


## Jika Anda ingin menonaktifkan layanan
<img width="376" alt="langkah 3c hostman" src="https://github.com/user-attachments/assets/a6b6edff-6a21-47df-8950-8b74d0abcad9">


# Jika kita Menggunakan NAT Maka langkah sudah selesai setelah kita mengaktifkan layanan, mengaktifkannya di cmd windows dengan ssh -p 2222 usename@ip Adress
# Disini Menggunakan ssh -p 2222 adzkia@192.168.56.2, maka komputermu telah tersambungn dengan Windows
<img width="736" alt="langkah 4 benar juga dengan NAT" src="https://github.com/user-attachments/assets/b2cdcef6-229e-47bf-a437-fbc9862c90a4">


# 8. Konfigurasikan firewall
## Sebelum menghubungkan ke server melalui SSH, periksa firewall untuk memastikannya dikonfigurasi dengan benar

<img width="290" alt="langkah 4a hostman" src="https://github.com/user-attachments/assets/c97bacb3-2850-4009-b3bd-f1d55bd7b0a9">

## mengizinkan koneksi SSH yang masuk.

<img width="310" alt="langkah 4b" src="https://github.com/user-attachments/assets/6958cc24-3b1c-4ace-892d-abdc7bd0a90f">


# 9. Hubungkan ke server
## Untuk melakukan ini, Anda memerlukan alamat IP atau nama domain server dan nama pengguna yang dibuat di server.

Note : Langkah Tersebut sama bisa terhubung dan menggunakan bride
