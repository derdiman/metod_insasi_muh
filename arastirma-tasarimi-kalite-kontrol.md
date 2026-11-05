# Araştırma Tasarımı İçin Yönteme Özgü Kalite Kontrolleri

Bu kontrol listesi bütün çalışmalarda baştan sona uygulanmaz. Sadece seçilen yöntem ailesine uyan maddeleri kullan. Bilinmeyen değerleri uydurma; gerekçeli plan veya “doğrulanacak” maddesi yaz.

## 1. Deneysel çalışmalar ve laboratuvar testleri

- Test amacı, bağımsız/dependent değişkenler ve kontrol edilecek koşullar net mi?
- Numune/tekrar sayısı; beklenen etki, değişkenlik, standart veya pilot çalışma ile gerekçelendirildi mi? Sayı bilinmiyorsa rastgele belirleme.
- Uygunsa rastgeleleştirme, bloklama, kontrol numunesi ve deney sırası etkileri planlandı mı?
- Numune hazırlığı, ekipman, kalibrasyon, ölçüm aralığı, çözünürlük ve belirsizlik kaydedildi mi?
- İstatistiksel analizden önce varsayımlar, aykırı değer yaklaşımı, etki büyüklüğü ve güven aralığı planlandı mı?
- Aynı numuneden alınan tekrar ölçümleri bağımsız numune gibi sayılıyor mu? Sözde tekrardan kaçınıldı mı?
- İlgili test standardının kapsamı, baskısı ve koşulları resmî kaynaktan doğrulandı mı?

## 2. Saha, gözlemsel ve çoklu vaka çalışmaları

- Analiz birimi nedir: kişi, makine, faaliyet, proje, vardiya, gün, tesis veya başka birim mi?
- Birimler arasında veri seviyesi aynı mı? Günlük/haftalık toplulaştırılmış kayıtlar tekil faaliyetlere doğrudan bağlanabilir mi?
- Zaman sırası, ölçüm sıklığı, eksik kayıtlar, veri kaynağı ve değişken tanımları açık mı?
- Birden fazla proje/tesis/kişi içindeki tekrarlar iç içe geçmiş (nested) yapı oluşturuyor mu? Bağımsız gözlem varsayımı kontrol edildi mi?
- Mevsim, ölçek, ekip, teknoloji, proje türü veya başka karıştırıcı etkenler ele alındı mı?
- İlişki, tahmin ve nedensellik iddiaları birbirinden ayrıldı mı? Gözlemsel veri tek başına neden-sonuç kanıtı değildir.
- Az sayıda vaka varsa derin bağlamsal analiz ve analitik karşılaştırma tercih edilip geniş istatistiksel genellemeden kaçınıldı mı?

## 3. Sayısal modelleme ve hesaplamalı çalışmalar

- Modelin amacı, denklemleri, kabulleri, geometri/sistem sınırı ve geçerlilik aralığı açık mı?
- Başlangıç/sınır koşulları, malzeme/akışkan özellikleri ve girdi kaynakları belirtilmiş mi?
- Ağ/mesh, zaman adımı, tolerans veya çözümleyici ayarlarına ilişkin yakınsama/bağımsızlık incelemesi gerekiyor mu ve planlandı mı?
- Kod/algoritma verification; analitik çözüm, referans problem veya bağımsız uygulama ile kontrol edildi mi?
- Model validation, model kurulumunda kullanılmayan bağımsız deney/saha verisi veya uygun referans ile planlandı mı?
- Parametre belirsizliği, duyarlılık ve model sınırları incelendi mi?
- Yazılım/çözümleyici adı, sürümü, ayarlar ve donanım yeterince kaydedildi mi?

## 4. Simülasyon çalışmaları

