# ChatGPT ile bu kütüphaneyi kullanmak

Depo: https://github.com/yavuzates34/videolar

## Sesli sohbette tek paketle kullanım

Kütüphane sahibinin 5 Kasım 2026'da deneyerek doğruladığını bildirdiği sıra:

1. Önce ChatGPT web'de sesli sohbeti başlat ve selam ver.
2. Sesli sohbet açıkken artı düğmesine tıkla; videonun ZIP paketini seç.
3. Arayüzdeki ilet düğmesiyle dosyayı sohbete bir kez gönder.
4. Aynı sesli oturumda ilgili zamanları, başlıkları ve bölümleri sorarak devam et.

Dosya iletme sırası önemlidir. Önce yazılı alanda depoyu okutmak, sesli modelin aynı kaynağa erişeceğini kanıtlamaz. Yukarıdaki sıra kullanıcı beyanına dayanır; yeni yoğun ZIP'in gerçek kabulü ayrıca sınanmalıdır.

Videoların ZIP bağlantısı ana [kütüphane dizinindedir](README.md). ZIP içinde `BASLA.md`, tam transkript/bölümler ve Python'un saniyede en az 10 kare çıkardığı görüntüler bulunur. Karelerin dosya adında ve alt şeridinde zaman vardır; `frames.csv` gerçek kaynak PTS bilgisini de taşır. Sorduğun anın karesini gerçekten açıp açamadığını kontrol et.

## Yazılı alandan alternatif depo erişimi

Şu istem, depoyu yazılı olarak okumak içindir; sesli oturumda otomatik GitHub erişimi garantisi değildir:

> https://github.com/yavuzates34/videolar deposundaki index.json dosyasını aç. UI Collective'ın “How to Design Without Figma” videosunu bul. İlgili OKUMA.md dosyasını, soruma bağlı bölümün transkriptini ve görsel açıklamalarını oku. Erişebildiğin kaynakları söyle; görüntüleri gerçekten açamıyorsan bunu belirt. Ardından benimle Türkçe, kısa yanıtlarla konuyu tartış. Konuşmacının iddialarını kendi yorumundan ayır; önemli açıklamalarda zaman damgası ver.

## Bu videoya doğrudan erişim

- [İnceleme](videos/uzQCZD3w3hs/OKUMA.md)
- [Tam transkript](videos/uzQCZD3w3hs/transkript.md)
- [Görsel açıklamaları](videos/uzQCZD3w3hs/gorseller.md)
- [Tek dosyalık incelemenin ham bağlantısı](https://raw.githubusercontent.com/yavuzates34/videolar/main/videos/uzQCZD3w3hs/OKUMA.md)

## Erişim sınırı

Depoya yüklenmesi, her ChatGPT oturumunun dosyayı kendiliğinden bulacağı anlamına gelmez. Oturumda GitHub bağlantısı veya web erişimi bulunmalı; yeni dosyaların aramada görünmesi gecikebilir. Arama sonuç vermezse doğrudan ham dosya bağlantısını kullan. Bağlantıyı açamayan oturumda inceleme/transkript dosyasını ek olarak yükleyebilirsin.

Markdown'daki bir resim bağlantısını okumak, resmin görüntüsünün modele iletildiğini kanıtlamaz. Gerekli kareyi gerçekten açıp açamadığını sor; açılamıyorsa JPEG dosyasını ek olarak yükle. Resim ekleme yolu [resmî OpenAI belgelerinde](https://learn.chatgpt.com/docs/image-inputs) anlatılır.

GitHub/raw erişim kontrolü ile ChatGPT web sesli sohbet kabulü ayrı tutulur. Bu depoyu hazırlayan Codex oturumu, kullanıcının ayrı web/sesli oturumunda başarılı okuma gerçekleştiğini kendiliğinden doğrulayamaz.

Gerçekleştirilen kontroller: [ERISIM.md](ERISIM.md).
