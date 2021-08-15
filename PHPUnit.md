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

31. Untuk menjalankan file tertentu kita dapat menggunakan perintah...

   a. filter-testcase

   b. vendor

   **c. filter**

   d. testcase-filter

32. Perintah untuk menajalankan test tertentu adalah...

   a. ./vendor/bin/phpunit --filter=UserTest

   **b. ./vendor/bin/phpunit --filter=UserTest**

   c. ./vendor/bin/phpunit --filter=UserTest

   d. ./vendor/bin/phpunit --filter=UserTest

33. Penulisan nama method mesti diawali dengan prefix...

   **a. test**

   b. nama pengetesan

   c. nama penguji

   d. nama assert

34. Apa yang terjadi jika kita tidak menambahkan prefix test pada nama method...

   **a. PHPUnit tidak membaca testcase**

   b. PHPUnit tetap membaca testcase

   c. PHPUnit tidak bisa berjalan normal

   d. PHPUnit membaca semua testcase

35. Jika kita tidak ingin menambahkan prefix pada nama method kita dapat melakukan...

   a. Memberi prefix pada nama method

   **b. Memberi komentar atau dokumentassi pada testcase**

   c. Memberi tulisan test pada nama method

   d. Semua jawaban benar

36. Penulisan dokumentasi atau komentar yang benar adalah...

   a. ```/** #test */```

   **b. ```/** @test */```**

   c. ```/** test */```

   d. ```/** .test */```

37. Constructor adalah...

   **a. Method khusus yang akan dieksekusi pada saat pembuatan objek**

   b. Method khusus yang akan dieksekusi pada saat penghapusan objek

   c. Method khusus yang akan dieksekusi pada saat pembuatan method

   d. Method khusus yang akan dieksekusi pada saat penghapusan method

38. Untuk menghindari instance objek model pada setiap method kita dapat melakukan satu kali intance objek dengan...

   **a. Constructor**

   b. setdown

   c. Destructor

   d. Construction

39. Constructor pada PHPunit memiliki nama...

   a. Constructor

   b. Instance

   **c. setUp**

   d. setDown

40. Property $user berfungsi untuk...

   a. Menyimpan data assert

   **b. Menyimpan data dari instance objek**

   c. Menyimpan parameter

   d. Menyimpan data pengujian

41. Penulisan sysntax method setUp yang tepat adalah...

   a. protected function setUp(): void
    {
      
        $this->user = new \App\Models\User::
    }

   b. protected function setUp(): String
    {

        $this->user = new \App\Models\User;
    }

   **c. protected function setUp(): void
    {

        $this->user = new \App\Models\User;
    }**

   d. protected function setUp(): int
    {

        $this->user = new \App\Models\User;
    }

42. Method setUp memeliki fungsi untuk...

   a. Mempersingkat source code

   b. Mempersingkat waktu pengujian

   c. Memudahkan pengujian

   **d. Semua jawaban benar**

43. Pada class AdditionalTest memiliki berapa method atau Testcase...

   a. 1

   **b. 2**

   c. 4

   d. 3

44. Pada method add_operands ada berapa parameter pada property setOperands...

   **a. 2**

   b. 4

   c. 1

   d. 3

45. fungsi testcase no_operands_exception adalah...

   a. Untuk mengecek fungsi adition memiliki try catch atau tidak

   **b. Untuk mengecek fungsi adition memiliki Throw Exception atau tidak** 

   c. Untuk mengecek fungsi adition memiliki oeprands atau tidak

   d. Semua Jawaban Benar

46. Sysntax untuk melakukan operasi penjumlahan atau adition adalah...

   a. return sum($this->operands); 

   b. return array($this->operands);

   c. return array-sum($this->operands);

   **d. return array_sum($this->operands);**

47. Fungssi if pada function atau method calculate pada file adition.php adalah...
    
   a. Mengecek apakah nilai yang akan dijumlahkan sama dengan kosong

   b. Mengecek apakah nilai yang akan dijumlahkan tidak kosong

   **c. Mengecek apakah nilai yang akan dijumlahkan kosong atau tidak**

   d. Mengecek apakah operasi dijalankan atau tidak

