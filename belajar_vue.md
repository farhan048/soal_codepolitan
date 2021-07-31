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

6. Reactive Data pada Vue.js adalah...
   
   **a. Hubungkan component atau suatu elemen dengan data secara otomatis akan terhubungan dan berubah secara realtime**

   b. Hubungan componet atau suatu elemen secara mandiri

   c. Hubungan component menjadi bagian satu ke satuan yang utuh dalam FrontEnd

   d. Hubungan data yang tampil terus menerus

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
   
   a. v-switch

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

## Mengatur Style CSS

46. Untuk mempersingkat sysntax directive kita dapat menggunakan...
    
    a. =>

    **b. :**

    c. -->

    d. ==

47. Penulisan syntax binding array yang tepat adalah...
    
    a. :class="['font-weight-bold'. 'mr-2']"

    b. :class="['font-weight-bold'; 'mr-2']"

    **c. :class="['font-weight-bold', 'mr-2']"**

    d. :class="['font-weight-bold'- 'mr-2']"

48. Di Vue.js kita bisa melakukan binding attribute dengan melakukan binding...
    
    a. JSON

    b. Array

    c. Objek

    **d. Jawaban B dan C Benar**

49. Dalam memanggil attribute kelas dalam binding array kita dapat menggunakan sysntax...
    
    **a. :class="style.label"**

    b. :class="style, label"

    c. :class="style -> label"

    d. :class="style:label"

50. Penulisan sysntax binding objek yang tepat adalah...
    
    a. :class="['font-weight-bold', 'mr-2']"

    **b. :class="{'font-weight-bold', 'mr-2'}"**

    c. :class="['font-weight-bold', 'mr-2'}"

    d. :class="{'font-weight-bold'; 'mr-2'}"

51. Selain menggunakan property data untuk style kita juga dapat menggunakan property...
    
    a. Computed

    b. Method

    **c. Jawaban A dan B Benar**

    d. Switch

52. Pada Vue.js kita bisa memanggil 2 class sekaligus yaitu class html dan class vue.js dengan cara... 

    a. ```<div class="align-items center" class="style.label"> </div>```

    b. ```<div :::class="align-items center" :class="style.label"> </div>```

    c. ```<div :class="align-items center" :class="style.label"> </div>```

    **d. ```<div class="align-items center" :class="style.label"> </div>```**

53. Pada Styling Secara Terprogram lebih efisien menggunakan property...

    **a. Computed**

    b. Method

    c. Data

    d. Mounted

54. Kita dapat menggunakan icon dengan menggunakan CDN dari...

    a. Vue.js

    **b. Fontawesome**

    c. CodeIgniter

    d. Laravel

55. Bagaimana cara mengakses CDN dari fontawesome...

    a. Menaruh link CDN ke dalam file app.js

    b. Menaruh link CDN ke dalam file web.php

    **c. Menaruh link CDN ke dalam file HTML**

    d. Menaruh link CDN ke dalam file vue.js

56. Selain menggunakan v-on untuk menyingkat directive event handler click kita dapat menggunakan...

   a. @doubleclick

   b. @if

   c. @clickdata

   **d. @click**

57. Membuat transisi pada Vue.js kita memerlukan tag...
    
    **a. ```<transition> </transition>```**

    b. ```<transisi> </transisi>```

    c. ```<transicion> </transicion>```

    d. ```<ternsition> </ternsition>```

58. Berikut list kelas transisi pada Vue.js yang tepat adalah...
    **a. V-enter,  v-enter-active, v-enter-to, v-leave, v-leave-active, v-leave-to**   

    b. V-enter,  v-enter-active, v-enter-to, v-enter, v-enter-active, v-enter-to

    c. V-switch,  v-switch-active, v-enter-to, v-leave, v-leave-active, v-leave-to

    d. V-in,  v-in-active, v-in-to, v-leave, v-leave-active, v-leave-to

59. Jika kita tidak memberikan name pada tag transisi kita wajib memberikan nilai...

    a. w-

    **b. v-**

    c. s-

    d. z-

