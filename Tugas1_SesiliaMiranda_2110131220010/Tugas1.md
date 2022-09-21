## Tugas 1 Desain dan Analisis Algoritma
Nama    : Sesilia Miranda<br>
Nim     : 2110131220010

<h2 align="center">TIME COMPLEXITY DAN BIG-O NOTATION</h2>
<hr>

<p align="justify">Setiap programmer yang baik akan menggunakan cara yang paling efektif dan efisien dalam menyelesaikan suatu permasalahan. Dan untuk bisa melakukan hal tersebut, <b>kita harus bisa meminimalisir kompleksitas dari algoritma yang kita gunakan.</b><br>

Kompleksitas suatu algoritma dibagi menjadi 2, yaitu <i>Time Complexity</i> dan <i>Space Complexity.</i><br>

<b>Time Complexity</b> adalah seberapa lama waktu yang diperlukan untuk menjalankan suatu algoritma. Sedangkan <b>Space Complexity</b> adalah seberapa besar memori yang kita gunakan untuk menjalankan suatu algoritma. Dan disini kita hanya akan membahas tentang <b>Time Complexity</b>.</p><br>

#### Algoritma
<p align="justify">Sebelum kita melanjutkan pembahasan, kita harus mengerti dulu apa itu <b>algoritma/fungsi</b>.<br>

Sederhananya, algoritma adalah serangkaian proses yang dilakukan secara berurutan untuk menyelesaikan sebuah permasalahan. Algoritma bisa bermacam-macam tergantung kepada siapa yang membuat algoritma tersebut. Namun permasalahannya adalah <b>algoritma mana yang lebih efektif dan efisien?</b><br> 

Seperti halnya yang sering kita hadapi dalam permasalahan sehari-hari, ketika kita akan berpergian ke suatu tempat. Kita tahu ada banyak jalan yang bisa dilalui untuk bisa sampai di tempat tujuan, namun permasalahannya adalah <b>rute mana yang paling cepat yang bisa kita ambil untuk sampai di tempat tujuan?</b><br>  

<b>Time Complexity Analysis</b> adalah suatu cara sederhana untuk mengetahui berapa lama waktu yang dibutuhkan untuk menjalankan suatu algoritma dengan input tertentu(n). Biasanya lebih dikenal dengan sebutan <b>Big-O Notation</b>.<br>      

<b><i>Big O Notation</i></b> digunakan untuk mengukur tingkat kompleksitas suatu algoritma.</p><br>

#### So, What’s Big-O Notation?
<p align="justify"><b>Big-O Notation</b> adalah cara untuk mengkonversi keseluruhan langkah-langkah suatu algoritma kedalam bentuk <b>Aljabar</b>, yaitu dengan menghiraukan konstanta yang lebih kecil dan koefisien yang tidak berdampak besar terhadap keseluruhan kompleksitas permasalahan yang diselesaikan oleh algoritma tersebut.<br>

Mari kita liat contoh dibawah ini:</p>

<p align="center"><img src = "foto/1.PNG" width="600"></p>

<p align="justify">Sederhananya, semua contoh yang ada diatas mengatakan bahwa <b>“kita hanya akan melihat faktor yang memiliki dampak paling besar terhadap nilai yang dihasilkan oleh algoritma tersebut”.</b><br>

Terdapat beberapa macam <b>time complexity</b>, diantaranya:</p><br>

#### O(1) — Constant Time
<p align="justify"><b>Constant Time</b> artinya banyaknya input yang diberikan kepada sebuah algoritma, tidak akan mempengaruhi waktu proses (runtime) dari algoritma tersebut.</p>

<p align="center"><img src = "foto/2.PNG" width="600"><br>Constant Time</p>

<p align="justify">Contoh diatas, terdapat sebuah fungsi untuk mengambil elemen pertama dari sebuah input array. Kita bisa melihat bahwa berapapun jumlah array yang diberikan kepada fungsi tersebut, dia akan selalu melakukan 1 hal, yaitu mengambil elemen pertama. Itu artinya <b>jumlah input yang diberikan tidak mempengaruhi waktu proses (<i>runtime</i>) dari algoritma tersebut.</b></p>

<p align="center"><img src = "foto/3.png" width="600"></p><br>

#### O(log n) — Logarithmic Time
<p align="justify"><b>Logarithmic Time</b> artinya ketika kita memberikan input sebesar n terhadap sebuah fungsi, jumlah tahapan yang dilakukan oleh fungsi tersebut berkurang berdasarkan suatu faktor. Salah satu contohnya adalah algoritma <b>Binary Search.</b><br>

<b>Binary Search</b> adalah algoritma yang kita gunakan dalam mencari posisi nilai dari suatu array dengan cara ‘mengeliminasi’ setengah dari array input untuk mempercepat proses pencarian.</p>

<p align="center"><img src = "foto/4.1.PNG" width="600"><img src = "foto/4.2.PNG" width="600"></p>

Note: Fungsi rekursif biasanya Logarithmic
<br>
#### O(n) — Linear Time
<p align="justify"><b>Linear Time</b> adalah ketika runtime dari fungsi kita berbanding lurus dengan jumlah input yang diberikan.</p>

<p align="center"><img src = "foto/5.png" width="600"></p> 

<p align="justify">Kita bisa melihat bahwa <b>semakin banyak jumlah input yang diberikan, maka waktu proses/<i>runtime</i> dari fungsi tersebut akan semakin besar.</b></p>

<p align="center"><img src = "foto/6.png" width="600"><br>Linear Time</p>

<br>
#### O(n²) — Quadratic Time
<p align="justify"><b>Quadratic Time</b> adalah ketika runtime dari fungsi kita adalah sebesar n^2, dimana n adalah jumlah input dari fungsi tersebut. Hal tersebut bisa terjadi karena kita menjalankan <b>fungsi linear didalam fungsi linear</b> (n*n).</p>

<p align="center"><img src = "foto/7.png" width="600"></p>

<p align="center"><img src = "foto/8.png" width="600"><br>Quadraric Time</p>

<br>
#### O(2^n) — Exponential Time
<p align="justify"><b>Exponential Time</b> biasanya digunakan dalam situasi dimana kita tidak terlalu tahu terhadap permasalahan yang dihadapi, sehingga mengharuskan kita mencoba setiap <b>kombinasi</b> dan <b>permutasi</b> dari semua kemungkinan.</p>

<p align="center"><img src = "foto/9.png" width="600"><br>Exponential Time</p>

<br>
### Kesimpulan

<p align="justify">Sebagai programmer, kita sering kali dihadapkan dengan adanya beberapa solusi untuk sebuah permasalahan dan kita dibingungkan dengan pertanyaan <b>“mana solusi yang lebih efisien?”.</b><br>

Dengan memahami <b>Big-O Notation</b>, kita akan lebih mudah dalam melihat mana algoritma yang lebih efisien yang bisa kita gunakan untuk menyelesaikan permasalahan yang sedang dihadapi.</p>