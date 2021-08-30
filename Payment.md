# Soal Implementasi Payment Gateway Indonesia Menggunakan Laravel

# Pendahuluan

## Perkenalan

1. Tujuan dari Cource ini adalah...
   
    a. Mengimplementasikan Payment Gateway Indonesia menggunakan Framework Laravel

    b. Mempraktikan dasar-dasar mengimplementasikan Payment Gateway Indonesia menggunakan Framework Laravel

    c.  Mengenal langkah-langkah mengimplementasikan Payment Gateway Indonesia menggunakan Framework Laravel

    **d. Semua Jawaban Benar**

2. Payment Gateway apa yang digunakan dalam Cource ini...

    a. Doku

    **b. Midtrans**

    c. Dana

    d. Gopay

3. Dalam Cource ini kita menggunakan Framework...

    a. Vue

    b. CodeIgniter

    **c. Laravel**

    d. PHP NATIVE

4. Dalam Cource ini kita membuat program atau studi kasus...

    a. E-commerce

    b. Aplikasi pembayaran

    **c. Donasi**

    d. Travel

## Perubahan Library dan Source Code Sebelum Mengikuti
5. composer require vertirans/veritrans-php berfungsi untuk...

    a. Menginstal package midtrans

    b. Menginstal componen yang di perlukan

    c. Mendownload dan menginstal modul - modul midtrans

    **d. Semua jawaban benar**

6. Package versi lama midtrans adalah...

    **a. vertirans**

    b. Midtrans

    c. Startrans

    d. Oketrans

7. Package versi terbaru mindtrans adalah...

    a. vertirans

    **b. Midtrans**

    c. Startrans

    d. Oketrans

8. composer require vertirans/veritrans-php diubah menjadi...

    **a. composer require midtrans/midtrans-php**

    b. composer require midtrans/vertirans-php

    c. composer require midtrans/midtrans_package-php

    d. composer require vertirans/midtrans-php

9.  Isi public function __construct() diversi terbaru diubah menjadi...

    a. ```public function __construct()
{
   \Midtrans_Config::$serverKey = config('services.midtrans.serverKey');
   \Midtrans_Config::$isProduction = config('services.midtrans.isProduction');
   \Midtrans_Config::$isSanitized = config('services.midtrans.isSanitized');
   \Midtrans_Config::$is3ds = config('services.midtrans.is3ds');
}```

    **b. ```public function __construct()
{
   \Midtrans\Config::$serverKey = config('services.midtrans.serverKey');
   \Midtrans\Config::$isProduction = config('services.midtrans.isProduction');
   \Midtrans\Config::$isSanitized = config('services.midtrans.isSanitized');
   \Midtrans\Config::$is3ds = config('services.midtrans.is3ds');
}```**

    c. ```public function __construct()
{
   Veritrans_Config::$serverKey = config('services.midtrans.serverKey');
   Veritrans_Config::$isProduction = config('services.midtrans.isProduction');
   Veritrans_Config::$isSanitized = config('services.midtrans.isSanitized');
   Veritrans_Config::$is3ds = config('services.midtrans.is3ds');
}```

    d. ```public function __construct()
{
   \Veritrans_Config::$serverKey = config('services.midtrans.serverKey');
   \Veritrans_Config::$isProduction = config('services.midtrans.isProduction');
   \Veritrans_Config::$isSanitized = config('services.midtrans.isSanitized');
   \Veritrans_Config::$is3ds = config('services.midtrans.is3ds');
}```

10. Sysntax Notification handler pada versi lama adalah...

    **a. $notif = new Veritrans_Notification();**

    b. $notif = new \Veritrans_Notification\Notification();

    c. $notif = new \Midtrans\Midtrans_Notification();

    d. $notif = new \Midtrans\Notification();

## Pengenalan SNAP dan Installasi SDK
11. Link mengakses Dokumentasi SNAP adalah...

    **a. https://docs.midtrans.com/en/snap/overview**

    b. https://docs.midtrans.com/en/midtrans-account/overview

    c. https://docs.midtrans.com/en/after-payment/overview

    d. https://iris-docs.midtrans.com/

12.  Perintah untuk menginstal package midtrans adalah...

    **a. composer require midtrans/midtrans-php**

    b. composer require midtrans/vertirans-php

    c. composer require midtrans/midtrans_package-php

    d. composer require vertirans/midtrans-php

12.  Untuk menginstal packgae midtrans membutuhkan...

    a. Composer

    b. Manual instaler

    c. Internet

    **d. Jawaban A dan c benar**

13.  Untuk mengintegrasikan client key dan server key kita perlu mengonfigurasi file...

    **a. Services.php**

    b. App.php

    c. Broadcasting.php

    d. mail.php

