
# **RESUMMARY ONE WEEK**

 # **1. Unix Commandline (Dasar)**
<img src="un.jpg">


## **DEFINISI**
* Merupakan berbagai ketikan perintah yang di gunakan untuk menjalankan tugas tertentu. 

## **CONTOH PERINTAH :**




**1. Untuk Menampilkan daftar file** 
> *ls*  


**2. Untuk menampilkan daftar file yang tersembunyi**
>*ls -la*



**3.  Untuk membersihkan tampilan**
   > *clear/ ctr + i*


**4. Masuk kedalam directory**
>  *cd nama_folder*

> **Contoh:** *cd skilvul*


**5. Kembali ke directory sebelumnya**
> *cd ..*

**6. Mengcopy file ke directory/folder lain**
> *cp nama_file.exstensi /directory/directory*

> **Contoh:**  *cp scenery.jpg /home/username/Pictures*


**7. Pidah file ke directory/folder lain**
>*mv nama_file.ekstensi /directory/directory*

>**Contoh:** *mv file.txt /home/username/Documents*


**8. Membuat file baru**
> *touch nama_file.ekstensi*

> **Contoh:** *touch Skilvul.txt*



**9. Membuat foder baru**
> *mkdir nama_folder*

> **Contoh:** *mkdir amman_bootcamp*



**10. Menghapus  folder/file**
> *rm -r nama_folder / rm -r nama_file.ekstensi*



>**Contoh:**  *rm -r 'little nightmare' / rm -r 'little nightmare.exe'



**11. Menampilkan posisi berada**
> *pwd*


---

# **GIT & GITHUB (DASAR)**

<img src="https://miro.medium.com/max/882/1*D5zGIGFZoEO4uCTriOj4xg.jpeg" />


## **DEFINISI**
* Git adalah tools bagi progammer, git juga sebagai version control, yang di mana tugasnya mencatat  setiap perubahan pada File dan juga tempat menyimpan file.

## **PERINTAH YANG DIGUNAKAN UNTUK MENGUPLOAD FILE  :**

**1. Configurasi Git:**

 > *git config --global user.name "username github"*

> *git config --global user.email email yang di pakai*

**2. Melihat hasil konfigurasi**

>*git config --list*

**3. Menginisialisasi repository**

>*git init*

**4. check status file  mengalami perubahan atau tdk dalam proyek
tsb:**

>*git status*

**5. Memasukan file dari working tree ke stage area**

>*git add nama_file.ekstensi*

**6. Menyimpan perubahan kedalam version control**

>*git commit -m "pesan_comit"*

**7.Melihat apakah sudah  di commit apa belum**

 >*git log*

 **8. Setelah di commit file perlu di remote/di hubungkan dengan repsitory yg di miliki**

 >*git remote add origin alamat repositorynya*

 **9. Mengupload ke github**

 >*git push -u origin master*
 ---

 # **HTML**

<img src="https://www.oxfordwebstudio.com/user/pages/06.da-li-znate/sta-je-html/sta-je-html.jpg">

 ## **DEFINISI**

* HTML adalah singkatan dari Hypertext Markup Language.
 HTML digunakan untuk menampilkan konten pada browser. 


*Html memiliki 2 jenis tag: single tag dan double tag*

* <img src="ss1.png">

  

## **SOFTWARE YANG DI GUNAKAN**
* Notepad++
* Atom.
* BracketsText.
* Sublime Text Editor.
* Visual Studio Editor.
* Emacs.
* Netbeans.
* Aptana Studio.

## **STRUCTUR HTML**

<img src="https://kinsta.com/wp-content/uploads/2021/11/Untitled-54.png">

HTML tersusun sebagai kesatuan dari sebuah tingkatan (family tree relationship).

## **ANATOMY HTML**
<img src="https://schoolsofweb.com/wp-content/uploads/anatomy-of-an-html-element.jpg">

## **ELEMENT HTML**

HTML element didefinisikan dengan opening tag, content, dan closing tag.

## **ATRIBUT HTML**

<img src="https://monadical.com/static/html-tag-attributes.png">

Attribute adalah properties dari sebuah HTML Element.

## **contoh atribut html:**
* Atribut *href*. Atribut href dipakai pada link 
* Atribut src. Atribut src dipakai pada image 
* Atribut width dan height. untuk mengatur ukuran

## **TAG POPULER HTML**

