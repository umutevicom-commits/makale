# ChatGPT mucidinin yeni bir yapay zeka modeli geliştiricileri heyecanlandırıyor

ChatGPT, Diogo Almeida'nın kalbini kırdı.

Almeida, sohbet robotunun oluşturulmasına yardımcı olan ve daha sonra mevcut yapay zeka çağımızdan belki de en çok sorumlu olan model eğitim tekniği olan insan geri bildiriminden (RLHF) pekiştirmeli öğrenmeyi icat eden bir OpenAI araştırmacısıydı. Ancak yeteneklerine rağmen hayal kırıklığına uğradı.

TechCrunch'a konuşan Almeida, "Bir şişede yıldırımımız var ama yine de kullanışlı değil" dedi. "O zamandan beri bu sorunla mücadele ediyorum. Sonuca varmam biraz zaman aldı: Sorun şu ki, insan dilini optimize ediyoruz… Dört yıldır insan dilinde süper iyiyiz, ancak bilgisayarlar farklı bir dil konuştuğu için otomasyon için yararlı değil .”

İki yıl önce Almeida, bu sorunu çözmeye çalışan bir girişim olan TypeSafe AI'yı başlatmak için OpenAI'den ayrıldı. Bu hafta şirket, büyük bir dil modeli (LLM) olmayan yeni bir transformatör tabanlı model olan JEV'i piyasaya sürdü. Metin çıktısı vermez, bunun yerine olasılıklar veya şirketin “kalibre edilmiş kararlar” olarak adlandırdığı şeyler üretir.

Dilden kaçınmak birkaç şey yapar: Modeli inanılmaz derecede ucuz ve hızlı hale getirir ve kullanıcılar çıktıları önceden tanımladıkları için halüsinasyon göremez. Çıkış tokenleri ücretsizdir ve giriş tokenleri milyonla değil milyarla ölçülür.

Geliştiriciler ürüne büyük ilgi gösteriyor; şirket, talep çok yüksek olduğu için kullanıcılara API'sinden hizmet verme yeteneğini kısaca kaybetti. Jev en çok yazılım otomasyonu için yararlı görünmektedir. Şimdiye kadar, yazılım geliştiricileri bunu zekayı kodlarına dahil etmenin daha ucuz ve daha sağlam bir yolu olarak görüyorlar.

Örneğin, ajan altyapısı yapan bir şirket olan Vercel'de yazılım mühendisi olan Pranit Sharma, şirketinin OpenAI'nin ChatGPT Luna 5.6 'sını güvenlik komutlarını gözden geçirmek için bir sınıflandırıcı çalıştırmak için kullandığını söyledi. Vercel, OpenAI'nin Luna'sını Jev ile değiştirdiğinde, sonuçları beş ila 18 kat daha hızlı ve daha doğru bir şekilde elde etti.

Bir başka geliştirici, Bryo AI CTO Nikhil Mudholkar, Jev'i iş e - postalarını sınıflandırmak için Gemini'ye karşı test etti. Testinde İkizler biraz daha doğruydu, ancak 10 ila 20 kat daha pahalıydı. Mudholkar için daha ilginç olan Jev'in güven puanlarıydı — "gerçek bir olasılığı geri veren tek kişi o, bu da onu iş akışlarını otomatikleştirmek için ideal kılıyor !!"

Yeni model, belirli kullanım durumlarında LLM'lerin yerini almanın yanı sıra, yanlış davranışlara akıllı bir kontrol görevi görerek onları da artırabilir. Almeida, ajanları izlemek için ajan kullanmanın hızla pahalı hale gelebileceğini, ancak bunu yapmak için Jev kullanmanın mantıklı olduğunu savunuyor. Kullanıcıların LLM ajan izlerini izlemek ve jailbreak'leri önlemek için JEV'i konuşlandırdığını görüyor.

