# Collatz Hipotezi 

## Proje Hakkında
Bu proje, Nesne Tabanlı Programlama dersi kapsamında Python kullanılarak hazırlanmış bir matematiksel döngü uygulamasıdır. Program, Collatz hipotezinin kurallarını pozitif tam sayılara uygulayarak sayı dizisini ve 1'e ulaşmak için gereken işlem sayısını hesaplar.

## Proje Ne Yapar?
- Kullanıcıdan pozitif bir tam sayı girmesini ister.
- `while` döngüsü kullanarak sayı 1 olana kadar işlemleri tekrarlar.
- Sayı çiftse 2'ye böler.
- Sayı tekse 3 ile çarpıp 1 ekler.
- Her işlem sonucunda oluşan sayıyı ekrana yazdırır.
- `steps` değişkeniyle gerçekleştirilen işlem sayısını hesaplar.
- Sayı 1'e ulaştığında döngüyü sonlandırır.

## Proje Neden Faydalıdır?
Bu çalışma, Python'da `while` döngüsünün, `if-else` koşul ifadelerinin, mod alma (`%`), tam sayı bölme (`//`) ve artırmalı atama (`+=`) operatörlerinin kullanımını öğrenmek amacıyla hazırlanmıştır.

Ayrıca Collatz hipotezinin matematiksel kurallarının programlama yoluyla incelenmesini sağlar.

## Proje Nasıl Çalıştırılır?
1. Bilgisayarınızda Python 3'ün yüklü olduğundan emin olun.
2. Proje dosyasını Python IDLE üzerinden açın.
3. `F5` tuşuna basarak programı çalıştırın.
4. Pozitif bir tam sayı girin.
5. Oluşan sayı dizisini ve toplam işlem sayısını görüntüleyin.

## Örnek Kullanım

**Girdi ve Çıktı:**

```text
Enter a positive number: 6
3
10
5
16
8
4
2
1
steps = 8
```

**Not:** Collatz hipotezi, her pozitif tam sayının bu işlemler sonucunda 1'e ulaşacağını öne sürmektedir. Ancak hipotez henüz matematiksel olarak kanıtlanmamıştır.

## Nereden Yardım Alınabilir?
Python hakkında ayrıntılı bilgi almak için [Python Resmî Dokümantasyonu](https://docs.python.org/3/) incelenebilir.

## Projeyi Kim Geliştiriyor ve Sürdürüyor?
Bu proje, Nesne Tabanlı Programlama dersi kapsamında LAB çalışması olarak hazırlanmıştır.

## Lisans
Bu proje MIT Lisansı kapsamında paylaşılmaktadır. Lisans koşulları için `LICENSE` dosyasını inceleyebilirsiniz.
