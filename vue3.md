# Membuat Chat Group dengan Vue 3 dan Firebase
## Persiapan Project Vue
### Installasi Vue 3 Dan Setup Project
1. Untuk menginstal Vue membutuhkan ?

   **a. Node.Js**

   b. Node.Kt

   c. Node.Rb

   d. Semua Jawaban Benar

2. Perintah instal Vue adalah ?

   a. npm start -g @vue/cli

   b. npm download -g @vue/cli

   **c. npm install -g @vue/cli**

   d. npm pull -g @vue/cli

3. Database pada kelas ini menggunakan ?

   a. MySQL

   **b. FireBase**

   c. MongoDB

   d. PostGre

4. Pada kelas ini menggunakan vue ?

   **a. 3x**

   b. 2x

   c. 1x

   d. 4x
5. Perintah untuk membuat project Vue adalah ?
  
   a. vue make vuechat

   b. vue instal vuechat

   **c. vue create vuechat**

   d. vue start vuechat

6. Perintah untuk menjalankan Vue cli adalah ?

   a. npm servve start

   b. npm serve

   c. npm start serve

   **d. npm run serve**

### Membuat Login Dan Register Component
7. Chat Group menggunakan kelas UI milik ?
   
   **a. Bootsrap**

   b. Livewire

   c. Tailwind

   d. Next.Js

8. Syntax import component yang tepat adalah ?

   a. imported Login from '/components/auth/Login'

   b. use Login from '../components/auth/Login'

   c. get Login from '../components/auth/Login'

   **d. import Login from '../components/auth/Login'**

9.  Cara menggunakan component yang sudah diimport adalah ?

    a. Membuat div yang class nya nama dari component

    b. Membuat container yang class nya nama dari component

    **c. Membuat tag yang sesuai dengan nama Component**

    d. Membuat tag head yang isinya component

10. Syntax menggunakan compinent pada Template adalah ?

   **a. ```<Login/> ```**

   b. ```@Login ```

   c. ```V-view(Login) ```

   d. ```V-view->Login ```

### Membuat Fungsi Show Component Login Dan Register
11. Dalam Vue.js perintah If menggunakan syntax...
    
    a. @if

    b. if

    **c. v-if**

    d. @endif

12. Sysntax else pada Vue.js adalah...
    
   a. @elseif

   b. else

   **c. v-else**

   d. elseif

13. Untuk memunculkan component login variabel showLogin harus bersifat ?

    **a. True**

    b. false

    c. actived
    
    d. diactived

14. Apa yang akan terjadi jika ariabel showLogin bersifat false ?

    a. Menampilkan Component Login

    **b. Menampilkan Component Register**

    c. Menampilkan Component Login dan Register
    
    d. Semua Jawaban Benar

15. Syntax menggubah variabel showLogin menjadi false adalah ?

    a. @click="showLogin = true"

    b. fun click="showLogin = false"

    **c. @click="showLogin = false"**
    
    d. vue fun click="showLogin = false"

### Mempercantik Component Login Dan Register
16 Bentuk extensi Style Sheets yang digunakan adalah ?
    
    a. .ccs

    **b. .css**

    c. .sass

    d. .scss

17. Untuk menggunakan App.css kita perlu ?
    
    **a. Mengimport file App.css ke main.js**

    b. Membuat syntax css di main.js

    c. Mengimport file main.js ke App.css

    d. Semua Jawaban Benar

18. Untuk memanggil App.css di index.html kita perlu memanggil ?
    
    a. Membuat syntax css di index.html

    **b. Memanggil id APP**

    c. Memanggil file Main.js
    
    d. Semua Jawaban Benar

### Membuat Component Room Dan Chat Box
19.  Fungsi dari property Path adalah...

    a. Menyimpan data - data untuk menampilkan

    b. Menyimpan property VueRouter

    **c. Untuk mengenali url yang diakses user**

    d. Menyimpan file component

20. Fungsi dari property Routes adalah...

    **a. Menyimpan beberapa path dan component**

    b. Menyimpan data - data untuk menampilkan

    c. Menyimpan property VueRouter

    d. Menyimpan file component

21. Kita perlu meregistrasikan component yang sudah diimport di views dengan ?

    a. Menuliskan nama component yang diimport pada export default

    **b. Menuliskan property Component kemudian nama component yang diimport pada export default**

    c. Semua Jawaban Benar
    
    d. Menuliskan Property Component pada export default

### Mempercantik Component Chatbox
22. Untuk membuat scrollable pada chatbox menggunakan ?

    **a. Overflow-y**

    b. Overflow-x

    c. Scrollable-y
    
    d. Scrollable-x

23. Agar sudut chat bubble tidak mengotak menggunakan ?

    a. rounded

    **b. border-radius**

    c. circle
    
    d. round-corner
   
### Mempercantik Component Chat Form Menggunakan Font Awesome
24. Tag style pada component berfungsi untuk ?

    **a. Style yang bekerja pada component itu sendiri**

    b. Style yang digunakan secara global

    c. Style yang digunakan untuk child component
    
    d. Semua Jawaban Benar

25. Kita dapat menggunakan icon dengan menggunakan CDN dari...

    a. Vue.js

    **b. Fontawesome**

    c. CodeIgniter

    d. Laravel

26. Bagaimana cara mengakses CDN dari fontawesome...

    a. Menaruh link CDN ke dalam file app.js

    b. Menaruh link CDN ke dalam file web.php

    **c. Menaruh link CDN ke dalam file HTML**

    d. Menaruh link CDN ke dalam file vue.js

