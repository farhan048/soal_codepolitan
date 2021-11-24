# Soal Optimasi Kinerja Laravel dengan Redis

## Optimasi Laravel dengan Redis
### Persiapan Redis Server
1. Redis adalah ?

    a. Project Close Source Yang mengelola data

    b. Project Subscription Source Yang mengelola data

    **c. Project Open Source Yang mengelola data**

    d. Semua jawaban salah

2. Redis menyimpan data pada ?

    **a. Memori atau Ram**

    b. Prosessor

    c. Hardisk

    d. Semua jawaban salah

3. Untuk menginstal redis pada windows membutuhkan software ?

    a. NodeJs

    b. NPM

    c. Composer

    **d. Laragon**

4. Port default redis adalah ?

    a. 8080

    b. 112111

    **c. 6379**

    d. 3306

5. Redis adalah project bersifat ?

    a. Close Source

    **b. Open Source**

    c. Subscription

    d. Licence code

6. Menginstal laragon pada windows menggunakan ?

   a. Perintah di terminal

    **b. File execute**

    c. Mengclone library-nya

    d. HomeBrew

7. Menginstal redis pada MAC OS menggunakan ?

    a. Perintah di terminal

    **b. HomeBrew**

    c. Mengclone library-nya

    d. File execute

8. Menginstal redis pada linux terutama ubuntu menggunakan ?

    **a. Perintah di terminal**

    b. HomeBrew

    c. Mengclone library-nya

    d. File execute

### Mengenal Beberapa Tipe Data Di Redis
9. Perintah menjalankan cli adalah ?

    a. redis-cli-start

    **b. redis-cli**

    c. initiate redis-cli

    d. start redis-cli

10. Respon apa yang diberikan redis jika kita melakukan ping ?

    a. HELLO

    b. HAI

    **c. PONG**

    d. PING TOO

11. Untuk menentukan data menggunakan ?

    **a. SET**

    b. GET

    c. INSERT

    d. SHOW

12. Untuk mengambil data menggunakan ?

    a. SHOW

    b. ALL

    c. SET

    **d. GET**

13. Syntax mengambil data adalah ?

    a. GET value key

    b. GET value

    **c. GET key**

    d. GET

14. LPUSH menambahkan data pada posisi ?

    a. Paling kanan atau akhir

    **b. Paling kiri atau awal**

    c. Kedua setelah paling awal

    d. Kedua sebelum paling akhir

15. RPUSH menambahkan data pada posisi ?

    **a. Paling kanan atau akhir**

    b. Pada tengah - tengah index datanya

    c. Paling kiri atau awal

    d. Kedua sebelum paling akhir

16. LPOP menngeluarkan atau data pada posisi ?

    a. Paling kanan atau akhir

    **b. Paling kiri atau awal**

    c. Kedua setelah paling awal

    d. Kedua sebelum paling akhir

17. RPOP menngeluarkan atau data pada posisi ?

    **a. Paling kanan atau akhir**

    b. Pada tengah - tengah index datanya

    c. Paling kiri atau awal

    d. Kedua sebelum paling akhir

### Menyimpan Dan Menampilkan Nilai Redis Di Laravel
18. Perintah instal redis pada laravel adalah ?

    **a. composer require predis/predis**

    b. php artisan install predis/predis

    c. composer install predis/predis

    d. php artisan require predis/predis

19. Agar redis dapat bekerja kita perlu melakukan config pada file ?

    a. Provider

    **b. Database**

    c. App

    d. ENV.

20. pada file config database kita mengubah phpredis menjadi ?

    **a. predis**

    b. redisphp

    c. redis

    d. semua jawaban salah

21. Syntax import namespace redis adalah ?

    a. use REDIS

    b. use Illuminate\Facades\REDIS

    **c. use Illuminate\Support\Facades\REDIS**

    d. Semua jawaban salah

22. Syntax increment view pada article adalah ?

    a. Redis::incrementdata("article.{$id}.views");

    b. Redis::incr->("article.{$id}.views");

    **c. Redis::incr("article.{$id}.views");**

    d. Redis::incr=>("article.{$id}.views");

