# Membuat Halaman Website Portofolio Menggunakan Tailwind CSS

## Pendahuluan
### Pendahuluan
1. Apa kelebihan Tailwind CSS ?

   a. Lebih mudah di custom

   **b. Tidak responsif**

   c. Lebih mudah membuat desain unik tanpa framework

   d. Responsif

2. Step by step pembuatan web portofolio, **Kecuali** ?

   a. Menyiapkan halaman html & menautkan file css atau link CDN.

   b. Menentukan apa saja yang ingin ditampilkan di web portofolio, seperti navigasi bar, about me, skill, recent work, contact me dan footer.

   c. Membuat bagian demi bagian yang sudah ditentukan dan mempercantik tampilannya

   **d. Melakukan hosting**

3. Impelementasi materi dasar tailwindcss yang tepat adalah...
   
    a. Security

    b. Validation

    **c. Flexbox dan Grid**

    d.AI

4. Tampilkan di web portofolio biasanya terdiri atas ?

    **a. Navigasi bar, about me, recent work dan contact me**

    b. hobi, gaji, navigasi bar, dan about me

    c. Contac me, foto keluarga

    d. Foto kendaraan, nomer rekening, data pribadi rahasia

### Kerangka Layout
5. Rancangan yang biasanya digunakan web portofolio adalah ?
   
    a. Navigasi bar, About me, blog, register form

    **b. About me, Navigasi bar, My Recent Work**

    c. Navigasi bar, login form, register form

    d. Contact me, footer, login form

6. Hal apa yang dilakukan untuk memulai membuat layout portofolio dengan tailwindcss ?

    a. Folder untuk menyimpan file-file proyek kita

    b. File html untuk membuat layout web portofolio

    c. File tailwindcss atau link CDN

    **d. Semua jawaban benar**

7. Untuk menggunakan Tailwind CSS terdapat berapa cara ?

    a. 3

    b. 4

    **c. 2**

    d. 1

8. 2 Cara untuk menggunakan Tailwind CSS terdiri atas ?

    **a. File tailwindcss atau link CDN**

    b. File tailwindcss atau Microservices

    c. Microservices atau link CDN

    d. Semua jawaban benar

9.  Untuk membuat setiap bagian dari kerangka web menggunakan elemen ?

    a. div

    **b. section**

    c. component

    d. item

10. Untuk menggunakan Tailwind CSS pada elemen kita perlu menggunakan ?

    a. item

    **b. class**

    c. list

    d. component

11. Syntax Tailwind untuk Section navigasi bar yang tepat adalah ?

    a. ```<section class="w-screen mx-auto py-4 bg-indigo-700 h-32 img">Navigasi me</section>```

    **b. ```<section class="w-screen mx-auto px-4 h-8"> Navigasi Bar</section>```**

    c. ```<section>Navigasi bar</section>```

    d. ```<class="w-screen mx-auto py-4 bg-indigo-700 h-32">Navigasi bar </class>```

12. w-screen berfungsi untuk...

    **a. memastikan elemen menjangkau seluruh lebar viewport**

    b. memastikan elemen menjangkau sebagian lebar viewport

    c. memastikan elemen tampil sebagian lebar viewport

    d. semua jawaban benar

13. mx-auto berfungsi untuk...

    a. Mengatur margin vertikal secara auto

    b. Mengatur padding horisontal secara auto

    **c. Mengatur margin horisontal secara auto**

    d. Mengatur padding vertikal secara auto

14. Syntax untuk memberikan warna background yang tepat adalah ?

    a. bg-colour-indigo-700

    b. bg:indigo-700

    c. Colour-bg-indigo-700

    **d. bg-indigo-700**

15. Untuk membedakan warna antara tampilan kecil dan besar menggunakan ?

    **a. breakpoint**

    b. break

    c. edge

    d. boundery

16. Dalam Tailwind terdapat beberapa breakpoint, **Kecuali** ?

    **a. sx**

    b. sm

    c. md

    d. lg

