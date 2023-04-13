# Deskripsi tugas
Anda bekerja sebagai seorang analis video *ads* di agensi periklanan Sterling & Draper. Anda menghabiskan banyak waktu untuk menganalisis video yang sedang *trending* di YouTube guna menentukan jenis konten yang menarik bagi tim pemasaran.

Setiap video memiliki kategori tertentu (Hiburan, Musik, Berita & Politik, dll.), wilayah, dan tanggal *trending*.

Suatu video bisa saja berada di jajaran segmen *trending* selama beberapa hari berturut-turut.

Setiap minggu, dua karyawan baru selalu mengajukan pertanyaan yang sama kepada Anda:

- Kategori video apa saja yang *trending* minggu lalu?
- Bagaimana penyebarannya di setiap wilayah?
- Kategori apa saja yang paling populer di Amerika Serikat?

Pada minggu keenam Anda bekerja, Anda memutuskan bahwa sudah saatnya untuk mengotomatisasikan proses ini. Anda pun memutuskan untuk membuat sebuah *dashboard*.

## Ringkasan pedoman teknisnya:

- Tujuan bisnis: menganalisis riwayat video yang sedang *trending* di YouTube
- Frekuensi penggunaan *dashboard*: minimal sekali sehari
- Pengguna *dashboard* yang ditargetkan: para manajer perencanaan video *ads*
- Konten data *dashboard*:
    - Video yang pernah *trending*, dikelompokkan berdasarkan hari dan kategori
    - Video yang sedang *trending*, dikelompokkan berdasarkan negara
    - Tabel yang menghubungkan kategori dan negara
- Parameter yang digunakan untuk mengelompokkan data:
    - Tanggal dan waktu *trending*
    - Kategori video
    - Negara
- Data:
    - Riwayat *trending* — nilai absolut yang dibagi berdasarkan hari (dua grafik: nilai absolut dan rasio persentase)
    - Sesi, dikelompokkan berdasarkan negara — nilai relatif (% sesi)
    - Hubungan antara kategori dan negara — nilai absolut (tabel)
- Signifikansi: semua grafik sama pentingnya
- Sumber data untuk *dashboard*: *data engineer* akan membuat tabel agregat yang dinamai `trending_by_time`. Berikut adalah strukturnya:
    - `record_id` — kunci primer
    - `region` — negara/wilayah geografis
    - `trending_date` — tanggal dan waktu
    - `category_title` — kategori video
    - `videos_count` — jumlah video pada segmen *trending*
- Tabel disimpan di *database* `youtube`
- Interval pembaruan data: setiap 24 jam sekali, pada tengah malam waktu UTC
- Grafik, kontrol *dashboard*, dan susunannya:<br>
<br>

![ID_Description](https://github.com/yusufsp7/Data_Analysis_Projects/blob/Project_11/source_files/ID_Description.png)

# Dashboard
Ini merupakandashboard berdasarkan pedoman teknis diatas
![Gif](https://github.com/yusufsp7/Data_Analysis_Projects/blob/Project_11/source_files/Tableau%20Public%20-%20Youtube%20Trending.gif)

Silakan buka tautan ini untuk membuka versi lengkap: [Youtube Dashboard](https://public.tableau.com/views/YoutubeTrending_16798306360250/Dashboard1?:language=en-GB&publish=yes&:display_count=n&:origin=viz_share_link)
