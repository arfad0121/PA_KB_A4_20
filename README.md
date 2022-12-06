# TEMA : PENDETEKSI MASKER
# KELOMPOK 4 A1 2020
1. Ega Sulfika 2009106009
2. Muhammad Akmal Rifad 2009106010
3. Yanuar Gideon Simalango 20091014


# Table of Contents
- [Jobs Desk] (#jobs-desk--)
- [Mengklasifikasi Jumlah Angka Pada Jari Tangan Kanan dan Kiri](#mengklasifikasi-jumlah-angka-pada-jari-tangan-kanan-dan-kiri)
- [Dataset](#dataset)
- [Labels](#labels)
- [Tahap - Tahap Pengerjaan] (#tahap---tahap-pengerjaan-)
  - [Data Collecting](#1-data-collecting)
  - [Data Preprocessing - Data Augmentasi](#2-data-preprocessing---data-augmentasi)
  - [Data Modelling](#3-data-modelling)
  - [Prediksi Gambar Menggunakan Model](#4-prediksi-gambar-menggunakan-model)

<h2>Jobs Desk : </h2>
<ul>
</ul>

# Pendeteksi Masker
Saat pandemi covid-19 masih banyak masyarakat yang tidak menggunakan masker di tempat publik.
Oleh karena itu, tujuan program ini untuk membantu instansi - instansi atau pelayanan publik yang masih melakukan WFO atau berintraksi langsung oleh masyarakat banyak agar mudah untuk mengingatkan masyarakat agar menggunakan masker dengan baik dikala pandemi masih terjadi


# Tentang Dataset
 Dalam Dataset yang digunakan cuman ada dua yaitu with masker dan without masker, dimana masing-masing kelas itu terbagi menjadi train, test dan validasi. Pembagian yang dilakukan juga secara manual karena sekaligus memilah-milah data yang sekiranya menimbulkan akurasi yang rendah. total dataset ada 2000 data yang terbagi 3 yaitu train 1400 data, validasi 400 data, dan test 200 data

# Collecting Data
Data pelatihan kami didasarkan pada kumpulan data dari kaggle. Kumpulan data ini menyediakan kumpulan wajah yang ditangkap di alam liar dengan berbagai etnis, usia, dan emosi. Kami menggunakan 2000 gambar dari kumpulan data ini. Data ini akan digunakan untuk melatih classifier mask/no_mask. Dengan ukurang gambar asli yaitu 128x128.
Data tran, validasi dan testing kami terdiri dari gambar orang dengan dan tanpa masker yang kami kumpulkan dari sumber kaggle. Kami telah melakukan split data secara manual. Gambar dibagi atau di split 70/20/10 atas set train, set validasi dan set testing.

# 
