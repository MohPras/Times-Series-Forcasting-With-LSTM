# Times Series Forcasting Untuk Memprediksi Produksi Susu 12 Bulan Terahir Menggunakan peramalan deret waktu jaringan saraf LSTM (Long short term memory) dengan python.

LSTM adalah varian dari RNN (jaringan saraf berulang) dan banyak digunakan untuk proyek deret waktu dalam peramalan dan prediksi masa depan. Dataset yang ada digunakan dalam latihan ini berasal dari github nachi-hebbar ( https://github.com/nachi-hebbar/Time-Series-Forecasting-LSTM/blob/main/monthly_milk_production.csv ).

Dalam kasus ini masalah yang diambil yaitu memprediksi produksi susu 12 bulan terahir untuk menentukan prediksi susu pada bulan berikutnya menggunakan LSTM.
Berdasarkan percobaan model memiliki skor RMSE: 15 (menggunakan spliitng smeua data kecuali 12 terahir) untuk dan 23 (menggunakan spiliting data 80:20) untuk pelatihan dan pengujian. Hasil tersebut menunjukkan bahwa dimungkinkan untuk menggunakan spliting data pertama untuk digunakan sebagai data untuk melakukan fortasting. Dalam projek ini masih banyak terdapat kesalahan karena keterbatasan ilmu juga pengalaman yang belum banyak, Terimakasih.
