## Mengumpulkan konteks

Pertanyaan (untuk *stakeholders*):
- Apa yang dibutuhkan *stakeholder*: *stakeholder* meminta untuk menganalisa data yang akan digunakan untuk membuat tawaran khusus untuk pelanggan, dan mereka juga membutuhkan presentasi, dan *dashboard* dari hasil analisa.

- Kenapa *stakeholder* membutuhkan analisa: riset yang dilakukan secara kualitatif tidaklah cukup untuk membuat keputusan, mereka membutuhkan argumen berdasarkan data.

- Apa saja riset yang telah dilakukan sebelumnya, dan bagaimana hasil temuan tersebut dapat memberikan informasi untuk riset sekarang: Tidak, ini riset baru. Jelaskan se-detail mungkin saat mendeskripsikan bagaimana solusi Anda dapat bekerja.

- Kerangka waktu (*time frame*) seperti apa yang harus dipertimbangkan dalam analisa: seluruh periode yang tercakup pada sumber data.

Pertanyaan (untuk saya sendiri):
- Siapa *stakeholdernya*, siapa yang membutuhkan informasi tersebut, siapa yang akan menggunakan hasil akhirnya: Product Manager - bertanggung jawab terhadap pengalaman pengguna (*user experience*).

- Dataset seperti apa yang saya butuhkan: data yang mencakup transaksi pelanggan.

- Dimana dan bagaimana saya mendapatkan dataset tersebut: data engineer.

- Kapan hasil analisa ini dibutuhkan: tenggat waktu 26/4/2023

## *Summary*

***Stakeholders***: Product Manager

**Menentukan masalah**:
   - Menganalisa data yang akan digunakan untuk membuat tawaran khusus untuk pelanggan,
   - Seluruh periode yang tercakup pada sumber data,
   - Presentasi
   - *Dashboard*
   
**Bagaimana saya menyelesaikan masalah tersebut**: 

   - Objektif: Segmentasi pengguna berdasarkan profil konsumen mereka
   
   - Pertanyaan:
       - Segmen seperti apa yang cenderung melakukan pembelian musiman? Apakah pengguna ini cenderung melakukan pembelian berulang?
       - Segmen seperti apa yang cenderung membuat beberapa pesanan dalam jangka waktu lama?
       - Segmen seperti apa yang melakukan banyak pembelian dalam waktu singkat?
       - Segmen seperti apa yang membuat pesanan banyak? Apa yang didapatkan tentang pola konsumsi mereka?
       - Segmen seperti apa yang membuat pesanan sedikit? Apa yang didapatkan tentang pola konsumsi mereka?
       - Bagaimana perbedaan dalam preferensi produk di antara segmen konsumen?
       
   - Menganalisa dataset:
       - Ikhtisar Data;
           - Memuat semua library
           - Memuat dataset
           - Melihat informasi umum dataset
           - Memeriksa kualitas data:
               - Memeriksa nilai yang hilang,
               - Nilai duplikat,
               - Tipe data,
               - Nama kolom,
               - Nilai setiap kolom,
               - Kemungkinan adanya *outlier*
           
       - Pra-pemprosesan Data;
           - Memperbaiki kualitas data (jika ada):
               - Memperbaiki penamaan kolom,
               - Memperbaiki nilai duplikat,
               - Memperbaiki nilai yang hilang,
               - Menambahkan kolom (semisal kolom yang berisi nilai tanggal, hari, bulan, tahun transaksi),
               - Memperbaiki *outlier*
       - EDA:
           - Metrik toko:
               - Tren pendapatan,
               - Rata-rata ukuran pembelian dan trennya,
               - tren dari bulan ke bulan pada rata-rata pendapatan per pengguna
           - Mencari tahu jawaban dari pertanyaan-pertanyaan di bagian "Pertanyaan"
           - Menulis hasil temuan, *insight*, dan rekomendasi.
           
       - Uji Hipotesis
           - Menggunakan metode t-test independen, atau Mann-Whitney (jika data tidak terdistribusi normal) untuk menguji hipotesis tentang perbedaan frekuensi dan ukuran pesanan rata-rata untuk segmen pengguna yang berbeda.
           - Mengetahui ada atau tidaknya perbedaan dari hasil uji statistik:
               - p-value (nilai probabilitas) > alpha (tingkat error) tidak ada perbedaan signifikan, atau 
               - p-value (nilai probabilitas) < alpha (tingkat error) ada perbedaan signifikan.
           
       - Machine Learning (jika dibutuhkan)
           - Menggunakan metode pengklasteran (*unsupervised machine learning*)  untuk mempelajari dan memvisualisasikan setiap segmen pelanggan
           
       - Kesimpulan Umum
       
       - Presentasi
           - *Insight* dari hasil analisa
           - Menjelaskan lebih lanjut tentang *insight* tersebut berdasarkan data
           - Rekomendasi berdasarkan *insight* tersebut
           
       - Dashboard
           - Konten data *dashboard*:
               - Kategori pengguna
           - Parameter yang digunakan untuk mengelompokkan data:
               - Tanggal dan waktu transaksi pelanggan,
               - Segmen pelanggan
           - Grafik, kontrol *dashboard*, dan susunannya:
             [Dashboard](https://docs.google.com/document/d/1LQ0_dSiO7O9gG7WLvLgAMbhO-v5vFi-KdU77QLdI13I/edit?usp=sharing)
