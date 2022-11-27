# JanakaToufikCapstone3
Capstone 3 Janaka Toufik Daugu Apartment Price Prediction
### **Contents**

1. Business Problem Understanding
2. Data Understanding
3. Data Preprocessing
4. Modeling
5. Conclusion
6. Recommendation

****
1. Business problem understanding terdiri dari konteks tentang dataset apartemen Daegu, Problem Statement, Goals, analytic approach, dan metric evaluation
2. Data understanding menjelaskan tiap kolom pada dataset dan akan melakukan EDA
3. Data preprocessing yaitu mengisi missing value, drop duplicates, adress outliers
4. Modeling akan dilakukan tes cross validation, predict to test set, dan hyperparametric tuning pada clean dataset
5. Conclussion:
Berdasarkan model yang telah dibuat dapat diambil beberapa kesimpulan:
- Model machine learning paling baik untuk dataset ini adalah XGBoost Regressor
- Model memiliki R2 score atau nilai rsquared sebesar 0.81 artinya model dapat menjelaskan 81% dari variansi data.
- Model memiliki MAPE score sebesar 0.18, artinya harga prediksi dapat lebih besar atau lebih kecil 18% dari harga sebenarnya
- Model memiliki MAE score atau residual sebesar 36436 USD, karena range harga apartemen berkisar dari 30000 USD hingga 580000 USD maka residual tersebut dapat dianggap wajar dan tidak terlalu besar.
- Model tidak terlalu baik memprediksi apartemen dengan harga mahal, tetapi sudah cukup baik memprediksi harga apartemen murah.
- Model tidak mempertimbangkan inflasi harga.
- Fitur paling penting untuk memprediksi harga apartemen adalah Hallway type dan size
- Model machine learning dapat memprediksi harga apartemen dengan cepat dan dapat menghemat waktu dan tenaga untuk melakukan prediksi harga dibandingkan dengan melakukan research tiap apartemen satu persatu.
6. Recommendation:
Untuk memperbaiki model yang dapat dilakukan adalah:
- Mencoba menggunakan model lain seperti Neural Network Regression
- Menambahkan fitur-fitur lain yang dapat memengaruhi harga apartemen, seperti waktu untuk mencapai halte bis terdekat, lantai apartemen, dan jumlah SD,SMP,SMA di dekat apartemen (karena ada fitur jumlah universitas dekat apartemen).
- Menambahkan data baru (update)
- Menggunakan Grid search saat hyperparametric tuning 
- Melakukan hyperparametric tuning untuk model lain yang tidak digunakan (DT,KNN,Linear Regression, Random Forrest) dan membandingkan hasilnya

