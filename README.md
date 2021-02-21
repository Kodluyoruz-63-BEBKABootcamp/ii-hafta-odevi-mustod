# ii-hafta-odevi-mustod
ii-hafta-odevi-mustod created by GitHub Classroom
* Yeni bir Github repository oluştururken, repomuza ekleyebileceğimiz lisanslar nelerdir, bu lisanslar arasındaki farklar nelerdir?
* Merge - Squash-Rebase arasındaki farklar nelerdir?
* Github Learning Lab'de First Day ve First Week kısımlarını bitiriniz.
* Agile-Scrum-Kanban kavramlarını araştırınız
* Derste yaptığımız .Net Console uygulamasının .NetCore versiyonunu yazmayı deneyiniz.
* Github Flow'un alternatifleri nelerdir? Artılarını ve eksilerini karşılaştırınız.
* Gang of Four(GOF) araştırınız.
* Interface ve Abstract sınıflar arasındaki farklar nelerdir?
-------------------------
## GPL (Genel Kamu Lisansı)
GPL lisansı ilk olarak 1989 yılında yayınlanmıştır. Güncel sürümü GPL V3 dür. 
GPL teşvik edici gelişime açık bir lisansdır. 
Hem geliştirici hem de kullanıcı açısından büyük olanaklar sağlar. 
GPL’in en çok dikkat ettiği konu üretilen yazılımın kaynak kodları ile beraber dağıtılmasıdır.

GPL lisansını kullanan bir yazılımı alıp kendi projenize eklerseniz siz de kaynak kodunuzu GPL ile lisanslamalısınız ve açık kaynak olarak dağıtmalısınız. GPL, yazılımın ücretlendirme konusunda fikir beyan etmez, yazılımlar ücretsiz olmak zorunda değildir. Bu ibare lisansta bulunmasına rağmen GPL lisanslı yazılımların çoğu ücretsizdir.

GPL in dezavantajı diyebileceğimiz bir yanı ise GPL ile lisanslanmış yazılımın başkaları tarafından değiştirilerek geliştirilmesi sonucunda elde ettiği gelire hiç bir konuda maddi talepte bulunamazsınız. Yaptığınız yazılımın ya da kütüphaneden gelir elde etmek gibi bir durumunuz varsa başka lisanslarla lisanslamanız gerekir.

GPL lisansı kullanarak geliştirilen yazılımlar;
Mozilla, Mozilla ThunderBird, GIMP, Audacity, Scribus, eMule, Vuze, Shareaza, Notepad++, VLC, Processing

## LGPL (Kısıtlı Genel Kamu Lisansı)
Kısıtlı Genel Kamu Lisansı (LGPL) genel ağırlıklıkta kütüphane olarak geliştirilen yazılımlarda kullanılır. 
GPL in aksine LGPL’de geliştirdiğiniz bir kütüphaneyi özel mülk yazılımın içerisinde kapalı kaynak olarak kullanabilirsiniz. Ancak LGPL ile geliştirilmiş kütüphanenin içerisinde herhangi bir değişiklik yapmış veya yama geliştirmiş iseniz bu kısmı açmak zorundasınız.
Büyük yazılım firmaları LGPL ile ilgili kütüphaneleri kendi projelerine eklerken script dosyaları yazarak kendi projelerine bağlarlar. Böylelikle LGPL de bir değişikliği kolaylıkla açık olarak yayınlama imkanına sahip olurlar.
LGPL lisansı altında geliştirilen yazılımlar;
Mozilla, Mozilla ThunderBird, GIMP, LibreOffice,Processing, OpenGL

## BSD Lisansı
BSD lisansı adını Berkeley Software Distribution dan alır. Özgür yazılım lisans ailesindendir. Yazılım üzerine neredeyse hiç bir sınırlama koymaz. İstenilen şekilde değiştirebilirsiniz, kodu kapatabilirsiniz ve üzerinden para kazanabilirsiniz. İsteyen herkes istediği gibi kullanabilmektedir.
BSD lisansı altında geliştirilen projeler;
PostgreSQL, OpenCV

## MPL (Mozilla Kamu Lisansı)
MPL açık kaynak lisans ailesi içerisindedir. Genel olarak BSD lisansının olanaklarıyla Genel Kamu Lisansını bir araya getirmeye çalışan bir lisansdır.
MPL lisansı altında geliştirilen yazılımlar;
Mozilla, Mozilla ThunderBird, LibreOffice

## MIT Lisansı
MIT lisansı üzerinde geliştirilmiş olan yazılımın bir kopyasını dağıtma, kullanma, kopyalama, değiştirme, alt lisanslama gibi imkanların hepsini sağlar. Ticari ve hususi olarak kullanma imkanını sağlar. Zorunlu yapmanız gereken MIT lisans ibaresini kodunuza eklemeniz gerekmektedir ve telif bulundurmanız gerekmektedir. Yazarları sorumlu tutamazsınız.

