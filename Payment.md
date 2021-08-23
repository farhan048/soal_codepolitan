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

    **b. CodeIgniter**

    c. Laravel

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

    a. Services.php

    b.

    c.

    d.

14.  Isi configurasi integrasi client key dan server key yang tepat adalah..

    a.

    b.

    c.

    d.

15.  Kenapa key isProduction bernilai false...

    a. Jika bernilai True Midtrans mengenakan biaya untuk setiap transaksi

    b. Jika bernilai False Midtrans tidak akan mengenakan biaya untuk setiap transaksi

    c. Untuk memberitahu midtrans bahwa program atau procjet kita masih dalam mengembangan atau development

    **d. Semua Jawaban Benar** 

16.  Pada file .env kita menambahkan key...

    a. client key dan server key

    b.

    c.

    d.

17.  Bagaimana cara mendapatkan Client key dan server key...

    a.

    b.

    c.

    d.
    
