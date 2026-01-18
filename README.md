# Basit ATM Simülasyonu (Java) 🏧

Bu proje, Java programlama dili kullanılarak geliştirilmiş, konsol tabanlı bir ATM (Bankamatik) simülasyonudur. Kullanıcı kimlik doğrulama, bakiye yönetimi ve menü tabanlı işlem yapısı üzerine kurulmuştur.

## 🚀 Özellikler

Bu uygulama aşağıdaki temel bankacılık işlemlerini simüle eder:

* **Güvenli Giriş Sistemi:** Kullanıcının sisteme girmek için 3 deneme hakkı vardır. Hatalı girişlerde kalan hak gösterilir.
* **Bakiye Sorgulama:** Mevcut bakiyeyi görüntüleme.
* **Para Çekme:** Bakiye kontrolü yapılarak para çekme işlemi (Yetersiz bakiye uyarısı içerir).
* **Para Yatırma:** Hesaba para ekleme.
* **Şifre Değiştirme:** Mevcut giriş şifresini güncelleme.
* **Döngüsel Menü:** Kullanıcı "Çıkış" diyene kadar işlemler devam eder.

## 🛠️ Kullanılan Teknolojiler ve Yapılar

* **Dil:** Java
* **Girdi Alma:** `java.util.Scanner` sınıfı.
* **Kontrol Yapıları:** `if-else if-else` blokları.
* **Döngüler:**
    * `do-while`: Kullanıcı şifreyi doğru girene veya hakkı bitene kadar döngü kurmak için.
    * `do-while`: Ana menünün kullanıcı çıkış yapana kadar ekranda kalması için.

## 💻 Kurulum ve Çalıştırma

Proje dosyasını bilgisayarınıza indirdikten sonra terminal veya komut satırı üzerinden şu adımları izleyebilirsiniz:

1.  Projeyi derleyin:
    ```bash
    javac dongulerCalısma.java
    ```

2.  Projeyi çalıştırın:
    ```bash
    java dongulerCalısma
    ```

## 📝 Varsayılan Bilgiler

* **Başlangıç Şifresi:** 6025
* **Başlangıç Bakiyesi:** 1000 TL

---
**Geliştirici:** Nuh Dağ
