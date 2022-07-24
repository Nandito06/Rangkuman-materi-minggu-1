# **Rangkuman Minggu Ke-2**

## **javaScript(Dasar)**
---
<img src="https://pandagila.com/wp-content/uploads/2021/11/apa-itu-javascript.png">

JavaScript adalah merupakan bahasa pemograman yang membuat suatu halaman website menjadi lebih interaktif dan dinamis

### **Contoh Syntax Javascript:**
**1. Alert**

- Alert digunakan untuk menampilkan notif pesan

contoh penggunaannya:
- > alert("Terima Kasih Sudah Mendaftar")

**2. prompt**
- adalah sebuah notif yang bisa di isi 

contoh penggunaannya:
- > prompt("Tuliskan Nama Anda")

**3. Confirm**
- adalah notif yg di gunakan untuk menanyakan intraksi selanjutnya

contoh penggunaanya: 
- > Confirm("press a button")

### **Console log**

adalah tempat untuk menampilkan apa yg kita tulis pada console
> contoh: console.log(hai)

### **Tipe-Tipe Data**

**1. Number**
- adalah tipe data yg mengandung semua angka termasuk angka desimal 
> contoh: let number = 123;

**2. String**
- adalah tipe data yang berisikan berbagai karakter seperti angka, huruf
> contoh: let= "halo 5 orang";

**3. Boolen**

- tipe data yang berisi 2 buah nilai yaitu:True and False
> contoh: let benar= "true"

**4. Null**

- tipe data yang diartikan bahwa sebuah variable tidak memiliki nilai
- berbeda dengan string kosong tetap memiliki nilai stringd

**5. Undefined**
- tipe data dari pemanggilan variable yang belum di definisikan 

**6. object**
- tipe data yang saling berhubungan, tipa data ini menyimpan tipe data apapun


## **Cara  Mendefinisikan Variable**
- var
> var myName = 'andi'
- let
>  let meal= 'kacang'
- const
> const pi = '3,14'

### **Logical Oprator**
 **AND(&&)**

>- jika kondisi a,b benar = benar
>- jika a salah b benar  = salah
> - jika a,b salah = salah

 **OR(||)**
 > - jika a,b benar = benar
 > - jika a benar dan b salah = benar
 > - jika a,b salah = salah


 ## **Function**
 ---
 adalah sebuah kode yg di gunakan dalam sebuah grup untuk menyelsaikan satu fitur

 ### **Parameter dan argumen**
 - **parameter**
    
    merupakan data yang di input pada function

- **argumen**
   
   merupakan nilai yang digunakan saat memanggil function

   ### **Contoh Function**
1. hitunglah luas 2 persegi, persegi1(30) dan persegi2(s=10), lalu jumlahkan kedua persegi

 >-  function luasPersegi (s1,s2){
> - return s1*s2
> - }
> - let persegi1 =luasPersegi(30,30)
> - let persegi2 =luasPersegi(10,10)
>- let jumlahPersegi= persegi1 + persegi2
> - console.log(jumlahPersegi)

2. Buat sebuah function untuk toko online kita. Ikuti poin-poin dibawah ini:
Function mempunyai 2 parameter yaitu nama pembeli dan produk yang dibeli
Function akan mengembalikan nilai “Terima kasih (nama pembeli) telah membeli produk (produk yang dibeli)”
Panggil function dengan menggunakan console.log()


> -  function(name='nando', produk='kopi'){
    return 'terima kasih' + name + telah membeli + 
    produk 
    }

    console.log('nando ', 'kopi ')

 
# **DOM**
dom atau document object model yang di gunakan untuk memanipulasi text html atau css

- **mencari element HTML**

   ada 4 cara yaitu:
   1. document.getElementById("id_tag")
   2.  document.getElementByClass("class_tag")
   3. document.querySelector(#(id).(class))
   4. document.querySelectorAll(#(id).(class))
  

- **mengubah konten html**
    1. Element.textContent (menampilkan seluruh konten termasuk tag cth = ``` <p>halo</p>```)
    2. Element.innerHTML (mengubah konten html)

- **Interaksi User (Events)**

di gunakan untuk berintraksi dengan user
dapat di gunakan dengan cara **Element.addEventListener(“event”)**

beberapa contoh event:

 **1. clik**

   - pada html
   >  ```<button id="alert-button">show</button>.```   
   - pada js
   > let button = document.getElementById("alert-button")
 button.addEventListener("click", function() {
	alert("haloo cuy")  
 })

 **2. Blur**

- pada html
> ```	<input id="username" />		```
- pada js
>let input = document.getElementById("username")
 input.addEventListener("blur", function (event) {
	console.log(event.target.value)
 });




     


