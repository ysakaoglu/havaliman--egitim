# Yer Hizmetleri Eğitim Rehberi

Tek dosyada çalışan, mobil uyumlu ve interaktif bir infografik web sitesi.

## İçerik

- 8 eğitim modülü ve açılır detay kartları
- ICAO, IATA, airside, landside ve apron kavramları
- Aranabilir ve kategorilere ayrılmış İngilizce ifade bankası
- Tarayıcı üzerinden İngilizce sesli telaffuz
- Fazla bagaj problem çözme akışı
- Baştan sona check-in role-play simülasyonu
- 8 soruluk mini sınav
- Cihazda kaydedilen eğitim öncesi kontrol listesi
- Açık/koyu tema ve yazdırma/PDF görünümü

## Bilgisayarda açma

`index.html` dosyasına çift tıklaman yeterlidir. İnternet bağlantısı gerekmez.

## GitHub Pages'ta yayınlama

1. GitHub'da yeni ve herkese açık bir repository oluştur.
2. Bu klasördeki `index.html` dosyasını repository'nin ana dizinine yükle.
3. Repository içinde **Settings → Pages** bölümüne git.
4. **Build and deployment** altında **Deploy from a branch** seç.
5. Branch olarak `main`, klasör olarak `/ (root)` seçip **Save** düğmesine bas.
6. GitHub kısa süre sonra `https://kullaniciadi.github.io/repository-adi/` biçiminde yayın adresini gösterecektir.

## Google Sites'a ekleme

Google Sites doğrudan HTML dosyası barındırmaz. Önce siteyi GitHub Pages'ta yayınla, ardından:

1. Google Sites düzenleme ekranında **Ekle → Yerleştir** seçeneğini aç.
2. **URL ile** seçeneğine GitHub Pages adresini yapıştır.
3. Önizlemeyi kabul et ve gömülü alanı sayfa genişliğine göre büyüt.

## Düzenleme

Metinler, sorular ve İngilizce ifadeler `index.html` dosyasının sonundaki JavaScript dizilerinde bulunur:

- `modules`
- `phrases`
- `roleDialog`
- `quiz`
- `checklistItems`

Herhangi bir sunucu veya paket kurulumu gerektirmez.

## Not

Bu çalışma paylaşılan ChatGPT sohbetinden düzenlenmiş gayriresmî bir tekrar rehberidir. Havayolu ve yer hizmetleri şirketlerinin resmî eğitimleri ve prosedürleri esas alınmalıdır.

Son güncelleme
