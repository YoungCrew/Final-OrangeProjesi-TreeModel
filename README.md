# Final-OrangeProjesi-TreeModel
Grup Üyeleri :  Merve TAŞDELEN- Ayşe ŞAHİN - Kader GÜROL - Yasemin ÜZÜM - Hamiyet KAYA
Orange Canvas Programında Tree Modelini kullanarak 5 farklı data set uyguladık. Hepimizin verisi birbirinden farklı konuları içermektedir. Orange projemiz üzerinde çalışabilmek için öncelikle github üzerinden bir proje alanı oluşturduk.  Bu proje alanında yalnızca bir tane yönetici yerine grup üyelerinin tamamını yönetici yaptık ki verilere herkes ulaşabilsin, düzenleyebilsin ve silebilsin. İlk olarak Git Bashı kullanarak git temel kodlarıyla verilerimizi github da bulanan depo alanımıza gönderdik. Daha sonradan eklemek istediğimiz çalışmayı sürükle bırak mantığını kullanarak github üzerinde paylaştık. İlk önce çalışmalarımızı dosya şeklinde atarken, kafa karışıklığı yaratılmasın diye süreç sonuna doğru çalışmalarımızı klasör şeklinde yükledik.Klasör içerisinde grup üyelerinin , orange çalışması, kullandığı veri seti, orange çalışmasının html görüntüsü bulunmaktadır.Böylece süreci hızlandırmış olduk. Böylece kim ne yapmış, hangi veri ya da çalışma kime ait bir düzen içinde belirlenmiş oldu. 

Orange canvas üzerinde verilerimizi görselleştirirken veri bulmamız biraz zor oldu. Her veri tree modele uyumlu değildi ve aralarında en uygun olanlarını grupça kendi aramızda belirledik. Veri görselleştirme aşamalarını(file-data table-tree-tree viewer) oluştururken zorluk yaşamadık fakat veri görselleştirildikten sonra verilerimizi yorumlama ve anlama aşaması uzun sürdü. 

Oluşturduğumuz verilerin tamamını web sitemizde yayımladık. Her birimizin sayfasında en başta kendi çalışmamız ve diğer grup üyelerinin çalışmaları yer aldı. Yaptığımız görselleştirme sürecinin verisini sitemize de gömdük. Herkesin çalışmasıyla ilgili veri dosyası, orange dosyası, github bağlantısı ve html bağlantıları verildi. Dersin ilgili hocalarının isminin yazılmasına özen gösterildi. Yaptığımız çalışmalar github ve Web sitemiz haricinde başka bir yerde paylaşılmadı.

Yaptığımız çalışma sürecini anlatan (github ve orange) yaklaşık yedi dakikalık bir video oluşturduk. Videonun oluşturulma sürecindeki ilgili dosyalar, github ve orange ile ilgili çalışmalarımızın tamamını CD’ ye yükledik. 

Merve Taşdelen Car.tab verisini kullanmıştır. Açıklaması şu şekildedir:
Araba alırken dikkat edilen unsurlar
Car.tab (otomobil) veri dosyasının tree modeliyle görselleştirilmiş halidir. Burada 1728 tane veri, araba unsurları göz önünde bulundurularak hazırlanmıştır. (Fransa)
Altı tane de özellik bulunmaktadır.
Buying= Satın Alım Dört tane değeri bulunmaktadır. V-high(0)(oldukça yüksek), High(2)(yüksek), Med(4)(orta), Low(6)(düşük)
Maint= Bakım Dört tane değeri bulunmaktadır. V-high(0)(oldukça yüksek), High(2)(yüksek), Med(4)(orta), Low(6)(düşük)
Doors= Kapılar Beş ve daha fazla değeri bulunmaktadır. 2, 3, 4, 5-More(5)
Persons=Kişi Sayısı Üç ve daha fazla değeri bulunmaktadır. 2, 4, More(6)
Lug_boot=Çekiş Üç tane değeri bulunmaktadır. Small(0)(küçük), Med(1)(orta), Big(2)(büyük)
Safety=Emniyet Üç tane değeri bulunmaktadır. Low(0)(düşük), Med(1)(orta), High(2)(yüksek)
Dört tane sınıf bulunmaktadır. 
Unacc= Kabul edilemeyecek kadar kötü  	Değeri=0
Acc= Kabul edilebilir idare eder.                	Değeri=2 	
Good=İyi                                                       	Değeri=4
V-good=Oldukça iyi                                  	Değeri=6
Sıfır değerine yaklaştıkça özellikler açısından kötüye doğru, altı değerine yaklaşıldıkça özellikler açısından çok iyidir.
Burada en fazla önem verilen özellik kişi sayısı ve emniyettir.
Emniyeti düşük olanlar ve kişi sayısının da iki kişi olması kabul edilmemektedir. Aynı zamanda bakımı yüksek olanlarda tercih edilmeyenler arasındadır.
En fazla dikkatimi çeken çekiş ve kişi sayısı oldu. Kişi sayısında iki kişiliklere çok önem verilememekteyken, çekiş gücünün büyük ya da küçük olması çok etkilememektedir.
Görselleştirmede en yüksek değer alanlar gösterilmiştir.  