### Membangun Navigasi Bar
17. Apa saja yang harus disiapkan dalam membuat navigasi bar ?  

    a. Rancangan tampilan navigasi bar.

    b. Gambar atau logo jika dibutuhkan.

    c. Elemen-elemen yang akan ditampilkan di navigasi bar.

    **d. Semua jawaban benar**

18. Untuk membuat navigasi bar menggunakan elemen ?

    **a. nav**

    b. menu

    c. div

    d. item

19. Syntax untuk menampilkan logo adalah...

    a. 
    ```
        <div class="flex flex-shrink-0 mr-6">
            <img path="img/logo.png" class="h-10 w-50 mr-2">
       </div>
    ```

    b. 
    ```
        <div class="flex flex-shrink-0 mr-6">
            <img url="img/logo.png" class="h-10 w-50 mr-2">
       </div>
    ```

    c. 
    ```
        <div class="flex flex-shrink-0 mr-6">
            <image link="img/logo.png" class="h-10 w-50 mr-2">
       </div>
    ```

    **d. 
    ```
        <div class="flex flex-shrink-0 mr-6">
            <img src="img/logo.png" class="h-10 w-50 mr-2">
       </div>
    ```
    

20. Untuk link menu menggunakan elemen ?

    a. ```<b>```

    **b. ```<a>```**

    c. ```<button>```

    d. ```<link>```

21. flex-shring-0 berfungsi untuk...

    a. untuk mencegah data pada elemen hilang

    **b. untuk mencegah penyusutan item flex**

    c. untuk mengeluarkan item dari flex

    d. untuk mengeluarkan item dari viewport

22. Utilitas untuk mengatur tinggi logo menggunakan ?
    
    **a. h**

    b. w

    c. mr

    d. flex

23. flex-wrap berfungsi untuk ?
    
    a. untuk memastikan item-item flex di dalamnya terbungkus di luar container semua

    b. untuk memastikan container di dalamnya terbungkus di dalam item-item flex semua

    c. untuk memastikan item-item flex dan container di dalamnya terbungkus di dalam view port semua

    **d. untuk memastikan item-item flex di dalamnya terbungkus di dalam container semua**
    
24. Berikut List menu navigasi bar yang tepat adalah ?
    
    a. Contact me

    b. Recent work

    c. About me

    **d. semua jawaban benar**

25. Untuk utilitas yang bekerja dengan breakpoint tertentu kita bisa menambahkan nya dengan cara ?    
    
    a. Membungkus utilitas dengan dalam kurung dan berikan identitas breakpointnya

    **b. Menambahkan identitas breakpoint sebelum utilitas**

    c. Menambahkan utilitas kemudian menuliskan breakpoint

    d. Semua jawaban benar

26. Syntax untuk penggunaan utilitas pada breakpoint lg yang tepat adalah ?     
    
    **a. lg:items-center** 

    b. lg::w-auto

    c. lg->flex-grow

    d. lg=>flex-grow

27. Block berfungsi untuk ?   
    
    a. untuk

    b. untuk

    c. untuk membuat background block

    **d. untuk membuat elemen block-level**

28. Syntax untuk membuat button yang tepat adalah ?   
    
    **a.
    ```
        <div class="block lg:hidden">
       <a class="flex items-center px-3 py-2 rounded border border-indigo-400 text-indigo-500 hover:text-indigo-700 hover:border-indigo-700">
         <svg class="fill-current h-3 w-3" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><title>Menu</title><path d="M0 3h20v2H0V3zm0 6h20v2H0V9zm0 6h20v2H0v-2z"/></svg>
         </a>
            </div>
    ```**

    b. ```
        <div class="block lg:hide">
       <a class="flex items-center px-3 py-2 rounded border border-indigo-400 text-indigo-500 hover:text-indigo-700 hover:border-indigo-700">
         
         </a>
            </div>
    ```

    c. 
    ```
       <a class="flex items-center px-3 py-2 rounded border border-indigo-400 text-indigo-500 hover:text-indigo-700 hover:border-indigo-700">
         <svg class="fill-current h-3 w-3" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><title>Menu</title><path d="M0 3h20v2H0V3zm0 6h20v2H0V9zm0 6h20v2H0v-2z"/></svg>
         </a>
    ```

    d.
    ```
        <div class="block lg:hidden">
       
            </div>
    ```

