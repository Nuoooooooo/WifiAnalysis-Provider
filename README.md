# WifiAnalysis-Provider
Wireless network assignment about wifi analysis and the provider used

Group 1:
- Muhammad Faizal
- Muhammad Sandu Paswallah
- Pratama Arjan Rangkuti
- Rizky Rivaldo

# Wifi Analysis

![7fbffc84-adc2-4d51-a453-8037b9f590bd](https://github.com/user-attachments/assets/6b33c7f1-85c1-4ed9-ab38-dd84c8e101b1)

## A. Kekuatan Sinyal Wi-Fi (dari yang terkuat ke yang terlemah):
AA → -51 dBm (Sinyal kuat)
Izhar → -51 dBm (Sinyal kuat)
Infinix HOT 11S NFC → -65 dBm (Sinyal lebih lemah)
Kekuatan sinyal Wi-Fi diukur dalam dBm (decibel-milliwatts), di mana nilai yang lebih mendekati 0 dBm menunjukkan sinyal yang lebih kuat. Dalam daftar ini, AA dan Izhar memiliki kekuatan sinyal -51 dBm, yang tergolong kuat dan stabil, cocok untuk penggunaan internet dengan kecepatan tinggi serta aktivitas seperti streaming atau gaming online. Sementara itu, Infinix HOT 11S NFC memiliki sinyal -65 dBm, yang masih cukup baik tetapi lebih lemah dibandingkan dua jaringan lainnya, sehingga mungkin mengalami penurunan kecepatan atau ketidakstabilan jika ada gangguan seperti dinding tebal atau banyak perangkat yang terhubung. Jika sinyal Infinix HOT 11S NFC dirasa kurang stabil, pengguna dapat mencoba mendekatkan perangkat ke router atau berpindah ke kanal yang lebih bebas dari interferensi.

## B. Analisis Bandwidth Analog Wi-Fi
Bandwidth analog Wi-Fi pada frekuensi 2.4 GHz terbagi menjadi 13 kanal utama, di mana setiap kanal memiliki lebar 20 MHz dengan sedikit overlap antar kanal, kecuali kanal 1, 6, dan 11 yang tidak saling tumpang tindih. Pada gambar Wi-Fi Analyzer, terdapat tiga jaringan Wi-Fi dengan penggunaan kanal sebagai berikut: Izhar menggunakan kanal sekitar 6-7, sementara AA dan Infinix HOT 11S NFC menggunakan kanal 12-13, yang berpotensi mengalami interferensi karena kanal tersebut berada dalam area overlapping. Overlapping ini dapat menyebabkan penurunan bandwidth efektif, peningkatan latensi, serta gangguan koneksi, terutama jika banyak perangkat terhubung. Dalam bandwidth analog, semakin tinggi tingkat interferensi antar kanal, semakin kecil kapasitas data yang bisa dikirim dalam waktu tertentu, sehingga kecepatan internet dapat menurun. Untuk meningkatkan efisiensi bandwidth, sebaiknya jaringan Wi-Fi menggunakan kanal yang minim overlap, seperti 1, 6, atau 11, agar transmisi data lebih optimal dan minim gangguan dari jaringan lain. Selain itu, pemilihan kanal yang lebih sepi dan menggunakan perangkat dengan dukungan teknologi dual-band (2.4 GHz & 5 GHz) dapat membantu mengurangi masalah interferensi serta meningkatkan kualitas koneksi.

## C. Kesimpulan 
Berdasarkan analisis sinyal Wi-Fi, semakin dekat perangkat dengan modem, maka sinyal yang diterima akan semakin kuat, seperti yang terlihat pada jaringan AA dan Izhar yang memiliki kekuatan sinyal -51 dBm, menunjukkan koneksi yang stabil dan berkualitas baik. Sebaliknya, jaringan Infinix HOT 11S NFC memiliki sinyal -65 dBm, yang lebih lemah, kemungkinan karena jaraknya lebih jauh dari modem atau terhalang oleh dinding dan objek lain. Secara umum, sinyal Wi-Fi melemah seiring bertambahnya jarak serta dipengaruhi oleh hambatan fisik seperti dinding, lantai, dan perangkat elektronik yang dapat menyebabkan interferensi. Oleh karena itu, untuk mendapatkan kualitas sinyal terbaik, perangkat sebaiknya berada dalam jarak dekat dengan modem, atau jika memungkinkan, menggunakan Wi-Fi extender atau berpindah ke frekuensi 5 GHz untuk performa yang lebih optimal pada jarak menengah.

# Provider Analysis
In this analysis we using three diffrent provider that is XL Axiata, Telkomsel, Tri. We analyze impact from how far the mobile celuler from provider BTS (Base Transciever Station) and we using two range in this test and we using >100 meter (Over hundred meter) and <100 meter (Under hundred meter). This is the network category :
- Exellent  : > -80 dBm and -10 dB
- Good      : -81 to -90 dBm and -11 to -15 dB
- Mid Cell  : -91 to -100 dBm and -16 to -20 dB
- Cell Edge : < -100 and < -20

## A. Over 100 Meter
## XL Axiata
  
  ![14f682af-f1dd-498d-85f8-dc62b43226f3](https://github.com/user-attachments/assets/31dc3f12-03e2-4409-b4b1-8b697df69280 ) 


LTE XL Axiata on over 100 meter from the BTS like from this image is :
- RSRP (Reference Signal Received Power)    : -96
- RSRQ (Reference Signal Received Quality)  : -17
- Bandwidth                                 : 3
- ASU (Arbitary Strength Unit)              : 45

The measurement results from the application have the following results:
![image](https://github.com/user-attachments/assets/50d5b5ff-0482-43e3-815a-1da64cb11d0f)

- Download  : 25.3 Mbps
- Upload    : 11.7 Mbps
- Jitter    : 7 ms
- PING      : 49 ms


Depend on this analysis we can conclude that LTE XL Axiata network from distance over 100 meter can categorize as Mid Cell. It depend on RSRP, RSRQ, ASU, PING, Jitter, Download, and Upload with pretty good score.

## Telkomsel

![WhatsApp Image 2025-02-12 at 10 33 48 PM (2)](https://github.com/user-attachments/assets/02f69a04-3608-4129-9cab-618489f797fa)


LTE Telkomsel on over 100 meter from the BTS like from this image is :
- RSRP (Reference Signal Received Power)    : -95
- RSRQ (Reference Signal Received Quality)  : -15
- Bandwidth                                 : 3
- ASU (Arbitary Strength Unit)              : 48

The measurement results from the application have the following results:
![WhatsApp Image 2025-02-12 at 10 33 48 PM (1)](https://github.com/user-attachments/assets/9e9bcc79-dad3-41e1-82be-133c5e03089f)



- Download  : 15,1 Mbps
- Upload    : 8,0 mpbs
- Jitter    : 8 ms
- PING      : 29 ms

Depend on this analysis we can conclude that LTE Telkomsel network from distance over 100 meter can categorize as Mid Cell. It depend on RSRP, RSRQ, ASU, PING, Jitter, Download, and Upload with pretty good score.

## Tri

![11fc2439-de1b-4938-bdd5-4c079225454d](https://github.com/user-attachments/assets/e8c982fb-0dda-4b5f-a96f-142d50385506)



LTE Tri on over 100 meter from the BTS like from this image is :
- RSRP (Reference Signal Received Power)    : -94
- RSRQ (Reference Signal Received Quality)  : -10
- Bandwidth                                 : 3
- ASU (Arbitary Strength Unit)              : 40


![ad1feaa2-f2d3-45f2-8f11-4dcd10bfcbba](https://github.com/user-attachments/assets/c63cdbfd-677d-4f5b-a38a-043b9dee2a74)

The measurement results from the application have the following results:

- Download  : 12 Mbps
- Upload    : 28 Mbps
- Jitter    : 5 ms
- PING      : 54 ms

Depend on this analysis we can conclude that LTE Tri network from distance over 100 meter can categorize as Mid Cell. It depend on RSRP, RSRQ, ASU, PING, Jitter, Download, and Upload with pretty good score.


    
## A. Under 100 Meter  
## XL Axiata
![WhatsApp Image 2025-02-12 at 9 20 10 PM](https://github.com/user-attachments/assets/efd9ad6b-ad01-45df-84c6-d239d3807822)
![WhatsApp Image 2025-02-12 at 9 20 11 PM](https://github.com/user-attachments/assets/fba5e1bd-5c23-4b0e-9a4d-c872cadd3738)

LTE XL Axiata on over 100 meter from the BTS like from this image is :
- RSRP (Reference Signal Received Power)    : -55
- RSRQ (Reference Signal Received Quality)  : -9
- Bandwidth                                 : 3
- ASU (Arbitary Strength Unit)              : 80



The measurement results from the application have the following results:

![image](https://github.com/user-attachments/assets/f6f10af9-b9df-491a-a37a-aa03af171798)

- Download  : 49.1 Mbps
- Upload    : 27.3 Mbps
- Jitter    : 4 ms
- PING      : 54 ms


Depend on this analysis we can conclude that LTE XL Axiata network from distance over 100 meter can categorize as Excellent. It depend on RSRP, RSRQ, ASU, PING, Jitter, Download, and Upload with very high score.

XL Axiata BTS Picture
![b14dc988-1293-4f2a-be6e-4c2f9f9647d8](https://github.com/user-attachments/assets/a108fdf6-a413-4275-a580-8dd3ca96224e)


## Telkomsel
![WhatsApp Image 2025-02-12 at 10 33 48 PM](https://github.com/user-attachments/assets/d92011ad-85ef-4954-8d39-de45b214a853)


LTE Telkomsel on over 100 meter from the BTS like from this image is :
- RSRP (Reference Signal Received Power)    : -68
- RSRQ (Reference Signal Received Quality)  : -9
- Bandwidth                                 : 40
- ASU (Arbitary Strength Unit)              : 47


 ![WhatsApp Image 2025-02-12 at 10 33 48 PM (4)](https://github.com/user-attachments/assets/7c3cd25d-5918-4cab-9724-deb47bc9cb84)

The measurement results from the application have the following results:


- Download  : 132, 1 Mbps
- Upload    : 51,6 Mbps
- Jitter    : 4 ms
- PING      : 23 ms

Depend on this analysis we can conclude that LTE Telkomsel network from distance under 100 meter can categorize as Excellent. It depend on RSRP, RSRQ, ASU, PING, Jitter, Download, and Upload with very high score.

Telkomsel BTS picture
![745fdd81-027a-4fbc-8109-6b3d964cdfd8](https://github.com/user-attachments/assets/681cb30f-8c31-49bf-818f-a9a25eba6e59)


## Tri
![f1adc8b1-5cc5-438f-b907-d548c4a31bfb](https://github.com/user-attachments/assets/77236c62-90a7-43cb-8035-a9bce947dd15)


LTE Telkomsel on over 100 meter from the BTS like from this image is :
- RSRP (Reference Signal Received Power)    : -74
- RSRQ (Reference Signal Received Quality)  : -9
- Bandwidth                                 : 3
- ASU (Arbitary Strength Unit)              : 62


![b5345b8b-9736-47e8-8569-e8b2999d1e33](https://github.com/user-attachments/assets/99474438-c0d3-463c-954e-e7dd85d87fd5)

The measurement results from the application have the following results:


- Download  : 65.9 Mbps
- Upload    : 35.2 Mbps
- Jitter    : 4 ms
- PING      : 59 ms

Depend on this analysis we can conclude that LTE Tri network from distance over 100 meter can categorize as Excellent . It depend on RSRP, RSRQ, ASU, PING, Jitter, Download, and Upload with high score.

Tri BTS picture
![d7c5a573-237a-43c1-a62d-39808f19afd4](https://github.com/user-attachments/assets/828cf10d-6268-4f0f-982e-a2a06cf26577)


=======
