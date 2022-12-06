# TEMA : PENDETEKSI MASKER
<h2>NAMA KELOMPOK</h2>
<ol> 1. Muhammad Akmal Rifad 2009106010</ol>
<ol> 2. Ega Sulfika 2009106011</ol>
<ol> 3. Yanuar Gideon Simalango 2009106014</ol>


# Table of Contents
- [Nama Kelompok](#nama-kelompok)
- [Jobs Desk](#jobs-desk--)
- [Pendeteksi Masker](#pendeteksi-masker)
- [Dataset](#dataset)
- [Tahapan Pengerjaan](#tahapan-pengerjaan-)
  - [Data Collecting](#1-data-collecting)
  - [Data Preprocessing](#2-data-preprocessing)
  - [Data Analisis dan Visualisasi](#3-data-analisis-dan-visualisasi-)
  - [Data Modelling](#4-data-modelling)
  - [Evaluasi](#5-evaluasi-)

<h2>Jobs Desk : </h2>
<ul>
  <li>Muhammad Akmal Rifad : Ketua Kelompok, Data Analysis and Visualization, Data Modelling</li>
  <li>Ega Sulfika: Data Collecting, Data Preprocessing</li>
	<li>Yanuar Gideon Simalango : Evaluasi</li>
</ul>

<h2>Pendeteksi Masker</h2>
<p>Saat pandemi covid-19 masih banyak masyarakat yang tidak menggunakan masker di tempat publik. Oleh karena itu, tujuan program ini untuk membantu instansi - instansi atau pelayanan publik yang masih melakukan WFO atau berintraksi langsung oleh masyarakat banyak agar mudah untuk mengingatkan masyarakat agar menggunakan masker dengan baik dikala pandemi masih terjadi </p>


<h2>Dataset</h2>
<p>Dalam Dataset yang digunakan cuman ada dua yaitu with masker dan without masker, dimana masing-masing kelas itu terbagi menjadi train, test dan validasi. Pembagian yang dilakukan juga secara manual karena sekaligus memilah-milah data yang sekiranya menimbulkan akurasi yang rendah. Dataset sebelumnya terdapat tiga class, yaitu mask_weared_incorrect. Dan dari hasil analisi kami, jadi hanya menggunaan dua class saja.

Kaggle Dataset URL: https://www.kaggle.com/datasets/vijaykumar1799/face-mask-detection</p>

<br>
	<p>Setiap folder berisi 2994 gambar orang yang termasuk dalam kelas berlabel tersebut..</p>
  <p> Deskripsi Class 1
	<ul>
		<li>Nama folder: with_mask.</li>
		<li>Gambar yang ada di dalam folder: 2994 gambar.</li>
		<li>Dimensi gambar: 128 x 128</li>
    <li>Jenis file gambar: .png</li>
    <li>Deskripsi: Folder ini berisi contoh gambar orang yang memakai masker dengan benar.</li>
	</ul>
  </p>
  
  <p> Deskripsi Class 2
	<ul>
		<li>Nama folder: without_mask.</li>
		<li>Gambar yang ada di dalam folder: 2994 gambar.</li>
		<li>Dimensi gambar: 128 x 128</li>
    <li>Jenis file gambar: .png</li>
    <li>Deskripsi: Folder ini berisi contoh gambar orang yang tidak memakai masker dengan benar.</li>
	</ul>
  </p>

<h2>Tahapan Pengerjaan :</h2>

### 1. Data Collecting
<li>Data pelatihan kami didasarkan pada kumpulan data dari kaggle. Kumpulan data ini menyediakan kumpulan wajah yang ditangkap di alam liar dengan berbagai etnis, usia, dan emosi. Kami menggunakan 2000 gambar dari kumpulan data ini. Data ini akan digunakan untuk melatih classifier mask/no_mask. Dengan ukurang gambar asli yaitu 128x128. Data tran, validasi dan testing kami terdiri dari gambar orang dengan dan tanpa masker yang kami kumpulkan dari sumber kaggle. Kami telah melakukan split data secara manual. Gambar dibagi atau di split dengan Train : Val : Test = 70% : 20% : 10% .</li>

### 2. Data Preprocessing
<li>Melakukan Data Gambar Augmentasi dan Load Data</li>

### 3. Data Analisis dan Visualization 
<li>Visualisasi Hasil Prediksi dengan menampilkan label aktual dan label prediksi dan visuluasasi jumlah data dari masing-masing class</li>

### 4. Data Modelling
<li>Membuat Model Sequential dan Visualisasi : Accuracy & Loss Model</li>
<li>Save Model</li>

### 5. Evaluasi 
<li>Melakukan dan menampilkan hasil evaluasi dari data testing</li>
<li>Melakukan predict</li>
<br>
