# Struktur Sistem Operasi

>## A. Struktur Sederhana (Monolitchic Method)

System monolitik ini berisikan kumpulan dari berbagai prosedur yang dapat dipanggil oleh persedur lainnya untuk menjalankan sistem. Sehingga antar prosedur dapat saling bekerja sama dalam menjalankan sebuah sistem.

Beberapa contoh sistem operasi yang memiliki system monolitic adalah seperti MS DOS dan UNIX. MS DOS lebih berfokus pada menyediakan fungsional yang lebih sedikit dan tidak bisa dibagi dalam beberapa modul.

Sedangkan UNIX lebih berfokus pada setiap prosedur dapat memanggil prosedur lainnya, sehingga tiap prosedur bisa saling berkomunikasi, dan kernel akan berisi semua layanan yang telah disediakan oleh sistem yang akan digunakan oleh pengguna. 

**Kelebihan yang dimiliki oleh system monolitic adalah akses layanannya lebih cepat karena dilakukan pada satu tempat.**

>## B. Struktur Berlapis (Layered Systems)

Sistem operasi memiliki sistem layer. Maksudnya adalah sistem operasi terdiri dari beragam layer mulai dari bahwa hingga atas. Sehingga masing-masing layer memiliki tujuan dan fungsi masing-masing.

Lapisan layer paling bawah biasa digunakan sebagai perangkat keras, sedangkan lapiran layer paling atas digunakan sebagai user-interface. Adanya struktur berlayer ini digunakan untuk mengurangi kompleksitas rancangan dari implementasi sistem operasi.

Setiap lapisan layer dari struktur tersebut merupakan hasil implementasi dari objek abstrak. Dimana hasil implementasi tersebut merupakan enkapsulasi data dan operasi yang bisa dimanipulasi.

Agar lebih jelas, berikut jenis layer yang digunakan dalam sistem operasi:

1. Layer Perangkat keras

Bagian yang berhubungan dengan perangkat keras. Biasanya terdiri dari sirkuit elektronik yang digunakan untuk membersihkan register dan membaca lokasi memori, set instruksi pada prosesor, dan interupsi yang berisikan perintah yang baru dijalankan.

2. Layer Sistem Operasi

Bagian sistem operasi yang berhubungan langsung dengan programmer yang spesifik pada bagian sistem operasinya. Sehingga akan lebih teknis pembahasannya. Layer ini biasanya terdiri dari ide dalam eksekusi program, penyimpanan sekunder dari komputer, dan lamat logic dari setiap proses yang akan dijalankan. Segala hal tersebut membutuhkan kode program agar dapat dijalankan dengan benar dan sesuai dengan yang diharapkan.

3. Layer Kelengkapan

Pada bagian ini termasuk kelengkapan dari bagian sebelumnya, sehingga masih terkait dan berhubungan dengan programmer. Layer kelengkapan bertugas untuk mengatasi komunikasi informasi yang terjadi dan termasuk pesan-pesan antar proses.

Selain itu juga terdapat penyimpanan jangka panjang, akses dari perangkat eksternal menggunakan antarmuka (user-interface) yang standar, dan bertanggung jawab untuk memastikan hubungan eksternal dan internal identifier yang dimulai dari sumber daya dan objek sistem.

4. Layer Program Aplikasi

Pada bagian ini berhubungan dengan pengguna aplikasi komputer (end-user). Sehingga berkaitan erat dengan user-interface yang mudah digunakan oleh user agar dapat mengakses aplikasi. Sehingga sistem dapat memproses informasi yang dibutuhkan oleh user.

>## C. Mikro Kernel

Fungsi dari kernel mikro ini adalah untuk mempermudah komunikasi yang terjadi antara program client dengan beragam layanan yang terdapat pda ruang user. Sehingga dengan adanya kernel mikro ini dapat mempermudah dan memperluas sistem operasi, dan mudah ketika akan diubah (transformasi) ke arsitektur yang lebih baru. Selain itu, dengan menggunakan kernel mikro, kode program akan aman karena lebih kecil.

# Kesimpulan

