# Descriptive-Statistics

Descriptive Statistics merupakan dokumentasi dari pengolahan dan penyajian data. Data yang digunakan ialah data survei yang berjudul **"Berapa Menit Anda Ngoding Dalam Satu Minggu"**. Survei ini ditujukan bagi mahasiswa **Teknik Informatika UPN "Veteran" Jawa Timur**. Untuk data survei bisa dilihat [disini](https://github.com/arryaaas/Descriptive-Statistics/blob/main/notebook/coding.csv).

## Fitur

Dalam dokumentasi ini dilakukan **pengolahan dan penyajian data** hasil survei sebagai berikut : 

Pengolahan Data | Penyajian Data
----------------|---------------
Mean, Median, Modus | Tabel Distribusi Frekuensi
Kuartil bawah (Q1), Kuartil atas (Q3) | Tabel Distribusi Frekuensi Kumulatif
Varian | Tabel Distribusi Frekuensi Relatif
Standar Deviasi| Tabel Distribusi Frekuensi Relatif Kumulatif
Rentang Kelas | Diagram Histogram (untuk 4 tabel diatas)
Banyak Kelas | Diagram Lingkaran (untuk 4 tabel diatas)
Panjang Kelas| Diagram Ogive (untuk 4 tabel diatas)

## Visualisasi Data

Visualisasi data menggunakan library [matplotlib](https://matplotlib.org/) yang dimiliki oleh Python. Data divisualisasikan menjadi 3 diagram, yaitu diangram histogram, diagram lingkaran, dan diagram ogive. Style yang digunakan dalam diagram berikut ialah [seaborn](https://seaborn.pydata.org/).

<p>
<img width="200px" src="https://github.com/arryaaas/Descriptive-Statistics/blob/main/images/image-1.png"/>
<img width="200px" src="https://github.com/arryaaas/Descriptive-Statistics/blob/main/images/image-2.png"/>
<img height="160px" src="https://github.com/arryaaas/Descriptive-Statistics/blob/main/images/image-3.png"/>
</p>

## Libraries
- [math](https://docs.python.org/3/library/math.html) digunakan untuk menghitung math.log10() untuk mencari banyak kelas pada fungsi number_of_classes.
- [NumPy](https://numpy.org/) digunakan untuk melakukan perhitungan pada parameter weights pada fungsi hist() dari matplotlib untuk membuat grafik histogram.
- [Pandas](https://pandas.pydata.org/) digunakan untuk membaca file excel dan visualisasi tabel distribusi dengan cara diubah menjadi dataframe.
- [Matplotlib](https://matplotlib.org/) digunakan untuk visualisasi data dalam bentuk grafik.

## Video Penjelasan 

Video penjelasan tentang Descriptive Statistics (Pengolahan dan Penyajian Data) dan Demo Programnya dapat dilihat [disini](https://youtu.be/DQyrIqbD0L0).

## Lisensi

Didistribusikan di bawah Lisensi MIT. Lihat `LISENSI` untuk informasi lebih lanjut.

## Kontak

Mochammad Arya Salsabila - Aryasalsabila789@gmail.com
