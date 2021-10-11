# Soal Membuat Infinite Scroll Timeline seperti Instagram di Aplikasi Android

## Intro
1. Pada Course ini kita membuat aplikasi...

    a. Instagram
    
    b. Facebook
    
    c. Netflix
    
    **d. Movie List**

2. Aplikasi Movie List menggunakan teknik...

   a. ViewModel
   
   **b. Infinite Scroll**
   
   c. Rest API
   
   d. Authentication

3. Infinite Scroll adalah...

   a. Memungkinkan pengguna menscroll content dengan batasan
   
   b. Mengungkinkan pengguna hanya melihat data saja tanpa melakukan scroll
   
   **c. Memungkinkan pengguna menscroll content tanpa batas**
   
   d.  A dan C benar

4. Apakah Infinite Scroll memuat data sekaligus ?

   a. Ya
   
   b. Bisa sekaligus dan juga tidak
   
   **c. Tidak**
   
   d. Semua jawaban benar

5. Cara kerja Infinite Scroll dalam memuat data adalah...

   a. Sekaligus
   
   b. Tidak Memuat data
   
   **c. Sebagian - Sebagian**
   
   d.  Memuat data tertentu

6. Ketika kita sudah scroll sampe batas akhir konten yang muncul, yang dilakukan Infinite Scroll adalah...

   a. Berhenti
   
   **b. Memuat content atau halaman berikutnya**
   
   c. Merefresh halaman awal
   
   d.  Mengclose dirinya sendiri

7. Contoh aplikasi yang meggunakan Infinate Scroll adalah...

   a. Facebook
   
   b. Instagram
   
   c. Twitter
   
   **d. Semua jawaban benar**

8. Kelebihan menggunakan Infinate Scroll adalah...

   a. Menghemat memori
   
   b. Menghemat kuota pengguna
   
   c. Mempertahankan performa smartphone
   
   **d. Semua jawaban benar**

9. Apa yang terjadi jika kita tidak menggunakan Infinate Scroll ?

   a. Boros memori
   
   b. Boros kuota
   
   c. Loading lama
   
   **d. Semua jawaban benar** 

10. Materi Pada Course ini adalah...

   a. Perkembangan Infinate Scroll dan Logicnya
   
   **b. Logic Infinate Scroll dan Membuat aplikasi dengan API dan tanpa API**
   
   c. Sejarah Infinate Scroll
   
   d. Semua Jawaban benar

## Proyek Preview
11.  Project aplikasi di simpan pada ?

   a. gitlab 
   
   **b. github**
   
   c. bitbucket
   
   d. forkhub

12. Link github yang tidak menggunakan API adalah...

   **a. https://github.com/rhmn68/codepolitan-android-contact-infinite-scroll**
   
   b. https://github.com/rhmn68/codepolitan-movie-db-infinite-scroll
   
   c. https://github.com/rhmn68/codepolitan-android-contact
   
   d. https://github.com/codepolitan-movie-db-infinite-scroll

13. Nama Repository dari project yang tidak menggunakan API adalah...

   **a. codepolitan-android-contact-infinite-scroll**
   
   b. codepolitan-android
   
   c. codepolitan-android-contact-infinite-scroll-apps
   
   d. A dan C benar 

14. Link github yang menggunakan API adalah...

   a. https://github.com/rhmn68/codepolitan-android-contact-infinite-scroll
   
   b. https://github.com/rhmn68/codepolitan-android-contact
   
   c. https://github.com/codepolitan-android-contact-infinite-scroll
   
   **d.  https://github.com/rhmn68/codepolitan-movie-db-infinite-scroll** 

15. Nama Repository dari project yang menggunakan API adalah...

   a. codepolitan-movie-apps-infinite-scroll
   
   **b. codepolitan-movie-db-infinite-scroll**
   
   c. codepolitan-apps-movie-infinite-scroll
   
   d. codepolitan-movie_apps-infinite-scroll

16. Project Infinate Scroll Movie Apps yang menggunakan API ?

   **a. Moviedb**
   
   b. Netflix
   
   c. Iqiy
   
   d. VIU

