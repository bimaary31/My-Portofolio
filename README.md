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
    4. Prediksi confusion matrix Pelanggan yang  benar-benar beralih  ke operator lain sebanyak 235
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
    
## Project 3: Retail Raw Reduced in DKI Jakarta Province

