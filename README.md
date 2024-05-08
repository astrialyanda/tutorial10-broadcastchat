## 2.1 Original code of broadcast chat
![alt text](<Screenshot 2024-05-08 093952.png>)
Setiap client mendapatkan broadcast chat yang dikirimkan dari salah satu client akan terkirimkan ke semua client serta server. Setiap client mengirimkan pesan melalui command line, pesan tersebut akan terkirim ke server lalu server akan mengirimkan pesan tesebut ke semua client lainnya.

## 2.2 Modifying the websocket port
Jika port client dan server sama maka program akan berjalan dengan baik-baik saja. Jika kita mengganti port client dan server menjadi 8080 maka program tidak mengalami error. Namun, jika kita hanya mengganti misal port client menjadi 8080 dan port server tetap pada port 2000 maka akan terjadi error

## 2.3 Small changes. Add information to client
![alt text](<Screenshot 2024-05-08 110215.png>)
Perubahan dibuat sehingga IP address client juga terkirim ke client-client lainnya.