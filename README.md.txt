# 📈 Borsa Veri Tahmini: LSTM ve GRU ile Hisse Senedi Fiyat Tahmini

Bu proje, BIST (Borsa İstanbul) şirketlerinin geçmiş hisse senedi verilerini kullanarak, LSTM (Long Short-Term Memory) ve GRU (Gated Recurrent Unit) modelleriyle hisse fiyatlarını tahmin etmektedir.

## 🚀 Kullanılan Kütüphaneler

- TensorFlow
- Keras
- NumPy
- Pandas
- scikit-learn
- Matplotlib
- yFinance

## 🧠 Amaç

Proje, belirli BIST hisselerinin geçmiş verilerini kullanarak:
- LSTM ve GRU modelleriyle fiyat tahmini yapmak,
- Modellerin performansını karşılaştırmak,
- MSE, RMSE, MAE, R², Accuracy, F1 Score gibi metriklerle başarıyı ölçmek amacıyla geliştirilmiştir.

## 📊 Kullanılan Hisseler

Aşağıdaki BIST hisseleri analiz edilmiştir:

- KRDMA
- KRDMB
- KRDMD
- EREGL
- ISDMR
- KCAER
- YKSLN
- CEMTS
- CUSAN
- ERBOS

## ⚙️ Nasıl Çalıştırılır?

1. Gerekli kütüphaneleri yükleyin:
    ```bash
    pip install tensorflow scikit-learn matplotlib yfinance pandas
    ```

2. Python dosyasını çalıştırın:
    ```bash
    python tahmin_modeli.py
    ```

3. Kod, her hisse için hem LSTM hem de GRU ile tahmin yapacak ve sonuçları grafiklerle gösterecektir.

## 📌 Model Yapısı

### LSTM & GRU Yapıları:
- 3 katmanlı LSTM/GRU
- Dropout (%20)
- Dense çıkış katmanı
- `Adam` optimizer, `mean_squared_error` kayıp fonksiyonu

## 📈 Değerlendirme Metrikleri

Her model için aşağıdaki performans metrikleri hesaplanmaktadır:

- MSE (Mean Squared Error)
- MAE (Mean Absolute Error)
- RMSE (Root Mean Squared Error)
- R² (Determination Coefficient)
- Accuracy (İkili sınıflandırma üzerinden)
- F1 Score

## 💻 Donanım

Kod GPU destekliyse GPU üzerinden çalışır, değilse CPU kullanılır. TensorFlow GPU desteği varsa otomatik olarak algılanır.


## Lisans

Bu proje MIT lisansı ile lisanslanmıştır. Dilediğiniz gibi kullanabilir, değiştirebilir ve dağıtabilirsiniz. Ancak kaynak belirtilmelidir. Ayrıntılar için [LICENSE](LICENSE) dosyasına bakınız.


---

## ✉️ İletişim

📧 beyzadursun2002@gmail.com  
📍 GitHub: [@beyzadursun0](https://github.com/beyzadursun0)

