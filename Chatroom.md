# Soal Belajar Membuat Realtime Chatroom dengan Websocket Menggunakan Laravel dan Vue

# Persiapan
## Perkenalan Kelas

1. Dalam Cource ini kita menggunakan Framework...

    a. Vue dan CodeIgniter

    b. CodeIgniter dan laravel

    **c. Laravel dan Vue**

    d. PHP NATIVE

2. Dalam Course ini kita menggunakan fitur laravel yaitu...

    a. Controller

    b. Migration

    c. Auth

    **d. Broadcasting**

3. Untuk mengirim data secara realtime kita menggunakan...

    a. LaravelMailer

    **b. Pusher**

    c. Laravel Auth

    d. Midtrans

4. Pusher berguna untuk...

    a. Service untuk mengirim data secara manual

    b. Service untuk mengirim data dari model ke controller

    **c. Service Untuk mengirim data secara realtime**    

    d. Service untuk mengirim data dari controller ke view

5. chatRoom yang akan dibuat bersifat...

    **a. Realtime**

    b. Statis

    c. Tidak realtime

    d. Manual

## Instalasi Project

6. Perintah untuk menginstal laravel adalah...

    a. laravel create new nama folder/ project 

    b. laravel build new nama folder/ project 

    **c. laravel new nama folder/ project** 

    d. laravel start new nama folder/ project 

7. Sysntax untuk mengenerate auth pada instal laravel adalah...

    **a. --auth**

    b. --authentications -m

    c. --migration

    d. --resource

8. php artisan serve berfungsi untuk...

    **a. Perintah untuk menjalankan aplikasi kita pada localhost**

    b. Perintah untuk menjalankan aplikasi kita pada hosting

    c. Perintah untuk menghapus aplikasi kita pada localhost

    d. Perintah untuk menghapus aplikasi kita pada hosting

9. Sysntax membuat model adalah...

    a. php artisan make:model Chat 

    **b. php artisan make:model Chat -m**

    c. php artisan make:model Chat -r

    d. php artisan make:controller Chat -m

10. fungsi -m pada membuat model untuk...

    a. Membuat controller pada model

    b. Membuat database pada server

    **c. Membuat tabel migration**

    d. Semua jawaban benar

11. nama model pada cource ini adalah...

    a. Chatting user

    **b. Chat dan user**

    c. User dan control

    d. Realtime dan user

12. relasi yang digunakan dalam model user adalah...

    a. belongsToMany

    **b. hasMany**

    c. belongsTo

    d. hasOne

13. sysntax relasi pada model user adalah...

    a. return $this->belongsTO(Chat::class);

    b. return $this->hasMany(User::class);

    **c. return $this->hasMany(Chat::class);**

    d. return $this->hasOne(Chat::class);

14. relasi pada model user di simpan pada method...

    a. User

    **b. Chats**

    c. Data

    d. Semua jawaban benar

 15.  relasi yang digunakan dalam model chat adalah...

    a. belongsToMany

    b. hasMany

    **c. belongsTo**

    d. hasOne

16. sysntax relasi pada model chat adalah...

    **a. return $this->belongsTo(User::class);**

    b. return $this->hasOne(User::class);

    c. return $this->belongsTo(Chat::class);

    d. return $this->hasMany(User::class);

17. relasi pada model chat di simpan pada method...

    a. Data

    b. One

    c. Chat

    **d. user**

18. composer require pusher/pusher-php-server perintah untuk...

    **a. Menginstal pusher**

    b. Menjalankan pusher

    c. Membuat migration

    d. Menguninstal pusher

19. Untuk instal pusher kita harus terhubung ke...

    a. Package laravel

    b. Data pusher

    c. Database

    **d. Internet**

20. Sysntax untuk menginstal laravel echo adalah... 

    a. laravel install --save-dev laravel-echo pusher-js

    **b. npm install --save-dev laravel-echo pusher-js**

    c. npm composer install --save-dev laravel-echo pusher-js

    d. install --save-dev laravel-echo pusher-js

