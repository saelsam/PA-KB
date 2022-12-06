<h1>Kelompok 2 A2 Kecerdasan Buatan</h1>
<ul>
  <li>2009106018 - Ahmad Zidan Maulidinnur</li>
	<li>2009106034 - Sael Samuel Rude'</li>
	<li>2009106041 - Shalsabyla Putrie Rahmadaniah</li>
</ul>

**Table of Contents**
- [Jobs Desk](#jobs-desk--)
- [Mengklasifikasi Jumlah 4 Jenis Pada Cuaca](#mengklasifikasi-jumlah-4-jenis-pada-cuaca)
- [Dataset](#dataset)
- [Labels](#labels)
- [Tahap - Tahap Pengerjaan](#tahap---tahap-pengerjaan-)
  - [Data Collecting](#1-data-collecting)
  - [Data Preprocessing - Data Augmentasi](#2-data-preprocessing---data-augmentasi)
  - [Data Analysis and Visualization](#3-Data-Analysis-and-Visualization)
  - [ Data Modelling](#4-Data-Modelling)
  - [Evaluasi](#5-evaluasi)

<h2>Jobs Desk : </h2>
<ul>
	<li>Sael Samuel Rude' : Ketua Kelompok, Data Collecting, Data Visualisasi</li>
  <li>Shalsabyla Putrie Rahmadaniah : Data Augmentasi (Preprocessing)</li>
	<li>Ahmad Zidan Maulidinnur : Data Modelling</li>
</ul>

<h2>Mengklasifikasi Jumlah 4 Jenis Pada Cuaca</h2>

Tujuan Akhir:
<br>
<p>Setelah memasukkan data beberapa jenis pada tiap cuaca, mulai dari cuaca matahari terbit, cerah, berawan dan hujan, mesin akan mempelajari foto foto tersebut sehingga dapat membedakan mana musim tiap cuaca , apakah itu cuaca matahari terbit, cerah, berawan dan hujan</p>
<p>Training Data menggunakan Data Train dan Data Validation</p>
<p>Melakukan Prediksi menggunakan Data Test</p>

<h2>Dataset</h2>

<p>Kami mengambil salah satu dataset yang kami temukan di internet.
Kaggle Dataset URL: https://www.kaggle.com/datasets/pratik2901/multiclass-weather-dataset untuk digunakan sebagai data train dan validation serta kami menambah data test yang kami ambil dari google dan foto sendiri sesuai dengan label foto</p>

<br>
	<p>Dataset terdiri dari 1163 gambar cuaca matahari terbit, cerah, berawan dan hujan.</p>
	<ul>
		<li>Gambar Data Train Terdiri dari 825</li>
		<li>Gambar Data Validation Terdiri dari 227</li>
    <li>Gambar Data Test diambil dari google dan foto sendiri sebanyak 111</li>
	</ul>
		<p>Dengan Target Ukuran 150x150 pixels</p>
	</ul>
	<p>Spliting dengan rasio : </p>
	<p> Train : Val : Test = 70% : 20% : 10% </p>

<h2>Labels</h2>

<p>Label data diambil penamaan file : cuaca+nomor</p>
<ul>
		<li>cloudy : menunjukkan cuaca berawan</li>
		<li>rain : menunjukkan cuaca hujan</li>
    <li>shine : menunjukkan cuaca cerah</li>
    <li>sunrise : menunjukkan cuaca matahari terbit</li>
	</ul>

<h2>Tahap - Tahap Pengerjaan :</h2>

### 1. Data Collecting
<p> Menentukan Path Folder Data Validation, dari Data Train & Test</p>

### 2. Data Preprocessing - Data Augmentasi
<p>Membuat Data Gambar Augmentasi dan Visualisasi Data Augmentasi</p>

### 3. Data Analysis and Visualization
<p>Menampilkan Meta Data</p>

### 4. Data Modelling
<p>Membuat Model Sequential dan Visualisasi : Accuracy & Loss Model</p>
<p>Menampilkan visualisasi model</p>

### 5. Evaluasi
<p>Membuat Model Prediksi dengan Folder Data Test</p>

