# Kursiyer Projesi

Bu proje, Java ile nesne yonelimli programlama mantigini gostermek icin hazirlanmis basit bir kursiyer otomasyonu ornegidir.

Uygulama; ilkokul ogrencisi, lise ogrencisi ve yetiskin ogrenci turlerine gore kurs bilgilerini, indirim oranlarini ve odenecek tutari hesaplayip ekrana yazdirir.

## Dosyalar

- `kursiyer/Kursiyer.java`: Ortak kursiyer bilgilerini ve ucret hesaplamasini tutan temel sinif.
- `kursiyer/IlkokulOgrencisi.java`: Ilkokul ogrencileri icin veli ve sinif bilgilerini ekler.
- `kursiyer/LiseOgrencisi.java`: Lise ogrencileri icin alan, ortalama ve takviye kontrolu ekler.
- `kursiyer/YetiskinOgrenci.java`: Yetiskin ogrenciler icin meslek ve ders programi bilgilerini ekler.
- `kursiyer/Main.java`: Konsoldan bilgi alip uygun kursiyer turunu olusturan ana program.

## Calistirma

```bash
javac kursiyer/*.java
java kursiyer.Main
```
