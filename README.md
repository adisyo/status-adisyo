# status-adisyo

GitHub Pages üzerinde yayınlanan statik bakım sayfası. `content.md` dosyasını düzenleyerek içerik güncellemesi yapılabilir.

## 📝 İçerik Düzenleme

`content.md` dosyasını düzenleyin. Format:

```markdown
## Ana_Baslik
Başlık metni

## Aciklama
Açıklama metni

## Uyari_Mesaji
Uyarı mesajı

## Ozur_Mesaji
Özür mesajı

## Durum_Bilgisi
- Status: 2
- Tahmini_Sure: 10-15 dakika
```

## Status Değerleri

- **Status: 1** → Yeşil (Aktif) - Giriş butonu gösterilir, ana mesaj ve özür mesajı gizlenir. Durum: "Aktif"
- **Status: 2** → Kırmızı (Müdahale Ediliyor) - Tüm mesajlar gösterilir. Durum: "Müdahale Ediliyor"

Durum metni otomatik olarak status'a göre belirlenir. Mevcut_Durum alanına gerek yoktur.