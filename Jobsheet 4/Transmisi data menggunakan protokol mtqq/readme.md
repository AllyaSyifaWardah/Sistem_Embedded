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

# Transmisi Data Menggunakan Protokol MQTT
<p align="justify">Dalam percobaan ini, program ESP32 memanfaatkan protokol MQTT untuk mentransmisikan data dummy, seperti level, rainfall, dan flow. Server broker MQTT yang digunakan adalah layanan EMQ X, yang merupakan platform perangkat lunak open-source untuk implementasi MQTT. Setelah program diupload, dilakukan pemantauan melalui serial monitor untuk memastikan koneksi dan debug pada Node-Red. Hasil output dari percobaan ini meliputi data yang dipublikasikan ke topik "flood/node1", serta visualisasi data pada dashboard Node-Red.

# 1. Alat dan Bahan
    1. Node-RED
    2. ESP32
    3. XAMPP
    
# 2. Source Kode
![alt text]![image (https://github.com/AllyaSyifaWardah/Sistem_Embedded/assets/155618590/a27ae1d1-0672-4780-b49f-feffdc7bb00a)

# 3. Flowchart
![image](https://github.com/AllyaSyifaWardah/Sistem_Embedded/assets/155618590/49643d14-22d2-4dd5-b5eb-e3c8bf8f859f)


# 4. Hasil dan Pembahasan
## Praktikum 4C.1
![job4c 1](https://github.com/AllyaSyifaWardah/Sistem_Embedded/assets/155618590/422cb772-4d60-4f3a-a83f-52f08f42d6de)

## Praktikum 4C.2
![job4c 2](https://github.com/AllyaSyifaWardah/Sistem_Embedded/assets/155618590/df970750-64d7-41cf-afc9-4868b710f3b0)

## Praktikum 4C.3
![job4c 3](https://github.com/AllyaSyifaWardah/Sistem_Embedded/assets/155618590/53d70e4d-dfd4-4934-b226-2995b0848874)

## Praktikum 4C.4
![job4c 4](https://github.com/AllyaSyifaWardah/Sistem_Embedded/assets/155618590/10b84ee0-43b9-46ee-9ba9-9f48781ee5c5)

Berdasarkan hasil percobaan yang telah didapatkan di ketahui bahwa untuk melakukan percobaan perlu diketahui IP  dari komputer atau laptop yang digunakan.
Pada MQTT yang berfungsi sebagai pengirim adalah Publish sedangkan subscribe untuk menerima pesan. Pada MQTT broker berfungsi sebagai penghubung antara publisher dan subscriber yaitu pesan yang melewati broker akan dikirim dan dikategorikan sesuai topik. Pada percobaan diatas ada 3 publisher yang disetting QoS masing - masing publishernya, dan kemudian hasilnya akan sesuai dengan yang diinginkan


