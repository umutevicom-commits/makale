# Karar modelleri interneti doldururken Amazon kendi Jev klonunu piyasaya sürdü

Amazon Web Services, TypeSafe'in JEV'inden esinlenen açık kaynaklı bir karar modeli yayınladı ve yapay zeka geliştiricileri, sınır LLM'lerinden daha fazla bilgisayar otomasyonuna uygun istihbarat arayışına girdi.

OpenAI'nin benzer bir teklifi duyurduğu aynı hafta piyasaya sürülen Amazon'un Strands Decider 2B'si, önceden belirlenmiş seçenekler arasında sıralama yapmanın ve seçiminde ne kadar emin olduğunun bir ölçüsünü sunmanın yüksek hızlı, düşük maliyetli bir yoludur. Model tamamen açık kaynaklıdır, şu anda mevcuttur ve yerel olarak çalışacak kadar küçüktür.

Amazon'un seçkin mühendisi Marc Brooker, Jev'i gördükten ve böyle bir model üzerinde kendi görüşünü oluşturmaya çalıştıktan sonra projeyi ortaya attı. Homebrew projesi, Amazon mühendislerinin yapay zeka ajanlarını dağıtmak için yeni araçlar ve protokoller geliştiren bir kuruluş olan Strands Labs'tan bir teklif olarak temizledikleri ve piyasaya sürdükleri Jevbench sıralamasında kısa bir süre için en üst noktaya ulaştı.

Brooker, böyle bir araca duyulan ihtiyacın, aracı iş akışları her zaman tam özellikli bir LLM'nin kabiliyetini veya maliyetini gerektirmeyen AWS müşterileriyle yapılan görüşmelerde ortaya çıktığını söylüyor.

"Bu model sınıfına olan ilgimi asıl çeken şey, bir iş akışı adımı için mükemmel bir karar vermeleriydi: ‘Nerede olduğuma bağlı olarak burada yapmam gereken bir sonraki şey nedir?" "Brooker, TechCrunch'a verdiği demeçte, müşterilere" kapalı cevap alanı sayesinde güven puanları sayesinde daha güvenilir bir şekilde yapılandırılabilen bir iş akışı adımı sunduğunu ve daha düşük gecikme süresi, potansiyel olarak daha düşük maliyet sunduğunu "söyledi.

Diğer karar modelleri gibi, Strands Decider da bir LLM'nin "gövdesi" üzerine inşa edilmiştir, bu durumda Qwen3.5-2b, ancak metin üretmek yerine kalibre edilmiş seçenekler sunar. TypeSafe, modellerine ekonomist William Stanley Jevons'ın adını verdi. Jevons, bilgisayar zekası gibi bir şeyin düşen maliyetinin aslında talebini artırabileceği teorisine başvurmayı umuyor.

TypeSafe'in fikrini ortaya atmasından bu yana onlarca benzer modelin araştırmacılar tarafından üretilmiş olması büyük ilgiyi ortaya koyarken, ne kadar değerli olabilecekleri sorusunu da gündeme getiriyor. Brooker, zorluğun modelin zekasından ödün vermeden hızlı karar vermesini optimize etmek olacağını öne sürüyor.

TechCrunch'a "Farklı dilleri anlama, sahip olduğu bilgiye sahip olma konusundaki performansını düşürmeden, bu tür görevlerde doğruluk ve kalibrasyon konusundaki performansını zorlamak istediğiniz çok dikkatli bir denge var, bu da onu genel amaçlı ve ilginç ve kullanışlı kılıyor" dedi.

Yine de, sınır laboratuvarlarının alana hakim olmasını beklemiyor, özellikle de daha küçük pazarlarda ilginç bir şey inşa etmenin maliyeti yüzlerce veya binlerce dolar olduğundan.

TypeSafe yöneticileri ise başlarını öne eğdiklerini ve gelecek modellerini geliştirdiklerini söylüyor.

CEO ve kurucusu Diogo Almeida TechCrunch'a verdiği demeçte, "İnsanların bunun altına hücum olduğunu düşündüğünü anlıyorum, ancak modelleri gerçekten akıllı hale getirmenin zorluğunu hafife alıyor olabilirler" dedi ve şimdilik şirketi için gerçek bir rekabetin ortaya çıktığını görmediğini söyledi.

"Mevcut grup, istihbaratı kullanışlı hale getirmeye derinden adanmış bir ekipten ziyade havalı bir mimari uygulamak isteyen ML insanları gibi görünüyor ."

---

## Görseller

![The economist William Stanley Jevons.](https://umutevicom-commits.github.io/makale/data/images/amazon-releases-its-own-jev-clone-as-decision-models-flood-the-web/William_Stanley_Jevons_portrait_extract.jpg)
