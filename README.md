Crash Pulse 


Apa Itu Tools Ini?

Tools ini dibuat untuk pengujian Dos dan DDoS

PERINGATAN : TOOLS INI DIBUAT DENGAN TUJUAN EDUKASI.RESIKO DITANGGUNG SENDIRI.


---

Fitur Utama:

1. Dua Mode:

DoS: Serangan dari satu sumber.

DDoS: Serangan dari banyak IP lewat proxy.



2. Banyak Metode Serangan:

HTTP: GET, POST, HEAD.

TCP/UDP: Trafik langsung ke port tertentu.



3. Dukungan Proxy:

Bisa pake list proxy yang kamu punya (HTTP/HTTPS/SOCKS5).



4. Multithreading Power:

Jalankan ribuan thread buat ngirim trafik gila-gilaan.



5. Rate Limit:

Atur kecepatan serangan sesuai kebutuhan.



6. Custom User-Agent:

Bikin trafik lebih real, gak gampang ke-detect.



7. Monitoring Real-Time:

Selama uji coba, kamu bisa lihat statistiknya langsung.



8. Log Error ke File:

Error yang muncul otomatis dicatet di file biar gampang dianalisis.





---

Kelebihan tools?

Gampang Dipake: Interface simpel, cocok bahkan buat pemula.

Super Fleksibel: Kamu bebas atur semua parameter serangan.

Cepat & Efisien: Tools ini ringan tapi performanya ngebut.

Aman: Bisa dienkripsi biar gak gampang disalahgunakan.

Serbaguna: Cocok buat server kecil sampe enterprise.



---

Cara Pake Tools Ini:

1. Persiapan:

Install git,python dan tool ini dengan command :

pkg update && pkg upgrade && pkg install git python && git clone https://github.com/DarkLoic/CrashPulse




2. Jalanin Tools:

cd CrashPulse


3. Pilih Mode:

Pilih DoS atau DDoS sesuai kebutuhan.

Isi parameter yang diminta:

Metode Serangan (GET, POST, dll.).

Jumlah Thread.

Rate Limit (opsional).

File Proxy (kalau pake DDoS).



4. Mulai Uji Coba:

Tools langsung jalan, trafik dikirim ke server target.

Kamu bisa lihat status live, seperti jumlah request sukses, error, dll.


5. Analisis Hasil:

Kalau ada error atau hasil tertentu, cek file log yang udah disiapkan.



---

Note : Untuk mode DDoS memerlukan file proxylist.untuk itu,bisa dicari sendiri.disarankan memakai proxylist dengan protokol https atau socks5 agar traffic terenkripsi
---
