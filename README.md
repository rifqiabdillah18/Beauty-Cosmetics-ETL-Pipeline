# Beauty Cosmetics ETL Pipeline

## Project Overview
Proyek ini mengotomatisasi pengolahan dataset kosmetik (15.000+ baris) menggunakan **KNIME**. Pipeline ini mengubah data mentah menjadi laporan siap pakai dengan standarisasi harga dan segmentasi pasar otomatis.

## 🛠️ Tahapan ETL
* **Data Cleaning:** Menghapus duplikat dan mengisi nilai kosong (Missing Values).
* **Feature Engineering:** Menghitung 'Price per Unit' menggunakan Math Formula untuk perbandingan harga yang adil.
* **Business Logic:** Klasifikasi otomatis menggunakan Rule Engine untuk menentukan:
  * **Brand Tier:** Luxury, Mid-Range, atau Mass Market.
  * **Quality Assessment:** Best Seller, Average, atau Underperform berdasarkan rating.
* **Data Delivery:** Ekspor hasil akhir ke Excel (Laporan Kosmetik 2.xlsx).


