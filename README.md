# Analisis-Sentiment-Linkedin-Singapura-dengan-Algoritma-Naive-Bayes-Support-Vector-Machine-LSTM-
Analisis-Sentiment-Lexicon-Based-Linkedin-Singapura-dengan-Algoritma-Naive-Bayes-Support-Vector-Machine-LSTM 



## Abstrak: 
Penelitian ini bertujuan untuk menganalisis sentimen pengguna Android terhadap suatu aplikasi di Google Play Store, menggunakan tiga metode klasifikasi berbeda: Naive Bayes, Support Vector Machine (SVM), dan Long Short-Term Memory (LSTM). Data yang digunakan berupa ulasan pengguna di Google Play Store. Pada penelitian ini, teks ulasan diolah menggunakan representasi TF-IDF dan metode pembelajaran mesin serta deep learning diterapkan untuk memprediksi sentimen apakah termasuk ke dalam kelas positif, netral, atau negatif. Berdasarkan hasil evaluasi, model Naive Bayes dan LSTM memberikan akurasi yang sama sebesar 93.44%, sedangkan model SVM sedikit lebih rendah dengan akurasi 93.15%. Hal ini menunjukkan bahwa baik model Naive Bayes maupun LSTM sama-sama efektif dalam mengklasifikasikan sentimen ulasan pengguna, dengan sentimen positif lebih dominan dibandingkan sentimen negatif atau netral.

Dari hasil evaluasi terhadap tiga model yang digunakan untuk klasifikasi sentimen, dapat disimpulkan sebagai berikut:

## Naive Bayes:
![naive bayes](https://github.com/user-attachments/assets/26ba427a-33db-466c-87fa-e96f5bdabafc)
Akurasi: 0.934
Model ini menunjukkan performa yang sangat baik dengan akurasi yang cukup tinggi, yaitu 93.44%. Naive Bayes, sebagai model probabilistik, seringkali bekerja dengan baik dalam tugas klasifikasi teks seperti sentimen karena asumsi independensi antar fitur.
Support Vector Machine (SVM):

## Support Vector Machines :
![confusion matrix linkedin sg](https://github.com/user-attachments/assets/6c190483-1008-416b-b172-c298f40bbc5e)
Akurasi: 0.931
Model SVM memberikan hasil akurasi sebesar 93.15%, sedikit di bawah Naive Bayes. Meskipun demikian, SVM dikenal sebagai model yang kuat dan mampu menangani data dengan dimensi tinggi seperti data teks dengan representasi TF-IDF.


## LSTM (Long Short-Term Memory):
![lstm](https://github.com/user-attachments/assets/78ad038b-75af-4837-8bd1-18ce279e3c29)

Akurasi: 0.934
Model LSTM, yang merupakan model berbasis jaringan saraf tiruan untuk pemrosesan sekuensial, memiliki akurasi yang sama dengan Naive Bayes, yaitu 93.44%. LSTM bekerja baik dalam menangkap konteks dan urutan kata dalam teks, yang membantu dalam memahami sentimen.
Kesimpulan Utama:
Naive Bayes dan LSTM memberikan akurasi tertinggi yang sama, yaitu 93.44%. Hal ini menunjukkan bahwa kedua model ini efektif untuk tugas klasifikasi sentimen pada dataset yang digunakan.
SVM juga memiliki akurasi yang kompetitif, hanya terpaut sedikit dari dua model lainnya dengan akurasi sebesar 93.15%.
Secara keseluruhan, semua model menunjukkan performa yang baik dengan akurasi di atas 93%. Pilihan model terbaik dapat tergantung pada aspek lain seperti waktu pelatihan, interpretasi, dan sumber daya komputasi yang tersedia.