Hamiyet Kaya titanic.tab verisini kullanmıştır. Açıklaması şu şekildedir:
Titanic.tab veri dosyasının tree modeliyle gösterilmiş halidir.
Titanic’teki bireylerin hayatta kalma durumları incelenmiştir.
Hayatta kalanlar : Yes Hayatta kalmayanlar : No
Tree modelde kırmızı renklerin koyuluğu arttıkça hayatta kalanların sayısı artmaktadır.
Tree modelde mavi renklerin koyuluğu arttıkça hayatta kalanların sayısı azalmaktadır.


Veri görselleştirme modelinde; cinsiyet, yaş, sınıf değişkenlerine göre bireylerin hayatta kalma durumları evet, hayır olarak gösterilmiştir.
 Veri görselleştirme modelinde, titanic.tab veri setinde 2201 yolcu bulunmaktadır. 
 Cinsiyet  değişkenine  göre kadın yolcuların erkek yolculara oranla sağ kaldığı tespit edilmiştir.%73 oranla kadın kurtarılmıştır.
Tree Modeli incelediğimizde kadın, dallara ayrıldığında  hayatta kalanların %92’si mürettebat, 1’inci ve 2’inci sınıf yolcularıdır .  3. sınıf yolcuların %54 ‘ü kurtarılamamıştır.
1’inci sınıfın %97’si , mürettebat ya da ikinci sınıfın %87’si kurtarılmıştır. Yani 1. sınıfa daha önem verilmiştir.
Yaş değişkenine göre,çocukların %100’ü kurtarılmıştır. Yetişkinlerin  % 86’sı kurtarılmıştır. Yetişkin kesim ,çocuk yaş grubuna oranla daha az kurtarılmıştır.
Dikkatimi çeken unsurlar : Erkeklerde  çocukların %100’ü kurtarılmıştır. Ayrıca erkeklerde  e ikinci sınıf %91, üçüncü sınıf %83 oranla hayatını kaybetmiştir.
İstatistiklere göre  %67 oranla, toplamda  1490 kişi hayatını kaybetmiştir.

Kader Gürol dermatology.tab verisini kullanmıştır. Açıklaması şu şekildedir:
Cilt hastalıklarının belirtilere göre incelenmesi
Dermatology.tab veri dosyası tree modeliyle görselleştirilmiştir.
Veriler 366 kişi üzerinden elde edilmiş.
Veriler 6 farklı deri hastalığı kategorisinde incelenmiştir.
Pisoriasis (Kronik deri iltihabı)
Liken planus
Pityriasis rosea(Gül hastalığı)
Pityriasis rubra pilaris
Sedef hastalığı
Seboreik egzama
Dermatolojik hastalıklar,34 farklı klinik (kızarıklık, pullanma, kaşıntı, çokgen kabarcıklar, follicular kabarcıklar vs.) ve histopatolojik nitelik açısından incelenmiştir.
Modelde etki alanı için oluşturulan veri kümesindeki aile geçmişi özelliği, ailenin bu hastalıklarından herhangi birine sahip olması durumunda 1 değerini, aksi takdirde 0 değerini almıştır. 
Yaş özelliği yalnızca hastanın yaşını temsil eder. Diğer her özellikte (klinik ve histopatolojik) 0 ile 3 arasında bir derece verilmiştir. Burada 0, özellik bulunmadığını, 3 olası en büyük miktarı, 1 ve 2 ise ara değerleri ifade eder.
366 kişiden 112si Kronik deri iltihabı(pisoriasis) hastalığına sahiptir bu hastalığın belirtisi de derideki çıkıntılardır.
Seboreik egzama hastalığı yaşa göre incelendiğinde 25 yaşından küçük olanların hepsinin bu hastalığa sahip olduğu, yaşı 25ten büyük olan 4 kişiden 2sinin de Pisoriasis hastalığına sahip olduğu gözlemlenmiştir.

