![image](https://github.com/user-attachments/assets/2909bda9-1c2f-43a0-b32d-8572ce16fd22)






Untuk mengatasi kesulitan mengontrol tagihan dan kurangnya kesadaran konsumsi energi real-time, sistem
 monitor energi prabayar ini dirancang dengan Mikrokontroler ESP32 sebagai pusatnya. Sistem bekerja dengan
 Sensor PZEM-004T V3 yang mengukur pemakaian listrik pada Beban Listrik, lalu ESP32 memproses data
 tersebut untuk mengurangi saldo prabayar pengguna. Jika saldo habis, ESP32 menginstruksikan Modul Relay
 untuk memutus aliran listrik. Pengguna dapat memantau dan mengontrol seluruh sistem, termasuk melakukan
 isi ulang, melalui Antarmuka Web (HTML) yang diakses via WiFi, dengan data yang juga bisa ditampilkan pada
 Layar LCD/TFT lokal.

 Sistem ini dirancang untuk memantau konsumsi daya listrik secara real-time menggunakan sensor arus
 (PZEM-004T V3) dan sensor tegangan. Data dari sensor dibaca dan diproses oleh mikrokontroler ESP32, yang
 menghitung konsumsi energi listrik (dalam kWh) dan mengonversinya menjadi estimasi biaya berdasarkan
 tarif listrik yang dapat diatur secara manual.
 Hasil pemantauan dapat ditampilkan melalui beberapa media, yaitu serial monitor, serta dikirim melalui
 koneksi WiFi untuk diakses secara jarak jauh, misalnya ke server lokal atau endpoint tertentu. Selain itu,
 sistem memungkinkan pengaturan batas konsumsi daya, sehingga dapat memberikan peringatan atau
 notifikasi apabila konsumsi melebihi batas yang telah ditentukan.
 Dengan fitur monitoring, perhitungan biaya, dan notifikasi, sistem ini dapat menjadi solusi praktis untuk
 membantu pengguna dalam mengelola penggunaan listrik secara efisien
![image](https://github.com/user-attachments/assets/d0843ca8-f7f3-40f4-88d2-3ce4feb65677)

PRINSIP KERJA ALAT PRINSIP KERJA ALAT
 Untuk mengatasi permasalahan tersebut, sistem Monitor Energi Prabayar Berbasis ESP32 dengan Sensor PZEM-004T dan Antarmuka
 Web ini dirancang sebagai solusi yang komprehensif. Sistem ini memungkinkan pengguna untuk:
 1.Melakukan Pembayaran di Muka (Prabayar)
 2.Memantau Konsumsi Energi secara Real-Time
 3.Melihat Riwayat dan Statistik Pemakaian
 4.Mengelola Anggaran Listrik
 Komponen utama sistem meliputi:
 1.ESP32: Sebagai mikrokontroler utama yang menjadi otak sistem, menjalankan server web, membaca sensor, mengontrol relay, dan
 mengelola logika prabayar.
 2.Sensor PZEM-004T: Untuk mengukur parameter listrik secara akurat.
 3.Modul Relay: Sebagai saklar elektronik untuk menghubungkan atau memutuskan aliran listrik ke beban.
 4.Interface Web(HTML): Sebagai sarana interaksi utama pengguna dengan sistem.
 Dengan sistem ini, pengguna mendapatkan kendali penuh atas pemakaian dan biaya listrik mereka, mendorong penggunaan energi
 yang lebih bijak dan efisien
