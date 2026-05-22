# Notlarım — Destek

macOS için Notlarım uygulamasının resmi destek sayfası.

Sorularınız, geri bildirimleriniz veya hata bildirimleriniz için:

**📧 İletişim:** [44mert2001@gmail.com](mailto:44mert2001@gmail.com)

---

## Sıkça Sorulan Sorular

### Widget Bildirim Merkezi'nde görünmüyor

1. Uygulamanın `/Applications/` klasöründe yüklü olduğundan emin olun (`~/Downloads` veya başka bir yer **değil**)
2. Uygulamayı bir kez açıp kapatın — macOS extension'ları index'lesin
3. NotificationCenter'ı yeniden başlatın: Terminal'de `killall NotificationCenter`
4. Sağ kenardan iki parmakla kaydırın → en alta inin → "Widget'ları Düzenle"
5. "Notes" araması yapın, sürükleyip ekleyin

### Verilerim nerede saklanıyor?

Tüm notlarınız, todo'larınız, ses kayıtlarınız ve çizimleriniz yalnızca Mac'inizde,
App Group container'ında saklanır:

```
~/Library/Group Containers/group.com.merchantsbox.notlarim/
```

Hiçbir veri buluta gönderilmez. İnternet bağlantısı gerekmez.

### Notlarımı yedeklemek istiyorum

Yukarıdaki klasörü Time Machine yedeğinize dahil ederek veya manuel olarak
kopyalayarak yedek alabilirsiniz. `notes.json` dosyası tüm notlarınızı içerir.

### Kod bloğundaki "Terminal'de Çalıştır" butonu çalışmıyor

İlk seferinde macOS izin penceresi çıkar — "Notlarım, Terminal'i kontrol etmek
istiyor" mesajına **İzin Ver** demeniz gerekir. Bir kerelik onaydır.

Daha sonra reddederseniz şuradan tekrar açabilirsiniz:
**Sistem Ayarları → Gizlilik ve Güvenlik → Otomasyon → Notlarım → Terminal**

### Touch ID ile kilitli notlarımı unutursam ne olur?

Kilitli notlar yalnızca Touch ID veya cihaz parolasıyla açılır. Bunlar kaybolursa
notlar geri alınamaz, çünkü şifreleme anahtarı sadece bizdeki kayıt için
local'de tutulur.

### Markdown nasıl çalışıyor?

Bir text bloğunda şunları yazarsanız otomatik dönüşür:

- `# ` → büyük başlık
- `## ` → orta başlık
- `### ` → küçük başlık
- `- ` → bullet liste
- `1. ` → numaralı liste
- `> ` → alıntı
- `[] ` → yapılacak (todo)
- `---` → ayraç çizgi
- ` ``` ` → kod bloğu
- `>! ` → callout

### Slash menüsü ne yapar?

Bir text bloğunun başında `/` yazınca block tipi seçici çıkar. Aradığını yaz
(`/todo`, `/code`, `/quote`, `/terminal`...), Enter'a bas.

---

## Sistem Gereksinimleri

- **macOS 14 (Sonoma)** veya üstü
- Apple Silicon (M1, M2, M3, M4) veya Intel Mac
- Yaklaşık 50 MB disk alanı

## Sürüm Notları

Sürüm geçmişini görmek için: [Releases](https://github.com/KULLANICI_ADI/notlarim-support/releases)