## Pengenalan Infinite Scroll
### Pengenalan Infinite Scroll
17. Jika kita memiliki banyak data sebaiknya dimuat secara ?

   a. Sekaligus
   
   b. Tidak Memuat data
   
   **c. Sebagian - Sebagian**
   
   d.  Memuat data tertentu

18. Apa yang terjadi jika kita memuat secara sekaligus ?
    
   a. Boros memori
   
   b. Boros kuota
   
   c. Loading lama
   
   **d. Semua jawaban benar** 

20. Apa yang terjadi jika kita memuat data secara sebagian - sebagian ?

   a. Menghemat memori
   
   b. Menghemat kuota pengguna
   
   c. Mempertahankan performa smartphone
   
   **d. Semua jawaban benar**

21. Ada berapa cara untuk menampilkan data secara sebagian - sebagian ?

   **a. 2**
   
   b. 3
   
   c. 1
   
   d. Semua jawaban benar

### Logic Infinite Scroll RecyclerView
22. Data yang ada akan disimpan di...

   a. Array
   
   **b. ArrayList**
   
   c. Query
   
   d. Database

23. Arraylist berada pada...

   **a. MovieAdapter**
   
   b. Parent ArrayList
   
   c. AddDataMovies()
   
   d. removeDataMovies()

24. Fungsi getItemViewType() adalah...

   a. Menambahkan data movie
   
   b. Menghapus data movie
   
   **c. Mengecek apakah data movie null atau tidak**
   
   d. Menyimpan data movie

25. Apa yang dikembalikan jika datanya tidak null ?

   a. TYPE_TYPING
   
   **b. TYPE_ITEM**
   
   c. TYPE_DATA
   
   d. TYPE_LOADING

26. Apa yang dikembalikan jika datanya null ?

   a. TYPE_ITEM
   
   b. TYPE_DATA
   
   c. TYPE_TYPING
   
   **d. TYPE_LOADING**

27. Untuk mengecek tipe returnnya berada pada ?

   a. removeDataLoading()
   
   b. addDataLoading()
   
   **c.  OnCreateViewHolder()**
   
   d. onScrolled()

28. Jika viewType == TYPE_ITEM maka yang terjadi adalah...

   a. Menampilkan layout movie
   
   **b. Memunculkan ItemViewHolder**
   
   c. Memunculkan ProgressViewHolder
   
   d. Splash screen

29. ItemViewHolder berupa...

   **a. Menampilkan layout movie** 
   
   b. Splash screen
   
   c. Loading
   
   d. ProgressViewHolder

30. Jika viewType != TYPE_ITEM maka yang terjadi adalah...

   a. Memunculkan ItemViewHolder
   
   b. OnCreateViewHolder()
   
   c. Menampilkan layout movie
   
   **d. Memunculkan ProgressViewHolder**

31. ProgressViewHolder Berupa...

   a. Splash screen
   
   b. ItemViewHolder
   
   **c. Loading**
   
   d. Menampilkan layout movie

32. onScrolled() akan mengambil data diantaranya **kecuali** ?

   a. int countItems
   
   **b. boolean loading**
   
   c. int firstVisiblePosition
   
   d. int childCount

33. Dalam pengambilan fetch data kita akan menambahkan ?

   a. onScrolled()
   
   b. removeDataLoading()
   
   **c. addDataLoading()**
   
   d. OnCreateViewHolder()

34. Ketika selesai melakukan fetch data apa yang kita lakukan ?

   **a. removeDataLoading()**
   
   b. addDataLoading()
   
   c. OnCreateViewHolder()
   
   d. onScrolled()

35. Infinite Scroll akan berhenti ketika scroll sudah mencapai ?

   **a. Halaman terakhir**
   
   b. Halaman awal
   
   c. Kembali ke halaman terakhir
   
   d. Kembali ke halaman awal

## Infinite Scroll Tanpa Menggunakan API (Contacts Apps)
### Design Aplikasi Contact Infinite Scroll
36. Dalam Pembuatan Contacts Apps menggunakan IDE ?

   a. VSC
   
   b. Sublim Text
   
   **c. Android Studio**
   
   d. Swift Studio

