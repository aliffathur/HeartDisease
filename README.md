# HeartDisease
**1. Distribusi Penyakit Jantung:**
**Visualisasi:** Bar Plot
**Deskripsi:**
Visualisasi ini menunjukkan distribusi jumlah pasien yang memiliki penyakit jantung dan yang tidak. Sumbu X mewakili dua kategori: 0 untuk pasien tanpa penyakit jantung dan 1 untuk pasien dengan penyakit jantung. Sumbu Y menunjukkan jumlah pasien dalam setiap kategori.
**Interpretasi:**
Plot ini membantu kita memahami proporsi pasien yang terdiagnosis dengan penyakit jantung dibandingkan dengan yang tidak. Ini memberikan gambaran awal tentang prevalensi penyakit dalam dataset.
**Algoritma:** Tidak ada algoritma khusus yang digunakan di sini; ini adalah visualisasi sederhana dari data distribusi.

**2. Korelasi Antar Fitur:
Visualisasi: Heatmap
Deskripsi:**
Heatmap ini menampilkan korelasi antara berbagai fitur dalam dataset seperti usia, tekanan darah, kolesterol, dan lainnya. Korelasi diukur dengan koefisien korelasi Pearson, yang berkisar dari -1 (korelasi negatif sempurna) hingga 1 (korelasi positif sempurna).
**Interpretasi:**
Heatmap membantu mengidentifikasi fitur-fitur yang saling berhubungan kuat, yang bisa menjadi indikator penting dalam analisis lebih lanjut. Misalnya, fitur dengan korelasi tinggi mungkin menunjukkan ketergantungan yang lebih besar pada hasil (yaitu, risiko penyakit jantung).
Algoritma: Korelasi Pearson digunakan untuk menghitung hubungan linier antara dua variabel.

**3. Distribusi Usia Berdasarkan Penyakit Jantung:**
Visualisasi: Histogram dan KDE (Kernel Density Estimation)
**Deskripsi:**
Histogram ini menunjukkan distribusi usia pasien yang dikelompokkan berdasarkan apakah mereka memiliki penyakit jantung atau tidak. Selain histogram, garis KDE ditambahkan untuk memperkirakan distribusi probabilitas dari data.
**Interpretasi:**
Visualisasi ini memberikan wawasan tentang bagaimana distribusi usia berbeda antara pasien yang memiliki dan yang tidak memiliki penyakit jantung. Jika distribusi usia cenderung berbeda secara signifikan antara dua kelompok ini, usia mungkin merupakan faktor risiko penting untuk penyakit jantung.
**Algoritma:** KDE digunakan untuk memperkirakan distribusi probabilitas, sementara histogram menampilkan distribusi frekuensi.

**4. Cluster Berdasarkan Usia dan Kolesterol:**
**Visualisasi: ** Scatter Plot dengan KMeans Clustering
**Deskripsi:**
Scatter plot ini menampilkan pengelompokan pasien berdasarkan usia dan kadar kolesterol menggunakan algoritma KMeans. Setiap titik dalam plot mewakili seorang pasien, dengan warna yang berbeda menunjukkan cluster yang berbeda.
**Interpretasi:**
Visualisasi ini membantu mengidentifikasi pola atau pengelompokan alami di antara pasien berdasarkan usia dan kadar kolesterol. Cluster yang dihasilkan bisa menunjukkan segmen populasi yang berbeda dengan risiko penyakit jantung yang bervariasi.
Algoritma: KMeans Clustering digunakan untuk mengelompokkan data ke dalam sejumlah cluster yang ditentukan, berdasarkan jarak Euclidean antar titik data.
