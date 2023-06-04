# Analisis Sentimen Coldplay di Indonesia Menggunakan PySpark

Analisis sentimen melibatkan penggunaan teknik pemrosesan bahasa atau NLP untuk memahami kata - kata dari kalimat yang diinputkan sehingga teks dapat diklasifikasikan yang umumnya menjadi positif, negatif, atau netral. Pada studi kasus ini, digunakan teknik web scraping dari youtube terhadap komentar 5 video yang berkaitan dengan konser Coldplay yang akan diadakan di Indonesia mendatang. Tujuannya adalah untuk melihat antusiasme masyarakat Indonesia dengan adanya kedatangan Coldplay di Indonesia.

komentar akan dibagi menjadi 3 kategori setelah melalui process pre-processing dan labelling yaitu positif, negatif, netral. Kemudian data komentar awal akan di-splitting dengan rasio 7:3 sebagai data training dan data testing. Dalam pemodelannya, digunakan teknik logistic regression dan melakukan evaluasi dengan melihat berapa banyak prediksi yang sesuai dengan labellingnya.