38. Yang dimaksud dengan layout...

   a. Merupakan suatu tampilan yang hanya dapat mengatur teks

   **b. Merupakan suatu tampilan tata letak di Android untuk mengatur penempatan teks, gambar, ataupun komponen lainnya**

   c. Merupakan suatu tampilan yang hanya dapat mengatur gambar

   d. Semua salah

39. Viewgroup yang digunakan adalah ?

   a. Relative
   
   b. Constraint
   
   **c. Linear**
   
   d. Ripple

40. Textview adalah...

   **a. Elemen yang berfungsi untuk menampilkan output berupa text**

   b. Komponen untuk memberikan informasi kepada pengguna untuk melakukan suatu perintah

   c. Sekelompok tampilan yang menyejajarkan semua child elemen dalam satu arah

   d. komponen untuk menampilkan informasi dalam bentuk grid

41. Untuk membuat item loading mengunakan tag ?
    
   a. TextView
   
   **b. ProgressBar**
   
   c. Button
   
   d. Loading

42. ```
    <ProgressBar
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"/>

      adalah Syntax untuk ?

      **a. Membuat loading item**
   
      b. Membuat splash screen berupa loading
   
      c. Membuat list contact
   
      d. Semua jawaban benar

43. procject Contact Apps menggunakan library material ?

    **a. Google material**

    b. Chrome material

    c. Amazon material
 
    d. Ios material

44. Library material di simpan pada file...

    a. Gradle.properties

    **b. Build.graddle**

    c. gradlew.bat

    d. settings.gradle

45. TextView pada main activity dirubah menjadi ?

      a. ProgressBar
   
      b. TittleView
   
      c. DataView
   
      **d. Recyclerview**

### Pembuatan Contact Adapter
46. Nama dari package baru adalah...

      **a. Adapter**
   
      b. ContactList
   
      c. ViewType
   
      d. ViewHolder

47. Class Contact apdater memiliki extends terhadap ?

      a. RecyclerView.ViewHolder
   
      b. List<String> contacts
   
      c. dataContacts.size();
   
      **d. RecyclerView.Adapter<RecyclerView.ViewHolder>**

48. Class ItemViewHolder memiliki extends terhadap ?

      a. RecyclerView.Adapter<RecyclerView.ViewHolder>
   
      b. dataContacts.size();
   
      c. List<String> contacts
   
      **d. RecyclerView.ViewHolder**

49. Variabel yang digunakan sebagai collector adalah ?

      **a. ArrayList<>**
   
      b. Array
   
      c. Matrixs
   
      d. getter

50. Tipe data dari ArrayList adalah...

      **a. String**
   
      b. int
   
      c. boolean
   
      d. double

51. Nama variabel dari ArrayList yaitu ?

      a. TYPE_ITEM 
   
      **b. dataContacts**
   
      c. TYPE_LOADING 
   
      d. Semua jawaban benar

52. Berikut variabel yang ada di ContactAdapter.java **kecuali** ?

      a. TYPE_ITEM
   
      b. dataContacts
   
      **c. viewType** 
   
      d. TYPE_LOADING

53. Syntax return viewType == TYPE_ITEM adalah ...

      a. return new ProgressViewHolder(LayoutInflater.from(parent.getContext()).inflate(R.layout.item_loading->R.layout.item_loading, parent, false));
   
      b. return new ProgressViewHolder(LayoutInflater.from(parent.getContext()).inflate(R.layout.item_loading, parent, false));
   
      c. return new ProgressViewHolder(LayoutInflater.from(parent.getContext()).inflate(R.layout.item_loading:R.layout.item_loading, parent, false));
   
      **d. return new ItemViewHolder(LayoutInflater.from(parent.getContext()).inflate(R.layout.item_contact, parent, false));**

54. Syntax return viewType != TYPE_ITEM adalah ...

      a. return new ItemViewHolder(LayoutInflater.from(parent.getContext()).inflate(R.layout.item_contact, parent, false));
   
      b. return new ProgressViewHolder(LayoutInflater.from(parent.getContext()).inflate(R.layout.item_loading:R.layout.item_loading, parent, false));
   
      **c. return new ProgressViewHolder(LayoutInflater.from(parent.getContext()).inflate(R.layout.item_loading, parent, false));**
   
      d. return new ProgressViewHolder(LayoutInflater.from(parent.getContext()).inflate(R.layout.item_loading->R.layout.item_loading, parent, false));

55. Variabel apa yang dihitung dalam getItemCount ?

      **a. dataContacts**
   
      b. TYPE_ITEM
   
      c. item_loading
   
      d. TYPE_LOADING

56. Untuk menghitung getItemCount menggunakan ?

      **a. size();**
   
      b. plek();
   
      c. pluck();
   
      d. count();

57. getItemViewType berfungsi untuk ?

      a. Melakukan passing data
   
      b. Untuk get datacontacts
   
      **c. Melakukan pengecekan datacontacts bersifat null atau tidak**
   
      d. Semua jawaban benar

58. Sysntax addDataContact yang tepat adalah ?

      a. if (contacts == null){
            dataContacts.addAll(contacts);
            notifyDataSetChanged();
        }
   
      **b. if (contacts != null){
            dataContacts.addAll(contacts);
            notifyDataSetChanged();
        }**
   
      c. if (contacts != null){
            dataContacts.remove(contacts);
            notifyDataSetChanged();
        }
   
      d. if (contacts != null){
            dataContacts.addAllandRemove(contacts);
            notifyDataSetChanged();
        } 

59. Sysntax addDataLoading yang tepat adalah ?

      **a. dataContacts.add(null);
        notifyDataSetChanged();**
   
      b. dataContacts.remove(dataContacts.size() - 1);
        notifyDataSetChanged();
   
      c. super(itemView);
   
      d. tvName = itemView.findViewById(R.id.tvName);

60. Syntax removeDataLoading yang tepat adalah ?

      a. tvName = itemView.findViewById(R.id.tvName);
   
      b. dataContacts.add(null);
        notifyDataSetChanged();
   
      **c. dataContacts.remove(dataContacts.size() - 1);
        notifyDataSetChanged();**
   
      d. super(itemView);
### Implementasi Infinite RecyclerView
61.  Nilai default variabel isScroll adalah ?
    
      **a. true;**
   
      b. false;
   
      c. netral;
   
      d. Scrolled;

62.  Sysntax instance dari ContactAdapter adalah ?

      a.  private ContactAdapter contactAdapter use new ContactAdapter();
   
      b.  private ContactAdapter contactAdapter initiate new ContactAdapter();
   
      **c.  private ContactAdapter contactAdapter = new ContactAdapter();**
   
      d. A dan B benar

63.  Untuk menghindari penumpukan data sebaiknya kita melakukan ?

      **a. clear();**
   
      b. size();
   
      c. removed();
   
      d. reset();

64.  Sysntax memanggil RecyclerView layout ke MainActivity.java yaitu...

      a. RecyclerView rvContacts = import(R.id.rvContacts);
   
      **b. RecyclerView rvContacts = findViewById(R.id.rvContacts);**
   
      c. RecyclerView rvContacts = used(R.id.rvContacts);
   
      d. RecyclerView rvContacts = (findViewById (R.id.rvContacts));

65.  Syntax kondisi jika data di scroll terdapat pada...

      a. rvContacts.setLayoutManager(layoutManager);
   
      b.  rvContacts.setHasFixedSize(true);
   
      c.  rvContacts.setAdapter(contactAdapter);
   
      **d.  rvContacts.addOnScrollListener**

66.  Siapa yang menangani untuk menambah halaman baru ?

      a. layoutManager
   
      b. setHasFixedSize
   
      **c. handler**
   
      d. super.onScrolled(recyclerView, dx, dy);

67.  Syntax untuk menjalakan halaman baru berada pada method...

      **a. run**
   
      b. start
   
      c. create
   
      d. initiate

68.  Syntax method run yang tepat adalah ?

      a. public void run() {
                            contactAdapter.removeDataLoading();
                            fetchData(datacontacts);
                            isScroll = true;
                        }
                    });
   
      b. public void run() {
                            contactAdapter.addDataLoading();
                            contactAdapter.removeDataLoading();
                            fetchData(countItems);
                            isScroll = false;
                        }
                    }, 2000);
   
      c. public void run() {
                            contactAdapter.removeDataLoading();
                            isScroll = true;
                        }
                    }, 2000);
   
      **d. public void run() {
                            contactAdapter.removeDataLoading();
                            fetchData(countItems);
                            isScroll = true;
                        }
                    }, 2000);**

69.  Jika data memenuhi kondisi berikut  if (isScroll && totalScrollItem >= countItems) maka yang terjadi adalah...

      a. Mematikan fungsi scroll
   
      b. Langsung menambahkan halaman baru
   
      **c. Mematikan fungsi scroll dan Menampilkan loading**
   
      d. Menampilkan loading

### Penjelasan Infinite RecyclerView di Contact Apps
70.  Variabel isScroll berupa...

      a. data
   
      **b. Flag**
   
      c. Variabel
   
      d. Semua jawaban benar

71.  Fungsi variabel dataContacts adalah...

      **a. Menampung fake data**
   
      b. Menampung RecyclerView
   
      c. Menampung Infinite scroll
   
      d. A dan B benar

72.  Isi dari datacontacts adalah...

      **a. dataContacts.add(i + 1 + ". John Doe");**
   
      b. dataContacts.add(data);
   
      c. dataContacts.insert(i + 1 + ". John Doe"); 
   
      d. Semua jawaban salah

73.  Proses penambahan data ditangani oleh method ?

      **a. public void fecthData**
   
      b. public void onCreate
   
      c. public void onRemove
   
      d. public void onScrolled

74.  Fungsi utama infinate scroll berada pada...

      a. public void fecthData
   
      b. public void onCreate
   
      c. public void onRemove
   
      **d. public void onScrolled**

75.  Method onScroll akan bekerja ketika kita melakukan ?

      **a. Melakukan scroll**
   
      b. Melakukan input data
   
      c. Melakukan remove
   
      d. Melakukan dataContacts

76.  Apa yang didapatkan ketika melakukan scroll ?

      a. Jumlah data yang ada pada RecyclerView
   
      b. Jumlah data yang terlihat di layar
   
      c. Index data yang terlihat pertama kali (kalo vertical index data yang berada diatas)
   
      **d. Semua jawaban benar**

77.  int totalScrollItem terdiri atas ?

      **a. currentItems + firstVisiblePosition**
   
      b. countItems + firstVisiblePosition
   
      c. countItems + currentItems
   
      d. firstVisiblePosition

78.  Jika data **tidak** memenuhi kondisi berikut  if (isScroll && totalScrollItem >= countItems) maka yang terjadi adalah...

      a. Tetap dapat di scroll
   
      b. Tidak menambah loading
   
      c. Tidak ada penambahan halaman baru
   
      **d. Semua jawaban benar**

79. Kenapa kita harus memberikan delay ?

      a. Memberi waktu untuk addDataContacts();
   
      **b. Memberi waktu untuk contactAdapter.addDataLoading();**
   
      c. Memberi waktu untuk contactAdapter.RemoveDataLoading();
   
      d. Memberi waktu untuk contactAdapter.insertDataLoading();

80. Jika waktu delay telah habis maka apa yang terjadi ?

      a. Menjalakan contactAdapter.addDataLoading();
   
      **b. Menjalankan method run**
   
      c. Menjalankan  isScroll = false;
   
      d. Menjalankan contactAdapter.addDataContacts();

## Infinite Scroll Menggunakan API (Movie Apps)
81. Berikut library yang digunakan untuk membuat Movie Apps, **kecuali**...
    
      **a. CalenderPicker**
   
      b. Volley
   
      c. Glid
   
      d. Material

82. Fungsi dari volley adalah...

      a. Untuk menampilkan data JSON
   
      **b. Untuk mengambil data API**
   
      c. Untuk mendesain RecyclerView dan Card
   
      d. Convert dari JSON ke Objek

83. Fungsi dari glide adalah...
      
      a. Menampilkan path gambar dari URL
   
      **b. Convert dari JSON ke Objek**
   
      c. Menampilkan gambar dari URL
   
      d. Untuk mendesain RecyclerView dan Card

84. Fungsi dari material adalah...

      a. Menampilkan gambar dari URL
   
      **b. Untuk mendesain RecyclerView dan Card**
   
      c.  Menampilkan path gambar dari URL
   
      d. Convert dari JSON ke Objek

85. Fungsi dari gson adalah...

      a. Untuk mendesain RecyclerView dan Card
   
      **b. Convert dari JSON ke Objek**
   
      c. Convert dari Array ke JSON
   
      d. Menampilkan gambar dari URL

86. Fungsi dari swap refresh adalah...

      a. Untuk mendesain RecyclerView dan Card
   
      b. Convert dari JSON ke Objek
   
      c. Convert dari Array ke JSON
   
      **d. Merefresh layout**
   
87. Berikut Base url movie **kecuali**....

      a. BASE_URL_MOVIE_DB
   
      b. API_VERSION
   
      c. TOKEN_MOVIE_DB
   
      **d. BASE_URL_MOVIE_DB**

88. CardView terdapat pada...

      a. ITEM_LOADING

      b. ITEM_TYPE

      **c. ITEM_MOVIE**

      d. ITEM_ADAPTER

89. Constraint layout adalah...

      a. Adalah sekelompok tampilan yang menyejajarkan semua anak dalam satu arah, secara vertikal atau horizontal

      b. Komponen untuk menampilkan informasi dalam bentuk grid

      c. Adalah elemen yang berfungsi untuk menampilkan output berupa text

      **d. Merupakan komponen ViewGroup yang dapat kita gunakan untuk menyusun tampilan aplikasi yang kompleks tanpa adanya nested layout**

90. ImageView adalah...

      **a. Komponen untuk menampilkan gambar**

      b. komponen untuk menampilkan informasi dalam bentuk card

      c. Komponen untuk menampilkan informasi dalam bentuk list

      d. Semua jawaban benar

91. Membuat rating menggunakan tag...

      **a. RatingBar**

      b. StatusBar

      c. StarBar

      d. GalaxyBar

92. Agar tulisan menjadi tebal...

      **a. android:textStyle="bold"**

      b. android:textStyle="italic"

      c. android:textStyle="underline"

      d. android:textStyle="bolded"
      
### Buat Movie Adapter
93. Gson digunakan untuk...

      **a. library untuk melakukan serialisasi dan deserialisasi data JSON dengan mudah**

      b. library untuk melakukan hashing data JSON dengan mudah

      c. library untuk melakukan naturalisasi data JSON dengan mudah

      d. A dan C benar

94. Singkatan dari JSON...

      **a. JavaScript object notation**

      b. JavaScript object notification

      c. JavaSheet object notation

      d. JavaScript notation object

95. Jika viewType != TYPE_LOADING maka yang terjadi adalah...

      a. Menampilkan AddLoading

      b. Menampilkan RemoveLoading

      **c. Menampilkan movieviehodler**

      d. Menampilkan fecthData

96. Untuk mengambil data movie ditangani oleh method ?

      a. public int fecthData()

      **b. public int getDataMovies()**

      c. public int getDataMovies()

      d. public int getDataMovies()

97. Apa yang di return oleh getDataMovies ?

      a. dataMovies.add(null);

      b. dataMovies.remove(dataMovies.size() - 1);

      **c. return dataMovies.size();**

      d. binding = ItemMovieBinding.bind(itemView);

98. Syntax untuk menggunakan view binding adalah...

      **a. binding = ItemMovieBinding.bind(itemView);**

      b. private ItemMovieBinding binding;

      c. DecimalFormat decimalFormat = new DecimalFormat("#.#");

      d. binding.ratingBarMovie.setRating(movie.movieRate());

99.  Berikut adalah binding yang digunakan dalam movie adapter **kecuali** ?

      a. binding.ratingBarMovie.setRating(movie.movieRate());

      b. binding.tvTitleMovie.setText(movie.getOriginalTitle());

      **c. binding.tvReleaseDate.setText(ItemMovie.getReleaseDate());**
 
      d. binding.ratingBarMovie.setRating(movie.movieRate());

100. Syntax untuk menampilkan data image adalah ?

      **a. Glide.with(itemView).load(urlImage).into(binding.ivMovie);**

      b. String urlImage = BuildConfig.BASE_URL_IMAGE_MOVIE_DB + movie.getPosterPath();

      c. binding.tvTitleMovie.setText(movie.getOriginalTitle());

      d. binding.ratingBarMovie.setRating(movie.movieRate());

101. Untuk menampilkan angka desimal menggunakan ?

      **a. DecimalFormat**

      b. parseDecimal

      c. ConvertDecimal

      d. PreverenceDecimal

102. Function movieRate berfungsi untuk ?

      a. Membagi total data movie dengan

      b. Membagi total user yang melakukan vote dengan 2

      **c. Membagi avarage vote dengan 2 yang hasilnya bernilai maksimal 5**

      d. Membagi total data decimal dengan 2

### Fetch Data API
103. Default value dari page adalah ?

      **a. 1**

      b. 2

      c. 0

      d. 3

104. Untuk memunculkan progress bar di handle oleh ?

      a. private void onStop()

      b. private void hideLoading()

      **c. private void loadLoading()**

      d. private void onCreate()

105. Value dari mainUrl adalah...

      a. BuildConfig.API_VERSION + BuildConfig.TOKEN_MOVIE_DB;

      **b. BuildConfig.BASE_URL_MOVIE_DB + BuildConfig.API_VERSION;**

      c. mainUrl + "discover/movie?api_key=" + BuildConfig.TOKEN_MOVIE_DB + "&page=" + page;

      d. BuildConfig.TOKEN_MOVIE_DB + mainUrl

106. Value dari movieUrl adalah...

      **a. mainUrl + "discover/movie?api_key=" + BuildConfig.TOKEN_MOVIE_DB + "&page=" + page;**

      b. BuildConfig.BASE_URL_MOVIE_DB + BuildConfig.API_VERSION;

      c. BuildConfig.API_VERSION + BuildConfig.TOKEN_MOVIE_DB;

      d. BuildConfig.TOKEN_MOVIE_DB + mainUrl;

107. Request Method yang digunakan pada StringRequest adalah...

      a. POST

      b. PUT

      **c. GET**

      d. DELETE

108. Apa yang terjadi jika requestQueue != null ?

      a. Mengecek koneksi API

      b. Tetap melakukan fecthData

      c. Memberhentikan koneksi API dan tetap melakukan fecthData

      **d. Memberhentikan semua aktifitas fecthData**

### Implementasi Infinite RecyclerView
109. Syntax convert dari JSON ke objek adalah...

      a. MovieResponse movieResponse = new Json().fromJson(response, MovieResponse.class);

      **b. MovieResponse movieResponse = new Gson().fromJson(response, MovieResponse.class);**

      c. MovieResponse movieResponse = new Object().fromJson(response, MovieResponse.class);

      d. MovieResponse movieResponse = new Gson().fromObject(response, MovieResponse.class);

110. Default value dari lastPage adalah ?

      a. 1

      b. 2

      **c. 0**

      d. 3

111. Kondisi Untuk menambah page yang tepat adalah ?

      **a.  if (isScroll && totalScrollItem >= countItems && page <= lastPage)**

      b.  if (isScroll && totalScrollItem >= countItems || page <= Page)

      c.  if (isScroll || totalScrollItem >= countItems && page <= FirstPage)

      d.  if (isScroll && totalScrollItem >= totalScrollItem && page <= lastPage)

112. Syntax untuk menambah page yang tepat adalah ?

      a. isScroll = false;
                    page + 1;
                    fetchData(page);

      b. isScroll = true;
                    page += 1;
                    fetchData(page);

      c. isScroll = false;
                    page += 1;
                    fetchData(page);

      **d. isScroll = false;
                    page += 1;
                    fetchData(page);**

113. if (movieAdapter.getDataMovies() > 0){
     
            movieAdapter.addDataLoading();

        }

        berfungsi untuk....

      a. Mempertahankan loading

      b. Menghilangkan loading

      **c. Menambahkan loading**

      d. Semua jawaban salah

114. movieAdapter.addDataMovies(movieResponse.getMovies()); memiliki fungsi untuk...

      a. Meremove data movie

      **b. Menambah data movie**

      c. Memindahkan data movie ke API

      d. Semu jawaban benar

115. Apa yang terjadi jika  if (response != null){}

      **a. Menghentikan loading dan menyalakan scroll**

      b. Menjalakan loading dan menyalakan scroll

      c. Menghentikan loading dan Mematikan scroll

      d. Menjalakan loading dan Mematikan scroll
     