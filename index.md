---
layout: default
title: Tensely Gizlilik Politikası
---

# Tensely Gizlilik Politikası

**Yürürlük tarihi:** 1 Ağustos 2026
**Veri sorumlusu:** TenseMaster Academy
**İletişim:** info@tensemasteracademy.com

Bu politika Tensely mobil uygulamasında ("Uygulama") hangi kişisel verilerinizi, hangi amaçla ve nasıl işlediğimizi açıklar. 6698 sayılı Kişisel Verilerin Korunması Kanunu ("KVKK") ile Apple App Store'un gizlilik politikası şartlarına uygun olarak hazırlanmıştır.

---

## 1. İşlenen Kişisel Veriler

### 1.1 Kimlik ve iletişim
- E-posta adresi
- Ad-soyad (isteğe bağlı)
- Apple / Google girişleri sağlayıcı tarafından paylaşılan benzersiz kullanıcı kimliği
- Şifre (yalnızca hash'lenmiş biçimde Supabase üzerinde saklanır; Tensely erişemez)

### 1.2 Öğrenme verileri
- Seçilen sınıf ve hedef CEFR seviyesi
- Günlük çalışma hedefi (dakika)
- Tamamlanan dersler, çözülen alıştırmalar, sonuçları
- Ustalık puanları ve seri (streak) takibi
- Hata analizi kayıtları (yanlış cevap desenleri)

### 1.3 Cihaz ve teknik veriler
- Cihaz tipi ve modeli
- İşletim sistemi sürümü
- Uygulama sürümü
- Push bildirim tokenı (yalnızca izin verdiyseniz)

Uygulamada çökme raporlama veya analitik aracı **bulunmuyor**. App Store ve Google Play, siz izin verdiyseniz kendi altyapıları üzerinden anonim çökme verisi toplayabilir; bu veri Apple ve Google'ın kendi politikalarına tabidir ve bize kimliğinizle ilişkilendirilmiş biçimde ulaşmaz.

### 1.4 Mikrofon ve konuşma tanıma
Konuşma alıştırmalarında, söylediğiniz İngilizce cümlenin beklenen cümleyle
eşleşip eşleşmediğini gösterebilmek için mikrofonu kullanırız.

- Mikrofon **yalnızca** bir konuşma alıştırmasında kayıt düğmesine bastığınızda açılır; arka planda dinleme yapılmaz.
- Konuşma, **işletim sisteminin kendi konuşma tanıma servisiyle** (iOS Speech, Android SpeechRecognizer) yazıya çevrilir. Bu servisler tanımayı cihazda ya da Apple/Google sunucularında yapabilir; hangisinin kullanılacağına cihazınızın işletim sistemi karar verir. Bu işlem Apple ve Google'ın kendi gizlilik politikalarına tabidir.
- **Ses Tensely'nin sunucularına hiçbir zaman ulaşmaz.** Kaydı ne alırız ne saklarız; alıştırma bittiğinde yazıya çevrilen metin de silinir.
- Tensely'ye yalnızca alıştırmayı doğru yapıp yapmadığınız bilgisi ulaşır.
- İzni reddedebilirsiniz; bu durumda konuşma alıştırmaları atlanır, dersin geri kalanı normal çalışır.

### 1.5 Abonelik ve ödeme
- Abonelik durumu (aktif / iptal edilmiş / süresi dolmuş)
- Abonelik tipi (aylık / yıllık)
- Satın alma tarihleri
- **Ödeme bilgileri (kart numarası, banka bilgisi vb.) Apple/Google tarafından tutulur; Tensely bu bilgilere erişmez veya saklamaz.**

### 1.6 İzlemediklerimiz
Aşağıdaki verileri **toplamıyoruz**:
- Reklam kimliği (IDFA / GAID)
- Konum bilgisi (GPS)
- Adres defteri, fotoğraflar, mesajlar
- Kamera erişimi
- Ses kaydı (mikrofon yalnızca anlık konuşma tanıma için kullanılır — bkz. 1.4)
- Sağlık verisi
- Finansal bilgiler (kart vb.)
- Web tarama geçmişi

---

## 2. İşleme Amaçları

Kişisel verileriniz yalnızca aşağıdaki amaçlarla işlenir:

- Kişiselleştirilmiş öğrenme deneyimi sunmak ve ilerlemenizi kaydetmek
- Hesap oluşturma, giriş ve kimlik doğrulama
- Cihazlar arası veri senkronizasyonu
- Bildirim ve hatırlatma gönderme (yalnızca izin verdiyseniz)
- Abonelik yönetimi
- Uygulama hatalarını ayıklama, güvenlik ve performans iyileştirmesi
- Kullanıcı desteği taleplerine yanıt verme
- Yasal yükümlülüklerin yerine getirilmesi

Verileriniz **reklam**, **profil oluşturma** veya **üçüncü taraf pazarlama** amacıyla kullanılmaz.

---

## 3. Hukuki Sebep (KVKK m.5)

- **Sözleşmenin ifası (m.5/2/c):** hesabınızı yönetmek ve uygulama hizmetini sunmak
- **Hukuki yükümlülük (m.5/2/ç):** fatura, mali kayıtlar, tüketici hakları mevzuatı
- **Meşru menfaat (m.5/2/f):** hata ayıklama, güvenlik, dolandırıcılık önleme
- **Açık rıza (m.5/1):** push bildirim tercihleri ve isteğe bağlı analitik veriler

---

## 4. Verilerin Aktarımı

Verileriniz aşağıdaki hizmet sağlayıcılarla paylaşılır — her biri kendi gizlilik politikası kapsamında hareket eder:

| Sağlayıcı | Amaç | Bölge |
|---|---|---|
| **Supabase** (AWS altyapısı üzerinde) | Veritabanı, kimlik doğrulama | Frankfurt, Almanya (AB) |
| **Apple Push Notification Service** | iOS bildirim iletimi | Apple altyapısı |
| **Google Firebase Cloud Messaging** | Android bildirim iletimi | Google altyapısı |
| **RevenueCat** | Abonelik doğrulama ve yönetimi | ABD |
| **Apple App Store / Google Play** | Ödeme işleme | Apple / Google altyapısı |

Yurt dışına aktarım söz konusu olan hallerde KVKK m.9 kapsamında gerekli güvenceler (standart sözleşme maddeleri) alınmaktadır.

Verilerinizi **satmıyoruz** ve reklam veren üçüncü taraflarla paylaşmıyoruz.

---

## 5. Saklama Süresi

- Öğrenme kayıtları: hesap aktif olduğu sürece
- Hesap silme talebinden sonra: **en geç 30 gün** içinde tüm kişisel verileriniz silinir veya anonimleştirilir
- Yasal yükümlülük gereği tutulması zorunlu veriler (fatura, vb.): mevzuatın öngördüğü süre boyunca saklanır (T.C. Vergi Usul Kanunu m.253 uyarınca 5 yıl)

---

## 6. KVKK Kapsamındaki Haklarınız

KVKK m.11 uyarınca aşağıdaki haklara sahipsiniz:

- Kişisel verilerinizin işlenip işlenmediğini öğrenme
- Kişisel verileriniz işlenmişse buna ilişkin bilgi talep etme
- Kişisel verilerinizin işlenme amacını ve amacına uygun kullanılıp kullanılmadığını öğrenme
- Yurt içinde veya yurt dışında kişisel verilerinizin aktarıldığı üçüncü kişileri bilme
- Kişisel verilerinizin eksik veya yanlış işlenmiş olması halinde bunların düzeltilmesini isteme
- KVKK m.7'de öngörülen şartlar çerçevesinde silinmesini veya yok edilmesini isteme
- Otomatik sistemler vasıtasıyla analiz edilmesi suretiyle aleyhinize bir sonucun ortaya çıkmasına itiraz etme
- Kanuna aykırı olarak işlenmesi sebebiyle zarara uğramanız halinde zararın giderilmesini talep etme

Bu haklarınızı kullanmak için: **info@tensemasteracademy.com**

Talebinizi en geç **30 gün** içinde ücretsiz olarak yanıtlarız.

---

## 7. Çocukların Gizliliği

Tensely, K-12 öğrencilerine yönelik bir eğitim uygulamasıdır. **13 yaşın altındaki kullanıcılar için ebeveyn izni gereklidir**.

- Kayıt ekranında, 13 yaşından küçük kullanıcıların hesabı ebeveyn izniyle oluşturması gerektiği belirtilir
- Ebeveyn izni olmadan çocuklardan bilinçli olarak kişisel veri toplamayız
- Ebeveynler, çocuklarının verilerinin silinmesini talep edebilir (yukarıdaki iletişim yoluyla)
- Reklamsız bir uygulamadır; hedefli reklam gösterilmez
- 13 yaş altı hesaplar için isteğe bağlı analitik kapalı olur

Apple Family Sharing ile hesap yönetimi desteklenir.

---

## 8. Güvenlik

- Tüm iletişim HTTPS/TLS 1.2+ üzerinden şifrelidir
- Şifreler bcrypt ile hash'lenir; düz metin olarak saklanmaz
- Ödeme bilgileri hiçbir zaman Tensely sunucularına ulaşmaz (Apple/Google tarafından işlenir)
- Kişisel veriler Supabase Row-Level Security politikaları ile korunur — her kullanıcı sadece kendi verisine erişebilir
- Abonelik durumu server-side (RevenueCat webhook) ile yönetilir; kullanıcı tarafından değiştirilemez

Buna rağmen internet üzerinden mükemmel güvenlik garantisi verilemez. Herhangi bir güvenlik olayı hakkında bilgi sahibi olursanız derhal bize bildirin.

---

## 9. Politika Değişiklikleri

Bu politikada değişiklik yaparsak:
- Yürürlük tarihini güncelleriz
- Önemli değişikliklerde uygulama içi bildirim gösteririz
- E-posta ile hesap sahiplerine bilgilendirme göndeririz

Değişikliklerden sonra Uygulamayı kullanmaya devam etmeniz güncellenen politikayı kabul ettiğiniz anlamına gelir.

---

## 10. İletişim

Bu politikayla veya kişisel verilerinizle ilgili herhangi bir sorunuz için:

**TenseMaster Academy**
E-posta: **info@tensemasteracademy.com**

---

<a id="hesap-silme"></a>

## 11. Hesabınızı ve Verilerinizi Silme

Hesabınızı iki yoldan silebilirsiniz.

**Uygulama içinden:** Tensely uygulamasında **Profil → Hesabımı sil** adımını izleyin. İki onay ekranından sonra hesabınız silinir.

**E-posta ile:** Uygulamaya erişiminiz yoksa **info@tensemasteracademy.com** adresine, hesabınızın kayıtlı e-posta adresinden bir silme talebi gönderin. Talebinizi en geç **30 gün** içinde ücretsiz olarak sonuçlandırırız.

Silme işlemiyle birlikte kaldırılan veriler:

- Hesap bilgileriniz (e-posta adresi, ad, kullanıcı kimliği)
- Öğrenme kayıtlarınız (tamamlanan dersler, ustalık puanları, seri, hata analizi)
- Bildirim tercihleriniz ve push bildirim tokenınız
- Abonelik geçmişiniz Tensely tarafında anonimleştirilir

**Silinmeyenler:** Vergi Usul Kanunu m.253 uyarınca 5 yıl saklanması zorunlu olan fatura ve mali kayıtlar ile Apple/Google tarafında tutulan satın alma kayıtları. Aboneliğinizi iptal etmek için ayrıca App Store veya Google Play abonelik ayarlarını kullanmanız gerekir; hesabın silinmesi aboneliği kendiliğinden iptal etmez.


---

*Bu politika Türkçe olarak hazırlanmıştır. İngilizce bir sürüm gerekli olursa info@tensemasteracademy.com adresinden talep edebilirsiniz.*