48. Sysntax untuk melakukan operasi pembagian atau division adalah...
   
   a. $a : $b

   **b. $a / $b**

   c. $a \ $b

   d. $a :: $b

49. Pada division atau pembagian digunakan jenis array...

   a. array_reduce dan array_filter

   **b. array_merge dan array_filter**

   c. array_reduce dan array_merge

   d. array_increase dan array_filter

50. Parameter function calculate pada class division adalah...

   a. $a, $c

   b. $a, $s

   **c. $a, $b**

   d. $b, $a

51. Untuk mengakses class abstract kita dapaat melakukan dengan cara...

   **a. extend**

   b. implements

   c. import

   d. use abstract class

52. class abstract memiliki fungsi untuk...

   **a. Sebagai induk class yang di pakai berulang - ulang**

   b. Sebagai subclass yang di pakai hanya boleh satu kali

   c. Sebagai subclass yang di pakai berulang - ulang

   d. Sebagai induk class yang di pakai hanya boleh satu kali

53. Kenapa function setOperands ditaruh pada class abstract...

   a. Karena function setOperands dipanggil sekali pada class yang sama

   **b. Karena function setOperands dipanggil berulang - ulang pada class yang berbeda**

   c. Karena function setOperands berbentuk abstract

   d. Karena function setOperands sebagai data dummy saja

54. Fungsi dari array_filter adalah...

   a. Sebagai filter apakah operation intance dari Operation Interface

   **b. Sebagai filter apakah operation intance dari Operation Interface**

   c. Sebagai filter apakah operation intance dari Operation Interface

   d. Sebagai filter apakah operation intance dari Operation Interface

55. Fungsi dari assertcount adalah...

   a. Membandingkan hasil test dengan semua function yang ada sesuai atau tidak 

   b. Membandingkan hasil test dengan test lainnya sesuai atau tidak

   **c. Membandingkan hasil test dengan hitungan ekspetasi sesuai atau tidak**

   d. Membandingkan hasil test dengan data sesuai atau tidak

56. Fungsi dari assertIsArray adalah...

   **a. Membandingkan hasil test apakah berbentuk array atau tidak**

   b. Membandingkan hasil test berbentuk JSon atau tidak

   c. Membandingkan hasil test berbentuk object atau tidak

   d. Membandingkan hasil test berbentuk data atau tidak

57. Fungsi dari array_merge adalah...

   a. Menggabungkan 2 array dari dua property yang sama

   **b. Menggabungkan 2 array dari dua property yang berbeda**

   c. Menggabungkan 1 array dari dua property yang berbeda

   d. Menggabungkan index array dari dua property yang berbeda

58. Dalam function multiple_operations property setOperations menggunakan tipe data...

   a. JSON

   b. Object

   **c. Array**

   d. String

59. Nama class pengetesan harus sesuai dengan nama...

   a. Filenya

   b. Testcasenya

   c. Fitur yang akan diuji

   **d. Semua jawaban benar**

60. Sysntax melakukan calculate_multiple_results adalah ....

   **a. $addition = new App\Calculator\Addition;
        $addition->setOperands([5, 10]);

        $division = new App\Calculator\Division;
        $division->setOperands([100, 2]);

        $calculator = new \App\Calculator\Calculator;
        $calculator->setOperations([$addition, $division]);**

   b. $addition = new App\Calculator\Addition;
        $addition->setOperands([5, 10]);

        $division = new App\Calculator\Division;
        $division->setOperands([100, 2]);

        $calculator = new \App\Calculator\Calculator;
        $calculator->setOperations([$division, $division]);

   c. $addition = new App\Calculator\Addition;
        $addition->setOperands([5, 10]);

        $division = new App\Calculator\Division;
        $division->setOperands([100, 2]);

        $calculator = new \App\Calculator\Calculator;
        $calculator->setOperations([$addition, $addition]);

   d. $addition = new App\Calculator\Addition;
        $addition->setOperands([5, 10]);

        $division = new App\Calculator\Division;
        $division->setOperands([100, 2]);

        $calculator = new \App\Calculator\Calculator;
        $calculator->setOperations($addition, $division);

