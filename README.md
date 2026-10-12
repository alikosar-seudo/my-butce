# My Bütçe — Android test sürümü

[Güncel Android test APK’sını indir](https://raw.githubusercontent.com/alikosar-seudo/my-butce/v0.1.1-test/my-butce-test.apk)

Türkçe ses ve mikrofon başlangıcı düzeltmesi. Uygulama sürümü 1.0.1, Android versionCode 2. Android 7.0+, ARM64/x86_64; bağımsız çalışır.

- Türkçe okuma sesi açıkça seçilir; Türkçe ses yoksa kurulum adımı gösterilir.
- Ana ekrandaki “Sesle işlem yap” düğmesi asistan odaklanınca dinlemeyi başlatır.
- Mikrofon izni zaten verilmişse yeniden istenmez. Kurulu Google tanıma hizmeti tercih edilir; tanıma dili tr-TR.
- Yanıttan sonra sonraki komut dinlenir; yanıt okunurken mikrofon kapalıdır.
- “Sesle işlem yap”, “Kaydet.” ve “Dinlemeyi durdur” ifadeleri desteklenir.
- Yanıt vermeyen konuşma hizmeti için süre sınırı ve anlaşılır hata eklendi.

APK’yı mevcut uygulamanın üzerine güncelleme olarak kurun. Önceki sürümle aynı test imzası doğrulandı. İlk kullanımda mikrofon izni verin; izin ekranından sonra dinleme durdu mesajı görünürse Konuşmaya başla düğmesine dokunun. “Markete yüz lira harcadım” diyerek taslağı kontrol edin, sonra “Kaydet” deyin.

47 otomatik kontrol, TypeScript, lint, Android/Hermes paketleme ve native derleme geçti. Android 11’de sentetik RecognitionService metin sonuçları ve sessiz TTS ile 7 native kontrol geçti; Türkçe dil/ses seçimi, ardışık komut, onay/iptal ve çift kayıt koruması doğrulandı. Fiziksel mikrofon tanıması ve duyulabilir Türkçe ses Samsung M31 üzerinde doğrudan test edilmedi.

Bu APK Android Debug test anahtarıyla imzalanmıştır; Play Store üretim sürümü değildir. Test hizmetleri ve test verileri uygulama APK’sına dahil değildir.
