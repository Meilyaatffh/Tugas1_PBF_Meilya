#### Tugas1_PBF_Meilya
# CODEIGNINER
***

<details>
<summary> PENGENALAN DASAR CODEIGNITER </summary>

### Definisi CodeIgniter
CodeIgniter merupakan salah satu framework yang populer di dunia pengembangan aplikasi dan web dengan menggunakan konsep Model-View-Controller (MVC). Sebagai platform open-source, CodeIgniter menjadi pilihan utama bagi para pengembang yang bekerja dengan bahasa pemrograman PHP. Penggunaan CodeIgniter bertujuan untuk mempercepat dan menyederhanakan proses pengembangan proyek. CodeIgniter mengadopsi model MVC, suatu pendekatan yang sangat cocok untuk merancang aplikasi atau website yang bersifat dinamis. Konsep MVC digunakan untuk memisahkan komponen utama ke dalam beberapa bagian, membentuk pola yang efektif saat proses pengembangan aplikasi. 


### Fitur Fitur CodeIgniter
* #### Model-View-Controller
  Model View Controller atau yang dapat disingkat MVC adalah sebuah pola arsitektur dalam membuat sebuah aplikasi dengan cara memisahkan kode menjadi tiga bagian yang terdiri dari:
  
  - Model : 
    Bagian yang bertugas untuk menyiapkan, mengatur, memanipulasi, dan mengorganisasikan data yang ada di database.
  - View
    Bagian yang bertugas untuk menampilkan informasi dalam bentuk Graphical User Interface (GUI).
  - Controller
    Bagian yang bertugas untuk menghubungkan serta mengatur model dan view agar dapat saling terhubung.
  
* #### Library Bawaan
  Dalam library bawaan ini, tersedia tutorial atau petunjuk yang mencakup masalah umum yang pernah dihadapi oleh pengembang lain dan solusi yang ditemukan, sehingga bisa menjadi referensi bagi pengguna lain. Fitur ini memungkinkan pengguna menemukan berbagai solusi seputar pemrograman. Pengembang CodeIgniter memiliki akses ke dokumentasi lengkap yang menjelaskan cara kerja sistem aplikasi serta informasi lainnya seputar pengembangan PHP. 
* #### Sangat Ringan
  Dalam era di mana kecepatan pemuatan aplikasi menjadi prioritas, CodeIgniter memberikan waktu pemuatan kurang dari satu detik setelah instalasi. Dengan respons cepat kurang dari 50 milisekon, CodeIgniter menjadi lebih cepat dibandingkan dengan beberapa framework lainnya. 
* #### Source Code yang Kompak
  Ukuran source code yang kecil menjadi keunggulan, menyederhanakan implementasi dan pembaruan sistem aplikasi. CodeIgniter memiliki source code yang kurang lebih hanya 2 MB, memudahkan pengguna untuk memahami CodeIgniter dan cara kerjanya.

### Keuntungan CodeIgniter
- Mudah dipelajari : CodeIgniter merupakan framework yang sangat mudah dipelajari, terutama jika sudah menguasai PHP. Anda dapat menguasai CodeIgniter dalam waktu singkat untuk membangun dan mengembangkan aplikasi.
- Dapat dimodifikasi : CodeIgniter sudah dilengkapi dengan library yang berisi banyak bantuan dan petunjuk. Jika Anda tidak menemukan yang Anda cari, Anda dapat dengan mudah menambahkan bantuan, petunjuk, atau library sendiri secara mandiri.
- Fleksibel : CodeIgniter dilengkapi dengan sejumlah fitur dan komponen canggih yang berdiri sendiri tanpa saling bergantung. Hal ini memungkinkan pengguna untuk meng-upgrade dan memperbaiki masalah tertentu dengan mudah.
- sagat cepat : Pengguna umumnya lebih menyukai perangkat lunak yang mampu memproses proses dengan cepat. CodeIgniter hadir sebagai framework super cepat, di mana proses loading dan eksekusi perintah dapat diproses dalam waktu kurang dari 50 milisekon.

### Kekurangan CodeIgniter
- CodeIgniter masih memiliki keleluasaan yang signifikan dalam penulisan kode, seperti kemampuan untuk secara bebas menambahkan file.
- Framework ini tidak sepenuhnya mencerminkan konsep Model-View-Controller (MVC) dengan benar, seperti contoh penggunaan perintah echo yang masih dapat dilakukan langsung pada file Controller.
- Walau terdapat berbagai library yang tersedia, CodeIgniter tidak dirancang untuk pengembangan situs web dengan skala besar atau kebutuhan perusahaan.  
</details>

<details>
<summary> INSTALASI </summary>
  
CodeIgniter memiliki 2 cara yang dapat dilakukan untuk melakukan proses instalasi
  
### 1. Instalasi Secara Manual
Untuk melakukan instalasi manual, download file zip dari CodeIgniter 4 melalui website resminya.
![Screenshot 2024-03-18 105007](https://github.com/Meilyaatffh/Meilyaatffh/assets/134565192/b626da98-f509-4d39-a6f5-399372ce99d0)
Kemudian, extract file zip tersebut dan ubah namanya sesuai dengan nama project yang  diinginkan. CodeIgniter ini sudah bisa langsung dijalankan di web browser Anda dengan mengakses localhost/ci4/public.


### 2. Instalasi Melalui Composer
Cara kedua untuk menginstall CodeIgniter 4 adalah menggunakan Composer. Kelebihannya, path folder project Anda bisa dibuat dimana saja, tidak perlu di folder htdocs. 
Melakukan cek composer untuk memastikan apakah composer sudah terinstall di komputer kita, dengan mengetikkan perintah composer. Jika tampilannya sudah seperti yang dibawah ini maka artinya composer sudah berhasil terinstall
![Screenshot 2024-03-18 101643](https://github.com/Meilyaatffh/Meilyaatffh/assets/134565192/83bd8c44-59eb-4e87-a108-eedc4518fcaa)

kemudian ketikkan perintah composer create-project codeigniter4/appstarter nama_folder untuk melakukan proses install. Disini saya membuat folder dengan nama BelajarCI4.
![Screenshot 2024-03-18 103248](https://github.com/Meilyaatffh/Meilyaatffh/assets/134565192/6b8a05b0-d32f-4dc0-9d92-999085fc0c67)

ketikkan perintah cd BelajarCI4 untuk masuk ke dalam folder yang telah kita buat. Perintah php spark serve untuk menjalankan.
![image](https://github.com/Meilyaatffh/Meilyaatffh/assets/134565192/c4f2140f-3905-4298-812a-e9790a5aa7db)

Selanjutnya, buka browser dan ketikkan akses localhost:8080. Halaman awal CodeIgniter akan tampil seperti gambar di bawah ini :
![image](https://github.com/Meilyaatffh/Meilyaatffh/assets/134565192/fa733798-789f-4982-a89f-101626b240e5)




