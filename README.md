### Daftar Dataset
1. [Dataset sentimen Twitter Pilkada DKI 2017](#analisis-sentimen-tentang-opini-pilkada-dki-2017-pada-dokumen-twitter-berbahasa-indonesia-menggunakan-naïve-bayes-dan-pembobotan-emoji "Dataset sentimen Twitter Pilkada DKI 2017")
2. [Dataset sentimen Twitter layanan telekomunikasi Indonesia](#analisis-sentimen-tingkat-kepuasan-pengguna-penyedia-layanan-telekomunikasi-seluler-indonesia-pada-twitter-dengan-metode-support-vector-machine-dan-lexicon-based-features "Dataset sentimen Twitter layanan telekomunikasi Indonesia")
3. [Dataset sentimen komentar Instagram Cyberbullying](#analisis-sentimen-cyberbullying-pada-komentar-instagram-dengan-metode-klasifikasi-support-vector-machine "Dataset sentimen komentar Instagram Cyberbullying")
4. [Dataset sentimen Twitter tayangan televisi](#analisis-sentimen-terhadap-tayangan-televisi-berdasarkan-opini-masyarakat-pada-media-sosial-twitter-menggunakan-metode-k-nearest-neighbor-dan-pembobotan-jumlah-retweet "Dataset sentimen Twitter tayangan televisi")
5. [Dataset sentimen Twitter opini film](#analisis-sentimen-tentang-opini-film-pada-dokumen-twitter-berbahasa-indonesia-menggunakan-naive-bayes-dengan-perbaikan-kata-tidak-baku "Dataset sentimen Twitter opini film")

------------
### Analisis Sentimen Tentang Opini Pilkada DKI 2017 Pada Dokumen Twitter Berbahasa Indonesia Menggunakan Naïve Bayes dan Pembobotan Emoji


>**Dataset ini tersedia untuk penggunaan pribadi, tetapi jika Anda ingin mempublikasikan artikel ilmiah, publikasi jurnal, atau seminar dengan menggunakan dataset ini, maka Anda harus mengutip publikasi di bawah ini:**

Lestari, A.R.T., Perdana, R.S., & Fauzi, M.A. (2017). Analisis Sentimen Tentang Opini Pilkada DKI 2017 Pada Dokumen Twitter Berbahasa Indonesia Menggunakan Naïve Bayes dan Pembobotan Emoji. Jurnal Pengembangan Teknologi Informasi Dan Ilmu Komputer, 1(12), 1718-1724. Diambil dari http://j-ptiik.ub.ac.id/index.php/j-ptiik/article/view/627


**Abstrak**

Analisis sentimen merupakan cabang dari text mining, fokus utamanya adalah menganalisa dokumen teks. Dokumen teks terkadang mengandung unsur non-tekstual, salah satunya emoji. Emoji merupakan simbol grafis Unicode berupa gambar untuk mengekspresikan perasaan seseorang. Algoritme yang digunakan dalam penelitian ini adalah Naïve Bayes dengan pembaharuan berupa penambahan pembobotan non-tekstual (emoji). Hasil dari pembobotan tekstual dan non tekstual yang dinormalisasi dengan metode Min-max digabungkan disertai nilai konstanta tertentu sehingga menghasilkan sentimen positif maupun negatif. Data diambil dari Twitter tentang Pilkada DKI 2017 sebanyak 900 data tweet. Dari hasil pengujian akurasi, diperoleh 68,52% untuk kondisi pembobotan tekstual, 75,93% untuk pembobotan non-tesktual, dan 74,81% untuk kondisi penggabungan dengan nilai konstanta 0,5 untuk tekstual dan 0,5 untuk non-tekstual. Dari hasil pengujian pengaruh pembobotan non-tesktual disimpulkan bahwa pembobotan non-tekstual berpengaruh terhadap akurasi dan pengklasifikasian, dengan komposisi konstanta pengali terbaik ketika α=0,4 dan β=0,6 sampai dengan α=0,1 dan β=0,9.

**Download Artikel (Paper):** [PDF](http://j-ptiik.ub.ac.id/index.php/j-ptiik/article/view/627/245 "PDF")

**Dataset:**
[dataset_tweet_sentiment_pilkada_DKI_2017.csv ](https://github.com/rizalespe/Dataset-Sentimen-Analisis-Bahasa-Indonesia/blob/master/dataset_tweet_sentiment_pilkada_DKI_2017.csv "dataset_tweet_sentiment_pilkada_DKI_2017.csv ")

Detail: Dataset analisis sentimen dikumpulkan dari situs jejaring sosial Twitter terkait dengan pelaksanaan Pemilihan Gubernur DKI Jakarta Tahun 2017 sejumlah 900 dokumen tweet dari 3 pasangan calon yaitu Agus-Sylvi, Ahok-Djarot, & Anies-Sandi. Dataset memiliki 2 kelas sentimen yaitu `positive` dan `negative`. Sebelum dipublikasikan, dataset ini telah kami lakukan preproses sebagai berikut:
- Mengganti emoticon yang ada dengan tag/penanda spesial seperti pada file [Master Emoji](https://github.com/rizalespe/Dataset-Sentimen-Analisis-Bahasa-Indonesia/blob/master/master_emoji.csv "Master Emoji")
- Pada penelitian ini, kami menghapus kata-kata yang terdapat pada file [Stopword](https://github.com/rizalespe/Dataset-Sentimen-Analisis-Bahasa-Indonesia/blob/master/stopword_tweet_pilkada_DKI_2017.csv "Stopword")

------------

### Analisis Sentimen Tingkat Kepuasan Pengguna Penyedia Layanan Telekomunikasi Seluler Indonesia Pada Twitter Dengan Metode Support Vector Machine dan Lexicon Based Features


>**Dataset ini tersedia untuk penggunaan pribadi, tetapi jika Anda ingin mempublikasikan artikel ilmiah, publikasi jurnal, atau seminar dengan menggunakan dataset ini, maka Anda harus mengutip publikasi di bawah ini:**

Rofiqoh, U., Perdana, R.S., & Fauzi, M.A. (2017). Analisis Sentimen Tingkat Kepuasan Pengguna Penyedia Layanan Telekomunikasi Seluler Indonesia Pada Twitter Dengan Metode Support Vector Machine dan Lexicon Based Features. Jurnal Pengembangan Teknologi Informasi Dan Ilmu Komputer, 1(12), 1725-1732. Diambil dari http://j-ptiik.ub.ac.id/index.php/j-ptiik/article/view/628


**Abstrak**

Analisis sentimen adalah salah satu cabang penelitian dari Text Mining yang berguna untuk mengklasifikasi dokumen teks berupa opini berdasarkan sentimen. Dokumen teks yang digunakan dalam penelitian berasal Twitter tentang opini masyarakat mengenai penyedia layanan telekomunikasi seluler. Metode yang digunakan adalah Support Vector Machine dengan menggunakan Lexicon Based Features sebagai pembaharuan fiturnya selain memakai fitur TF-IDF. Data yang digunakan pada penelitian ini sebanyak 300 data yang dibagi menjadi dua jenis data dengan perbandingan 70% untuk data latih dan 30% untuk data uji. Hasil akurasi sistem yang diperoleh dari analisis sentimen dengan metode Support Vector Machine dan Lexicon Based Features sebesar 79% menggunakan nilai degree sebesar 2, nilai konstanta learning rate 0,0001, serta jumlah iterasi maksimum sebanyak 50 kali. Sedangkan sistem analisis sentimen tanpa menggunakan Lexicon Based Features menghasilkan tingkat akurasi sebesar 84% dengan nilai parameter yang sama.

**Artikel (Paper):** [PDF](http://j-ptiik.ub.ac.id/index.php/j-ptiik/article/view/628/246 "PDF")

**Dataset:**
[dataset_tweet_sentiment_cellular_service_provider.csv ](https://github.com/rizalespe/Indonesian-Sentiment-Analysis-Dataset/blob/master/dataset_tweet_sentiment_cellular_service_provider.csv "dataset_tweet_sentiment_cellular_service_provider.csv ")

Detail: Dataset analisis sentimen dikumpulkan dari situs jejaring sosial Twitter terkait dengan sentimen masyarakat terhadap penyedia layanan seluler di Indonesia sejumlah 300 tweet. Dataset memiliki 2 kelas sentimen yaitu `positive` dan `negative`. Sebelum dipublikasikan, dataset ini telah kami lakukan beberapa praproses sebagai berikut:
- Mengganti nama/identitas penyedia layanan dengan tag `<PROVIDER_NAME>`
- Mengganti alamat URL dengan tag `<URL>`
- Mengganti @mention pengguna dengan tag `<USER_MENTION>`
- Mengganti nama produk dengan tag `<PRODUCT_NAME>`

------------
### Analisis Sentimen Cyberbullying pada Komentar Instagram dengan Metode Klasifikasi Support Vector Machine


>**Dataset ini tersedia untuk penggunaan pribadi, tetapi jika Anda ingin mempublikasikan artikel ilmiah, publikasi jurnal, atau seminar dengan menggunakan dataset ini, maka Anda harus mengutip publikasi di bawah ini:**

Luqyana, W., Cholissodin, I., & Perdana, R.S. (2018). Analisis Sentimen Cyberbullying pada Komentar Instagram dengan Metode Klasifikasi Support Vector Machine. Jurnal Pengembangan Teknologi Informasi Dan Ilmu Komputer, 2(11), 4704-4713. Diambil dari http://j-ptiik.ub.ac.id/index.php/j-ptiik/article/view/3051


**Abstrak**

Instagram merupakan media sosial yang paling populer pada zaman sekarang. Pengguna yang dimulai dari anak-anak, remaja hingga orang dewasa turut mendongkrak popularitas Instagram. Namun, media sosial ini tidak lepas dari bahaya cyberbullying yang sering dilakukan oleh pengguna khususnya pada kolom komentar.  Dengan data statistik yang telah didapatkan, bahwa 42% remaja berusia 12-20 tahun telah menjadi korban cyberbullying. Bahaya cyberbullying tentunya meresahkan banyak orang dikarenakan dampak yang ditimbulkan, maka dari itu dapat dilakukan suatu analisis sentimen pada kolom komentar Instagram yang berupaya untuk mengetahui sentimen dari setiap komentar. Analisis sentimen merupakan suatu cabang ilmu dari text mining yang digunakan untuk mengekstrak, memahami, dan mengolah data teks. Untuk mengetahui setiap sentimen pada komentar digunakan fitur Term Frequency-Inverse Document Frequency (TF-IDF) dan metode klasifikasi Support Vector Machine (SVM). Dokumen yang berisi 400 data yang diambil secara luring (offline) dengan total fitur 1799. Dokumen komentar dibagi menjadi 70% data latih dan 30% data uji. Berdasarkan pengujian yang dilakukan didapatkan parameter terbaik pada metode SVM yaitu dengan nilai degree kernel polynomial sebesar 2, nilai learning rate sebesar 0,0001, dan jumlah iterasi maksimum yang digunakan adalah 200 kali. Dari pengujian tersebut didapatkan hasil akurasi tertinggi sebesar 90% pada komposisi data latih 50% dan komposisi data uji 50%.

**Artikel (Paper):** [PDF](http://j-ptiik.ub.ac.id/index.php/j-ptiik/article/view/3051/1195 "PDF")

**Dataset:**
[dataset_komentar_instagram_cyberbullying.csv](https://github.com/rizalespe/Dataset-Sentimen-Analisis-Bahasa-Indonesia/blob/master/dataset_komentar_instagram_cyberbullying.csv "dataset_komentar_instagram_cyberbullying.csv")

Detail: Dataset analisis sentimen dikumpulkan dari komentar sosial media Instagram dan dilabeli secara manual dengan label "positive" dan "negative". Jumlah total dataset terdapat 400 komentar dengan pembagian masing-masing kelas label sejumlah 200 komentar. Sebelum dipublikasikan, dataset ini telah kami lakukan beberapa praproses sebagai berikut:
- Mengganti setiap username (`@username`) yang ada di teks komentar dengan tag `<USERNAME>`. Kode regular expression untuk mendeteksi kemunculan username adalah:
``` 
(?<=^|(?<=[^a-zA-Z0-9-_\.]))@([A-Za-z]+[A-Za-z0-9-_]+) 
```

------------
### Analisis Sentimen Terhadap Tayangan Televisi Berdasarkan Opini Masyarakat pada Media Sosial Twitter menggunakan Metode K-Nearest Neighbor dan Pembobotan Jumlah Retweet


>**Dataset ini tersedia untuk penggunaan pribadi, tetapi jika Anda ingin mempublikasikan artikel ilmiah, publikasi jurnal, atau seminar dengan menggunakan dataset ini, maka Anda harus mengutip publikasi di bawah ini:**

Nurjanah, W.E., Perdana, R.S., & Fauzi, M.A. (2017). Analisis Sentimen Terhadap Tayangan Televisi Berdasarkan Opini Masyarakat pada Media Sosial Twitter menggunakan Metode K-Nearest Neighbor dan Pembobotan Jumlah Retweet. Jurnal Pengembangan Teknologi Informasi Dan Ilmu Komputer, 1(12), 1750-1757. Diambil dari http://j-ptiik.ub.ac.id/index.php/j-ptiik/article/view/631


**Abstrak**

Twitter merupakan situs web layanan jejaring sosial yang banyak diminati pengguna internet sebagai media komunikasi dan mendapatkan informasi. Informasi yang terdapat pada Twitter berupa pertanyaan, opini atau komentar, baik yang bersifat positif maupun negatif. Analisis sentimen merupakan salah satu cabang penelitian dari Text Mining yang melakukan proses klasifikasi pada dokumen teks. Metode yang digunakan adalah K-Nearest Neighbor, dengan menambahkan fitur pembobotan jumlah retweet (non-tekstual). Pembobotan tekstual hasil dari klasifikasi K-Nearest Neighbor dan pembobotan non-tekstual dari pembobotan jumlah retweet akan digabungkan menggunakan  nilai konstanta tertentu (α dan β) untuk menghasilkan sentimen positif dan negatif. Data yang digunakan berupa opini masyarakat terhadap tayangan televisi pada twitter sejumlah 400. Dari hasil pengujian akurasi menggunakan pembobotan tekstual diperoleh 82,50%, menggunakan pembobotan non-tekstual 60%, dan menggunakan penggabungan keduanya 83,33% dengan nilai k=3 dan konstanta perkalian yang tepat α=0,8 dan β=0,2.

**Artikel (Paper):** [PDF](http://j-ptiik.ub.ac.id/index.php/j-ptiik/article/view/631/250 "PDF")

**Dataset:**
[dataset_tweet_sentimen_tayangan_tv.csv](https://github.com/rizalespe/Dataset-Sentimen-Analisis-Bahasa-Indonesia/blob/master/dataset_tweet_sentimen_tayangan_tv.csv "dataset_tweet_sentimen_tayangan_tv.csv")

Detail: Dataset terdiri dari 400 dokumen tweet dari 4 acara televisi yaitu HitamPutihTransTV, IndonesiaLawyersClubTvOne, KickAndyMetroTV, dan MataNajwaMetroTV. Dataset dilengkapi dengan informasi `Jumlah Retweet` dari masing-masing dokumen tweet tersebut.

------------
### Analisis Sentimen Tentang Opini Film Pada Dokumen Twitter Berbahasa Indonesia Menggunakan Naive Bayes Dengan Perbaikan Kata Tidak Baku


>**Dataset ini tersedia untuk penggunaan pribadi, tetapi jika Anda ingin mempublikasikan artikel ilmiah, publikasi jurnal, atau seminar dengan menggunakan dataset ini, maka Anda harus mengutip publikasi di bawah ini:**

Antinasari, P., Perdana, R.S., & Fauzi, M.A. (2017). Analisis Sentimen Tentang Opini Film Pada Dokumen Twitter Berbahasa Indonesia Menggunakan Naive Bayes Dengan Perbaikan Kata Tidak Baku. Jurnal Pengembangan Teknologi Informasi Dan Ilmu Komputer, 1(12), 1733-1741. Diambil dari http://j-ptiik.ub.ac.id/index.php/j-ptiik/article/view/629


**Abstrak**

Pertumbuhan media sosial yang sangat pesat tidak membuat Twitter ditinggalkan oleh penggunanya. Twitter merupakan salah satu media sosial yang memungkinkan penggunanya untuk melakukan interaksi, berbagi informasi, atau bahkan untuk mengutarakan perasaan dan opini, termasuk juga dalam mengutarakan opini film. Komentar atau Tweet mengenai film yang ada pada Twitter dapat dijadikan sebagai evaluasi dalam menonton film dan meningkatkan produksi film. Untuk mengetahui hal tersebut, analisis sentimen dapat digunakan untuk mengklasifikasikan kedalam sentimen negatif atau positif.  Didalam Tweet terkandung banyak ragam bahasa yang digunakan, yaitu diantaranya bahasa dalam bentuk tidak baku seperti bahasa slang, penyingkatan kata, dan salah eja. Oleh sebab itu dibutuhkan penanganan khusus pada Tweet. Pada penelitian ini digunakan kamus kata tidak baku dan normalisasi Levenshtein Distance untuk memperbaiki kata yang tidak baku menjadi kata baku dengan pengklasifikasian Naive Bayes. Berdasarkan hasil pengujian yang telah dilakukan didapatkan akurasi tertinggi dengan nilai accuracy, precision, recall, dan f-measure sebesar 98.33%, 96.77%, 100%, dan 98.36%.

**Artikel (Paper):** [PDF](http://j-ptiik.ub.ac.id/index.php/j-ptiik/article/view/629/247 "PDF")

**Dataset:**
[dataset_tweet_sentimen_opini_film.csv](https://github.com/rizalespe/Dataset-Sentimen-Analisis-Bahasa-Indonesia/blob/master/dataset_tweet_sentiment_opini_film.csv "dataset_tweet_sentimen_opini_film.csv")

Detail: Dataset terdiri dari 200 dokumen tweet terkait opini pada film. Tujuan dari penelitian ini adalah untuk mengetahui pengaruh kata tidak baku dalam sebuah dokumen terhadap sentimen.
