# osrn | Solar Ağı Blok Üreticisi Önerisi
Testnet'in ilk aşamalarından beri Solar Blok Üreticisiyim. Telekom, Medya ve IoT alanlarında uzun yıllara dayanan Dijital Pazarlama, İş Geliştirme ve Mühendislik deneyimimle projeye katıldım. Bir teknoloji meraklısı olarak, blokzincir gibi yeni nesil teknolojilere doğal bir ilgim var ve 25 yılı aşkın bir süredir de hem profesyonel hem de kişisel projelerde *nix tabanlı sistemler ve sunucular ile çalıştım, kurulum ve bakımını üstlendim.

> *This proposal is [available here in English](https://delegates.solar.org/delegates/osrn).*

## Solar Network'de şu ana kadar,

- [x] Solar Blokzinciri ile entegre çevrimiçi çok oyunculu bir Tavla oyununu Blok Üreticis mtaylan ile beraber geliştirerek $SXP kullanımını özendirmek ve yakıma katkıda bulunmayı amaçladık. $SXP harcayın, kazanın, yakın, eğlenin! Tavla'ya buyrun: https://tavla.xyz/
- [x] Oy ödüllerinin hesaplanması ve dağıtımı için [Lazy Ledger](https://github.com/osrn/lazy-ledger) yazılımını geliştirdim. Bu yazılım ödülleri sürekli oy değiştiren botlardan koruma mekanizması da içermektedir.
- [x] Python SDK Crypto API (>3.0.0) dokumantasyon ve örneklerini güncelledim
- [x] Sunucuları monitor eden ve sağlık durumunu anlık mesaj ile bildiren [Lazy Delegate](https://github.com/osrn/lazy-delegate), uygulamasını yazdım. (Piton tabanlı bu uygulamayı yazarken Blok Üreticisi mtaylan'ın daha önce yayınladığı [SOLAR NODE MONITOR](https://github.com/mtaylan/SOLAR_NODE_Monitor_Discord) scriptindeki gözlem noktaları ve metodları temel aldım.)
- [x] Solar Desktop Cüzdan kullanımı, swap ve oylama sürecini [Türkçe](https://youtu.be/WA38JbE3MlE) ve [İngilizce](https://youtu.be/W4qAOb50Pcw) olarak anlatan videolar yayınladım, Telegram ve Discord gruplarında yatırımcıların soru ve sorunlarında destek oldum.
- [x] Proje yol haritası gibi bilgileri sade ve görsel olarak anlatan [Türkçe](https://osrn.github.io/solar/solar-roadmap-2022-infogx-tr.jpg) ve [İngilizce](https://osrn.github.io/solar/solar-roadmap-2022-infogx-en.jpg) infografikler yayınladım.
- [x] SXP swap hareketini destekledim.
- [x] Solar Art Contest, SXP Quiz, D53 Spooktacular Halloween gibi etkinliklere sponsor oldum.
- [x] Bir çok blok üreticisi tarafından oy verenlerin ödüllerinin hesaplanması ve dağıtımında kullanılan [Galperins4/True Block Weight](https://github.com/galperins4/core2_tbw) algoritması kodlamasına düzenli olarak katkıda bulundum ve kurulumu için diğer blok üreticilerine destek oldum. Katkılarıma göz atmak için [GitHub alanımı ziyaret edin](https://github.com/osrn/core2_tbw)
- bazı uygulamalara Türkçe dil desteği eklenmesine destek oldum.
- [x] Telegram'da Solar Network Türkiye 🇹🇷 topluluğunun düzenlediği AMA oturumuna katıldım. Etkinliğin Türkçe dökümüne [bu linkten](https://t.me/solarnetwork_tr/17902), İngilizce dökümüne ise [bu linkten](https://youtu.be/howzWfVJUgA) ulaşabilirsiniz.
- [x] SXP ve Solar Ağını profesyonel iş ağımda tanıtarak, bir ticari firmanın Solar Ağında entegrasyon kararı almasını sağladım. Detayları [Yol Haritası](#yol-haritası) bölümünde bulabilirsiniz.
- [x] Hem Mainnet hem de Devnet'te birden fazla node çalıştırdım; aktif olarak geliştirme ve test çalışmalarına katıldım.

<br>

# Blok Üreticisi önergesi
Bir blok üreticisi olarak asıl görevim **Solar Ağını çalışır durumda tutmak için yüksek standartlı nodlar çalıştırmak ve sürdürmek**. Buna ek olarak deneyimimi şu amaçlarla kullanacağım:
- Yardımcı programlar ve araçlar geliştirmek/katkıda bulunmak
- Yeni uygulamaların, modüllerin ve güncellemelerin test edilmesine destek olmak
- Kayıt defteri tutulması ve oy veren ödül paylaşımının sürekliliğini sağlamak için acil durumda devreye girebilecek bir yedek nodu aktif tutmak
- Geliştirme ve test işlemleri için Testnet'te aktif nodlar bulundurmak
- Bilgi ve belgelerin (Türkçe'ye) çevirilmesi
- Destek taleplerine yanıt vermek ve Solar'ın benimsenmesine yardımcı olmak için gruplarda etkin olarak bulunmak
- Solar'ı profesyonel iş ağımda tanıtarak SXP ve Solar Ağını kullanan projeler geliştirilmesi için cesaretlendirmek ve destek olmak. Her yeni proje SXP talebi yaratmak ve ağın kullanımını artırmakta destek olacaktır.

## Ödül paylaşımı
Ödüllerin **%60**'ını kendi geliştirdiğim ve ödülleri sürekli oy değiştiren botlardan koruma mekanizması içeren ödül dağıtım yazılımıyla dağıtacağım.
- Ödüller 24 saatte bir ve otomatik olarak paylaşılacak
- Bir ödül kazanım alt limiti yok - herkese günlük ödeme yapılacak
- Bir minimum SXP tutarı yok - dileyen herkes dilediği miktar ile oylayabilir
- Bir maximum SXP tutarı yok

 Ödül ve paylaşımları takip etmek için [https://solar.osrn.network](https://solar.osrn.network) adresinde bir kontrol panel ~mevcut~ >2022-09-12 dan itibaren bakımda.

<br>

## Yol Haritası
**(*)** Tavla yeni özellik: turnuva modu.

**(*)** Ödül dağıtım uygulaması ve Tavla'nın Core 5.0 için uyarlanması.

**(*)** Şubat ayında bir **Mikro Mobilite Kentsel Ulaşım girişimiyle** 4. çeyrekte duyurusunu yapacakları yeni projelerinde **SXP ile ödeme kabul etmeleri** ve yine aynı proje kapsamında çıkarmak istedikleri **NFT varlıklarını  Solar Ağında yayınlamalarına** imkan sağlamak üzere bir prensip anlaşması yaptık. Bu projeyi **[Blok Üreticisi mtaylan](https://delegates.solar.org/sxp/delegates/mtaylan)** ile birlikte yürüteceğiz. Bu konuda detaylı bilgi ve planları, firmanın pazarlama ve duyuru planlarına paralel olarak paylaşıyor olacağım.

- Güncelleme 1: https://twitter.com/osrnnetwork/status/1520123320401862657?s=20&t=FcdMpM7uvs0djlVJcfEPMw

<br>

---
**Oy ve desteğinizi almaktan mutluluk duyacağım.**

Herhangi bir soru veya fikir için iletişime geçmekten çekinmeyin.

Discord [osrn#5120](https://discordapp.com/users/934889170139222077)<br>
Telegram [@osrnx](https://t.me/osrnx)<br>
Twitter [@osrnnetwork](https://twitter.com/osrnnetwork)
