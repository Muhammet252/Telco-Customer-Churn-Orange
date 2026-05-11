📊 Telco Müşteri Terk (Churn) Analizi – Orange Data Mining

Bu proje, bir telekomünikasyon şirketindeki müşteri kaybını (churn) tahmin etmek ve müşteri davranışlarını analiz etmek amacıyla Orange Data Mining platformu kullanılarak geliştirilmiştir. Proje kapsamında veri ön işleme, sınıflandırma modellerinin karşılaştırılması ve müşteri segmentasyonu analizleri yapılmıştır.

-------------------------------------------------------------------------------------------------

🚀 Proje Özeti

Müşteri terki (churn), bir işletme için en büyük maliyet kalemlerinden biridir. Bu çalışmada:

Eksik veriler tamamlanmış ve veri seti analiz için normalize edilmiştir.

Lojistik Regresyon, Random Forest ve Karar Ağaçları (Tree) modelleri eğitilmiştir.

Modellerin başarı oranları AUC, CA ve F1 skorları üzerinden kıyaslanmıştır.

En riskli müşteri profilleri belirlenerek stratejik öneriler sunulmuştur.

-------------------------------------------------------------------------------------------------
🛠 Akış Şeması (Workflow)

Projenin Orange üzerindeki tam akış şeması aşağıdadır:

<img width="1440" height="743" alt="Ekran görüntüsü 2026-05-11 203625" src="https://github.com/user-attachments/assets/436d171b-8b2c-41ab-898d-6e64dfce747d" />

-------------------------------------------------------------------------------------------------

📈 Model Performans Karşılaştırması

Modeller 5-fold Cross-Validation yöntemiyle test edilmiş ve aşağıdaki sonuçlar elde edilmiştir:

<img width="413" height="201" alt="Ekran görüntüsü 2026-05-11 204637" src="https://github.com/user-attachments/assets/17c40059-1173-4bb1-91c7-fe34b0932b28" />

-------------------------------------------------------------------------------------------------

🔍 Temel Bulgular ve Teknik Yorumlar

1. En Riskli Sözleşme Tipleri
Dağılım analizi sonuçlarına göre, aylık (Month-to-month) sözleşmeye sahip müşteriler, yıllık taahhütleri olan segmentlere kıyasla istatistiksel olarak anlamlı derecede daha yüksek bir terk (churn) hacmi sergilemektedir. Bu durum, düşük geçiş maliyetlerinin müşteri sadakatini negatif etkilediğini göstermektedir.

<img width="1214" height="791" alt="Ekran görüntüsü 2026-05-11 153449" src="https://github.com/user-attachments/assets/e207d184-30ec-4bd3-8d63-49d51dd69769" />

-------------------------------------------------------------------------------------------------

2. En Riskli Müşteri Profili
   
Tree Viewer analizi sonucunda elde edilen verilere göre şirket için en yüksek riskli müşteri profili; aylık (Month-to-month) sözleşmeye sahip, şirket bünyesinde 6 aydan daha az süredir bulunan ve Fiber Optik internet hizmeti kullanan kullanıcılardır.

<img width="1055" height="726" alt="Ekran görüntüsü 2026-05-11 204133" src="https://github.com/user-attachments/assets/77aee23c-8d15-45c1-a65f-2bc572fd850e" />

-------------------------------------------------------------------------------------------------

📁 Proje Dosyaları

telco_churn_analysis.ows: Orange projesinin ana dosyası.

dataset.csv: Analizde kullanılan veri seti (Eğer açıksa ekleyin).

README.md: Proje dökümantasyonu.

-------------------------------------------------------------------------------------------------

⚙️ Nasıl Çalıştırılır?

Bilgisayarınıza Orange Data Mining uygulamasını indirin.

Bu depodaki .ows dosyasını indirin.

Orange uygulamasını açın ve File > Open yoluyla dosyayı seçin.

(Opsiyonel) Veri dosyası yolu hata verirse, File widget'ına tıklayarak ekteki veri setini manuel olarak seçin.


Hazırlayan: Muhammet Hanifi Yıldırım - Karadeniz Teknik Üniversitesi, Bilgisayar Programcılığı