29. Utilitas untuk membuat ujung dari button tumpul adalah ?   
    
    a. round

    **b. rounded**

    c. circle

    d. ratangle

30. Utilitas untuk membuat sorotan pada button adalah ?   
    
    a. spotlight

    **b. hover**

    c. brightness

    d. intensity

31. Untuk menyembunyikan button dengan utilitas ?   
    
    **a. hidden**

    b. block

    c. hide

    d. lock

32. Link website Tailwind css yang tepat adalah....

    a. https://tailwindcss.co.id/

    b. https://tailwindcss.sch/

    c. https://tailwindcss.uk/

    **d. https://tailwindcss.com/**

## About me
### About Me Bagian 1
33. Icon yang digunakan berupa ?   
    
    **a. Font Awesome**

    b. Remixicon

    c. Tabler Icons

    d. Material Design

34. Untuk menampilkan judul menggunakan elemen ?   
    
    **a. h1**

    b. h6

    c. Dispyal-1

    d. h2

35. Mengatur ukuran font menggunakan ?   
    
    a. text-size-5xl

    **b. text-5xl**

    c. text-weight-5xl

    d. text-width-5xl

36. Mengatur about me untuk rata tengah menggunakan ?   
    
    a. item-center

    b. flex-between

    **c. text-center**

    d. Semua jawaban benar

37. text white berfungsi untuk ?   
    
    a. digunakan untuk mengatur font style

    b. digunakan untuk mengatur font size

    c. digunakna untuk mengatur background text color

    **d. digunakan untuk mengatur warna text**

38. Mengatur lebar garis menggunakan ?   
    
    **a. w-**

    b. h-

    c. width-

    d. heigth-

39. Mengatur tinggi garis menggunakan ?   
    
    **a. h1**

    b. width

    c. tall

    d. heigth

40. Elemen untuk sambutan menggunakan ?   
    
    a. h2

    **b. h1**

    c. h3

    d. h4
    
41. Mengatur padding vertikal menggunakan ?

    **a. py**

    b. pz

    c. pa

    d. px

42. Mengatur padding horizontal menggunakan ?

    a. pz

    **b. px**

    c. py

    d. pa

43. Foto di simpan pada folder ?

    a. image

    b. icon

    c. logo

    **d. img**

44. Path img url yang tepat adalah ?

    a. image.baby.jpg

    **b. img/baby.jpg**

    c. img.baby.jpg

    d. image/baby.jpg

45. shadow lg berfungsi membuat ?

    **a. Untuk memberikan efek bayangan**

    b. Menampilkna gambar

    c. Menampilkan path gambar

    d. Semua jawaban benar

46. Rounded-full berfungsi untuk ?

    a. Untuk menampilkan gambar

    b. Untuk membuat background gambar

    **c. Untuk membuat mengatur border radius pada suatu elemen**

    d. Semua jawaban salah

47. gradient yang digunakan adalah gradient ?

    a. bg-gradient

    **b. linear-gradient**

    c. transparent-gradient

    d. gradient-linear-bg

48. Arah dari gradient yang tepat adalah ?

    **a. to bottom right**

    b. to top right

    c. to bottom

    d. to left

49. berapa warna yang digunakan untuk membuat gradient 

    a. 3

    b. 5

    **c. 2**

    d. 1

50. Colour code yang digunakan adalah ?

    a. czrb code

    b. cmyk code

    c. rgb code

    **d. hex code**

### About Me Bagian 2
51. Pembuatan box menggunakan ?
    
    a. flex

    **b. grid**

    c. layout

    d. tables

52. Syntax untuk menentukan jumlah kolom yang tepat adalah ?

    a. grid-rows-cols-1

    b. grid-row-1

    **c. grid-cols-1**

    d. grid-cols-1-1

