# pv26-miniproject-management-buku-film-F1D02310045

Nama Aplikasi : MangAnime

deskripsi     : aplikasi sederhana yang digunakan untuk list Manga ataupun Anime yang sudah ditonton maupun dibaca oleh pengguna

Teknologi yang digunakan : 
- Python 3.10+: Sebagai bahasa pemrograman utama yang menangani seluruh logika aplikasi.
- PySide6 (Qt for Python): Framework GUI (Graphical User Interface) standar industri yang digunakan untuk membangun jendela, tombol, tabel, dan dialog.
- SQLite3: Mesin database serverless yang tertanam langsung dalam aplikasi. Teknologi ini dipilih agar data tetap tersimpan secara permanen tanpa memerlukan instalasi server database yang rumit.
- QSS (Qt Style Sheets): Digunakan untuk mendesain tampilan (seperti CSS pada web). Seluruh gaya visual ungu gelap (Violet Dark) dipisahkan ke dalam file .qss eksternal.
- SoC Architecture: Pemisahan modul antara UI, Database, dan Logika Bisnis untuk memudahkan pemeliharaan kode.

  Cara menjalankan aplikasi:
  Untuk menjalankan aplikasi MangAnime diperlukan lingkungan Python (minimal versi 3.8) terlebih dahulu. Pertama, buka terminal atau command prompt di dalam folder proyek, lalu buat dan aktifkan virtual environment guna memastikan pustaka aplikasi terisolasi dengan aman. Setelah itu, instal pustaka PySide6 menggunakan perintah pip install PySide6 sebagai satu-satunya dependensi utama untuk antarmuka grafis. Terakhir, jalankan aplikasi dengan mengetikkan perintah python main.py pada terminal; sistem akan secara otomatis memuat seluruh konfigurasi, memicu pembuatan database SQLite MangAnime.db jika belum tersedia, dan menampilkan jendela utama aplikasi yang siap digunakan.
