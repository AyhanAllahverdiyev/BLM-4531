# Adres Defteri .NET Projesi

Bu proje, temel bir adres defteri uygulamasının adım adım nasıl oluşturulacağını içeren bir rehber sunulmaktadır.

## İçindekiler
- [Başlangıç](#başlangıç)
  - [Proje Oluşturuluyor](#proje-oluşturuluyor)
  - [Form Tasarımı](#form-tasarımı)
- [Veri Yapısı](#veri-yapısı)
  - [İletişim Sınıfı](#iletisim-sınıfı)
  - [Kişi Listesi](#kisi-listesi)
- [Temel İşlemler](#temel-islemler)
  - [Kişi Ekleniyor](#kisi-ekleniyor)
  - [Kişiler Görüntüleniyor](#kisiler-goruntuleniyor)
  - [Kişi Siliniyor](#kisi-siliniyor)
- [Veri Saklama](#veri-saklama)
  - [Veri Kaydediliyor](#veri-kaydediliyor)
  - [Veri Yükleniyor](#veri-yukleniyor)
- [Ek Geliştirmeler](#ek-gelistirmeler)
  - [Doğrulama](#dogrulama)
  - [Form Temizleniyor](#form-temizleniyor)
  - [Hata Ayıklama](#hata-ayıklama)
- [Test ve Dökümantasyon](#test-ve-dokumantasyon)
  - [Uygulama Test Ediliyor](#uygulama-test-ediliyor)
  - [Dökümantasyon](#dokumantasyon)
  - [Kullanıcı Dostu Mesajlar](#kullanici-dostu-mesajlar)
  - [Kod Yeniden Düzenleniyor](#kod-yeniden-duzenleniyor)
  - [Geliştirmeler](#gelistirmeler)
  - [Kapsamlı Testler](#kapsamli-testler)
- [Sonuç](#sonuc)

## Başlangıç

### Proje Oluşturuluyor
- Visual Studio kullanılarak yeni bir Windows Forms Uygulaması projesi oluşturuluyor.

### Form Tasarımı
- Ana form, ad, telefon ve e-posta giriş alanları ile tasarlanıyor.
- Ekleme, güncelleme, silme ve kişileri görüntüleme düğmeleri ekleniyor.

## Veri Yapısı

### İletişim Sınıfı
- İletişimi temsil etmek için yeni bir sınıf oluşturuluyor.
- Bu sınıf, ad, telefon ve e-posta gibi özellikleri içeriyor.

### Kişi Listesi
- Formun kodunda, kişileri saklamak için bir `List<Contact>` oluşturuluyor.

## Temel İşlemler

### Kişi Ekleniyor
- "Ekle" düğmesi için kod uygulanıyor.
- Yeni bir İletişim nesnesi oluşturuluyor ve liste ekleniyor.

### Kişiler Görüntüleniyor
- "Kişileri Görüntüle" düğmesi için kod uygulanıyor ve kişiler bir liste veya tablo ile gösteriliyor.

### Kişi Siliniyor
- "Sil" düğmesi için kod uygulanıyor ve seçilen kişi listeden kaldırılıyor.
- 
## Veri Saklama

### Veri Kaydediliyor
- Program kapatıldığında iletişim listesi bir metin dosyasına kaydediliyor.

### Veri Yükleniyor
- Program başladığında iletişim verileri metin dosyasından yükleniyor.

## Ek Geliştirmeler

### Doğrulama
- Kullanıcıların geçerli veri girdiğinden emin olmak için temel giriş doğrulaması ekleniyor.

### Form Temizleniyor
- "Temizle" düğmesi eklenerek giriş alanları sıfırlanıyor.

### Hata Ayıklama
- Dosya yükleme sorunları veya geçersiz veri gibi hatalar nazikçe ele alınıyor.

## Test ve Dökümantasyon

### Uygulama Test Ediliyor
- Uygulama, örnek veri ile test ediliyor ve doğru çalıştığından emin olunuyor.

### Dökümantasyon
- Kodun daha iyi anlaşılabilmesi için yorumlar ekleniyor.
 

### Kod Yeniden Düzenleniyor
- Kod temizleniyor ve optimize ediliyor.

### Geliştirmeler
- Kullanıcı deneyimini artırmak için arama veya sıralama gibi ek özellikler ekleniyor.

### Kapsamlı Testler
- Uygulama, çeşitli senaryolarla test ediliyor ve hatalar tespit ediliyor.

## Sonuç

Bu adımlar, .NET'te temel bir adres defteri projesi oluşturmak için gereken temel temelleri kapsamaktadır.
