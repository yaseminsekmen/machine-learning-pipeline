# machine-learning-pipeline

An end-to-end machine learning pipeline including data preprocessing, outlier handling (winsorization), feature extraction via PCA and LDA, classification with multiple algorithms (Logistic Regression, Decision Tree, Random Forest, XGBoost, Naive Bayes), and model evaluation using nested cross-validation. The project also includes ROC curve analysis for each class using One-vs-Rest strategy.

Eksik veri ön işleme, aykırı değer baskılama (winsorization), özellik çıkarımı (PCA ve LDA), çeşitli sınıflandırma algoritmalarıyla modelleme (Lojistik Regresyon, Karar Ağacı, Rastgele Orman, XGBoost, Naive Bayes) ve nested cross-validation ile performans değerlendirmesi yapılan uçtan uca bir makine öğrenmesi projesidir. Ayrıca her sınıf için ROC eğrileri One-vs-Rest yöntemi ile analiz edilmiştir.

## 🚀 Features / Özellikler

- ✅ Missing value detection and imputation (median-based)
- ✅ Outlier detection using IQR method and winsorization
- ✅ Dimensionality reduction: PCA & LDA
- ✅ Model training with:
  - Logistic Regression
  - Decision Tree
  - Random Forest
  - XGBoost
  - Gaussian Naive Bayes
- ✅ Nested cross-validation (5 outer folds, 3 inner folds)
- ✅ ROC-AUC curve analysis (OVA - One-vs-Rest)

## 📊 Evaluation Metrics / Değerlendirme Metrikleri

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC (per class)


## 🧠 Used Libraries / Kullanılan Kütüphaneler

- pandas, numpy
- matplotlib, seaborn
- scikit-learn
- xgboost

## 📌 Notes / Notlar

This project was developed for educational purposes in a machine learning course and demonstrates the full pipeline from preprocessing to evaluation.  
Bu proje, bir makine öğrenmesi dersi kapsamında hazırlanmış olup, veri ön işlemeden model değerlendirmeye kadar tüm süreci kapsamaktadır.




