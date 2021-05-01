# Draft Kurikulum iData1011

Adaptasi dari:
![](https://cdn-images-1.medium.com/max/1600/0*C2eUsvALEoqx20re.png)

# Daftar Isi
- [Draft Kurikulum iData1011](#draft-kurikulum-idata1011)
- [Daftar Isi](#daftar-isi)
  - [Jalur Menjadi Ilmuwan Data](#jalur-menjadi-ilmuwan-data)
    - [Jalur 1: Fundamental](#jalur-1-fundamental)
      - [1. Dasar Matriks dan Algebra Linear](#1-dasar-matriks-dan-algebra-linear)
    - [Jalur 2: Statistika](#jalur-2-statistika)
      - [1.](#1)
    - [Jalur 3:](#jalur-3)
    - [Jalur 4:](#jalur-4)
    - [Jalur 5:](#jalur-5)
    - [Jalur 6:](#jalur-6)
    - [Jalur 7:](#jalur-7)
    - [Jalur 8: Data Ingestion](#jalur-8-data-ingestion)
      - [1. Using ETL](#1-using-etl)
      - [2. How much Data?](#2-how-much-data)
      - [3. Google OpenRefine](#3-google-openrefine)
      - [4. Data Survey](#4-data-survey)
      - [5. Transformation & Enrichment](#5-transformation--enrichment)
      - [6. Data Fusion](#6-data-fusion)
      - [7. Data Integration](#7-data-integration)
      - [8. Data Sources & Acquisition](#8-data-sources--acquisition)
      - [9. Data Discovery](#9-data-discovery)
      - [10. Summary of Data Formats](#10-summary-of-data-formats)
    - [Jalur 9: Data Munging](#jalur-9-data-munging)
      - [1. Dimensionality & Numeriosity Reduction](#1-dimensionality--numeriosity-reduction)


## Jalur Menjadi Ilmuwan Data
### Jalur 1: Fundamental
#### 1. Dasar Matriks dan Algebra Linear

### Jalur 2: Statistika
#### 1. 

### Jalur 3:
### Jalur 4:
### Jalur 5:
### Jalur 6:
### Jalur 7:
####

### Jalur 8: Data Ingestion
#### 1. Using ETL
#### 2. How much Data?
#### 3. Google OpenRefine
#### 4. Data Survey
#### 5. Transformation & Enrichment
#### 6. Data Fusion
#### 7. Data Integration
#### 8. Data Sources & Acquisition
#### 9. Data Discovery
#### 10. Summary of Data Formats

### Jalur 9: Data Munging
#### 1. Principal Component Analysis
#### 2. Stratified Sampling
#### 3. Sampling
#### 4. Denoising
#### 5. Feature Extraction
#### 6. Binning Sparse values
#### 7. Unbiased Estimators
#### 8. Handling Missing Values
#### 9. Data Scrubbing
#### 10. Normalization
* Normalization memiliki arti mentransformasikan data, yakni mengubah data ke bentuk lain untuk pemrosesan data yang memungkinkan menjadi lebih efektif. Tujuan utama Normalization adalah meminimalkan bahkan mengecualikan data-data yang bersifat ganda atau duplikat. Hal ini cukup penting karena menjadi permasalahan apabila menyimpan data dalam database relasional, dimana menyimpan data identik di lebih dari satu tempat. 
* Penggunaan Normalization memiliki beberapa keuntungan, yaitu :
  * 1. Penerapan algoritma menjadi lebih mudah.
  * 2. Algoritma data menjadi lebih efektif dan efisien.
  * 3. Dapat dipahami semua orang.
  * 4. Data dapat diekstraksi lebih cepat.
  * 5. Memungkinkan untuk menganalisis data dengan cara tertentu.
* Teknik umum Normalization adalah sebagai berikut :
  * 1. Min-Max Normalization ⇒ x_new = (x - min(x))/(max(x)-min(x))
  * 2. Mean-Standard Deviation Normalization ⇒ x_new = (x - mean(x))/std(x)
  * 3. Softmax Normalization ⇒ (1+exp((mean(x)-x)/std(x)))^-1
#### 11. Dimensionality & Numeriosity Reduction
**Dimensionality Reduction**
* Dimensionality reduction adalah proses pengurangan jumlah variabel atau atribut acak yang mengubah atau memproyeksikan data asli ke ruang yang lebih kecil.
* Beberapa teknik yang mungkin, diantaranya sebagai berikut :
  * 1. Principal Component Analysis. Merupakan teknik pengurangan fitur yang paling umum. Dalam teknik ini dapat menentukan jumlah komponen utama yang sesuai.
  * 2. Linear Discriminant Analysis. Ialah teknik lain dengan cara kerja serupa, yaitu dengan memilih jumlah vektor eigen yang sesuai.
  * 3. Autoencoders. Merupakan teknik pengurangan dimensi berbasis Neural Networks.
  * 4. Manifold Learning. Adalah teknik yang menggunakan reduksi dimensi non-linier.
* Terdapat beberapa teknik lain untuk reduksi fitur dengan berdasarkan fitur yang dipilih sesuai dengan kepentingannya masing-masing, yaitu : sequential forward selection, feature importance estimation based on Random forests or decision trees or any ensemble methods, Relief Algorithm, mutual information, information gain, dan lain-lain.
**Numerosity Reduction**
* Numerosity Reduction adalah teknik reduksi data yang menggantikan data asli dengan bentuk representasi data yang lebih kecil. Terdapat dua teknik untuk Numerosity Reduction, yaitu :
  * 1. Parametric Methods, data direpresentasikan menggunakan model untuk mengestimasi data, sehingga hanya parameter data yang perlu disimpan, bukan data aktualnya. Terdapat dua model, diantaranya : _Regression_, dapat berupa linier sederhana dan linier berganda. Dan _Log-Linear_, dapat digunakan untuk memperkirakan probabilitas setiap titik data dalam ruang multidimensi untuk sekumpulan atribut terpisah, memungkinkan ruang data dimensi lebih tinggi dibangun dari atribut berdimensi lebih rendah.
  * 2. Non-Parametric Methods, metode ini digunakan untuk menyimpan representasi data yang dikurangi meliputi Histogram, Clustering, Sampling, dan Data Cube Aggregation.

### Jalur 10: Toolbox
#### 2. Java, Python
