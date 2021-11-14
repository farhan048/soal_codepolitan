# Soal Laravel 8x Fundamental

## Pendahuluan
### Laravel dan Cara Installnya
1. Laravel adalah ?

    **a. Framework PHP**

    b. Framework Css

    c. Framework Javascript

    d. PHP Native

2. Siklus pembaruan laravel yang tepat adalah ?

    a. 6 bulan sekali

    **b. 12 bulan sekali**

    c. 8 bulan sekali

    d. Semua jawaban benar
    
3. Software pendukung laravel adalah ? 

    a. Xampp

    b. Composer

    c. Node js

    **d. Semua jawaban benar**
    
4. Instal composer pada windows menggunakan ?

    a. Perintah di terminal

    **b. File execute**

    c. Mengclone library-nya

    d. Mengimport database package composer
    
5. Untuk mengompile preset bootstrap atau tailwind menggunakan ? npm

    **a. Npm**

    b. Node js

    c. Javascript

    d. Semua jawaban benar
    
6. Link dokumentation laravel 8 yang tepat adalah...

    a. https://laravel.com/docs/7.x/

    **b. https://laravel.com/docs/8.x/**

    c. https://laravel.co.id/docs/8.x/

    d. https://laravel.co.id/docs/7.x/
    
7. Perintah composer create project laravel adalah...

    a. composer new-project laravel/laravel example-app

    b. composer make-project laravel/laravel example-app

    **c. composer create-project laravel/laravel example-app**

    d. composer start-project laravel/laravel example-app
    
8. Untuk menginstal laravel membutuhkan ?

    **a. Koneksi Internet**

    b. NPM

    c. Node js

    d. Yarn
    
9.  laravel memiliki perintah khusus yaitu...

    a. Development

    **b. Artisan**

    c. Park

    d. Jarvis
    
10. Perintah menjalankan laravel adalah...

    a. Php park serve

    **b. Php artisan serve**

    c. Php Jarvis start

    d. Php Development serve
    

### Struktur Folder Project Laravel
11. Mendefinisikan logic, transaksi data dan cara sistem bekerja biasanya di simpan pada direktori ?

    a. resources

    **b. app**

    c. config

    d. public
    
12. Direktori config berisi ?

    **a. File php configurasi yang nanti nya digunakan untuk mengatur project**

    b. File env yang mengonfigurasi file - file yang ada di config

    c. File bootstrap

    d. Semua jawaban benar
    
13. Direktori factories berfungsi untuk ?

    a. Menjalakan atau menginsert dummy data ke database

    **b. Membuat struktur data dummy**

    c. Class yang membuat tabel otomatis

    d. Semua jawaban benar
    
14. Direktori migration befungsi untuk ?

    a. Menjalakan atau menginsert dummy data ke database

    b. Membuat struktur data dummy

    **c. Class yang membuat tabel otomatis**

    d. Semua jawaban benar
    
15. Fungsi dari seeder adalah...

    a. Semua jawaban benar

    b. Class yang membuat tabel otomatis

    c. Membuat struktur data dummy

    **d. Untuk menjalakan atau menginsert dummy data ke database**
    
16. Data aset di simpan pada direktori ?

    **a. public**

    b. config

    c. routes

    d. resources
    
17. Data halaman web di simpan pada direktori ?

    a. app

    b. database

    c. routes

    **d. resources**
    
18. Routes berfungsi untuk...

    **a. Menangani rute dari url untuk menampilkan halaman yang di inginkan** 

    b. Menangani database dan logic

    c. Menangani view dan database

    d. Menangani antar controller
    
19. Unit testing berada di direktori ?

    a. vendor

    **b. tests**

    c. config

    d. database
    
20. Konfigurasi secara umum di laravel di simpan pada file ?

    **a. .env**

    b. config

    c. webpack.mix

    d. vendor
    

### Perbedaan Letak Model Di Laravel 8X
30.  Perbedaan secara umum laravel 8 dan sebelumnya terletak pada folder ?

    a. folder http

    **b. Folder app**

    c. database

    d. models
    
