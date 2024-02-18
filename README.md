# California-Housing-Price-Regression 🏡

### Context 🐻

Di California, salah satu negara bagian terpadat di Amerika Serikat, pertumbuhan populasi dan permintaan akan perumahan sangat tinggi. Ini membuat industri properti menjadi sangat kompetitif dan pentingnya memahami faktor-faktor yang memengaruhi nilai suatu properti. Dengan informasi yang tepat, para pemilik properti yang ingin menjual properti mereka di California dapat memiliki pemahaman tentang faktor-faktor yang memengaruhi nilai properti, seperti lokasi, usia bangunan, dan pendapatan median di sekitar wilayah tersebut. Hal ini akan membantu mereka dalam menentukan harga jual yang optimal, sehingga mereka dapat memaksimalkan profitabilitas properti mereka.

### Problem Statement 💵

Salah satu tantangan utama yang dihadapi oleh pemilik properti di California adalah menentukan harga jual properti mereka dengan tepat. Dalam industri properti yang sangat kompetitif, harga properti yang ditawarkan haruslah kompetitif dan sebanding dengan nilai properti tersebut, untuk memastikan properti tetap diminati pembeli potensial.

Dengan kebebasan yang diberikan kepada pemilik properti untuk menentukan harga jual properti mereka sendiri, keputusan ini menjadi sangat penting dan membutuhkan analisis yang cermat. Faktor-faktor seperti lokasi geografis, usia bangunan, jumlah ruangan dan kamar tidur, populasi di sekitar wilayah tersebut, dan pendapatan median penduduk dapat memengaruhi nilai properti.

Dengan pertumbuhan populasi yang terus meningkat di California, pemilik properti perlu memastikan bahwa harga sewa atau harga jual properti mereka optimal untuk menarik minat pembeli potensial, sambil tetap memastikan profitabilitas properti mereka.

Oleh karena itu, **masalah utama yang dihadapi adalah bagaimana menentukan harga jual properti yang optimal di tengah persaingan yang ketat di pasar properti California**. Hal ini menuntut analisis mendalam terhadap data properti, termasuk identifikasi pola-pola dan tren-tren pasar yang ada, sehingga pemilik properti dapat membuat keputusan yang cerdas dan strategis dalam menentukan harga properti mereka.

### Goals 📈

Berdasarkan permasalahan yang dihadapi oleh pemilik properti di California, tujuan utama projek ini adalah untuk mengembangkan sebuah alat prediksi harga properti yang dapat membantu pemilik properti (tuan rumah) dalam menentukan harga jual properti mereka dengan tepat. Tujuan spesifik proyek ini adalah:

* Mengembangkan model prediksi harga properti: Menggunakan data historis properti California, tujuan utama adalah mengembangkan model Machine Learning yang dapat memprediksi harga jual properti berdasarkan berbagai fitur properti, seperti lokasi geografis, usia bangunan, jumlah ruangan dan kamar tidur, populasi di sekitar wilayah tersebut, dan pendapatan median penduduk.

* Meningkatkan keakuratan prediksi: Tujuan kedua adalah meningkatkan keakuratan prediksi model sehingga pemilik properti dapat memiliki keyakinan yang tinggi dalam menentukan harga properti mereka.

* Mendukung keputusan strategis: Model prediksi harga properti ini diharapkan dapat menjadi alat yang berguna bagi pemilik properti dalam membuat keputusan strategis terkait harga properti mereka. Dengan memahami tren dan pola pasar properti, pemilik properti dapat membuat keputusan yang cerdas dan menguntungkan untuk properti mereka.


### Analytic Approach 📊

* Eksplorasi Data: Tahap awal akan melibatkan analisis eksplorasi data untuk memahami karakteristik dan distribusi dari setiap fitur dalam dataset. Pemeriksaan statistik deskriptif, visualisasi data, dan korelasi antar fitur untuk mengidentifikasi pola dan hubungan yang mungkin ada di dalam dataset.

* Preprocessing Data: Setelah memahami data, langkah selanjutnya adalah preprocessing data. Ini mencakup penanganan *missing value* atau scaling fitur, dan konversi variabel kategori menjadi bentuk yang dapat diolah oleh model.

* Pemilihan Fitur: Pemilihan fitur untuk menentukan subset fitur yang paling relevan dan berpengaruh terhadap harga properti. Hal ini dapat dilakukan berdasarkan analisis korelasi.

* Pembangunan Model: Beberapa model regresi yang berbeda, seperti Linear Regression, Random Forest Regression, dan DecisionTree Regression akan dibuat. Setiap model akan dievaluasi untuk menentukan kinerja dan keakuratannya.

* Evaluasi Model: Evaluasi model akan dilakukan menggunakan berbagai metrik evaluasi, termasuk Root Mean Squared Error (RMSE), Mean Absolute Error (MAE), dan coefficient of determination (R-squared). Ini akan membantu untuk memahami seberapa baik model  dalam memprediksi harga properti.

* Tuning Model: Jika diperlukan, akan dilakukan tuning parameter pada model. Hal ini dilakukan untuk meningkatkan kinerja model.


### Metric Evaluation 📋

Untuk mengevaluasi kinerja model prediksi harga properti, digunakan beberapa metrik evaluasi berikut:

* Root Mean Squared Error (RMSE): Nilai rata-rata akar kuadrat dari error antara nilai prediksi dan nilai sebenarnya. RMSE memberikan gambaran tentang seberapa jauh rata-rata prediksi model dari nilai sebenarnya. Semakin kecil nilai RMSE, semakin baik model dalam memprediksi harga properti.

* Mean Absolute Error (MAE): Rata-rata nilai absolut dari error antara prediksi dan nilai sebenarnya. MAE mengukur kesalahan rata-rata absolut dari prediksi model. Nilai MAE yang lebih kecil menunjukkan bahwa model memiliki tingkat kesalahan yang lebih rendah.

* Mean Absolute Percentage Error (MAPE): Mengukur rata-rata persentase kesalahan prediksi terhadap nilai sebenarnya. Ini memberikan gambaran tentang seberapa akurat prediksi model dalam persentase. Semakin kecil nilai MAPE, semakin akurat model dalam memprediksi harga properti dalam hal persentase kesalahan.

* Coefficient of Determination (R-squared): Untuk model regresi linear, nilai R-squared atau adjusted R-squared digunakan sebagai metrik evaluasi tambahan. R-squared mengukur seberapa baik variabel independen menjelaskan variasi dalam variabel dependen. Nilai R-squared berkisar antara 0 dan 1, di mana nilai yang lebih tinggi menunjukkan bahwa model lebih baik dalam menjelaskan variasi dalam data.

Metrik evaluasi ini digunakan untuk mengevaluasi kinerja model dan memilih model terbaik yang paling sesuai untuk memprediksi harga properti di California.
