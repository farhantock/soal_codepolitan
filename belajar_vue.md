# Soal Belajar cepat Vue.js
## Dasar Vue.js
1. Vue.js adalah framework javascript termasuk framework...
   
   a. BackEnd

   **b. FrontEnd**

   c. SideEnd

   d. TopEnd

2. Dalam Menginstal Vue.js terdapat beberapa cara yang paling umum diantaranya sebagai berikut :
   
   a. CDN (Content Delivery Network)

   b. Vue-CLI (Command Line Interface)

   c. dengan composser

   **d. Jawaban A dan B Benar**

3. Kita dapat menginstal Vue.js dengan mengakses website...
   
   a. https://vuejs.com/

   **b. https://vuejs.org/**

   c. https://vuejs.id/

   d. https://vuejs.sch

4. Vue.js versi terbaru adalah versi...

   **a. 3.x**

   b. 1.x

   c. 4.x

   d. 2.x

5. Penggunaan CDN dalam Vue.js bergantung dengan...
   
   a. Prosessor

   b. Keyboard

   **c. Internet**

   d. VGA
## Reactive data Vue.js

6. Reactive Data pada Vue.js adalah...
   
   **a. Hubungkan component atau suatu elemen dengan data secara otomatis akan terhubungan dan berubah secara realtime**

   b. Hubungan componet atau suatu elemen secara mandiri

   c. Hubungan component menjadi bagian satu ke satuan yang utuh dalam FrontEnd

   d. Hubungan data yang tampil terus menerus

## Bindding data Vue.js

7. Diketahui ada sebuah penggalan program pada file app.js yang berisi :
```
   var produk = {
      "nama"      : "Jaket Bomber Navy Blue",
      "deskripsi" : "Jaket Bomber Premium"
   }

   var app = new Vue({
      el: '#app',
      data : produk 
   });
   ```
   Bagaimana caranya kita memanggil variabel produk ke dalam Index.html ?
```
   a. <div id="app">
         <h1> {{nama}} </h1>
         <p>{{deskripsis}}</p>
      </div> 
   ```
```
   b. <div id="apps">
         <h1> {{nama}} </h1>
         <p>{{deskripsi}}</p>
      </div>
   ```
```
   **c. <div id="app">
         <h1> {{nama}} </h1>
         <p>{{deskripsi}}</p>
      </div>**
   ```
```
   d. <div id="apps">
         <h1> {{nama}} </h1>
         <p>{{deskripsi}}</p>
      </div>
   ```
8. Pada Script sebelumnya jika kita memanggil kode berikut   ```<h1> {{nama}} </h1>  ``` maka yang akan muncul beruba data...
   
   a. Jaket Bomber Navy green

   b. Jaket Bomber 

   c. Jaket Bomber Premium

   **d. Jaket Bomber Navy Blue**

9.  Dalam melakukan Binding Data ke dalam attribute HTML terdapat 2 cara yaitu...
    
```
   **a. <img v-bind:src="..." class="img-fluid" v-bind:alt="..."> atau <img :src="..." class="img-fluid" :alt="...">**
   ```
```   
    b. <img y-bind:src="..." class="img-fluid" y-bind:alt="..."> atau <img :src="..." class="img-fluid" :alt="...">
   ```
```
    c. <img src="..." class="img-fluid" alt="..."> atau <img :src="..." class="img-fluid" :alt="...">
   ```
```
    d. <img src="..." class="img-fluid" alt="..."> atau <img v-bind:src="..." class="img-fluid" v-bind:alt="...">
```

10. Dalam Vue.js perintah Looping menggunakan syntax...
    
    a. @foreach
    
    b. for
    
    **c. v-for**
    
    d. @endforeach
    
11. Dalam Vue.js untuk memanggil atau membuka array dengan cara..
    
    a. {{$data->name}}

    b. {{$data['name']}}

    c. {{$data->produk['name']}}

    **d. {{data.name}}**

12. Berikut beberapa syntax Looping yang benar adalah...
```
   ** a. <ul>
         <li v-for='product in products'>
            {{ product.name }}
         </li>
      </ul>**
   ```
```
    b.<ul>
         <li v-for='product in products'>
            {{ product->name }}
         </li>
      </ul>
   ```
```
    c.<ul>
         <li for='product in products'>
            {{ product.name }}
         </li>
      </ul>
   ```
```
    d.<ul>
         <li x-for='product in products'>
            {{ products.name }}
         </li>
      </ul>
   ```
13. Fungsi Lopping adalah...
    
    **a. Mengulang suatu kondisi terus menerus hingga kondisi itu tercapai**

    b. Menampilkan data - data

    c. Mengenerate data - data

    d. Mengulang suatu kondisi hanya 1 kali saja

14. Dalam Vue.js perintah If menggunakan syntax...
    
    a. @if

    b. if

    **c. v-if**

    d. @endif

15. Berikut beberapa syntax If yang benar adalah...
```
    a. <div v-if="item->harga <=100"> 
         ...
      </div>
   ```
```
    b. <div v-if="item=>harga <=100"> 
         ...
      </div>
   ```
```
    c. <div v-if="items.harga <=100"> 
         ...
      </div>
   ```
```
    **d. <div v-if="item.harga <=100"> 
         ...
      </div>**
   ```
16. Ada potongan syntax sebagai berikut :
```
     var produk = [{
      "kode"      : "001"
      "nama"      : "Jaket Bomber Navy Blue",
      "deskripsi" : "Jaket Bomber Premium"
      "harga"     : "100"
   },
   {
      "kode"      : "002"
      "nama"      : "Jaket Bomber Navy Blue",
      "deskripsi" : "Jaket Bomber Premium"
      "harga"     : "99"
   }
   ]
   v-if="item.harga <100" 
   ```
   maka data yang akan tampil adalah...

   a. kode 001

   **b. kode 002**

   c. kode 001 dan 002

   d. semua jawaban salah

17. Sysntax else pada Vue.js adalah...
    
   a. @elseif

   b. else

   **c. v-else**

   d. elseif

