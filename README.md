# 2026 Turkey Salary & Raise Calculator

2026 yılı Türkiye vergi düzenlemelerine göre güncellenmiş, gizlilik odaklı ve gerçek net maaş verilerini hesaplayan web tabanlı bir uygulama.

## Proje Amacı

Bu uygulama, çalışanların "Şirketim %X oranında zam yaptığında, yılın her ayında elime tam olarak ne kadar net ücret geçecek?" sorusuna yanıt vermek amacıyla geliştirilmiştir. Türkiye'deki kümülatif vergi dilimi yapısını baz alarak en doğru aylık projeksiyonu sunmayı hedefler.

## Öne Çıkan Özellikler

* **Kümülatif Vergi Hesaplama:** 2026 gelir vergisi dilimlerine tam uyumlu otomatik hesaplama motoru.
* **12 Aylık Detaylı Döküm:** Ocak ayından Aralık ayına kadar vergi dilimi geçişlerini gösteren aylık net maaş tablosu.
* **Yasal Kesintiler:** SGK İşçi Payı (%14), İşsizlik Sigortası (%1), Gelir Vergisi ve Damga Vergisi (%0.759) kalemlerinin ayrıntılı dökümü.
* **Gizlilik ve Güvenlik:** Hiçbir veri depolanmaz veya dış sunucuya aktarılmaz; tüm işlemler tamamen kullanıcı tarayıcısında (offline) gerçekleşir.
* **Modern Kullanıcı Deneyimi:** Karanlık mod desteği, mobil uyumlu tasarım ve sade bir arayüz.

## Aylık Maaş Değişiminin Nedeni

Türkiye'deki gelir vergisi sistemi artan oranlı bir yapıya sahiptir. Yılın başında daha düşük vergi diliminde başlayan gelir, yıl içinde kümülatif toplamın artmasıyla üst dilimlere (Örneğin %15'ten %20 ve %27'ye) geçer. Bu araç, Ocak ve Aralık ayları arasındaki bu farkı gerçekçi bir şekilde hesaplar.

## Kullanım Talimatları

1. `index.html` dosyasını yerel sürücünüze indirin.
2. Dosyayı herhangi bir modern internet tarayıcısı (Chrome, Safari, Edge vb.) ile açın.
3. Mevcut brüt maaşınızı ve beklenen zam oranını ilgili alanlara girin.
4. **Hesapla** butonuna tıklayarak yıllık projeksiyonunuzu inceleyin.

## Teknik Mimari

Uygulama, yüksek performans ve taşınabilirlik amacıyla herhangi bir framework veya harici kütüphane kullanılmadan **saf HTML5, CSS3 ve JavaScript (Vanilla JS)** kullanılarak inşa edilmiştir. Tek bir dosya halindedir ve internet bağlantısı gerektirmez.

## 2026 Tahmini Vergi Dilimleri

| Vergi Oranı | Gelir Aralığı |
| :--- | :--- |
| **%15** | 110.000 TL'ye kadar |
| **%20** | 110.000 TL - 230.000 TL arası |
| **%27** | 230.000 TL - 580.000 TL arası |
| **%35** | 580.000 TL - 3.000.000 TL arası |
| **%40** | 3.000.000 TL üzeri |

## Geliştirici

**Metin Demirtel** VP of Demand & Value Management | Banking & Analytics Professional

## Lisans

MIT Lisansı kapsamında serbestçe kullanılabilir, geliştirilebilir ve dağıtılabilir.
