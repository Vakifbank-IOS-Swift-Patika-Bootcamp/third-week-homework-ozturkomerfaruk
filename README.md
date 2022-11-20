# Third-Week-Homework

* [1. Soru Açıklamaları](https://github.com/Vakifbank-IOS-Swift-Patika-Bootcamp/third-week-homework-ozturkomerfaruk/blob/main/README.md#1-soru)
* [2. Soru Açıklamaları](https://github.com/Vakifbank-IOS-Swift-Patika-Bootcamp/third-week-homework-ozturkomerfaruk/blob/main/README.md#2-soru)
* [3. Soru Açıklamaları](https://github.com/Vakifbank-IOS-Swift-Patika-Bootcamp/third-week-homework-ozturkomerfaruk/blob/main/README.md#3-soru)


1- Şirket Playground Yazılımının Xcode ile projelendirilmesi yapılacaktır. Aşağıdaki özelliklerin bulunması gerekmektedir:
--
<pre>
• Giriş Ekranında;

◦ Şirketin bilgileri yer almalıdır.
◦ Şirket gelir gider eklemeleri bu ekrandan yapılabilmelidir.
◦ Şirket maaş ödemesi bu ekrandan yapılabilmelidir.
◦ Çalışan ekle butonu olmalıdır.(Çalışan ekleme ekranı açılmalı)
◦ Çalışan listele butonu olmalı.(Çalışan listesi ekranı açılmalı)

• Çalışan Ekleme Ekranında;

◦ Çalışan bilgileri girilecektir.(İsim, yaş, çalışan türü vs)
◦ Çalışan maaşı otomatik hesaplanıp ekranda gösterilecektir.
◦ Çalışan ekle yapıldığında şirket ekranına yönlenmelidir.
◦ Bu ekranda UIStackView kullanılmalıdır.

• Çalışan Listesi Ekranında;

◦ Çalışanlar listelenmelidir.
◦ UITableView veya UICollectionView kullanılmalıdır.
◦ Çalışanlar arasında isimden arama yapılabilmelidir.
</pre>

2- Hayvanat bahçesi Playground yazılımının Xcode ile projelendirilmesi yapılacaktır. Aşağıdaki Özelliklerin bulunması gerekmektedir:
--
<pre>
• Giriş Ekranında;

◦ Hayvanat bahçesi bilgileri yer almalıdır.
◦ Hayvanat bahçesi gelir gider, su limiti eklemeleri bu ekrandan yapılabilmelidir.
◦ Hayvanat bahçesi maaş ödemesi bu ekrandan yapılabilmelidir.
◦ Bakıcı ekle butonu olmalıdır.(Bakıcı ekleme ekranı açılmalı)
◦ Hayvan ekle butonu olmalıdır.(Hayvan ekleme ekranı açılmalı)
◦ Bakıcı&Hayvan listele butonu olmalı.(Bakıcı&Hayvan listesi ekranı açılmalı)

• Bakıcı ve Hayvan Ekleme Ekranlarında;

◦ Bilgileri girilecektir.(İsim, yaş, çalışan türü vs)
◦ Bakıcı için maaşı otomatik hesaplanıp ekranda gösterilecektir.
◦ Bakıcı ekle yapıldığında hayvanat bahçesi ekranına yönlenmelidir.
◦ Bu ekranlarda UIStackView kullanılmalıdır.

• Bakıcı&Hayvan Listesi Ekranında;

◦ Bakıcı ve Hayvanlar listelenmelidir.
◦ UITableView veya UICollectionView kullanılmalıdır.
◦ Listede bakıcılar için hayvanlar, hayvanlar için bakıcı bilgisi mutlaka bulunmalıdır.
◦ Listede bir hayvana bastığımda kendi sesini çıkarmalıdır. Gerçek ses bekliyoruz bu sefer :)
</pre>

3- https://programming-quotes-api.herokuapp.com/index.html üzerinden random endpointi kullanılarak aşağıdaki özellikler sağlanacaktır.
--
<pre>
• Tek bir ekran üzerinde multiline(Uzunluğa göre satır sayısı değişmeli) label ve button olacak.
• Buttona her bastığımda yeni bir random quote çekecek ve label içerisinde değeri gösterecek.
• Uygulama ilk açıldığında random quote göstererek başlamalı.
</pre>
4- Pragmatic Programmer 8,9 chapterlar özetlenmelidir.
--

Kolay gelsin :)

--
HAVE A GOOD DAY..

Kaan YILDIRIM


----------------

# 1. Soru

![ezgif com-gif-maker](https://user-images.githubusercontent.com/56068905/202732811-4f546a9a-3ea3-4428-84c9-29ee15a61f07.gif)

## Kodlara ulaşmak için [tıklayınız](https://github.com/Vakifbank-IOS-Swift-Patika-Bootcamp/third-week-homework-ozturkomerfaruk/tree/main/Hw3-1/Hw3-1)

### Şirket Hakkında Sayfası

<img width="300" height= "600" src= "https://user-images.githubusercontent.com/56068905/202904226-2128ea14-c96c-4de7-a831-111d656a6310.png"/>

Bir ImageView altında şirket logosu ve kuruluş tarihi bulunmaktadır. Bu şirketin bütçesinin gelir ve giderlerinin hesaplandığı ve çalışanlarının maaşlarının ödendiği sayfadır. İlk açılış ekranı bu sayfa olmaktadır.

Diğer sayfalara gitmek için Navigation Controller'dan yararlanarak butonlar oluşturdum. Yeni bir çalışan ekleme ve çalışanları görmek için bu butonlara tıklamak gerekir.

Bütçenin negatife düşmesi durumunda, bir uyarı ekranı "Alert" açılmaktadır.

### Çalışan Ekleme Sayfası

<img width="300" height= "600" src= "https://user-images.githubusercontent.com/56068905/202904421-934634b9-024c-4875-95f6-2a0227be007e.png"/>

Çalışan ekleme sayfasında çalışan bilgileri girilmektedir. Bu kapsamda, isim, yaş, evlilik durumu, yaşadığı şehir, memleketi ve çalışanın statüsü bilgilerini içermektedir.

Bilgiler girildikten sonra maaşı belli olmaktadır. Eğer çalışan evliyse fazladan 2500 TL para verilmektedir. Ayrıca çalışanın statüsüne göre maaşında katlanma olmaktadır. Başlangıç seviyesindeyse maaşı 5 bin, orta seviye ise 10 bin ve eğer uzman bir çalışansa maaşı 20 bin lira olmaktadır.

### Çalışan Listeleme Sayfası

<img width="300" height= "600" src= "https://user-images.githubusercontent.com/56068905/202904820-b87c0a29-7371-447d-8175-1e6dbb4778fe.png"/>

Çalışanların listelendiği ekrandır.

### Çalışan Detay Sayfası

<img width="300" height= "600" src= "https://user-images.githubusercontent.com/56068905/202904867-f5612da2-86de-44ce-9016-231a74ffa7bd.png"/>

Çalışanların bilgilerinin listelendiği ekrandır. Bu ekran sayfasına ulaşmak için çalışanların listelendiği sayfada, çalışana tıklama gerçekleştirildiğinde açılmaktadır.

---

# 2. Soru

![ezgif com-gif-maker](https://user-images.githubusercontent.com/56068905/202899463-efd829c9-c6ef-4505-9dfd-1e5ddf310ddc.gif)

---

# 3. Soru


---

![ezgif com-gif-maker](https://user-images.githubusercontent.com/56068905/202902260-4c6893d7-3c8f-4cb0-bfbe-6d67309d898d.gif)
