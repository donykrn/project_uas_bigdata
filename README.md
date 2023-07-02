# project_uas_bigdata
# Mengatasi Kejahatan Internasional: Penegakan Hukum Pidana dan Pencegahan Berdasarkan Data Kejahatan Sebelumnya
Kejahatan adalah masalah sosial yang penting di negara ini, mempengaruhi keamanan publik, perkembangan anak, dan status sosial ekonomi orang dewasa. Seorang petugas polisi mungkin mengetahui di mana daerah berbahaya berdasarkan pengalamannya, tetapi dia mungkin tidak dapat mengetahui jenis kejahatan apa yang bisa terjadi. Tujuan kami adalah membantu petugas polisi dengan memberikan informasi berguna yang sulit didapat, sehingga mereka dapat mengambil tindakan yang tepat

# Tujuan
Memprediksi jenis kejahatan dan probabilitas kejahatan berdasarkan lokasi.

Memprediksi jenis kejahatan berdasarkan Waktu dan juga parameter lainnya.

# Dataset
Kumpulan data yang dipilih untuk proyek ini terdiri dari insiden kejahatan yang dilaporkan di kota Chicago dari tahun 2001 hingga 2019. Ini adalah salah satu sumber data terkaya di bidang kejahatan. Kumpulan data mencakup informasi yang cukup tentang Tanggal, Jenis, Deskripsi, lokasi, dll tentang kejahatan untuk analisis kami.

Dataset berisi 7 juta catatan kejahatan. Data sebesar ini membutuhkan pemrosesan data yang cepat dan efisien. Kami menggunakan Spark karena memudahkan untuk menangani data sebesar ini.

## Metode
1. Menghilangkan nilai yang hilang/nol karena menyumbang <1% dari data.
2. Memfilter fitur yang tidak relevan dari kumpulan data.
3. Mengurangi dan menggabungkan jumlah jenis kejahatan dari 32 menjadi 16.
4. Menggunakan teknik Random Over sampling/Under sampling untuk menyeimbangkan data.

![1](https://github.com/donykrn/project_uas_bigdata/assets/107750653/842df851-d054-4884-b8fe-a14cbad785c3)

