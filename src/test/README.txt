1.  Singleton driver üreten bir Driver classi olusturun

2.  Utils icine Parent class"i oluturun
    WebDriver, WebDriverWait ve methodlariniz bu classda olacak
    Test classlariniz Parent class"i extend edecek

3.  Parent class"da olacaklar
    fields : driver, wait,
    methodlar : clickTo(); sendKeysTo(); waitFor(); (konusalim)

4.  "http://opencart.abstracta.us/index.php?route=common/home" adresine gidip
    a.   menu isimlerini assert edelim


5.  AnaMenu üzerine hover yapinca alt menüsü varsa acildigini assert edin.
    ParentClass"a bir hover methodu ekleyin.

--------------------------------------------------------------------
    Senaryo 1
      1- Siteyi açınız.
      2- Login olun, Login oldugunuzu assert edin.
      3- Newsletter  Subscribe edin.
      4- Newsletter UnSubscribe Islemi yapin.


    Senaryo 2
      1- Siteyi açınız.
      2- Edit Account a tıklatınız.
      3- Yeni isim ve soyisim göndererek Continue yapınız.
      4- İşlem sonucunu kontrol ediniz.
      5- Bu işlemi 2 kez çalıştırarak eski haline getiriniz.




    mxl"de  suit iinde 2 test olacak

    test1 TestGrup1

    test2 TestGrup2, TestGrup3
        test2 calistirilmayacak













/*
      1- Siteyi açınız.
      2- Edit Account a tıklatınız.
      3- Yeni isim ve soyisim göndererek Continue yapınız.
      4- İşlem sonucunu kontrol ediniz.
      5- Bu işlemi 2 kez çalıştırarak eski haline getiriniz.
     */

