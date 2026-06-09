# Orwell Türkçe Yama (Turkish Patch)

Bu yama Orwell oyununa Türkçe dil desteği eklemek için tasarlanmıştır.

## Kurulum (Installation)

### Yöntem 1: Unity Asset Araçları ile (Önerilen)

1. **Gerekli Araçlar:**
   - [AssetStudio](https://github.com/Perfare/AssetStudio) veya
   - [UABE](https://github.com/AssetRipper/AssetRipper) veya
   - Unity asset editing araçları

2. **Adımlar:**
   - `Orwell_Turkish_Patch.zip` dosyasını çıkarın
   - `resources.assets` dosyasını bulun (genellikle `Orwell_Data` klasöründe)
   - Asset aracıyla `resources.assets` dosyasını açın
   - `Language.enU` (İngilizce) TextAsset dosyasını bulun
   - İçeriğini `lang_tr_final.xml` dosyasındaki içerikle değiştirin
   - Dosyayı kaydedin

### Yöntem 2: Dosya Değiştirme

1. Oyunun `Orwell_Data/resources.assets` dosyasının yedeğini alın
2. Asset araçlarıyla dosyayı düzenleyin
3. Turkish dil dosyasını yükleyin

## Dosyalar

- `lang_tr_final.xml` - Türkçe çeviri dosyası (478 string)
- `Orwell_Turkish_Patch.zip` - Yama paketi

## Çeviri Durumu

- **Toplam String:** 478
- **Çevrilen:** ~450+ ( Tahminen %94+)
- **Kalan:** UI diyalogları ve bazı özel terimler

## Notlar

- Bu yama sadece metin çevirisi içerir (sesli diyaloglar değiştirilmez)
- Çeviri kalitesi topluluk tarafından sağlanmıştır
- Oyun orijinal dosyalarını değiştirmeden önce yedek alın

## Katkıda Bulunma

Hata bulursanız veya çeviriyi geliştirmek isterseniz, pull request açabilirsiniz.

---

# Orwell Turkish Patch

This patch adds Turkish language support to the Orwell game.

## Installation

1. Extract `Orwell_Turkish_Patch.zip`
2. Use an asset modification tool (AssetStudio, UABE, etc.)
3. Open `resources.assets` from the game's data folder
4. Replace the `Language.enU` TextAsset content with `lang_tr_final.xml`
5. Save and enjoy!

## Files

- `lang_tr_final.xml` - Turkish translation (478 strings)
- `Orwell_Turkish_Patch.zip` - Patch package

## Translation Status

- **Total Strings:** 478
- **Translated:** ~450+ (~94%+)
- **Remaining:** Some UI dialogs and special terms

## Notes

- This patch only translates text (voice acting not changed)
- Translation provided by community
- Always backup original files before modifying