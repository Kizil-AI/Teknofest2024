
# Teknofest 2024 AI in Healthcare Competition Code

Bu repository, Teknofest Sağlıkta Yapay Zeka Yarışması kapsamında 5 kişilik bir takım tarafından geliştirilen modellerin kodlarını içermektedir. Mamografi görüntülerinden kalsifikasyon ve kitle tespiti ile rapor metinlerinden BI-RADS sınıflandırması yapan çift modüllü bir sistem içerir.

## Proje Hakkında

### Temel Modüller
1. **Görüntü İşleme Modülü**  
   Mamografi görüntülerinde:
   - Kalsifikasyon tespiti
   - Kitle tespiti
   - Anomali lokalizasyonu

2. **Doğal Dil İşleme (NLP) Modülü**  
   Rapor metinlerinde:
   - BI-RADS kategorizasyonu
   - Klinik terim tanıma
   - Çoklu-etiket sınıflandırma

## Teknik Özellikler
- **Platform**: Python 3.8+
- **ML Framework**: TensorFlow/Keras,
- **NLP Araçları**: BERT-tabanlı modeller
- **Görüntü İşleme**: CNN mimarileri (YOLO, RCNN), pytorch


## Kurulum
1. Repository klonlama:
   ```bash
   git clone https://github.com/Kizil-AI/Teknofest2024
   ```

> **Not:** Yarışma veri seti lisans kısıtlamaları nedeniyle repository'de bulunmamaktadır. Kendi veri setinizle kullanmak için veri yollarını güncellemeniz gerekmektedir.

## Katkı Rehberi
Bu README, projeyi hem geliştiriciler hem de ilgi duyan kullanıcılar için anlaşılır kılmayı amaçlamaktadır. Herhangi bir sorunuz veya katkı öneriniz olursa, lütfen iletişime geçmekten çekinmeyin.

## Önemli Notlar
- **Performans Metrikleri**:
  - Görüntü Sınıflandırma:
    -YOLO: 0.51 F1-Score
    -RCNN: 0.535 F1-Score
    -Ensemble: 0.617 F1-Score
  -Bi-RADS Sınıflandırması: 0.91 F1-Score 
  - NLP Modeli: 0.92 F1-Score
---
