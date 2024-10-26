# Java Hesap Makinesi

Bu proje, Java dilinde yazılmış bir hesap makinesi uygulamasıdır. Kullanıcıya dört temel matematiksel işlemi yapma imkanı sunar: toplama, çıkarma, çarpma ve bölme. Toplama ve çarpma işlemleri için metod aşırı yükleme (method overloading) kullanılarak, iki veya üç parametreli işlemler yapılabilmektedir.

## Özellikler

- **Toplama:** İki veya üç sayı ile toplama işlemi yapabilirsiniz.
- **Çıkarma:** İki sayı arasındaki farkı hesaplar.
- **Çarpma:** İki veya üç sayı ile çarpma işlemi yapabilirsiniz.
- **Bölme:** İki sayı arasındaki bölme işlemini yapar ve sıfıra bölme hatasını kontrol eder.

## Gereksinimler

- **Java 8** veya daha yeni bir sürüm

## Kurulum

1. Projeyi bilgisayarınıza klonlayın veya `Main.java` dosyasını indirin.
2. Terminalde Java dosyasını derlemek için:

    ```bash
    javac Main.java
    ```

3. Uygulamayı çalıştırmak için:

    ```bash
    java Main
    ```

## Kullanım

1. Uygulama çalıştırıldığında bir işlem seçmeniz istenir:
   - 1: Toplama İşlemi
   - 2: Çıkarma İşlemi
   - 3: Çarpma İşlemi
   - 4: Bölme İşlemi
   - Çıkış için "q" girin.

2. Seçtiğiniz işlemi yapabilmek için gerekli sayıları girin.

3. İşlem sonucu ekranda görüntülenir.

## Kod Hakkında

- **Method Overloading:** `toplama` ve `carpma` metodları, iki veya üç parametre alacak şekilde aşırı yüklenmiştir. Bu sayede kullanıcı istediği sayıda (2 veya 3) parametre ile toplama ve çarpma işlemlerini gerçekleştirebilir.
- **Hata Kontrolü:** `bolme` metodunda, sıfıra bölme hatası kontrolü bulunmaktadır. Bu durumda bir uyarı mesajı görüntülenir ve `Double.NaN` döndürülür.
  
**Not:** Programın sonunda `scanner.close()` ile tüm `Scanner` nesneleri kapatılır.

## Katkıda Bulunma

Bu proje geliştirmeye açıktır. Katkıda bulunmak için:
1. Projeyi çatallayın.
2. Değişikliklerinizi yapın.
3. Bir çekme isteği gönderin.
