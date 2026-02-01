1. Buat sebuah diagram sebuah jaringan komputer dengan 4 device dengan kondisi : 
- IP Class C : 192.168.4.xxx 
- CIDR Block : 192.168.11.0/24 
 <img width="464" height="374" alt="image" src="https://github.com/user-attachments/assets/b3b7e832-128b-4fc8-92cd-50e95de9b834" />

2. Jelaskan perbedaan antara SH (Shell) dan BASH (Bourne-Again Shell)
Jawab :
Shell merupakan bahasa yang umum digunakan pada OS UNIX/Linux sedangkan BASH adalah jenis pengembangan dari shell itu sendiri yang mana lebih lengkap dan modern dan sering dijadikan default
Perbedaan :
	Shell	BASH
Fitur	Sederhana	Lebih lengkap dan modern
Script 	Terbatas	Sangat mendukung 
Digunakan	Unix Lama	Linux modern (sering dijadikan default)

 
3. Buat dokumentasi/kumpulan command linux yang kalian ketahui! (Command diluar materi akan diberi nilai ++)
- sudo apt update = update repo sebagai admin
 
- sudo apt list –upgradable = untuk melihat list repo yang bisa di upgarde
 
- mkdir  “nama folder” =  membuat folder
- ls = melihat isi direktori
- touch “nama file” = membuat file kosong
- ls -la = melihat isi direktori secara detail beserta file hidden
- cd  “nama direktori”/ = pindah ke direktori
- cd .. = kembali direktori sebelumnya  



- cp “nama file yang ada” “nama file baru” = copy file 
- mv  “nama file” “tujuan” = pindah file 
 
-echo “text” = menampilkan text
-echo “text” > “nama file” = membuat text dan menyimpan di file baru (jika belum ada file)
- cat “nama file” = menampilkan isi file
- echo “text” >> “nama file” = menambah text di akhir baris file
- echo “text baru” > “nama file yang sudah ada” = mengganti text dengan yang baru 
 
- find = mencari file
- find -type f = mencari semua file biasa
-find -type d = mencari seluruh direktori
 
-find -type f -name “nama file” = mencari file biasa (jika ada akan menampilkan lokasi file jika tidak ada maka tidak menampilkan apapun”
 


- grep “text” “nama file” = mencari text di dalam file (jika tidak ada maka tidak akan menampilkan apapun)
 
- nano “nama file” = menampilkan gui file sederhana  (bisa edit, tambah, hapus dll)
 
-chmod 777 file.js = mengubah hak akses kepada semua  user
- chmod 773 file.js = mengubah hak akses, hanya bisa tulis dan eksekusi untuk selain yang mempunyai file
 




-sudo chown root:root file.js = mengubah kepemilikan file
 
-history = melihat histori komen
-sudo su = berpindah ke user root
-exit = keluar dari user root
 

