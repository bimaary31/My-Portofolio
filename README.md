# My-Portofolio
My Portofolio in Data Science

# [Project 1:Credit Risk Analysis](https://github.com/bimaary31/data_credit_rating.git)

## 1. Credit Score Asumption
- Jika jumlah tanggungan berjumlah lebih dari 4, kecenderungan resikonya sangat tinggi (rating 4 dan 5).
- Jika durasi pinjaman semakin lama yaitu lebih dari 24 bulan, maka kecenderungan resiko juga meningkat (rating 4 dan 5).
- Jika jumlah tanggungan berjumlah kurang dari 5 orang , dan durasi pinjaman kurang dari 24 bulan maka rating diberikan nilai 2 dan pengajuan pinjaman diterima. 
- Jika jumlah tanggungan berjumlah lebih dari 4 orang dan durasi pinjaman lebih dari 24 bulan maka maka rating diberikan nilai 5 dan pengajuan pinjaman ditolak.
- Jika jumlah tanggungan berjumlah kurang dari 5, dan durasi pinjaman kurang dari 36 bulan maka maka rating diberikan nilai 3 dan diberikan pinjaman.

## 2. Credit Score Output
Decision tree:
- jumlah_tanggungan > 4:
    :...durasi_pinjaman_bulan <= 24: 4 (98/25)
    :   durasi_pinjaman_bulan > 24: 5 (129/49)
- jumlah_tanggungan <= 4:
    :...jumlah_tanggungan > 2: 3 (219/17)
        jumlah_tanggungan <= 2:
        :...durasi_pinjaman_bulan <= 36: 1 (259/80)
            durasi_pinjaman_bulan > 36:
            :...jumlah_tanggungan <= 0: 2 (37/7)
                jumlah_tanggungan > 0: 3 (58/2)
           
<br> 
<img height ="400" src="https://github.com/bimaary31/data_credit_rating/blob/main/Rplot.png"/>
<br>

## [Project 2: Predict Customer Churn Telco for Telco Companny](https://github.com/bimaary31/customer_churn.git)
- Melakukan prediksi dengan machine learning dengan pendekatan Logistic Regression 
- Menggunakan variabel independen 
    1. Gender
    2. Senior Citizen
    3. Partner
    4. Tenure
    5. Phone Service
    6. Streaming Tv
    7. Internet Service
    8. PaperLessBilling
    9. MonthlyCharges
    10. TotalCharges
- Variabel Inti
    1. Churn
- Eksplorasi Data
<br>
<img  height="400" src="https://github.com/bimaary31/customer_churn/blob/main/Eksplorasi%20data.png"/>
<br>

- Hasil Testing Predict Model
<br>
<img height="350" src="https://github.com/bimaary31/customer_churn/blob/main/Testing%20Model.png"/>
<br>
    1. Prediksi confusion matrix Pelanggan yang  benar-benar tidak beralih  ke operator lain sebanyak 1338 pelanggan <br>
    2. Prediksi confusion matrix Pelanggan yang  diperkirakan  tidak beralih  ke operator lain namun beralih ke operator lain sebanyak 151 pelanggan <br>
    3. Prediksi confusion matrix Pelanggan yang  diperkirakan  beralih  ke operator lain namun tidak beralih ke operator lain sebanyak 311 pelanggan <br>
    4. Prediksi confusion matrix Pelanggan yang  benar-benar beralih  ke operator lain sebanyak 235 <br>
    
- Hasil Training Model
<br>
<img height="350" src="https://github.com/bimaary31/customer_churn/blob/main/Training%20Model.png"/> 
<br>
    1. Prediksi confusion matrix Pelanggan yang  benar-benar tidak beralih  ke operator lain sebanyak 3199 pelanggan <br>
    2. Prediksi confusion matrix Pelanggan yang  diperkirakan  tidak beralih  ke operator lain namun beralih ke operator lain sebanyak 376 pelanggan <br>
    3. Prediksi confusion matrix Pelanggan yang  diperkirakan  beralih  ke operator lain namun tidak beralih ke operator lain sebanyak 723 pelanggan <br>
    4. Prediksi confusion matrix Pelanggan yang  benar-benar beralih  ke operator lain sebanyak 567 <br>
