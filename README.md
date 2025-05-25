# ML_PROJECT
 Craigslist Araç Fiyat Tahmin Projesi
 
 Proje Amacı
 
Bu projenin amacı, ikinci el araçların temel özelliklerine bakarak tahmini satış fiyatlarını tahmin etmektir. Veri seti, Craigslist'te yayımlanmış araç ilanlarından alınmış olup çeşitli marka, model, kilometre, üretim yılı gibi birçok özelliği barındırmaktadır.

 Çözülen Problem
 
Veri seti üzerinde bir regresyon problemi ele alınmıştır. Amaç, aracın üretim yılı, kilometresi, durumu, yakıt türü, vites tipi gibi özelliklerine bakarak aracın fiyatını tahmin etmek ve böylece hem alıcıların hem de satıcıların fiyat konusunda daha bilinçli kararlar almasını sağlamaktır.

 Kullanılan Algoritmalar
 
Projede iki farklı denetimli öğrenme algoritması uygulanmıştır:

DecisionTreeRegressor


RandomForestRegressor  (en iyi sonuç veren model)


Bu modellerin parametreleri, GridSearchCV ile optimize edilmiş ve en iyi performans veren yapı seçilmiştir. Model başarısı için MSE (Mean Squared Error), RMSE (Root Mean Squared Error) ve MAE (Mean Absolute Error) metrikleri kullanılmıştır.


 Gerçek Hayattaki Katkısı
 
Bu tarz bir fiyat tahmin sistemi:

Araç satın almak isteyen kullanıcıların, ilanlarda sunulan fiyatın uygun olup olmadığını anlamasına yardımcı olabilir.

Araç satmak isteyen kullanıcıların, aracını ne kadardan satışa koyması gerektiğini tahmin edebilmesine yardımcı olur.

Galeriler veya ikinci el satış platformları için fiyat öneri motoru olarak kullanılabilir.

Proje Nasıl Geliştirilebilir?

Daha gelişmiş modeller (XGBoost, LightGBM gibi GPU destekli modeller) ile daha yüksek doğruluk sağlanabilir.

Görseller (araç fotoğrafları) entegre edilerek multimodal bir model oluşturulabilir.

Aracın konumu (şehir, eyalet) gibi konumsal özellikler eklenerek fiyat tahminleri daha bölgesel hale getirilebilir.

Modelin tahmin sonuçlarını web tabanlı bir arayüzle gösteren küçük bir demo sayfası geliştirilebilir (örneğin React + Flask).

Kullanılan Kütüphaneler

pandas, numpy – veri işleme

seaborn, matplotlib – görselleştirme

scikit-learn – modelleme, regresyon, GridSearch

Kaggle Notebook Linki:

https://www.kaggle.com/code/furkanpikin/ml-project3




