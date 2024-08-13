# Churn Analizi

Bu proje, müşteri kaybı (churn) analizini gerçekleştirmek için makine öğrenimi araçlarını kullanarak hazırlanmıştır. Amaç, müşterilerin kaybını tahmin etmek ve bu kayıpları minimize etmek için tahmin modelleri oluşturmaktır.

## İçerik

1. [Proje Hakkında](#proje-hakkında)
2. [Kullanılan Veri Seti](#kullanılan-veri-seti)
3. [Analiz Süreci](#analiz-süreci)
4. [Sonuçlar](#sonuçlar)

## Proje Hakkında

Bu proje, bir şirketin müşterilerinin hangi sebeplerle hizmetten ayrıldığını (churn) anlamak ve bu durumları tahmin edebilmek için çeşitli veri analizi ve makine öğrenimi yöntemlerini kullanır.

## Kullanılan Veri Seti

Veri seti, **[Kaggle](https://www.kaggle.com/competitions/playground-series-s4e1)**'dan alınmıştır ve aşağıdaki özellikleri içermektedir:


## Analiz Süreci

1. **Veri Temizleme:** Eksik verilerin doldurulması ve gereksiz verilerin ayıklanması.
2. **Veri Görselleştirme:** Müşteri kaybını etkileyen faktörlerin görselleştirilmesi.
3. **Modelleme:** Churn tahmini için makine öğrenimi modellerinin oluşturulması ve eğitilmesi.
4. **Model Değerlendirme:** Modellerin performanslarının karşılaştırılması ve en iyi modelin seçilmesi.

## Sonuçlar

Analiz sonucunda,en iyi performansı GradientBoostingClassifier modeli göstermiştir ve bu model, %87 doğruluk oranıyla churn tahmininde bulunabilmektedir.

