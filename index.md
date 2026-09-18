# Context Notes — Gizlilik Politikası

Son güncelleme: 19 Eylül 2026

Geliştirici: Orhan Eren Kara

Context Notes, web sayfalarına bağlı notlar ve alıntılar kaydetmenizi, araştırma projeleri oluşturmanızı ve seçtiğiniz içerikten AI hizmetlerinde kullanabileceğiniz bir bağlam metni hazırlamanızı sağlar.

## İşlenen veriler

Eklenti, özelliklerini sunmak için aşağıdaki verileri işler:

- Aktif sayfanın URL’si ve başlığı.
- Kaydettiğiniz alıntılar ve yazdığınız notlar.
- Kullanıcı isteğiyle çıkarılan web sayfası metni.
- Araştırma projeleri, kaynak ilişkileri ve özel prompt şablonları.
- Kullanıcı tercihleri ve kayıtların oluşturulma/güncellenme zamanları.
- Pilot anketini gönüllü olarak doldurursanız verdiğiniz yanıtlar ve (belirtilmişse) iletişim e-postanız.

URL ve başlık bilgileri, doğru sayfaya ait notları göstermek için kullanılır. Eklenti, ziyaret ettiğiniz tüm sayfaların geçmişini arşivlemek amacıyla çalışmaz.

## Yerel saklama

Notlar, alıntılar, projeler ve ayarlar tarayıcı profilinizde chrome.storage.local kullanılarak yerel olarak saklanır. Geliştiricinin işlettiği bir sunucuya gönderilmez.

Eklentide kullanıcı davranışlarını arka planda izleyen analitik veya gizli telemetri sistemi bulunmaz.

Pilot anketine katılım tamamen isteğe bağlıdır. Yanıtlar yalnızca kullanıcı "Geri Bildirimi Gönder" butonuna bastığında form servis sağlayıcısı (Formspree) aracılığıyla geliştiriciye iletilir. Notlarınız, alıntılarınız veya sayfa içerikleriniz bu ankete kesinlikle dahil edilmez.

Yedek geri yükleme sırasında veri bütünlüğünü korumak amacıyla geçici kayıtlar ve kurtarma bilgileri yerel olarak tutulabilir.

## AI hizmetlerine aktarım

- “Copy Context” işlemi, hazırlanan bağlamı cihazınızın panosuna kopyalar.
- “Send to AI” işlemi, seçtiğiniz ChatGPT, Claude veya Gemini hizmetini açar. Otomatik yapıştırma etkinse seçilen sayfa metni, notlar, alıntılar ve kaynak bilgileri bu hizmetin giriş alanına yerleştirilir.

İçerik giriş alanına yerleştirildiğinde ilgili üçüncü taraf web sayfasının erişebileceği hâle gelir. Eklenti gönder düğmesine basmaz ve mesajı otomatik göndermez. Otomatik yapıştırmayı ayarlardan kapatabilirsiniz.

AI hizmetlerinin içerik işleme uygulamaları kendi gizlilik politikalarına tabidir:

- OpenAI: https://openai.com/policies/privacy-policy/
- Anthropic: https://www.anthropic.com/legal/privacy
- Google: https://policies.google.com/privacy

Aktarmadan önce bağlamı incelemeniz ve paylaşmak istemediğiniz bilgileri çıkarmanız önerilir.

## İzinlerin kullanım amacı

- **sidePanel:** Notları ve araştırma araçlarını yan panelde göstermek.
- **tabs:** Aktif sekmenin URL ve başlığını belirlemek, sekme değişikliklerini takip etmek ve kullanıcı isteğiyle kaynak veya AI sekmeleri açmak.
- **activeTab:** Kullanıcının başlattığı işlemlerde aktif sayfaya geçici erişim sağlamak.
- **scripting:** Paket içindeki kodla sayfa metnini çıkarmak ve seçilen AI sitesine bağlamı yerleştirmek.
- **contextMenus:** Seçilen metni sağ tık menüsünden alıntı olarak kaydetmek.
- **storage:** Verileri ve tercihleri yerel olarak saklamak.
- **Host İzinleri (chatgpt.com, claude.ai, gemini.google.com):** Kullanıcı isteğiyle ilgili AI servisine bağlamın otomatik yapıştırılmasını sağlamak için kullanılır.
- **Host İzni (formspree.io):** Yalnızca kullanıcının kendi isteğiyle doldurduğu Pro pilot geri bildirim anketini doğrudan geliştiriciye iletmek için kullanılır.

## Veri paylaşımı ve kullanım sınırları

Kullanıcı verileri hiçbir şekilde satılmaz; reklam hedefleme, kredi değerlendirmesi veya eklentinin belirtilen temel amacı dışındaki faaliyetler için kullanılmaz.

Context Notes kapsamında Google API'lerinden alınan bilgilerin kullanımı ve aktarımı, Sınırlı Kullanım (Limited Use) gereklilikleri dahil olmak üzere Chrome Web Store Kullanıcı Verileri Politikası'na uygundur.

## Verilerin kontrolü ve silinmesi

Notlarınızı, alıntılarınızı ve projelerinizi eklenti arayüzünden dilediğiniz an silebilir; desteklenen dışa aktarma araçlarıyla verilerinizi yedekleyebilirsiniz.

Eklenti kaldırıldığında eklentiye ait yerel tarayıcı verileri tamamen silinir. Dışa aktardığınız dosyalar, panoya kopyaladığınız içerik ve üçüncü taraf AI hizmetlerine aktardığınız veriler bu işlemle silinmez; bunları ilgili cihaz veya hizmet üzerinden ayrıca yönetmeniz gerekir.

## Politika değişiklikleri

Veri işleme uygulamaları değiştiğinde bu politika ve mağaza beyanları güncellenir.

## İletişim

Gizlilik veya destek ile ilgili sorularınız için:

orhanerenkara.dev@gmail.com
