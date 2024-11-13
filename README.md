# Shopping-Mall-Analysis

Project ini dibuat oleh San Gabriel Vanness Kenrick Erwi.

## Objective(Background)

Peningkatan mal di turki berdampak signifikan pada budaya dan sosial. Memahami perubahan ini sangat penting untuk memahami tren yang sedang berlangsung dan terus berkembang. Mal atau pusat perbelanjaan ini mempengaruhi pilihan gaya hidup di Turki. Juga memegang peran penting dalam membentuk dan mengglobalkan kebiasaan konsumsi. Keberadaan banyak mal saat ini tentunya akan menimbulkan persaingan yang ketat di sektor ini. Oleh karena itu setiap mal harus mampu mengantisipasi persaingan pasar untuk menarik minat konsumen untuk mengunjungi mal tersebut agar intensitas penjualan meningkat.

Maka dari itu, harus dilakukan analisis terhadap data transaksi pelanggan di beberapa mal untuk mencari atau mengetahui strategi pemasaran yang harus dilakukan untuk meningkatkan intensitas penjualan. Dengan strategi pemasaran yang berhubungan dengan trend dan habit maka produk yang dijual akan lebih mudah diterima oleh pelanggan.

Sumber : https://dergipark.org.tr/en/download/article-file/3136104

## Data Overview

Dataset : Customer Shopping Dataset - Retail Sales Data

Dataset berasal dari informasi penjualan dari 10 mall dari tahun 2021 hingga 2023. Data dikumpulkan dari umur dan jenis kelamin yang beragam untuk memberikan pandangan terhadap habit pembelian di Istanbul. Data ini dapat digunakan untuk memdapatkan insight dalam tren dan kebiasaan dalam pembelian di Istanbul.


Column | Data Type | Explanation|
--------|-----------|-----------|
invoice_no | Integer | Invoice number. |
customer_id | Integer | Customer number. |
gender | String | Customer gender. |
age | Integer | Customer age. |
category | String | The category of the purchased product. |
quantity | Integer | The quantities of each product (item) per transaction. |
price | Float | Product price per unit in Turkish Liras (TL). |
payment_method | String | The payment method (cash, credit card or debit card) used for the transaction. |
invoice_date | String | The day when a transaction was generated. |
shopping_mall | String | The name of the shopping mall where the transaction was made. |

Sumber : https://www.kaggle.com/datasets/mehmettahiraslan/customer-shopping-dataset

## Kesimpulan

Dari analisis yang telah dilakukan maka dapat disimpulkan bahwa strategi penjualan dalam 3 bulan akan dilakukan dari bulan februari hingga mei. Dimana pada strategi penjualan ini akan berfokus pada 3 kategori yang memiliki total sales terbesar yaitu 'Clothing', 'Shoes' dan 'Technology' yang akan menargetkan kategori usia 'Dewasa Akhir' yang memiliki jumlah pembelian terbanyak setiap tahunnya dengan harga produk untuk setiap kategori yang berkorelasi negatif lemah. Lalu dengan lebih menargetkan penggunaan cara pembayaran cash dan credit card. Maka dalam 3 bulan dari bulan februari hingga mei dapat mencapai peningkatan sebanyak 11.1% sampai 20.82% dimana perkiraan tengahnya adalah 15,96%. Dengan perkiraan setiap transaksi dalam interval ₺2,502.5472289772524 sampai ₺2,555.0313074756878.

## Rekomendasi Bisnis

Rekomendasi yang dapat dilakukan:
1. Cash Promotions
    - Menambah promosi dengan minimum total belanja(₺2,500) dengan pembayaran tunai.
2. Clothes Promotions
    - Membuat promosi pada setiap bulan dari bulan februari sampai mei karena 'Clothing' menjadi penjualan terbesar pada transaksi.
3. Shoes Promotions
    - Membuat promosi pembelian lebih dari 1 sepatu dari bulai februari sampai mei.
4. Technology Promotions
    - Membuat promosi penjualan teknologi atau pameran teknologi pada bulan ferbuari sampai mei.