- Simpulan 
    Berdasarkan hasil prediksi diatas bahwa  penlanggan yang menetap pada telco companny lebih banyak dibandingkan pelanggan yang beraliih  
    
## [Project 3: Retail Raw Reduced in DKI Jakarta Province](https://github.com/bimaary31/Data_Visualization.git)

## [Project 4: Isurance Cost Prediction](https://github.com/bimaary31/insurance_cost_prediction.git)
- Tahap-tahap project
1. Loading data
2. Data wrangling
3. Exploration Data Analysis
4. Data Preprocessing Encoding
5. Model Selction
    <br> X: age, bmi, children, region <br>
    Y: Chargers
6. Linear Regression model
7. Model Evaluation
    - berdasarkan hasil evaluasi training_set dengan pendekatan R Square memiliki akurasi 75%
    - berdasarkan hasil evaluasi test_set dengan pendakatan R Square memiliki akurasi 74%
    <br> dengan demikian model ini dapat dilanjutkan <br>
8. Building data predict
    <br> jika pengguna asuransi berumur  19 tahun atau berjenis kelamin perempuan atau tidak ada anak-anak atau merokok yang tinggal di wilayah southwest diprediksi memmiliki<br> cost_insurance sebesar  USD 25597.739413468422   
    
## [Project 5: Market Basket Ball Analysis](https://github.com/bimaary31/apriori.git)
Project ini menentukan package dari beberapa pembelian barang atau arules
-Tahap-Tahap Project
1. Loading data
2. Menampilkan data
3. Melakasanakan Market Basket Ball Analysis dengan pendekatan Apriori 
 
Berdasarkan hasil tersebut petfood & sirup layak untuk di jadikan package penjualan karena memiliki nilai support 0.4 dan conffidance 0.8  serta ditunjang dangan  nilai lift di atas 1. Hal ini  menandakan memiliki nilai asosiasi yang kuat,  dan paket ini akan terjual 40%.

## [Project 6: Loan Predict with Approch Support Vector Model](https://github.com/bimaary31/Loan_Model_Prediction.git)<br>
Project ini menggunakan pendekatan Support Vector Model untuk mengklasifikasi pembiayaan kepada nasabah
- Tahap-Tahap Project
1. Loading Data
2. Check Missing Value
3. Describe Data
4. Exploration Data
5. Convert type data to int64
6. Selection Model
7. Training & Testing Model
8. Evaluation Model

- Hasil 
Pada model selection menggunakan ukuran uji sebesar 10% dan untuk melatih sebesar 90% dan menghasilkan (48,11) untuk pengujian, (432,11) untuk melatih.
Berdasarkan hasil evaluasi melatih model.<br>
Hasil Melatih Model:
    1. Prediksi confusion matrix Pelanggan yang  benar-benar ditolak  sebanyak 46  nasabah <br>
    2. Prediksi confusion matrix Pelanggan yang  dinyatakn ditolak namun ternyata diprediksi diterima sebanyak 87 nasabah <br>
    3. Prediksi confusion matrix Pelanggan yang  dinyatakan diterima namun ternyata ditolak sebanyak  4 nasabah  <br>
    4. Prediksi confusion matrix Pelanggan yang  benar-benar diterima sebanyak 295 <br>
Dari hasil model ini sangat membutuhkan prediksi yang ke empat, maka sangat dibutuhkan evaluasi dari precison model tersebut yaitu 77%

Berdasarkan hasil uji model tersebut.<br>
Hasil menguji Model:
    1. Prediksi confusion matrix Pelanggan yang  benar-benar ditolak  sebanyak 8  nasabah. <br>
    2. Prediksi confusion matrix Pelanggan yang  dinyatakn ditolak namun ternyata diprediksi diterima sebanyak 7 nasabah. <br>
    3. Prediksi confusion matrix Pelanggan yang  dinyatakan diterima namun ternyata diprediksi ditolak sebanyak  1 nasabah.  <br>
    4. Prediksi confusion matrix Pelanggan yang  benar-benar diterima sebanyak 32. <br>
Dari hasil model ini sangat membutuhkan prediksi yang ke empat, maka sangat dibutuhkan evaluasi dari precison model tersebut yaitu 88%
- Kesimpulan:
    Kesimpulan dari kedua evaluasi model latih dan model uji model ini sangat bagus untuk memprediksi pembiayaan