60. Untuk Mengatur animasi transisi kita dapat lakukan pada file...
    a. app.js

    b. app.php

    **c. app.css**

    d. app.vue

61. Konfigurasi animasi pada Vue.js menggunakan...

    **a. css**

    b. php

    c. laravel

    d. html

62. Selain animasi bawaan Vue.js kita bisa menambahkan banyak animasi lainnya dengan library...

    a. livewire

    b. vuex

    **c. animate.css**

    d. dompdf

63. Kita bisa menggunakan library animate.css dengan cara...

    a. Menggunakan NPM  

    b. Menggunakan Yarn

    c. Menggunakan CDN

    **d. Semua Jawaban Benar**

64. Untuk animasi masuk kita menggunakan property...
    
    **a. enter-active-class**

    b. enter-class

    c. In-active-class

    d. inside-active-class

65. Untuk animasi keluar kita menggunakan property...
    
    a. exit-class

    b. leave-class

    **c. leave-active-class**

    d. exit-leave-active-class

66. Variabel atau nilai default yang wajib dipakai untuk menggunakan library animate.css adalah...

    a. animasi

    **b. animated**

    c. anime

    d. animate

67. Bagaimana cara kita Menggunakan Transition Group...
    
    a. Menggunakan tag ```<ternsition-group> </ternsition-group>```

    b.  Menggunakan tag ```<transicion-group> </transicion-group>```

    c.  Menggunakan tag ```<transisi-group> </transisi-group>```

    **d.  Menggunakan tag ```<transition-group> </transition-group>```**

68. Fungsi tag pada Transition Group adalah...
    
    **a. Untuk memberitahu bawah transisi akan di berikan kepada elemen div**

    b. Untuk pengenal data transisi

    c. Untuk gaya transisi

    d. Untuk menyimpan data transisi

69. Dalam menggunakan Transition Group diperlukan key berfungsi...
    
    a. Sebagai penyimpan data

    **b. Sebagai indentifikasi pada data**

    c. Sebagai fungsi menjalankan perulangan

    d. Sebagai fungsi menghentikan perulangan

70. Penggunaan attribute key biasanya menggunakan sesuatu yang...

    **a. Unik**

    b. Seragam

    c. Beragam

    d. Mandiri

71. Selain attribute yang unik dari data kita bisa juga menggunakan indikator key dari...

    a. id data

    b. data - data

    c. array

    **d. index dari for / perulangan**

72. Berikut urutan event untuk animasi transisi yang benar adalah...

    **a. @beforeEnter -> @enter -> @levae**

    b. @Enter -> @beforeEnter -> @levae

    c. @beforeEnter -> @levae -> @enter

    d. @before -> @enter -> @levae

73. Untuk mengkonfigurasi event animasi transisi dilakukan pada property...

    a. Mounted

    b. Computed

    **c. Method**

    d. css

74. Selain menggunakan transisi bawaan Vue.js dan library kita juga dapat membuat animasi transisi dengan...

    a. PHP

    **b. Javacript**

    c. Vue

    d. Flutter

75. Delay pada property method berfungsi untuk...

    **a. Menunda waktu kemunculan elemen**

    b. Menunda proses menampilkan

    c. Menunda proeses data

    d. Menunda pengambilan data

## Mendalami Vue.js

76. Bagaimana cara menggunakan property filter...
    
    **a. {{ value data | fungsi filter }}**

    b. {{ value data || fungsi filter }}

    c. {{ value data == fungsi filter }}

    d. {{ value data != fungsi filter }}

77.   return 'Rp' + Number.parseFloat(value).toFixed(2); 
    
    parseFloat berfungsi untuk...

    **a. Memparse atau mengubah value ke dalam bentuk desimal**

    b. Memparse atau mengubah value ke dalam bentuk bilangan bulat atau int

    c. Memparse atau mengubah value ke dalam bentuk string

    d. Memparse atau mengubah value ke dalam bentuk boolean

