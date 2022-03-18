# Project-count-sum-group-data-python
Thisproject about learning counting, summing and grouping data in python (In Indonesia)

SQL Functions:
- Contohnya: Count, Sum
- from sqlalchemy import func
- Lebih efisien daripada memproses dengan Python, karena kita tidak perlu melakukan perulangan
- Aggregate data : menggabungkan beberapa records menjadi satu

Sum Example:
Sebagai contoh, disini kita akan menghitung nilai total dari kolom pop2008 dengan menggunakan perintah sum SQLAlchemy.
Pastikan terlebih dahulu untuk membuat engine dan koneksi string ke database. Lalu kita buat akses ke tabel serta perintah apa saja yang ingin kita gunakan. Untuk kasus ini kita hanya ingin menampilkan data dari table census maka kita import select.
Group by:
- Mengizinkan kita mengelompokkan data berdasarkan nilai tertentu

Sebagai contoh, kita ingin mendapatkan sum dari populasi di tahun 2008 kemudian kita lakukan agregasi berdasarkan jenis kelamin dari database census.
Group by mendukung banyak kolom untuk dikelompokkan dengan dengan pola yang mirip dengan order_by () serta membutuhkan semua kolom yang dipilih untuk dikelompokkan atau diagregasikan oleh suatu fungsi.