31. Peletakan model pada laravel sebelumnya terletak di...

    a. vendor

    b. models

    **c. app**

    d. http

32. Peletakan model pada laravel 8 terletak di...

    **a. models**

    b. app

    c. http

    d. vendor
    
33. Perintah untuk membuat kelas model adalah ?

    **a. Php artisan make:model nama_model**

    b. Php artisan model:make nama_model

    c. Php artisan new:model nama_model

    d. Semua salah
    
34. Pada laravel 8 kita bisa meletakan model pada direktori app dengan cara ?

    a. Menambahkan namespace app\

    b. Menghapus folder apps

    **c. Menghapus folder models**

    d. Menambahkan direktori ketika menginstal model
    
35. Kenapa laravel membuat folder models pada laravel 8 ?

    a. Lebih muda

    b. Mudah diakses

    c. Lebih terstruktur

    **d. Semua jawaban benar**

## Alur Kerja Framework Laravel
### Konsep MVC di Laravel
36. Framework php pada umumnya menggunakan konsep ?

    a. MNC

    b. MEVN

    c. MERN

    **d. MVC**
    
37. MVC singkatan dari ?

    a. View, modal, connection

    **b. Model, view, controller**

    c. Controller

    d. Modal, variable, controller
    
38. Fungsi model yaitu ?

    a. Bagian yang mengatur tampilan ke pengguna, Tampilan view berupa halaman web

    **b. Bagian yang berkomunikasi dengan database**

    c. Bagian yang menjembatani antara model dan view

    d. Untuk menampilkan tampilan
    
39. Fungsi view yaitu ?

    a. Bagian yang menjembatani antara model dan view

    b. Bagian yang berkomunikasi dengan database

    **c. Untuk menampilkan data yang diterima oleh Controller dari Model**

    d. Sebagai jembatan antara model dan view, letak logic program di simpan
    
40. Fungsi controller yaitu ?

    **a. Sebagai jembatan antara model dan view, letak logic program di simpan**

    b. Bagian yang berkomunikasi dengan database

    c. Untuk menampilkan data yang diterima oleh Controller dari Model

    d. Semua jawaban benar

41. Dalam laravel memiliki entitas berbeda dari konsep mvc umum yaitu ?

    a. connection

    **b. Routing / Route**

    c. model

    d. vision

### Membuat URL Baru untuk Menampilkan Halaman Melalui Route
42. Ada berapa jenis file route pada laravel ?

    a. 1

    b. 2

    **c. 4**

    d. 5

43. File route yang paling umum digunakan adalah ?

    a. api.php

    **b. web.php**

    c. json.php

    d. admin.php

44. Syntak dari value url yang tepat adalah...

    **a. Route::get('about', function(){});**

    b. Route::get('~about', function(){});

    c. Route::get('/\about', function(){});

    d. Route->get('about', function(){});

45. Menampilkan halaman menggunakan method ?

    a. redirect

    b. return

    **c. view**

    d. compact

### Menampilkan Data Secara Langsung Melalui Route
46. Menampilkan data secara langsung di route menggunakan tipe data ?

    a. object

    **b. JSON**

    c. array

    d. Semua jawaban benar

47. Syntax return dengan chain method JSON adalah ?

    a. return response(json());

    b. return json();

    c. return->json()->response();

    **d. return response()->json();**

48. Secara default return pada laravel meggunakan response ?

    a. array

    b. Semua jawaban benar

    **c. JSON**

    d. object

49. Syntax return langsung tanpa return respone json adalah...

    a. this->return $dataArray;

    b. $return @dataArray;

    **c. return $dataArray;**

    d. return this->$dataArray;

50. Kelebihan menggunakan chain method JSON adalah ?

    **a. Bisa menambahkan status code**

    b. Memudahkan

    c. Bagus

    d. Semua jawaban salah

