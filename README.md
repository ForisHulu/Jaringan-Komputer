# Jaringan-Komputer

**Laporan: Implementasi Program Client-Server Ping-Pong Menggunakan Python**

Program ini mengukur waktu tempuh bolak-balik (RTT) antara klien dan server menggunakan protokol UDP. Klien mengirimkan pesan "ping" dan server membalas dengan "pong", mencatat waktu respons untuk setiap paket.

**Tujuan Program :**
Mengukur RTT antara klien dan server menggunakan UDP.
Mendeteksi kehilangan paket.

**Cara Menjalankan Program :**
server.py: Program server.
foris.py: Program klien.
Buka Terminal (dua jendela jika menggunakan Raspberry Pi).

**Jalankan server dengan perintah 1:**
python3 server.py
Server akan menunggu pesan "ping" dari klien.
**Jalankan klien dengan perintah 2:**
python3 foris.py
Klien akan mengirimkan 10 pesan "ping" dan menampilkan RTT untuk setiap balasan "pong".
Output Program

**Server: Menampilkan pesan "ping" yang diterima dan membalas dengan "pong".
Klien: Menampilkan RTT untuk setiap pesan atau pesan "Timeout" jika paket hilang.**

**Kesimpulan :**
Program ini berhasil mengukur RTT dan mendeteksi paket yang hilang dengan protokol UDP. Ini menunjukkan cara kerja komunikasi klien-server dengan UDP yang tidak menjamin keandalan pengiriman data.