78.  return 'Rp' + Number.parseFloat(value).toFixed(2);
    
    toFixed(2) berfungsi untuk...

    a. Menambahkan 1 angka di belakang koma

    b. Menambahkan angka di belakang koma

    **c. Menambahkan 2 angka di belakang koma**

    d. semua jawaban salah

membuat data toggle elemen

79.  ```<button class="btn btn-succes btn-sm dropdown-toggle" id="dropdowncart" data-toggle="dropdwon" aria-haspopup="true" aria-expanded="false">Cart</button>```
    hasilnya adalah...

    **a.** <a href="https://imgbb.com/"><img src="https://i.ibb.co/qRFT7Dh/a.png" alt="a" border="0"></a>

    b. <a href="https://imgbb.com/"><img src="https://i.ibb.co/b30spjs/b.png" alt="b" border="0"></a>

    c. <a href="https://imgbb.com/"><img src="https://i.ibb.co/wW5Zftx/c.png" alt="c" border="0"></a>

    d. <a href="https://imgbb.com/"><img src="https://i.ibb.co/XWCYb0G/d.png" alt="d" border="0"></a>

80.  Fungsi dari data-toggle adalah...

    a. sebagai trigger untuk button

    **b. sebagai trigger untuk dropdownd**

    c. sebagai trigger untuk filter

    d. sebagai trigger untuk menghapus

81.  For pada dropdown cart berfungsi untuk...

    a.  Melakukan perulangan untuk Memfilter semua data

    **b. Melakukan perulangan untuk menapilkan semua data yang ada pada cart**

    c. Melakukan perulangan untuk menjumlah semua data

    d. Melakukan perulangan untuk menghitung semua data


82.  Pengkategorian Data dalam array menggunakan fungsi...

    **a. Filter**

    b. Method

    c. Mounted

    d. Computed

83.  Untuk mengategorikan data dalam array diperlukan variabel...

    a. var productPrice;

    b. var productQty;

    c. var productName;

    **d. var productIndex;**

84.  Pehatikan syntax berikut :

    <a href="https://ibb.co/Hr8ZMy0"><img src="https://i.ibb.co/p3FqsTg/addItem.png" alt="addItem" border="0"></a>
  
    fungsi dari if else yang ditandai oleh kotak merah  adalah...

    **a. Mengecek apakah id produk ada yang sama atau tidak**

    b. Mengecek apakah nama produk ada yang sama atau tidak

    c. Mengecek apakah qty produk ada yang sama atau tidak

    d. Mengecek true dan false ada yang sama atau tidak
   

85.   fungsi cart total berada pada property...

    a. Mounted

    b. Filter

    **c. Computed**

    d. Method

86.   Bagaimana untuk mendapatkan nilai total...

    a.Menyamakan harga produk dengan kuantiti

    b. Menambahkan harga produk dengan kuantiti

    c. Membagi harga produk dengan kuantiti

    **d. Mengkalikan harga produk dengan kuantiti**

