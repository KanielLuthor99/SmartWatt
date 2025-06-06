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
