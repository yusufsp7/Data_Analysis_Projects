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
Analisa perilaku pengguna untuk membantu mengoptimalkan biaya pemasaran.

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

# Objektif:
Analysis of passenger preferences and the impact of external factors on trips

-----------------------------------------------

# Libraries
*pandas*,
*numpy*,
*matplotlib*,
*seaborn*,
*scipy*.