**1. IMG**
* tag ini di gunakan untuk menaruh gambar, img merupakan single tag, tagi ini memiliki atribut juga yaitu: *alt*

* <img src="https://webapi.virtuousreviews.com/Resources/Editor/28012022-7EJ16CZWCBID5LEZNY1D.png">

**2. VIDEO**
* tag ini merupakan double tag yang di mana  membutuhkan tag penutup, tag ini di gunakan untuk menampilkan video,tag ini juga memiliki atribut *control, autoplay*

* <img src="91.jpg">

**3. TABLE**
 <img src="https://flaviocopes.com/html-tables/no-styling.png">
tag ini juga sering di gunakan dalam pembuatan website

## **SEMANTIC HTML**

Semantic artinya kita menggunakan element html yang sesuai dengan kebutuhan konten.
* <img src="https://www.w3schools.com/html/img_sem_elements.gif">

Ini sangat membantu untuk  supaya lebih mudah di buat dan di baca 

---
# **CSS**
<img src="https://www.oxfordwebstudio.com/user/pages/06.da-li-znate/sta-je-css/sta-je-css.png">


 ## **DEFINISI**

CSS(Cascading Style Sheet) css di gunakan untuk mendesain halaman website
bisa mengubah warna,menggunakan comstum font,mengatur posisi,dll
 * HTML itu= layer struktur
 * CSS itu= layer Presentation

## **STRUCTUR CSS**

<img src="https://www.techfor.id/wp-content/uploads/2019/12/x1.png">

## **CARA MENGGUNAKAN CSS**
1. inline styles=menambahkan atribut css langsung dalam tag nya
  2. internal styles=menambahkan atribut css di luar tag
  3. external style= menambahkan atribut css diluar html, cara memanggilnya lewat link
  * <img src="css.jpg">
    
## **CARA MEMANGGIL**

**1. CSS-Tag Name**

kita memanggil tag html untuk di modifikasi
tetapi mempengaruhi seluruh tag yg di panggil pd html
cth: h1 berarti seluruh tag h1 berubah 

**2. CSS-class Name**
Kita bisa menggunakan attribute class pada elemen HTML 
lalu memanggil nama class tersebut pada CSS

## **Multiple class**

Kita bisa menggunakan lebih dari 1 class
karna class lebih flexsible dari pada id, 
intinya dng multiple class kita bisa memanggil lebih dari 1 class
pada 1 element html
## **ID**
Id untuk 1 value dan n
cara panggilnya menggunakan #
tapi id lebih di utamakan daripada class 

## **Nested element**
adalah ketika ada suatu parent yg
memiliki class maka anaknya akan mengikutinnya
cth kalau parent di warnai merah maka anaknya akan berwarna merah

## **!Important css**
menyatakan bahwa properti ini wajib di gunakan
lebih di utamakan dari pada id dan class

## **Multiple selector**
membuat kita menggukan code lebih efisien kita
dapat menggunakan l class untuk beberapa element html
## **box system**
* border garis luar 
* margin daerah terluar 
* padding jarak di dalam konten

* <img src="https://flaviocopes.com/css-box-model/Screen%20Shot%202019-04-06%20at%2015.18.39.png">

## **FLEX BOX**
mengatur tata letak dari suatu website
secara otomatis menyesuaikan layout 
sesuai ukuran layar secara otomatis
Order gunanya untuk mengurutkan

* <img src="data:image/png;base64,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">
 ---

 # **ALGORITMA**

<img src="https://3.bp.blogspot.com/-VTIT85w3qQU/WJ2cJ8G8qTI/AAAAAAAAHPs/6PRBEAAVc7g5BdPwBxsJGri3Lmpemv1eACLcB/w850/cover.jpg">

 ## **DEFINISI**

Algoritma adalah sebuah langkah langkah   dibutuhkan untuk menyelesaikan suatu masalah 

## **PSEUDOCODE**

pseudocode adalah deskripsi dari algoritma pemrograman yang dituliskan secara sederhana tujuannya agar lebih mudah dibaca dan di pahami manusia.
* <img src="ss2.png" >

## **CONDITONAL**
adalah algoritma yg berjalan sesuai kondisi
jika kondisi A tidak terpenuhi maka output B
begitu sebaliknya, tetapi jika ke dua kondisi tidak terpenuhi maka output C
 * <img src="ee.png">

 



 






