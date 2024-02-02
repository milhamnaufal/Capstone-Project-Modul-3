## Capstone-Project-Modul-3 (Penerapan Model Machine Learning (ML) dalam Deposito Perbankan

## **Permasalahan**
Terdapat sebuah Perusahaan Perbankan yang bergerak dalam bidang deposito yang sedang melakukan analisis serta manajemen pengeluaran keuangan dari Perusahaan. Permasalahan pengeluaran keuangan Perusahaan akan berfokus ketika terjadi salah prediksi mengenai calon Nasabah yang diprediksi akan melakukan deposito namun aktualnya calon Nasabah tersebut tidak melakukan deposito. Maka dari itu Perusahaan yang sebelumnya telah mengeluarkan biaya pelayanan terhadap calon Nasabah karena dianggap akan melakukan deposito namun kenyataannya Nasabah tersebut tidak melakukan deposito. Biaya yang dikeluarkan untuk setiap Nasabah untuk melakukan pelayanan adalah sebesar $50 per Nasabah.

Maka dari itu saya akan memberikan solusi berupa penerapan modeling Machine Learning pada permasalahan ini dengan tujuan agar biaya yang dikeluarkan oleh Perusahaan dapat di minimalisir ketika terjadi kondisi seperti hal tersebut. Oleh karena itu, untuk melakukan modeling maka saya akan menjelaskan beberapa tahap modeling sebagai berikut:

- **Data Understanding**
    - Merupakan bagian untuk mengetahui isi dari dataset yang diberikan dengan tujuan untuk mengetahui informasi dari data 
- **Data Cleaning**
    - Tahap untuk membersihkan dataset dengan tujuan agar proses analisis dan modeling tidak terganggu oleh Noise yang disebabkan akibat data tidak dilakukan cleaning. Adapun proses dari Data Cleaning dapat diuraikan sebagai berikut.
        - Handling Missing Value
        - Handling Duplicate Data
        - Outliers Checking
        - Handling Ireelevant feature or value
        - Feature Selection
- **Exploratory Data Analysis (EDA)**
    - EDA merupakan tahapan untuk menampilkan insight yang dapat diambil dari data dan dapat dilakukan dengan bantuan dari visualisasi
- **Define Variable**
    - Mendefinisikan variabel X (Feature) dan Y (Target) sebagai prasyarat untuk membuat sebuah model Machine Learning (ML)
- **Data Splitting**
    - Mendefinisikan data training dan testing agar model Machine Learning (ML) dapat mempelajari terlebih dahulu dari data yang ada untuk kemudian model tersebut akan diujikan terhadap data Testing untuk mengetahui seberapa besar akurasi dari model yang dipilih
- **Data Preprocessing**
    - Mempersiapkan data agar data tersebut mampu disediakan untuk melakukan pembuatan model Machine Learning (ML). Adapun bagian dari Data Preprocessing terdiri sebagai berikut
        - Encoding
        - Scaling
        - Binning
        - Handling Missing Value (Optional)
- **Cross Validation**
    - Merupakan tahapan untuk memilih model / algoritma Machine Learning (ML) terbaik berdasarkan metrik / scoring yang digunakan
- **Hyperparameter Tuning**
    - Menentukkan parameter terbaik dari model yang terpilih dari proses Cross Validation sebelumnya
- **Menentukan Threshold terbaik**
    - Threshold merupakan ambang batas yang menentukkan apakah setiap baris data dikategorikan sebagai kelas negatif (0) atau positif (1) pada variabel target. Pada tahapan ini akan menentukkan berapa nilai ambang batas terbaik sehingga nilai Threshold tersebut diharapkan akan meningkatkan akurasi dari model yang dipilih
- **Menampilkan Confusion Matrix**
    - Menampilkan Confusion Matrix bertujuan untuk mengetahui nilai / value dari setiap kondisi yang ada
- **Membandingkan model pada saat sebelum dan sesudah Tuning**
    - Bertujuan untuk mengetahui model mana yang terbaik jika dibandingkan pada saat sebelum dan sesudah dilakukan Tuning. Perbandingan tersebut dapat dilihat dari nilai akurasi dari model pada setiap kondisi. 
- **Feature Importance**
    - Feature Importance merupakan tahapan untuk mengetahui fitur manakah yang berpengaruh signifikan terhadap variabel target

## Kesimpulan
- Ketika Perusahaan belum menerapkan modeling maka terdapat sejumlah 27 Nasabah yang salah prediksi sehingga biaya yang dikeluarkan oleh Perusahaan adalah sebesar 27 x $50 = $135.
- Namun setelah dilakukan modeling dengan menggunakan K-Nearest Neighbors dapat meminimalisir pengeluaran tersebut. Terdapat hanya sejumlah satu orang saja yang disalah prediksi sehingga biaya yang dikeluarkan oleh Perusahaan hanya sebesar $50.
