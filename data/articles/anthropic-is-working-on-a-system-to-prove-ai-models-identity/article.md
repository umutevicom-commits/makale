# Anthropic, yapay zeka modellerinin kimliğini kanıtlamak için bir sistem üzerinde çalışıyor

Salı günü yayımlanan bir blog gönderisine göre Anthropic, hangi yapay zeka modelinin belirli bir çıktı ürettiğini doğrulamak için açık kaynaklı bir sistem üzerinde çalışıyor. FlashProve adı verilen sistem, araştırmacıların "kanıtlanabilir çıkarım" dediği şeyi sağlamak için inşa edilmiştir — belirli bir çıktının belirli bir modelden geldiğinin kriptografik bir kanıtı, esasen matematiksel bir garantisi. Bu, kullanıcıların aldıkları cevabın gerçekten kullandıklarını düşündükleri modelden geldiğini onaylamalarını sağlamak içindir.

Alıcıların bir mesajın gerçekten iddia edilen göndericisinden geldiğini doğrulamasına izin veren kriptografik e - posta imzalarına benzer şekilde, FlashProve, dolandırıcı modeli oluşturan ve çalıştıran laboratuvar olsa bile, bir modeli başka bir model olarak gizlemeye çalışan dolandırıcılara karşı sağlam olacaktır. Özellikle araştırmacılar, sistemin bir yapay zeka şirketinin maliyetleri düşürmek için daha ucuz bir modelle veya performans sonuçlarını şişirmek için daha pahalı bir modelle gizlice yer değiştirmesini önlemek için kullanılabileceğini belirtiyor.

FlashProve, belirli bir görevin gelişmiş bir model tarafından yapıldığına dair üçüncü tarafların iddialarını doğrulamak için de kullanılabilir. Araştırmacılar, "Bir geliştirici, yazılım kütüphanesinin bir sınır siber güvenlik modeli tarafından güvenlik açıklarına karşı tarandığını iddia edebilir veya bir şirket, iş planına uygun bir model tarafından izin verildiğini iddia edebilir" diye yazıyor. "Bir kullanıcı bu iddiaları nasıl doğrulayabilir ?"

Sistemin çalışması için yapay zeka laboratuvarlarının piyasaya sürdükleri her modelin daha sonra belirli çıktılarla eşleştirilebilecek ve kriptografik olarak doğrulanabilecek bir "parmak izi" yayınlamasını gerektiriyor. En önemlisi, parmak izleri bir modelin ağırlıklarını, nasıl davrandığını tanımlayan dahili sayıları ve Anthropic ve OpenAI gibi hangi kapalı model üreticilerinin gizli tuttuğunu ortaya çıkarmaz. Bu, laboratuvarların en değerli varlıklarından vazgeçmeden parmak izlerini yayınlayabileceği ve sistemin ticari modellerle de çalışmasını sağlayabileceği anlamına geliyor. Sistem ayrıca hafif olacak şekilde tasarlanmıştır, bu nedenle doğrulama yerel bir cihazda gerçekleştirilebilir.

Duyurunun bir parçası olarak araştırmacılar, GitHub'da açık kaynak lisansı altında kamuya açık olan sistemin çeşitli unsurları için ayrıntılı bir teknik şartname ve çalışma kodu yayınladı. Sistemdeki araştırmalar devam ediyor ve Anthropic veya başka bir laboratuvara yerleştirme planı yok.

Araştırmacılar duyuru gönderisinde, "Bu araştırma gönderisi, tamamlanmış bir araştırma gündemini değil, ara ilerlemeyi paylaşmayı amaçlıyor" diye açıklıyor. "Bunu, başkalarının yaptığımız şeye bakması, kabul etmesi ve iyileştirmesi hedefiyle açıkça paylaşıyoruz ."

---

## Görseller

![The Claude logo is displayed on a smartphone screen.](https://umutevicom-commits.github.io/makale/data/images/anthropic-is-working-on-a-system-to-prove-ai-models-identity/GettyImages-2294192768.jpg)