14.  Isi configurasi integrasi client key dan server key yang tepat adalah..

    a. 'midtrans' => [
        'serverKey'     => env('MIDTRANS_SERVERKEY'),
        'isProduction'  => env('MIDTRANS_IS_PRODUCTION', false),
        'isSanitized'   => env('MIDTRANS_IS_SANITIZED', true),
        'is3ds'         => env('MIDTRANS_IS_3DS', true),
    ]

    b. 'midtrans' => [
        'serverKey'     => env('MIDTRANS_SERVERKEY');
        'clientKey'     => env('MIDTRANS_CLIENTKEY');
        'isProduction'  => env('MIDTRANS_IS_PRODUCTION', false);
        'isSanitized'   => env('MIDTRANS_IS_SANITIZED', true);
        'is3ds'         => env('MIDTRANS_IS_3DS', true);
    ]

    **c. 'midtrans' => [
        'serverKey'     => env('MIDTRANS_SERVERKEY'),
        'clientKey'     => env('MIDTRANS_CLIENTKEY'),
        'isProduction'  => env('MIDTRANS_IS_PRODUCTION', false),
        'isSanitized'   => env('MIDTRANS_IS_SANITIZED', true),
        'is3ds'         => env('MIDTRANS_IS_3DS', true),
    ]**

    d. 'midtrans' => [
        'isProduction'  => env('MIDTRANS_IS_PRODUCTION', false),
        'isSanitized'   => env('MIDTRANS_IS_SANITIZED', true),
        'is3ds'         => env('MIDTRANS_IS_3DS', true),
    ]

15.  Kenapa key isProduction bernilai false...

    a. Jika bernilai True Midtrans mengenakan biaya untuk setiap transaksi

    b. Jika bernilai False Midtrans tidak akan mengenakan biaya untuk setiap transaksi

    c. Untuk memberitahu midtrans bahwa program atau procjet kita masih dalam mengembangan atau development

    **d. Semua Jawaban Benar** 

16.  Pada file .env kita menambahkan key...

    **a. client key dan server key**

    b. isProduction dan isSanitized

    c. isSanitized dan server key

    d. client key dan isProduction

17.  Bagaimana cara mendapatkan Client key dan server key...

    a. Masuk ke Dashboard Midtrans (Production) ke bagian pengaturan pilih akses key

    b. Masuk ke Dashboard Midtrans (Sandbox) ke bagian akses key pilih pengaturan

    **c. Masuk ke Dashboard Midtrans (Sandbox) ke bagian pengaturan pilih akses key**

    d. Masuk ke Dashboard Midtrans (Production) ke bagian akses key pilih pengaturan
    
# Membuat Modul Yang Dibutuhkan

## Membuat Model dan Migration Donation
1.    Perintah untuk membuat model sekaligus migrationnya adalah...

    a. php artisan make:model Donation 

    **b. php artisan make:model Donation -m**

    c. php artisan make:model Donation -r

    d. php artisan make:controller Donation -m

2.   Nullable adalah...

    a. Nullable adalah type yang harus memasukan nilai

    b. Semua salah

    **c. Nullable adalah type yang digunakan untuk mewakili kondisi yang tidak mempunyai nilai**

    d. Nullable adalah type yang digunakan untuk mewakili kondisi yang mempunyai nilai

3.   DBMS apakah yang digunakan untuk membangun Cource ini...

    a. SQLite

    b. PostgreSQL

    **c. MySql**

    d. IBM DB2

4.   Di mana letak kita untuk membuat tabel untuk database pada laravel...

    **a. Migration**

    b. Routes

    c. Controller

    d. Middleware

5.   Apakah fungsi Model di Laravel...

    a. Model berguna untuk menampilkan tampilan

    b. Model adalah bagian yang mengatur tampilan ke pengguna, Tampilan view berupa halaman web

    c. Model adalah yang menjembatani antara model dan view

    **d. Model adalah bagian yang berkomunikasi dengan database. Biasanya model berisi fungsi-fungsi yang membantu dalam pengelolaan basis data, seperti memasukan data ke basis data, pembaruan data, dan lain-lain**

6.   Method - Method pada model donation berfungsi untuk...

    **a. Mengupade status respon dari Midtrans**

    b. Menampilkan data

    c. Memfilter data

    d. Semua jawaban benar

7.   Perintah untuk menjalankan migration adalah...

    a. php artisan migration

    **b. php artisan migrate**

    c. php artisan make=migration

    d. php artisan make:migration

## Membuat Controller dan Halaman Donation
1.  Yang berfungsi sebagai jembatan antara model dan view adalah...

    a. Routes

    b. Livewire

    c. Middleware

    **d. Controller**

