# Notlarım — Gizlilik Politikası

**Son güncelleme:** 19 Mayıs 2026

Bu gizlilik politikası, macOS için Notlarım uygulamasının kişisel verilerinizi
nasıl işlediğini açıklar.

## Kısa Özet

**Notlarım hiçbir kişisel veri toplamaz, sunuculara hiçbir şey göndermez.**

Tüm notlarınız, todo'larınız, ses kayıtlarınız ve çizimleriniz yalnızca
Mac'inizde, App Group container'ında saklanır:

```
~/Library/Group Containers/group.com.merchantsbox.notlarim/
```

İnternet bağlantısı gerektirmez (web link kartlarını önizlemek için **isteğe
bağlı** olarak Apple'ın LinkPresentation API'si kullanılır; bu API doğrudan
linklenen siteye bağlanır ve verileri hiçbir şekilde geliştiriciye aktarmaz).

## Detaylar

### 1. Topladığımız Veriler

**Hiçbir kullanıcı verisi toplamıyoruz.** Notlarım:
- Analitik araç (Google Analytics, Mixpanel vb.) içermez
- Çökme raporu (crash reporter) hizmeti içermez
- Kullanıcı davranış takibi yapmaz
- Reklam ağına bağlı değildir
- Sosyal medya entegrasyonu içermez

### 2. Yerel Olarak Saklanan Veriler

Aşağıdaki veriler **yalnızca cihazınızda** saklanır, hiçbir üçüncü tarafa
gönderilmez:

- Notlarınızın metni, başlıkları, etiketleri ve ayarları
- Yapılacaklar listeniz ve tamamlama durumları
- Ruh hâli (mood) kayıtlarınız
- Ses kayıtlarınız (.m4a)
- Çizimleriniz (.png)
- Görseller eklediğiniz dosyalar
- Sürüm geçmişi (notların eski hâlleri)
- Klasör organizasyonu

### 3. Sistem İzinleri

Notlarım yalnızca aşağıdaki sistem izinlerini ister:

- **Mikrofon**: Ses notu kaydı yapabilmek için (yalnızca siz kayıt başlattığınızda)
- **Bildirimler**: Alışkanlık hatırlatmaları gönderebilmek için (opsiyonel)
- **Otomasyon (Terminal)**: Kod bloklarındaki shell script'leri Terminal'de
  çalıştırmak için (yalnızca siz butona bastığınızda)

Bu izinlerin tümünü Sistem Ayarları'ndan istediğiniz zaman geri alabilirsiniz.

### 4. Bağlantılı Verileriniz

Notlar arasında bağlantı (`@@notbaşlığı`) kurabilirsiniz; bu işlem tamamen
yerel olarak çalışır.

Web link kartları (URL embed) için Apple'ın LinkPresentation API'si kullanılır.
Bu API linklenen siteye doğrudan bağlanıp başlık ve önizleme alır. Notlarım
geliştiricisi olarak biz bu trafiği görmüyoruz veya kaydetmiyoruz.

### 5. Üçüncü Taraflarla Paylaşım

Hiçbir veri üçüncü tarafla paylaşılmaz. Çünkü zaten bizde herhangi bir veri yok.

### 6. Çocukların Gizliliği

Notlarım'ı 13 yaş altı çocuklar için pazarlamıyoruz ve bilerek onlardan veri
toplamıyoruz.

### 7. Veri Saklama ve Silme

Tüm verileriniz cihazınızda kalır. Uygulamayı silerseniz, App Group container'ı
da silinir ve verileriniz kalıcı olarak yok olur. Yedek almak istiyorsanız,
container klasörünü yedekleyiniz.

### 8. Politikadaki Değişiklikler

Bu politikada güncelleme yaparsak, bu sayfada yayınlarız. Önemli
değişiklikleri uygulama içinde de bildirebiliriz.

### 9. İletişim

Bu politika hakkında sorularınız için:

**📧 [44mert2001@gmail.com](mailto:44mert2001@gmail.com)**

---

*Bu politika hem Türkçe hem İngilizce sürümleriyle geçerli olup, ihtilaf
hâlinde Türkçe metin esas alınır.*