Açık kaynaklı model koşum takımı Pi'yi oluşturan Earendil'in CTO'su Armin Ronacher, "Günün sonunda, halüsinasyon sorununu biraz kullanıcıya devrediyor" dedi. "Kullanıcı, tamam, eğer bu sadece % 50 olasılıkla geri gelirse, belki de bu bir yazı tura ve ben bunu göz ardı ediyorum demek zorunda. Ama eğer % 95 ise, o zaman onunla bir şeyler yapabilirim ."

Ronacher, Jev için bir diğer potansiyel kullanımın model yönlendirmesi olduğunu söyledi. Belirli bir iş yükünün belirli bir model gerektirip gerektirmediğini tahmin etmek yararlı olacaktır, ancak iş için bir LLM kullanmak pahalı olacaktır. Jev'in düşük maliyeti ve hızı, bu tür gerçek zamanlı sıralamayı mümkün kılmaktadır.

Ve bu Almeida'nın umudu. Model, adını bir metanın düşen maliyetinin giderek daha fazla kullanılmasına nasıl yol açabileceğini açıklayan 19. yüzyıl ekonomisti William Stanley Jevons'tan almıştır. Bu durumda, düşen istihbarat maliyeti yaygınlaşmasına yol açmalıdır.

Almeida, "Ortaya çıkan ve dağıtılan bir şekilde her yerde akıllı yazılımlar olacağını düşünüyoruz... insanların şu anda oluşturmaya çalıştığı mega uygulamalar gibi bildiğinizden çok daha fazla internet gibi" dedi.

Almeida, dış gözlemcilerin açık ağırlıklı bir LLM'nin üzerine inşa edildiğinden şüphelendiği modelin mimarisi hakkında ağzı sıkı. Şirket, JEV'i akıl yürütmekten ziyade sezgiye odaklanan ve özellikle doğru göreve odaklanan bir "Birinci Sistem modeli" olarak adlandırıyor. Almeida, Jev'in "kalibre edilmiş kararlardan pekiştirmeli öğrenme" adını verdiği bir teknik kullanarak yalnızca sentetik veriler üzerinde eğitildiğini söylüyor.

TechCrunch'a verdiği demeçte, "Tüm verilerimizi yapacağımıza dair erken bir bahse girdik ve bu hayatımda yaptığım en iyi bahislerden biriydi — bence lansmanımızdan daha iyi, RLHF'den daha iyi" dedi. "[ Şirketimizin] yarısı, temelde istatistiksel olarak iyi anlaşılmış sentetik verilerin tüm bu alt alanına sahip bir laboratuvar ve şimdi bu benim hayatımın neşesi ."

Şimdilik, Jev bu tür bir model olarak tek başına duruyor, ancak Ronacher, faydası belirgin olduğu için rakiplerin ortaya çıkmasını bekliyor.

"Bunu birçok yönden daha önce görmeliydik, ancak muhtemelen LLM'ler çok ucuz ve sübvanse edildiğinden, çoğu zaman henüz yaratıcı olmak zorunda değilsiniz" dedi.

TypeSafe'in kendisi, yeni yöntemlerle modelin daha fazla sürümünü oluşturacaktır. TypeSafe'in bir sınır laboratuvarı olup olmadığı sorulduğunda Almeida, “sınır laboratuvarlarının ana ürünü korku veya aldatmacadır. Ana ürünümüzün zeka olmasını isterdim...[ama biz] sonsuz zenginliğe, bir dine, bir veri merkezinde Tanrı'yı inşa etmeye ya da bugünün olayı her neyse ona bahse girmek anlamında bir laboratuvar değiliz ."

---

## Görseller

![TypeSafe AI co-founders Erik Gafni, Sasha Sheng, and Diogo Almeida.](https://umutevicom-commits.github.io/makale/data/images/a-new-kind-of-ai-model-from-a-chatgpt-inventor-is-thrilling-developers/typesafe-ai.jpg)

![Görsel](https://umutevicom-commits.github.io/makale/data/images/a-new-kind-of-ai-model-from-a-chatgpt-inventor-is-thrilling-developers/Screenshot-2026-09-18-at-12_08_01-PM.png)