2.  Perintah untuk membuat controller adalah...

    a. php artisan make: control-logic donationController

    b. artisan make: controller donationController

    **c. php artisan make: controller donationController**

    d. php artisan make: logic-control donationController

3.  Penulisan route untuk halaman donasi...

    a. Route::delete('/donation', 'DonationController@index');

    b. Route::patch('/donation', 'DonationController@index');

    c. Route::put('/donation', 'DonationController@index');

    **d. Route::get('/donation', 'DonationController@index');**

4.  Framework frontend untuk template mengunakan...

    a. react

    b. vue.js

    c. laravel

    **d. bootstrap**

5.  Method Index berfungsi untuk....

    **a. menampilkan semua data yang ada pada model**

    b. menampilkan satu data yang dipilih yang ada pada model

    c. menampilkan semua data yang ada pada database

    d. menampilkan satu data yang dipilih yang ada database

## Membuat Fungsi Store Payment

30. Berikut cara pemanggilan model Donation yang benar adalah...

    **a. use App\Donation;**

    b. use Donation;

    c. App\Donation use;

    d. use App\model\Donation;

31. Method Store berfungsi untuk...

    a. Method untuk melakukan put / update data ke dalam database

    b. Method untuk melakukan delete / destroy data ke dalam database

    c. **Method untuk melakukan insert / input data ke dalam database**

    d. Method untuk melakukan select / get data ke dalam database

32. \DB::transaction berfungsi untuk...

    **a. untuk mengawasi jalannya query pada saat menjalankan suatu fungsi transaksi aplikasi**

    b. untuk mengawasi jalannya query pada saat menjalankan suatu fungsi insert aplikasi

    c. untuk mengawasi jalannya query pada saat menjalankan suatu fungsi delete aplikasi

    d. untuk mengawasi jalannya query pada saat menjalankan suatu fungsi select aplikasi

33. Untuk menginsert data atau mensave data dapat kita lakukan dengan sysntax...

    a. Update

    b. Desytroy

    **c. Create**

    d. Delete

34. floatval memiliki fungsi yaitu...

    a. Untuk dapat mengembalikan nilai string dari variabel

    **b. Untuk dapat mengembalikan nilai float dari variabel**

    c. Untuk dapat mengembalikan nilai int dari variabel

    d. Untuk dapat menghitung nilai float dari variabel

35. Isi Parameter dari Payload diantaranya...

    a. item_details, customer_details

    b.  item_details, oder_details, data_details

    c.  item_details, array_details, json_details

    **d.  item_details, customer_details, transaction_details**

36. Sysntax generate snap token versi Baru adalah...

    a. \Veritrans\Snap::getSnapToken($payload)

    **b. \Midtrans\Snap::getSnapToken($payload)**

    c. \Midtrans_Snap::getSnapToken($payload)

    d. Veritrans_Snap::getSnapToken($payload)


37. Sysntax generate snap token versi lama adalah...

    **a. Veritrans_Snap::getSnapToken($payload)**

    b. \Veritrans\Snap::getSnapToken($payload)

    c. \Midtrans\Snap::getSnapToken($payload)

    d. \Midtrans_Snap::getSnapToken($payload)


## Mengintegrasikan Snap Payment

38. Untuk mengintegrasikan snap kita perlu mengembedded...

    a. vertirans.js

    **b. snap.js**

    c. midtrans.js

    d. pay.js

39. Isi value data-client-key yang tepat adalah...

    **a. {{ config('services.midtrans.clientKey')}}**

    b. {{ config('services.vertirans.clientKey')}}

    c. {{ config('services.midtrans.serverkey')}}

    d. {{ config('services.vertirans.serverkey')}}

40. Selector form yang tepat adalah...

    a. #formdonations

    **b. #donation_form**

    c. #form

    d. #donations

41. Berikut isi parameter $.post ("/donation") **kecuali**...

    a. _Method : "POST"

    b. donor_name

    c. donation_type

    **d. Status**

42. Perintah untuk menampilkan pop up pembayaran (snap) adalah...

    a. snap.button

    **b. snap.pay**

    c. snap.switch

    d. snap.toggle

43. Untuk membantu mengetahui callback kita perlu website...

    **a. Webhooks**

    b. Ngok

    c. laravel

    d. bootstrap

44. Untuk menggunakan website webhook site kita perlu melakukan configurasi di...

    a. pengaturan vertitrans -> payment notification URL

    b. pengaturan webhook -> payment notification URL

    **c. pengaturan midtrans -> payment notification URL**

    d. pengaturan snap pay -> payment notification URL

