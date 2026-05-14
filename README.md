# NYAT ÖDEV - Akıllı Tedarik ve Lojistik Yönetim Sistemi

Bu teslim paketi ASP.NET Core MVC mimarisine göre düzenlenmiştir. Projede ürün/stok yönetimi, sipariş durum akışı, ödeme stratejileri, kargo firmaları, ek kargo hizmetleri, kritik stok bildirimi, rol bazlı yetkilendirme ve sistem loglama bulunmaktadır.

## Çalıştırma

1. Visual Studio ile `NYAT_ODEV.sln` dosyasını açın. Yeni Visual Studio sürümlerinde isterseniz `NYAT_ODEV.slnx` de kullanılabilir.
2. Başlangıç projesi olarak `NYAT_ODEV` seçili olmalıdır.
3. Uygulamayı çalıştırın.
4. İlk ekranda `Demo Giriş Yap` bağlantısı üzerinden rol seçerek sisteme girin.

## Demo roller

- Admin: tüm modüller ve loglar.
- DepoGorevlisi: ürün/stok ve sipariş durum yönetimi.
- Kurye: kargo yönetimi ve kargodaki siparişlerin iade süreci.
- Musteri: sipariş oluşturma ve ödeme.

## Testler

`NYAT_ODEV.Tests` klasöründe harici NuGet paketi gerektirmeyen basit bir birim test çalıştırıcısı vardır.

```bash
cd NYAT_ODEV.Tests
dotnet run
```

## Teslim belgeleri

`Belgeler` klasöründe analiz raporu, tasarım raporu, test raporu ve UML diyagram taslakları bulunmaktadır.
