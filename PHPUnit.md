# soal Pengenalan Automation Testing menggunakan PHPUnit

## Pendahuluan

1. Automation Testing adalah... 
   
   a. Proses pengujian yang dilakukan secara otomatis dengan internet
   
   b. Proses pengujian yang dilakukan secara semi otomatis yang membutuhkan internet
   
   c. Proses pengujian yang dilakukan secara manual
   
   **d. Proses pengujian yang dilakukan secara otomatis**

2. Apa yang di uji dalam Automation Testing... 
   
   **a. Method dan keseluruhan sistem yang dibangun**
   
   b. Data yang ada pada sistem yang dibangun
   
   c. UI/UX pada sistem
   
   d. Database

3. Kenapa pengujian ini disebut Automation Testing...  
   
   a. Karena perlu input manual menggunakan mouse dan keyboard setiap melakukan testing
   
   **b. karena tidak perlu input manual menggunakan mouse dan keyboard setiap melakukan testing**
   
   c. Karena pengetesan dilakukan oleh manusia secara langsung
   
   d. Semua jawaban salah

4. Automation Testing cocok untuk orang yang menggunakan design pattern...
   
   a. Refactoring
   
   **b. Test-Driven Development**
   
   c. Prototype
   
   d. Singleton

5. Tujuan dari Automation Testing adalah...  
   
   a. Mempercepat penemuan bug dalam proses pengujian
   
   b. Meningkatkan produktivitas dalam pembuatan sistem
   
   c. Mempersingkat pengujian karena di lakukan secara otomatis
   
   **d. Semua jawaban benar**

6. test driven development adalah...  
   
   **a. Proses menuliskan test terlebih dahulu baru production code** 
   
   b. Proses menuliskan test dan production code terlebih dahulu
   
   c. Proses menuliskan production code terlebih dahulu baru proses penulisan test
   
   d. Semua jawaban benar

7. Automation Testing pada pembelajaran ini di handle oleh framework... 
   
   a. Lumen
   
   **b. PHPUnit**
   
   c. Cypress.io
   
   d. Katalon

8. Manfaat test driven development adalah... 
   
   a. Mempersingkat waktu pengujian software
   
   b. Mempersempit kemungkinan terjadi bug
   
   c. Mempermudah dalam pengetesan program
   
   **d. Semua Jawaban benar**

## Automation Testing PHPUnit

9. Kita dapat mengakses website PHPUnit dengan memasuki link sebagai berikut… 
   
   a. https://phpunit.com/
   
   **b. https://phpunit.de/**
   
   c. https://phpunit.sch/
   
   d. https://phpunit.co.id/

10. Untuk menginstal framework PHPUnit kita memerlukan... 
   
   **a. Composser**
   
   b. Yarn
   
   c. Xampp
   
   d. CDN

11. Perintah untuk menginstal framework PHPunit adalah... 
   
   a. composer require --dev phpunit/phpunit
   
   b. composer require -dev phpunit/phpunit
   
   **c. composer require --dev phpunit/phpunit**
   
   d. composer require dev phpunit/phpunit -last

12. Setiap perubahan pada file composer.json kita wajib melakukan...

   a. composer dump-reload
   
   **b. composer dump-autoload**
   
   c. composer dump-update
   
   d. composer update

13. Folder app meliki fungsi untuk....
    
   **a. Menyimpan class yang akan diuji**
   
   b. Menyimpan file testing
   
   c. Menyimpan composer
   
   d. Menyimpan package PHPUnit

14. Folder tests meliki fungsi untuk....

   a. Menyimpan file / class yang akan diuji
   
   **b. Menyimpan file / class pengujian**
   
   c. Menyimpan file / class yang diuji dan yang menguji
   
   d. Semua jawaban Benar

15. Secara default framework PHPUnit akan mencari direktori atau folder yang namespace bernama...

   a. test
   
   b. Test
   
   **c. tests**
   
   d. teests