### Fungsi Debuging di Laravel untuk Menampilkan Response
51. Untuk melakukan debuging di laravel menggunakan fungsi ?

    a. debug

    **b. dd**

    c. laraveldd

    d. Semua jawaban benar

52. Syntax die and dump adalah ?

    a. dd[($data yang mau di debugging)];

    b. dd[$data yang mau di debugging];

    **c. dd($data yang mau di debugging);**

    d. [dd($data yang mau di debugging)];

53. Kelebihan menggunakan die and dump adalah ?

    a. Format lebih mudah di baca

    b. Format lebih tersturktur

    c. Dapat melihat semua informasi variabel atau data 

    **d. Semua jawaban benar**

54. dalam debuging ddd (triple d) terdapat proses tambahan yaitu ?

    a. die

    **b. debug**

    c. dump

    d. Semua jawaban salah

### Konsep Routing dan Beberapa HTTP Method
55. Ada berapa jenis routing yang dimiliki oleh laravel ?

    **a. 6**

    b. 4

    c. 7

    d. 8

56. Berikut adalah method route yang dimiliki laravel **kecuali** ?

    a. Post

    b. Put/Patch

    c. Get

    **d. Reading**

57. Untuk create disarankan menggunakan method route ?

    a. Put

    b. Patch

    **c. Post**

    d. Get

58. Method get berfungsi untuk ?

    **a. Read**

    b. Store / Insert

    c. Update

    d. Delete

59. Put dan patch memiliki kesamaan yaitu ?

    a. Menginsert data

    **b. Mengupdate / mengubah data**

    c. Membaca data

    d. Mendelete data

60. Untuk mencoba route method menggunakan software ?

    a. JSON Online editor

    **b. Postman**

    c. Ngrokdraw.io

    d. connection.io

### Menggunakan Method GET Dan Parameter Route
61. Memanggil variabel diluar method atau function menggunakan ?

    a. insert($variabel yang ingin digunakan)

    **b. use($variabel yang ingin digunakan)**

    c. intance($variabel yang ingin digunakan)

    d. start($variabel yang ingin digunakan)

62. Url yang tepat untuk mengakses route get melalui postman adalah ?

    a.

    b.

    c.

    d.

63. Bagaimana cara memanggil data berdasarkan key yang di inginkan ?

    a.

    b.

    c.

    d.

64. Syntax route parameter yang tepat adalah ?

    a.

    b.

    c.

    d.

65. Syntax untuk mengakses value dari key $tasklist dari param adalah...

    a.

    b.

    c.

    d.

### Mendapatkan Data Dari Query String Pada Method GET
70. Query String menggunakan helper ?

    **a. Reuqest**

    b. Help

    c. Order

    d. Semua jawaban benar

71. fungsi dari if(request()->search) adalah ?

    a. Mengecek semua data

    **b. Mengecek ada request search atau tidak**

    c. Melakukan perulangan

    d. Semua jawaban benar

72. Jika terdapat request()->search maka yang terjadi adalah ?  

    **a. Menampilkan 1 data sesuai dengan request()->search**

    b. Menampilkan semua data sesuai dengan request()->search

    c. Menampilkan semua data  

    d. Menampilkan 1 data 

73. Jika **tidak terdapat** request()->search maka yang terjadi adalah ?  

    a. Menampilkan 1 data sesuai dengan request()->search

    b. Menampilkan semua data sesuai dengan request()->search

    **c. Menampilkan semua data**  

    d. Menampilkan 1 data 

74. Syntax untuk mengakses value dari key $tasklist dari query string adalah...

    a.

    b.

    c.

    d.

75. Url dari query string di postman yang tepat adalah ?

    a.

    b.

    c.

    d.

### Menggunakan Method POST dan Cara Mendapatkan Datanya
76. Post digunakan untuk mengirim data dari ?

    a. Cloud

    b. Database

    **c. Form**

    d. Semua jawaban benar

