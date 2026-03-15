![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)	![Google Colab](https://img.shields.io/badge/Google%20Colab-%23F9A825.svg?style=for-the-badge&logo=googlecolab&logoColor=white)


🍫 Chocolate Sales Machine Learning Project

📌 Project Overview

Project ini bertujuan untuk menerapkan pipeline Machine Learning secara lengkap mulai dari eksplorasi data, pemodelan, hingga evaluasi model.

Dataset yang digunakan berisi data transaksi penjualan cokelat tahun 2025. Analisis dilakukan untuk menjawab dua studi kasus utama:

Sales Prediction (Regression) → memprediksi nilai revenue penjualan

Customer Segmentation (Clustering) → mengelompokkan pola transaksi penjualan

Seluruh analisis dilakukan menggunakan Python dan Jupyter Notebook.

📊 Dataset Information

Dataset berisi 500 data transaksi penjualan cokelat dengan beberapa variabel penting.

Feature	Description
Sale_ID	ID transaksi
Date	tanggal transaksi
Brand	merek cokelat
Product_Type	jenis produk
Country	negara penjualan
Sales_Channel	channel penjualan
Payment_Method	metode pembayaran
Price_USD	harga produk
Units_Sold	jumlah unit terjual
Revenue_USD	total pendapatan

Revenue dihitung dari kombinasi harga produk dan jumlah unit yang terjual.

⚙️ Machine Learning Pipeline

Project ini mengikuti tahapan pipeline Machine Learning berikut:

1️⃣ Data Understanding
2️⃣ Data Cleaning
3️⃣ Exploratory Data Analysis (EDA)
4️⃣ Feature Selection
5️⃣ Model Training
6️⃣ Model Evaluation
7️⃣ Customer Segmentation

Tahapan ini dilakukan secara sistematis agar model yang dihasilkan dapat dianalisis dengan baik.

📈 Exploratory Data Analysis (EDA)

Pada tahap ini dilakukan eksplorasi terhadap dataset untuk memahami pola data.

Analisis yang dilakukan antara lain:

distribusi penjualan

tren revenue

deteksi outlier menggunakan boxplot

analisis korelasi antar variabel menggunakan heatmap

EDA membantu memahami hubungan antar variabel yang akan digunakan dalam pemodelan machine learning.

📉 Sales Prediction (Regression)
Objective

Membangun model yang dapat memprediksi Revenue_USD berdasarkan variabel yang tersedia.

Models Used

Model yang digunakan dalam tugas ini:

Linear Regression

Random Forest Regressor

Evaluation Metrics

Performa model diukur menggunakan beberapa metrik evaluasi:

Mean Absolute Error (MAE)

Mean Squared Error (MSE)

Root Mean Squared Error (RMSE)

R² Score

Grafik Actual vs Predicted digunakan untuk melihat akurasi prediksi model.

Result

Model berhasil mempelajari hubungan antara variabel input dan nilai revenue.

Model Random Forest Regressor memberikan performa yang lebih baik karena mampu menangkap hubungan yang lebih kompleks dibandingkan Linear Regression.

👥 Customer Segmentation (Clustering)
Objective

Mengelompokkan transaksi penjualan berdasarkan pola pembelian menggunakan metode clustering.

Method

Algoritma yang digunakan:

K-Means Clustering

Jumlah cluster optimal ditentukan menggunakan:

Elbow Method

Silhouette Score

Result

Data transaksi berhasil dikelompokkan menjadi 3 cluster utama:

Cluster	Karakteristik
Cluster 0	transaksi dengan revenue rendah
Cluster 1	transaksi dengan revenue sedang
Cluster 2	transaksi dengan revenue tinggi

Segmentasi ini membantu memahami pola pembelian pelanggan.

🛠 Tools & Libraries

Project ini menggunakan beberapa library Python berikut:

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

📂 Project Structure
MachineLearningTask-Nanda
│
├── MachineLearningTask_Nanda.ipynb
├── chocolate_sales_2025_dataset.csv
└── README.md
🎯 Conclusion

Dari analisis yang dilakukan dapat disimpulkan bahwa:

Machine learning dapat digunakan untuk memprediksi nilai revenue penjualan dengan cukup baik.

Model Random Forest memberikan performa yang lebih baik dibandingkan Linear Regression.

Metode clustering berhasil mengelompokkan pola transaksi penjualan menjadi tiga segmen utama.

Hasil analisis ini dapat membantu memahami pola penjualan dan mendukung pengambilan keputusan bisnis berbasis data.

🚀 Future Improvement

Beberapa pengembangan yang dapat dilakukan pada project ini:

menambahkan fitur baru untuk meningkatkan akurasi model

mencoba algoritma regresi lain seperti Gradient Boosting

melakukan analisis segmentasi pelanggan yang lebih mendalam
