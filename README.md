# Otomatik Hazine Avcısı

## Proje Açıklaması

Otomatik Hazine Avcısı, Java programlama dili kullanılarak geliştirilmiş bir oyun projesidir. Oyuncu, otomatik olarak hareket eden bir karakteri kontrol ederek, engellerle dolu bir ortamda
tüm hazineleri toplamaya çalışır.

## Oyun Mekaniği

- **Otomatik Hareket**: Karakter otomatik olarak hareket eder ve patika arama algoritmaları kullanarak en kısa yolu bulur
- **Engeller**: 
  - Hareketli engeller rastgele hareket eder
  - Hareketsiz engeller karakterin yolunu engeller
  - Herhangi bir engele çarpma durumunda oyun kaybedilir
- **Hazine Sandıkları**: Farklı türlerde hazine sandıkları (altın, zümrüt, gümüş, bakır) toplanarak puan kazanılır
- **Dinamik Harita**: Her oyun başlangıcında yeni bir harita oluşturulur ve engeller ile hazineler rastgele yerleştirilir
 
## Kullanılan Teknolojiler

- **Programlama Dili**: Java
- **Grafiksel Arayüz**: Swing ve AWT kütüphaneleri
- **Görsel İşleme**: ImageIO kütüphanesi
- **Algoritma**: Patika arama algoritmaları (en kısa yol bulma)

## Özellikler

- Kullanıcı dostu grafiksel arayüz
- Basit kontrol paneli (başlatma, duraklatma, yeniden başlatma)
- Modüler kod yapısı
- Nesne yönelimli programlama prensipleri
- Yüksek kod kalitesi ve test edilmiş yapı

## Kurulum ve Çalıştırma

### Gereksinimler
- Java Development Kit (JDK) 8 veya üzeri
- Java çalışma ortamı (JRE) 

### Kurulum
1. Projeyi bilgisayarınıza indirin
2. Java IDE'nizde projeyi açın (Eclipse, IntelliJ IDEA, NetBeans)
3. Gerekli kütüphanelerin yüklendiğinden emin olun
4. Ana sınıfı çalıştırın

### Çalıştırma
```bash
javac *.java
java MainClass
```

## Kullanım

1. Oyunu başlatın
2. "Yeni Harita Oluştur" butonuna tıklayın
3. "Oyunu Başlat" butonuna tıklayın
4. Karakterin otomatik olarak hareket etmesini izleyin
5. Tüm hazineleri toplamaya çalışın
6. Gerektiğinde oyunu duraklatın veya yeniden başlatın

## Proje Yapısı

```
src/
├── main/
│   ├── Game.java          # Ana oyun sınıfı
│   ├── Character.java     # Karakter sınıfı
│   ├── Obstacle.java      # Engel sınıfı
│   ├── Treasure.java      # Hazine sınıfı
│   ├── Map.java           # Harita sınıfı
│   └── GUI.java           # Grafiksel arayüz
├── resources/
│   └── images/            # Oyun görselleri
└── README.md
```


## Gelecek Geliştirmeler

- Farklı zorluk seviyeleri
- Ses efektleri
- Çoklu karakter desteği
- Online skor tablosu
- Özel harita editörü

## Katkıda Bulunma

Bu proje açık kaynaklı olarak geliştirilmiştir. Katkıda bulunmak için:

1. Projeyi fork edin
2. Yeni bir branch oluşturun
3. Değişikliklerinizi yapın
4. Test edin
5. Pull request gönderin

## İletişim

**Geliştirici**: Ümit Dansuk  
**Kurum**: Kocaeli Üniversitesi Bilgisayar Mühendisliği 

## Referanslar

- [Oracle Java Dokümantasyonu](https://docs.oracle.com/javase/)
- [Java Tutorial for Beginners](https://www.w3schools.com/java/)
- [Java SE Dokümantasyonu](https://docs.oracle.com/en/java/javase/)
- Java Design Patterns (Gang of Four)
- [Java EE Dokümantasyonu](https://docs.oracle.com/javaee/)

---

*Bu proje, bilgisayar mühendisliği eğitimi kapsamında geliştirilmiş bir örnek projedir.*
