>Please refer to [this](https://github.com/yusufsp7/Data_Analysis_Projects/blob/07_Project/EN_Marketing_Cost_Analysis.ipynb) .ipynb files to see full content

>Silahkan lihat file .iypnb [ini](https://github.com/yusufsp7/Data_Analysis_Projects/blob/07_Project/ID_Analisa_Biaya_Pemasaran.ipynb) untuk melihat keseluruhan konten

ID
# Dokumentasi tabel `visits` (log/catatan server yang memuat data kunjungan ke situs web):
Semua tanggal dalam tabel ini menggunakan format YYYY-MM-DD.

- `Uid` - ID pengguna
- `Device` - perangkat pengguna
- `Start Ts` - tanggal dan waktu dimulainya sesi
- `End Ts` - tanggal dan waktu berakhirnya sesi
- `Source Id` - ID sumber iklan, sumber yang digunakan pengguna untuk datang ke situs web

# Dokumentasi tabel `orders` (data terkait pesanan):

- `Uid` - ID pengguna yang membuat pesanan
- `Buy Ts` - tanggal dan waktu pesanan dibuat
- `Revenue` - pendapatan Y.Afisha dari pesanan tersebut

# Dokumentasi tabel `costs` (data terkait pengeluaran pemasaran):

- `source_id` - ID sumber iklan
- `dt` - tanggal
- `costs` - pengeluaran untuk sumber iklan pada tanggal tersebut

# Objektif:
Analisa untuk membantu mengoptimalkan biaya pemasaran.

-----------------------------------------------
EN
# Documentation of the `visits` table (logs/server records that contain data on website visits):
All dates in this table use the YYYY-MM-DD format.

- `Uid` - User ID
- `Device`  - the user's device
- `Start Ts`  - session start date and time
- `End Ts`  - session end date and time
- `Source Id`  - The advertising source ID, the source by which the user came to the website

# `orders` table documentation (data related to orders):

- `Uid`  - ID of the user who made the order
- `Buy Ts`  - the date and time the order was made
- `Revenue` - Y.Afisha's income from the order

# `costs` table documentation (data related to marketing expenses):

- `source_id` - Ad source ID
- `dt` - date
- `costs` - expenses for advertising sources on that date

# Objektive:
Analysis to help optimize marketing budget.

-----------------------------------------------

# Libraries
*pandas*,
*numpy*,
*matplotlib*,
*seaborn*,
*scipy*.

[Back to tables of contents](https://github.com/yusufsp7/Data_Analysis_Projects/tree/Tables_of_Contents)
