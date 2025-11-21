# OMR for Placement Test in LIA Hertasning
> _Repository_ ini **milik pribadi** dan dibuat untuk **kepentingan pribadi** pihak pertama selama di Lembaga Bahasa LIA Hertasning. Redistribusi atau penyebaran publik atas program ini tidak diperbolehkan tanpa izin eksplisit dari pihak pertama. Lihat file LICENSE untuk detail lebih lanjut!

<br>

![BENAR SALAH](https://github.com/bitacode/images/blob/main/BENAR_SALAH.png)
![SALAH SALAH](https://github.com/bitacode/images/blob/main/SALAH_SALAH.png)

## Mengenai File
### 1. Jenis-Jenis File
File-file yang dibutuhkan yaitu `kode program OMR` dengan ekstensi .ipynb, `kode fungsi untuk OMR` dengan ekstensi .ipynb template rapor hasil tes dalam `google spreadsheet` dan `pindaian lembar placement test` (PT) dengan ekstensi .png. Pastikan pindaian lembar PT sesuai dengan gambar panduan di atas. Disarankan untuk <ins>**menggunakan mesin scanner**</ins> dan bukan menggunakan aplikasi scan.

### 2. Direktori File
Unggah semua file yang ke dalam Google Drive pada `My Drive` dan <ins>tidak di dalam folder apapun</ins>.
<br>
<br>
![mydrive](https://github.com/bitacode/images/blob/main/mydrive.png)

## Cara Penggunaan
### 1. Sebelum Pengolahan Gambar
Pastikan lembaran PT tidak kotor/bernoda. Rapihkan hasil bulatan peserta agar <ins>sesuai aturan dan instruksi dalam booklet PT</ins> .
<br>
<br>
<img src="https://github.com/bitacode/images/blob/main/bulat.png" width="20%"/>

### 2. Pengolahan Gambar
![Static Badge](https://img.shields.io/badge/recommend-green?style=for-the-badge)
<br>
Buka file OMR.ipynb pada Google Drive lalu tekan kombinasi keyboard `shift+enter` pada tiap baris dan tunggu proses _running_ hingga selesai. 
<br>
<br>
<img src="https://github.com/bitacode/images/blob/main/Running.png" width="20%"/>

 ![Static Badge](https://img.shields.io/badge/not_recommend-red?style=for-the-badge)
 <br>
Proses _running_ juga bisa dilakukan melalui menu Runtime ➜ Run all.
<br>
<br>
<img src="https://github.com/bitacode/images/blob/main/runall.png" width="50%"/>

Bila muncul kotak pemberitahuan seperti ini, klik **Connect to Google Drive** untuk menyambungkan Google Colab dengan Google Drive, setelah itu lanjut dengan mengklik **Continue**.
<br>
<br>
<img src="https://github.com/bitacode/images/blob/main/connect.png" width="50%"/>

Bila muncul kotak pemberitahuan seperti ini, klik **Allow** untuk mengautentikasi Google Colab dengan Google Drive-mu.
<br>
<br>
<img src="https://github.com/bitacode/images/blob/main/allow.png" width="50%"/>

Sebelum melanjutkan pastikan untuk mencentang **Select all** seperti gambar di bawah, bila sudah langsung lanjutkan dengan mengklik **Continue**.
<br>
<br>
<img src="https://github.com/bitacode/images/blob/main/selectall.png" width="40%"/>

 ![Static Badge](https://img.shields.io/badge/important-yellow?style=for-the-badge)
 <br>
 Ada 2 jenis kunci jawaban pada bagian `GRADING`. Perhatikan program yg dipilih oleh peserta PT dan **sesuaikan variabel-variabel kunci jawaban sebelum melanjutkan proses _running_**. 

### 3. Setelah Pengolahan Gambar
Hasil pengolahan gambar akan tomatis terunduh dengan nama file `Test Report [NAMA].pdf`, silahkan cari dalam folder Downloads.
<br>

## PENTING!
Periksa ulang informasi peserta (Program, Booklet Number, Date, dll) dalam file google spreadsheet! Ketidakcocokan informasi dapat terjadi karena adanya kecacatan produksi atau noda tak kasat mata pada lembaran PT. Bila ada ketidakcocokan, silahkan edit manual informasi peserta dalam file google spreadsheet `Placement Test Report` lalu <ins>**run ulang**</ins> (shift+enter) <ins>**baris paling terakhir dari program OMR.ipynb**</ins>.

