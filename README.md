# 🎧 Speech Emotion Analysis
## 📌 Proje Hakkında
* Bu proje, ses sinyallerinden duyguların analizi üzerine odaklanmaktadır.
* Amaç, ham ses verilerini işleyip çeşitli özellikler (MFCC, ZCR, RMS vb.) çıkararak duygulara göre farklılıklarını görselleştirmek ve ses işleme sürecine dair  bir çalışma sunmaktır.

## 🎯 Amaçlar
* Ses verilerini işleme ve görselleştirme tekniklerini öğrenmek
* Spektrogram ve Mel-Spektrogram analizleriyle frekans-temelli özellikleri incelemek
* MFCC gibi öznitelikler çıkararak duygular arasındaki farklılıkları gözlemlemek
* Veri bilimi yaklaşımıyla ses verilerini anlamlandırmak

## 🛠️ Kullanılan Teknolojiler ve Kütüphaneler
* Python 3.9+
* Librosa Ses işleme ve öznitelik çıkarma
* Matplotlib & Seaborn
* Görselleştirme
* NumPy, Pandas – Veri işleme
* tqdm – İşlem barı

## 📊 Uygulanan Adımlar
* Ses Yükleme & Ön İşleme
* Ham ses sinyallerinin yüklenmesi
* Sessiz bölümlerin temizlenmesi (trim işlemi)
* Dalga formu görselleştirmeleri
### Spektrogram Analizi
* STFT ile ayrıntılı spektrogram üretimi
* Mel-Spektrogram hesaplama ve görselleştirme
### Öznitelik Çıkarımı
* RMS (loudness proxy)
* ZCR (zero crossing rate)
* Spektral centroid & rolloff
* MFCC (Mel Frequency Cepstral Coefficients)

### Analiz & Görselleştirme
* Duygu dağılımı ve frekans analizi
* Boxplot / Violin plot ile akustik özelliklerin karşılaştırılması
* MFCC değerlerinin heatmap analizi
* Her duygu için ortalama Mel-Spektrogramların görselleştirilmesi