78. Pada route method insert (post) dan update (put/ptach) laravel terdapat proteksi ?

    **a. CRFS**

    b. Password

    c. Middleware

    d. Auth

79. Membuka proteksi crfs dengan cara ?

    a.

    b.

    c.

    d.

80. Syntax insert data dari route adalah ?

    a.

    b.

    c.

    d.

### Kegunaan Method PATCH atau PUT dan Mendapatkan Data
81. Method PATCH atau PUT digunakan untuk ?

    a. Membaca data

    b. Menginsert data

    c. Menghapus data

    **d. Mengubah atau mengupdate data**

82. Untuk menggunakan Method PATCH atau PUT kita menambahkan ... URL 

    a. url

    **b. parameter**

    c. data

    d. koneksi

83. Syntax url patch method adalah ?

    a.

    b.

    c.

    d.

84. Syntax update $tasklist yang tepat adalah ?

    a.

    b.

    c.

    d.

85. Cara mengoveride method post untuk menjadi method patch adalah ?

  **a. Menambahkan key _method "patch"**

    b. Menambahkan key _overide "patch"

    c. Menambahkan key _mask "patch"

    d. Menambahkan key _push "patch"


### Menggunakan Method DELETE dan Menghapus Salah Satu Data
86. Untuk menghapus data menggunakan method ?

    **a. Delete**

    b. Get

    c. Post

    d. Put

87. Url method delete hampir sama dengan url method ?

    a. Post

    b. Get

    **c. Put dan Patch**

    d. Semua jawaban benar

88. Syntax delete $tasklist adalah ?

    a. delete($tasklist[$key])

    b. destroy($tasklist[$key])

    c. remove($tasklist[$key])

    **d. unset($tasklist[$key])**

89. Cara mengoveride method post untuk menjadi method delete adalah ?

    **a. Menambahkan key _method "delete"**

    b. Menambahkan key _overide "delete"

    c. Menambahkan key _mask "delete"

    d. Menambahkan key _push "delete"

90. key untuk mengoveride method post adalah ?

    a. _overide

    b. _mask

    c. _push

    **d. _method**

## Controller untuk Meletakkan Logic Aplikasi
### Menampilkan Halaman dengan Controller dan Cara Membuatnya
91. Proses yang dilakukan di dalam controller adalah ?

    **a. Menampilkan hasil ke dalam view dan Melakukan proses query**

    b. 

    c. 

    d.

92. Lokasi controller berada di direktori ?

    a. database

    **b. app**

    c. config

    d. vendor

93. Untuk membuat controller menggunakan ?

    a. Perintah php native

    b. Semua jawaban benar

    **c. Perintah artisan**

    d. Perintah spark

94. Syntax untuk membuat controller adalah ?

    a. php make:controller NamaController

    b. php spark make:controller NamaController

    c. php native make:controller NamaController

    **d. php artisan make:controller NamaController**

95. Syntax routes yang memanggil function pada controller yang tepat adalah ?

    a.

    b.

    c.

    d.

### Memindahkan Method GET dan Mendapatkan Nilai Query String
96. Fungsi dari method index adalah ?

    a. Menampilkan satu data

    **b. Menampilkan semua data yang ada**

    c. Menampilkan data yang dicari saja

    d. Semua jawaban benar

97. Untuk memanggil variabel $tasklist ke dalam method index menggunakan ?

    a. use

    b. $use->

    **c. $this->**

    d. this

98. Syntax import namespace dari TaskController adalah ?

    a.

    b.

    c.

    d.

### Memindahkan Method GET dan Route Parameter di Controller
99.  Pada umumnya untuk menampilkan 1 data yang di inginkan menggunakan method ?

    **a. Show**

    b. Index

    c. Edit

    d. Update

100. Untuk menampilkan 1 data saja method show membutuhkan ?

    a. model

    **b. parameter**

    c. request

    d. semua jawaban benar

101. Syntax untuk mengakses value dari key $tasklist dari param pada method show adalah 

    a.

    b.

    c.

    d.

