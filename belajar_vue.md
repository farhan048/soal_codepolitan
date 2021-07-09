# Soal Belajar cepat Vue.js
## Perkenalan Vue.js

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
### Reactive data Vue.js

6. Reactive Data pada Vue.js adalah...
   
   **a. Hubungkan component atau suatu elemen dengan data secara otomatis akan terhubungan dan berubah secara realtime**

   b. Hubungan componet atau suatu elemen secara mandiri

   c. Hubungan component menjadi bagian satu ke satuan yang utuh dalam FrontEnd

   d. Hubungan data yang tampil terus menerus

### Bindding data Vue.js

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

### Looping pada Vue.js

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

### Kondisi pada Vue.js

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
   ** d. <div v-if="item.harga <=100"> 
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

18. Selain menggunakan v-if ada satu sysntax lagi yang dapat kita gunakan sebagai kondisi yaitu...
   
   a. v-tamin

   b. v-see
   
   c. v-display
   
   **d. v-show**

19. Untuk menampilkan data lebih dari sama dengan 5 maka sysntax yang di perlukan adalah...
    
    **a. ```<h1 v-if="item => 5"> ... </h1>```**
    
    b  ```<h1 v-if="item == 5"> ... </h1>```

    c. ```<h1 v-if="item > 5"> ... </h1>```

    d. ```<h1 v-if="item =< 5"> ... </h1>```

20. Jika kita mempunyai sysntax sebagai berikut
```
   var data = "awesome"
   ...
    <h1 v-if="data == 'awesome'">Vue is awesome!</h1>
    <h1 v-else>Oh no 😢</h1>
```
     maka hasil yang akan muncul adalah...
    
    a.Yeayy!!!
    
    b Oh no 😢

    **c.Vue is awesome!**

    d. Vue.js

###  Input Data dari User

21. Pada Vue.js kita dapat menggunakan kelas UI milik framework...
    
    a. Laravel

    b. Vue.js
    
    c. Visual Studio Code

    **d. Bootstrap**

22. Untuk menghandle inputan user kita bisa menggunakan Directive...
    
    **a. V-model**

    b. X-model
    
    c. Y-model

    d. S-model

23. Penulisan V-model yang benar adalah...
    
    a. ``` <input v-model=="message" >```

    **b. ``` <input v-model="message" >```**

    c. ``` <input v-model=>"message" >```

    d. ``` <input v-model->"message" >```

24. V-model sangat membantu dalam menghandle inputan user karena...
    
      a. Biasa seperti inputan Bootstrap

      b. Menunggu aksi terlebih dahulu

      **c. Langsung secara realtime pada UI**

      d. Menunggu proses lainnya 

### Lifecyle Hooks VueJS

25. Pengambilan data atau Fetch dari API biasanya berupa response data berbentuk...
    
    a. XML

    **b. JSON**

    c. Array

    d. HTML

26. Dalam Lifecycle Hooks Vue.js terdapat beberapa proses diantaranya...

 
    **a. Created, Mounted, Update, Destroy.**

    b. Created, Read, Update, Destroy.

    c. Created, Mounted, Delete, Destroy.

    d. Created, Mounted, Update, Update.

27. Mounted adalah method bawaan Vue.js yang berfungsi untuk...
    
    a. Untuk menaruh banyak fungsi atau method yang mau dipakai di dalam Vue

    b. Untuk menyimpan attribute

    **c. Mengaktifkan suatu fungsi atau kejadian pada saat component itu dipanggil**

    d. Untuk proses Logic


### Event dan Method

28. Untuk menghandle event dari user kita bisa menggunakan Directive
    
    a. v-do

    b. v-if

    c. v-show

    **d. v-on**

29. Penulisan v-on yang tepat adalah...
    
    a. ```<button v-on=>click="counter += 1">Add 1</button>```

    b. ```<button v-on-></button>click="counter += 1">Add 1</button>```

    **c. ```<button v-on:click="counter += 1">Add 1</button>```**

    d. ```<button v-on::click="counter += 1">Add 1</button>```

30. Pada Vue.js fungsi atau method yang akan kita gunakan mesti didefinisikan dengan...
    
    **a. Objek methods**

    b. Objek class

    c. Objek variabel

    d. Objek attribute

31. Penulisan fungsi pada Vue.js versi 2 yang tepat adalah...
    
    **a. namaMethod : function (parameter){ .... }**

    b. namaMethod :: function (parameter){ .... }

    c. namaMethod => function (parameter){ .... }

    d. namaMethod -> function (parameter){ .... }

