ID
# Dokumentasi tabel `calls` (data panggilan):

- `id` — ID sesi web unik
- `call_date` — tanggal panggilan
- `duration` — durasi panggilan (dalam menit)
- `user_id` — ID pengguna yang melakukan panggilan

# Dokumentasi tabel `internet` (data sesi web):

- `id` — ID sesi web unik
- `mb_used` — volume data yang dihabiskan selama sesi (dalam megabita)
- `session_date` — tanggal sesi web
- `user_id` — ID pengguna

# Dokumentasi tabel `messages` (data SMS):

- `id` — ID SMS unik
- `message_date` — tanggal SMS dikirim
- `user_id` — ID pengguna yang mengirim SMS

# Dokumentasi tabel `plans` (data paket telepon):

- `plan_name` — nama paket telepon
- `usd_monthly_fee` — biaya bulanan dalam dolar AS
- `minutes_included` — alokasi menit panggilan bulanan
- `messages_included` — alokasi SMS bulanan
- `mb_per_month_included` — alokasi volume data bulanan (dalam megabita)
- `usd_per_minute` — harga per menit jika telah melebihi batas alokasi paket (misalnya, jika paket memiliki alokasi 100 menit, maka penggunaan mulai dari menit ke-101 akan dikenakan biaya)
- `usd_per_message` — harga per SMS jika telah melebihi batas alokasi paket
- `usd_per_gb` — harga per ekstra gigabita data jika telah melebihi batas alokasi paket (1 GB = 1024 megabita)

# Dokumentasi tabel `users` (data pengguna):

- `user_id` — ID pengguna
- `first_name` — nama depan pengguna
- `last_name` — nama belakang pengguna
- `age` — usia pengguna (tahun)
- `reg_date` — tanggal mulai berlangganan (dd, mm, yy)
- `churn_date` — tanggal pengguna berhenti menggunakan layanan (jika nilainya hilang atau tidak ada, berarti paket layanan sedang digunakan saat data ini dibuat)
- `city` — kota tempat tinggal pengguna
- `plan` — nama paket telepon

# Objektif:
Laporan ini menganalisis kumpulan data perilaku klien dan menentukan paket prabayar mana yang menghasilkan lebih banyak pendapatan.

-----------------------------------------------
EN
# `internet` table documentation (web session data):

- `id` — A unique web session ID
- `mb_used` — volume of data consumed during session (in megabytes)
- `session_date` — web session date
- `user_id` — User ID

# `message` table documentation (SMS data):

- `id`  — a unique SMS ID
- `message_date`  — the date the SMS was sent
- `user_id`  — ID of the user who sent the SMS

# `plans` table documentation (telephone package data):

- `plan_name` — phone plan name
- `usd_monthly_fee` — monthly fee in US dollars
- `minutes_included` — allocated monthly call minutes
- `messages_included` — monthly SMS allocation
- `mb_per_month_included` — monthly data volume allocation (in megabytes)
- `usd_per_minute` — price per minute if the package allocation limit has been exceeded (for example, if a package has an allocation of 100 minutes, then usage starting from the 101st minute will be charged)
- `usd_per_message` — price per SMS if the package allocation limit has been exceeded
- `usd_per_gb`  — price per extra gigabyte of data if the package allocation limit has been exceeded (1 GB = 1024 megabytes)

# `users` table documentation (user data):

- `user_id`  — User ID
- `first_name` — the user's first name
- `last_name` — last name of the user
- `age` — user's age (years)
- `reg_date` — subscription start date (dd, mm, yy)
- `churn_date`  — the date the user stopped using the service (if the value is missing or not there, it means the service plan was in use when this data was generated)
- `city` — the city where the user lives
- `plan` — name of the phone plan

# Objektive:
This report analyzes datasets client behavior and determine which prepaid plans bring in more income.

-----------------------------------------------

# Libraries
*pandas*,
*numpy*,
*matplotlib*,
*scipy*.