### Memindahkan Proses Method POST, PATCH dan DELETE ke Controller
102. Post data biasanya di handle oleh method ?

    a. update()

    **b. Store()**

    c. show()

    d. create()

103. Put atau patch data biasanya di handle oleh method ?

    a. destroy()

    b. edit()

    c. index()

    **d. Update()**

104. Delete atau patch data biasanya di handle oleh method ?

    a. edit()

    b. update()

    **c. Destroy()**

    d. index()

### Mengubah Helper Request menggunakan Class untuk Mendapatkan Data
105. Syntax untuk menginject class request ke dalam method adalah ?

    a.

    b.

    c.

    d.

106. Bagaimana cara meletekan class request dan key pada method update ?

    **a. Dengan menambahkan , diantara class request dan key di parameter**

    b. Memanggil class reuqest di dalam fungsi

    c. Semua jawaban benar

    d. Menambahkan key di dalam fungsi

## Menggunakan Database di Laravel
### Konsep Migration Untuk Merancang Tabel di Database
107. Pada umumnya mendesain table di laravel tidak dilakukan secara ?

    a. Otomatis

    **b. Manual**

    c. Import data

    d. Semua jawaban benar

108. Migration mempermudah dalam ?

    a. mengelola database

    b. pembuatan table

    c. pembuatan flied

    **d. semua jawaban benar**

109. Untuk megonfigurasi koneksi database dengan laravel berada di...

    a. config

    b. database

    **c. env**

    d. env.example

110. Migrtion hanya mengenerate ?

    **a. tabel**

    b. database

    c. connection database

    d. semua jawaban benar

111. Walaupun kita menggunakan migration namun tetap saja kita harus membuat .... secara manual

    a. tabel

    b. connection database

    **c. database**

    d. semua jawaban benar

112. Perintah migration adalah

    **a. php artisan migrate**

    b. php artisan start migrate

    c. php spark migrate

    d. php spark sart migrate

113. Table migration berfungsi untuk ?

    a. Penyimpan database

    b. Penghubung model dan database

    **c. Mencatat migrasi database yang telah kita lakukan**

    d. Mencatat data masuk ke database

114. Perintah untuk mendrop table dari artisan adalah ?

    a. php artisan migrate:remove

    **b. php artisan migrate:rollback**

    c. php artisan migrate

    d. php artisan migrate:refresh

### Cara Membuat Tabel dengan Migration
115. Perintah membuat tabel dengan migration adalah ?

    **a. php artisan make:migration create_user_table --create=users**

    b. php artisan make:migration create_user_table --make=users

    c. php artisan make:migration create_user_table --cons=users

    d. php artisan make:migration create_user_table --insert=users

116. Perintah membuat kolom dengan migrtaion jika tablenya sudah di migrate adalah ?

    a. php artisan make:migration insert add_votes_to_users_table --table=users

    b. php artisan make:migration add_votes_to_users_table --insert=users

    **c. php artisan make:migration add_votes_to_users_table --table=users**

    d. php artisan make:migration add_votes_to_users_table --create=users

117. Syntax untuk menambahkan kolom setelah kolom tertentu adalah ?

    a. $table->string('user')->inner('task');

    **b.  $table->string('user')->after('task');**

    c. $table->string('user')->outter('task');

    d. $table->string('user')->side('task');


### Menambah Data dengan Query Builder
118. Syntax import facades DB adalah ?

    **a. use Iluminate\Support\Facades\DB;**

    b.  use Support\Facades\DB;

    c.  use Iluminate\Support\DB;

    d.  import Iluminate\Support\Facades\DB;

119. Syntax store menggunakan query builder adalah ?

    a. DB::table('tasks')->create([]);

    **b. DB::table('tasks')->insert([]);**

    c. DB::table('tasks')->save([]);

    d. DB::table('tasks')->store([]);

120. Yang perlu dipertikan dalam menambahkan data antara form dan controller adalah ?

    **a. Name dari input form**

    b. Id dari input form

    c. Class dari input form

    d. Method dari input form

