# Materi
1. [Pengenalan](#pengenalan)
2. [Instalasi](#instalasi)
4. [Konsep](#konsep)
3. [CLI](#command-line-interface)
5. [Git Workflow](#git-workflow)


# Pengenalan
Sub-materi
1. [Pengertian Linux](#1-pengertian-linux)
2. [Distro Linux](#2-distro-linux)
3. [Perbedaan Linux, MAC, dan Windows](#3-perbedaan-linux-mac-dan-windows)

### 1. Pengertian Linux
**Linux** adalah nama yang diberikan kepada sistem operasi bertipe Unix. Linux merupakan salah satu contoh hasil pengembangan perangkat lunak bebas dan sumber terbuka utama. Seperti perangkat lunak bebas dan sumber terbuka lainnya pada umumnya, kode sumber Linux dapat dimodifikasi, digunakan dan didistribusikan kembali secara bebas oleh siapa saja.

### 2. Distro Linux
**Distro Linux** (singkatan dari **distribusi Linux**) adalah sebutan untuk sistem operasi komputer dan aplikasinya, merupakan keluarga yang menggunakan kernel Linux.

**1. Red Hat**

![Red Hat](img/RedHat-150x150.png  "Red Hat")  

Red Hat ini merupakan salah satu Distro Linux yang dikembangkan oleh salah satu perusahaan bernama Red Hat Inc dan seringkali juga disebut Red Hat Linux namun pada tahun 2003 diganti menjadi Red Hat Enterprise Linux khusus untuk lingkungan perusahaan. Sistem operasi yang satu ini juga yang pertama kali mempopulerkan penggunaan sistem _RPM Package Manager_.

**2. CentOS**

![CentOS](img/centos-150x150.jpg  "CentOS")  
CentOS merupakan singkatan dari _Community Enterprise Operating System_dan merupakan salah satu contoh Distro Linux yang dikembangkan oleh The CentOS Project. Sistem operasi ini dibuat menggunakan kode sumber yang berasal dari Red Hat. Oleh karena itu, dalam hal produk CentOs ini sangatlah mirip dengan Red Hat Enterprise Linux.

**3. Fedora**  

![Fedora](img/fedora-150x150.png  "Fedora")  
Fedora ini merupakan salah satu Distro Linux yang dkembangkan karena disponsori dan didukung oleh Red Hat namun dibuat oleh tim khusus bernama Fedora Project. Bahkan nama Fedora ini diambil dari salah satu karakter dalam logo Red Hat itu sendiri. Sama halnya dengan Red Hat, sistem operasi Fedora juga menggunakan sistem _RPM Package Manager_.

**4. openSUSE**  

![openSUSE](img/openSUSE-150x150.png  "openSUSE")  

openSUSE ini juga termasuk salah satu sistem operasi yang didirikan diatas kernel Linux atau biasa disebut Distro Linux. openSUSE Project selaku pihak pengembang menciptakan sistem operasi ini dengan tujuan agar penggunaan Linux dapat lebih maju dengan kinerjanya yang stabil dan ramah pengguna. openSUSE ini lebih sering digunakan sebagai sistem operasi desktop/ server.

**5. Mandrake (Mandriva)**  

![Mandrake](img/mandriva-150x150.jpg  "Mandrake")  

Sistem operasi Mandrake atau yang juga bisa disebut Mandriva Linux merupakan salah satu jenis Distro Linux yang kali ini dikembangkan oleh suatu perusahaan bernama Mandriva. Sama halnya dengan Fedora, sistem operasi Mandrake ini juga menggunakan sistem _RPM Package Manager_.

**6. Debian**  

![Debian](img/2000px-Ardebian_logo.svg-150x150.png  "Debian")  

Proses penamaan dari salah satu Distro Linux ini bisa dibilang cukup unik. Sang pencetus pertama kali yakni Ian Murdock memberi nama Debian karena merupakan kombinasi dari namanya dan mantan kekasihnya. Salah satu alasan mengapa Debian ini termasuk Distro Linux yang paling banyak digunakan adalah karena security-nya yang bagus .

**7. Ubuntu**  

![Ubuntu](img/ubuntu-150x150.png  "Ubuntu")  
Ubuntu merupakan suatu sistem operasi yang berbasiskan pada Debian dan dikembangkan oleh suatu perusahaan dari Afrika Selatan yang bernama _Canonical ltd_. Asal penamaan dari Ubuntu ini juga berasal dari bahasa Afrika Selatan yang berarti kemanusiaan. Dengan sifatnya sebagai OS open source, Ubuntu sengaja diprioritaskan untuk kepentingan umum atau server.

**8. Mint**  

![Mint](img/mint-150x150.png  "Mint")  

Jika sebelumnya anda mengetahui bahwa Distro Linux yang bernama Ubuntu dibuat dengan berbasiskan pada Debian, maka kali ini ada Distro Linux yang berbasiskan pada Debian dan Ubuntu. Namanya adalah Mint atau yang biasa disebut Linux Mint.

**9. Zorin**  

![Zorin](img/zorin-150x150.jpg  "Zorin")  

Zorin ini merupakan salah satu Distro Linux yang memiliki tampilan grafis sangat mirip dengan Windows, bahkan termasuk pada aplikasi – aplikasinya. Sejak awal tujuan pembuatan sistem operasi ini memang agar para pengguna yang terbiasa dengan Windows dapat menikmati fitur dari Linux tanpa harus mengalami kesulitan.

### 3. Perbedaan Linux, MAC, dan Windows
 
| ASPEK | LINUX | MAC | WINDOWS |  
|---|---|---|---|
| Kemanan | Memiliki tingkat keamanan paling kuat | Sulit terkena virus | Rentan terkena virus |  
| Ekonomis / Harga | Gratis | Berbayar | Berbayar |  
| Tampilan | Tampilan pada Linux sangat mudah dimengerti oleh penggunanya, tetapi tidak unggul dalam grafis | Segi tampilan Macintosh paling bagus dari Windows dan Linux, desain dan stylenya tampak sangat premium dan indah dimata konsumen | Windows unggul dalam segi grafis, memiliki tampilan yang bagus dan mudah dimengerti oleh peggunanya |  
| Performance | Performa linux sangat tinggi karena detail yang disediakan dari UI sedikit sehingga digunakan untuk embedded system karena performanya bagus dan sedikit memakan resources | High performance, dengan prosesor Intel terbaru dan inovasi terbaik lainnya, Mac dapat melakukan semua hal yang hanya dapat dilakukan Mac – dengan kecepatan yang menakjubkan | Performa lumayan baik tetapi dengan rentannya terhadap virus membuat performanya tidak maksimal sehingga cenderung lambat karena terlalu banyak detail pada UI yang menyebabkan meningkatnya ukuran Windows secara tidak langsung yang menghambat proses komputer |  
| User | Banyak user yang belum terbiasa menggunakan linux dan lumayan sulit untuk dipelajari | User-Friendly, dengan tampilan GUI yang sangat menarik, menmbuat Mac OS menjadi  salah satu OS yang banyak diminati khususnya oleh para graphic desainer | Paling disukai karena lebih mudah dipakai dan hampir digunakan oleh mayoritas pengguna komputer di dunia |  
User Interface | Memiliki banyak user interface | Tidak memiliki banyak user interface, tetapi sudah lebih mudah dipakai dan tampilannya menarik | Tidak memiliki banyak user interface |  
| Kelengkapan Program | Sudah terdapat banyak program yang siap untuk dipakai | Sudah terdapat program yang siap dipakai, tapi tidak terlalu banyak | Pertama kali memakai harus mengisi program aplikasi yang lain |  
Perangkat Lunak yang Bisa Dipakai | Sangat minim software karena sedikit developer yang membuat software di Linux | Macintosh masih kalah dibanding Windows tetapi lebih unggul dari Linux, karena software dan hardware-nya harus memiliki licence dari Apple, sedangkan Windows didukung dari berbagai vendor software dan hardware | Memiliki banyak software yang bisa dipakai karena para developer lebih memilih mengembangkan softwarenya di Windows yang pembuatannya mudah dan banyak yang memakai |  
| Pilihan sitem operasi | Linux banyak jenis yang bisa kita pilih baik lokal maupun luar | Macintosh tidak terlalu banyak yang yang disediakan | Windows tidak banyak varian/jenis yang di tawarkan |  
| Segi hardware | Ada beberapa hardware yang tidak bekerja atau belum maksimal karena ada vendor yg tidak tidak menyediakan driver versi Linux | Mac tidak bisa dirakit sendiri karena Apple sudah tidak memberi license buat perusahaan lain untuk membuat hardware yang bisa menggunakan Mac OS | Di Windows, biasanya Anda tidak pernah mendengar masalah hardwre, karena hampir semua hardware yang ada sudah menyertakan drivernya |  
 
##### Referensi :
- http://ayukhusnulkhotimah.web.ugm.ac.id/2018/03/04/perbandingan-linux-mac-os-window/
- https://www.nesabamedia.com/distro-linux/
- https://id.wikipedia.org/wiki/Linux
- https://id.wikipedia.org/wiki/Distribusi_Linux

<div style="page-break-after: always;"></div>

# Instalasi
Sub-materi
1. [Persiapan](#1-persiapan)
2. [Teknik Instalasi](#2-teknik-instalasi)
3. [Membuat Virtual Machine](#3-membuat-virtual-machine)
4. [Instalasi Ubuntu](#4-instalasi-ubuntu-1604)

### 1. Persiapan
- File ISO Ubuntu 16.04 LTS ([Download](http://releases.ubuntu.com/16.04/ubuntu-16.04.5-desktop-amd64.iso))
- Installer VirtualBox ([Download](https://download.virtualbox.org/virtualbox/5.2.22/VirtualBox-5.2.22-126460-Win.exe))

### 2. Teknik Instalasi
Jika hendak menggunakan lebih dari satu sistem operasi atau sering disebut OS(operating system) pada suatu komputer biasanya ada dua pilihan teknik instalasi, yaitu **dual-boot** atau **virtualisasi**.
**Dual-boot** adalah teknik menginstall dua atau lebih OS pada satu komputer, dimana masing-masing OS berjalan secara mandiri. Pengguna hanya dapat menggunakan salah satu OS dalam satu watu, dengan cara memilih OS yang akan dipakai ketika menyalakan komputer.

![Tampilan GRUB Dual Boot Linux(Ubuntu) dan Windows](img/tampilan_grub_dual_boot.png "Tampilan GRUB Dual Boot Linux(Ubuntu) dan Windows")

Sedangkan **Virtualisasi** adalah teknik menginstal dan menjalankan suatu OS di atas OS lain sebagai host, yaitu dengan menggunakan program berjenis mesin virtual (virtual machine), salah satu contohnya adalah VirtualBox. Dengan mesin virtual ini, pengguna dapat menjalankan suatu OS, sebagai contoh Linux, pada saat OS lain berjalan, sebagai contoh Windows, sehingga pengguna dapat menjalankan beberapa OS sekaligus dalam satu waktu.

Berikut ini perbandingan termasuk kelebihan dan kekurangan dari kedua teknik instalasi tersebut:

|Dual-Boot|Virtual Machine|
|---|---|
|Secara umum lebih cepat, karena masing - masing OS berjalan secara mandiri|Secara umum lebih lambat, karena harus berbagi sumber daya prosesor dan memori dengan OS host|
|Kedua OS dapat bertukar data dengan mudah, asalkan saling mendukung format sistem file pada harddisk|Bertukar file antar OS tidak dapat dilakukan secara langsung, perlu beberapa konfigurasi|
|Hanya dapat menjalankan salah satu OS saja pada satu waktu|Dapat menjalankan beberapa OS sekaligus dalam satu waktu(asal spesifikasi komputer mencukupi)|
|Prosedur instalasi dan konfigurasi untuk dual-booting cukup rumit dan beresiko (kehilangan data), terutama pada saat partisi harddisk|Prosedur instalasi OS menjadi mudah tanpa harus bingung dengan hal-hal teknis seperti partisi harddisk|
|Ideal untuk penggunaan sehari-hari, yang membutuhkan performa penuh komputer|Ideal untuk sekedar mengetes suatu OS, atau sekedar menjalankan suatu program yang tidak dapat berjalan pada OS host|
|Jika terjadi kerusakan pada salah satu OS, ada kemungkinan berpengaruh dengan OS satunya|Kerusakan pada OS yang di virtualisasikan tidak akan berpengaruh pada OS host|

### 3. Membuat Virtual Machine(VirtualBox v7.0.8) dengan Ubuntu 22.0.4
1. Install versi terbaru Oracle VM VirtualBox. Jika sudah ada, lanjut ke langkah 2.
2. Buka aplikasi Oracle VM VirtualBox di Windows Anda.  
![Tampilan awal Oracle VM VirtualBox](img/virtualbox-1.png "Tampilan awal Oracle VM VirtualBox")

3. Klik **New** untuk membuat Virtual Machine baru. Isi **name** dengan nama 'Ubuntu 22.0.4', pilih dimana **folder** VM diletakkan, dan lokasikan dimana file .iso dari OS Ubuntu berada. Kemudian klik **Next** untuk proses selanjutnya.  
![Membuat Virtual Machine baru Oracle VM VirtualBox](img/virtualbox-2.png "Membuat Virtual Machine baru Oracle VM VirtualBox")

4. Selanjutnya Anda disuruh untuk menentukan username dan password yang nantinya digunakan untuk log-in ke VM. Di section additional options di sebelah kanan, berikan nama hostname dan domain name yang sesuai (alfanumerik tanpa spasi). Jika sudah klik **Next**.  
![Set memori VM baru Oracle VM VirtualBox](img/virtualbox-3.png "Set memori VM baru Oracle VM VirtualBox")

5. Selanjutnya Anda disuruh untuk menentukan ukuran memori RAM dan jumlah core/thread processor yang akan digunakan, namun VirtualBox otomatis merekomendasikan alokasi jumlah. Jika sudah sesuai dengan keinginan, klik **Next**.  
![Set ukuran harddisk VM baru Oracle VM VirtualBox](img/virtualbox-4.png "Set ukuran harddisk VM baru Oracle VM VirtualBox")

6. Anda akan diminta untuk menentukan ukuran hard disk. Untuk Ubuntu sendiri rekomendasi kapasitas hard disk minimal adalah 8GB. Diluar itu, Anda bisa menentukan space yang Anda inginkan. Jika sudah, klik **Next** 
![Set tipe harddisk VM baru Oracle VM VirtualBox](img/virtualbox-5.png "Set tipe harddisk VM baru Oracle VM VirtualBox")

7. Virtual machine yang Anda buat sudah jadi!

### 4. Instalasi Ubuntu 16.04
Setelah berhasil membuat virtual machine, selanjutnya kita menginstall Ubuntu 16.04 pada virtual machine yang telah dibuat.
1. Pilih virtual machine yang ingin di install, lalu klik **Setting** -> **Storage** -> **Controller: IDE** -> **Empty** -> **Choose Virtual Optical Disk File** untuk memilih file ISO Ubuntu yang akan di install. Kemudian klik **Start** (tanda panah hijau).
![Set file ISO Ubuntu VM baru Oracle VM VirtualBox](img/vb_set_iso.png "Set file ISO Ubuntu VM baru Oracle VM VirtualBox")  
![Set file ISO Ubuntu VM baru Oracle VM VirtualBox(2)](img/vb_get_iso_file.png "Set file ISO Ubuntu VM baru Oracle VM VirtualBox(2)")  
![Set file ISO Ubuntu VM baru Oracle VM VirtualBox(3)](img/vb_vm_jadi.png "Set file ISO Ubuntu VM baru Oracle VM VirtualBox(3)")

2. File ISO Ubuntu sudah berjalan. Selanjutnya tinggal ikuti langkah instalasinya. Klik **Install Ubuntu**.  
![Instalasi Ubuntu(1)](img/vb_install_ubuntu1.png "Instalasi Ubuntu(1)")

3. Tidak perlu mencentang apapun untuk menghemat waktu instalasi, kemudian klik **Continue**.  
![Instalasi Ubuntu(2)](img/vb_install_ubuntu2.png "Instalasi Ubuntu(2)")

4. Pilih **Erase disk and install Ubuntu**, lalu klik **Install Now**.  
![Instalasi Ubuntu(3)](img/vb_install_ubuntu3.png "Instalasi Ubuntu(3)")

5. Memilih zona waktu. Ketik **Jakarta**, lalu klik **Continue**.  
![Instalasi Ubuntu(4)](img/vb_install_ubuntu4.png "Instalasi Ubuntu(4)")

6. Memilih bahasa yang digunakan untuk penyesuaian keyboard. Ikuti saja defaultnya, langsung klik **Continue**.  
![Instalasi Ubuntu(5)](img/vb_install_ubuntu5.png "Instalasi Ubuntu(5)")

7. Mengatur nama, nama komputer, username, dan password. Biasanya ketika mengetikkan nama kita pada form **Your name**, form **Your computer's name** dan form **Pick a username** otomatis tergenerate sesuai nama yang kita ketikkan.  
![Instalasi Ubuntu(6)](img/vb_install_ubuntu6.png "Instalasi Ubuntu(6)")

8. Tunggu hingga proses instalasi selesai.  
![Instalasi Ubuntu(7)](img/vb_install_ubuntu7.png "Instalasi Ubuntu(7)")

9. Instalasi sudah selesai! Klik **Restart Now** untuk me-*restart* Ubuntu untuk menyudahi tahapan instalasi.  
![Instalasi Ubuntu(8)](img/vb_install_ubuntu8.png "Instalasi Ubuntu(8)")


##### Referensi
- https://abrari.wordpress.com/2009/12/12/dual-booting-vs-virtualisasi/
- https://id.wikihow.com/Memasang-Ubuntu-di-VirtualBox
- https://www.ubuntu.com/
- https://www.virtualbox.org/

<div style="page-break-after: always;"></div>

# Konsep
Sub-Materi
1. [Struktur Folder](#1-Struktur-Folder)
2. [Repository](#2-Repository)

### 1. Struktur Folder
Jika kita ingin belajar Linux lebih mendalam, hal yang paling dasar untuk dipahami adalah struktur direktorinya. Struktur direktori pada Linux sangat berbeda dengan Windows. 
#### 1.1 Struktur direktori Windows
Sistem operasi Windows memiliki struktur direktori yang sederhana dan mudah dipahami, seperti dibawah ini:  

![Struktur direktori Windows](img/windows.jpg "Struktur direktori Windows")

- **Program Files** : Berfungsi untuk menyimpan program-program dan aplikasi  yang terinstal di dalam Windows
- **Windows** : menyimpan segala proses juga konten-konten utama windows. Akan terjadi kerudakan system jika ada kesalahan dalam mengatur folder ini. Isi dari folder ini berupa system32, Assembly, dan Web
- **Temp** : digunakan untuk menyimpan file-file sementara
- **Document and Settings** : berfungsi untuk menyimpan dokumen dan pengaturan-pengaturan user mulai dari desktop, start menu, dsb

#### 1.2 Struktur direktori Linux

#### 1.2.1 Struktur direktori
Pada struktur direktori Linux tidak akan ditemukan drive C, drive D, dan drive-drive lainnya karena Linux menganut satu direktori utama yaitu "**/**" (baca: root). Berikut ini adalah struktur direktori beserta apa yang berada di dalam sistem operasi Linux:

![Struktur direktori Linux](img/linux.jpg "Struktur direktori Linux")

Penjelasan beberapa direktori yang perlu kalian ketahui: 
- **/** ("root") : Merupakan root atau akar dari seluruh direktori global. Partisi dimana diletakkan/ (root system) akan menjadi direktori sistem atau partisi pokok. Hanya bisa diakses oleh user root atau super user.
- **/bin** (user binaries) : Memuat program arahan yang merupakan sebagian dari sistem operasi Linux. Direktori ini meng-handle perintah standar Linux, seperti cd, ls, cp, dll.
- **/boot** (boot loader files) : Direktori yang berisi file-file yang berhubungan dengan boot loader, contohnya Grub boot manager, File Kernel initrd, vmlinux, dll.
- **/dev** (device files) : Memuat semua file penting.
- **/etc** (configuration files) : Berisi file-file konfigurasi sistem. Selain itu, juga berisi file yang dijalankan ketika start up.
- **/home** (home directories) : GNU/Linux merupakan sistem operasi yang mendukung multi-user. Kebijakannya sangat ketat. Oleh karena itu, direktori **/home** menyimpan semua direktori home user kecuali user root atau super user.
- **/lib** (system libraries) : Memuat file-file library Linux yang mendukung binary files dalam direktori **/bin** dan **/sbin**
- **/media** (removable media devices) : Direktori untuk mounting removable media seperi drive CD-ROM, hardisk eksternal, flashdisk, zip drive, dll.
- **/mnt** (mount directory) : Direktori untuk mounting file sistem sementara.
- **/opt** (optional add-on applications) : Direktori ini menyimpan file-file tambahan dari vendor-vendor tertentu. Sifatnya hanya optional. Diharapkan dengan adanya direktori ini, manajemen paket aplikasi tambahan dapat dilakukan dengan mudah.
- **/sbin** (system binaries) : Memuat file administration yang dapat diakses seperti mount, shutdown, umount.
- **/srv** (service data) : Memuat data untuk layanan (HTTP, FTP, etc.) yang ditawarkan oleh sistem.
- **/tmp** (temporary files) : Direktori yang digunakan untuk menyimpan data sementara. Isi dari direktori ini dibersihkan setiap kali sistem boot.
- **/usr** (user programs) : direktori yang berisi file-file binary, libraries, dokumentasi, dan source code dari sistem. 
- **/var** (variable files) : Memuat berbagai sistem file seperti log, direktori mail, print dan lain – lain. Yang sering kali berubah kandungannya.

Salah satu perbedaan mendasar dan mencolok antara Linux dan Windows adalah apabila kita memasuki inti dari sistem Windows (yakni System 32), kita bisa dengan bebas meng-copy atau paste file yang berada di dalamnya. Tentunya hal ini membuat Windows sangat mudah diinfeksi virus, bahkan jika kita memasang antivirus sekalipun.
Sedangkan pada Linux, jika kita ingin meng-copy, paste, atau mengedit file di dalam direktori sistem Linux (**/**, dibaca root) kita harus menggunakan super user (root) dan melakukannya file via terminal. Hal ini menyebabkan Linux menjadi sangat kebal terhadap virus.
#### 1.2.2 Absolute Path & Relative path
Setiap file dan direktori dalam filesystem Linux dapat diakses bila kita mengetahui jalur atau path direktorinya.

**Absolute Path**

Path ditulis dengan lengkap dari nama parent direktori sampai nama filenya. Misal, _/home/Penunggu/aloha.txt_ untuk meng-akses file _aloha.txt_ atau _/home/Penunggu/Downloads/_ untuk mengakses direktori.

**Relative Path**

Path tidak ditulis lengkap, tetapi berdasarkan posisi direktori yang sedang anda akses atau sering disebut direktori kerja (working directory). Misal, saat ini anda berada di direktori _/home/Penunggu_ atau "**~**" Maka cukup dituliskan aloha.txt untuk meng-akses file _aloha.txt_ atau _Downloads/_ untuk mengakses direktori. Nama working directory dapat diganti dengan sebuah tanda "**.**" ( single dot atau titik tunggal), sedangkan parent directory dapat digantikan dengan tanda "**..**" (double dot atau titik ganda).
### 2. Repository
#### 2.1. Apa itu Repository?  
   **Repository** adalah tempat menyimpan berbagai macam program atau aplikasi yang telah di buat sedemikian rupa sehigga bisa di akses melalui internet. Selain di internet, **Repository** juga tersedia di media seperti DVD sebagai alternatif **Repository** saat tak ada koneksi internet. Ketika kita melakukan download Repository melalui internet default servernya adalah server luar, seperti archive.ubuntu.com, security.ubuntu.com, dll. Untuk Fungsinya, disini Repository berperan sebagai penyedia aplikasi atau kumpulan paket software dari distro-distro linux, yang dapat di akses melalui internet.  
  
#### 2.2. Dimana file Repository itu berarda?  
File Repository ini langsung otomatis berada di laptop atau PC kita saat kita sudah menginstall linux dengan nama file biasanya "sources.list", terletak di folder apt di dalam folder etc. Jika ingin melihat Repository milik kita hanya perlu mengetikan :  

```sh
$ sudo gedit /etc/apt/sources.list
```

Kita bisa melakukan edit seperti menambah, menghapus, mengganti Repostitory milik kita sesuai yang kita inginkan.  
  
#### 2.3. Apakah Repository itu Penting?  
Adanya Repository di linux itu sangatlah _**Penting**_, karena itu adalah tempatnya paket-paket software untuk linux itu sendiri, kita hanya perlu langsung menginstall tanpa harus cari lagi paket softwarenya karena sudah tersedia di Repository tersebut. walau pun kita bisa juga mencari paket softwarenya secara manual dan menginstallnya juga, tetapi cara tersebut cukup ribet dan akan banyak memakan waktu. 
  
#### 2.4. Apakah semua Paket software ada di Repository? 
Tidak semua paket software langsung ada di repository, itu sebabnya kita harus tau nama file repository dan letaknya dimana, karena jika kita akan menginstall suatu software dan aplikasi, kemudian di Repository ternyata paketnya belum ada, kita bisa mencari repositorynya dan menambahkannya di di Repository kita dengan mengedit file sources.list tadi, yang berada di directory sudo gedit /etc/apt/sources.list.

##### Referensi
- http://2010183ifunsika.blogspot.com/2012/10/analisis-struktur-sistem-linux-dan.html
- http://www.belkomindo.com/2015/12/apasih-repository-itu.html
- http://kuntoaji.blogspot.com/2008/08/absolute-path-relative-path.html

<div style="page-break-after: always;"></div>

# Command Line Interface 
Sub-Materi
1. [Basic Command](#1-basic-command)
2. [Administrative Command](#2-administrative-command)
3. [File Editing](#3-file-editing)
4. [Export Variable](#4-export-variable)
5. [Cek IP dan Koneksi](#5-cek-ip-dan-koneksi)
6. [Menginstall Software](#6-menginstall-software)

### 1. Basic Command
##### 1. pwd
*print working directory*. Untuk mengetahui di directory mana kita berada sekarang.  
![pwd](img/pwd.png)

##### 2. ls
*list*. Untuk menampilkan file-file apa saja yang ada di suatu directory.  
![ls](img/ls.png)  
Parameter yang sering dipakai pada perintah ls adalah `-a` dan `-l`.
- Saat menggunakan parameter `-a` maka semua file akan ditampikan, termasuk yang *hidden* (diawali dengan `.`).  
![ls -a](img/ls_a.png)
- Sedangkan parameter `-l` menampilkan file yang tidak *hidden* dalam format *long-list*.  
![ls -l](img/ls_l.png)

##### 3. man
*manuals*. Digunakan untuk melihat fungsi dan parameter dari suatu comman
Contoh `man ls` akan menampilkan manual penggunaan command `ls`.
Untuk keluar dari tampilan manual tersebut kita tinggal menekan tombol `q`. 
![man](img/manls.png)

##### 4. cd
*change directory*. Digunakan untuk pindah ke directory lain. Syntax-nya adalah ```cd [namadirectory]```.
Misalnya kita sedang berada di directory `/home/Penunggu` dan ingin berpindah ke directory `Desktop/`. Maka command yang kita gunakan adalah `cd Desktop/`  
![cd](img/cd.png)  
Contoh lain:
+ `cd` atau `cd ~` untuk pindah ke directory home user
+ `cd /` untuk pindah ke directory root
+ `cd ..` untuk pindah ke parent directory dari directory sekarang
+ `cd -` untuk pindah ke working directory sebelumnya 
 
##### 5. mkdir
*make directory*. Digunakan untuk membuat sebuah directory (folder).
Syntax-nya adalah ```mkdir [namadirectory]```  
![mkdir](img/mkdir.png)

##### 6. cp
*copy*. Digunakan untuk menyalin (meng-copy) file.
Syntax-nya adalah ```cp [namafile] [namacopyannya]```  
![cp](img/cp.png)

##### 7. mv
*Move* Digunakan untuk memindahkan suatu file ke directory lain.
+ Untuk memindahkan file, syntax-nya adalah ```mv [namafile] [pathbarunya]```  
![mv](img/mv.png)
+ Selain itu `mv` dapat juga digunakan untuk me-rename file, syntax-nya adalah ```mv [namafile] [namabaru]```  
![mv](img/mv2.png)

##### 8. cat
*concatenate*. Digunakan untuk menampilkan isi dari suatu file.  
![cat](img/cat.png)

##### 9. rm
*remove*. Digunakan untuk menghapus suatu file. Syntax-nya adalah ```rm [namafile]```  
![rm](img/rm.png)  
Selain itu rm juga dapat digunakan untuk menghapus directory, yaitu dengan menambahkan parameter `-r`  
![rm -r](img/rm_r.png)

##### 10. rmdir
*remove directory*. Digunakan untuk menghapus directory yang kosong. Syntax-nya adalah ```rmdir [namafolder]```  
![rmdir](img/rmdir.png)

##### 11. echo
Digunakan untuk menampilkan string yang kita inputkan. Syntax-nya adalah ```echo [string yang diinginkan]```  
![echo](img/echo.png)

##### 12. grep
Digunakan untuk menampilkan setiap baris pada suatu file yang mengandung kata yang dicari.
Syntax-nya adalah `grep "[katayangdicari]" [namafile]`  
![grep](img/grep.png)

##### 13. zip
Command ini digunakan untuk melakukan compress data menjadi bentuk zip. Syntax-nya adalah ```zip [namafilezip] [file1] [file2]```.
Misalnya kita ingin mengompress file **makanan** dan **cemilan** menjadi  **energi.zip** .
Maka command yang kita jalankan adalah `zip energi makanan cemilan`   
![zip](img/zip.png)

##### 14. unzip
Kebalikan dari command zip, unzip digunakan untuk mengekstrak isi dari file .zip
Syntax-nya adalah ```unzip [namafilezip]```.
Jadi untuk mengekstrak file foobar.zip kita perlu menjalankan comman `unzip energi.zip`.
![unzip](img/unzip.png)

##### 15. exit
Digunakan untuk menutup terminal atau mengakhiri suatu script (misalnya saat melakukan ssh ke komputer lain)

##### 16. clear
Digunakan untuk 'membersihkan' isi layar terminal.
Sebelum clear:  
![clear1](img/sebelumclear.png)  
Sesudah clear:  
![clear2](img/sesudahclear.png)

##### 17. tree
Digunakan untuk menampilkan list directory.
Untuk menggunakan command ini, user harus meng-*install*-nya terlebih dahulu dengan command
`sudo apt-get install tree`  
![tree](img/tree.png)

### 2. Administrative Command
##### 1. su
Digunakan untuk mengganti user ID atau menjadi superuser.
Syntax-nya adalah `sudo su`

##### 2. sudo
*superuser do*. Digunakan untuk menjalankan command sebagai superuser, superuser biasanya digunakan untuk meng-edit file konfigurasi, mengatur paket, menginstall program.
Syntax-nya adalah `sudo [command]`

###### 3. chown
*change owner*.
+ Digunakan untuk mengubah kepemilikan dari suatu file. Syntax-nya adalah 
```chown [namauser] [namafile]```  
![chown](img/chown.png)  
+ Selain user pemilik, command `chown` juga bisa digunakan untuk mengganti *group* pemilik. Syntax-nya adalah
```chown [namauser]:[namagroup] [namafile]```
![chown-group](img/chown2.png)  
**Note:** mohon diingat bahwa nama user dan group yang dipilih harus sudah ada di komputer tersebut.

##### 4. adduser
*adduser*.
+ Digunakan untuk membuat user baru. Penggunaan perintah ini sangat sederhana, hanya dengan sudo adduser $loginname. Perintah tersebut akan membuat home directory dan user masuk ke default group, lalu sistem akan meminta informasi mengenai user secara rinci.
+ User baru dapat ditambahkan ke dalam group *sudoers* menggunakan perintah `sudo adduser [nama_user] sudo` 

##### 5. passwd
Digunakan untuk meng-*update* password user.  
![passwd](img/passwd.png)  

##### 6. chmod
*change mode*. Digunakan untuk mengubah izin akses dari suatu dokumen.
Contoh syntax `chmod 777 [namafile]`
*777* adalah representasi dari permission yang diberikan. Angka pertama melambangkan permission untuk user, angka kedua untuk group, dan angka ke tiga untuk *Others*  
![chmod](img/chmod.png)  

Permission Table

|#|Permission|rwx|Binary|
|---|---|---|---|
|7|read, write and execute|rwx|111|
|6|read and write|rw-|110|
|5|read and execute|r-x|101|
|4|read only|r--|100|
|3|write and execute|-wx|011|
|2|write only|-w-|-1-|
|1|execute only|--x|001|
|0|none|---|000|

### 3. File Editing
##### 1. vim
vim merupakan singkatan dari "Vi IMprovised" dan merupakan salah satu teks editor pada OS Linux yang dapat digunakan untuk mengedit jenis teks apapun, termasuk suatu program komputer. Vim diupgrade dari teks editor vi, yang memiliki beberapa peningkatan dari vi, beberapa diantaranya adalah syntax highlighting, on-line help, multi-windows dan buffers, dll.
Untuk lebih jelas perbedaan antara vim dan vi : https://github.com/vim/vim/blob/master/runtime/doc/vi_diff.txt
##### Install vim teks editor
```sh
$ sudo apt-get update
```
```sh
$ sudo apt-get install -y vim
```
##### Membuat dan meng-insert teks 
Syntax yang biasa digunakan adalah `vim [nama-file]`. Setelah command tersebut dijalankan akan terlihat lambang `~` pada tiap baris yang kosong. 
```sh
$ vim nyoba.txt
```
![vim3](img/vim3.png)

Vim sekarang dalam *mode normal*. Untuk menginsertkan teks, maka ketik `i` untuk masuk ke *mode insert* dan diikuti dengan mengetikkan teks yang diinginkan.
Ketika kita menekan `i` untuk menginsertkan teks, karakter yang kita inputkan akan terketik sesuai dengan posisi kursor saat itu. Agar karakter yang kita inputkan terketik pada sebelah kanan posisi kursor, maka kembalikan vim pada mode normal, dan tekan `a`. Maka karakter yang kita inputkan akan terketik pada sebelah kanan posisi kursor saat itu.

Jika sudah selesai menginputkan teks, tekan `esc` dan vim akan kembali ke mode normal. Dalam mode normal, tekan `h` untuk bergerak ke kiri, `l` untuk ke kanan, `j` untuk bergerak ke atas dan `k` untuk ke bawah.  
![vim4](img/vim4.png)

##### Menghapus karakter
Untuk menghapus sebuah karakter, selain bisa dilakukan pada mode insert dapat pula dilakukan ketika vim dalam *mode normal*. Yaitu dengan mengarahkan tanda kursor pada karakter yang ingin dihapus, dan menekan `x`.
Contohnya misal ketika kursor diletakkan pada huruf pertama yaitu huruf *i* pada kalimat *ini baris 3 ya* dan `x` ditekan sebanyak 4 kali, maka kalimat pada baris tersebut yang tersisa adalah *baris 3 ya*.  
![vim5](img/vim5.png)

##### Menghapus baris
Jika yang ingin dihapus adalah satu baris penuh, maka yang perlu dilakukan pada *mode normal* yaitu memposisikan kursor pada baris yang ingin dihapus, dan ketikkan `dd`. Misalnya kita ingin menghapus baris pertama dimana terdapat kalimat *hehe :)* maka setelah memposisikan kursor pada baris tersebut, ketika kita mengetikkan `dd` maka baris yang tersisa adalah *nyoba nulis* sebagai baris pertama dan *baris 3 ya* sebagai baris ke-2.  
![vim6](img/vim6.png) 

##### Menggabungkan dua baris
Untuk menggabungkan dua baris menjadi satu baris atau dengan kata lain menghilangkan spasi diantara 2 baris, maka pada *mode normal* cukup dengan memposisikan kursor pada kalimat di baris pertama dan tekan `J`. Maka kalimat pada baris kedua akan menjadi satu baris dengan kalimat pertama.  
![vim7](img/vim7.png)

##### Undo dan Redo
Pada teks editor vim, untuk meng-undo perubahan yang baru saja kita lakukan dilakukan dengan mengetik `u`. Maka pengerjaan yang baru saja kita lakukan akan ter-undo.
Sedangkan untuk me-redo atau kebalikan dari undo yang baru saja kita lakukan yaitu dengan menekan `Ctrl+R`.

##### Menulis pada line baru
Pertama posisikan kursor pada sebuah baris. Untuk membuat line baru dibawah baris tersebut, tekan `o` dan otomatis sebuah baris baru akan terbentuk di bawah kalimat tersebut dengan vim sudah berada pada mode insert. Jika baris yang ingin ditambahkan berada diatas baris tempat kursor berada saat ini, maka dilakukan dengan menekan `O`. 

##### Keluar dari teks editor vim
1. Keluar ketika dalam mode insert tanpa menyimpan perubahan apa-apa dengan mengetikkan `:q!`
2. Keluar ketika dalam mode insert dengan menyimpan perubahan yang dilakukan `:wq`
3. Keluar dan menyimpan perubahan dilakukan pada mode normal dengan mengetikkan `ZZ`

Untuk mengeksplorasi lebih lanjut mengenai teks editor vim, terdapat tutorial vim yang bisa diakses melalui terminal
```sh
$ vimtutor
```

##### 2. gedit
Gedit atau *Gnome-Text-Editor* adalah teks editor untuk GNOME desktop dan dapat digunakan untuk mengedit teks jenis apapun.
Syntax yang biasa digunakan untuk menjalankan teks editor ini adalah 
```sh
$ gedit [nama-file]
```

Misal kita akan membuat file txt dengan nama *cobagedit* maka ketikkan pada terminal
```sh
$ gedit cobagedit.txt
```
Halaman gedit pun akan muncul dan kita bisa menginputkan teks yang kita inginkan.  
![gedit1](img/gdit1.png)

File gedit memungkinkan kita untuk mengedit banyak file sekaligus. Syntax yang digunakan 
```sh
$ gedit [file1 file2 ...]
```
misalnya mengedit 2 file yaitu *cobagedit.txt* dan *nyobajuga.txt*
```sh
$ gedit cobagedit.txt nyobajuga.txt
```  
![gedit2](img/gdit2.png)

##### 3. nano
Nano atau *Nano's ANOther editor* merupakan teks editor yang dikembangkan mirip dengan teks editor *Pico* yang menjadi editor default dari Pine. Nano termasuk teks editor yang *user-friendly* karena adanya *shortcut* pada bagian bawah editor sehingga memudahkan pengguna dalam menggunakan teks editor ini.
Syntax yang biasa digunakan 
```sh
$ nano [nama-file]
```  
![nano1](img/nanoo.png)

Command tersebut akan memunculkan default nano-screen  

![nano2](img/nano2.png)

Untuk melihat list dari shortcut-shortcut yang ada tekan `Ctrl+G`

![nano3](img/nano3.png)

Ketika `Ctrl+X` ditekan untuk keluar dari editor, pada bagian bawah di baris ketiga dari bawah akan muncul pertanyaan *Save modified buffer?* Tekan `Y` untuk menyimpan perubahan dari file, dan `N` untuk keluar dari teks editor nano tanpa menyimpan perubahan. 

Selain itu sebelum benar-benar keluar dari teks editor nano, kita juga dapat merubah nama file yang baru saja kita buat tadi. Cukup dengan mengganti nama file sebelumnya yang tertera pada bagian bawah teks editor dimana terdapat tulisan *File name to write: ...* lalu tekan Enter.   
![nano4](img/nano4.png)

##### 4. touch
Digunakan untuk membuat sebuah file. Syntax yang digunakan 
```sh
$ touch [nama-file]
```  
![touch1](img/touch1.png)

### 4. Export Variable
Command *export* adalah salah satu command yang merupakan bagian dari shell (BuiltIn bash shell). Command ini cukup mudah digunakan karena syntax nya 'langsung' dan hanya memiliki 3 opsi perintah:

- `-p` : Daftar semua nama yang diekspor dalam shell saat ini
- `-n` : Hapus nama dari daftar ekspor
- `-f` : Nama diekspor sebagai fungsi

Secara umum, perintah ekspor menandai *environment variabel* untuk diekspor sehingga proses *child* yang baru bercabang dapat mewarisi semua variabel yang ditandai.

Contoh penggunaan export:

##### Meng-export Proxy
Untuk melakukan export proxy, misalnya menggunakan proxy ITS, maka syntax pada terminal
```sh
$ export http_proxy="http://username%40mhs.if.its.ac.id:password@proxy.its.ac.id:8080"
```
##### Men-set vim sebagai text editor
pada terminal ketikkan command
```sh
$ export EDITOR=/usr/bin/vim
```

Untuk cek hasil export variabel dapat melalui 
```sh
$ export -p
```
atau

```sh
$ export | grep EDITOR
```
![export1](img/export1.png)

##### Me-remove variable dari export list
Digunakan option `-n`
```sh
$ export -n EDITOR
```
### 5. Cek IP dan Koneksi

##### 1. ifconfig
Untuk mengkonfigurasi network interface.  
![ifconfig1](img/ifconfig1.png)

##### 2. ping
Merupakan sebuah utility program/alat untuk menguji apakah host tertentu dapat dijangkau.
Syntax yang biasa digunakan
```sh
$ ping [host tujuan]
```
![ping1](img/ping1.png)

##### 3. ssh
ssh adalah suatu network protokol untuk berkomunikasi secara aman antar komputer. ssh menghubungkan dan masuk (log) ke host yang ditentukan. Command ini dapat meremote server SSH komputer lain untuk menjalankan perintah-perintah dari jarak jauh.

ssh akan menyediakan koneksi terenkripsi yang aman antara dua host melalui jaringan yang tidak aman. Sambungan ini juga dapat digunakan untuk akses terminal, transfer file, dan untuk tunneling aplikasi lain.

Syntax yang biasa digunakan
```sh
$ ssh [hostname]
```

### 6. Menginstall Software

##### 1. apt-get update
```sh
$ sudo apt-get update
```
command **apt-get** dengan opsi **_update_** akan menyinkronisasi ulang file indeks paket dari sumber mereka. indeks-indeks dari paket yang tersedia akan diambil dari lokasi-lokasi yang telah ditentukan di _etc/apt/sources.list_.
##### 2. apt-get install pkg
```sh
$ sudo apt-get install <packages>
```
Opsi **install** ini diikuti oleh beberapa nama paket yang akan diinstall. 
Semua paket yang dibuthkan oleh paket yang akan diinstall juga akan terunduh dan terinstall. Berkas /etc/apt/sources.list digunakan untuk menentukan lokasi repositori dari paket yang dimaksud.

# Git Workflow
Sub-materi
1. [Pengenalan git](#1-pengenalan-git)
2. [Instalasi Git dan Konfigurasi Awal](#2-instalasi-git-dan-konfigurasi-awal)
3. [Basic Command git](#3-basic-command-git)

### 1. Pengenalan GIT
#### 1.1 Mengenal Git

[![HbuXSyv.md.webp](https://iili.io/HbuXSyv.md.webp)](https://freeimage.host/i/HbuXSyv)

Git adalah salah satu sistem pengontrol versi (Version Control System) pada proyek perangkat lunak yang diciptakan oleh Linus Torvalds.
Pengontrol versi bertugas mencatat setiap perubahan pada file proyek yang dikerjakan oleh banyak orang maupun sendiri.
Git dikenal juga dengan distributed revision control (VCS terdistribusi), artinya penyimpanan database Git tidak hanya berada dalam satu tempat saja.

[![Hbuj5q7.md.png](https://iili.io/Hbuj5q7.md.png)](https://freeimage.host/i/Hbuj5q7)

Semua orang yang terlibat dalam pengkodean proyek akan menyimpan database Git, sehingga akan memudahkan dalam mengelola proyek baik online maupun offline.Dalam Git terdapat merge untuk menyebut aktifitas penggabungan kode. Sedangkan pada VCS (Version Control System) yang terpusat… database disimpan dalam satu tempat dan setiap perubahan disimpan ke sana.

VCS terpusat memiliki beberapa kekurangan:
* Semua tim harus terkoneksi ke jaringan untuk mengakses source-code
* Tersimpan di satu tempat, nanti kalau server bermasalah bagaimana?

Karena itu, Git hadir untuk menutupi kerkurangan yang dimiliki oleh VCS terpusat.

#### 1.2 Apa yang dilakukan oleh Git?
Git sebenarnya akan memantau semua perubahan yang terjadi pada file proyek. Lalu menyimpannya ke dalam database.

Sebelum menggunakan Git:

[![HbuNkVp.md.png](https://iili.io/HbuNkVp.md.png)](https://freeimage.host/i/HbuNkVp)

Setelah menggunakan Git:

[![HbuOq0P.md.png](https://iili.io/HbuOq0P.md.png)](https://freeimage.host/i/HbuOq0P)

Saat kita ingin menyimpan semua perubahan pada file, biasanya kita membuat file baru dengan “save as”. Lalu, file akan menumpuk dalam direktori proyek seperti pada ilustrasi di atas.

Tapi setelah menggunakan Git…

Hanya akan ada satu file dalam proyek dan perubahannya disimpan dalam database. Git hanya akan menyimpan delta perubahannya saja, dia tidak akan menyimpan seluruh isi file yang akan memakan banyak memori. Git memungkinkan kita kembali ke versi revisi yang kita inginkan.

#### 1.3 Kenapa Git Penting Bagi Programmer?
Jadi selain untuk mengontrol versi, git juga digunakan untuk kolaborasi. Saat ini Git menjadi salah satu tool terpopuler yang digunakan pada pengembangan software open souce maupun closed source. Google, Microsoft, Facebook dan berbagai perusahaan raksasa lainnya menggunakan Git.

Selain itu, berikut ini ada beberapa menfaat yang akan kamu rasakan setelah bisa menggunakan Git.

* Bisa menyimpan seluruh versi source code;
* Bisa paham cara kolaborasi dalam proyek;
* Bisa ikut berkontribusi ke poryek open-source;
* Lebih aman digunakan untuk kolaborasi, karena kita bisa tahu apa yang diubah dan siapa yang mengubahnya.
* Bisa memahami cara deploy aplikasi modern;
* Bisa membuat blog dengan SSG.
* dan sebagainya…

### 2. Instalasi Git dan Konfigurasi Awal
#### 2.1 Cara Install Git di Linux
Instalasi Git pada Distro keluarga Debian dapat menggunakan perintah apt.

```
sudo apt install git
```
atau
```
sudo apt-get install git
```
Pada Fedora:

```
yum install git
```
Setelah itu, coba perika versi yang terinstal dengan perintah:
```
git --version
```
[![HphewNV.md.png](https://iili.io/HphewNV.md.png)](https://freeimage.host/i/HphewNV)

#### 2.2 Cara Install Git di Windows
Instalasi Git di Windows memang tidak seperti di Linux yang ketik perintah langsung terinstal. Kita harus men-download dulu, kemudian melakukan ritual next>next>finish. Tapi dalam ritual tersebut, ada pilihan yang harus diperhatikan agar perintah ```git``` dapat dikenali di CMD.
##### 2.2.1 Download Git

Silahkan buka website resminya Git [git-scm.com](https://git-scm.com). Kemudian unduh Git sesuai dengan arsitektur komputer kita. Kalau menggunakan 64bit, unduh yang 64bit. Begitu juga kalau menggunakan 32bit.

##### 2.2.3 Langkah-langkah Install Git di Windows
Baiklah, mari kita mulai ritual instalnya. Silahkan klik 2x file instaler Git yang sudah diunduh.

[![Hph8Fcu.md.jpg](https://iili.io/Hph8Fcu.md.jpg)](https://freeimage.host/i/Hph8Fcu)

Maka akan muncul infomasi lisensi Git, klik Next > untuk melanjutkan.

[![Hph8kVS.jpg](https://iili.io/Hph8kVS.jpg)](https://freeimage.host/id)

Selanjutnya menentukan lokasi instalasi. Biarkan saja apa adanya, kemudian klik Next >.

[![Hph8mUg.jpg](https://iili.io/Hph8mUg.jpg)](https://freeimage.host/id)

Selanjutnya pemilihan komoponen, biarkan saja seperti ini kemudian klik Next >.

[![HphSFsI.jpg](https://iili.io/HphSFsI.jpg)](https://freeimage.host/id)

Selanjutnya pemlilihan direktori start menu, klik Next >.

[![HphSXqP.jpg](https://iili.io/HphSXqP.jpg)](https://freeimage.host/id)

Selanjutnya pengaturan PATH Environment. Pilih yang tengah agar perintah ```git``` dapat di kenali di Command Prompt (CMD). Setelah itu klik Next >.

[![HphU949.jpg](https://iili.io/HphU949.jpg)](https://freeimage.host/id)

Selanjutnya konversi line ending. Biarkan saja seperti ini, kemudian klik Next >.

[![HphUz3F.jpg](https://iili.io/HphUz3F.jpg)](https://freeimage.host/id)

Selanjutnya pemilihan emulator terminal. Pilih saja yang bawah, kemudian klik Next >.

[![HphU13X.jpg](https://iili.io/HphU13X.jpg)](https://freeimage.host/id)

Selanjutnya pemilihan opsi ekstra. Klik saja Next >.

[![HphUrwx.jpg](https://iili.io/HphUrwx.jpg)](https://freeimage.host/id)

Selanjutnya pemilihan opsi ekspreimental, langsung saja klik Install untuk memaulai instalasi.

[![HphUpwv.jpg](https://iili.io/HphUpwv.jpg)](https://freeimage.host/id)

Tunggu beberapa saat, instalasi sedang dilakukan.

[![Hphr0es.jpg](https://iili.io/Hphr0es.jpg)](https://freeimage.host/id)

Setelah selesai, kita bisa langsung klik Finish.

[![HphrrBV.jpg](https://iili.io/HphrrBV.jpg)](https://freeimage.host/id)

Selamat, Git sudah terinstal di Windows. Untuk mencobanya, silahkan buka CMD atau PowerShell, kemudian ketik perintah ```git --version.

[![Hph4iMl.md.png](https://iili.io/Hph4iMl.md.png)](https://freeimage.host/i/Hph4iMl)

#### 2.3 Konfigurasi Awal
Ada beberapa konfigurasi yang harus dupersiapakan sebelum mulai menggunakan Git, seperti name dan email.

Silahkan lakukan konfigurasi dengan perintah berikut ini.

`git config --global user.name "John Doe"`
`git config --global user.email johndoe@example.com`

Untuk mengecek apakah sudah terkonfigurasi email dan username bisa menggunakan 
`git config --list`

Dalam kasus seperti pada umumnya kita akan diminta credential github berupa username github dan token git, seperti ini
![gitlogin](img/gitlogin.png)	
Untuk bisa melakukan push tanpa memasukkan otomatis kita bisa store credentials di global sehingga kita tidak perlu memasukkan credential
 - Generate Token
![generatetoken](img/generatetoken.png)
 - `nano ~/.git-credentials`
![gitcred](img/gitcred.png)
Tulis https://Username:token@github.com pada file ini
 - `git config --global credential.helper store`
![gitnocreds](img/gitnocreds.png)
Dengan ini kalian tidak perlu lagi memasukkan credential github ketika akan melakukan push

### 3. Basic Command Git
#### 3.1 Git Init
Command ini digunakan untuk membuat repositori Git baru di dalam direktori proyek. Setelah dieksekusi, Git akan mulai melacak perubahan pada proyek di dalam repositori tersebut.

```git init ```

#### 3.2 Git Remote Add

```git remote add <nama-remote> <URL-remote>```

ika proyek Anda akan disimpan di remote repository (seperti GitHub, GitLab, atau Bitbucket), Anda perlu menambahkan remote repository tersebut ke dalam repositori lokal. ```<nama-remote>``` adalah nama yang Anda tentukan untuk remote, dan ```<URL-remote>``` adalah URL dari remote repository tersebut.

contoh lengkap :

```git remote add origin https://github.com/username/repository.git```

#### 3.3 Git Add

```git add <nama-file>```

Command ini digunakan untuk menambahkan perubahan pada file yang ingin Anda lacak ke dalam staging area. Anda dapat menyertakan nama file atau menggunakan tanda . untuk menambahkan semua perubahan dalam direktori.

contoh lengkap:
* Untuk menambahkan semua perubahan:

```git add .```

* Untuk menambahkan perubahan pada file tertentu:

```git add nama-file.txt```

* Untuk melihat status perubahan:

```git status```

* Git Commit

```git commit -m "pesan-commit"```

Setelah Anda menambahkan perubahan ke staging area, Anda perlu membuat commit untuk menyimpan perubahan tersebut ke dalam sejarah repositori. Pesan commit harus jelas dan menggambarkan perubahan yang dilakukan.

contoh lengkap:

```git commit -m "Pesan commit mengenai perubahan yang dilakukan"```

#### 3.4 Git Branch

```git branch```

Command ini menampilkan daftar cabang yang ada dalam repositori Anda. Cabang digunakan untuk mengembangkan fitur atau memperbaiki bug tanpa mempengaruhi cabang utama (biasanya disebut "master" atau "main").

#### 3.5 Git Checkout

```git checkout <nama-cabang>```

Untuk pindah ke cabang yang berbeda, Anda menggunakan command ini. Misalnya, git checkout nama-cabang akan memindahkan Anda ke cabang dengan nama yang diisikan.

contoh lengkap:

```git checkout nama-cabang```

#### 3.6 Git Pull

```git pull <nama-remote> <nama-cabang```

Command ini digunakan untuk mengambil perubahan dari remote repository ke repositori lokal. Ini berguna jika ada perubahan yang dilakukan oleh anggota tim atau pada remote repository.

contoh lengkap:

```git pull origin main```

#### 3.7 Git Push

```git push <nama-remote> <nama-cabang>```

Command ini digunakan untuk mengirim perubahan yang ada pada repositori lokal ke remote repository. Ini berguna jika Anda ingin berbagi perubahan Anda dengan anggota tim atau mengamankan perubahan pada server remote.

contoh lengkap:

```git push origin main```

##### Referensi
+ https://searchdatacenter.techtarget.com/tutorial/77-Linux-commands-and-utilities-youll-actually-use
+ https://linux.die.net/man/8/apt-get
+ https://www.tutorialspoint.com/unix_commands/export.htm
+ https://www.howtogeek.com/howto/42980/the-beginners-guide-to-nano-the-linux-command-line-text-editor/
+ https://linux.die.net/man/1/gedit
+ https://www.computerhope.com/unix/vim.htm
+ https://www.simplified.guide/ubuntu/install-vim
+ https://www.ssh.com/ssh/command/
+ https://linux.die.net/man/8/ifconfig
+ https://en.wikipedia.org/wiki/Chmod
+ https://www.tecmint.com/dpkg-command-examples/
+ https://linuxconfig.org/how-to-install-google-chrome-browser-on-ubuntu-16-04-xenial-xerus-linux
+ https://askubuntu.com/questions/219545/dpkg-error-dpkg-status-database-is-locked-by-another-process

<div style="page-break-after: always;"></div>
