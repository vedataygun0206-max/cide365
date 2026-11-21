# Cide365

Cide365, Cide'deki yerel üreticileri müşterilerle buluşturmayı hedefleyen bağımsız bir pazaryeri projesidir.

## İş modeli

- Üretici üyeliği ücretsizdir.
- Platform komisyonu, komisyona esas tamamlanmış ürün satış tutarı üzerinden %5 olarak planlanmıştır.
- Kargo ve ödeme kuruluşu ücretleri komisyon dışında ayrı gösterilir.
- Müşteri ödemesi internetten kartla yapılacaktır.
- Kargo: üreticiden adresten alım veya anlaşmalı şubeye teslim.

## Teknoloji

- Next.js App Router
- React
- TypeScript
- İlk sürüm: mobil uyumlu web arayüzü

Veritabanı, kimlik doğrulama, ödeme ve kargo entegrasyonları henüz eklenmemiştir.

## Gereksinimler

- Node.js 20.9 veya üzeri
- npm
- GitHub hesabı

## Yerel çalıştırma

```bash
npm install
npm run dev
```

Tarayıcıda `http://localhost:3000` adresini açın.

## GitHub'a yükleme

1. GitHub'da `cide365` adında **Private** bir repository oluşturun.
2. Bu ZIP dosyasını bilgisayarınıza çıkarın.
3. Proje klasörünü GitHub deposuna yükleyin veya Git ile gönderin.
4. `main` dalını koruyun; geliştirmeleri `develop` dalında yapın.

## Bulut geliştirme

GitHub deposunu açın:
1. `Code` menüsüne girin.
2. `Codespaces` sekmesini açın.
3. `Create codespace on main` seçeneğini kullanın.
4. Terminalde `npm install` ve `npm run dev` komutlarını çalıştırın.

GitHub Codespaces kullanılabilirliği ve ücretsiz kullanım kotası hesaba göre değişebilir.

## Güvenlik

- Gerçek API anahtarlarını veya şifreleri Git'e yüklemeyin.
- Gizli bilgileri Codespaces Secrets veya dağıtım platformunun secret manager alanında tutun.
- Kart bilgilerini Cide365 sunucusunda saklamayın; lisanslı ödeme kuruluşunun barındırılan ödeme akışını kullanın.

## Geliştirme aşamaları

1. Ana sayfa ve kategori arayüzü
2. Üyelik ve rol bazlı erişim
3. Üretici mağazası ve ürün yönetimi
4. Sepet ve siparişler
5. Lisanslı ödeme kuruluşu ve alt üye işyeri akışı
6. Kargo firması entegrasyonu
7. Yönetici paneli, iade ve destek
8. Güvenlik, mevzuat ve pilot test

## Durum

`v0.1.0` başlangıç arayüzü. Canlı pazaryeri, ödeme, üyelik veya kargo sistemi değildir.
