<h2><b>Simple & Multiple Regression Models (Supervised)
Regularized Regression in Python</b></h2>

<b>Process Detail:</b>

<b>Pendahuluan:</b>
Anda akan menerapkan regresi teratur untuk memprediksi harga perumahan di Boston.

<b>Dataset:</b> boston.csv
Data tersebut tentang prediksi harga rumah (medv) di kota Boston, fitur:
- Criminal rate (crim)
- Residential land zoned proportion (zn)
- Non-retail business acres proportion (indus)
- Is bounds with river (chas)
- Nitrogen oxides concentration (nox)
- Number rooms average (rm)
- Owner age proportion (age)
- Weighted distance to cities (dis)
- Accessibility index (rad)
- Tax rate (tax)
- Pupil-teacher ratio (ptratio)
- Black proportion (black)
- Percent lower status (lstat)

<b>Persiapan Data:</b> 
Pisahkan data menjadi set pelatihan, validasi, dan pengujian.

<b>Analisis Korelasi dan Seleksi Fitur:</b> 
Buat plot korelasi pada data pelatihan dan lakukan seleksi fitur pada fitur yang sangat berkorelasi.

<b>Pelatihan Model:</b> 
lambdas = [0.01, 0.1, 1, 10]
Latih model Ridge regression dan LASSO pada data pelatihan dengan beberapa nilai lambda yang diberikan.
Pilih nilai lambda terbaik dari set validasi menggunakan RMSE sebagai metrik.

<b>Interpretasi Model:</b> 
Interpretasikan sampel koefisien dari model terbaik yang dipilih.

<b>Evaluasi Model:</b> 
Evaluasi model terbaik pada set pengujian menggunakan MAE, MAPE, dan RMSE.
Sertakan interpretasi dari hasil evaluasi.

