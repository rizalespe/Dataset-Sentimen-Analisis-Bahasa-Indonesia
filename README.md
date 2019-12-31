# Analisis Sentimen Tingkat Kepuasan Pengguna Penyedia Layanan Telekomunikasi Seluler Indonesia Pada Twitter Dengan Metode Support Vector Machine dan Lexicon Based Features

**Abstrak**

Analisis sentimen adalah salah satu cabang penelitian dari Text Mining yang berguna untuk mengklasifikasi dokumen teks berupa opini berdasarkan sentimen. Dokumen teks yang digunakan dalam penelitian berasal Twitter tentang opini masyarakat mengenai penyedia layanan telekomunikasi seluler. Metode yang digunakan adalah Support Vector Machine dengan menggunakan Lexicon Based Features sebagai pembaharuan fiturnya selain memakai fitur TF-IDF. Data yang digunakan pada penelitian ini sebanyak 300 data yang dibagi menjadi dua jenis data dengan perbandingan 70% untuk data latih dan 30% untuk data uji. Hasil akurasi sistem yang diperoleh dari analisis sentimen dengan metode Support Vector Machine dan Lexicon Based Features sebesar 79% menggunakan nilai degree sebesar 2, nilai konstanta learning rate 0,0001, serta jumlah iterasi maksimum sebanyak 50 kali. Sedangkan sistem analisis sentimen tanpa menggunakan Lexicon Based Features menghasilkan tingkat akurasi sebesar 84% dengan nilai parameter yang sama.

**Dataset:**
File: [dataset_tweet_sentiment_cellular_service_provider.csv ](https://github.com/rizalespe/Indonesian-Sentiment-Analysis-Dataset/blob/master/dataset_tweet_sentiment_cellular_service_provider.csv "dataset_tweet_sentiment_cellular_service_provider.csv ")

Detail: Dataset analisis sentimen dikumpulkan dari situs jejaring sosial Twitter terkait dengan sentimen masyarakat terhadap penyedia layanan seluler di Indonesia sejumlah 300 tweet. Dataset memiliki 2 kelas sentimen yaitu `positive` dan `negative`. Sebelum dipublikasikan, dataset ini telah kami lakukan beberapa praproses sebagai berikut:
- Mengganti nama/identitas penyedia layanan dengan tag `<PROVIDER_NAME>`
- Mengganti alamat URL dengan tag `<URL>`
- Mengganti @mention pengguna dengan tag `<USER_MENTION>`
- Mengganti nama produk dengan tag `<PRODUCT_NAME>`


>**Dataset ini tersedia untuk penggunaan pribadi, tetapi jika Anda ingin mempublikasikan artikel ilmiah, publikasi jurnal, atau seminar dengan menggunakan dataset ini, maka Anda harus mengutip publikasi di bawah ini:**


Rofiqoh, U., Perdana, R.S., & Fauzi, M.A. (2017). Analisis Sentimen Tingkat Kepuasan Pengguna Penyedia Layanan Telekomunikasi Seluler Indonesia Pada Twitter Dengan Metode Support Vector Machine dan Lexicon Based Features. Jurnal Pengembangan Teknologi Informasi Dan Ilmu Komputer, 1(12), 1725-1732. Diambil dari http://j-ptiik.ub.ac.id/index.php/j-ptiik/article/view/628

------------


