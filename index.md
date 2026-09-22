# MindContext: AI Research Notes & Side Panel — Gizlilik Politikası

Son güncelleme: 22 Eylül 2026

Geliştirici: Orhan Eren Kara

MindContext, web sayfalarına bağlı notlar ve alıntılar kaydetmenizi, araştırma projeleri oluşturmanızı ve seçtiğiniz içerikten yapay zeka (AI) servislerinde kullanabileceğiniz zengin bağlam metinleri hazırlamanızı sağlar.

## İşlenen veriler

Eklenti, temel özelliklerini sunmak için aşağıdaki verileri işler:

- Aktif sayfanın URL’si ve sayfa başlığı.
- Kullanıcı tarafından kaydedilen alıntılar ve yazılan notlar.
- Kullanıcı isteğiyle bağlama eklenmek üzere çıkarılan web sayfası gövde metni.
- Araştırma projeleri, kaynak ilişkileri ve özel prompt şablonları.
- Kullanıcı tercihleri/ayarları ve kayıtların oluşturulma/güncellenme zamanları.
- Pilot anketini gönüllü olarak doldurursanız verdiğiniz geri bildirim yanıtları ve (isteğe bağlı belirtilmişse) iletişim e-postanız.

URL ve sayfa başlığı bilgileri, yalnızca bulunulan sayfaya ait doğru not ve alıntıları eşleştirmek amacıyla kullanılır. Eklenti, tarayıcı geçmişinizi izlemez veya ziyaret ettiğiniz sayfaları arşivlemez.

## Yerel saklama (Local Storage)

Notlar, alıntılar, projeler, özel şablonlar ve ayarlar tarayıcı profilinizde `chrome.storage.local` API'si kullanılarak tamamen cihazınızda yerel olarak saklanır. Geliştiricinin işlettiği herhangi bir uzak sunucuya veya üçüncü taraflara gönderilmez.

Eklentide kullanıcı davranışlarını arka planda takip eden hiçbir analitik, izleyici (tracker) veya telemetri kodu bulunmaz.

Pilot anketine katılım tamamen isteğe bağlıdır. Yanıtlar yalnızca kullanıcı anketteki "Geri Bildirimi Gönder" butonuna bastığında form servis sağlayıcısı (Formspree) aracılığıyla doğrudan geliştiriciye iletilir. Notlarınız, alıntılarınız veya sayfa içerikleriniz bu ankete kesinlikle dahil edilmez.

Yedekleme ve geri yükleme sırasında veri kaybını önlemek amacıyla geçici işlem kayıtları yine sadece tarayıcınızın yerel depolama alanında tutulur.

## AI hizmetlerine aktarım

- **Promptu Kopyala (Copy Context):** Hazırlanan bağlam ve prompt metnini doğrudan cihazınızın panosuna (clipboard) kopyalar.
- **AI'a Aktar (Send to AI):** Kullanıcının seçtiği AI servisini (ChatGPT, Claude veya Gemini) yeni bir sekmede açar. Otomatik yapıştırma seçeneği açıksa, kullanıcının seçtiği sayfa notları, alıntıları ve sayfa içeriği ilgili AI servisinin metin giriş alanına yerleştirilir.

İçerik AI servisinin giriş alanına yerleştirildiğinde ilgili üçüncü taraf servisin erişimine açık hale gelir. MindContext kesinlikle "Gönder / Enter" tuşuna basmaz ve mesajı otomatik olarak göndermez; nihai kontrol her zaman kullanıcıdadır. Otomatik yapıştırma özelliği Ayarlar menüsünden istenildiği zaman kapatılabilir.

AI hizmetlerinin veri işleme politikaları kendi kullanım koşullarına tabidir:
- OpenAI (ChatGPT): https://openai.com/policies/privacy-policy/
- Anthropic (Claude): https://www.anthropic.com/legal/privacy
- Google (Gemini): https://policies.google.com/privacy

Hassas veya paylaşmak istemediğiniz kişisel verileri AI servislerine göndermeden önce önizleme ekranından incelemeniz önerilir.

## İzinlerin kullanım amacı

- **sidePanel:** Notları, alıntıları ve araştırma panellerini tarayıcının yan panelinde görüntülemek.
- **tabs:** Aktif sekmenin URL ve başlığını tespit etmek, sekme geçişlerini algılayarak ilgili notu getirmek ve kullanıcının isteğiyle kaynak/AI sayfalarını açmak.
- **activeTab:** Kullanıcı işlem başlattığında aktif sayfaya güvenli ve geçici erişim sağlamak.
- **scripting:** Kullanıcı talep ettiğinde aktif sayfanın okunabilir metin içeriğini çıkarmak ve seçilen AI servisinin metin kutusuna bağlamı yerleştirmek.
- **contextMenus:** Web sayfasında fareyle seçilen metinleri sağ tık menüsü üzerinden tek tıkla alıntı olarak kaydetmek.
- **storage:** Notları, alıntıları, projeleri, prompt şablonlarını ve ayarları yerel olarak kaydetmek.
- **Host İzinleri (`http://*/*` ve `https://*/*`):** Yalnızca kullanıcının açıkça "Sayfa İçeriğini Ekle" seçeneğini kullandığı anlarda, bulunulan web sayfasının metin içeriğini okumak ve bağlama dahil edebilmek için gereklidir.
- **Host İzinleri (`chatgpt.com`, `claude.ai`, `gemini.google.com`):** Kullanıcı "AI'a Aktar" dediğinde ilgili AI sekmesindeki sohbet kutusunu bularak bağlam metnini otomatik yapıştırabilmek için kullanılır.
- **Host İzni (`formspree.io`):** Yalnızca kullanıcının kendi isteğiyle doldurup onayladığı pilot geri bildirim anketini geliştiriciye iletmek amacıyla kullanılır.

## Veri paylaşımı ve kullanım sınırları

Kullanıcı verileri hiçbir şart altında üçüncü taraflara satılmaz, reklam ağlarıyla paylaşılmaz, kredi/finansal değerlendirmeler için kullanılmaz veya eklentinin temel amacı dışında hiçbir amaçla işlenmez.

MindContext kapsamında Google Chrome API'lerinden alınan tüm bilgilerin kullanımı ve aktarımı, Sınırlı Kullanım (Limited Use) gereksinimleri dahil olmak üzere Chrome Web Store Kullanıcı Verileri Politikası'na (Chrome Web Store User Data Policy) harfiyen uygundur.

## Verilerin kontrolü ve silinmesi

Kullanıcılar notlarını, alıntılarını, projelerini ve şablonlarını diledikleri an eklenti arayüzünden silebilir veya JSON formatında dışa aktararak yedekleyebilirler.

Eklenti Chrome'dan kaldırıldığında, tarayıcıda saklanan tüm yerel veriler otomatik olarak kalıcı olarak silinir.

## İletişim

Gizlilik politikası, veri güvenliği veya destek talepleriniz için:

**E-posta:** orhanerenkara.dev@gmail.com
