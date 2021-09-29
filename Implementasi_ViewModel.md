# soal Implementasi ViewModel pada Aplikasi Android
 
## Pendahuluan
### Intro
1. onSavedInstance() digunakan untuk data...
   
    a. Berukuran besar

    **b. Berukuran kecil**

    c. Bawaan android

    d. Semua jawaban benar

2. viewModel digunakan untuk data...

    a. Berukuran Kecil

    b. Bawaan android

    **c. Berukuran besar**

    d. Semua jawaban benar

3. viewModel Bertahan terhadap perubahan...

    **a. LifeCyle**

    b. Activity Rotated

    c. Activity Created

    d. Finish()

4. viewModel Bagian dari arsitektur..

    a. Mode View ViewModel

    b. Model View ViewMode

    c. Model Variant ViewModel

    **d. Model View ViewModel**

5. viewmodel menggunakan konsep pemrosesan data secara...

    a. Perlu refresh setiap ada perubahan

    **b. Realtime**

    c. Manual

    d. Semua jawaban benar

6. viewmodel sebagai penghubung...

    **a. Model dan Activity atau fragment**

    b. Viewmodel dan Activity atau fragment

    c. Model 

    d. Activity atau fragment

### Penjelasan ViewModel dan LiveData

7. viewModel adalah...

    **a. Objek yang menyiapkan dan mengola data dan menampilkannya ke dalam UI**

    b. Objek yang membuat data dan menampilkannya ke dalam UI

    c. Objek yang menyiapkan dan mengola data dan menyimpannya

    d. Objek yang menyiapkan dan mengola data saja tanpa return 

8. viewModel dapat menjaga...

    a. Kerahasian data

    b. Kemampuan data

    **c. Kestabilan data**

    d. Keakuratan data

9.  viewmodel akan bertahan sampai...

    a. Memori lifeCyle yang dicakupnya hilang secara sementara finish()

    **b. Memori lifeCyle yang dicakupnya hilang secara permanen (Finished)** 

    c. Memori lifeCyle yang dicakupnya mencapai tahap activity created

    d. Memori lifeCyle yang dicakupnya mencapai tahap activity rotated

10. Apa itu liveData ?

    a. Adalah penyimpan data yang tertutup

    b. Adalah penyimpan data yang bersifat sementara

    c. Adalah penyimpan data yang terjadi pada LifeCyle activity created

    **d. Adalah penyimpanan data yang observable**

11. liveData berbasis ?

    a. Activity created saja

    b. LifeCyle Event

    **c. Activity rotated saja**

    d. Semua jawaban benar


## Membuat Layout
### Proses Pembuatan Layout (Part 1)
12. Pada project ScoreCounter menggunakan bahasa pemograman...

    a. Java

    b. Dart

    **c. Kotlin**

    d. Pyhton

13. Pada procject ScoreCounter menggunakan sdk minimum berapa...

    **a. APi 21: Android 5.0 (Lollipop)**

    b. APi 26: Android 8.0 (Oreo)

    c. APi 23: Android 6.0 (Marshmallow)

    d. APi 24 Android 7.0 (Nougat)

14. Library yang digunakan pada pembuatan layout adalah...

    **a. Material**

    b. Layout

    c. Shape

    d. Icon

15. procject ScoreCounter menggunakan library material ?

    **a. Google material**

    b. Chrome material

    c. Amazon material
 
    d. Ios material

16. Library material di simpan pada file...

    a. Gradle.properties

    **b. Build.graddle**

    c. gradlew.bat

    d. settings.gradle

17. Syntax untuk membuat TextView ScoreCounter adalah...

    a.  ```<Text
           android:id="@+id/textViewScoreCounter"
           android:layout_width="wrap_content"
           android:layout_height="wrap_content"
           android:text="@string/score_counter"
           android:textSize="32sp"
           android:textColor="@android:color/black"
           app:layout_constraintLeft_toLeftOf="parent"
           app:layout_constraintRight_toRightOf="parent"
           app:layout_constraintTop_toTopOf="parent" />```

    b. ```<TextViewInput
           android:id="@+id/textViewScoreCounter"
           android:layout_width="wrap_content"
           android:layout_height="wrap_content"
           android:textSize="32sp" />```

    c. ```<String
           android:id="@+id/textViewScoreCounter"
           android:layout_width="wrap_content"
           android:layout_height="wrap_content"
           android:text="@string/score_counter"
           android:textSize="32sp"
           android:textColor="@android:color/black"
           app:layout_constraintLeft_toLeftOf="parent"
           app:layout_constraintRight_toRightOf="parent"
           app:layout_constraintTop_toTopOf="parent" />```

    **d. ```<TextView
           android:id="@+id/textViewScoreCounter"
           android:layout_width="wrap_content"
           android:layout_height="wrap_content"
           android:text="@string/score_counter"
           android:textSize="32sp"
           android:textColor="@android:color/black"
           app:layout_constraintLeft_toLeftOf="parent"
           app:layout_constraintRight_toRightOf="parent"
           app:layout_constraintTop_toTopOf="parent" />```**