### Menampikan Data dengan Query Builder
121. Menampilkan seluruh data di handle oleh fungsi ?

    a. show

    b. create

    c. update

    **d. index**

122. Mendapatkan semua data yang ada di tabel task menggunakan query builder method ?

    a. get()

    b. all()

    **c. first()**

    d. pluck()

123. Syntax get mthod pada fungsi index adalah ?

    a. Karena menampilkan 2 data

    b. Karena menampilkan 1 data saja 

    **c. Karena menampilkan semua data**

    d. Semua jawaban benar

124. Untuk menampilkan data dengan search menggunakan query builder method ?

    a. get()

    b. all()

    **c. first()**

    d. pluck()
  
125. Kenapa fungsi index menggunakan query builder method first ?

    a. Karena menampilkan 2 data

    **b. Karena menampilkan 1 data saja** 

    c. Karena menampilkan semua data

    d. Semua jawaban benar

### Mengubah Data dengan Query Builder
126. Langkah pertama untuk update data adalah ?

    a. Pilih semua data

    **b. Pilih data yang akan diupdate**

    c. Gunakna rand untuk memilih data yang diupdate

    d. Semua jawaban benar

127. Untuk mengubah data menggunakan query builder method ?

    **a. update()**

    b. insert()

    c. delete()

    d. upgrade()
 
128. Fungsi class request pada update sama dengan fungsi ?

   a. update()

    b. insert()

    c. desytroy()

    **d. store()**

### Menghapus Data dengan Query Builder
129. Konsep delete, update, dan show memiliki konsep yang sama yaitu ?

    a. Memproses satu data kemudian menampilkan data pada index

    b. Menampilkan semua data

    **c. Memilih salah satu data**

    d. Semua jawaban benar

130. Untuk menghapus data menggunakan query builder method ?

    a. get()

    b. all()

    c. first()

    **d. delete()**

131. Syntax menghapus data menggunakan query builder adalah ?

    a. DB::table('task')->where('id', $id)->destory();

    b. DB::table('task')->where('id', $id)->remove();

    **c. DB::table('task')->where('id', $id)->delete();**

    d. DB::table('task')->where('id', $id)->unset();

## Model dan Konsep Eloquent Laravel
### Konsep Model dan Cara Membuatnya
132. Nama model sebaiknya dibuat sesuai dengan ?

    a. Nama plural / jamak dari tabelnya

    **b. Nama singular / tunggal dari tabelnya**

    c. Nama bebas dari tabelnya

    d. Semua jawaban benar

133. Pada umumnya satu model berkomunikasi dengan 1 ?

    **a. tabel**

    b. database

    c. server

    d. row

134. $fillable pada model berfungsi untuk ?

    a.  Mendifinisikan fill apa saja yang tidak boleh di isi pada tabel

    b.  Mendifinisikan jenis tipe data

    **c. Mendifinisikan fill apa saja yang boleh di isi pada tabel**

    d.  Semua jawaban benar

135. Syntax pendefinisian nama tabel jika berbeda dengan nama model adalah ? 

    a. protected $definiton = 'pekerjaan';

    b. protected $table_connection = 'pekerjaan';

    c. protected $table_comunication = 'pekerjaan';

    **d. protected $table = 'pekerjaan';**

136. Selain menggunakan fillable kita juga dapat menggunakan property .... untuk menginsert ke database ?

    **a. $guarded**

    b. $gate

    c. $fillable

    d. $coloum

### Membuat Banyak Data Secara Otomatis dengan Factory
137. Untuk membuat data dummy memerlukan package atau library ?

    **a. faker**

    b. fake

    c. dummy

    d. imitation

138. Perintah membuat factory adalah ?

    **a. php artisan make:factory TaskFactory --model=Task**

    b. php spark make:factory TaskFactory --model=Task

    c. php make:factory TaskFactory --model=Task

    d. php artisan make:factories TaskFactory --model=Task

