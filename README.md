# Sentimen_Analyst_Lazada_Review
Sebuah kata yang kita tulis pastinya memiliki sebuah makna dan emosi yang tersirat, seperti halnya kita menuliskan review pada sebuah produk yang kita beli melalui e-commerce. Review pelanggan terhadap produk yang dijual sangat berguna sekali bagi pelaku bisnis untuk mengevaluasi produk kita agar kedepannya produk-produk yang kita jual dapat lebih baik lagi dan dapat meningkatkan penjualannya. 
cara kita agar bisa memahami review dari pelanggan memiliki makna positif, netral atau negatif di sebut dengan proses sentiment analysis.
### apasih sentimen analisis itu?

Sentiment analysis and opinion mining is the field of study that analyzes people's opinions, sentiments, evaluations, attitudes, and emotions from written language. 

berdasarkan kutipan diatas, sentimen analysis adalah bidang studi yang menganalisis opini, sentimen, evaluasi, sikap, dan emosi orang dari bahasa tertulis.
sedangkan menurut [MongkeyLearn](https://monkeylearn.com/sentiment-analysis/) sentiment analysis adalah proses memahami dan mendeteksi emosi (positif, negatif, dan netral) yang terdapat dalam tulisan menggunakan teknik analisis teks.
### Tipe - Tipe Sentimen analysis
Dalam artikel ini penulis akan menggunakan sentiment analysis tipe Fine - grained sentiment analysis karena data yang akan saya ambil dari situs kaggle berupa data review salah satu e-commerce Lazada, Apa itu tipe sentimen analysis Fine - grained dan tipe sentimen analysis lainya dapat dilihat dari penjelasan dibawah ini. 
1. Fine - grained sentiment analysis

Fine-grained sentiment analysis adalah tipe analisis yang memiliki penilaian spesifik. Tipe ini memungkinkan kamu memiliki range penilaian yang lebar. tipe sentiment analysis ini sering digunakan pada review e-commerce berupa nilai bintang. kita dapat mengkonversikan bintang dalam review menjadi sebuah sentimen seperti berikut ini
   - bintang 5 = Sangat positif,
   - bintang 4 = Positif,
   - bintang 3 = Netral,
   - bintang 2 = Negatif,
   - bintang 1 = Sangat negatif

atau bisa di sederhanakan menjadi 
   - bintang 4&5 = positif,
   - bintang 3   = Netral,
   - bintang 2&1 = Negatif

2. Emotion detection

sentimen emotion detection bertujuan untuk mendeteksi emosi, seperti kebahagiaan, kemarahan, kesedihan, dan frustrasi. kelemahan dari sentimen ini adalah pengekspresian emosi setiap orang dapat berbeda-beda.

contohnya akhir-akhir ini banyak influencer dalam mengiklankan sebuah makanan mengatakan "parah, Makanan ini enak banget seperti mau meninggal" sebenarnya jika dilihat secara menyeluruh makna dari kalimat tersebut adalah positif, akan tetapi karena mesin mendeteksi kata "parah" dan "meninggal" sebagai makna negatif maka bisa jadi kalimat tersebut dibaca mesin sebagai sentimen negatif

3. Aspect-based sentiment analysis

Aspect-based sentiment analysis biasanya digunakan pada ulasan produk, Anda ingin mengetahui aspek atau fitur tertentu yang disebutkan orang secara positif, netral, atau negatif.
<br>misal dalam review produk pelanggaan memberikan komentar "Masa pakai baterai kamera ini terlalu pendek", klasifikasi berbasis aspek akan dapat menentukan bahwa kalimat tersebut mengungkapkan pendapat negatif tentang masa pakai baterai fitur.

4. multilingual sentiment analysis

Analisis sentimen multilingual dimanfaatkan untuk menganalisis kata-kata dalam berbagai bahasa.ipe analisis yang satu ini terbilang cukup sulit karena kamu harus memiliki daftar kata dari bermacam bahasa.
Selain itu, kamu harus terus meng-update daftar tersebut sesuai perkembangan bahasa. [2][3]

### bagaimana caranya melakukan sentimen analysis?

Sentimen analysis berfungsi karena natural language processing (NLP) dan machine learning algorithms, untuk secara otomatis menentukan nada emosional di balik percakapan online.

machine learning adalah subbidang dari kecerdasan buatan (AI) yang memungkinkan komputer untuk belajar melakukan tugas dan meningkatkan kinerja dari waktu ke waktu tanpa diprogram secara eksplisit. Ada sejumlah algoritme penting yang membantu mesin membandingkan data, menemukan pola, atau belajar dengan coba-coba untuk pada akhirnya menghitung prediksi yang akurat tanpa campur tangan manusia.