18. Untuk menempatkan TextView Team A atau Team B di bawah TextView ScoreCounter mengunakan...

    a. app:layout_constraintEnd_toEndOf

    b. app:layout_constraintStart_toStartOf

    **c.  app:layout_constraintTop_toBottomOf**

    d. app:layout_constraintStart_toBottomOf

19. constraintTop_toBottomOf pada TextView Team A atau B menggunakan referesni id...

    a. @id/cardViewScoreTeamB

    b. @id/textViewScoreCounterCard

    c. @id/cardViewScoreTeamA

    **d. @id/textViewScoreCounter**

### Proses Pembuatan Layout (Part 2)
20. Tag untuk membuat cardView adalah..

    **a. <androidx.cardview.widget.CardView>**

    b. <androidx.cardview.CardView>

    c. <androidx.cardview.widget>

    d. <cardview.widget.CardView>

21. app:CardbackgroundColor berfungsi untuk...

    a. Memberikan warna forground pada card

    **b. Memberikan warna background pada card**

    c. Memberikan warna text pada card

    d.  Memberikan warna background dan text pada card

22. app:CardElevation berfungsi untuk...

    **a. Menampilkan bayangan dan efek melayang**

    b. Menampilkan warna background dan text

    c. Menampilkan bayangan pada text

    d. Menampilkan warna pada card

23. Untuk membuat sudut dari card tidak lancip menggunakan...

    a. app:CardElevation

    b. app:margin

    c. androidx.cardview.CardView

    **d. app:cardCornerRadius**

24. Untuk menambahkan warna kita perlu menyimpan hex atau kode warna pada...

    a. styles.xml

    b. AndroidManifest.xml

    **c. colors.xml**

    d. String.xml

25. Synstax pemanggilan nama warna yang sudah kita tambahkan secara manulai adalah...

    **a.  app:cardBackgroundColor="@color/blue"**

    b. app:cardBackgroundColor="@blue"

    c. Color="@color/blue"

    d. app:cardBackgroundColor="@android:color/holo_orange_dark"

### Proses Pembuatan Layout (Part 3)
26. Untuk membuat custom button mengunakan jenis extensi file...

    a. kotlin

    **b. xml**

    c. jpg
 
    d. gradle

27. Tag bg_button_team_a mengunakan...

    **a. ripple**

    b. constraint

    c. Relative

    d. Linear

28. Shape yang digunakan untuk button adalah...

    a. Oval

    b. Triangle

    c. Rounded

    **d. Rectangle**

29. Syntax membuat shape untuk button adalah...

    **a. <shape android:shape="rectangle">**

    b. <shape :shape="rectangle">

    c. <shape android:shape="oval">

    d. <shape android="rectangle">

30. Berikut adalah nama file dari custom button **kecuali**...

    a. bg_button_reset.xml

    b. bg_button_team_a.xml

    **c. bg_card_view.xml**

    d. bg_button_team_b.xml

31. Tujuan peggunaan Riple adalah...

    a. Untuk mengirimkan data

    **b. Untuk mendapatkan feedback ketika button di tekan (Memunculkan efect gelombang)**

    c. Untuk mendapatkan feedback ketika proses selesai (Memunculkan efect gelombang)

    d. Untuk mendapatkan feedback ketika proses berjalan (Memunculkan efect gelombang)

32. Bagaimana cara untuk memanggil custom button team A pada main activity ?

    a. Mengimport atau memanggil file custom button team B

    **b. Mengimport atau memanggil file custom button team A**

    c. Mengcopy semua syntax yang ada di custom button team A

    d. Memanggil id main activity ke dalam custom button team A