## Membuat Component Chat Room

21. Component chat menggunakan....

    a. React.js

    **b. Vue.js**

    c. Angular

    d. Ember.js

22. Direktori component chat yang tepat adalah...

    a. resources\components\chat

    b. resources\js\chat

    c. js\components\chat

    **d. resources\js\components\chat**

23. Untuk mendaftarkan component kita perlu mengonfigurasi pada file...

    a. css.js

    **b. app.js**

    c. app.php

    d. public folder

24. Syntax mendaftarkan component yang tepat adalah....

    a. Vue.component('chatroom-component', require('./components/ExampleComponent.vue').default);

    b. Vue.component('example-component', require('./components/chatroom-component.vue').default);

    c. Vue.component('chatroom-component', require('./chatroom-component/ExampleComponent.vue').default);

    **d. Vue.component('chatroom-component', require('./components/chat/RoomComponent.vue').default);**

25. cara memanggil component di blade laravel adalah...

    a. use

    **b. Menggunakan tag seperti tag html**

    c. import syntax

    d. Semua jawaban benar

26. Untuk mengabung component vue dan laravel blade kita perlu...

    a. instal

    b. running

    **c. compile**

    d. jalankan

27. untuk mengompile component vue dan laravel blade kita perlu...

    a. laravel broadcast

    **b. laravel mix**

    c. laravel auth

    d. laravel share

28. perintah untuk mengompile atau me run hanya sekali saja adalah...

    a.

    b.

    c. npm run dev

    d.

29. Perintah untuk mengompile aatau me run terus menerus adalah...

    a. npm run watch

    b. 

    c.

    d.

30. Setelah mengompile kita perlu....
    
    a.

    b. merefresh browser kita

    c.

    d.

31. file apakah yang di mix oleh laravel mix...

    a. app.js

    b. app.css

    c. app.js dan app.css

    **d. Semua jawaban Benar**

## Implementasi Pusher di Laravel

32. Untuk menggunakan pusher kita mesti membuat....

    a. Menghubungkan pusher ke project kita

    **b. Membuat akun pusher**

    c. Menghubungkan project kita ke pusher

    d. Membuat akun laravel

33. Bagaimana cara membuat channel apps yang baru...

    **a. Klik button create new app, isi form kemudian klik button create my app**

    b. Klik button create new app, klik button create my app kemudian isi form 

    c. Isi form, klik button create new app kemudian klik button create my app

    d. Klik button create my app,  isi form kemudian klik button create new app

34. Cluster atau server mana yang digunakan pada setingan pusher...

    a. Indonesia

    b. USA

    c. Eropa

    **d. Singapore**

35. Credentials apa yang ditambahkan pada file .env...

    a. PUSHER_APP_ID, PUSHER_LARAVEL_APP_KEY, PUSHER_APP_SECRET

    b. PUSHER_APP_ID, PUSHER_APP_KEY, PUSHER_APP_CLUSTER

    **c. PUSHER_APP_ID, PUSHER_APP_KEY, PUSHER_APP_SECRET**

    d. PUSHER_LARAVEL_ID, PUSHER_SERVER_KEY, PUSHER_APP_SECRET

36. Selain menambahkan credentials, kita juga mengonfigurasi BROADCAST_DRIVERS menjadi...

    **a. Pusher**

    b. React.js

    c. Angular

    d. Laragon

37. Untuk mengaktifkan laravel echo kita perlu mengonfigurasi pada file...

    a. App.css

    b. App.js

    **c. Bootstrap.js**

    d. mix

38. Bagaimana cara mengaktifkan service provider Broadcast pada laravel...

    a. Mengetikan perintah activated pada terminal

    b. Mengetikan sysntax broadcast yang ada di dokumentasi laravel

    c. Membuat sysntax sendiri unuk melakukan broadcast

    **d. Membuka komentar yang ada pada syntax service provider Broadcast**

