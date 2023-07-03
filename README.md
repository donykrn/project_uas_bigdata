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

![2](https://github.com/donykrn/project_uas_bigdata/assets/107750653/543a129c-9a93-4a6f-b004-3f795a531822)

![3](https://github.com/donykrn/project_uas_bigdata/assets/107750653/985b7d24-b28b-4b9c-89cb-8c781ad32cb6)

![4](https://github.com/donykrn/project_uas_bigdata/assets/107750653/c457ed65-5496-4785-b619-e1aaecb369a7)

![5](https://github.com/donykrn/project_uas_bigdata/assets/107750653/c84f26d4-d887-4c8f-bfa6-8b9b85b9fddf)

![6](https://github.com/donykrn/project_uas_bigdata/assets/107750653/a569224c-8563-4d5b-b5b9-37b6af293c1e)

![7](https://github.com/donykrn/project_uas_bigdata/assets/107750653/664fd5cc-67af-4e16-ac88-8ecdc56f0c15)

![8](https://github.com/donykrn/project_uas_bigdata/assets/107750653/bfb00bb6-2fba-491e-8bba-21c34e70059d)

![9](https://github.com/donykrn/project_uas_bigdata/assets/107750653/18213dcf-ee2e-46c2-bf08-722ac0d4cb80)

![10](https://github.com/donykrn/project_uas_bigdata/assets/107750653/f581c9fe-19cd-40c2-9728-9b8b5706f1a5)

![11](https://github.com/donykrn/project_uas_bigdata/assets/107750653/41dc21ca-fab1-4056-bb8d-72fb39c6a411)

![12](https://github.com/donykrn/project_uas_bigdata/assets/107750653/8fa20d83-b051-4a70-81d3-d98f5e7082e7)

![13](https://github.com/donykrn/project_uas_bigdata/assets/107750653/574075d9-5250-404d-b9bb-8691b4b6c1ce)

![14](https://github.com/donykrn/project_uas_bigdata/assets/107750653/f4a3469c-40bd-4933-9a4c-3b2b7e3f3f26)

![15](https://github.com/donykrn/project_uas_bigdata/assets/107750653/9bba1ed2-2cb8-4694-882a-a111ea9839e5)

![16](https://github.com/donykrn/project_uas_bigdata/assets/107750653/23fc97fc-f2b3-4cd7-9c83-ab8e14df5723)
![grafik batang](https://github.com/donykrn/project_uas_bigdata/assets/107750653/258824ee-3edb-4cf8-a35d-098759537291)