33. Syntax Untuk memanggil custom button team A adalah...

    a. android:background="@bg_button_team_a"

    b. android:image="@drawable/bg_button_team_a"

    **c.  android:background="@drawable/bg_button_team_a"**

    d. background="@drawable/bg_button_team_a"

34.  android:textColor="@android:color/white" berfungsi untuk...

    **a. Membuat text menjadi warna putih**

    b. Membuat background menjadi warna putih

    c. Membuat bayangan menjadi warna putih

    d. Membuat texture menjadi warna putih

### Proses Pembuatan Layout (Part 4)
1.  Bagaimana cara untuk memanggil custom button team b pada main activity ?

    a. Mengimport atau memanggil file custom button team A

    b. Memanggil id main activity ke dalam custom button team B

    **c. Mengimport atau memanggil file custom button team B**

    d. Mengcopy semua syntax yang ada di custom button team B


2.    Syntax Untuk memanggil custom button team b adalah...

    a.  android:background="@bg_button_team_b"

    **b. android:background="@drawable/bg_button_team_b"**

    c.  android:forground="@drawable/bg_button_team_b"

    d.  background="@drawable/bg_button_team_b"

3.   android:text="+1" berfungsi untuk...

    a.  Sebagai operator sesuai dengan value (+1)

    b.  Menampilkan data sesuai dengan value (+1)

    c.  Membuat data sesuai dengan value (+1)

    **d. Menampilkan text sesuai dengan value (+1)**

4.   Tag button yang tepat adalah...

    **a. ```<Button/>```**

    b. ```<Button.button/>```

    c. ```<Button.widget/>```

    d. ```<Button.androidx/>```

5.   Bagaimana cara untuk memanggil custom button reset pada main activity ?

    a. Memanggil id main activity ke dalam custom button reset

    b. Mengimport atau memanggil file custom button team B

    c. Mengcopy semua syntax yang ada di custom button reset

    **d. Mengimport atau memanggil file custom button reset**

6.   Syntax Untuk memanggil custom button reset adalah...

    a. background="@drawable/bg_button_reset"

    b. android:"@drawable/bg_button_reset"

    **c. android:background="@drawable/bg_button_reset"**

    d. android:background="/bg_button_reset"

7.   app:layout_constraintStart_toStartOf button reset menggunakan value...

    a. With content

    **b. Parent**

    c. Wrap content

    d. Childern

8.   app:layout_constraintStart_toEndOf button reset menggunakan value...

    **a. Parent**

    b. With content

    c. Wrap content

    d. Childern

9.   constraintTop_toBottomOf pada button reset menggunakan referesni id..
 
    a. @id/cardViewScoreTeamA

    b. @id/textViewScoreCounterCard

    **c. @id/btnMinusScoreTeamA**

    d. @id/cardViewScoreTeamB

10. Tag awal main activity xml adalah... 

    a. ConstraintLayout

    b. ripple

    c. scroll view

    **d. androidx.constraintlayout.widget.constraintlayout**

11. Tag baru main activity xml adalah... 

    a. ConstraintLayout

    b. ripple

    **c. scroll view**

    d. relative

12. fungsi ScrollView adalah...

    **a. Tampilan dapat di scroll jika ukuran layang mengecil**

    b. Tampilan akan mengecil mengikuti ukuran layar

    c. Tampilan dapat di scroll dari kanan ke kiri

    d. Tampilan dapat di scroll dalam posisi optimal

13. Value untuk menghilangkan action bar adalah...

    a. ActionBar.Hide

    b. No.Action.Bar.Hide

    c. HideActionBar

    **d. NoActionBar**

## Implementasi ViewModel
### Proses Implementasi ViewModel dan LiveData (Part 1)

48. Untuk membuat logic CounterScore terdapat pada file....

    **a. MainActivity.kt**

    b. MainActivity.java

    c. MainActivity.vue

    d. MainActivity.swift

49. Modifier yang digunakan dalam variabel global adalah...

    a. Public

    **b. Private**

    c. Protected

    d. Null

50. Insiasi Set On Click Listiner yang tepat adalah...

    **a.  btnPlusScoreTeamA.setOnClickListener(this)**

    b.  btnPlusScoreTeamA.insertOnClickListener()

    c.  btnPlusScoreTeamA.OnClickListener(this)

    d.  btnPlusScoreTeamA.useOnClickListener(this)

