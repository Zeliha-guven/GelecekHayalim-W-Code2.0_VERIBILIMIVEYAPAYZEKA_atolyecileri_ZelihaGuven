🌍 GelecekHayalim – W-Code2.0: Climate Readiness Inequality
Project by Zeliha Güven

📌 Küresel Readiness Eşitsizliklerini Sayılarla Görünür Kılmak 📌 Making Global Readiness Inequalities Visible Through Data

🇹🇷 Türkçe Açıklama
Bu proje, ND-GAIN, OWID ve World Bank veri setlerini birleştirerek küresel iklim hazırlık eşitsizliklerini görünür kılmayı hedeflemektedir. Kişi başı CO₂ salımı, enerji tüketimi ve kişi başı gelir gibi göstergeler kullanılarak çevresel kırılganlık ve sosyoekonomik kapasite arasındaki eşitsizlikler analiz edilmiştir.

🔍 Veri Hazırlama ve Temizleme
2023 yılı ve eksik GDP verileri olan ülkeler çıkarıldı.

Korelasyon analizi ile düşük etkili değişkenler temizlendi.

Hazırlık skorları yıl bazlı sınıflandırıldı.

Eksik veriler XGBoost regresyon ile tahmin edildi.

Özellikle sağlık, yönetişim, ekosistem gibi bileşenlere odaklanıldı.

🗺️ Görselleştirme ve Modelleme
Choropleth haritalarla küresel hazırlık ve CO₂ dağılımı görselleştirildi.

CO₂ kişi başı salım ve hazırlık skoruna göre “İklim Adaleti Üçgeni” oluşturuldu.

Regresyon ve XGBoost modelleri RMSE ve R² ile değerlendirildi.

Öne çıkan değişkenler: kişi başı gelir, sağlık, ekosistem etkisi.

📌 Politika Önerileri
Doğa temelli çözümler

Yenilenebilir enerjiye geçiş

Topluluk odaklı uyum stratejileri

Açık veri ve uluslararası işbirliği

🇬🇧 English Description
This project aims to make global climate readiness inequalities visible by integrating datasets from ND-GAIN, OWID, and the World Bank. Indicators such as CO₂ emissions per capita, energy usage, and GDP per capita are used to analyze the imbalance between environmental vulnerability and socioeconomic resilience.

🔍 Data Preparation and Cleaning
Removed 2023 entries and countries with missing GDP data.

Applied correlation analysis to filter out low-impact variables.

Classified readiness scores annually using statistical thresholds.

Used XGBoost regression to impute missing values in health, governance, ecosystems, etc.

Focused on key readiness components for modeling.

🗺️ Visualization and Modeling
Created choropleth maps to visualize global readiness and CO₂ distribution.

Built the “Climate Justice Triangle” based on per capita CO₂ and readiness scores.

Evaluated regression and XGBoost models with RMSE and R² metrics.

Key features driving predictions: GDP per capita, health, ecological exposure.

📌 Policy Suggestions
Nature-based climate adaptation

Transition to renewable energy

Community-centered resilience models

Open data and fair international cooperation
