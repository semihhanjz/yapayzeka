# Türkçe Sosyal Medya Yorumlarında Yapay Zeka ile Duygu Analizi

## Proje Özeti
Bu projede, Türkçe sosyal medya ve e-ticaret yorumlarının duygu durumunu (olumlu/olumsuz) otomatik olarak sınıflandıran hazır bir derin öğrenme modeli uygulanmıştır.

## Problem Tanımı
Günümüzde firmalar ve dijital platformlar binlerce kullanıcı geri bildirimi almaktadır. Bu yorumların insanlar tarafından tek tek okunup analiz edilmesi zaman ve maliyet açısından imkansızdır. Bu yapay zeka projesi sayesinde, müşteri memnuniyeti veya sosyal medya algısı saniyeler içinde otomatik olarak ölçülebilmektedir.

## Kullanılan Veri Seti ve Kaynağı
Projede Kaggle üzerinde yer alan "Twitter (X) Türkçe Duygu Analizi Veri Seti" referans alınmıştır.
- **Veri Seti Linki:** [Kaggle - Turkish Market Sentiment Dataset](https://www.kaggle.com/datasets/gorkemgunay/turkish-market-sentiment-dataset-for-twitter)

## Kullanılan Model ve Yöntem
Projede sıfırdan model eğitmek yerine, transfer learning mantığıyla Hugging Face kütüphanesinde yer alan ve Türkçe metinler üzerinde önceden eğitilmiş olan **`savasy/bert-base-turkish-sentiment`** BERT modeli kullanılmıştır.

## Nasıl Çalıştırılır?
1. Projeyi bilgisayarınıza indirin veya klonlayın.
2. Gerekli kütüphaneleri yüklemek için terminalde şu komutu çalıştırın:
```bash
   pip install -r requirements.txt