51. Syntax function addScoreA() adalah...

    a.  R.id.btnPlusScoreTeamA -> {
                addScoreA()
        }

    **b. private fun addScoreA() {
            scoreA += 1
            tvScoreTeamA.text = ScoreA.toString()
        }**

    c. R.id.btnPlusScoreTeamA -> {
                resetScore()
        }

    d. private fun addScoreA() {
            scoreA -= 1
            tvScoreTeamA.text = ScoreA.toString()
        }

52. sysntax button plus Score team A adalah...

    a.  R.id.btnPlusScoreTeamA -> {
                addScoreB()
        }

    **b. R.id.btnPlusScoreTeamA -> {
                addScoreA()
        }**

    c.  R.id.btnPlusScoreTeamA -> {
                minScoreA()
        }

    d. R.id.btnPlusScoreTeamA -> {
                resetScore()
        }

53. Syntax function resetScore() adalah...


    a. R.id.btnPlusScoreTeamA -> {
                resetScore()
        }

    b. private fun resetScore() {
            scoreA = 1
            scoreB = 1
            tvScoreTeamA.text = ScoreA.toString()
        }

    **c. private fun resetScore() {
            scoreA = 0
            scoreB = 0
            tvScoreTeamA.text = ScoreA.toString()
            tvScoreTeamB.text = ScoreB.toString()
        }**

    d. R.id.btnPlusScoreTeamA -> {
                addScoreA()
        }

### Proses Implementasi ViewModel dan LiveData (Part 2)
54. Library yang digunakan untuk logic project ScoreCounter adalah...

    **a. View Model**

    b. Google material

    c. Calender picker

    d. Semua jawaban benar

55. Syntax Untuk Implementasi library viewModel adalah...

    a. implementation 'com.google.android.material:material:1.2.0-alpha05'

    b. used 'com.google.android.material:material:1.2.0-alpha05'

    c. used 'androidx.lifecycle:lifecycle-extensions:2.2.0'

    **d. implementation 'androidx.lifecycle:lifecycle-extensions:2.2.0'**

56. Variabel val Score A dan B menggunakan tipe data...
   
    **a. int**

    b. string

    c. null

    d. char

57. Ada berapa jenis liveData ?

    a. 1

    **b. 2**

    c. 3

    d. 4

58. LiveData yang digunakan dalam project ScoreCounter adalah....

    **a. MutableLiveData**

    b. LiveData

    c. SharingData

    d. IntegrationData

59. Perbedaan dari MutableLiveData dan LiveData adalah...

    a. MutableLiveData hanya dapat melakukan read saja sedangkan LiveData melakukan insert dan read

    b. MutableLiveData melakukan insert dan read sedangkan LiveData melakukan insert saja

    **c. MutableLiveData dapat melakukan insert dan read saja sedangkan LiveData melakukan read**

    d. MutableLiveData dan LiveData sama - sama melakukan insert dan read

60. Kenapa getScoreA() menggunakan LiveData tidak MutableLiveData ?

    **a. Karena memerlukan read data**

    b. Karena memerlukan insert dan read data

    c. Karena memerlukan insert data

    d. Karena memerlukan insert data

61. Ada Berapa cara untuk menyimpan data ke dalam liveData ?

    a. 4

    b. 3

    **c. 2**

    d. 1

62. Syntax untuk menyimpan data ke dalam liveData secara Main Thread / UI Thread adalah...

    a. scoreA?.postValue(0)

    b. scoreA?.postValue = 0

    c.  scoreA.value = 0

    **d.  scoreA?.value = 0**

63. Syntax untuk menyimpan data ke dalam liveData secara Background Thread adalah...

    a. scoreA?.value = 0

    b. scoreA.value = 0

    **c.  scoreA?.postValue(0)**

    d. scoreA?.postValue = 0

### Proses Implementasi ViewModel dan LiveData (Part 3)

64. Syntax fun addScoreA() dengan liveData adalah...

    **a.  fun addScoreA(){
        val result = getScoreA()?.value?.plus(1)
        scoreA?.value = result
    }**

    b. fun addScoreB(){
        val result = getScoreB()?.value?.plus(1)
        scoreB?.value = result
    }

    c.  fun resetScore(){
        scoreA?.value = 0
        scoreB?.value = 0
        }

    d. fun addScoreA(){
        val result = getScoreA()?.value?.minus(1)
        scoreA?.value = result
    }

