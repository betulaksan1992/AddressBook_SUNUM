# AddressBook_SUNUM

Merhaba, Address Book projesi İstanbul - Beşiktaş Wissen Akademi'de Eğitmenlik yaptığım süreçte 302 sınıfım ile yazdık.Bu projede Trendyol,Getir gibi uygulamalardaki adres ekleme bölümünden esinlendik. Amacımız açık adres kaydı yapmaktır. Ayrıca gerçek hayata yaklaşmak ve istihdam sürecindeki hazır bulunuşluğu maksimum seviyeye getirebilmektir.

Bu projenin tüm hakları ben Betül Akşan'a,  302 sabah grubu sınıfımın öğrencilerine aittir. Burada projenin ekran resimlerini ve kaynak kodlardan bazı kod parçalarını aşağıda görebilirsiniz.


***PROJE HAKKINDA TEKNİK BİLGİLER:***

- Proje Visual Studio .Net 6 ASP.NET MVC CORE ile yazıldı.
- Proje Entity Framework Core Code-First yaklaşımıyla yazılmıştır.
- Projede AspnetCore Identity kullanarak üyelik sistemini yazdık.
- Projeyi 5 katman (EL,DAL,BLL,UI, AddressBookNeighborhoodsLoad) olarak yazdık.
-AddressBookNeighborhoodsLoad katmanı Console uygulaması olup Mahalle datasını eklemektedir. (70bin data bulunuyor)
- Projede İlleri  ve İlçeleri Excel dosyasını back-endde okuyarak veritabanına proje ilk ayağa kalktığında ekledik.
- Projede Adres listesi ve Adres Ekle - Adres Sil ekranları bulunuyor. 
- Adres Ekle sayfasındaki işlemleri AJAX ile yapmaktayız. Örneğin; ili seçtiğinde ilçeler sayfa yenilenmeden gelir. İlçeyi seçtiğinde mahalleler sayfa yenilenmeden gelir.
- Mahalleyi seçince o mahallenin posta kodunu APi'den çektik.  https://api.ubilisim.com/postakodu/il/34
- Proje gelişmeye açık olup zaman buldukça yeni sayfalar ya da yeni özellikler eklenecektir.

Ekran resimleri ve kaynak kodlardan bir parça aşağıda görebilirsiniz .

<img width="953" alt="01" src="https://user-images.githubusercontent.com/94163797/219572540-abd005fc-65f3-4be0-b576-0d21f0902b80.png">
<img width="960" alt="02" src="https://user-images.githubusercontent.com/94163797/219572552-edf5e923-5112-4529-93b3-a99fe2b277b3.png">
<img width="960" alt="03" src="https://user-images.githubusercontent.com/94163797/219572558-1bc3befc-494b-498a-95ce-6ee726aa3e69.png">
<img width="254" alt="04" src="https://user-images.githubusercontent.com/94163797/219574439-6f3c596d-6916-4fda-8b35-e23da3ddbc48.png">
<img width="956" alt="05" src="https://user-images.githubusercontent.com/94163797/219574456-075c80bd-eb93-4e6e-813e-6fa4de9292f8.png">
<img width="959" alt="06" src="https://user-images.githubusercontent.com/94163797/219574469-ec16aeee-8e9c-44ad-ac3d-0c7973c37eff.png">
