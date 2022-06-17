# Bank-Customer-Clustering

# Introduction


##<h2>Title</h2>
Bank Marketing Campaign - Customer Bank Clustering.

selamat datang di project saya, saya Irvan Sikajudin, seorang Data Science enthusiast, project ini berisikan beberapa proses, mulai dari Data Understanding, EDA, Deep dive EDA, Data Prepocessing, kemudian segmentasi dengan algoritma K-means clustering, agglomerative clustering dan juga K-prototypes Clustering.

##<h2>Context and Source</h2>

<h2>Context</h2>
Temukan strategi terbaik untuk ditingkatkan untuk kampanye pemasaran berikutnya. Bagaimana lembaga keuangan memiliki efektivitas yang lebih besar untuk kampanye pemasaran di masa depan? Untuk menjawab ini, kami harus menganalisis kampanye pemasaran terakhir yang dilakukan bank dan mengidentifikasi pola yang akan membantu kami menemukan kesimpulan untuk mengembangkan strategi masa depan.<br>

<h2>Source</h2>
[Moro et al., 2014] S. Moro, P. Cortez and P. Rita. A Data-Driven Approach to Predict the Success of Bank Telemarketing. Decision Support Systems, Elsevier, 62:22-31, June 2014

Dataset is about Bank campaign dataset obtained from Kaggle and licensed under CC0: Public Domain.

## Idea of The Project
The idea of ​​this project is to find out the Cluster of Dataset.

The dataset contains order-related columns, look at below for more information about columns

<table>
<thead><tr>
<th>Header</th>
<th>Definition</th>
</tr>
</thead>
<tbody>
<tr>
<td><code>Age</code></td>
<td>Age of customer</td>
</tr>
<tr>
<td><code>Job</code></td>
<td>Job of customer</td>
</tr>
<tr>
<td><code>Martial</code></td>
<td>Martial status of customer  </td>
</tr>
<tr>
<td><code>Education</code></td>
<td>Customer education level</td>
</tr>
<tr>
<td><code>Default</code></td>
<td>Has credit in default?</td>
</tr>
<tr>
<td><code>Housing</code></td>
<td>If costumer has housing loan</td>
</tr>
<tr>
<td><code>Loan</code></td>
<td>Has Personal Loan</td>
</tr>
<tr>
<td><code>Balance</code></td>
<td>Customer's individual balance</td>
</tr>
<tr>
<td><code>Contact</code></td>
<td>Communication type</td>
</tr>
<tr>
<td><code>Month</code></td>
<td>Last contact month of year </td>
</tr>
<tr>
<td><code>Day</code></td>
<td>Last contact day of the week</td>
</tr>
<tr>
<td><code>Duration</code></td>
<td>Last contact duration, in seconds</td>
</tr>
<tr>
<td><code>Campaign</code></td>
<td>Number of contacts performed during this campaign and for this client</td>
</tr>
<tr>
<td><code>Pdays</code></td>
<td>Number of days that passed by after the client was last contacted from a previous campaign</td>
</tr>
<tr>
<td><code>Previous</code></td>
<td>Number of contacts performed before this campaign and for this client</td>
</tr>
<tr>
<td><code>Poutcome</code></td>
<td>outcome of the previous marketing campaign </td>
</tr>
<tr>
<td><code>Deposit</code></td>
<td>has the client subscribed a term deposit</td>
</tr>
</tbody>
</table>

## <h2>Creative Marketing Ideas for Banks:</h2>


*   Location-Based Advertising
*   Gamification in FinTech
*   Make Customer Service Fun!
*   Highlight Success Stories
*   Social Media Personality
*   Partnerships
*   Reward Users for Engagement


<h1>Rekomendasi untuk Marketing Dept</h1></br>
demi tercapainya peningkatan pelanggan yg melakukan term deposit, maka pertimbangkan beberapa hal sebagai berikut :

Pertimbangkan untuk malakukan kampanye pada usia 30 an.
Pertimbangkan untuk malakukan kampanye pada pasangan yang tidak bercerai.
Pertimbangkan untuk melakukan kampanye pada pelanggan yang tidak memiliki Loans(Pinjaman) serta menghindari pelanggan yg memiliki pinjaman.
Pertimbangkan untuk melihat tingkat saldo pada setiap profesi, usahakan untuk lebih banyak mendekati pelanggan yg bekerja di rana management.
Tidak disarankan untuk campaign (menghubungi) pelanggan terlalu sering, karena semakin banyak menghubungi(melakukan kampanye/iklan) kepada pelanggan maka kesempatan utk pelanggan tersebut melakukan term deposit semakin mengecil.


<h1>Note</h1></br>
dapat dilihat model agglomerative clustering penulis beranggapan cluster ideal terbagi menjadi 3 cluster, pada model agglomerative dan K-means, fitur kategorik di drop karena model tersbut hanya untuk data numerikal kontinu, sedangakan untuk dapat menghandle data mix (data kategori dan kontinu) penulis menggunakan K-prototypes sebagai jalan keluar.
