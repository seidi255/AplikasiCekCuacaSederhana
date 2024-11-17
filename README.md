# AplikasiCekCuacaSederhana
 Tugas 6- SEIDI RAHMAT(2210010262)

**Deskripsi Lengkap Aplikasi Cuaca**

Aplikasi cuaca ini adalah sebuah program komputer yang dirancang untuk memberikan informasi cuaca terkini kepada pengguna. Aplikasi ini dibangun menggunakan bahasa pemrograman Java dan menggunakan antarmuka pengguna grafis (GUI) yang dibuat dengan Swing.

**Fungsi Utama:**

1. Mengambil Data Cuaca: Aplikasi ini terhubung ke layanan cuaca online (dalam kasus ini, OpenWeatherMap) untuk mendapatkan data cuaca real-time berdasarkan kota yang dimasukkan pengguna.
2. Menampilkan Data: Data cuaca yang diperoleh kemudian ditampilkan dalam format yang mudah dibaca, biasanya dalam bentuk tabel. Informasi yang ditampilkan umumnya meliputi:
- Suhu
- Kondisi cuaca (cerah, mendung, hujan, dll.)
- Kelembapan
- Dan mungkin informasi tambahan seperti kecepatan angin, tekanan udara, dll.

3. Fitur Tambahan: Beberapa aplikasi cuaca juga menawarkan fitur tambahan seperti:
- Menyimpan Kota Favorit: Pengguna dapat menyimpan beberapa kota favorit untuk memudahkan akses.
- Ekspor/Impor Data: Data cuaca dapat disimpan ke dalam file (misalnya, CSV) atau diimpor dari file.
- Notifikasi: Aplikasi dapat memberikan notifikasi kepada pengguna tentang perubahan cuaca yang signifikan, seperti peringatan dini cuaca buruk.
- Grafik Cuaca: Beberapa aplikasi menampilkan grafik perubahan suhu atau kelembapan dalam beberapa hari terakhir.

**Komponen Utama dan Cara Kerjanya:**

1. Antarmuka Pengguna (GUI): Bagian yang berinteraksi langsung dengan pengguna. Terdiri dari elemen-elemen seperti kotak teks untuk memasukkan nama kota, tombol untuk melakukan pencarian, tabel untuk menampilkan data, dan mungkin beberapa tombol tambahan untuk fitur-fitur lain.
2. Logika Aplikasi: Bagian yang menjalankan proses utama aplikasi. Ketika pengguna memasukkan nama kota dan menekan tombol pencarian, aplikasi akan:
- Membuat permintaan ke API: Mengirim permintaan ke API OpenWeatherMap dengan menyertakan nama kota yang dimasukkan pengguna.
- Menerima Respons: Menerima data cuaca dalam format JSON dari API.
- Mengurai Data: Mengubah data JSON menjadi format yang dapat dipahami oleh aplikasi.
- Menampilkan Data: Menampilkan data cuaca yang telah diurai ke dalam antarmuka pengguna.
3. API OpenWeatherMap: Layanan web yang menyediakan data cuaca secara real-time. Aplikasi ini menggunakan API ini untuk mendapatkan data cuaca berdasarkan lokasi yang ditentukan.
4. JSON: Format data yang ringan dan mudah dibaca oleh mesin. Data cuaca yang diterima dari API OpenWeatherMap biasanya dalam format JSON.

**Proses Secara Singkat:**

1. Pengguna membuka aplikasi dan memasukkan nama kota.
2. Aplikasi mengirimkan permintaan ke API OpenWeatherMap.
3. API mengirimkan data cuaca dalam format JSON.
4. Aplikasi mengurai data JSON dan menampilkannya dalam bentuk yang mudah dibaca.

**Teknologi yang Digunakan:**

- Java: Bahasa pemrograman yang digunakan untuk membangun aplikasi.
- Swing: Library untuk membuat antarmuka pengguna grafis dalam Java.
- JSON: Format data yang digunakan untuk pertukaran data.
- HTTP: Protokol yang digunakan untuk berkomunikasi dengan API OpenWeatherMap.



![Demo GIF](https://github.com/seidi255/AplikasiCekCuacaSederhana/blob/main/img/DEmo%20cek%20cuaca.gif)
