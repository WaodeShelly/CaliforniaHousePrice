### **Business Problem Understanding**
**Context**

Pasar perumahan di California memainkan peran penting dalam perekonomian, namun juga menghadapi tantangan besar akibat fluktuasi harga yang terus terjadi. Berbagai faktor seperti lokasi geografis, aksesibilitas terhadap fasilitas umum, pendapatan masyarakat, dan dinamika pasar lokal memengaruhi harga rumah secara signifikan.

Bagi pembeli, pengembang, dan agen real estate, memahami dan memperkirakan harga rumah dengan akurat menjadi prioritas untuk mendukung pengambilan keputusan strategis, baik untuk investasi maupun penentuan harga jual-beli. Namun, proses ini memiliki sejumlah hambatan, termasuk:

- Kompleksitas variabel: Data yang melibatkan berbagai aspek seperti ukuran rumah, jumlah kamar, usia bangunan, dan karakteristik lingkungan membutuhkan analisis mendalam.
- Efisiensi waktu: Metode manual dalam menentukan harga rumah sering memakan waktu lama dan rentan terhadap bias.
- Variasi harga lokal: Perbedaan harga yang signifikan antara wilayah urban, suburban, dan rural memerlukan pendekatan yang kontekstual dan berbasis data.

Selain itu, pasar perumahan California memiliki tantangan spesifik seperti permintaan tinggi di wilayah padat penduduk, ketimpangan daya beli antar komunitas, dan krisis keterjangkauan rumah akibat kenaikan harga yang melampaui pendapatan rata-rata. Untuk mengatasi masalah ini, pendekatan berbasis Machine Learning menjadi penting untuk membantu menemukan pola harga rumah secara otomatis dan akurat dengan memanfaatkan data historis.

**Problem Statement**

Bagaimana membangun sebuah model berbasis Machine Learning yang dapat memperkirakan harga rumah di California secara akurat berdasarkan berbagai faktor, seperti lokasi geografis, ukuran rumah, jumlah kamar, serta pendapatan rata-rata di lingkungan sekitarnya?

Fluktuasi harga rumah yang tinggi menciptakan ketidakpastian bagi berbagai pemangku kepentingan dalam pasar properti. Tantangan ini menimbulkan dampak negatif seperti:

- Kerugian finansial: Penetapan harga yang tidak akurat dapat merugikan pembeli maupun penjual rumah.
- Peluang yang terlewatkan: Investor properti kesulitan memanfaatkan peluang pasar akibat kurangnya prediksi harga yang tepat.
- Krisis keterjangkauan: Pembeli rumah sulit menentukan apakah suatu properti berada dalam jangkauan mereka, terutama di daerah dengan harga yang terus meningkat.

Pendekatan tradisional yang bergantung pada estimasi manual tidak cukup untuk mengatasi dinamika kompleks pasar California. Dengan mengembangkan model prediktif berbasis Machine Learning, kita dapat:

1. Mengidentifikasi pola harga: Menganalisis hubungan antar variabel yang memengaruhi harga rumah secara sistematis.
2. Menyediakan prediksi akurat: Membantu pembeli, penjual, dan investor untuk mengambil keputusan berbasis data.
3. Meningkatkan efisiensi: Menghemat waktu dan tenaga dibandingkan metode tradisional.

Tanpa solusi ini, pasar properti California akan terus menghadapi tantangan dalam memastikan keputusan yang tepat dan efisien di tengah fluktuasi harga yang signifikan.

**Goals**

1. Membangun model regresi dengan performa akurasi tinggi dan dapat diandalkan.
2. Memberikan alat bantu bagi pembeli rumah, agen properti, dan pengembang real estate untuk memperkirakan harga rumah secara objektif.
3. Mendukung pengambilan keputusan strategis di pasar properti dengan analisis berbasis data.

**Analysis Approach**

Langkah-langkah yang akan dilakukan meliputi:

1. Eksplorasi data: Melakukan analisis untuk memahami pola, distribusi data, dan hubungan antar fitur, seperti lokasi, luas rumah, jumlah kamar, dan pendapatan lingkungan terhadap harga rumah.
2. Pra-pemrosesan data: Membersihkan dan mempersiapkan data, seperti menangani missing values, outliers, dan transformasi data jika diperlukan.
3. Pembangunan model regresi: Menggunakan algoritma regresi (seperti Linear Regression, Random Forest, atau Gradient Boosting) untuk memprediksi harga rumah berdasarkan fitur yang tersedia.
4. Optimasi model: Melakukan tuning hyperparameter untuk meningkatkan performa prediksi model.
Hasil dari analisis ini akan digunakan untuk membangun tool prediksi harga rumah yang dapat membantu berbagai pemangku kepentingan dalam menetapkan harga yang kompetitif dan wajar.

**Metric Evaluation**

Evaluasi model akan menggunakan beberapa metrik, di antaranya:

1. Root Mean Squared Error (RMSE): Mengukur akar rata-rata kuadrat error, memberikan bobot lebih pada error yang besar.
Mean Absolute Error (MAE): Mengukur rata-rata nilai absolut error, yang lebih mudah diinterpretasikan dalam skala harga rumah.
2. Mean Absolute Percentage Error (MAPE): Menunjukkan rata-rata persentase error, membantu memahami performa relatif model terhadap nilai sebenarnya.
3. R-squared (R²): Digunakan untuk mengevaluasi seberapa besar model mampu menjelaskan variansi dalam data (khusus untuk model linear).

Semakin kecil nilai RMSE, MAE, dan MAPE, semakin baik model dalam memprediksi harga rumah. Sementara itu, nilai R² mendekati 1 menunjukkan model yang fit dengan data.