Ayşe Şahin zoo.tab verilerini kullanmıştır. Açıklaması şu şekildedir:
Bir hayvanat bahçesinde bulunan 101 tane hayvan göz önüne alınarak hazırlanmıştır. Birtakım özelliklerine göre ağaç modeliyle hayvanlar sınıflandırılmıştır.
7 tane değer (memeli, kuş, balık, omurgasız, böcek, sürüngen, hem karada hem suda yaşayan hayvanlar) belirlenmiştir. Bu değerler bazı özelliklere göre (süt veren, tüy durumu, omurga durumu, kaç bacaklı olduğu, yüzgeç durumu, suda yaşama durumu, zehirli olup olmadığı) gruplandırılmıştır. 
Bu özelliklerden her biri varsa 1, yoksa 0 değerini alır. Bacak sayısına bakıldığında kaç bacağı varsa ona göre değer alır.
Özellik var=1
Özellik yok=0
Bacak sayısı=0, 4, 5 veya 8 (grup)
Bacak sayısı=2 veya 6 (grup)
Aynı zamanda bir grup içerisine hayvanların kaçının dahil edileceği belirtilmiş olup yüzde olarak da gösterilmiştir.
Hayvanlardan 41 tanesi memeli grubuna dahil edilmiştir. Bu neredeyse tüm hayvanların yarısına denk gelmektedir. Ben bu kadar fazla olacağını düşünmemiştim.
Geriye kalan 60 hayvandan süt verme özelliğine göre 20’si kuşlar grubundadır.
Geriye kalan 40 hayvandan tüysüz özelliğine sahip olan 13 hayvan balıklar grubundadır.
Modelde aşağı doğru inildikçe kontrol edilen özellik artar. en sonda hem suda hem karada yaşayabilen hayvanlarda yüzgeci olmayan, omurgalı, tüyü olmayan, süt vermeyen, suda yaşayan ve zehirli olduğu tespit edilen bir hayvan belirlenmiştir. O da deniz yılanıdır.

Yasemin Üzüm lenses.tab verisini kullanmıştır. Açıklaması şu şekildedir:
Lenses.tab veri setinin tree modeli ile görselleştirilmiş halidir. 24 adet kişinin bazı özelliklere göre hangi tür lensi taktıkları ya da takmadıkları ifade edilmiştir.
Sert lens: yüksek astigmatizma ve keratokonus gibi olgularda özellikle tercih edilirler.
Yumuşak lens: miyop, hipermetrop, astigmat ve presbiyopi görme kusurlarını düzeltmek için kullanılabilirler.
None: lens takmayanlar
Hard: sert lens takanlar
Soft: yumuşak lens takanları ifade etmektedir.
Veri setindeki özelliklerin bilgisi şu şekildedir:
Hastanı yaşı: young, presbyopic(yaşlanmaya bağlı miyop) ve pre-presbyopic
Gözlük reçetesi: miyop(uzağı görememe), hipermetrop(yakını görememe)
Astigmat: hayır, evet
Gözyaşı üretim oranı(tear rate): kısıtlı(az), normal
Gözyaşı üretim oranı kısıtlı(az) olanların tümü lens takmıyorlar.
Gözyaşı üretim oranı normal olanların %41,7 si yumuşak lens takıyorlar.
Astigmat olmayanlar yumuşak lens kullanıyorlar.
Yumuşak lens kullananların çoğunluğu young(genç) ve pre-presbyopic olan kişilerdir.
Astigmat olanların yarısından fazlası yani %66,7 si sert lens kullanıyorlar.
Astigmat olup lens kullanmayanlar hipermetrop olan kişilerdir.
Astigmat olanların yarısı miyoptur.
Sert lensler yüksek astigmatizma olan durumlarda kullanılır. Modelde astigmat olanların yarısından fazlasının sert lens taktığı görülmektedir. Buradan şu sonucu çıkarabiliriz astigmat olanların çoğunluğu yüksek astigmatizması vardır.
 
Merve Taşdelen: http://www.mervetasdelen.com/
Yasemin Üzüm: http://www.yaseminuzum.com/
Ayşe Şahin: http://www.ayse-sahin.com/
Hamiyet Kaya: http://www.hamiyetkaya.com/
Kader Gürol:http://www.kadergurol.com/