## Apache Lisansı
Apache lisansı yazılan programın kodlarının tüm kopyaları, değiştirilmiş ve ya değiştirilmemiş, lisansın bir kopyası eşliğinde dağıtabilir ya da kullanabilir. Üzerinde yapılan değişiklikler değiştirilmiş olarak işaretlenmelidir. Ticari kullanım olarak kullanım imkanı sağlar.

> [Kaynak](https://medium.com/@AntriKod/%C3%B6zg%C3%BCr-yaz%C4%B1l%C4%B1m-lisanslar%C4%B1-%C3%BCzerine-c28e66c2b6ef)

------------------
Git merge ile yaptığımız birleştirmede yeni bir commit yaratacak ve yeni branch’deki tüm history tarafını kaybetmeden birleştirme işlemi gerçekleşmiş olcaktır.

Git rebase ile birleştirdiğimizde ise branch deki commit’lerimizi tek tek alıp istediğmiz branch üzerine ekleyecektir. Böylelikle tek bir history oluşturacak ve istenmeyen history ortadan kalkacaktır.

Bu iki komutun farkına baktığımız noktada, aslında benzer işi yaptıklarını ve fark olarak ise git rebase kullanımında history’nin temizlendiğini ve git merge kullandığımızda ise tüm geçmişin korunduğunu görüyoruz.

git squash komutu, farklı bir rebase kullanımı olarak değerlendirmek daha doğru olacaktır. Geçmişte atılan commit’leri yeniden düzenlemek, isimlendirmek veya birleştirmek için kullanıyoruz.

> [Kaynak](https://medium.com/neyasistechnology/git-rebase-squash-ile-ge%C3%A7mi%C5%9Fi-yeniden-d%C3%BCzenlemek-9de36441f947)

--------------------------
### Agile nedir?
Agile modeli proje yönetimi, yazılım geliştirme sürecinde karşılaşılan problemleri çözmek üzere, tekrarlanan yazılım geliştirme modeli taban alınarak geliştirilmiş, sık aralıklarla parça parça yazılım teslimatını ve değişikliği teşvik eden bir yazılım geliştirme modeli.

### Scrum nedir?
Kendi rehberindeki tanımlaması “İnsanların mümkün olan en yüksek değere sahip ürünleri üretken ve yaratıcı bir şekilde geliştirirken, karmaşık ve adaptasyona açık sorunları ele alabildikleri bir çerçeve” olan scrum, agile proje yönetme metodolojilerinden biridir.

> [Kaynak](https://medium.com/@PeopleBox/agile-nedir-scrum-nedir-ba%C5%9Far%C4%B1l%C4%B1-proje-y%C3%B6netimi-y%C3%B6ntemleri-nelerdir-64c4ae723496)
### Kanban Nedir?
Kelime anlamı olarak etiket anlamına gelmekte olup yalın konseptte bilgi iletiminde kullanılan bir araç olarak karşımıza çıkmaktadır. Çekme sisteminde, malzemenin hareket görmesini veya üretimin başlamasını tetiklemeye yarayan bilgi iletiminde kullanılan araçtır.
> [Kaynak](https://www.donusumdanismanlik.com/kanban-nedir-uygulama-rehberi/)

--------------
Design Patterns: Elements of Reusable Object-Oriented Software (1994), yazılım tasarım modellerini açıklayanbir yazılım mühendisliği kitabıdır. Kitap, Grady Booch'un önsözüyle birlikte Erich Gamma , Richard Helm, Ralph Johnson ve John Vlissides tarafından yazılmıştır. Kitap, iki bölüme ayrılmıştır; ilk iki bölüm, nesne yönelimli programlamanın yeteneklerini ve tuzaklarını araştırırken, geri kalan bölümler ise 23 klasik yazılım tasarım modelini açıklamaktadır . Kitap, C ++ ve Smalltalk'ta örnekler içermektedir.

Yazılım mühendisliği alanında etkili olmuştur ve nesneye yönelik tasarım teorisi ve uygulaması için önemli bir kaynak olarak kabul edilmektedir. İngilizce ve diğer 13 dilde 500.000'den fazla kopya satıldı. Yazarlar genellikle Dörtlü Çete ( GoF ) olarak anılır.

>[Kaynak](https://en.wikipedia.org/wiki/Design_Patterns) 

----------------
### Interface - Abstract Sınıfların Farkları
![](https://i.hizliresim.com/m4ulTM.jpg)
[Kaynak](https://medium.com/software-development-turkey/abstract-class-ve-interface-aras%C4%B1ndaki-farklar-nelerdir-3c0a4f956eba)