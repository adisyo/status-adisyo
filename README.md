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
- Mevcut_Durum: Müdahale Ediliyor
- Tahmini_Sure: 10-15 dakika
```

## Status Değerleri

- **Status: 1** → Yeşil (Normal) - Giriş butonu gösterilir
- **Status: 2** → Turuncu (Müdahale) - Tüm mesajlar gösterilir
- **Status: 3** → Kırmızı (Ciddi) - Tüm mesajlar gösterilir

Renk otomatik olarak status'a göre belirlenir.