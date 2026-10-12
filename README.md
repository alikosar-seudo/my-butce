# My Bütçe — onay sorusunun seslendirilmesi

Kayıt onay sorusunun genel sesli yanıt ayarı kapalıyken sessiz kalması giderildi.

Kayıt soruları, onay ve iptal sonuçları sesli okunur. Taslakta Soruyu tekrar dinle düğmesi eklendi.

“500 TL market alışverişi yaptım” → tutar, kategori, hesap ve tarih okunur; “Onaylıyor musun?” sorulur.
“Onaylıyorum” → kaydeder. “Onaylamıyorum” / “İptal et” → kaydetmeden iptal eder.
Eksik bilgi sorulur; düzeltmeler tekrar onaya sunulur. Gelir ve transfer de aynı onay akışını kullanır.

[Android test APK indir](https://raw.githubusercontent.com/alikosar-seudo/my-butce/v0.1.3-test/my-butce-test.apk)

Mevcut uygulamanın üzerine güncelleme olarak kurulabilir. Android sürüm: 1.0.3 (kod 4).
31 core ve 27 UI/hook testi geçti; typecheck, lint ve native APK derlemesi başarılı. Bu sürüm fiziksel telefonda henüz test edilmedi.
APK test anahtarıyla imzalıdır; Google Play üretim sürümü değildir.
SHA256: `a259c2083d8b44dfc854b4ddd2336196f2a8bc2ce9b9975c55c64366526b28b6`
