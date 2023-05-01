>Please refer to [this](https://github.com/yusufsp7/Data_Analysis_Projects/blob/13_Final_Project/Part_3_SQL/SQL_EN.ipynb) .ipynb files to see full content

>Silahkan lihat file .iypnb [ini](https://github.com/yusufsp7/Data_Analysis_Projects/blob/13_Final_Project/Part_3_SQL/SQL_ID.ipynb) untuk melihat keseluruhan konten

ID
# Dokumentasi:
&ensp;&thinsp;&ensp;&thinsp; books (Berisi data tentang buku):
   - `book_id` — ID buku
   - `author_id` — ID penulis
   - `title` — judul buku
   - `num_pages` — jumlah halaman
   - `publication_date` — tanggal penerbitan
   - `publisher_id` — ID penerbit
<br>
   
&ensp;&thinsp;&ensp;&thinsp; authors (Berisi data tentang penulis):
   - `author_id` — ID penulis
   - `author` — nama penulis
<br>

&ensp;&thinsp;&ensp;&thinsp; publishers (Berisi data tentang penerbit):
   - `publisher_id` — ID penerbit
   - `publisher` — nama penerbit
<br>

&ensp;&thinsp;&ensp;&thinsp; ratings (Berisi data tentang ulasan pengguna):
   - `rating_id` — ID rating
   - `book_id` — ID buku
   - `username` — nama pengguna yang memberi rating buku
   - `rating` — rating dari pengguna
<br>

&ensp;&thinsp;&ensp;&thinsp; reviews reviews (Berisi data tentang ulasan pelanggan):
   - `review_id` — ID ulasan
   - `book_id` — ID buku
   - `username` — nama pengguna yang mengulas buku
   - `text` — teks ulasan
<br>

# Objektif:
Menganalisa dataset ini untuk mendapatkan informasi yang akan digunakan dalam membuat penawaran harga untuk sebuah produk baru.

-----------------------------------------------
EN
# Documentation:
&ensp;&thinsp;&ensp;&thinsp; books (Contains data about books):
   - `book_id` — book ID
   - `author_id` — author ID
   - `title` — book title
   - `num_pages` — number of pages
   - `publication_date` — publication date
   - `publisher_id` — publisher ID
<br>
   
&ensp;&thinsp;&ensp;&thinsp; authors (Contains data about the author):
   - `author_id` — author ID
   - `author` — author name
<br>

&ensp;&thinsp;&ensp;&thinsp; publishers (Contains data about publishers):
   - `publisher_id` — publisher ID
   - `publisher` — publisher name
<br>

&ensp;&thinsp;&ensp;&thinsp; ratings (Contains data about user reviews):
   - `rating_id` — rating ID
   - `book_id` — book ID
   - `username` — the username that rated the book
   - `ratings` — rating from the users
<br>

&ensp;&thinsp;&ensp;&thinsp; reviews (Contains data about customer reviews):
   - `review_id` — Review ID
   - `book_id` — book ID
   - `username` — the username who reviewed the book
   - `text` — review text
<br>

# Objective:
Analyze this dataset to obtain information that will be used in making a price quote for a new product.

-----------------------------------------------

# Libraries
*pandas*,
*sqlalchemy*.

# Data Diagrams
![Data Diagrams](https://github.com/yusufsp7/Data_Analysis_Projects/blob/13_Final_Project/Part_3_SQL/Diagram%20Data.png)

[Back to tables of contents](https://github.com/yusufsp7/Data_Analysis_Projects/tree/Tables_of_Contents)