53. md:grid-cols-3 berfungsi untuk ?

    a. Jumlah baris yang akan kita tampilkan

    **b. Jumlah kolom yang akan kita tampilkan**

    c. Jumlah tabel yang akan kita tampilkan

    d. Jumlah cell yang akan kita tampilkan

54. utilas mengatur margin yang digunakan pada box adalah ?

    a. mt-5

    b. mx-auto

    c. p-auto

    **d. rounded-lg**

55. Untuk membuat sudut dari box membulat atau tumpul menggunakan utilitas ?

    a. circle-box

    b. unrounded

    **c. rounded**

    d. box-circle

56. Untuk membuat bayangan menggunakan utilitas ?

    **a. shadow-lg**

    b. bg-shadow-lg

    c. lg-shadow flex

    d. item-flex shadow

57. Syntax dari box portopolio yang tepat adalah ?

    a. ```<box class="max-w-sm shadow-lg px-4 py-4 bg-pink-500 m-3"></box>```

    b. ```<ratangle class="max-w-sm shadow-lg px-4 py-4 bg-pink-500 m-3"></ratangle>```

    **c. ```<div class="max-w-sm shadow-lg px-4 py-4 bg-pink-500 m-3"></div>```**

    d. ```<square class="max-w-sm shadow-lg px-4 py-4 bg-pink-500 m-3"></square>```

58. max-w-sm digunakan untuk ?

    **a. Untuk mengatur maximal lebar**

    b. Untuk mengatur minimum lebar

    c. Untuk mengatur maximal tinggi

    d. Untuk mengatur minimum tinggi

59. Berapa banyak portopolio box yang dibuat ?

    a. 1

    **b. 3**

    c. 2

    d. 4

60. bg-white berguna untuk ?

    a. untuk mengatur warna text 

    b. untuk mengatur warna forground.

    c. untuk mengatur jenis warna sorotan.

    **d. untuk mengatur warna background**

### About Me Bagian 3
61. Penggunaan font awesome dengan cara ?

    **a. CDN**

    b. Instal manual

    c. Import dari tailwind package

    d. Semua jawaban benar

62. Syntax penggunakan CDN font awesome yang tepat adalah ?

    a. ```<import href="https://use.fontawesome.com/releases/v5.7.0/css/all.css">```

    **b. ```<link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.7.0/css/all.css">```**

    c. ```<link rel="stylesheet" href="https://use.tailwindcss.com/docs/releases/v5.7.0/css/all.css">```

    d. ```<import rel="stylesheet" href="https://use.tailwindcss.com/docs/releases/v5.7.0/css/all.css">```

63. Syntax icon font awesome yang benar adalah ?

    a. ```<font class="fas fa-laptop-code fa-5x text-blue-500 mb-6"></font>```

    b. ```<font-awesome class="fas fa-laptop-code fa-5x text-blue-500 mb-6"></font-awesome>```

    **c. ```<i class="fas fa-laptop-code fa-5x text-blue-500 mb-6"></i>```**

    d. Semua jawaban benar

64. Membuat garis pada list keahlian menggunakan ?

    a. br

    **b. hr**

    c. pr

    d. zr

65. Untuk membuat tombol menggunakan tag ?

    a. a href

    b. link

    **c. button**

    d. badge

66. Button di wrap atau di bungkus dengan ?

    a. item

    b. class

    c. section

    **d. div**

67. Syntax Membuat button yang tepat adalah ?


    a.  ```<a href class="bg-blue-500 hover:bg-blue-700 text-white font-bold px-4 py-2 shadow-md rounded-tl-lg rounded-br-lg">Lihat Portofolio </a href>```

    b. ```<link class="bg-blue-500 hover:bg-blue-700 text-white font-bold px-4 py-2 shadow-md rounded-tl-lg rounded-br-lg">Lihat Portofolio </link>```

    **c. ```<button class="bg-blue-500 hover:bg-blue-700 text-white font-bold px-4 py-2 shadow-md rounded-tl-lg rounded-br-lg">Lihat Portofolio </button>```**

    d. ```<badge class="bg-blue-500 hover:bg-blue-700 text-white font-bold px-4 py-2 shadow-md rounded-tl-lg rounded-br-lg">Lihat Portofolio </badge>```