- Kavramsal model ve sistem mantığı doğrulandı mı?
- Girdi dağılımları/parametreleri veri, literatür veya uzman gerekçesine dayanıyor mu?
- Isınma dönemi (gerekiyorsa), simülasyon süresi, tekrar sayısı ve rastgele tohumlar gerekçelendirildi mi?
- Sonuçlar birden fazla senaryo ve belirsizlik altında incelendi mi?
- Çıktılar gerçek saha ölçümü gibi değil, simülasyon sonucu olarak etiketlendi mi?

## 5. Optimizasyon ve karar modelleri

- Karar değişkenleri, amaç fonksiyonu, kısıtlar ve birimler açık mı?
- Model gerçek operasyonel/teknik koşulları temsil ediyor mu?
- Başlangıç çözümü veya baseline ile adil karşılaştırma var mı?
- Çözümün uygulanabilirliği, optimalite/çözüm kalitesi ve hesaplama maliyeti raporlanıyor mu?
- Parametre ve senaryo değişimlerine duyarlılık incelendi mi?
- Çok amaçlı problemde ödünleşimler (trade-off) görünür mü?
- Modelin önerdiği çözümün gerçek ortamda işe yaradığı iddiası için saha/pilot doğrulama gerekiyor mu?

## 6. Yapay zekâ ve veri odaklı çalışmalar

- Veri kaynağı, etiket tanımı, temsil gücü, sınıf dengesizliği ve veri kalitesi açık mı?
- Eğitim, doğrulama ve test ayrımı bağımsız birim/grup/zaman yapısını koruyor mu? Aynı kişi, cihaz, proje veya zaman serisinin parçaları veri sızıntısı yaratıyor mu?
- Model seçimi ve hiperparametre ayarı test verisine bakmadan yapılıyor mu?
- Uygun basit baseline ve mevcut yöntemlerle karşılaştırma var mı?
- Problem türüne uygun metrikler ve hata analizi yapılıyor mu? Yalnızca doğruluk oranı yeterli mi?
- Bağımsız veya dış veri üzerinde değerlendirme mümkün mü?
- Kod, veri sürümü, rastgele tohum, kütüphane sürümü ve hesaplama ortamı kaydedildi mi?

## 7. Yazılım, algoritma ve sistem geliştirme

- Gereksinimler, kullanım senaryoları ve başarı ölçütleri tanımlandı mı?
- Birim, entegrasyon, sistem, performans ve güvenlik testlerinden hangileri gerekli?
- Test ortamı, donanım, yazılım sürümü, bağımlılıklar ve test verisi kaydedildi mi?
- Benchmark veri setleri veya test yükleri temsil edici mi?
- Kod ve deneyler yeniden çalıştırılabilir mi?

## 8. Literatür/kanıt sentezi

- Derleme türü ve araştırma sorusu açık mı?
- Veri tabanları, tam sorgular ve son tarama tarihleri kayıtlı mı?
- Dahil etme/dışlama ölçütleri önceden tanımlı mı?
- Yinelenen kayıtlar, başlık/özet elemesi ve tam metin elemesi ayrıştırıldı mı?
- Kaynak kalitesi/yanlılık değerlendirmesi ve veri çıkarma planı var mı?
- Çalışmalar yöntem, sistem, koşul ve ölçüt bakımından yeterince benzer mi? Meta-analiz için gerekçe var mı?
- Raporlama rehberi (PRISMA veya uygun uzantı) bu derleme türüne gerçekten uyuyor mu?

## 9. Tüm yöntemler için ortak son kontrol

- Araştırma sorusu ile veri ve analiz doğrudan eşleşiyor mu?
- Olumsuz, başarısız veya beklenmeyen sonuçlar da raporlanacak mı?
- Belirsizlik ve sınırlılıkların iddialara etkisi açıklanıyor mu?
- Veri, kod, model, parametre ve prosedürün paylaşılabilirliği/lisansı değerlendirildi mi?
- İnsan katılımcı veya kişisel veri varsa etik onay, onam ve veri koruma koşulları net mi?
- Güvenlik-kritik kararlar yetkili uzman ve ilgili standart/otorite tarafından kontrol edilecek mi?
