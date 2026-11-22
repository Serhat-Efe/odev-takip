# Ödev Takip

Ödev Takip, birden fazla ders alan üniversite öğrencileri için geliştirilmiş basit bir ödev planlama uygulamasıdır.

Bir üniversite ödevi için kaynak kod, rapor, sunum veya grafik gibi birden fazla dosya hazırlamak gerekebilir. Öğrenci ödevini tamamen bitirmeden önce bazı dosyaları hazırlamış, bazılarını ise henüz tamamlamamış olabilir. Uygulama, ödevlerin son teslim tarihleriyle birlikte hazırlanması gereken dosyaların durumunu tek yerde takip etmeyi sağlar.

## Canlı uygulama

Uygulamayı tarayıcıda açmak için:

https://serhat-efe.github.io/odev-takip/

## Görev panosu

Projenin görevleri GitHub Projects panosunda takip edilmektedir:

https://github.com/users/Serhat-Efe/projects/1

Pano özel olarak tutulmaktadır. Değerlendirme için `musanmaz` kullanıcısına okuma erişimi verilmiştir.

## Geliştirilen özellikler

### 1. Ödevi dosyalarıyla birlikte planlama

Öğrenci ders adını, ödev başlığını ve son teslim tarihini girer. Hazırlaması gereken dosyaların adlarını virgülle ayırarak yazar. Kaydedilen ödev ve dosyalar aynı kart içinde görüntülenir.

### 2. Hazırlanan dosyaları işaretleme

Öğrenci hazırladığı dosyaları ayrı ayrı işaretleyebilir. Uygulama, hazır dosya sayısını toplam dosya sayısıyla birlikte gösterir. Örneğin iki dosyadan biri hazırsa sayaç `1/2 hazır` olarak güncellenir.

## Projeyi çalıştırma

Uygulama yalnızca HTML, CSS ve JavaScript kullanılarak hazırlanmıştır. Kurulum veya ek bir paket gerekmez.

1. Depoyu bilgisayarınıza indirin.
2. İndirilen klasördeki `index.html` dosyasını bir internet tarayıcısıyla açın.

Uygulama yukarıdaki canlı bağlantı üzerinden de doğrudan kullanılabilir.

## Özellikleri deneme

### Ödev planlama özelliği

1. Ders adı alanına `Veri Yapıları` yazın.
2. Son teslim tarihi olarak `30.11.2026` tarihini seçin.
3. Ödev başlığı alanına `Sıralama algoritmalarını karşılaştırma` yazın.
4. Hazırlanacak dosyalar alanına `Kaynak kod, Çalışma süresi grafiği` yazın.
5. `Ödevi kaydet` düğmesine basın.
6. Ders adının, ödev başlığının, teslim tarihinin ve iki dosyanın aynı ödev kartında göründüğünü doğrulayın.

### Dosya işaretleme özelliği

1. Eklenen ödevde yalnızca `Kaynak kod` kutucuğunu işaretleyin.
2. Sayacın `1/2 hazır` olarak güncellendiğini doğrulayın.
3. `Çalışma süresi grafiği` kutucuğunun işaretsiz kaldığını doğrulayın.

## Kullanılan teknolojiler

- HTML
- CSS
- JavaScript
- GitHub Projects
- GitHub Pages