68. Warna yang digunakan dalam hover button keahlian adalah ?

    **a. bg-blue-700**

    b. bg-pink-700

    c. bg-white-700

    d. bg-gray-700

69. Membuat sudut tumpul ujung tertentu pada button menggunakan ?

    a. Menggunakan custom button pada css

    **b. Menggunakan utilitas rounded dengan tambahan utilitas tertentu**

    c. Menggunakan utilitas circle dengan tambahan utilitas tertentu

    d. Semua jawaban benar

70. Syntax sudut tumpul ujung tertentu pada button adalah ?

    a. circle-br-lg

    b. square-tl-lg

    c. button-tl-rounded

    **d. rounded-tl-lg**

### Finishing About Me

71. Untuk cek tampilan pada breakpoint atau layar berbeda kita dapat menggunakan ?

    **a. developer tools pada browser**

    b. aplikasi pihak ketiga

    c. postman

    d. semua jawaban beanr

72. Untuk membuat layar responsive menggunakan meta tag ?

    a. author

    **b. viewport**

    c. keyword

    d. description

73. Meta tag yang digunakan di website portopolio kecuali ?

    **a. JSON**

    b. description

    c. keyword

    d. author

74. Content dari meta tag viewport yang tepat adalah ?

    a. content="codepolitan"

    b. content="Web portofolio tailwind"

    **c. content="width=device-width,initial-scale=1"**

    d. content="tailwindcss, CSS, tailwind"

75. Syntax dari meta tag viewport adalah ?

    a. ```<meta name="JSON" content="width=device-width,initial-scale=1">```

    b. ```<meta name="portview" content="width=device-width,initial-scale=1">```

    c. ```<meta name="view" content="width=device-width,initial-scale=1">```

    **d. ```<meta name="viewport" content="width=device-width,initial-scale=1">```**


## Menu Skill
### Membangun Menu Skill Framework 1
76. Sebelum memulai menambahkan elemen - elemen kita harus mengapus ?

    a. widht

    **b. height**

    c. size

    d. large

77. Pada elemen section kita menambahkan ?

    **a. id**

    b. namespace

    c. index

    d. semua jawaban benar

78. Lebar box **pertama** ketika berada pada breakpoint md dan lebih besar adalah ?

    a. w-full

    b. w-medium

    **c. w-4/12**

    d. w-1/12

79. Lebar box **pertama** ketika berada pada breakpoint lebih kecil md adalah ?

    a. w-1/12

    b. w-4/12

    c. w-medium

    **d. w-full**

80. Image untuk box skill framework di download pada situs ?

    a. font awesome

    **b. unsplash**

    c. google

    d. tailwind

81. Syntax image untuk box skill framework yang tepat adalah ?

    a. ```<image src="img/img4.jpg" class="max-w-full rounded-lg shadow-lg">```

    b. ```<img path="img/img4.jpg" class="max-w-full rounded-lg shadow-lg">```

    c. ```<image path="img/img4.jpg" class="max-w-full rounded-lg shadow-lg">```

    **d. ```<img src="img/img4.jpg" class="max-w-full rounded-lg shadow-lg">```**

### Membangun Menu Skill Framework 2
82. padding right akan berjalan ketika berada ?

    **a. md**

    b. lg

    c. sm

    d. xs

83. List item menggunakan elemen ?

    a. list-item

    b. table

    **c. ul**

    d. il

84. Syntax untuk item keahlian yang tepat adalah ?

    a.
    ```
    <item class="grid grid-cols-2 py-2">
      <p class="text-lg text-gray-600">Codeigniter</p>
      <div class="gradient-skill w-7/8"></div>
    </item>
```

    **b. 
    ```
    <li class="grid grid-cols-2 py-2">
      <p class="text-lg text-gray-600">Codeigniter</p>
      <div class="gradient-skill w-7/8"></div>
   </li>**
```

    c.
     ```
    <ul>
      <p class="text-lg text-gray-600">Codeigniter</p>
      <div class="gradient-skill w-7/8"></div>
    </ul>
```

    d.
     ```
    <ul->li>
      <p class="text-lg text-gray-600">Codeigniter</p>
      <div class="gradient-skill w-7/8"></div>
    </ul->li>
 ```

