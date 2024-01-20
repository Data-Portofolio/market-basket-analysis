
<h1 align="center">
<p align="center">  Market Basket Analysis
   
<br>
    <br>
<!-- PROJECT LOGO -->

  <kbd>
  <a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=DDF4CBF9&background=1F25E6D0&center=true&vCenter=true&random=false&width=435&lines=A+Simple+Pandas+DataFrame+CheatSheet" alt="Typing SVG" /></a>
  </kbd>
  
  <p align='center'>
    <a href='https://github.com/Data-Portofolio/The-Ultimate-Pandas-Guide-Simplifying-Data-Operations'>
        <img alt='total stars' title='Total stars on This Project' src='https://custom-icon-badges.herokuapp.com/badge/dynamic/json?logo=star&color=5&labelColor=488207&label=Stars&style=for-the-badge&query=%24.stars&url=https://api.github-star-counter.workers.dev/user/Data-Portofolio'/>
     <a href='https://github.com/astutir'>
        <img alt='Follow Me on GitHub' title='Follow Me on GitHub' src='https://custom-icon-badges.herokuapp.com/github/followers/astutir?style=for-the-badge&&label=GitHub&logo=Github&color=pink'/>
    <a href='https://www.linkedin.com/in/a-rahmawati' target='_blank'>
        <img src='https://img.shields.io/badge/linkedin%20-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white'/>
    <a href='mailto:astutirahmarubi@gmail.com' target='_blank'>
        <img src='https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white'/>
 </p>

</h1>
<details>
  <summary>Definition</summary>
 
### Market Basket Analysis (MBA)
adalah teknik analisis data yang digunakan untuk mengidentifikasi pola pembelian atau asosiasi antara produk atau layanan yang dibeli oleh pelanggan. Tujuannya adalah untuk memahami hubungan antara item yang sering dibeli bersama-sama sehingga bisnis dapat mengambil keputusan yang lebih baik terkait dengan penataan produk, promosi, dan strategi penjualan. Dalam prakteknya, analisis support, confidence, dan lift membantu bisnis membuat keputusan informasional terkait penempatan produk, strategi harga, atau promosi untuk meningkatkan penjualan dan kepuasan pelanggan.

Proses Market Basket Analysis melibatkan penggunaan algoritma data mining, terutama algoritma asosiasi, yang membantu mengidentifikasi aturan asosiasi antara item. Contohnya, jika seseorang membeli kopi, kemungkinan besar dia juga akan membeli gula. Atau, jika pelanggan membeli susu, mungkin dia juga akan membeli sereal.

Langkah-langkah umum dalam Market Basket Analysis:

1. **Data Collection:** Mengumpulkan data transaksi penjualan yang mencatat item-item yang dibeli oleh pelanggan pada setiap transaksi.

2. **Preprocessing Data:** Membersihkan dan mempersiapkan data untuk analisis. Ini mungkin melibatkan penghapusan data yang tidak relevan, mengelompokkan item, atau mengatasi masalah-masalah lain dalam data.

3. **Pembentukan Itemset:** Mengidentifikasi kombinasi item yang sering dibeli bersama-sama. Itemset dapat menjadi pasangan item (dua item), triplet (tiga item), atau lebih.

4. **Hitung Dukungan (Support):** Menghitung frekuensi kemunculan itemset dalam dataset. Dukungan mengukur seberapa sering kombinasi item muncul dalam transaksi.

5. **Hitung Keandalan (Confidence):** Menghitung sejauh mana aturan asosiasi dapat diandalkan. Keandalan mengukur seberapa sering aturan tersebut terbukti benar berdasarkan data.

6. **Pemilihan Aturan:** Menetapkan ambang batas (threshold) untuk dukungan dan keandalan untuk menentukan aturan asosiasi yang signifikan.

7. **Interpretasi Hasil:** Menganalisis aturan asosiasi yang dihasilkan dan mengambil tindakan berdasarkan temuan tersebut, seperti mengatur penempatan produk di toko, membuat bundel produk, atau merancang kampanye promosi yang lebih efektif.

### Metrics of MBA

Dalam konteks Market Basket Analysis, support, confidence, dan lift adalah konsep-konsep yang digunakan untuk mengukur dan mengevaluasi aturan asosiasi yang dihasilkan dari analisis data transaksi. Mari kita jelaskan masing-masing konsep tersebut:

Tentu, mari tambahkan definisi untuk setiap metrik:

1. **Support:**
   - **Definisi:** Support mengukur seberapa sering suatu itemset muncul dalam dataset transaksi.
   - **Contoh Perhitungan:**
     - Jumlah transaksi yang mencakup pembelian kopi (A) dan gula (B): 50 transaksi.
     - Total jumlah transaksi dalam dataset: 200 transaksi.
     - Support untuk {A, B} = (50/200) = 0,25 atau 25%.

   - **Interpretasi:**
     - Support 25% menunjukkan bahwa 25% dari seluruh transaksi melibatkan pembelian kopi dan gula bersama-sama. Ini menunjukkan popularitas atau keberadaan kombinasi ini dalam dataset.

2. **Confidence:**
   - **Definisi:** Confidence mengukur seberapa sering aturan asosiasi benar.
   - **Contoh Perhitungan:**
     - Jumlah transaksi yang mencakup pembelian kopi (A) dan diikuti oleh pembelian gula (B): 40 transaksi.
     - Jumlah transaksi yang hanya mencakup pembelian kopi (A): 60 transaksi.
     - Confidence untuk aturan {A} => {B} = (40/60) = 0,67 atau 67%.

   - **Interpretasi:**
     - Confidence 67% menunjukkan bahwa ketika pelanggan membeli kopi, ada 67% kemungkinan mereka juga akan membeli gula. Ini menunjukkan seberapa kuat asosiasi antara pembelian kopi dan gula.

3. **Lift:**
   - **Definisi:** Lift mengukur seberapa lebih mungkin dua item dibeli bersama-sama daripada jika mereka dibeli secara independen. Lift membantu menentukan apakah ada hubungan yang signifikan antara dua item atau apakah kombinasi tersebut lebih acak. Lift = 1 berarti tidak ada asosiasi yang signifikan, lift > 1 menunjukkan asosiasi yang positif, sementara lift < 1 menunjukkan asosiasi yang negatif.
   - **Contoh Perhitungan:**
     - Support untuk {A, B} = 0,25 (seperti pada contoh support).
     - Support untuk A = (60/200) = 0,3 atau 30% (jumlah transaksi yang mencakup pembelian kopi).
     - Support untuk B = (80/200) = 0,4 atau 40% (jumlah transaksi yang mencakup pembelian gula).
     - Lift = (0,25) / (0,3 * 0,4) = 2,08.

   - **Interpretasi:**
     - Lift lebih dari 1 (2,08) menunjukkan bahwa pelanggan lebih mungkin membeli kopi dan gula bersama-sama daripada jika pembelian kopi dan gula dilakukan secara independen. Ini menunjukkan adanya asosiasi yang positif.

Dengan informasi ini, toko atau bisnis dapat mengambil tindakan, seperti menempatkan kopi dan gula bersama-sama di area penjualan, membuat penawaran bundel, atau mengoptimalkan promosi untuk meningkatkan penjualan dan kepuasan pelanggan. 
  
</details>

