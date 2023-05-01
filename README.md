>Please refer to [this](https://github.com/yusufsp7/Data_Analysis_Projects/blob/12_Project/EN_Fitness_Center_Customer_Analysis.ipynb) .ipynb files to see full content

>Silahkan lihat file .iypnb [ini](https://github.com/yusufsp7/Data_Analysis_Projects/blob/12_Project/ID_Analisa_Pelanggan_Pusat_Kebugaran.ipynb) untuk melihat keseluruhan konten

ID
# Dokumentasi:
- `Churn` — *churn* aktual untuk bulan terkait, `0` berarti masih berlangganan dan `1` berarti sudah berhenti berlangganan <br>
<br>

&ensp;&thinsp;&ensp;&thinsp;&ensp;&thinsp; Data pengguna untuk bulan sebelumnya:
- `gender` - jenis kelamin pelanggan, `0` berarti perempuan dan `1` berarti laki-laki
- `Near_Location` - apakah pengguna tinggal atau bekerja di dekat lokasi pusat kebugaran
- `Partner` - apakah pengguna adalah karyawan perusahaan mitra (pusat kebugaran ini memiliki perusahaan mitra dan para karyawannya mendapatkan diskon; dalam hal ini, pusat kebugaran menyimpan informasi tentang perusahaan tempat kerja pelanggan mereka)
- `Promo_friends` - apakah pengguna awalnya melakukan pendaftaran melalui penawaran "ajak teman" (mereka menggunakan kode promo teman saat membayar keanggotaan pertama mereka)
- `Phone` - apakah pengguna memberikan nomor telepon mereka
- `Age` - usia pelanggan
- `Lifetime` - waktu (dalam bulan) sejak kunjungan pertama pelanggan ke pusat kebugaran
<br>

&ensp;&thinsp;&ensp;&thinsp;&ensp;&thinsp;  Data dari log kunjungan dan pembelian serta data terkait status keanggotaan saat ini:
- `Contract_period` - 1 bulan, 3 bulan, 6 bulan, atau 1 tahun
- `Month_to_end_contract` - sisa bulan sebelum kontrak berakhir
- `Group_visits` - apakah pengguna mengambil bagian dalam sesi kelompok
- `Avg_class_frequency_total` - frekuensi rata-rata kunjungan per minggu selama masa hidup pelanggan
- `Avg_class_frequency_current_month` - frekuensi rata-rata kunjungan per minggu selama bulan sebelumnya
- `Avg_additional_charges_total` - jumlah total uang yang dikeluarkan untuk membayar layanan lain di pusat kebugaran: kafe, barang atletik, kosmetik, pijat, dll.

# Objektif:
Menggunakan model *machine learning* untuk Menganalisis profil para pelanggan dan mengembangkan strategi retensi pelanggan (customer retention).

-----------------------------------------------
EN
# Documentation:
- `Churn` — actual churn for the concerned month, `0` means still subscribed and `1` means unsubscribed <br>
<br>

&ensp;&thinsp;&ensp;&thinsp;&ensp;&thinsp;  User data for the previous month:
- `gender` - gender of customer, `0` means female and `1` means male
- `Near_Location` - whether the user lives or works near the gym location
- `Partner` - whether the user is an employee of a partner company (this gym has a partner company and their employees get a discount; in this case, the gym stores information about the company their customer works for)
- `Promo_friends` - whether the user initially signed up via the "refer a friend" offer (they used a friend's promo code when paying for their first membership)
- `Phone` - whether the user provides their phone number
- `Age` - the age of the customer
- `Lifetime` - time (in months) since the customer's first visit to the fitness center
<br>

&ensp;&thinsp;&ensp;&thinsp;&ensp;&thinsp;  Data from visit and purchase logs and data regarding current membership status:
- `Contract_period` - 1 month, 3 months, 6 months or 1 year
- `Month_to_end_contract` - the remaining months before the contract expires
- `Group_visits` - whether the user is taking part in group sessions
- `Avg_class_frequency_total` - the average frequency of visits per week over the customer's lifetime
- `Avg_class_frequency_current_month` - average frequency of visits per week during the previous month
- `Avg_additional_charges_total` - the total amount of money spent to pay for other services in the gym: cafe, athletic goods, cosmetics, massage, etc.

# Objective:
Using *machine learning* models to analyze customer profiles and develop customer retention strategies.

-----------------------------------------------

# Libraries
*pandas*,
*numpy*,
*matplotlib*,
*seaborn*,
*sklearn*,
*scipy*,
*warnings*.

[Back to tables of contents](https://github.com/yusufsp7/Data_Analysis_Projects/tree/Tables_of_Contents)
