[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/hTtEshwM)
# Graded Challenge 5

_Graded Challenge ini dibuat guna mengevaluasi pembelajaran pada Hacktiv8 Comprehensive Data Analytics Program khususnya pada konsep Business Knowledge dan Practical Statistics._

---

## Assignment Instructions

*Graded Challenge 5* dikerjakan dalam format **Notebook (.ipynb)**  di bawah ini:

1. *Project* dinyatakan selesai dan diterima untuk dinilai jika notebook dapat dirun seluruhnya tanpa ada error (code block web scraping tidak perlu dirun ulang).

2. Pada tugas Graded Challenge 5, akan diminta untuk membuat:
   -  **Notebook (.ipynb)** yang berisikan pengambilan, pengolahan, dan analisis data. Kerjakan dengan Visual Studio Code!

3. Notebook **wajib** diberikan keterangan atau pengenalan dengan menggunakan `markdown` yang berisikan Judul tugas, Nama, Batch, dan penjelasan singkat tentang program yang dibuat, fitur-fitur. Contoh:
    ```py
    '''
    Graded Challenge 5

    Nama  : Fahmi Iman Alfarizki
    Batch : CODA-RMT-001

    Program ini dibuat untuk melakukan automatisasi pengolahan (cleaning) data text yang berguna untuk pemodelan model analisa sentimen.

    '''
    ```
5. Tiap cell diberikan penjelasan mengenai apa yang dilakukan/dijalankan dengan markdown.

6. **WARNING**: Plagiarisme sekecil apapun dapat terdeteksi. Tugas ini akan diuji tingkat plagiarismenya dengan software khusus.

---

## Assignment Submission

- Simpan assignment pada Graded Challenge 5 ini dengan nama `P1G5_<nama-student>.ipynb` (notebook). Misal `P1G5_fahmi-iman.ipynb`(**Maksimal nama dua suku kata**).
- Push file Assigment yang telah dibuat ke repository Github Classroom masing-masing student.

---

## Assignment Objectives

*Graded Challenge 5* ini dibuat guna mengevaluasi konsep Business Knowledge dan Practical Statistics sebagai berikut:

- Mampu membangun problem statement dengan framework SMART sebagai salah satu langkah business understanding
- Mampu melakukan perhitungan statistik deskriptif
- Mampu melakukan pengujian statistik dan merumuskan hipotesis
- Mampu mengambil insight/informasi dari hasil perhitungan
- Mampu mengambil kesimpulan yang menjawab problem statement

---

## Assignment Instructions and Cases

#### Case
Kamu ingin menambah pendapatanmu dengan berjualan. Namun, kamu tidak punya cukup modal untuk produksi barang dan hanya cukup untuk promosi, sehingga kamu memutuskan untuk menjalanan skema dropship di platform Tokopedia.

Kamu masih bingung akan berjualan apa dan teringat bahwa saat ini sedang viral seblak. Namun, kamu tidak yakin apakah benar bahwa masyarakat memiliki animo yang besar terhadap seblak.

Karena kamu lulusan bootcamp Data Analytics Hacktiv8, dengan kemampuan dan pengetahuan kamu, kamu ingin menganalisis bagaimana penjualan produk seblak di Tokopedia. Apakah orang suka, apakah banyak yang beli, dsb.

#### A. Dataset
1. Data yang tersedia adalah data hasil web scraping produk seblak dari Tokopedia sama seperti yang sudah kamu pernah lakukan di P0GC3.
2. Data sudah bersih jadi tidak perlu melakukan data cleaning
3. Kamu hanya perlu melakukan data eksplorasi sederhana untuk mengenal data


#### B. Business Understanding
1. Buat konteks bisnis dari data dan permasalahan yang ingin diselesaikan (Kamu boleh mengarang cerita namun harus relevan dengan konteks permasalahan dan masuk akal)
2. Kemudian, buat problem statement menggunakan SMART framework berikut dengan penjabaran Specific, Measurable, Achievable, Relevant, dan Time-bound. Jangan lupa rangkum dalam satu kalimat problem statement serta gunakan metrik yang tepat dari kasus ini.

#### C. Analysis
Dalam melakukan analisa data untuk mencapai tujuan yang diinginkan, kamu perlu mengikuti soal/pertanyaan/instruksi berikut ini:

1. Hitung rata-rata, median, standar deviasi, skewness, dan kurtosis dari kolom harga, banyak produk terjual, dan rating. Dari hasil perhitungan, insight apa saja yang bisa kamu dapatkan khususnya terkait dengan produk seblak dan datanya (distribusi dan kecenderungan ada/tidaknya outlier)?
   **Note:** Jika menemukan adanya indikasi outlier dari perhitungan ini, tidak perlu dihandle karena sifatnya alami. Dibiarkan saja.

2. Kamu memikirkan berapa potensi minimum dan maksimum pendapatan jika kamu menjual produk seblak?(Gunakan confidence interval untuk mendapatkan lower value dan upper value dari distribusi populasi pendapatan).

   Anggap data terdistribusi normal dan informasi produk terjual merupakan penjualan produk per bulan. Ambil confidence level 95%.

3. Apakah harga barang di Jabodetabek dan di luar Jabodetabek berbeda? mengingat biaya bahan baku di kedua lokasi berbeda. (Gunakan uji hipotesis yang diawali dengan menuliskan hipotesis null dan alternatifnya serta tentukan jenis hipotesis yang digunakan).

4. Apakah orang lebih cenderung suka dengan produk yang harganya murah?

   Kamu dapat jawab pertanyaan ini dengan uji korelasi. Gunakan library scipy jangan pandas. Analisis nilai korelasi dan p-value nya. Gunakan teknik yang sesuai dengan kondisi data!

   Kamu dilarang untuk copy-paste pertanyaan soal. Buat lah cerita yang runut dari persoalan dan jawaban nomor 1 sampai 4 sebagai ganti kalimat soal.

#### D. Conclusion
Tuliskan di markdown kesimpulan dari hasil analisis dari nomor 1-4. Kesimpulan yang baik menjawab tujuan yang ingin dicapai. Kamu dibebaskan menuliskan dalam format paragraf atau poin.

## Assignment Rubrics

|**Key Component**|**Description**|**Points**|
|---|---|---|
|Business Knowledge|Siswa mampu membangun konteks bisnis dari permasalahan yang ada dan pembuat problem statement dengan metode SMART |6 pts|
|Statistics Deskriptive|Siswa dapat menerapkan konsep statistik deskriptif pada data |8 pts|
|Statistics Inferential|Siswa dapat menerapkan konsep statistik inferensial pada data |8 pts|
|Insight dan Analysis|Siswa mampu mendapatkan insight dari analisa statistik dan mendapatkan kesimpulan |25 pts|
|Readability|Semua cell di notebook terdokumentasikan dengan baik dengan Semua markdown dan heading digunakan markdown pada tiap cell ntuk secara tepat sehingga notebook rapih dan penielasan kode|4 pts|

**Total: 51 pts**

---
## Score Reduction

Jika Student terlambat mengumpulkan dengan waktu yang ditentukan, maka Graded Challenge akan diberi poin nol.

--- 