16. Fungsi file phpunit.xml adalah

   **a. Sebagai configurasi dalam menggunakan PHPunit**
   
   b. Sebagai penyimpan data
   
   c. Sebagai penyimpan package PHPunit
   
   d. Sebagai Compposer dalam PHPUnit

17. Fungsi tag ```<directory>tests</directory>``` pada file phpunit.xml

   a. Untuk mementukan directory mana yang menyimpan file yang diuji
   
   **b. Untuk mementukan directory mana yang menyimpan file pengujian**
   
   c. Untuk mementukan directory mana yang menyimpan file package PHPUnit
   
   d. Untuk mementukan directory mana yang menyimpan file Vendor

18. colors pada file phpunit.xml berfunsig untuk...
 
   **a. untuk menampilkan warna pada hasil testing**
   
   b. untuk menampilkan warna pada proses testing
   
   c. untuk menampilkan warna pada input testing
   
   d. untuk menampilkan warna pada code testing

19. stopOnFailure pada file phpunit.xml berfungsi untuk...
    
   a. Untuk menghentikan testing jika terjadi assert yang sesuai
   
   b. Untuk menghentikan testing jika terjadi assert yang tidak sesuai
   
   c. Untuk menghentikan testing jika ada class yang akan diuji
   
   **d. Untuk menghentikan testing jika terjadi error**


20. Struktur penyimpanan file class pengujian pada pembelajaran ini adalah...

   a. tests/case/unit
   
   **b. tests/unit**
   
   c. unit/tests
   
   d. tests/unit/case

21. Exetensi file class pengujian adalah...

   **a. .php**
   
   b. .xml
   
   c. .json
   
   d. .lock

22. Pada file pengujian memiliki extends terhadap package PHPUnit yaitu...

   a. TestSuite
   
   b. Testdata
   
   **c. Testcase**
   
   d. Testsetting

23. Bagaimana cara kita mengimport Package Testcase pada file pengujian ?

   a. use PHPUnit\Framework\TestCase:
   
   **b. use PHPUnit\Framework\TestCase;**
   
   c. using PHPUnit\Framework\TestCase;
   
   d. import PHPUnit\Framework\TestCase;

24. Perintah untuk menjalankan test adalah...

   a. ./vendor/bin/phpunit all
   
   b. ./vendor/bin/phpunit ..
   
   **c. ./vendor/bin/phpunit**
   
   d. ./vendor/bin/phpunit run

25. assert adalah...

   a. Harapan atau ekspetasi dari hasil testing
   
   b. Sebagai pembanding hasil testing
   
   c. Sebagai informasi terhadap hasil testing apakah sesuai atau tidak
   
   **d. Semua jawaban benar**

26. Dalam class pengujian kita wajib membuat...
    
    **a. Method**

    b. class

    c. abstract class

    d. dummy data

27. bagaimana cara nya agar kita mendapat data objek dari model...

    a. Melakukan import package

    **b. Melakukan Instance objek**

    c. Melakukan encapsulation objek

    d. Melakukan pembuatan method objek

28. sysntax meng Instance objek yang benar adalah...

    a. $this->user =  \App\Models\User;

    **b. $this->user = new \App\Models\User;**

    c. $this=>user = new \App\Models\User;

    d. $user = new \App\Models\User;

29. Pada class pengujian kita dapat membuat testscase lebih dari...

   **a. Satu**

   b. Hanya satu

   c. Lebih dari satu dengan memanggil testcase dari file lain

   d. Semua jawaban Benar

30. fungsi assertEquals adalah...

   **a. Membandingkan hasil test dengan ekspetasi sesuai atau tidak**

   b. Membandingkan hasil test dengan hasil test lainnya

   c. Membandingkan hasil test dengan ekspetasi test lainnya

   d. Membandingkan hasil test dengan hasil test pada testcase yang sama