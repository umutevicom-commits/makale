# Google'ın en son yapay zeka hava durumu modeli, şemsiyenizi unutmanız için hiçbir bahane sunmuyor

Google DeepMind ve Google Research'teki bilim insanları, bugün değişen atmosferimizi daha net gören ve davranışlarını daha sık tahmin eden hava tahmini için yeni bir yapay zeka modeli yayınladı.

WeatherNext 3, derin öğrenme teknikleriyle ortaya çıkan meteorolojideki deniz değişiminin son dalgası ve Google, kullanıcıların aramada, Google Haritalar'da ve İkizler'de gördüğü hava durumu bilgilerinin yanı sıra Google'ın bulut platformlarındaki kullanıcılara ve araştırmacılara sunulmaya başlanacağını söylüyor.

Google kıdemli personel mühendisi Samier Merchant, TechCrunch'a verdiği demeçte, "Bu, temel değişkenlerden bazılarının Google ürünlerinin çoğunu beslediği ve güçlendirdiği ilk sefer olacak" dedi.

Yeni model, startup Brightband tarafından oluşturulan yapay zeka tahminlerini karşılaştırmak için bir yardımcı program olan Operational WeatherBench'te test edilen önde gelen yarışmacılar arasında en doğru model olduğunu zaten kanıtladı. Sıcaklık, rüzgar hızı ve nem gibi metriklere bakar.

Google, Microsoft, Nvidia ve Avrupa Orta Menzilli Hava Tahmini Merkezi (ECMWF) tarafından oluşturulan diğer derin öğrenme modellerini geride bırakmanın yanı sıra, ABD Ulusal Hava Durumu servisi ve ECMWF'den gelen geleneksel tahminleri de geride bırakıyor.

Hava durumu tahminlerinin çoğu, havanın fiziğini tanımlamak için yazılmış matematiksel denklemler aracılığıyla zahmetli bir şekilde çalkalanan devlete ait süper bilgisayarlardan geliyor; bu sistemler son derece doğru hale gelmiş olsa da, pahalı ve nispeten yavaştır. ECMWF, 2018 'de bu sistemler tarafından üretilen yarım yüzyıldan fazla hava durumu verisini yayınladıktan sonra, derin öğrenme araştırmacıları, hükümet araçlarıyla karşılaştırılabilir doğrulukta ve çok daha hızlı tahminlerde bulunabilecek modeller geliştirmeye başladı.

DeepMind'ın personel araştırma bilim insanı yöneticisi Ferran Alet, "Hava kaotik ve çok küçük farklılıklar gerçekten kitlesel olarak tedirgin olmaya başlıyor...Makine öğrenimi, gerçekten çözdüğümüz sorunu hedef alıyor, bu da eksik bilgilerden ve sonlu hesaplamalardan yaklaşık gürültülü fizik ve bu nedenle birçok veriden örüntüler öğreniyor" dedi.

O zamandan beri, model yapıcılar yapay zeka tahmin modellerinin temel zayıflıklarını öne sürdüler: Gerçekten yararlı olandan daha geniş bir alanda (15 ila 25 kilometre kare) tahmin etme eğilimindedirler, yağmurla her zaman iyi değillerdir ve hala devlet kurumları tarafından üretilen biçimlendirilmiş veri kümelerine bağlıdırlar.

WeatherNext 3, üç görevi de üstlenir. TechCrunch'a konuşan araştırmacılar, kilit değişkenler hakkında 5 km çözünürlüğe kadar tahmin yürütebileceğini söyledi. Yağmurla ilgili değerlendirmeleri WeatherNext 2 'ye göre % 60 iyileşti ve artık her altı saatte bir standart tahmin yerine saatlik tahminler üretebiliyor.

Bu iyileştirmeler, tasarımcılar tarafından yapılan belirli seçimlerin sonucudur. WeatherNext 3, selefinden 2,4 kat daha fazla parametreye sahip daha büyük bir modeldir ve kod çözücü kafaları için hedefleri daha yararlı cevaplar verecek şekilde uyarlamaktadır. Hava durumu tahminlerinin çoğu 3B ızgarada ortalama metrik olarak çıkarken, DeepMind araştırmacıları modellerini siklon yollarını da görselleştirecek şekilde ayarlayarak şimdiden takdir topladı.

