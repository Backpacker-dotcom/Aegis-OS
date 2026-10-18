# Aegis OS

Sahip olduğun her şeyin işletim sistemi — bireysel mülkiyet ve yasal haklar kokpiti (Android).

- **İndir:** [AegisOS.apk (son sürüm)](https://github.com/Backpacker-dotcom/Aegis-OS/releases/latest/download/AegisOS.apk)
- Zaman Tüneli: iade, ceza, MTV, muayene, garanti ve sigorta geri sayımları
- Garaj: 3 taşıt, yıllık sahip olma maliyeti, bakım sayaçları, akıllı QR park kartı, evrak paylaşımı
- Ev & Cihazlar: garanti takibi, doğrulanmış yetkili servis, tesisat sayaçları
- Tüketici Hakları: fiyat düşüş dedektifi, geri ödeme teyidi, THH dilekçesi

## Nasıl güncellenir

- `web/index.html` uygulamanın kendisidir. Bu dosya değişince telefondaki uygulama bir sonraki açılışta yeni sürümü indirir; yeniden kurmaya gerek yoktur.
- `android/` klasörü değişince GitHub Actions yeni bir APK derleyip **Releases** bölümüne koyar. İlk derlemede imza anahtarı (`android/app/release.keystore`) otomatik oluşturulup depoya eklenir; sonraki sürümler aynı anahtarla imzalanır, böylece kurulu uygulamanın üzerine güncellenebilir.

> Hatırlatmalar kullanıcı verilerine dayalıdır; resmi kayıtlar esastır. Dilekçe metinleri taslaktır; hukuki danışmanlık teşkil etmez.
