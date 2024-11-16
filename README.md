# AplikasiCekCuacaSederhana
 Tugas 6- SEIDI RAHMAT

Aplikasi Cek Cuaca Sederhana (Penjelasan Aplikasi Cek Cuaca Sederhana)
Inilah penjelasan mengenai aplikasi cek cuaca sederhana:

Antarmuka Pengguna (GUI)

jLabel1: Label yang menampilkan judul aplikasi "Aplikasi Cek Cuaca Sederhana"
jTextField1: Text field untuk memasukkan nama kota
jButton1: Tombol untuk mengecek cuaca berdasarkan kota yang dimasukkan
jComboBox1: Kotak combo yang menampilkan daftar kota favorit
jButton2: Tombol untuk menyimpan kota yang dimasukkan sebagai favorit
jButton3: Tombol untuk mengekspor data cuaca yang ditampilkan di tabel
jButton4: Tombol untuk mengimpor data cuaca dari file
jButton5: Tombol untuk menghapus baris yang dipilih pada tabel
jButton6: Tombol untuk keluar dari aplikasi
jLabel2: Label yang menunjukkan "Kota Pilihan"
jLabel3: Label yang menunjukkan "Kota Favorit"
jLabel4: Label yang menunjukkan "Gambar"
jScrollPane1: Scroll pane yang berisi tabel data cuaca
jTable1: Tabel yang menampilkan data cuaca, terdiri dari kolom Tanggal, Kota, Suhu, Kondisi, dan Kelembapan
Fungsionalitas

Pengguna dapat memasukkan nama kota pada text field jTextField1 dan menekan tombol jButton1 untuk mendapatkan informasi cuaca kota tersebut.
Informasi cuaca yang didapatkan akan ditampilkan pada tabel jTable1, termasuk tanggal, kota, suhu, kondisi cuaca, dan kelembapan.
Pengguna dapat menyimpan kota yang sering dicek sebagai favorit dengan menekan tombol jButton2. Kota favorit akan ditambahkan ke dalam daftar jComboBox1.
Tombol jButton3 memungkinkan pengguna untuk mengekspor data cuaca yang ditampilkan pada tabel ke dalam file.
Tombol jButton4 memungkinkan pengguna untuk mengimpor data cuaca dari file yang sebelumnya diekspor.
Tombol jButton5 memungkinkan pengguna untuk menghapus baris yang dipilih pada tabel.
Tombol jButton6 memungkinkan pengguna untuk keluar dari aplikasi.
Ikon cuaca akan ditampilkan pada label jLabel4 berdasarkan kode yang diterima dari API OpenWeatherMap.
Teknologi yang Digunakan

Aplikasi ini kemungkinan dibangun menggunakan Java Swing untuk membuat antarmuka pengguna.
Aplikasi ini menggunakan library eksternal untuk melakukan parsing data JSON yang diterima dari API OpenWeatherMap.
Aplikasi ini menggunakan API OpenWeatherMap untuk mendapatkan informasi cuaca.
Kesimpulan

Aplikasi ini merupakan aplikasi sederhana yang memungkinkan pengguna untuk mengecek cuaca di berbagai kota dan menyimpan kota favorit. Pengguna juga dapat mengekspor dan mengimpor data cuaca. 



![Demo GIF](https://github.com/seidi255/AplikasiCekCuacaSederhana/blob/main/img/DEmo%20cek%20cuaca.gif)
