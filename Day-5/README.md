Task :

NodeJS
- Deploy app wayshub-frontend
- Berjalan di port 3000
- Menggunakan NodeJS 10 & 12
```https://github.com/dumbwaysdev/wayshub-frontend```
- Jawab :
-  Untuk men deploy app wayshub-frontend menggunakan NodeJS, terlebih dahulu kita install NodeJS,nvm(version) dan npm(package)
-  Kita bisa melihat instalasi pada web nodejs download, karena app menggukan version 10/12 maka disini menginstall version 12
<img width="1115" height="790" alt="Screenshot 2026-02-04 220617" src="https://github.com/user-attachments/assets/826e0059-ba75-4cb2-8969-98cf06b88013" />

- setelah itu kita bisa melakukan clone repo dari app-nya, dengan cara git clone https://github.com/dumbwaysdev/wayshub-frontend
<img width="960" height="294" alt="Screenshot 2026-02-04 225956" src="https://github.com/user-attachments/assets/d0b2134a-b180-484c-a306-9c65a5092b97" />

- lalu jalankan npm install agar saat melakukan start tidak ada modul yang tertinggal, setalah itu bisa menjalankan npm start. untuk start disini sebenarnya sudah di konfigurasi yang terdapat di package.json
<img width="1115" height="628" alt="Screenshot 2026-02-05 231633" src="https://github.com/user-attachments/assets/c25cd2c5-ea8d-451b-9783-9822c677dd8a" />

- setalah menjalankan npm start, pada vm akan menampilkan seperti pada gambar
<img width="960" height="1032" alt="Screenshot 2026-02-04 231312" src="https://github.com/user-attachments/assets/a5f635ac-f8bc-417c-8747-35b97fe9dfda" />

- lalu kita bisa menjalankan pada web dengan cara mengetik ipserver:port (192.168.100.208:3000), lalu akan menampilkan app-nya
<img width="1920" height="1032" alt="Screenshot 2026-02-04 231425" src="https://github.com/user-attachments/assets/4fa6bc7c-d46c-4d62-8499-8030d0ada3cd" />

Python
- Deploy app menampilkan text nama kalian!
- Berjalan di port 5000 & bisa dibuka melalui web
- Jawab :
- Berbeda dengan NodeJS, kita tidak perlu install python karena ubuntu sudah terdapat python3 di dalamnya. Namun kita harus menginstal pip(package) dengan cara sudo apt install pyhon3-pip
- setalah itu kita buat direktori python dan menginstal flask didalamnya dengan cara pip install flask
<img width="1115" height="628" alt="Screenshot 2026-02-05 180942" src="https://github.com/user-attachments/assets/1af8fa2e-04e2-401a-a709-aadd611cddb4" />

- lalu buat file index.py yang berisi tentang konfigurasi sederhana tentang app yang akan kita deploy
<img width="1115" height="628" alt="Screenshot 2026-02-05 181100" src="https://github.com/user-attachments/assets/10dfd08c-2fad-4357-b865-67553f8a2dd1" />

- sebelum menajalankan app pastikan port yang setting sudah allow 
<img width="960" height="419" alt="Screenshot 2026-02-05 181728" src="https://github.com/user-attachments/assets/4dc0fb51-99c9-4fd4-bfa0-f65c7e53c968" />

- lalu jalankan file tersebut dengan cara python3 index.py dan kita melihat di web dengan mengetik ipserver:port(192.168.100.208:5000)
<img width="1920" height="1080" alt="Screenshot 2026-02-05 181656" src="https://github.com/user-attachments/assets/0712bdcb-2286-469f-b28a-059eaeff2db2" />

Golang
- Deploy app menampilkan text "Golang geming!"
- Jawab :
- Pertama kita bisa mendowload file instalasi pada web go.dev, lalu cari tar.gz untuk linux, setelah itu kita bisa mendownload melalui vm dengan cara ( wget link file yang akan di download)
- lalu kita bisa menginstall golang terlebih dahulu dengan cara $ rm -rf /usr/local/go && tar -C /usr/local -xzf go1.25.7.linux-amd64.tar.gz (bisa melihat installasi di web go.dev install)
<img width="1920" height="1080" alt="Screenshot 2026-02-05 182319" src="https://github.com/user-attachments/assets/04eecb90-7f46-4806-931c-0f355d5fce9a" />

- kita juga harus ubah user ke root karena akan ada perubahan di system ubuntu, setelah itu kita export PATH dengan cara export PATH=$PATH:/usr/local/go/bin, namun kita harus kembali lagi ke user terlebih dahulu
<img width="960" height="1032" alt="Screenshot 2026-02-05 182615" src="https://github.com/user-attachments/assets/a8f19d8d-b82e-4510-8064-b6213ff40c52" />

- setelah installasi golang kita bisa buat direktori golang dan buat  file index.go yang berisi app sederhana kita
<img width="960" height="248" alt="Screenshot 2026-02-05 183303" src="https://github.com/user-attachments/assets/9ec903d7-0ad0-43de-823d-85b99b2ec548" />

- Lalu kita bisa app atau file index.go dengan cara go run index.go
<img width="960" height="208" alt="Screenshot 2026-02-05 183253" src="https://github.com/user-attachments/assets/dc1be2ef-f51b-4ca0-b3a8-8dd4efd7b727" />

Note : Semua app WAJIB bisa diakses dengan **UFW enabled** (firewall menyala abangkuh 🔥🔥🔥)
