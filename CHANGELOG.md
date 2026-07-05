# Changelog

## [v4.154] - 2026-07-05

### İyileştirmeler

- **Kusursuz Şarkı Tespiti:** Önceden aynı sanatçının farklı şarkıları, sırf sanatçı ismi uzun olduğu için program tarafından "Aynı Şarkı" zannedilebiliyordu. Artık her bir şarkı tamamen birbirinden bağımsız olarak analiz ediliyor ve bu kafa karışıklığı kökünden çözüldü.
- **Liste Tarama Hızı:** Gereksiz tekrarlayan tarama işlemleri kaldırılarak çalma listelerinin analizi ve sonuç raporlaması daha hızlı hale getirildi.
- **Bağlantı Kısıtlamaları Giderildi:** YouTube'un indirme sıklığına bağlı olarak uyguladığı erişim kısıtlamaları (403 hatası) büyük oranda çözüldü. VPN kullanımında veya art arda yapılan indirmelerde yaşanan bağlantı kopmaları giderildi.
- **Otomatik Yeniden Deneme Sistemi:** İndirme sırasında geçici bir ağ veya erişim hatası oluştuğunda işlemin tamamen iptal olması engellendi. Hata durumunda uygulama 7 saniye bekleyip indirmeyi otomatik olarak tekrar deniyor (maksimum 2 deneme).
- **Genişletilmiş Çalma Listesi Desteği:** 100'den fazla içerik barındıran uzun çalma listelerindeki eksik yükleme problemi çözüldü. Artık listelerin tamamı eksiksiz olarak algılanıp indirilebiliyor.

## [v4.153] - 2026-06-30

### Eklendi / Güncellendi

- **Bağlantı Kısıtlamaları Giderildi:** YouTube'un indirme sıklığına bağlı olarak uyguladığı erişim kısıtlamaları (403 hatası) büyük oranda çözüldü. VPN kullanımında veya art arda yapılan indirmelerde yaşanan bağlantı kopmaları giderildi.
- **Otomatik Yeniden Deneme Sistemi:** İndirme sırasında geçici bir ağ veya erişim hatası oluştuğunda işlemin tamamen iptal olması engellendi. Hata durumunda uygulama 7 saniye bekleyip indirmeyi otomatik olarak tekrar deniyor (maksimum 2 deneme).
- **Genişletilmiş Çalma Listesi Desteği:** 100'den fazla içerik barındıran uzun çalma listelerindeki eksik yükleme problemi çözüldü. Artık listelerin tamamı eksiksiz olarak algılanıp indirilebiliyor.

## [v4.150] - 2026-04-30

### Eklendi / Güncellendi

- **Çift İndirme Koruması:** Aynı çalma listesinde bir şarkı veya video birden fazla kez yer alıyorsa, uygulamanın aynı dosyayı boş yere tekrar indirmesi engellendi ve kullanıcıya bilgi verilmesi sağlandı.
- **Daha Açıklayıcı Hatalar:** Bir sorun yaşandığında arka planda ne olduğunu anlamanızı kolaylaştıran daha net ve detaylı uyarı mesajları eklendi.
- **Yüksek Çözünürlük (4K) Desteği:** Artık destekleyen videoları kristal netliğinde 4K çözünürlüğünde indirebilirsiniz.

## [v4.141] - 2026-04-09

### İyileştirmeler

- **Daha Kararlı Çalışma:** Uygulamanın altyapısındaki görünmez hatalar temizlendi, böylece çökme veya donma gibi sorunlar en aza indirildi.
- **Performans Optimizasyonu:** Bellek kullanımı ve uygulamanın çalışma hızı iyileştirilerek çok daha akıcı bir deneyim sağlandı.

## [v4.140] - 2026-04-06

### İyileştirmeler

- **Yalancı İndirme Sorunu Çözüldü:** İnternet kesildiğinde uygulamanın dosyayı indiriyormuş gibi yapıp başarıyla tamamlandı demesi sorunu düzeltildi.
- **Net İnternet Uyarıları:** Bağlantı koptuğunda ekranı kaplayan kırmızı renkli uyarılarla durumun hemen fark edilmesi sağlandı.
- **Temiz Klasör Düzeni:** İndirme işlemi başarısız olduğunda bilgisayarınızda gereksiz yere boş klasörler bırakılmasının önüne geçildi.
- **Arayüz Akıcılığı:** Hata alındığında yükleme animasyonlarının donup kalması veya sürekli dönmeye devam etmesi sorunu giderildi.

## [v3.100] - v4.0.0 (Tasarım Güncellemesi)

### Eklendi / Güncellendi

- **Yepyeni Tasarım:** Uygulama, göz yormayan karanlık teması (Dark Mode) ve modern görünümüyle tamamen yenilendi.
- **Detaylı Özet Ekranı:** İndirme bittiğinde kaç dosyanın yeni eklendiğini, kaçının zaten var olduğunu veya hata verdiğini gösteren kullanışlı bir rapor ekranı eklendi.
- **Canlı Hız Göstergesi:** Artık dosyaların inme hızını ve yüzde kaçının tamamlandığını anlık olarak takip edebilirsiniz.

## [v2.0.0] - v3.0.0 (Fonksiyonel Gelişim)

### Eklendi / Güncellendi

- **Toplu İndirme Özelliği:** Artık koca bir oynatma listesini (Playlist) tek bir tıklamayla tamamen indirebilirsiniz.
- **Kalite ve Format Seçimi:** Videoların görüntü kalitesini ve formatını (MP4, MKV vb.) kendi isteğinize göre belirleme imkanı sunuldu.
- **Otomatik Altyapı Güncellemesi:** Uygulama her açıldığında indirme motorunu kendi kendine güncelleyerek YouTube'un yeniliklerine hızlıca ayak uydurması sağlandı.

## [v1.0.0] - İlk Sürüm

### Özellikler

- **İlk Buluşma:** YouTube videolarını ister görüntülü ister sadece ses (MP3) olarak indirebilen temel altyapı oluşturuldu.
- **Kullanım Kolaylığı:** Karmaşadan uzak, herkesin rahatça anlayabileceği sade bir arayüz tasarlandı.

---
