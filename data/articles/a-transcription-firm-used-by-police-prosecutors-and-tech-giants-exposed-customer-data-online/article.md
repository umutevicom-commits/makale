# Polis, savcılar ve teknoloji devleri tarafından kullanılan bir transkripsiyon şirketi, müşteri verilerini internette ifşa etti

Emniyet teşkilatlarına, devlet dairelerine ve Silikon Vadisi'deki teknoloji devlerine hizmet veren bir transkripsiyon şirketi, müşteri transkripsiyonları ve bunların kaynak materyalleri de dâhil olmak üzere çok sayıda dahili veriyi internette açıkta bıraktıktan sonra bir güvenlik açığını çözüme kavuşturdu.

San Francisco merkezli Tigerfish'te yaşanan veri güvenliği ihlali, polis sorgularının dökümlerini, vücut kamerası görüntülerini ve müşterilerin işlenmemiş ses ve video kayıtlarını ifşa etmiştir. Açığa çıkan veriler arasında şirketin polis teşkilatları ve savcılıklar da dâhil olmak üzere müşterilerinin faturaları da yer alıyordu.

Verileri bulan iyi niyetli güvenlik araştırmacısı Anurag Sen'e göre dosyalar, Amazon tarafından barındırılan (S3) bir bulut sunucusunda yer alıyordu. Bu sunucu açık bir şekilde listelenmişti ve tahmin etmesi kolay bir web adresi üzerinden herkes tarafından erişilebiliyordu. Yani parola gerekmiyordu.

Bu güvenlik açığı, özellikle yapay zekânın şirketleri ve verilerini riske atabilecek zayıf noktaları ortaya çıkarmayı kolaylaştırdığı bir dönemde, basit hataların veya yanlış yapılandırmaların hassas bilgilerin çevrim içi olarak ifşa edilmesine nasıl yol açabileceğini gözler önüne sermektedir.

Sen, ifşa edilen verileri Ekim ayında internette keşfetti ve şirketi bu konuda uyardı ancak ondan bir yanıt alamadı. Sen daha sonra, olayı çözüme kavuşturulması için şirkete bildirmek amacıyla TechCrunch'a ayrıntılı bilgi verdi.

30 yaşındaki Sen, TechCrunch'a yabancı değil. Son on yıldır, şirketleri ve kuruluşları bilgilerinin internete açık olduğu konusunda bilgilendirmek amacıyla çevrim içi olarak erişime açık hâle getirilmiş hassas veri kümelerini aramaktadır. Birçok güvenlik araştırmacısı gibi onun da çabalarının büyük bir kısmı interneti güvence altına alma görevi tarafından yönlendiriliyor ve o, çalışmalarını "ücretsiz bir hava trafik kontrolörü" olarak tanımlıyor.

Sen, Endonezya'daki ada evinden ABD ordusunun gizli e-postalarının Savunma Bakanlığı'nın bölümlere ayrılmış bulut sunucusundan sızdığını, veri tabanlarının tonlarca müşteri kaydını ifşa ettiğini, bir ülkenin ulusal araç plakası izleme sisteminin iç işleyişini ve kamu sistemlerinin yanlışlıkla dünyanın dört bir yanındaki insanların çevrim içi hesaplarına giriş yapmak için kullandıkları SMS kodları akışlarını gönderdiğini ortaya çıkardı.

Sen'in genellikle son derece gizli bilgileri internette bulma eğilimi göz önüne alındığında, sızıntının ve verilerin kaynağını doğruladık ve Tigerfish ile iletişime geçtik.

İletişim kurulduktan kısa bir süre sonra Tigerfish, açıkta kalan S3 bulut kovasını güvence altına aldı.

Tigerfish Başkanı Adam Goldberg bir e-postada, "Belirlediğiniz depolama alanına tüm genel erişimi, dizin listeleri ve tek tek dosyalar dâhil olmak üzere engelledik." dedi. "Ayrıca diğer tüm S3 klasörlerimizin de herkese açık erişime kapatıldığını doğruladık."

Goldberg, "Depolama güvenliğimizi daha geniş kapsamlı bir şekilde gözden geçirmeye ve güçlendirmeye devam ediyoruz." diye ekledi.

Şirket, Sen'in veri sızıntısını açıklayan e-postasının spam filtresine takıldığını söyledi.

Şirketin müşterilerini bilgilendirip bilgilendirmediği belirsiz. Tigerfish, gönderilen takip e-postasına yanıt vermedi.

Açığa çıkan veri kümelerinin keşfi, şimdiye kadar Sen'in siber güvenlik kariyerinin ilk döneminin büyük bir kısmını kaplamıştır. Çevrim içi ortamda korunmasız bırakılmaması gereken veri tabanlarını, bulut depolama alanlarını veya diğer hassas bilgileri tespit etmek için otomatik tarayıcıları ve özel arama motorlarını kullanarak her gün interneti tarıyor.

Modern internetin mutlak güven üzerine kurulu olduğunu ve dünyanın verilerinin güvende tutulduğu düşüncesiyle işlediğini söyledi. Ancak bulgularının, internetin perde arkasında ne kadar "kırılgan" olduğunun gerçekliğini nasıl ortaya koyduğunu anlattı.

Son zamanlarda yapay zekânın insanların güvenlik açıklarını keşfetme kabiliyetini nasıl hızlandırdığına odaklanılmasına rağmen Sen, tespit ettiği veri sızıntılarının ve ifşalarının çoğunun temel insan hatalarına dayandığını söylüyor.

"Bir mühendisin cuma günü bir test bulut veritabanını devreye sokması, bir API'yi test etmek için kimlik doğrulamasını devre dışı bırakması ve hafta sonuna girmeden önce kapıyı kapatmayı unutması" sadece bir örnekti, diye anlatıyor.

Sen'in yıllar içinde elde ettiği bulgular, tıpkı vibe-coding ve yapay zekâ tarafından oluşturulan geliştirmenin web'de konuşlandırılan güvenli olmayan ve kontrol edilmemiş kodlar nedeniyle yeni güvenlik sorunları yaratması gibi, bu tür güvenlik hatalarının neden olduğu devam eden sorunları da gözler önüne sermektedir.

Amazon'un S3 klasörlerini açık ve çok adımlı uyarılar olmadan herkese açık hâle getirmeyi zorlaştırmak için son zamanlarda gösterdiği çabalara benzer şekilde, Lovable ve Supabase gibi daha yeni vibe-coding platformları da kullanıcı hatalarını önlemek için platformlarında değişiklikler yapmıştır.

Sen, "Herkes genellikle gizemli hacker'lardan korkar." diyor. Ancak gerçek krizin, hassas sistemleri ve veri tabanlarını "şifre olmadan halka açık internete tamamen açık" bırakmak olduğunu savunuyor.

---

## Görseller

![Paper Craft Pixel Mosaic Covering a Yellow Speech Bubble on Gray Background Front View, Censorship Concept.](https://umutevicom-commits.github.io/makale/data/images/a-transcription-firm-used-by-police-prosecutors-and-tech-giants-exposed-customer-data-online/GettyImages-2150052525.jpg)