139. Dalam penamaan factory sebaiknya ?

    a. Sesuai preferensi masing - masing

    **b. Seusai dengan nama model**

    c. Seusai dengan nama factory

    d. Semua jawaban benar

140. Syntax dummy untuk field task adalah ?

    a. 'task' => $this-imitation->word();

    b. 'task' => $this-fake->word();

    **c. 'task' => $this-faker->word();**

    d. 'task' => $this-dummy->word();

141. Syntax memanggil TaskFactory dalam seeders adalah ?

    a. ..\Models\Task::factory(20)->create();

    b. \App\Task::factory(20)->create();

    c. \App\Models\Task::factories(20)->create();

    **d. \App\Models\Task::factory(20)->create();**

142. Perintah untuk menjalankan seeder adalah ?

    a. php artisan db:seed

    b. php artisan migrate:fresh --seed

    c. php artisan migrate --seed

    **d. Semua jawaban benar**

### Menggunakan Model Untuk Operasi CRUD
143. Yang dilakukan untuk menggunakan model pada operasi CRUD adalah ?

    a. Menambahkan nama model setelah DB::table

    b. Mereturn model

    c. Semua jawaban benar

    **d. Mengganti DB::table dengan nama model**

144. Syntax get semua data menggunakan model adalah ?

    **a. all()**

    b. get()

    c. show()

    d. first()

145. Untuk menginsert data dengan model menggunakan mehtod ?

    a. update()

    **b. create()**

    c. insert()

    d. entering()

146. Untuk mencari id dengan model menggunakan method ?

    a. first()

    b. focus()

    c. search()

    **d. find()**

## Templating dengan Blade
### Membuat Layout Web Dengan Blade
147. Template engine laravel disebut ?

    **a. blade**

    b. slice

    c. directive

    d. semua jawaban benar

148. Perintah @include berfungsi untuk ?

    a. Menggunakan kerangka file html

    b. Menghubungkan antara main content dan section

    **c. Memasukan potongan code dari file yang kita panggil**

    d. Semua jawaban benar

149. Untuk meletakan main content menggunakan syntax blade ?

    a. @section

    b. @extends

    **c. @yield**

    d. @endsection

150. @extends berfungsi untuk ?

    **a. Memanggil kerangka html nya**

    b. Memanggil main content 

    c. Memanggil databse

    d. Semua jawaban benar

151. Untuk menghubungkan yield membutuhkan syntax blade yaitu ?

    a. @endsection

    **b. @section**

    c. @extends

    d. @yield

### Membuat Halaman Create Dan Edit Task
152. Halaman untuk form create di handle oleh method ?

    a. edit()

    b. update()

    **c. create()**

    d. index()

153. Halaman untuk form edit di handle oleh method ?

    **a. edit()**

    b. update()

    c. create()

    d. index()

154. url route dari edit adalah ?

    a. /task

    b. /tasks/edit/{id}

    **c. /tasks/{id}/edit**

    d. Semua jawaban benar

## Operasi CRUD dengan Blade Template Engine
### Menampilkan Data Ke Dalam View Blade
1.   dadada

    a.

    b.

    c.

    d.

2.   dadada

    a.

    b.

    c.

    d.

3.   dadada

    a.

    b.

    c.

    d.

4.   dadada

    a.

    b.

    c.

    d.

5.   dadada

    a.

    b.

    c.

    d.

6.   dadada

    a.

    b.

    c.

    d.

7.   dadada

    a.

    b.

    c.

    d.

8.   dadada

    a.

    b.

    c.

    d.

9.   dadada

    a.

    b.

    c.

    d.

10.  dadada

    a.

    b.

    c.

    d.

11.  dadada

    a.

    b.

    c.

    d.

### Menampilkan Sebagian Data Per Halaman

### Mengaktifkan Form Create Untuk Membuat Data

### Mengaktifkan Form Edit Untuk Mengubah Data

### Membuat Fungsi Hapus Data Dengan Blade