85. Untuk membuat skala menggunakan elemen ?

    a. button

    b. image

    c. scale

    **d. div**

86. Ukuran skala menggunakan utilitas ?

    a. scale

    **b. width**

    c. size

    d. heigth

87. Syntax class pada div skala yang tepat adalah ?

    a. ```<scale class="gradient-skill w-1/2"></scale>```

    b. ```<div class="gradient-skill w-1/2"></div>```

    **c. ```<div class="gradient-skill w-1/2"></div>```**

    d. ```<div class="gradient-skill w-1/2"></div>```

88. Syntax dari gradient-skill yang tepat adalah ?

    a. background-image: gradient(#FC8181,#FED7D7);

    b. background: linear-gradient(#FC8181,#FED7D7);

    c. image: gradient-linear(#FC8181,#FED7D7);

    **d. background-image: linear-gradient(#FC8181,#FED7D7);**

## Menu Recent Work
### Membangun Menu Recent Work
89. Syntax membuat judul di Menu Recent Work sama dengan ?

    **a. Menu about me dan menu skill framework**

    b. home

    c. footer

    d. Semua jawaban benar

90. grid-cols-4 akan berfungsi pada breakpoint ?

    a. ketika pada breakpoint md dan lebih kecil

    **b. ketika pada breakpoint lg dan lebih besar**

    c. ketika pada breakpoint sm dan lebih kecil

    d. Semua jawaban benar

91. Ketika berada pada breakpoint sm dan lebih besar namun lebih kecil dari lg maka akan menerapkan grid ?

    a. -clos-2

    b.  cols-grid-2

    **c. grid-cols-2**

    d. Semua jawaban benar

92. grid-cols-1 akan berfungsi pada breakpoint ?

    **a. breakpoint lebih kecil dari sm**

    b. ketika pada breakpoint md dan lebih kecil

    c. Semua jawaban benar

    d. ketika pada breakpoint sm dan lebih kecil

93. grid-cols-4 menampilkan kolom sebanyak ?

    a. Sebanyak 1 kolom dalam 4 baris

    b. Sebanyak 4 kolom dalam 4 baris

    c. Semua jawaban benar

    **d. Sebanyak 4 kolom dalam satu baris**

94. Syntax untuk menampilkan 1 kolom dalam satu baris adalah ?

    a. grid-cols-4

    **b.  grid-cols-1**

    c. cols-grid-1

    d. grid-cols-3

95. Syntax untuk menampilkan 4 kolom dalam satu baris adalah

    a. grid-cols-1

    b. grid-cols-3

    **c.  grid-cols-4**

    d. grid-cols-2

### Membangun Menu Recent Work 2
96. Elemen apa yang terdapat pada box recent work

    a. Gambar

    b. Judul

    c. Deskripsi

    **d. Semua jawaban benar**

97. Syntax judul dari proyek **yang tepat** adalah ?

    a. ```<text class="font-normal text-xl mb-2 text-gray-700">Sistem Informasi Keuangan</text>```

    b. ```<p class=>"font-bold text-xl mb-2 text-gray-700">Sistem Informasi Keuangan</p>```

    **c. ```<p class="font-bold text-xl mb-2 text-gray-700">Sistem Informasi Keuangan</p>```**

    d. ```<p class:->"font-bold text-xl mb-2 text-gray-700">Sistem Informasi Keuangan</p>```

98. ```<img src="img/img1.jpg" class="w-full rounded-lg">``` Berfungsi untuk ?

    **a. Menampilkan gambar**

    b. Menampilkan path gambar

    c. Menampilkan judul

    d. Semua jawaban benar

99. Utilitas yang digunakan dalam deskripsi proyek **kecuali** ?

    a. text-gray-700

    b. text-base

    c. text-gray-700 text-base

    **d. text-description"**

100. Utilitas yang digunakan dalam judul proyek **yang tepat** adalah ?

    **a. Semua jawaban benar**

    b. font-bold

    c. text-xl

    d. text-gray-700

101. Syntax box recent work **yanng tepat** adalah ?

    a. ```<div class=>"bg-white px-4 py-4 m-2 shadow-lg rounded">```

    **b. ```<div class="bg-white px-4 py-4 m-2 shadow-lg rounded">```**

    c. ```<div class::"bg-pink px-4 py-4 m-2 ratangle">```

    d. ```<div class="bg-transparant px-4 py-4 m-2 shadow-lg">```

102. Utilitas box recent work **kecuali** ?

    a.rounded

    b. shadow-lg

    c. bg-white

    **d. ratangle-box**

## Contact Me
### Membangun Contact Me
103. Untuk membuat form membutuhkan tag ?

    **a. <form>**

    b. <input>

    c. <form-input>

    d. <register>

104. Elemen apa saja yang terdapat pada form ?

    a. Label

    b. Input

    c. Textarea

    **d. Semua jawaban benar**

105. uppercase pada label berfungsi untuk ?

    a. Membuat tampilan text menjadi camel case

    b. Membuat tampilan text menjadi paragrap

    **c. Membuat tampilan text menjadi kapital**

    d. Semua jawaban benar

106. Elemen input berfungsi untuk ?

    **a. Sebagai kolom isian dari user**

    b. Sebagai bagian ekstetika

    c. Sebagai pelengkap form

    d. Sebagai bagian dari form

107. placeholder berfungsi untuk ?

    a. Sebagai bagian ekstetika

    **b. Membuat tulisan dengan tujuan memberikan penamaan pada form**

    c. Sebagai bagian dari form

    d. Sebagai kolom isian dari user

108. type elemen input pesan menggunakan tag ?

    a. <input>

    b. <file>

    **c. <textarea>**

    d. <date>

109. Mengatur tinggi text area menggunakan ?

    **a. rows**

    b. cols

    c. h1

    d. h2

110. type dari button adalah ?

    a. submit

    b. reset

    c. a href

    **d. button**

## Footer
### Footer End
111. Untuk membuat icon pada footer menggunakan ?

  **a. Font Awesome**

    b. Remixicon

    c. Tabler Icons

    d. Material Design

112. Syntax icon pada footer adalah...

   a. ```<font class="fas fa-laptop-code fa-5x text-blue-500 mb-6"></font>```

    b. ```<font-awesome class="fas fa-laptop-code fa-5x text-blue-500 mb-6"></font-awesome>```

    **c. ```<i class="fa-2x fab fa-facebook"></i>```**

    d. Semua jawaban benar

113. Agar icon media sosial berada di tengah menggunakan utilitas ?

    a. item-center

    b. mx-auto

    c. grid-between

    **d. text-center**  

114. Agar icon media sosial terdapat sorotan menggunkan utilitas ?

    a. spotlight

    **b. hover**

    c. gradient

    d. light

115. Berikut utilitas icon media sosial **Keucali**...

    a. hover:text-indigo-900

    b. text-indigo-700

    **c. rounded**

    d. p-2 

116. Id pada masing -  masing section berfungsi untuk ?

    **a. Untuk menghubungkan link menu dengan masing - masing section**

    b. Untuk menghubungkan tailwind css

    c. Untuk menghubungkan antar section

    d. Semua jawaban benar

117. Isi href disamakan dengan id ?

    a. Pada menu

    **b. Pada section**

    c. Pada footer

    d. Pada header

118. Syntax id yang tepat adalah...

    **a. <section id="skill">**

    b. <section id=>"skill">

    c. <section id->"skill">

    d. <section id("skill")>

119. Syntax link menu yang tepat adalah...

    a. <a href="$skill">Skill Framework</a>

    b. <a href="@skill">Skill Framework</a>

    **c. <a href="#skill">Skill Framework</a>**

    d. <a href=>"@skill">Skill Framework</a>

120. Syntax link menu menggunakan tag...

    a. link

    **b. a href**

    c. component

    d. semua jawaban benar