Bu sefer tasarımcılar, modeli tahminlerini belirli hava durumu veri istasyonlarına hedefleyecek şekilde de eğitti. Bu sadece daha ayrıntılı tahminler sunmak için değil, aynı zamanda çalışmalarını belirli, temel gerçek verilere göre değerlendirebilmek için de önemlidir.

Brightband'da atmosfer bilimcisi Daniel Rothenberg, "Birçok yapay zeka uygulamasıyla buradaki fikir, görevleri mümkün olduğunca uçtan uca yürütmeye çalışmak" dedi. "Bu modelin şimdi, örneğin Denver havaalanının hava istasyonunun saatlik bazda neyi ölçeceğini de tahmin ettiği bir yetenek eklemek, bu tahmin görevini çekirdeğe daha yakın bir yere bağlıyor ."

Model, saatlik bazda gerçek zamanlı olarak toplanan hava durumu uydu verilerini alabildiği için daha sık tahmin yapabiliyor. Yapay zeka modellerini hava durumu süper bilgisayarları tarafından üretilen analizlerden ziyade ham ampirik gözlemlerle beslemek daha doğru bir tahmin vaat ediyor, ancak modellerin biçimlendirilmemiş verilerle çalışmasını sağlamak teknik olarak hala zor.

Google, WeatherNext 3 'ün yüksek çözünürlüklü bir küresel tahmin için ham gözlemleri doğrudan birleştiren "ilk" yapay zeka modeli olduğunu söylüyor. Ancak yapay zeka girişimi WindBorne, modeli WeatherMesh 6' nın 2025 'in sonlarından bu yana hava balonları filosundan ve diğer kaynaklardan ham gözlemleri birleştirdiğini söylüyor. Bu konuda sorulan Google, tahminlerinin dünya genelinde daha yüksek çözünürlükte olduğuna dikkat çekti. Ne olursa olsun, her iki model de tahminleri gerçekleştirmek için hala ulusal hava durumu veri kümelerine güvenmektedir, bu nedenle gerçek doğrudan veri asimilasyonu için daha fazla çalışma gerekecektir.

LLM'ler dikkatin büyük kısmını alırken, meteorolojideki transformatör devrimi de aynı derecede önemli olmuştur. Avrupa ve ABD hava durumu ajansları, tahmin ürünlerinde zaten yapay zeka modellerini kullanıyor ve hızları ve düşük maliyetleri, yüksek kaliteli sensörlerin ve süper bilgisayarların maliyetinin doğru tahminleri ulaşılamaz hale getirdiği daha yoksul bölgelere ekonomik etki getirme sözü veriyor.

Bill Gates yakın zamanda yapay zeka destekli hava tahminlerini teknolojinin çok önemli bir faydası olarak gösterdi ve gelişmekte olan ülkelerde mahsul verimini artıran daha iyi tahminler yaptı. DeepMind araştırmacısı Alet, daha yüksek çözünürlüklü rüzgar, yağmur ve bulut örtüsü tahminlerinin yenilenebilir enerji projelerini daha güvenilir hale getirmek için yararlı olacağını söyledi.

Alet, "Günün sonunda, Google'ın kullanıcıya yararlı bilgiler sağlamakla ilgili olduğunu ve kullanıcıların aradıklarının çoğunun bir şekilde hava durumuyla ilgisi olduğunu düşünüyorum" dedi.

---

## Görseller

![Görsel](https://umutevicom-commits.github.io/makale/data/images/googles-latest-ai-weather-model-gives-you-no-excuse-to-forget-your-umbrella/2-Figure-How-WeatherNext-3-works.png)

![Görsel](https://umutevicom-commits.github.io/makale/data/images/googles-latest-ai-weather-model-gives-you-no-excuse-to-forget-your-umbrella/30-day-weather-champion.png)

![Görsel](https://umutevicom-commits.github.io/makale/data/images/googles-latest-ai-weather-model-gives-you-no-excuse-to-forget-your-umbrella/3-Figure-Surface-temperature-still-image-1.png)
