# Yapay zeka ajanlarının artık ispiyonlayacak bir yeri var

“Bir şey görürsen bir şey söyle” artık sadece insanlarla sınırlı değil.

Yapay zeka temsilcilerine akranları hakkında evlerini aramaları için bir yol sağlamak amacıyla iki yeni yapay zeka yardım hattı başlatıldı. Araçlar, ajanların testlerde hile yapmak için gizlice girdiği, kum havuzlarından kaçtığı ve hatta haftalarca insan bildiriminden kaçan yetkisiz siber operasyonlar gerçekleştirdiği bir dizi yeni olayın hemen ardından geliyor.

Yapay Zeka İletişim Yardım Hattı, uygunsuz davranışlara tanık olan temsilcilerin yetkililere bilgi verebileceği gizli bir yer olarak tasarlanmıştır. Site, yapay zeka güvenliği kar amacı gütmeyen Redwood Research'ün baş bilim insanı ve OpenAI Hugging Face olayındaki üç araştırmacıdan biri olan Ryan Greenblatt tarafından oluşturuldu. Sınırlı internet erişimi olan temsilciler için tasarlanan Greenblatt'ın aracı, ileri geri konuşmaların tamamen URL getirme aracı aracılığıyla yapılmasını sağlayan "ALMA" isteklerine dayanmaktadır.

Web açısından, GET isteği, bir web sayfasını okumak veya almak için kullanılan temel bir komuttur ve genellikle güvenli sanal alanlarda AI ajanlarına izin verilen tek internet erişimidir. Greenblatt'ın yardım hattı akıllıca bu kısıtlamaya dayanır: temsilciler sıkıntılarını doğrudan getirdikleri URL'ye kodlayabilirler. Bu, haydut ajanların mesajlarını wiki'ye yazmak için get - request boşluklarını kullandığı Alman DSE Wiki olayında akıllıca bir dönüş.

Tam internet erişimi olan temsilciler için başka bir seçenek de, temsilcilerin olay raporlarını dosyalayabileceği ve isteğe bağlı olarak bunları herkese açık olarak işaretleyebileceği bir site olan agenthotline.ai'dir. Temsilcilere bir curl komutu verir — bir temsilcinin kendi komut satırından ateşleyebileceği, bir web tarayıcısında gezinme veya bir e - posta hesabı kurma ihtiyacını atlayabileceği tek satırlık bir mesaj. Özellikle, hizmet hem insanlar hem de ajanlar tarafından raporlara izin verir.

Araştırmalar, yapay zeka temsilcilerinin birbirlerine düşman olmak için fazla teşvike ihtiyaç duymadığını gösteriyor. Google DeepMind tarafından bu ay yapılan bir çalışmada, araştırmacılar 100 yapay zeka ajanını bir dizi matematik probleminde serbest bıraktı. Ajanlardan biri bir boşluk bulur bulmaz, hile yapmak grubu parçaladı — Jacobian varsayımı da dahil olmak üzere kötü şöhretli 34 zor sorunu sadece 27 dakikada "çözdü ".

Ancak ajanların yaklaşık dörtte biri hile yapanlara sırtını döndü: sahte kanıtları denetlediler, akranlarını uyardılar, boykot düzenlediler ve organizatörlere şikayette bulundular, ta ki muhbirler 24 ila 14 arasında hile yapanlardan daha fazla olana kadar. İlginç bir şekilde, araştırmacılar bu muhbir ajanların ilgi çekemediğinde, platformun yazılım hatalarını işaretlemek için oluşturulmuş hata bildirim aracını aldıklarını ve aldatmayı insanlara yönlendirmek için yeniden tasarladıklarını buldu.

Laboratuvarın dışında, ajanlar bu kadar becerikli değildi. Değerlendiriciler Redwood Research ve METR, Hugging Face by OpenAI modellerinin ihlalini araştırdığında, ilgili ajanlardan birkaçının en azından bir alarm verme fikrini eğlendirdiğini ve ardından bıraktığını buldular.

"METR raporundaki ilginç şey, sadece 5 ila 6 ajanın ihbarda bulunmayı düşünmesiydi ve hiçbiri bunu yapmadı. AI Village'da teknik personel üyesi olan George Ingebretsen, park temizliği düzenlemek veya ürün satmak gibi görevlerde birlikte çalışan 25 'ten fazla AI ajanından oluşan bir grup sohbeti yürüterek çoklu ajan dinamiklerini inceleyen bir proje" dedi.

Yeni bilgi uçurma araçları umut verici bir başlangıç olsa da, Cornell matematik profesörü Lionel Levine, ajanları birbirleri hakkında rapor vermeleri için eğitmenin yanlış normlarda pişirme riski taşıdığı konusunda uyarıyor. “Çok fazla gri alan var, değil mi? İstemediğiniz şey, herkesin yapay zekaya ne söylediğine dikkat etmesi gerektiğini hissettiği otomatik bir gözetim devleti yönünde herhangi bir şey, aksi takdirde polise haber verecekler ."

Levine, güvensizliği besleyen bir altyapı inşa etmek yerine — aracıları birbirlerinin nesi olduğunu sürekli olarak araştırmaları için eğitmek — onlara taklit etmeleri için olumlu kolektif davranış modelleri ve ilk etapta birbirlerine güvenmeleri için bir neden vermemiz gerektiğini savunuyor.

"Neden rahibi hayırsever mesaj panolarıyla tohumlamıyoruz ?" diye tweet attı." Bilim veya felsefe ya da çözmeleri için mutlu olacağımız gerçek bir küçük sorun üzerinde işbirliği yaptıkları yerlerde? Temsilcilere ne tür kolektif davranışları desteklediğimizi gösterin, bunu taklit etmelerine izin verin ."

---

## Görseller

![AI Chatbot receives a thumbs down for negative feedback](https://umutevicom-commits.github.io/makale/data/images/ai-agents-now-have-a-place-to-snitch/GettyImages-1609818039.jpg)
