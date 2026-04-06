# Dinamik Tablo Oluşturucu

Bu proje, kullanıcının girdiği satır ve sütun sayılarına göre dinamik olarak renkli bir tablo oluşturan basit bir PHP uygulamasıdır.

## Dosya Yapısı

*   **index.php**: Kullanıcının satır ve sütun sayılarını girdiği ana form sayfası.
*   **tablo.php**: Formdan gelen verileri alıp, her hücresi rastgele bir arka plan rengine sahip HTML tablosunu oluşturan sayfa.

## Kullanılan Teknolojiler

*   **PHP**: Sunucu taraflı mantık ve dinamik tablo oluşturma için.
*   **HTML/CSS**: Sayfa yapısı için.
*   **Bootstrap 5**: Modern ve düzenli bir görünüm için.

## Nasıl Çalışır?

1.  `index.php` sayfasında istediğiniz satır ve sütun sayısını girin.
2.  "Tabloyu Oluştur" butonuna basın.
3.  `tablo.php` sayfasında, her hücresi `rand(0, 255)` fonksiyonu ile rastgele atanmış RGB renklerine sahip tablonuz görüntülenecektir.