65. Syntax fun minScoreA() dengan liveData adalah...

    a. fun minScoreA(){
            val result = getScoreA()?.value?.minus(1)
        scoreA?.value = result
        }

    b. fun minScoreA(){
            val result = getScoreA()?.value?.minus(1)
            if (result!! < 0){
                scoreA?.value = 10
            }
        }

    **c.  fun minScoreA(){
            val result = getScoreA()?.value?.minus(1)
            if (result!! < 0){
                scoreA?.value = 0
            }else{
                scoreA?.value = result
            }
        }**

    d. val result = getScoreA()?.value?.minus(1)
        scoreA?.value = result

66. private lateinit var counterViewModel: ScoreCounterViewModel berfungsi untuk...

    **a. Variabel instance ScoreCounterViewModel**

    b. Variabel data score

    c. Variabel data UI

    d. A dan C benar

67. Syntax init counterViewModel adalah...

    a. ViewModelProvider()
            .get(ScoreCounterViewModel::class.kt)



   **b. ViewModelProvider(this)
            .get(ScoreCounterViewModel::class.java)

        initView()**

    c. ViewModelProvider()
            .get(ScoreCounterViewModel::class.kt)


    d. A dan C benar

68. Untuk mendapatkan data score menggunakan...

    a. initview

    **b. LiveData**

    c. MultitableData

    d. tvScoreTeamA.text = it.toString()

69. Syntax fun initview untuk getScoreA adalah...

    a.  tvScoreTeamA.text = it.toString()

    **b. counterViewModel.getScoreA()?.observe(this, Observer {
            if (it != null){
                tvScoreTeamA.text = it.toString()
            }
        })**

    c. counterViewModel.getScoreB()?.observe(this, Observer {
            if (it != null){
                tvScoreTeamB.text = it.toString()
            }
        })

    d.  tvScoreTeamB.text = it.toString()

### Proses Implementasi ViewModel dan LiveData (Part 4)

70. Syntax button plus score team a yang sudah menggunakan viewmodel dan live data adalah...

    **a.  R.id.btnPlusScoreTeamA -> {
                counterViewModel.addScoreA()
            }**

    b. R.id.btnminScoreTeamA -> {
                addScoreB()
        }

    c. R.id.btnPlusScoreTeamA -> {
                addScoreB()
        }

    d. R.id.btnReset -> {
                counterViewModel.resetScore()
            }

71. Syntax button reset yang sudah menggunakan viewmodel dan live data adalah...

    a. R.id.btnMinusScoreTeamA -> {
                counterViewModel.minScoreA()
            }

    b. R.id.btnminScoreTeamA -> {
                addScoreB()
        }

    c. R.id.btnPlusScoreTeamA -> {
                addScoreB()
        }

    **d. R.id.btnReset -> {
                counterViewModel.resetScore()
            }**

72. Untuk menggunakan function yang ada di ScoreCounterViewModel menggunakan prefix...

    **a. counterViewModel**

    b. counterViewModel.kt

    c. ModelCounterView

    d. counterViewModel.java

73. Kenapa CounterViewModel di instance terlebih dahulu ?

    a. Agar mempermudah aplikasi

    **b. Agar di jalankan terlebih dahulu dan terus menerus**

    c. Agar meringankan beban aplikasi

    d. Semua jawaban benar

74. Syntax button minus score team A yang sudah menggunakan viewmodel dan live data adalah...

    **a. R.id.btnMinusScoreTeamA -> {
                counterViewModel.minScoreA()
            }**

    b. R.id.btnminScoreTeamA -> {
                addScoreB()
        }

    c. R.id.btnPlusScoreTeamA -> {
                addScoreB()
        }

    d. R.id.btnReset -> {
                counterViewModel.resetScore()
            }

75. button plus score team b yang sudah menggunakan viewmodel dan live data adalah...

    a. R.id.btnMinusScoreTeamA -> {
                counterViewModel.minScoreA()
            }

    b. R.id.btnReset -> {
                counterViewModel.resetScore()
            }

    c. R.id.btnPlusScoreTeamA -> {
                resetScore()
        }

    **d.  R.id.btnPlusScoreTeamB -> {
                counterViewModel.addScoreB()
            }**



