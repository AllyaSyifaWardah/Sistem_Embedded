<h1 align="center">LAPORAN PRAKTIKUM EMBEDDED SYSTEM</h1>
<p align="center">
  <img src="https://en.polines.ac.id/images/logo_bw.jpg" width="200" height="200">
<br>
<br>ALLYA SYIFA WARDAH
<br>TE-3B
<br>4.31.21.1.05</p>
<b><p align="center">PROGRAM STUDI D4 TEKNIK TELEKOMUNIKASI</p>
<p style="font-family:courier;" align="center">POLITEKNIK NEGERI SEMARANG</p>
<p style="font-family:courier;" align="center">2023</p></b>

  

# Setting SSID dan Password WI-Fi
# 1.	Alat dan Bahan
      •	Node red
      •	ESP32
      •	XAMPP
      
# 2. Flowchart
![image](https://github.com/AllyaSyifaWardah/Sistem_Embedded/assets/155618590/98367bf4-39e7-413e-bfb8-6510251a3a15)

# 3.Hasil dan Pembahasan
Jika gagal terhubung
![alt text](https://github.com/rayabima/Embedded-System/blob/main/Media/3.%20serial%20monitor%20setelah%20memasukan%20ssid%20dan%20pass.jpeg?raw=true)

## Jika berhasil terhubung
![alt text](https://github.com/rayabima/Embedded-System/blob/main/Media/4.%20Serial%20Monitor%20Setelah%20Berhasil%20Terhubung.jpeg?raw=true)
  EPS32 akan menampilkan daftar SSID Wi-Fi yang tersedia pada serial monitor. 
  Program mencoba terhubung ke jaringan WiFi yang telah disimpan dalam EEPROM (non-volatile memory). 
  Jika koneksi WiFi gagal atau tombol fisik pada pin D15 (GPIO15) ditekan, program akan memulai 
  konfigurasi sebagai titik akses (Access Point) untuk mengonfigurasi ulang WiFi. 
  Output dari percobaan ini yaitu wifikampus succeessfully.



      