### Mengenal Tipe Data Sorted Sets
23. Salah satu contoh Sorted Sets yang digunakan adalah ?

    a. YADD

    b. SADD

    c. WADD

    **d. ZADD**

24. Syntax menambahkan key dan member dengan ZADD adalah ?

    **a. ZAAD key member**

    b. ZAAD key member insert

    c. ZAAD key->member

    d. ZAAD key (member)

25. Syntax get key dan member dengan ZADD adalah ?

    a. ZINTERVAL key index start index stop

    **b. ZRANGE key index start index stop**

    c. ZRANGE key member index start index stop

    d. ZINTERVAL key member index start index stop

26. Syntax menampilkan score pada trending_article adalah ?

    a. ZINTERVAL key index start index stop WITHSCORES

    **b. ZRANGE key index start index stop WITHSCORES**

    c. ZRANGE key member index start index stop WITHSCORES

    d. ZINTERVAL key member index start index stop WITHSCORES

### Implementasi Sorted Sets Di Laravel
27. Untuk menggunakan Sorted Sets harus menggunakan prefix atau command ?

    **a. Z**

    b. A

    c. Y

    d. D

28. Syntax increment Sorted Sets pada laravel adalah ?

    a. Redis::zinctby('trending'->$topic,1);

    **b. Redis::zinctby('trending',1, $topic);**

    c. Redis::zinctby(trending,1, $topic);

    d. Redis::zinctby('trending'+1, $topic);

29. Key dari increment zincrby adalah ?

    a. visit

    b. topic

    **c. trending**

    d. semua jawaban benar

30. Syntax menghapus member dari key trending adalah ?

    a. Redis::zremrangebyrank('trending',0-4);

    **b. Redis::zremrangebyrank('trending',0,-4);**

    c. Redis::zremrangebyrank(trending,0,-4);

    d. Redis::zremrangebyrank('trending');

### Menggunakan Tipe Hashes Di Laravel
31. Hashes diasumsikan sebagai ?

    **a. Assosiatif Array**

    b. JSON

    c. Object

    d. Semua jawaban salah

32. Untuk menset multipel hashes menggunakan ?

    a. hminsert

    **b. hmset**

    c. hmget

    d. hmpush

33. Syntax hmset adalah ?

    **a. HMSET key flied value**

    b. HMSET key value flied

    c. HMSET key flied flied

    d. HMSET key value

34. Setiap perintah hashes menggunakan prefix ?

    a. hs

    b. hhs

    **c. h**

    d. hms

35. Untuk mendapatkan seluruh data dari key menggunakan ?

    a. hshow

    b. hget

    c. hindex

    **d. hgetall**

36. Syntax hmset pada laravel adalah ?

    a. Redis::hasesset('user.1.stat', $user.1.stat);

    **b. Redis::hmset('user.1.stat', $user.1.stat);**

    c. Redis::hmset('user.1.stat-> $user.1.stat');

    d. Redis::hmset('user.1.stat');

### Implementasi Cache Laravel Dengan Redis
37. if($value = Redis::get('article.all')) berfungssi untuk ?

    a. Mengecek apakah redis menjalankan query get article.all

    **b. Mengecek apakah redis memiliki key dari article.all**

    c. Semua jawaban salah

    d. Mengecek apakah value ada atau null

38. Untuk menampilkan data kita perlu melakukan ?

    a. json_encode

    b. json_get

    **c. json_decode**

    d. json_show

39. Syntax menyimpan data dalam sistem chache pada redis adalah ?

    a. Redis::set('article.all');

    b. Redis::set('article.all->$article');

    **c. Redis::set('article.all', $article);**

    d. Semua jawaban benar

40. Syntax menyimpan data chache sementara adalah ?

    a. Redis::setex('article.all', $article);

    b. Redis::setex('article.all 60 * 60 $article);

    c. Redis::setex('article.all': 60 * 60: $article);

    **d.  Redis::setex('article.all', 60 * 60, $article);**