45. konfigurasi pada services.php kita panggil dan di simpan pada...

    a. tag script pada key data-client-key="{{ config('model/services.midtrans.clientKey')}}"

    **b. tag script pada key data-client-key="{{ config('services.midtrans.clientKey')}}"**

    c. tag script pada key data-client-key="{{ config('services.midtrans.clientKey')}}"

    d. tag script pada key data-client-key="{{ config('services.midtrans.clientKey')}}"

46. Simulator pembayaran dapat dilakukan dengan...

    a. Simulator transactions

    **b. Simulator sandbox midtrans**

    c. Simulator BI

    d. Simulator laravel

## Membuat Midtrans Notification Handler

47. Perintah untuk melakukan migrate ulang adalah...

    a. php artisan migrate:reset()->refresh

    b. php artisan migrate::refresh

    **c. php artisan migrate:refresh**

    d. php artisan migrate

48. Untuk menghandler respon dari Midtrans kita perlu...

    a. method atau fungsi insert

    b. method atau fungsi store

    **c. method atau fungsi notification**

    d. method atau fungsi index

49. $notif = new \Midtrans\Notification(); Adalah syntax untuk...

    a. notifikasi transaksi pembayaran

    b.  notifikasi transaksi pending

    c.  notifikasi transaksi input

    **d.  Semua jawaban benar**

50. Berikut status respon dari Midtrans kecuali...

    a. settlement

    b. pending

    c. deny

    **d. finished**

51. Synstax untuk mencari oderId pada function notification adalah...
    
    **a.  Donation::findOrFail($orderId);**

    b.  Donation()->findOrFail($orderId);

    c.  Donation::orderBy($orderId);

    d.  Donation::($orderId);

52. Untuk mengamankan data transaksi kita perlu menggunakan...

    a. \DB::store

    b. \DB::transfer

    c. \DB::insert

    **d. \DB::transaction**

## Implementasi Handler Menggunakan Ngrok

53. Route notification di simpan pada file...

    a. web.php

    **b. api.php**

    c. channels.php

    d. console.php

54. Penulisan route notification yang tepat adalah...

    a. Route::get('/midtrans/notification', 'DonationController@create');

    b. Route::post('/midtrans/notification', 'DonationController@store');

    **c. Route::post('/midtrans/notification', 'DonationController@notification');**

    d. Route::get('/midtrans/notification', 'DonationController@notification');

55. Route yang di simpan pada file api.php harus ditambahkan prefix...

    a. route

    **b. api**

    c. json

    d. Semua jawaban benar

56. Untuk mengonlinekan project kita, dapat menggunakan...

    a. localhost

    b. midtrans

    c. bootraps

    **d. Ngrok**

57. link website Ngrok yang tepat adalah...
    
    a. https://ngrok.id/

    **b. https://ngrok.com/**

    c. https://ngrok.uk/

    d. https://ngrok.sch/

58. Perintah untuk mengonlinekan project kita dengan Ngrok adalah...

    **a. ngrok http -host-header=rewrite midtrans.test**

    b. ngrok php artisan serve -host -header=rewrite midtrans.test

    c. ngrok ng -host-header=rewrite midtrans.test

    d. http ngrok -host-header=rewrite midtrans.test

59. URL payment notification URL yang tepat adalah...

    a. URL Ngrok/api/vertitrans/notification

    **b. URL Ngrok/api/midtrans/notification**

    c. URL Ngrok/api/notification

    d. URL Ngrok/api/midtrans

## Menampilkan Daftar Donasi

60. Cara mendapatkan Data donation dengan model yang benar adalah...

    a. $donations = Donation:::orderBy('id', 'desc')->paginate(8);

    b. $donations = use\app\Donation::orderBy('id', 'desc')->paginate(8);

    **c. $donations = Donation::orderBy('id', 'desc')->paginate(8);**

    d. Donation->orderBy('id', 'desc')->paginate(8) = $donations;

61. Mengapa kita menggunakan compact pada fungsi index()...

    **a. Berfungsi untuk melakukan passing data dari controller ke view**

    b. Berfungsi untuk memanggil data dari tabel

    c. Untuk menghapus data yang ada di tabel

    d. Untuk menampilkan seluruh data yang terhubung dengan tabel provinsi

62. Fungsi method paginate() adalah...

    a. Menampilkan syntax coding

    **b. Digunakan untuk menampilkan data dalam jumlah banyak, sehingga dapat dipisah / dipilih berapa data yang akan ditampilkan terlebih dahulu sesuai dengan urutan**

    c. Menampilkan satu data

    d. Semua jawaban benar

63. Untuk melakukan binding data dari controller ke view mengunakan...

    **a. compact**

    b. passing

    c. parse

    d. semua jawaban benar

