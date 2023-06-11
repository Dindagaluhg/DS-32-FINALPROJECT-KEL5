<h2> Final Project Data Science Batch 32 </h2>
<h2> Kelompok 5 </h2>

**Repository Content:**
1. Source code - D Avengers.ipynb
2. Laporan - D Avengers.ppt
3. Readme.md

Dataset: Marketing Campaign (https://www.kaggle.com/datasets/rodsaldanha/arketing-campaign)

<h3> STAGE 1 </h3>
<h3> EDA, Insight, & Visualization </h3>
Outline:
1. Descriptive Statistics
2. Univariate Analysis
3. Multivariate Analysis
4. Business Insight

**SUMMARY** <br>
Pada tugas stage 1, kesimpulan yang didapat berdasarkan korelasi dan business insight dari dataset Marketing Campaign adalah:

**Korelasi**
1. Bahwa  faktor ekonomi mempengaruhi keputusan keluarga untuk memiliki anak kecil. 
2. Semakin tinggi pendapatan, semakin besar juga kecenderungan untuk mengkonsumsi lebih banyak produk dan melakukan pembelian melalui berbagai saluran penjualan.
3. Secara umum, semakin tinggi pendapatan, umumnya umur kustomer juga lebih tua. Namun, hubungan ini tidak begitu kuat sehingga umur tidak menjadi faktor penentu utama dalam pendapatan.
4. Umumnya kustomer lebih memilih untuk membeli produk melalui toko fisik dan melalui katalog daripada melalui website.
5. Customer cenderung membeli wine karena terpengaruh oleh iklan yang diterima.
6. Semakin banyak jumlah anak kecil dalam keluarga, semakin sedikit jumlah pembelian wine. Ini bisa disebabkan oleh faktor keuangan, prioritas keluarga, atau preferensi pribadi yang berbeda dalam konsumsi alkohol.

**Business Insight** 
1. Kelompok dengan status single dan pendidikan minimal lulusan sarjana (graduation) mungkin lebih aktif dan responsif terhadap interaksi bisnis karena memiliki response terbesar.
2. produk wine mungkin menjadi preferensi atau prioritas bagi kelompok pelanggan dengan pendidikan minimal lulusan sarjana.
3. Customer dengan pendapatan tinggi dan tidak memiliki anak cenderung lebih aktif dalam memberikan tanggapan terhadap interaksi bisnis.
4. Untuk fokus pemasaran dan penjualan pada produk-produk wine dan daging
5. Bahwa kelompok pelanggan yang tidak memiliki anak mungkin merupakan segmen yang penting dalam strategi penjualan langsung.

Dari kesimpulan tersebut, tim marketing mendapatkan informasi berharga untuk mengarahkan strategi pemasaran, penjualan, dan interaksi dengan pelanggan secara lebih efektif.

<h3> STAGE 2 </h3>
<h3> Data Pre-Processing </h3>
Outline:
1. Data Cleaning
2. Feature Engineering

**SUMMARY** <br>
Pada tugas stage 2, kesimpulan yang didapat berdasarkan dari data pre-processing adalah:
1. Missing value pada income diatasi dengan imputasi median
2. Tidak terdapat dupilkat data
3. Melakukan fitur extraction: membuat fitur age menjadi categorical dan membuat fitur baru yaitu jumlah anggota keluarga
4. Melakukan feature encoding pada marital status, education, dan age
5. Melakukan feature selection 
6. Split data menjadi training-testing (70:30)
7. Mengatasi outlier pada training dan testing
8. Melakukan feature tranformation dengan standardisasi
9. Handle Data Imbalance dengan dipilih variabel *response* karena memiliki imbalance yang cukup tinggi dan variabel ini akan dipakai untuk memprediksi ciri kustomer yang akan respons iklan.
10. Membuat feature tambahan: WebEngagement, Jumlah cicilan, Tempat tinggal customer, Delivery time from web purchase

<h3> STAGE 3 </h3>
<h3> Machine Learning Evaluation &
Supervised Learning
Stage </h3>
Outline:
1. Modeling
2. Feature Importance

**SUMMARY** <br>
Pada tugas stage 3, kesimpulan yang didapat berdasarkan dari Machine Learning Evaluation &
Supervised Learning adalah:
1. Split data train dan test
2. Melakukan modeling, evaluation dan tuning parameter Logistic regression, Adaboost, Random forest
3. Membuat Feature importance