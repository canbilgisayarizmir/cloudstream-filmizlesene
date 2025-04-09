# Filmizlesene Cloudstream Eklentisi

Bu eklenti, [fullhdfilmizlesene.de](https://www.fullhdfilmizlesene.de) sitesini Cloudstream uygulamasında kullanmanızı sağlar.

## Özellikler

- Son eklenen filmleri görüntüleme
- Film arama
- Film detaylarını görüntüleme
- Film izleme

## Kurulum

1. Cloudstream uygulamasını açın
2. Ayarlar > Eklentiler'e gidin
3. "Depo ekle" seçeneğine tıklayın
4. Aşağıdaki URL'yi yapıştırın:
```
https://raw.githubusercontent.com/canbilgisayarizmir/cloudstream-filmizlesene/builds/repo.json
```

## Geliştirme

Bu eklenti Kotlin ile geliştirilmiştir ve Cloudstream eklenti API'sini kullanmaktadır.

### Gereksinimler

- Android Studio
- JDK 11 veya üzeri
- Kotlin bilgisi

### Derleme

```bash
./gradlew assembleDebug
``` 