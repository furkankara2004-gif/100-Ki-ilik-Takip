# 100 Kişilik Takip — Android proje

Bu proje HTML takip uygulamasını Android WebView içinde çalıştırır. İşaretlemeler WebView yerel depolamasında saklanır.

## APK üretimi (GitHub Actions)
1. Bu ZIP'i açıp içeriğini yeni bir GitHub deposuna yükleyin.
2. Depoda **Actions** sekmesine girin.
3. **Build Android APK** iş akışını çalıştırın (veya `main` dalına push edin).
4. Tamamlanınca iş akışının **Artifacts** bölümünden `100-kisilik-takip-apk` dosyasını indirin.
5. ZIP içindeki `app-debug.apk` dosyasını Android telefona aktararak kurun. İlk kurulumda Android, bilinmeyen kaynaklardan yüklemeye izin istemesi halinde ilgili izni açmanız gerekir.

Bu çıktı test/kişisel kullanım için debug APK'dır; Play Store yayını için ayrıca release imzalama gerekir.