39. Perintah untuk membuat event adalah...

    a. php artisan laravel make:event ChatSent

    b. php laravel make:event ChatSent

    **c. php artisan make:event ChatSent**

    d. artisan make:event ChatSent

40. event class chatsent mengimplementasikan...

    a. ShouldQueue

    b. ShouldDelay

    c. ShouldEvent

    **d. shouldBroadcast**

41. Variabel public $message berfungsi untuk...

    **a. Menyimpan data pesan yang dikirim dari user**

    b. Menjalanakan perintah pengiriman pesan

    c. Memanggil pusher

    d. Menjalankan pusher

42. Channel yang digunakan pada method broadcastOn adalah...

    a. PublicChannel

    b. PrivateChannel

    c. MixChannel

    **d. PresenceChannel**

43. Sysntax untuk memanggil event chatsent adalah...

    a. laravel(new ChatSent())

    **b. broadcast(new ChatSent())**

    c. broadcast(ChatSent())

    d. broadcast(used ChatSent())

44. Bagaimana syntax mengimport event chatsent...

    **a. use App\event\ChatSent**

    b. use App\ChatSent

    c. use App\Controller\ChatSent

    d. use App\model\ChatSent

45. Sysntax untuk get data dari pusher dan menampilkan di console log adalah...

    **a. Echo.Join('chat')
        .Listen(ChatSent, (e) => {
            console.log (e)
        });**

    b. Echo.Join('chat')
        .Listen(ChatSent, (e) => {
            debug.log (e)
        });

    c. Echo.Join('chat')
        .Hear(ChatSent, (e) => {
            console.log (e)
        });

    d. Echo.Join('data')
        .Listen(ChatSent, (e) => {
            console.log (e)
        });

46. Sysntax route channels yang tepat adalah...

    **a. Broadcast::channels('chat', function ($user) { return $user;})**

    b. Broadcast::get('chat', function ($user) { return $user;})

    c. Broadcast::channels('chat', function ($chat) { return $chat;})

    d. Broadcast::get('chat', function ($chat) { return $chat;})

## Menyimpan Data Message

47. Parameter method sendMessage adalah...

    a. $messages

    **b. $request**

    c. $Data

    d. $message

48. Sysntax request message dari view atau form adalah...

    **a. $message = $request->user()->chats()->create(['message' => $request->message]);**

    b. $message = $request->user()->chats()->insert(['message' => $request->message]);

    c. $message = $request->user()->chats()->create(['message' => message]);

    d. $request->user()->chats()->create(['message' => $request->message]);

49. Untuk menerima broadcast dari user lainnya kita menggunakan...

    a. toSharing();

    **b. toOthers();**

    c. toSend();

    d. toReSend();

50. Fungsi variabel Messages pada file RoomComponent adalah...

    a. Menyimpan data user pada room chat

    b. Menyimpan data user yang terdaftar

    **c. Menyimpan data message pada room chat**

    d. Semua jawaban benar

51. Session user di simpan pada...

    a. method

    **b. props**

    c. data

    d. mounted

52. Method sendMessage melakukan proses...

    a. Reload

    b. Pull

    **c. Push**

    d. Get

53. Untuk mengirim pesan dengan menekan enter kita membutuhkan...

    a. keydown.enter

    b. keyup.enter

    **c. @keyup.enter**

    d. @keydown.enter

54. Sysntax untuk mengirim pesan dengan menekan enter adalah...

    a. keyup.enter="sendMessage()"

    b. $keyup.enter="sendMessage()"

    **c. @keyup.enter="sendMessage()"**

    d. @keyup.enter="enter"

55. Setelah data disimpan pada array Message kita melakukan request dengan..

    **a. axios**

    b. vuex

    c. laravel mix

    d. laravel broadcast

## Menampilkan Data Chat

