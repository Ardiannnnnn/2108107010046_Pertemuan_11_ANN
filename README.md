Tugas3-Machine-Learning-2108107010046
Dataset regresi : Dataset Tanaman Padi Sumatera, Indonesia Link dataset : https://www.kaggle.com/datasets/ardikasatria/datasettanamanpadisumatera

About dataset regresi: Pulau Sumatera mempunyai lebih dari 50 persen lahan pertanian setiap provinsinya dengan komoditas pangan utama paling dominan adalah padi, sedangkan sisanya adalah jagung, kacang tanah, dan ubi. Hasil pertanian di Sumatera sangat rentan terhadap perubahan iklim karena dapat memengaruhi pola tanam, waktu tanam, produksi dan kualitas hasil. Perubahan iklim dapat memberikan dampak negatif terhadap produksi bahan pokok tersebut. Apalagi bertambahnya suhu bumi akibat dampak dari pemanasan global yang akan mempengaruhi pola presipitasi, evaporasi, water-run off, kelembaban tanah, dan variasi iklim yang sangat fluktuatif secara keseluruhan dapat mengancam keberhasilan hasil produksi pertanian. Prediksi hasil pertanian komoditas bahan pangan banyak dipengaruhi oleh perubahan cuaca (climate change). Untuk mendukung Sustainable Development Goals dunia, kita sebagai data scientist perlu membangun model prediktif dari masalah yang disebutkan. Regresi yang digunakan adalah metode supervised learning dari decision tree dan Artificial neural network.

Pengambilan data diperoleh melalui website BPS pada kategori tanaman pangan utama dari 8 provinsi di pulau Sumatera yaitu Nanggroe Aceh Darussalam (NAD), Sumatera Utara, Riau, Jambi, Sumatera Selatan, Bengkulu dan Lampung. Data yang digunakan adalah data dari tahun 1993 hingga tahun 2020 untuk dataset padi. Data memuat hasil produksi tahunan dan luas panen atau luas lahan. Kemudian data perubahan cuaca diperoleh melalui website BMKG untuk data harian curah hujan, kelembapan, dan temperatur rata-rata atau suhu rata-rata dari tahun 1993 hingga tahun 2020.

Silahkan bangun model regresi dengan machine learning untuk memprediksi produksi padi di pulau Sumatera.

Dataset klasifikasi : Obesity Classification Dataset Link Dataset : https://www.kaggle.com/datasets/sujithmandala/obesity-classification-dataset/data

About dataset klasifikasi: This dataset contains information about the obesity classification of individuals. The data was collected from a variety of sources, including medical records, surveys, and self-reported data. The dataset includes the following columns:

ID: A unique identifier for each individual Age: The age of the individual Gender: The gender of the individual Height: The height of the individual in centimeters Weight: The weight of the individual in kilograms BMI: The body mass index of the individual, calculated as weight divided by height squared Label: The obesity classification of the individual, which can be one of the following: Normal Weight Overweight Obese Underweight

Regresi
Menyiapkan library yang diperlukan
Melakukan preprocessing
Menerapkan metode klasifikasi menggunakan ANN
Melihat akurasi
Menampilkan consusion matrix

pada model yang dikerjakan kali ini pada saat melakukan regresi terdapat perbedaan hasil akurasi dengan menggunakan metode SVM pada tugas sebelumnya dengan menggunakan metode ANN pada tugas kali ini, dimana
Hasil akurasi dari metode SVM untuk regresi adalah sbb:

Mean Absolute Error: 190296.43555101554
Mean Squared Error: 66385108025.07722
Root Mean Squared Error: 257653.0768787309

sedangkan menggunakan metode ANN untuk regresi adalah sbb:

Mean Absolute Error: 248549.25980555557
Mean Squared Error: 127479596436.43893
Root Mean Squared Error: 357042.8495803255

Dari ketiga metode tersebut dapat dilihat SVM menghasilkan nilai yang lebih kecil dari pada ANN yang mana hasil yang bagus untuk regresi adalah ketiga error yang didapatkan semakin kecil

Klasifikasi
Menyiapkan library yang diperlukan
Melakukan preprocessing
Menerapkan metode Regresi menggunakan ANN
Melihat akurasi MEA
Menampilkan visualisasi

pada model yang dikerjakan kali ini pada saat melakukan klasifikasi terdapat perbedaan hasil akurasi dengan menggunakan metode SVM pada tugas sebelumnya dengan menggunakan metode ANN pada tugas kali ini, dimana
Hasil akurasi dari metode SVM untuk klasifikasi adalah sbb: 

Model accuracy score with default hyperparameters: 0.6818
Model accuracy score with rbf kernel and C=100.0 : 0.9091

sedangkan menggunakan metode ANN untuk klasifikasi adalah sbb:
Epoch 99/100
8/8 [==============================] - 0s 7ms/step - loss: 0.4076 - accuracy: 0.8400 - val_loss: 0.4879 - val_accuracy: 0.7273
Epoch 100/100
8/8 [==============================] - 0s 7ms/step - loss: 0.4034 - accuracy: 0.8400 - val_loss: 0.4829 - val_accuracy: 0.7273

Jadi saat menggunakan metode SVM dengan dengan parameter default maka ANN mendapatkan akurasi yang lebih tinggi dari pada SVM namun saat memberikan nilai kepada parameter C = 100, akurasi dari metode SVM lebih tinggi dibandingkan dengan metode ANN

















