Challenge App On Background :
1. NodeJS + Python berjalan di background (tanpa kondisi attached di terminal)
   - artinya, teman-teman tetep bisa menggunakan terminal di window yang sama namun app tetap berjalan

2. Golang bisa dibuka di browser kalian, menampilkan text "Jangan lupa sahur baby gurl rawr"
------------------------------------------------------------------------------------------------------
1. NodeJS + Python berjalan di background (tanpa kondisi attached di terminal)
- menjalankan dengan nohup (no hang up) dengan command nohup <command> > <logfile> 2>&1 &
- jalankan command di dalam direktori masing-masing, lalu jalankan di web
<img width="1920" height="1080" alt="Screenshot 2026-02-07 141038" src="https://github.com/user-attachments/assets/e26302ca-5e1e-4260-8270-a8746d2d5a3f" />

- untuk mematikan dengan cara kill <PID> , bisa melihat PID yang berjalan di sudo lsof -i :port
<img width="1920" height="1080" alt="Screenshot 2026-02-07 141935" src="https://github.com/user-attachments/assets/26e77b75-3b11-4442-aec6-018b6a6a1ebd" />
