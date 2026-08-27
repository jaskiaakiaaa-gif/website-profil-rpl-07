# website-profil-rpl-07
# Website Profil XI RPL
Website ini merupakan proyek pembelajaran kolaborasi Git dan GitHub.

## Anggota Tim
1. Jaskia - Project Manager
2. Zulmi - Developer Profil
3. Herlino - Developer Anggota
4. Faisal - Developer Kontak
```

#Pertanyaan
1. apa arti hasil git status? -untuk melihat kondisi

#Pertanyaan Analis
1.Mengapa setiap developer tidak langsung bekerja pada main ? -Biar main gak error: Kalau kodenya bug pas dites, kode utama di main tetep aman dan bisa dipakai

#Pertanyaan
Perbedaannya:

git commit -m "update": Terlalu umum dan ambigu. Tidak menjelaskan kode atau bagian mana yang diubah.

git commit -m "Menambahkan halaman profil kelas": Spesifik dan jelas. Menggambarkan tindakan pasti yang dilakukan pada kode.

Mana yang lebih baik?

Yang kedua ("Menambahkan halaman profil kelas"), karena memudahkan tim memahami riwayat perubahan proyek.

#Pertanyaan Analis
1. Fungsi git pull? - untuk update kode terbaru dari github ke laptop 
2.Apa yang terjadi jika programmer tidak melakukan git pull ? - kode bisa bertabrakan dengan yang punya teman
3.Mengapa main harus dijaga agar tetap stabil? -Karena main itu sumber utama kode yang siap rilis. Kalau main error, kerjaan seluruh tim bakal ikut rusak

#Pertanyaan Konflik
1.Mengapa conflict terjadi?
Karena dua orang (atau lebih) mengubah baris kode yang sama di file yang sama secara bersamaan.

2.Apakah conflict berarti Git rusak?
Tidak. Itu tanda Git berfungsi normal untuk mencegah kode temanmu tertimpa secara tidak sengaja.

3.Siapa yang harus menentukan versi kode yang benar?
Developer (programmer) yang sedang mengerjakan proyek tersebut melalui diskusi bersama.

4.Mengapa komunikasi antar programmer penting?
Agar tau siapa ngerjain bagian mana, sehingga mencegah bentrok kode (conflict) dan salah paham saat menggabungkan fitur.


#Refleksi Individu (jaskia)
1.Perbedaan bekerja sendiri vs pakai Git & GitHub:
Bekerja sendiri kodenya rawan hilang/tertimpa, sedangkan pakai Git & GitHub riwayat perubahan tersimpan rapi dan gampang kolaborasi bareng tim.

2.Manfaat branch:
Bisa mencoba fitur baru atau mengedit kode tanpa takut merusak kode utama (main).

3.Mengapa Pull Request diperlukan?
Buat mengajukan izin penggabungan kode dari branch kita ke main, sekaligus ajakan buat dicek bareng tim.

4.Manfaat Code Review:
Menemukan bug lebih cepat, menjaga kualitas kode tetap rapi, dan saling belajar dari cara koding teman.

5.Error apa yang paling sulit kalian selesaikan? 
Saat melakukan git push lalu gagal atau ditolak (rejected) karena kode di lokal belum sinkron dengan GitHub.

6.Bagaimana kalian menemukan solusinya?
Diskusi bareng teman Melakukan git pull terlebih dahulu untuk mengambil kode terbaru dari GitHub, lalu menyelesaikan bentrok jika ada, baru di-push ulang.

7.Apa kontribusi terbesar kalian dalam kelompok? 

Membantu membuat tampilan halaman profil/anggota,melakukan pull request dan merapikan struktur file HTML

8.Kebiasaan yang akan dipertahankan:
Selalu buat branch baru pas mau nambah fitur, rutin commit dengan pesan yang jelas, dan rajin pull kode terbaru.
