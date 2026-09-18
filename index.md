# Context Notes — Gizlilik Politikası

Son güncelleme: 18 Eylül 2026

Geliştirici: Orhan Eren Kara

Context Notes, web sayfalarına bağlı notlar ve alıntılar kaydetmenizi, araştırma projeleri oluşturmanızı ve seçtiğiniz içerikten AI hizmetlerinde kullanabileceğiniz bir bağlam metni hazırlamanızı sağlar.

## İşlenen veriler

Eklenti, özelliklerini sunmak için aşağıdaki verileri işler:

- Aktif sayfanın URL’si ve başlığı.
- Kaydettiğiniz alıntılar ve yazdığınız notlar.
- Kullanıcı isteğiyle çıkarılan web sayfası metni.
- Araştırma projeleri, kaynak ilişkileri ve özel prompt şablonları.
- Kullanıcı tercihleri ve kayıtların oluşturulma/güncellenme zamanları.
- Pilot anketini doldurursanız verdiğiniz yanıtlar.

URL ve başlık bilgileri, doğru sayfaya ait notları göstermek için kullanılır. Eklenti, ziyaret ettiğiniz tüm sayfaların geçmişini arşivlemek amacıyla çalışmaz.

## Yerel saklama

Notlar, alıntılar, projeler ve ayarlar tarayıcı profilinizde chrome.storage.local kullanılarak saklanır. Geliştiricinin işlettiği bir sunucuya gönderilmez.

Eklentide geliştiriciye kullanım analitiği gönderen bir sistem bulunmaz. Pilot anket yanıtları da otomatik olarak geliştiriciye iletilmez.

Yedek geri yükleme sırasında veri bütünlüğünü korumak amacıyla geçici kayıtlar ve kurtarma bilgileri yerel olarak tutulabilir.

## AI hizmetlerine aktarım

“Copy Context” işlemi, hazırlanan bağlamı cihazınızın panosuna kopyalar.

“Send to AI” işlemi, seçtiğiniz ChatGPT, Claude veya Gemini hizmetini açar. Otomatik yapıştırma etkinse seçilen sayfa metni, notlar, alıntılar ve kaynak bilgileri bu hizmetin giriş alanına yerleştirilir.

İçerik giriş alanına yerleştirildiğinde ilgili üçüncü taraf web sayfasının erişebileceği hâle gelir. Eklenti gönder düğmesine basmaz ve mesajı otomatik göndermez. Otomatik yapıştırmayı ayarlardan kapatabilirsiniz.

AI hizmetlerinin içerik işleme uygulamaları kendi gizlilik politikalarına tabidir:

- OpenAI: https://openai.com/policies/privacy-policy/
- Anthropic: https://www.anthropic.com/legal/privacy
- Google: https://policies.google.com/privacy

Aktarmadan önce bağlamı incelemeniz ve paylaşmak istemediğiniz bilgileri çıkarmanız önerilir.

## İzinlerin kullanım amacı

- sidePanel: Notları ve araştırma araçlarını yan panelde göstermek.
- tabs: Aktif sekmenin URL ve başlığını belirlemek, sekme değişikliklerini takip etmek ve kullanıcı isteğiyle kaynak veya AI sekmeleri açmak.
- activeTab: Kullanıcının başlattığı işlemlerde aktif sayfaya geçici erişim sağlamak.
- scripting: Paket içindeki kodla sayfa metnini çıkarmak ve seçilen AI sitesine bağlamı yerleştirmek.
- contextMenus: Seçilen metni sağ tık menüsünden alıntı olarak kaydetmek.
- storage: Verileri ve tercihleri yerel olarak saklamak.

ChatGPT, Claude ve Gemini alan adlarına ilişkin izinler, kullanıcı isteğiyle otomatik yapıştırma özelliğini sunmak için kullanılır.

## Veri paylaşımı ve kullanım sınırları

Kullanıcı verileri satılmaz; reklam hedefleme, kredi değerlendirmesi veya eklentinin belirtilen amacıyla ilgisiz faaliyetler için kullanılmaz.

Kullanıcının seçtiği AI hizmetine aktarım, bağlam hazırlama ve aktarım özelliğini sağlamak amacıyla yapılır.

Context Notes kapsamında Google API’lerinden alınan bilgilerin kullanımı ve aktarımı, Sınırlı Kullanım gereklilikleri dahil Chrome Web Store Kullanıcı Verileri Politikası’na uygundur.

## Verilerin kontrolü ve silinmesi

Notlarınızı, alıntılarınızı ve projelerinizi eklenti arayüzünden silebilir; desteklenen dışa aktarma araçlarıyla verilerinizi yedekleyebilirsiniz.

Eklenti kaldırıldığında eklentiye ait yerel tarayıcı verileri silinir. Dışa aktardığınız dosyalar, panoya kopyaladığınız içerik ve üçüncü taraf AI hizmetlerine aktardığınız veriler bu işlemle silinmez. Bunları ilgili cihaz veya hizmet üzerinden ayrıca yönetmeniz gerekir.

## Politika değişiklikleri

Veri işleme uygulamaları değiştiğinde bu politika ve mağaza beyanları güncellenir. Gerektiğinde değişiklikler eklenti içinde de açıklanır.

## İletişim

Gizlilik sorularınız için:

orhanerenkara.dev@gmail.com

E-posta gönderirken özel notlarınızı veya hassas sayfa içeriklerini paylaşmanız gerekmez.
