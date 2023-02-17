# AddressBook_SUNUM

Merhaba, MembershipIntro İstanbul - Beşiktaş Wissen Akademi'de Eğitmenlik yaptığım süreçte 302 sınıfım ile yazdık.Bu projede Trendyol,Getir gibi uygulamalardaki adres ekleme bölümünden esinlendik. Amacımız açık adres kaydı yapmaktır. Ayrıca gerçek hayata yaklaşmak ve istihdam sürecindeki hazır bulunuşluğu maksimum seviyeye getirebilmektir.

Bu projenin tüm hakları ben Betül Akşan'a,  302 sabah grubu sınıfımın öğrencilerine aittir. Burada projenin ekran resimlerini ve kaynak kodlardan bazı kod parçalarını aşağıda görebilirsiniz.


***PROJE HAKKINDA TEKNİK BİLGİLER:***

- Proje Visual Studio .Net 6 ASP.NET MVC CORE ile yazıldı.
- Proje Entity Framework Core Code-First yaklaşımıyla yazılmıştır.
- Projede AspnetCore Identity kullanarak üyelik sistemini yazdık.
- Projeyi 4 katman (EL,DAL,BLL,UI) olarak yazdık.
- Projede İlleri  ve İlçeleri Excel dosyasını back-endde okuyarak veritabanına proje ilk ayağa kalktığında ekledik.
- Projede Adres listesi ve Adres Ekle - Adres Sil ekranları bulunuyor. 
- Adres Ekle sayfasındaki işlemleri AJAX ile yapmaktayız. Örneğin; ili seçtiğinde ilçeler sayfa yenilenmeden gelir. İlçeyi seçtiğinde mahalleler sayfa yenilenmeden gelir.
- Mahalleyi seçince o mahallenin posta kodunu APi'den çektik.  https://api.ubilisim.com/postakodu/il/34
- Proje gelişmeye açık olup zaman buldukça yeni sayfalar ya da yeni özellikler eklenecektir.

Ekran resimleri ve kaynak kodlardan bir parça aşağıda görebilirsiniz .

