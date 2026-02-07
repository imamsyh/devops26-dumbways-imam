Challenge App On Background :
1. NodeJS + Python berjalan di background (tanpa kondisi attached di terminal)
   - artinya, teman-teman tetep bisa menggunakan terminal di window yang sama namun app tetap berjalan

2. Golang bisa dibuka di browser kalian, menampilkan text "Jangan lupa sahur baby gurl rawr"
------------------------------------------------------------------------------------------------------
1. NodeJS + Python berjalan di background (tanpa kondisi attached di terminal)
- menjalankan dengan nohup (no hang up) dengan command nohup <command> > <logfile> 2>&1 &
- jalankan command di dalam direktori masing-masing, lalu jalankan di web
<img width="1920" height="1030" alt="Screenshot 2026-02-07 141038" src="https://github.com/user-attachments/assets/be22d908-f102-4d19-9781-c93b296caf25" />

- untuk mematikan dengan cara kill PID , bisa melihat PID yang berjalan di sudo lsof -i :port
<img width="1920" height="1019" alt="Screenshot 2026-02-07 141935" src="https://github.com/user-attachments/assets/0479741d-973b-45c6-98f0-8ebf6e26ab03" />

2. Golang bisa dibuka di browser kalian, menampilkan text "Jangan lupa sahur baby gurl rawr"
- Buat file golang atau edit file yang sudah ada
<img width="960" height="1032" alt="Screenshot 2026-02-07 144309" src="https://github.com/user-attachments/assets/58d20a5b-ff22-4eee-b5a6-bc2e9cec6a3b" />

- set file seperti pada gambar
- import net/http : untuk handle http req dan res
- fmt.Fprintln(w, "Teks yang dikirim ke web") : w, untuk http response, jika tidak pakai maka akan muncul di server
<img width="960" height="1032" alt="Screenshot 2026-02-07 144320" src="https://github.com/user-attachments/assets/021ec7a4-a33f-4b34-9dd8-4e46513411e2" />

- karena disini set port pakai 7000 maka jangan lupa untuk allow port 7000
- dan jalankan file go run web.go
- lalu jalankan ip server:port di web
<img width="1920" height="1001" alt="Screenshot 2026-02-07 144441" src="https://github.com/user-attachments/assets/6da747fa-6ce3-4476-a977-2c66f6319228" />



