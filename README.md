### Daftar Dataset
1. [Dataset sentimen Twitter layanan telekomunikasi Indonesia](#analisis-sentimen-tingkat-kepuasan-pengguna-penyedia-layanan-telekomunikasi-seluler-indonesia-pada-twitter-dengan-metode-support-vector-machine-dan-lexicon-based-features "Dataset sentimen Twitter layanan telekomunikasi Indonesia")
2. [Dataset sentimen komentar Instagram Cyberbullying](#analisis-sentimen-cyberbullying-pada-komentar-instagram-dengan-metode-klasifikasi-support-vector-machine "Dataset sentimen komentar Instagram Cyberbullying")

------------

### Analisis Sentimen Tingkat Kepuasan Pengguna Penyedia Layanan Telekomunikasi Seluler Indonesia Pada Twitter Dengan Metode Support Vector Machine dan Lexicon Based Features

**Abstrak**

Analisis sentimen adalah salah satu cabang penelitian dari Text Mining yang berguna untuk mengklasifikasi dokumen teks berupa opini berdasarkan sentimen. Dokumen teks yang digunakan dalam penelitian berasal Twitter tentang opini masyarakat mengenai penyedia layanan telekomunikasi seluler. Metode yang digunakan adalah Support Vector Machine dengan menggunakan Lexicon Based Features sebagai pembaharuan fiturnya selain memakai fitur TF-IDF. Data yang digunakan pada penelitian ini sebanyak 300 data yang dibagi menjadi dua jenis data dengan perbandingan 70% untuk data latih dan 30% untuk data uji. Hasil akurasi sistem yang diperoleh dari analisis sentimen dengan metode Support Vector Machine dan Lexicon Based Features sebesar 79% menggunakan nilai degree sebesar 2, nilai konstanta learning rate 0,0001, serta jumlah iterasi maksimum sebanyak 50 kali. Sedangkan sistem analisis sentimen tanpa menggunakan Lexicon Based Features menghasilkan tingkat akurasi sebesar 84% dengan nilai parameter yang sama.

**Download Artikel (Paper):** [PDF](http://j-ptiik.ub.ac.id/index.php/j-ptiik/article/view/628/246 "PDF") | 
**Dataset:**
[dataset_tweet_sentiment_cellular_service_provider.csv ](https://github.com/rizalespe/Indonesian-Sentiment-Analysis-Dataset/blob/master/dataset_tweet_sentiment_cellular_service_provider.csv "dataset_tweet_sentiment_cellular_service_provider.csv ")

Detail: Dataset analisis sentimen dikumpulkan dari situs jejaring sosial Twitter terkait dengan sentimen masyarakat terhadap penyedia layanan seluler di Indonesia sejumlah 300 tweet. Dataset memiliki 2 kelas sentimen yaitu `positive` dan `negative`. Sebelum dipublikasikan, dataset ini telah kami lakukan beberapa praproses sebagai berikut:
- Mengganti nama/identitas penyedia layanan dengan tag `<PROVIDER_NAME>`
- Mengganti alamat URL dengan tag `<URL>`
- Mengganti @mention pengguna dengan tag `<USER_MENTION>`
- Mengganti nama produk dengan tag `<PRODUCT_NAME>`


>**Dataset ini tersedia untuk penggunaan pribadi, tetapi jika Anda ingin mempublikasikan artikel ilmiah, publikasi jurnal, atau seminar dengan menggunakan dataset ini, maka Anda harus mengutip publikasi di bawah ini:**


Rofiqoh, U., Perdana, R.S., & Fauzi, M.A. (2017). Analisis Sentimen Tingkat Kepuasan Pengguna Penyedia Layanan Telekomunikasi Seluler Indonesia Pada Twitter Dengan Metode Support Vector Machine dan Lexicon Based Features. Jurnal Pengembangan Teknologi Informasi Dan Ilmu Komputer, 1(12), 1725-1732. Diambil dari http://j-ptiik.ub.ac.id/index.php/j-ptiik/article/view/628

------------
### Analisis Sentimen Cyberbullying pada Komentar Instagram dengan Metode Klasifikasi Support Vector Machine

**Abstrak**

Instagram merupakan media sosial yang paling populer pada zaman sekarang. Pengguna yang dimulai dari anak-anak, remaja hingga orang dewasa turut mendongkrak popularitas Instagram. Namun, media sosial ini tidak lepas dari bahaya cyberbullying yang sering dilakukan oleh pengguna khususnya pada kolom komentar.  Dengan data statistik yang telah didapatkan, bahwa 42% remaja berusia 12-20 tahun telah menjadi korban cyberbullying. Bahaya cyberbullying tentunya meresahkan banyak orang dikarenakan dampak yang ditimbulkan, maka dari itu dapat dilakukan suatu analisis sentimen pada kolom komentar Instagram yang berupaya untuk mengetahui sentimen dari setiap komentar. Analisis sentimen merupakan suatu cabang ilmu dari text mining yang digunakan untuk mengekstrak, memahami, dan mengolah data teks. Untuk mengetahui setiap sentimen pada komentar digunakan fitur Term Frequency-Inverse Document Frequency (TF-IDF) dan metode klasifikasi Support Vector Machine (SVM). Dokumen yang berisi 400 data yang diambil secara luring (offline) dengan total fitur 1799. Dokumen komentar dibagi menjadi 70% data latih dan 30% data uji. Berdasarkan pengujian yang dilakukan didapatkan parameter terbaik pada metode SVM yaitu dengan nilai degree kernel polynomial sebesar 2, nilai learning rate sebesar 0,0001, dan jumlah iterasi maksimum yang digunakan adalah 200 kali. Dari pengujian tersebut didapatkan hasil akurasi tertinggi sebesar 90% pada komposisi data latih 50% dan komposisi data uji 50%.

**Download Artikel (Paper):** [PDF](http://j-ptiik.ub.ac.id/index.php/j-ptiik/article/view/3051/1195 "PDF") | 
**Dataset:**
[dataset_komentar_instagram_cyberbullying.csv](https://github.com/rizalespe/Dataset-Sentimen-Analisis-Bahasa-Indonesia/blob/master/dataset_komentar_instagram_cyberbullying.csv "dataset_komentar_instagram_cyberbullying.csv")

Detail: Dataset analisis sentimen dikumpulkan dari komentar sosial media Instagram dan dilabeli secara manual dengan label "positive" dan "negative". Jumlah total dataset terdapat 400 komentar dengan pembagian masing-masing kelas label sejumlah 200 komentar. Sebelum dipublikasikan, dataset ini telah kami lakukan beberapa praproses sebagai berikut:
- Mengganti setiap username (`@username`) yang ada di teks komentar dengan tag `<USERNAME>`. Kode regular expression untuk mendeteksi kemunculan username adalah:
``` 
(?<=^|(?<=[^a-zA-Z0-9-_\.]))@([A-Za-z]+[A-Za-z0-9-_]+) 
```


>**Dataset ini tersedia untuk penggunaan pribadi, tetapi jika Anda ingin mempublikasikan artikel ilmiah, publikasi jurnal, atau seminar dengan menggunakan dataset ini, maka Anda harus mengutip publikasi di bawah ini:**


Luqyana, W., Cholissodin, I., & Perdana, R.S. (2018). Analisis Sentimen Cyberbullying pada Komentar Instagram dengan Metode Klasifikasi Support Vector Machine. Jurnal Pengembangan Teknologi Informasi Dan Ilmu Komputer, 2(11), 4704-4713. Diambil dari http://j-ptiik.ub.ac.id/index.php/j-ptiik/article/view/3051

------------
