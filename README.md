
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
adalah teknik analisis data yang digunakan untuk mengidentifikasi pola pembelian atau asosiasi antara produk atau layanan yang dibeli oleh pelanggan. Tujuannya adalah untuk memahami hubungan antara item yang sering dibeli bersama-sama sehingga bisnis dapat mengambil keputusan yang lebih baik terkait dengan penataan produk, promosi, dan strategi penjualan.

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

1. **Support:**
   - **Definisi:** Support mengukur seberapa sering suatu itemset muncul dalam dataset transaksi.
   - **Perhitungan:** Jumlah transaksi yang mengandung itemset tertentu dibagi dengan total jumlah transaksi.
   - **Contoh:** Jika kita ingin mengukur support untuk itemset {A, B} dan ada 100 transaksi, di mana itemset ini muncul dalam 30 transaksi, maka supportnya adalah 30/100 = 0,3 atau 30%.

   - **Interpretasi:** Support membantu mengidentifikasi seberapa umum atau populer suatu kombinasi item dalam dataset. Kombinasi dengan support tinggi cenderung lebih bermanfaat dalam konteks analisis asosiasi.

2. **Confidence:**
   - **Definisi:** Confidence mengukur seberapa sering aturan asosiasi benar.
   - **Perhitungan:** Jumlah transaksi yang mengandung itemset yang mencakup kedua item dalam aturan asosiasi dibagi dengan jumlah transaksi yang mengandung item yang muncul di sisi kiri aturan.
   - **Contoh:** Jika kita memiliki aturan {A} => {B} dan confidence-nya adalah 0,8, ini berarti dalam 80% transaksi yang mengandung A, B juga ada.

   - **Interpretasi:** Confidence membantu mengevaluasi sejauh mana aturan asosiasi dapat diandalkan. Aturan dengan confidence tinggi menunjukkan bahwa pembelian item di satu sisi aturan cenderung diikuti oleh pembelian item di sisi lainnya.

3. **Lift:**
   - **Definisi:** Lift mengukur seberapa lebih mungkin dua item dibeli bersama-sama daripada jika mereka dibeli secara independen.
   - **Perhitungan:** (Support untuk itemset {A, B}) / (Support untuk A * Support untuk B)
   - **Contoh:** Jika lift > 1, ini menunjukkan bahwa pembelian A dan B bersama-sama lebih sering daripada pembelian secara independen.

   - **Interpretasi:** Lift membantu menentukan apakah ada hubungan yang signifikan antara dua item atau apakah kombinasi tersebut lebih acak. Lift = 1 berarti tidak ada asosiasi yang signifikan, lift > 1 menunjukkan asosiasi yang positif, sementara lift < 1 menunjukkan asosiasi yang negatif.

Dalam prakteknya, analisis support, confidence, dan lift membantu bisnis membuat keputusan informasional terkait penempatan produk, strategi harga, atau promosi untuk meningkatkan penjualan dan kepuasan pelanggan.
  
</details>

