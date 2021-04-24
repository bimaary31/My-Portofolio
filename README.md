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
<img height ="500" src="https://github.com/bimaary31/data_credit_rating/blob/main/Rplot.png"/>
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
