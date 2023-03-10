# Rangkuman video 1
GIT merupakan salah satu software yang bisa melakukan Version Control System (VCS), VCS adalah sistem yang menerima dan mengelola rekaman perubahan dari source code, sedangkan GITHUB adalah web untuk mengelola project GIT

cara kerja GIT adalah kita bisa mengedit sebuah file kerja kita tanpa perlu menghasilkan file yang baru, lalu cara kerja GITHUB yaitu kita bisa mengedit sebuah file secara bersamaan, seperti halnya GoogleDrive namun GITHUB lebih felksibel 

istilah dalam GIT & GITHUB, antara lain:
1. repo = project folder kita
2. commit = rekaman/snapshot dari repo kita 
3. hash = penanda unik pada sebuh commit
4. checkout = berpindah dari sebuah commit
5. branch = cabang bebas dari sebuah commit
6. merge = menggabungkan branch 
7. remote = sumber yang memiliki repo
8. clone = mengambil remote dari repo
9. puch = mengirimkan commit dari repo
10. pull = mengirimkan commit dari repo 

# Rangkuman video 2
video 2 menjelaskan tentang cara menggunakan GITHUB, mulai dari membuat *repository*, sampai mengcommitnya 
![Screenshot (215)](https://user-images.githubusercontent.com/123804483/215266320-b1f0f189-4ca2-41dc-a044-d240981a98cb.png)

# Rangkuman video 3
video 3 menjelaskan tentang branch, dan menyambungkan branch ke master branch (merge)
![Screenshot (216)](https://user-images.githubusercontent.com/123804483/215268795-a80ff6ee-2684-4f8b-a695-812768ee8d6a.png)
![Screenshot (217)](https://user-images.githubusercontent.com/123804483/215268827-a32c9774-11c3-4bd9-aeb0-8177a58fb996.png)
![Screenshot (219)](https://user-images.githubusercontent.com/123804483/215269001-98c86344-a23d-466e-83fa-85f41e654701.png)

# Rangkuman video 4
fork/forking adalah menduplikat *repository* milik orang lain. Fork tidak sama dengan clone, fork mengdupliakt punya orang lain, sedangkan clone mengduplikat dari GITHU ke GIT (komputer local kita)

# Rangkuman video 5
video 5 menjelaskan cara instalasi sampai menggunakan GIT.
berikut adalah cara menggunakan GIT :
1. kita harus memilih folder yang akan jadi tempat file yang kana kita edit, lalu kita harus merubah folder biasa menjadi *repository* GIT

![Screenshot (227)](https://user-images.githubusercontent.com/123804483/215294660-dfa9cf97-decc-4135-a5eb-5007351b98dd.png)
![Screenshot (225)](https://user-images.githubusercontent.com/123804483/215294743-6d11a4cd-2205-481a-b93e-8ee7bb925144.png)

2. kita menambahkan file yang kan kita edit (untuk contohnya saya menggunakan python), tetapi kita masih belum bisa meng commit filenya, oeh karena itu kita perlu memasukkan nama dan email kita (usahakan nama dan email sama seperti yang ada pada GITHUB)
![Screenshot (223)](https://user-images.githubusercontent.com/123804483/215295162-83c35aa3-6f80-4ca4-a593-a8372d5fb16e.png)

3. kita bisa mengubah hasil kerja, dan lalu mengcommitnya (saya menggunakan file python, sedangkan di video menggunakan HTML) 

file python awal
![Screenshot (221)](https://user-images.githubusercontent.com/123804483/215295328-bd9996ee-9413-473f-adb3-f072693f508d.png)

file python sesudah kita edit 
![Screenshot (222)](https://user-images.githubusercontent.com/123804483/215295399-c4c6157f-7bcb-4a82-9b18-236ee30eac8f.png)

katika mengcommit kata harus tambahkan "-m" sebagai pesan apa yang sudah kita ubah 
![Screenshot (228)](https://user-images.githubusercontent.com/123804483/215295494-4043e09f-c486-4e84-a3f2-8e6e59440dc3.png)

# Rangkuman video 6
video 6 menjelaskan tentang cara penggunaan branch dan merge pada GIT, saya membuat program python yang berisikan tentang program sederhana kasir toko yang akan menggunakan sistem diskon dan promo.
1. kita masuk ke file yang akan kita edit
2. ketikan "git branch **nama branch**" di sini saya menamakan branch dengan **diskon**

![Screenshot (238)](https://user-images.githubusercontent.com/123804483/215303807-5a65336a-0005-4fab-a8f7-7f0d714fe282.png)

3. lalu kita masuk ke VScode dan kita tmabahkan file "diskon" dan membuat programnya 
![Screenshot (239)](https://user-images.githubusercontent.com/123804483/215303979-2e780d9b-3b92-4b83-a939-85ed2897962b.png)

4. lalu kita kembali ke GIT Bash dan ketikan "git add ." ini bertujuan untuk memsukkan file "diskon.py" kedalam stagging area, setelah itu kita ketikan "git checkout master" ini bertujuan untuk mengembalikan kita ke branch master, lalu kita lakukan lagi branching, untuk kali ini saya beri nama branch baru tersebut dengan "promo".
![Screenshot (241)](https://user-images.githubusercontent.com/123804483/215304377-991599c1-300c-4318-9b16-7ecbc275e836.png)
  
5. setelah itu kita checkout dan masuk ke branch promo, dan kita menambahkan file "promo.py" lalu kita buat program di file itu, jika sudah jangan lupa ketikan "git add ." untuk memeasukkan file  "promo.py" ke dalam stagging area 
6. setelah itu kita akan melakukan merging, caranya kit acheckout dan masuk ke master branch lalu kita ketikan "git merge diskon" maka file diskon.py akan menyatu dengan kasirtoko.py. kita lakukan juga hal serupa kepada promo.py. anda juga bisa mengilangkan branch jika merasa branch sudah tidak diperlukan lagi dengan cara ketikan "git -d **nama file**"

![Screenshot (243)](https://user-images.githubusercontent.com/123804483/215304615-4ff2d95d-0db2-4d73-803f-85adc94845a7.png)

ini adalah hasil akir dari branch dan merge dari 3 file
![Screenshot (244)](https://user-images.githubusercontent.com/123804483/215304619-a350d1f7-2005-40f3-b75f-3c5969263250.png)

# Rangkuman video 7
video 7 menjelaskan tentang cara bagaimana merging file yang sama tetapi isinya sedikit berbeda, dan juga menjelaskan bagaimana caranya kemabli ke bentuk file yang semula 
1. buat branch seperti pada video - video sebelumnya
2. di brnach baru ubah variabel atau apapun yang berbeda dengan master branch
3. lalu lakukan merge
 **NOTE** : saya sudah mengikuti cara seperti yang di video, namun saya tidak perlu memilih akan memakai yang mana, dan langung dipilih ke Branch baru, saya tidak tau mengapa, menurut saya mungkin ini disebabkan saya menggunakan python sedangkan "youtuber" menggunakan html
 
 # Rangkuman video 12
 video 12 menjelaskan tentang gitignore, yaitu metode saat kita mengcommit hanya file tertentu yang tercommit tidak smeua file
