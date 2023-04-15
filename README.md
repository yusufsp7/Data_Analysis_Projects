ID
# Dokumentasi tabel `hypotheses_us`:
- `Hypotheses` - deskripsi singkat tentang hipotesis
- `Reach` - jangkauan pengguna, dalam skala satu hingga sepuluh
- `Impact` - dampak terhadap pengguna, dalam skala satu hingga sepuluh
- `Confidence` - keyakinan pada hipotesis, dalam skala satu sampai sepuluh
- `Effort` - sumber daya yang diperlukan untuk menguji hipotesis, dalam skala satu sampai sepuluh. Semakin tinggi nilai `Effort`, semakin intensif sumber daya pengujiannya.

# Dokumentasi tabel `orders_us`:
- `transactionId` - ID pesanan
- `visitorId` - ID pengguna yang membuat pesanan
- `date` - tanggal dibuatnya pesanan
- `revenue` - pendapatan dari pesanan
- `group` - kelompok uji (*test group*) A/B tempat pengguna berada

# Dokumentasi tabel `visits_us`:
- `date` - tanggal kunjungan
- `group` - kelompok uji (*test group*) A/B
- `visits` - jumlah kunjungan pada tanggal yang ditentukan untuk kelompok uji A/B yang ditentukan

# Objektif:
Hipotesis A/B *testing* untuk membantu meningkatkan pendapatan toko daring.

-----------------------------------------------
EN
# `hypotheses_us` table documentation:
- `Hypotheses`  - a brief description of the hypothesis
- `Reach` - user's range, on a scale of one to ten
- `Impact`  - the impact on users, on a scale of one to ten
- `Confidence` - belief in a hypothesis, on a scale of one to ten
- `Effort` - the resources needed to test a hypothesis, on a scale of one to ten. The higher the `Effort` value, the more resource intensive the test is.

# `orders_us` table documentation:
- `transactionId`  - order ID
- `visitorId`  - ID of the user who made the order
- `date` - the date the order was made
- `revenue`  - income from orders
- `group` - A/B test group (*test group*) to which the user belongs

# `visits_us` table documentation:
- `date` - date of visit
- `group`  - test group (*test group*) A/B
- `visits` - the number of visits on the specified date for the specified A/B test group

# Objektive:
A/B testing hypotheses to help increase online store revenue.

-----------------------------------------------

# Libraries
*pandas*,
*numpy*,
*matplotlib*,
*seaborn*,
*scipy*,
*datetime*.

[Back to tables of contents](https://github.com/yusufsp7/Data_Analysis_Projects/tree/Tables_of_Contents)
