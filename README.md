# Modul 2 - Pemrograman GPIO

Nama: Reva Aura Ramadhani  
NIM: H1H024059  

## Deskripsi
Praktikum ini bertujuan untuk memahami penggunaan GPIO (General Purpose Input/Output) pada Arduino Uno. GPIO digunakan untuk mengontrol perangkat output seperti seven segment dan membaca input dari push button.

## Percobaan
### 1. Seven Segment (Output)
Pada percobaan ini, seven segment digunakan untuk menampilkan angka dan karakter heksadesimal (0–9 dan A–F) secara berurutan menggunakan Arduino.

### 2. Counter dengan Push Button (Input)
Pada percobaan ini, push button digunakan sebagai input untuk mengontrol perubahan nilai counter yang ditampilkan pada seven segment.

## Penjelasan Program
Program menggunakan array `digitPattern` untuk menyimpan pola nyala LED pada setiap segmen seven segment. Setiap angka dan karakter memiliki kombinasi logika HIGH dan LOW yang berbeda.

Fungsi `displayDigit()` digunakan untuk menampilkan angka berdasarkan pola yang telah ditentukan.

Pada fungsi `loop()`, program menampilkan angka dari 0 hingga F secara berulang dengan delay 1 detik.

## Komponen yang Digunakan
- Arduino Uno
- Seven Segment
- Resistor 220 Ohm
- Breadboard
- Kabel Jumper
- Push Button

## Cara Kerja
1. Arduino mengirimkan sinyal digital ke setiap pin seven segment.
2. Kombinasi sinyal tersebut menentukan segmen mana yang menyala.
3. Seven segment menampilkan angka atau karakter sesuai pola.
4. Pada percobaan kedua, push button digunakan untuk mengubah nilai counter.

## Struktur Folder
