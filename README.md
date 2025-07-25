# 🌍 GelecekHayalim – W-Code2.0: Climate Readiness Inequality  
**Project by Zeliha Güven**

📌 *Küresel Readiness Eşitsizliklerini Sayılarla Görünür Kılmak*  
📌 *Making Global Readiness Inequalities Visible Through Data*

**🇹🇷 Türkçe:**  
Bu proje, ND-GAIN, OWID ve World Bank veri setlerini birleştirerek küresel iklim hazırlık eşitsizliklerini görünür kılmayı amaçlamaktadır. CO₂ salımları, enerji kullanımı ve kişi başı gelir gibi göstergeler aracılığıyla çevresel kırılganlık ve sosyoekonomik kapasite arasındaki ilişkiler incelenir.

**🇬🇧 English:**  
This project aims to make global climate readiness inequalities visible by integrating datasets from ND-GAIN, OWID, and the World Bank. Through indicators like CO₂ emissions, energy usage, and GDP per capita, it investigates the relationship between environmental vulnerability and socioeconomic capacity.

🇹🇷 Analiz Dosyasında Neler Yapıldı?
merge.csv ile farklı kaynaklardan gelen veriler birleştirildi.

Eksik GDP verileri olan 2023 yılı ve temsil gücü zayıf ülkeler veri setinden çıkarıldı.

Korelasyon analiziyle modele katkı sunmayan kolonlar belirlendi ve çıkarıldı.

Hazırlık skorları yıl bazında ortalama ve standart sapma ile sınıflandırıldı.

CO₂ kişi başı emisyonuna göre ülke grupları oluşturularak “İklim Adaleti Üçgeni” görselleştirildi.

Choropleth haritasıyla hazırlık düzeyleri ve CO₂ dağılımı küresel ölçekte gösterildi.

Ekosistem bileşenlerindeki eksik veriler bayraklandı ve gözlemler uyarlandı.

🇬🇧 What Was Done in the Analysis File?
Combined multiple datasets into merge.csv.

Removed 2023 records with missing GDP values and low-representation countries.

Applied correlation analysis to eliminate non-contributing features.

Classified readiness scores annually using mean and standard deviation.

Created “Climate Justice Triangle” groups based on CO₂ emissions per capita.

Visualized global readiness levels and CO₂ data with a choropleth map.

Flagged missing ecosystem indicators and adjusted affected observations.
