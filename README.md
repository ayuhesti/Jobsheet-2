# Jobsheet-2

A. ESP32 Capacitive Touch Sensor
 
 

https://user-images.githubusercontent.com/120068739/208413771-589ebf2c-f704-48dc-9efa-828192dea176.mp4




https://user-images.githubusercontent.com/120068739/208861317-828a3624-af10-45e2-9931-4a793641db91.mp4




Buatlah program agar LED menyala ketika sensor disentuh, dan LED akan 
mati ketika sensor tidak disentuh.




https://user-images.githubusercontent.com/120068739/208415407-3b457438-f1e6-46b2-bf36-666fa0e3def1.mp4




https://user-images.githubusercontent.com/120068739/208861639-f79923da-a193-4511-a98f-39b412b96c0e.mp4



Buatlah program agar ketika sensor disentuh, LED menyala Blink.




https://user-images.githubusercontent.com/120068739/208414005-d737b3dd-7e66-48cf-bf32-bdc79e002b38.mp4





https://user-images.githubusercontent.com/120068739/208861931-abad8c0d-6c45-4a01-b84f-dca8ec0f3e59.mp4



Buatlah program agar ketika LED menyala, maka pada Serial Monitor akan 
menampilkan angka yang akan bertambah setiap kali sensor disentuh.



https://user-images.githubusercontent.com/120068739/208414183-2af18c3c-fc8f-42f5-90ba-d565c23b7b21.mp4





https://user-images.githubusercontent.com/120068739/208862296-0f5a557f-a34b-4be3-9809-ff1100f3469e.mp4



Tambahkan 2 LED sehingga pada rangkaian terdapat 3 LED. Buatlah program agar ketika sensor disentuh, LED menyala menjadi running LED. Nyala running LED tersebut adalah bergerak dari kiri ke kanan, kemudian kanan ke kiri secara kontinyu.




https://user-images.githubusercontent.com/120068739/208414402-4cb94aa4-a5d5-4e50-96b7-2076a7cb0f4c.mp4




https://user-images.githubusercontent.com/120068739/208414494-edf2eaaa-33a7-4a4a-ae72-649ab6b57d5a.mp4




B. Mengakses Sensor DHT 11 (Single Wire / BUS)


Buatlah program agar ketika suhu rungan mencapai 30 derajat celcius, maka ESP32 akan menyalakan LED Merah dan buzzer secara beep (blink). Apabila suhu dibawah 30 derajat, ESP32 akan mematikan buzzer dan menyalakan LED berbentuk running LED seperti pada Percobaan A. Kemudian dokumentasikan hasilnya.



![WhatsApp Image 2022-12-21 at 16 05 53 (1)](https://user-images.githubusercontent.com/120068739/208881059-25ca54cd-c9ea-4b7e-9310-ea6ed7b7acbb.jpeg)





https://user-images.githubusercontent.com/120068739/208881098-622e9dc7-a0ff-4e4a-8d1b-2d4f5d04d4ea.mp4


C. Mengakses Sensor RFID (SPI Communication)

Dekatkan kartu atau Tag RFID ke RFID Reader. Amati dan analisis cara kerja programnya.



![image](https://user-images.githubusercontent.com/120068739/208885350-c77cfdd3-2ddc-4dbe-a570-2501df2acdd6.png)




https://user-images.githubusercontent.com/120068739/208881411-45487739-4b7c-4d8b-b95d-7a54cf77a09a.mp4



Buatlah program agar Tag RFID yang terbaca sebelumya dapat digunakan untuk hak akses. Apabila Tag RFID didekatkan pada Reader, maka LED Hijau akan menyala, servo akan bergerak ke kanan (lalu kembali ke posisi semula setelah 3 detik) dan di Serial Monitor akan tertampil pesan “Akses Diterima, Silahkan Masuk”. Apabila Tag RFID tidak dikenali, maka LED Merah akan menyala, servo tidak bergerak dan di Serial Monitor akan tertampil pesan “Akses Ditolak”. Gunakan Tag RFID lain untuk mencoba.



![image](https://user-images.githubusercontent.com/120068739/208885407-1653e60a-5363-4447-8830-18a6157478f7.png)



https://user-images.githubusercontent.com/120068739/208881757-80f9205f-7bc1-4b27-80da-e1d45941e940.mp4





https://user-images.githubusercontent.com/120068739/208881863-05b7f36d-4261-4c67-86a7-82b42685ade1.mp4
