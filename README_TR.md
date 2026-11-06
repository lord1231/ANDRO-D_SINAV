# TAHTA KALEM SINAV AI — Android APK projesi

## İçerik
- 8 ders, her ders için 20 başlangıç sorusu (toplam 160).
- 1. ve 2. dönem etiketleri.
- 5/10/20 soruluk sınav seçimi.
- Otomatik puan, doğru/yanlış/boş ve cevap incelemesi.
- Soru havuzu ve sınav geçmişi cihazda saklanır (WebView localStorage).
- JSON yedek dışa/içe aktarma.

## APK üretme (yalnızca Android telefonla)
1. GitHub'da yeni bir repository oluşturun.
2. Bu ZIP'i telefonda açıp içindeki dosyaları repository'nin ana dizinine yükleyin. `.github/workflows/build.yml` dosyasının da yüklendiğinden emin olun.
3. GitHub repository > Actions sekmesine girin.
4. `Build Android APK` iş akışını seçip `Run workflow` düğmesine dokunun (veya ilk push ile otomatik başlar).
5. İşlem tamamlanınca ilgili çalışmayı açın. Artifacts bölümündeki `tahta-kalem-sinav-ai-apk` dosyasını indirin.
6. ZIP içinden `app-debug.apk` dosyasını çıkarın ve Android'de açarak kurun. Gerekirse tarayıcıya/dosya yöneticisine bu kaynaktan yükleme izni verin.

## Önemli
- Bu, kurulabilir APK üretmek için hazırlanmış Android Studio/Gradle kaynak projesidir; burada doğrudan imzalı mağaza APK'sı üretilmedi.
- İlk sürümde soru metinleri başlangıç havuzudur. Öğretim programı ve dönem kazanımları okulun kullandığı güncel yıllık plana göre öğretmen/veli tarafından kontrol edilmelidir.
- Uygulama kaldırılırsa cihazdaki geçmiş ve düzenlemeler silinebilir. Düzenli JSON yedeği alın.