32. Penulisan sysntax objek method yang benar adalah...
    
    a.
      methods => {

       namaMethod : function (parameter) { .... }
       
    }
   

    b.
      methods  {

       namaMethod : function (parameter) { .... }

    }
   
   

    **c.** 
      methods: {

       namaMethod : function (parameter) { .... }

    }
   

    d.
     methods:: {

       namaMethod : function (parameter) { .... }

    }
   

## Bekerja dengan template

33. Cara yang paling basic untuk membinding data di Vue.js adalah dengan cara...
    
    **a. {{ name }}**

    b. {{ $data->name }}

    c. {{ $data-->name }}

    d. {{ $data=>name }}

34.  Selain double curly braces {{ }} Binding data di Vue.js bisa dilakukan dengan directive...
    
    a. v-if

    b. v-show

    **c. v-html**

    d. v-blade

35.  kelebihan dari v-html adalah...
    
    **a. Dapat memparse script html atau elemen html**

    b. Dapat menyimpan data

    c. Dapat menapilkan data

    d. Dapat memproses data

36.  v-html juga cukup berhabaya jika digunakan pada kondisi yang kurang tepat karena dapet menyababkan...
    
    a. Serangan Ransomware

    **b. Cross Script Injection**

    c. Serangan Malware

    d. Semua Jawaban salah

37.  Untuk menampilkan value yang pertama kali dideklarasikan kita dapat menggunakan directive...
    
    a. v-if

    b. v-show

    c. v-html

    **d. v-once**

38. Kita juga dapat memanipulasi atau me-overide value dari v-bind dengan cara menaruh attribute nya pada file...
    
    **a. app.js**

    b. .env

    c. config.js

    d. route.php

39. Apa maanfaatnya jika kita menaruh value atau attribute ke dalam file app.js...

    a. Mempermudah dalam pembuatan perangkat lunak

    b. Mudah dalam memanggil value atau attributenya

    c. Tidak perlu membuat value atau attribute yang sama

    **d. Semua Jawaban Benar**

40. Kita juga dapat menambahkan beberapa nilai class dengan cara...

    **a. ```<img :src="img-fluid + 'rounded'" class="img-fluid" :alt="...">```**

    b. ```<img :src="img-fluid + rounded" class="img-fluid" :alt="...">```

    c. ```<img :src="img-fluid.rounded" class="img-fluid" :alt="...">```

    d. ```<img :src="img-fluid-rounded" class="img-fluid" :alt="...">```

41. Bagaimana cara penulisan v-bind dengan struktur JSON yang benar...

    **a.<img v-bind="{
       
       class : imgClass,

       src : products[0].image,

       alt : products[0].name

    }"> **
    
    b.<img v-bind="{

       class : imgClass;

       src : products[0].image,

       alt : products[0].name

    }"> 
    

    c.<img v-bind="{

       class : imgClass +

       src : products[0].image +

       alt : products[0].name

    }"> 
    

    d. <img v-bind="{

       class : imgClass;

       src : products[0].image;

       alt : products[0].name

    }"> 
    
42. Computed Property dapat mengubah atau mereplace slug dengan...
    
    a. Permanen

    **b. Realtime atau Dinamis**

    c. Lama

    d. Menunggu proses

43. Pebedaan Computed dan method adalah...
    
    a. Methods akan menjalankan fungsi terus menerus dan computed menjalan fungsi terus menerus juga

    b. Sama - sama menjalankan fungsi

    **c. Jika Computed menyimpan chache sedangkan method tidak, Jadi bila dalam sebuah view muncul 100 variable yg sama, computed hanya menjalankan fungsi 1x saja (selama tidak ada perubahan), sedangkan methods akan menjalankan fungsi tersebut 100x**

    d. Semua jawaban benar

44. Computed property lebih unggul karena...
    
    a. Semua jawaban salah

    b. Menjalankan fungsi terus menerus
    
    c. Menjalankan fungsi ketika ada koneksi

    **d. Hanya menampilkan data selama itu ada perubahan jika tidak ada perubahan maka menampilkan hal yang sama sehingga menyimpan chahce pada browser**

45. Method pada Vue.js lebih berat karena...
    
    **a. Methods akan menjalankan fungsi terus menerus walaupun tidak ada perubahan**

    b. Menjalakan fungsinya ketika ada perubahan saja

    c. Tidak melakukan apa - apa

    d. Semua jawaban salah

### Mengatur Style CSS