## Mengintegrasikan Firebase dengan Vue
### Membuat Project Firebase Dan File Confignya
27. Firebase memiliki kelebihan yaitu ?

    a. Multi-Platform

    b. Realtime

    c. Gratis
    
    **d. Semua Jawaban benar**

28. Perintah instal library firebase adalah ?

    **a. npm install firebase**

    b. npm download firebase

    c. npm import firebase
    
    d. npm start firebase

29. Library firebase yang digunakan adalah ?

    a. Auth

    b. Firestore

    c. Timestamp 
    
    **d. Semua Jawaban Benar**

### Membuat Fungsi Registrasi Dengan Composable
30. Composable adalah ?

    **a. File Js yang memiliki fungsi dapat digunakan secara berulang**

    b. File Js yang memiliki fungsi dapat digunakan sekali

    c. File Js yang memiliki fungsi dapat digunakan hanya dalam component yang diregister
    
    d. Semua jawaban benar

31. Dalam function register membutuhkan proses ?

    a. load

    b. sync

    **c. async**
    
    d. synchron

### Mengaktifkan Fitur Registrasi Dengan Firebase
32. Sysntax memanggil file Composable register adalah ?

    a. use useRegister from '../../composable/useRegister'

    **b. import useRegister from '../../composable/useRegister'**

    c. get useRegister from '../../composable/useRegister'
    
    d. set useRegister from '../../composable/useRegister'

33. Untuk menghandle inputan user kita bisa menggunakan Directive...
    
    **a. V-model**

    b. X-model
    
    c. Y-model

    d. S-model

34. Penulisan V-model yang benar adalah...
    
    a. ``` <input v-model=="name" >```

    **b. ``` <input v-model="name" >```**

    c. ``` <input v-model=>"name" >```

    d. ``` <input v-model->"name" >```

### Menampilkan Pesan Error Registrasi
35. Untuk menampilkan pesan error menggunakan directive ?

    a. v-error

    b. v-else

    **c. v-if**

    d. ifError

36. Syntax menampilkan error message adalah ?

    a. {{ error.message }}

    **b. {{ error }}**

    c. ```<error />```
    
    d. ()=> error

### Membuat Fungsi Login Dengan Composable
37. Const Login menggunakan 2 parameter yaitu ?

    **a. email dan password**

    b. name email dan password

    c. name dan password
    
    d. username dan password

38. Proses Login menggunakan method firebase yaitu ?

    a. signInWithNameAndPassword

    **b. signInWithEmailAndPassword**

    c. signInWithUsernameAndPassword
    
    d. signInWithNameEmailAndPassword

### Mengaktifkan Fitur Login Dengan Firebase
39. Method Login pada uselogin digunakan pada method ?

    a. ref

    b. const

    **c. handleSubmit**
    
    d. Semua Jawaban Salah

40. Untuk menghubungan data yang ada pada setup dengan template kita harus melakukan ?

    a. Ketik use nama data yang di setup pada template

    b. Return data pada template

    c. Semua Jawaban Benar
    
    **d. Return pada method setup()**

41. Syntax event onClick pada tag form adalah ?

    a. $submit.prevent="handleSubmit"

    **b. @submit.prevent="handleSubmit"**

    c. use submit.prevent="handleSubmit"
    
    d. @submit.prevent=>"handleSubmit"

### Melakukan Redirect Seletah Otentikasi Dengan Emit
42. Untuk menggunakan emit login kita perlu menambahka parameter pada method ?

    **a. Setup()**

    b. export default()

    c. handleSubmit()
    
    d. return {}

43. Parameter yang digunakan pada method Setup adalah ?

    a. context

    **b. props dan context**

    c. props
    
    d. response

44. Syntax emit pada handleLogin adalah ?

    **a. context.emit('login')**

    b. emit.contaxt('login')

    c. emit.login()
    
    d. emit.('login')

45. Syntax Event listener pada component login yang ada di view home adalah ?

    a. login="accessRoom" 

    b. $login="accessRoom" 

    **c. @login="accessRoom"** 
    
    d. #login="accessRoom" 

### Membuat Fungsi Logout Firebase Dengan Composable
46. Proses Logout menggunakan method firebase yaitu ?

    a. destroy()

    **b. signOut()**

    c. logOut()
    
    d. forget()

47. Syntax Logout adalah ?

    **a. await projectAuth.signOut()**

    b. sync projectAuth.signOut()

    c. async projectAuth.signOut()
    
    d. get projectAuth.signOut()

### Mendapatkan Data User Dari Otentikasi Firebase
48. Untuk mendapatkan data user diambil dari data ?

    **a. CurrentUser**

    b. Session

    c. Atuh
    
    d. Auth

49. currentUser berfungsi untuk ?

    a. Menyimpan data user paling awal

    **b. Menyimpan data user paling terkahir**

    c. Menyimpan data user yang berubah
    
    d. Semua Jawaban benar

50. Syntax Menampilkan nama user yang sudah login pada template adalah ?

    a. { user.displayName }

    b. {{ user->displayName }}

    c. {{ user=displayName }}
    
    **d. {{ user.displayName }}**

## Membuat Chatgroup dengan Vue dan Firebase
### Membuat Route Guard Halaman Chat Room
### Membuat Composable Untuk Menyimpan Data Ke Firestore
### Menggunakan Composable Untuk Mengirim Data Chat
### Membuat Composable Getcollection Untuk Mendapatkan Data
### Menampilkan Data Chat Menggunakan Getcollection
### Mengubah Format Timestamp Lebih Mudah Dibaca
### Mencegah Proses Redirect Saat Reload Halaman Chat
### Mencegah Masuk Halaman Otentikasi Setelah Login
















































































## Mengintegrasikan Firebase dengan Vue
## Membuat Chatgroup dengan Vue dan Firebase