56. Syntax menampilkan message di simpan pada method...

    **a. fecthMessage();**

    b. unpackMessage();

    c. openMessage();

    d. detailMessage();

57. syntax untuk menampilkan message adalah...

    a. this.user = result.data

    **b. this.messages = result.data**

    c. this.messages = message

    d. this.messages = chat->user

58. Route method yang digunakan untuk menampilkan message adalah...

    a. Pull

    **b. Get**

    c. Push

    d. Insert

59. {{chat.user.name}} adalah syntax untuk....

    **a. Menampilkan nama user yang mengirim message**

    b. Menampilkan nama user yang menerima message

    c. Menampilkan semua data yang menerima message

    d. Semua jawaban benar

60. {{chat.message}} adalah syntax untuk....

    a. Menampilkan data user

    b. Menampilkan status online user

    c. Menampilkan nama user

    **d. Menampilkan data message user**

## Menampilkan Chat antar User Realtime

61. Untuk memunculkan message secara realtime kita perlu method...

    a. pull();

    **b. push();**

    c. pop();

    d. unshift();

62. sysntax menampilkan chat secara realtime di tambahkan pada...

    a. props

    **b. mounted**

    c. method

    d. update

63. respon e.message berisikan...

    a. Data register user

    b. Data message dan pusher

    **c. Data message dan object User**

    d. Semua jawaban benar

64. Fungsi dari overflow : auto adalah...

    **a. Agar chat-box bisa di scrollable**

    b. Agar chat-box bisa di minimize

    c. Agar chat-box bisa di maximize

    d. Agar chat-box bisa bersifat static

65. Untuk mencegah chat baru tenggelam kita perlu method...

    a. todown();

    **b. scrolldown();**

    c. toupdateMessage();

    d. newMessage();

66. sysntax untuk scrolldown yang tepat adalah...

    **a. container.scroolTop = scrollHeight;**

    b. container.scroolTop = scrollHeight

    c. container.scroolTop::scrollHeight;

    d. container.scroolTop => scrollHeight;


## Menampilkan Data Users Online

67.  Untuk mengecek user yang sedang bergabung atau tidak menggunakan....

    a. Puhsing dan Pulling

    b. Joining dan Entering

    c. Entering dan Leaving

    **d. Joining dan Leaving**

68.  Syntax untuk melakukan pengecekan joining adalah...

    a. users.push(user);

    b. this.users.push(message);

    **c. this.users.push(user);**

    d. this.push(user);

69. Sysntax untuk melakukan pengecekan leaving adalah...

    a. users = .users.filter(u => u.id != user.id)

    **b. this.users = this.users.filter(u => u.id != user.id);**

    c. this.users = this.users.filter(u => u.id == user.id)

    d. this.users = this.users.filter(u => his.users != user.id)

70. {{ user.name }} adalah syntax untuk...

    **a. Menampilkan nama user**

    b. Menampilkan message user

    c. Menampilkan data - data user

    d. Semua jawaban benar

## Menampilkan Status Typing

71. Untuk membuat status typing kita membuat method...

    a. statusTyping()

    b. keyboardStatus()

    **c. typingEvent()**

    d. keyboardEvent()

72. Pada method typingEvent kita membutuhkan attribute...

    a. joining

    **b. wishper**

    c. leaving

    d. entering

73. Sysntax untuk melakukan wishper adalah...

    **a. .whisper('typing', this.user);**

    b. .whisper('typing', this.user)

    c. .whisper('typing', this.chat);

    d. .whisper('typing', this.messages);

74. Method typingEvent akan bekerja dengan bantuan attribute...

    a. keyup

    **b. keydown**

    c. keyEnter

    d. keydown.enter

75. Timeout berfungsi untuk....

    a. Menghilangkan status typing ketika user mengetik

    b. Menampilkan status typing ketika user mengetik

    c. Menampilkan status typing jika user sudah berhenti

    **d. Menghilangkan status typing jika user sudah berhenti**