87.   Sysntax fungsi total yang tepat adalah...

    **a.cartTotal: function () {
            let sum = 0;
            for (key in this.cart) {
                sum = sum + (this.cart[key].product.price * this.cart[key].qty);
            }
            return sum;**

    b.cartTotal: function () {
            let sum = 0;
            for (key in this.cart) {
                sum = sum - (this.cart[key].product.price * this.cart[key].qty);
            }
            return sum;

    c.cartTotal: function () {
            let sum = 0;
            for (key in this.cart) {
                sum = sum * (this.cart[key].product.price * this.cart[key].qty);
            }
            return sum;

    d.cartTotal: function () {
            let sum = 0;
            for (key in this.cart) {
                sum = sum / (this.cart[key].product.price * this.cart[key].qty);
            }
            return sum;

88.  Untuk menghapus data diperlukan method...

    **a. Slice**

    b. Delete

    c. Pop

    d. Push

89.  synstax untuk menghapus item dalam array yang tepat adalah...

    a.deleteItem: function(id) {

            if(this.cart[id].qty < 1) {
                this.cart[id].qty--;
            } else {
                this.cart.splice(id, 1);
            }

        }
    **b.deleteItem: function(id) {

            if(this.cart[id].qty > 1) {
                this.cart[id].qty--;
            } else {
                this.cart.splice(id, 1);
            }
        }**

    c.deleteItem: function(id) {

            if(this.cart[id].qty > 1) {
                this.cart[id].qty++;
            } else {
                this.cart.splice(id, 1);
            }

        }

    d.deleteItem: function() {

            if(this.cart[id].qty > 1) {
                this.cart[id].qty--;
            } else {
                this.cart.splice(id, 1);
            }

        }

90.  Fungsi preventive stop pada @click berfungsi untuk...

    **a. memberhentikan dropdown cart agar tidak menutup**

    b. memberhentikan data agar tidak menutup

    c. memberhentikan running dari vue 

    d. memberhentikan running dari browser 

## Mendalami Component pada Vue.js

91.  Component adalah...
    
    a. Template yang dipakai satu kali saja kemudian tidak bisa di pakai kembali

    **b. Template yang dapat di pakai berulang - ulang**

    c. Template yang mesti di buat berulang - ulang

    d. Template yang mesti di buat berulang - ulang tetapi hanya dapat di pakai 1 kali

92.  Parameter yang digunakan pada Component adalah...

    **a. Nama dari component dan objek**

    b. Nama objek

    c. Nama component

    d. value yang akan di kirim ke dalam component

93.  Bagaimana cara memanggil Component ?

    a. Membuat div yang class nya nama dari component

    b. Membuat container yang class nya nama dari component

    **c. Membuat tag yang sesuai dengan nama Component**

    d. Membuat tag head yang isinya component

94.  Penulisan Nama Props terletak di...

    a. Pada tag div

    b. pada tag container

    c. pada tag body atau head

    **d. pada tag component**

95.  Props dapat menyimpan banyak data maka tipe data props berupa...

    **a. Array**

    b. String

    c. Int

    d. Float atau Double

96.  Untuk menyimpan value pada tag dibutuhkan directive...

    a. v-show

    b. v-click

    **c. v-bind:value**

    d. v-model:value

97.  Fungsi dari default value pada props adalah...

    a. Untuk menyimpan data 

    **b. Untuk meminimalisir kesalahan**

    c. Untuk memparse nilai

    d. Semua jawaban salah
    
98.  Dalam membuat Props yang memiliki nilai default, property apa saja yang diperlukan...

    **a. nama props, type data, nilai default**

    b. nama component, type data, nilai default

    c. nama props, type data, nilai value

    d. nama props, type data

99.   Penulisan sysntax props yang memiliki nilai default adalah...

    a.  props: {
        value: Number
        }

    **b.  props: {
         precision: {
            type: Number,
            default: 2
        }**

    c.  props: {
        
        prefix: {
            default: 'Rp'
        }
        }

    d.  props: {
        value: Number,
        prefix: {
            type: String,
            default: 'Rp'
        }

100.  Pada component kita dapat membuat atau menambahkan property...

    **a. Methods**

    b. Vuex

    c. default

    d. type

101.  Template pada component berfungsi untuk...

    a. Sebagai property untuk menyimpan data

    b. Sebagai property untuk memparse elemen

    **c. Sebagai property untuk menampilkan elemen**

    d. sebagai property untuk memparse data

102.  Apa yang harus dilakukann jika ada method atau elemen yang berada diluar component ?

    a. Memanggil method atau elemen tersebut dari objek global kedalam scop atau lingkup component

    **b. Memindahkan method atau elemen tersebut kedalam scop atau lingkup component**

    c. Memindahkan component kedalam method atau elemen tersebut

    d. Memindahkan method atau elemen tersebut kedalam scop atau lingkup component

103.  Untuk menggunakan Event Method dari Parent Component dibutuhkan property...

    **a. Emit**

    b. Emet

    c. value

    d. index

104.  Bagaimana cara menggunakan property emit pada template component...

    a. $emit('parameter', nama emit)

    **b. $emit('nama emit', parameter)**

    c. $emit('nama method', parameter)

    d. $emit('nama emit')

105.  Bagaimana cara menggunakan property emit pada tag component...

    **a.  <product-list :products="products" :maximum="maximum" @nama emit="Method parent"></product-list>**

    b.  <product-list :products="products" :maximum="maximum" $nama emit="Method parent"></product-list>

    c.  <product-list :products="products" :maximum="maximum" @nama emit="Method component"></product-list>

    d.  <product-list :products="products" :maximum="maximum" @nama method="nama emit"></product-list>

106. Pada template component symbol atau tanda yang digunakan untuk emit adalah...

     a. @

     **b. $**

     c. `

     d. ''

## Membangun project dengan Vue CLI

107. Dalam menginstal vue js CLi kita memerlukan software...

     **a. Nodejs dan git bash atau terminal lain sejenis**

     b. Nodejs dan OS mac

     c. Terminal atau comand promp

     d. Semua jawaban Salah

108. Perintah untuk menginstal vue js CLI adalah...

     a. npm install --g $vue\cli

     **b. npm install -g @vue/cli** 

     c. npm install -g @vue\cli

     d. npm install @vue->cli
     
109. Perintah untuk membuat project vue adalah...

     **a. vue create nama project**

     b. vue:make hello-world

     c. vue @create hello-world

     d. vue create hello-world
     
110. Ketika kita menjalankan perinah untuk membuat project vue, kemudian kita akan diberikan 2 opsi antara lain...

     a. default (babel, eslint) dan optimaze

     **b. default (babel, eslint) dan manually**

     c. default (babel, eslint) dan automatically 

     d. automatically  dan manually
     
111. Bagaimana cara meruning project vue cli...

     a. Buka terminal atau software sejenis, masuk kedalam direktori project dan ketikan npm start serve

     b. Buka terminal atau software sejenis, masuk kedalam direktori project dan ketikan npm running serve

     c. Buka terminal atau software sejenis, masuk kedalam direktori project dan ketikan npm run server

     **d. Buka terminal atau software sejenis, masuk kedalam direktori project dan ketikan npm run serve**
     
112. Scoped pada styling berfungsi untuk...

     **a. Melimitasi suati style yang nantinya akan bekerja pada component itu saja**

     b. Melimitasi suati style yang nantinya akan bekerja pada semua file src saja

     c. Melimitasi suati style yang nantinya akan bekerja pada component semua file yang ada

     d. Melimitasi suati style yang nantinya akan bekerja pada file js saja
     
113. Pada App.vue terdapat sysntax sebagai berikut :
     
 ```
<script>
import HelloWorld from "./components/HelloWorld.vue";
export default {
  name: "app",
  components: {
    HelloWorld
  }
};
</script>
```
Fungsi sysntax tersebut adalah...

     a.  Memanggil file HelloWorld.vue dari folder component

     **b. Memanggil file HelloWorld.vue dari folder component dan mengexportnya ke dalam file App.vue**

     c. Memanggil file App.vue dari folder component dan mengexportnya ke dalam file HelloWorld.vue

     d. Memanggil file HelloWorld.vue dari folder component dan mengexportnya ke dalam file main.js dan App.vue 
     
114. Untuk menyimpkn gambar, logo dan lain sebagainya kita letakan pada folder...

     a. src/component

     b. src/App.vue

     **c. src/assets**

     d. src/main.js
     
115. Pada folder component kita dapat menyimpan file...   
     
     a. Package modul

     **b. component atau view yang akan di gunakan pada project**

     c. ```READDME.md```

     d. Semua Jawaban Benar
     
116.   Modul yang sudah kita instal di vuejs akan tesimpan pada file...       
     
     **a. Package.Json**

     b. babel.config.js

     c. ```READDME.md```

     d. .gigigneore
     
117.   Perinah untuk menginstal modul adalah...     
     
     **a. npm i --save nama modul**

     b. npm a --save nama modul

     c. npm i --insert nama modul

     d. npm i --load nama modul
     
118.   Untuk melihat modul apa saja yang sudah terinstal kita bisa lihat pada objek...     
     
     a. DevDependencies

     b. EslintConfig

     c. Extends

     **d. Dependencies**
     
119.   Modul yang sudah kita instal dapat kita import pada file...     
     
     **a. main.js**

     b. App.vue

     c. babel.config.js

     d. Package.Json
     
120.   berikut cara import yang benar adalah...     
     
     a. import "nama package",

     **b. import "nama package";**

     c. import "nama package":

     d. import "nama package"

121. Bagaimana cara kita untuk mengimplementasikan modul di vuejs...
   
   a. Memanggil atau mengimport modul yang sudah di import dari file App.vue dan mengexportnya ke dalam file main.js

   b. Mengexport modul yang sudah di import dari file main.js dan mengexportnya ke dalam file Package.json

   c. Memanggil atau mengimport modul yang sudah di import dari file Package.json dan mengexportnya ke dalam file App.vue

   **d. Memanggil atau mengimport modul yang sudah di import dari file main.js dan mengexportnya ke dalam file App.vue**
     
## Implementasi VueRouter

122. VueRouter adalah...
     
     a. Library yang membantu dalam mengatur passing data

     **b. Library yang membantu dalam membuat struktur halaman dari project vue cli**

     c. Library yang membantu dalam membuat isi component

     d. Library yang membuat component

123. Bagaimana cara memanggil library VueRouter...

    **a. Dengan import package VueRouter dari node modules**

    b. Dengan memasukan script cdn ke main.js

    c. Dengan mengcopy packgae VueRouter ke dalam project CLI

    d. Semua jawaban benar

124. Pada file apa kita memanggil library VueRouter...
    
    **a. main.js**

    b. vue.app

    c. app.vue

    d. Semua jawaban Benar
    
125. sysntax untuk memanggil atau import yang tepat adalah...

    a. import VueRouter from node_modules "vue-router";

    b. import VueRouter from ('vue-router');

    c. import VueRouter from "node_modules.vue-router";

    **d. import VueRouter from "vue-router";**
    
126. Bagaimana sysntax mengconfig intance objek library VueRouter..

    **a. Vue.use(alias name pada import);**

    b. Vue.use(nama package);

    c. Vue.using(alias name pada import);

    d. Vue.use['alias name pada import'];
    
127. Fungsi dari property Routes adalah...

    **a. Menyimpan beberapa path dan component**

    b. Menyimpan data - data untuk menampilkan

    c. Menyimpan property VueRouter

    d. Menyimpan file component
    
128. Fungsi dari property Path adalah...

    a.

    b.

    c. Untuk mengenali url yang diakses user

    d.

129. Sysntax yang tepat untuk membuat VueRouter adalah..

    **a. const router = new VueRouter({
  routes: [
     {
       path: "*",
       component: Products
     },
     {
       path: "/checkout",
       component: Checkout
     }
  ]
});**

    b. const router = new VueRouter({
  routes: [ 'path: "*", component: Products', 'path: "/checkout", component: Checkout']});

    c. const router = new VueRouter({
  routes: [
     {
       path: "*",
       view : Products
     },
     {
       path: "/checkout",
       view : Checkout
     }
  ]
});

    d. const router = new VueRouter({
  routes: [
     {
       url : "*",
       component: Products
     },
     {
       url : "/checkout",
       component: Checkout
     }
  ]
});
    
    
1.     Tag component untuk VueRouter yang tepat adalah...

    **a. ```<router-view></router-view>```**

    b. ```<router-blade></router-blade>```

    c. ```<view-router></view-router>```

    d. ```<router-link></router-link>```
    
2.     Untuk menghubungkan antar component diperlukan sebuah tag yaitu...

    **a. ```<router-link> </router-link>```**

    b. ```<router-url> </router-url>```

    c. ```<uri-link> </uri-link>```

    d. ```<routes-link> </routes-link>```
    
3.     Fungsi to pada router-link adalah...

    a. Untuk menyimpan value path atau url halaman itu sendiri

    **b. Untuk menyimpan value path atau url dari halaman yang di tuju**

    c. Untuk menyimpan value path atau url halaman semua halaman yang ada di project

    d. Untuk menyimpan value path atau url halaman main.js
    
