Yazılım yaşam döngüsü nedir?
Bir yazılımı oluşturma, test etme ve dağıtma sürecidir. Kısa sürede yüksek kaliteli, düşük maliyetli yazılımların üretimini sağlayan yapılandırılmış bir süreçtir. Yazılım yaşam döngüsünde amaç, tüm müşteri beklentilerini ve taleplerini karşılayan ve aşan üstün yazılımlar üretmektir. Ayrıntılı aşamalardan oluşur  belli bir plana bağlılık yazılım geliştirme hızını arttırır ve alternatif üretim yöntemleriyle ilişkili proje risklerini ve maliyetlerini en aza indirir. 5 temel adımdan oluşur: Gereksinim, Analiz, Tasarım, Gerçekleştirme, Bakım
Gereksinim: Müşteri isteklerinin dikkate alındığı ve fizibilite çalışmalarının olduğu en önemli aşamadır. Üretilen somut veriler arasında proje planları, tahmini maliyetler, öngörülen programlar bulunmaktadır.
Analiz-Çözümleme: Sistem ihtiyaçlarının ayrıntılı olarak incelendiği aşamadır. Temel sorunlar belirlenir.
Tasarım: Belirlenen gereksinimleri karşılanarak yazılımın temel yapısının oluşturulduğu aşamadır. Mantıksal tasarım; Mevcut sistem değil, önerilen sistemin yapısı anlatılır,
Fiziksel tasarım; Yazılımı içeren bileşenler ve bunların ayrıntıları içerilir.
Gerçekleştirme: Modüllerin kodlandığı, birleştirildiği, test edildiği ve kurulum çalışmalarının olduğu aşamadır 
Bakım: Hata ayıklama ve yeni gereksinimlerin eklenebildiği aşamadır.

Yazılım yaşam döngüsü çeşitleri nelerdir?
1-Geleneksel(Waterfall model): Yaşam döngüsü temel adımları baştan sona en a bir kez izleyerek gerçekleştirilir. İyi tanımlı projeler ve üretimi az süre gerektiren projeler için uygundur. Barok modelinin aksine her aşamada belgeleme gereksinimi olmaz. Şu anki aşama bitmeden bir sonraki aşamaya başlanılmaz. Gerektiğinde iterasyonlar yapılır. Gerksinim adımı en temel adımıdır. Aşamaları net ve anlaşılırdır
Dezavantajları:- Test aşaması geliştirme sürecinin en sonunda yapıldığı için önemli bir hata olduğunda yeniden tasarım gerektirir.
-	Önceden anlaşma sağlansa bile yazılımın ne yapacağı konusu yoruma açıktır. Kullanıcılar kaliteyi en sondan önce anlayamazlar. Bu yüzden test etmeden önce sürece müşteri dahil edilmelidir.
-	Sistem geliştirilmesi süresince gereksinimlerin değişebileceği ihtimali vardır
-	Bir aşama tamamlanmadan bir sonraki aşamaya geçilmemesi maliyeti arttırır

2- V-Shaped Model: 
V şeklindeki bu modelde her aşamada karşılıklı bir test yani doğrulama vardır.
Kullanıcı modeli: Geliştirme sürecinin kullanıcı ile olan ilişkileri tanımlanmakta ve sistemin nasıl kabul edileceğine ilişkin sınama belirtimleri ve planları öne çıkar.
Mimari model: Sistem tasarımı ve oluşacak alt sistem ile tüm sistemin  sınama  işlemlerine ilişkin işlevler.
Gerçekleştirim model: Yazılım modüllerinin kodlanması ve sınanmasına ilişkin fonksiyonlardır.
Test odaklı bir süreç. Waterfall modeline göre test daha erken safhalarda başlıyor, bu da son süreçlerde keşfedilen eksik ve hataları daha erken bulmaya neden oluyor. Ama waterfall gibi bu model de yeterince esnek olmayabiliyor

3-İncremental (Arttırımsal) Model:
Modelde bir döngü söz konusudur. Planlama aşaması ile başlar. Planlamalardan geçip bu planlamanın ardından bir döngüye girilir. İstek analizleri, analizler, tasarımlar yapılır ve uygulamaya geçilir.  Uygulamadan sonra geliştirme yapılacaksa artık sürümler haline gelir ve güncellenme olasılığı vardır. Problemler her aşamada olduğu gibi geliştirme aşamasında da yaşanır. Ama bu problemler testlerin birer parçası olarak görülebilir. Bir yandan da testlerimiz devam eder. Bu problemler sistemi besler. Testlerden gelen bilgilere göre tekrar değerlendirilmeye tabii tutulur. Sonra tekrar istek analiz, analizler, canlıya bir bilgi verilmesi ve tekrar testler gibi süren bir döngü vardır. Bu sırada planlamada değişiklikler olabilir.
Örneğin;  Trendyol sayfası üzerinden satış yapılıyor olsun. Web sayfası ile ilgili yeni ihtiyaçlar gelmeye başlar. Bir yandan yazılımın çalışan hali ile ilgili bir problemler ortaya çıkar. Bir yandan da “Orada şu modüle şu ekranı da ekleyelim” gibi fikirler, yen istekler çıkmaya başlar. İşte bütün bunlar arttırımlı modelde her seferinde arttırıla arttırıla bir iterasyon şeklinde devam eder ve her yenilik bir sonraki iterasyonda sürece dâhil edilir.
ilk denemede bir ürünü teslim etmek yani aceleyle bitirmek yerine, yavaş ve istikrarlı bir felsefeyi teşvik eder. Görevlerin tekrar edilmesiyle ürün kademeli olarak geliştirilir.

4-Spiral Model:
Bölgeleri 4 e böldüğümüzü düşünelim ve her kısımda içten dışa doğru spiral şeklinde dönerek aşamaları ilerliyoruz. Bu dönme sırasında prototipler çıkarılıyor. Prototipler, maket uygulamadır. Ufak bir uygulama müşteriye gösterilir. Onun üzerinde müşterinin, yazılımı kullanacak kişinin fikir sahibi olması daha mümkündür. “Şurası olmamış. Böyle istiyorduk ama istediğimiz gibi olmamış.” Deme şansı daha da yüksektir. Dolayısıyla bu prototip çıkartma işlemi şöyle ele alınıyor. Bir defa istekler belirleniyor. Operasyon ile ilgili fikir sahibi olunuyor. İhtiyaçlar belirleniyor. Daha sonra risk analizleri yapılıp prototip çıkartılıyor. Bu prototipten sonra tekrar bunun ihtiyaçlarla ilgili kontrolü yapılıp doğrulama ve onaylama aşamasından geçirilip bir daha yazılım sürecinden geçiriliyor. Yine bir risk analizi yapılıp prototip 2 çıkarılıyor. Sonra bunun test planının yapılıp ve risk analizinin yapılıp bir prototip daha çıkarılıyor. Bu prototip uygulamaya geçmeden önceki son prototip. Bu adımların sayısı arttırılabilir. Burada 2-3 prototip var 4-5 prototipe gidilebilir. Veya tek bir prototip de yeterli görülebilir projenin büyüklüğüne göre. Uygulama prototipinden sonra detaylı tasarım, kodlama, entegrasyon, testler ve uygulama süreci başlar. Bu son aşama şelale modeline benzer bir yapıda işler. Spiral model buraya kadar bize değişik döngülerden geçen risk analizlerinin yapıldığı ve sonunda bir prototipin ortaya çıktığı ve hem yazılım geliştirme ekibinin ve proje yönetim ekibinin, hem de müşterinin üzerinde mutabık olduğu bir prototip ortaya çıkartır ve daha sonra bu prototipi gerçekleştirip canlıya çevirebiliriz. Bu spirali de 4’e böldüğümüzde 4 aşaması vardır. 1. Hedeflerin belirlenmesi 2. Risklerin belirlenmesi ve çözümü 3. Geliştirme ve testler 4. Sonraki dönüşün planlanması. Böyle bir döngü içerisinde sürekli dönülür. Yukarı doğru gittikçe maliyetin büyümesi söz konusu ve sola doğru gittikçe de gözden geçirme süreçlerinin arttırılması söz konusudur. Spiral modeli diğer modellerden ayıran özellik risk analizinin ön planda olması ve prototip oluşturulmasıdır. Risk analizi ön planda olduğu için sorunları erkenden fark etme imkanı sağlar.

5-Agile Model
Çevik model olarak da adlandırlır. Amaç isteklere uygun ürün çıkarabilme, az maaliyet’li ve kısa sürede ürün sunma, esnektir, verimlilik yüksektir,  hata oranı düşüktür.
Küçük iterasyonlardan oluşur ve buda hataların kısa sürede bulunup ona göre yöntemlerin geliştirilmesini hızlandırır. Müşteriyle iletişim her iterasyon sonrasında yapılır. Ekip üyeleri sürekli iletişim halindedir bu da projeyi olumlu etkiler. Verimliliği arttırır. Model, her biri bir Önceki sürümden küçük, artımlı değişikliklere sahip sürekli sürümler üretir. Her yinelemede ürün test edilir. Ancak bu model büyük ölçüde müşteri etkileşimine bağlı olduğundan, müşteri gitmek istediği yöne net değilse proje yanlış yola girebilir. 4 ana prensipten oluşur.
-Kişiler ve iletişim, süreç ve araçlardan üstündür.
-Çalışan yazılım, kapsamlı dökümantasyondan üstündür.
-Müşteri iş birliği, sözleşmelerden üstündür.
-Değişime cevap verebilme, belli bir planı uygulamaktan üstündür.
En yaygın kullanılan  çevik metodolojiler; XP(Extreme Programming), SCRUM, LEAN Software Development, Feature Driven Development(FDD)

XP(Aşırı Programlama-Extreme Programming)
XP, her yazılım geliştirme yaşam döngüsü aşamasında kodlamaya odaklanan yoğun, disiplinli ve çevik bir yazılım geliştirme metodolojisidir. Bu aşamalar şunlardır: Geliştirme sürecinin başlarında sorunları keşfetmek ve onarmak için sürekli entegrasyon Müşteri katılımı ve hızlı geri bildirim. Bu XP metodolojisi disiplinleri, XP'nin yaratıcısı Kent Beck'in aşağıdaki dört anahtar değerinden türetilir: İletişim: Ekip üyeleri ve müşteriler arasındaki iletişimin gerçekleşmesi gerekir ve sık sık misilleme korkusu olmadan açık proje tartışması ile sonuçlanır. Basitlik: Bu, müşterinin mevcut proje yinelemesine yönelik ihtiyaçlarını karşılamak için en basit tasarım, teknoloji, algoritmalar ve teknikleri kullanmayı içerir. Geri bildirim: Geri bildirim çoklu, farklı düzeylerde, örneğin birim testleri, kod incelemesi ve entegrasyonda alınmalıdır. Cesaret: Zor fakat gerekli kararları uygulayın. Gerekirse memnun olmadığınız projenizi çöpe atıp yeniden yazabilmelisinizdir.

LEAN Software Development
LSD aslında felsefesini, atıkları en aza indirmek ve müşteri değerini en üst düzeye çıkarmak için üretim ve montaj hatlarını optimize etmenin bir yolu olarak yalın geliştirme sürecini başlatan imalat endüstrisinden ödünç almaktadır. Aslında, başlangıçta Toyota Üretim Sistemi olarak adlandırıldı, çünkü otomobil üreticisi Toyota, yirminci yüzyılın ortalarında bu yaklaşımı otomobil üretimini kolaylaştırmanın ve boşa harcanan zamanı ve kaynakları ortadan kaldırmanın bir yolu olarak icat etti. ( İnşa edilen ve teslim edilen otomobilin işlevselliğini etkilemeyen herhangi bir işlem, bu sistem kapsamında bir atık olarak kabul edildi ve bu nedenle işlemden çıkarıldı. 
Yedi ilke ile özetlenebilir.
Atıkları ortadan kaldır, Öğrenmeyi güçlendir, mümkün olduğunca geç karar verin, mümkün olduğunca hızlı teslim edin, ekibi güçlendir, bütünlüğü oluşturun, bütünü optimize et
Bu modelde müşteriye değer katmayan her şeyi atık olarak görür. Kısmen yapılan iş, ekstra özellikler, yeniden öğrenme, görev değiştirme, buglar, yönetim faaliyetleri vs.
Avantajı; Kısa sürede basit bir taslak sunumu, gereksiz maaliyet ve zamandan tasarruf
Dezavantajı; Projenin büyük kısmı ekibe bağlıdır.

Feature Driven Development(FDD)
(Yazılım Geliştirme Metodolojisi)
 Yazılımımızda istediğimiz özelliklerin ilerleme kaydetme konusunda yazılım geliştirme düzenler. Şekil 6 ‘ daki gibi özellikler beş aşamada gelişme gösterirler.
Avantajı; Beş adımlı basit bir süreç daha hızlı gelişimi sağlar
Dezavantajları; Küçük projeler için verimli çalışmaz, karışıklığa yol açabilecek daha az yazılı belge, başlıca geliştiricilere veya programcılara oldukça bağımlı.

SCRUM
SCRUM Nedir?
Şirketlerin karmaşık ürünler yaratmasına, teslim etmesine ve sürdürmesine yardımcı olmak için geliştirilmiş hafif bir proje yönetimi çerçevesi. SCRUM kullanarak, ekipler uzun vadeli projeler için planlarını sprint adı verilen kısa vadeli çalışma dönemlerine ayırır, iki hafta veya bir ay ile sınırlıdır. Her sprint sırasında, geliştirme ekibi sadece birkaç üzerinde anlaşmaya varılan proje üzerinde çalışır. Bir proje, ekibin tek bir sprintte tamamlayabileceğinden daha fazla çalışma gerektiriyorsa, işi birkaç sprint'e ayıracaktır. Amaç, ürünü sık sık güncellemek ve bu güncellemeleri sık sık piyasaya sürmek, kullanıcılarla sürekli olarak neyin yankılandığını öğrenmektir. Böylece kullanıcıların ilgisini daha çok çekecektir.
Product Owner(Ürün sahibi): Ekibin bu üyesi, geliştiricilerin doğru öğeler üzerinde çalıştıklarından ve bunu verimli bir şekilde yaptıklarından sorumludur. Ürün sahibi, ürün birikimini yönetmekten de sorumludur. 
Scrum Master:  Geliştirme ekibini denetlemekten, geliştiricilere rehberlik etmekten ve koçluk yapmaktan ve çalışmalarını bozabilecek veya yavaşlatabilecek engelleri ortadan kaldırmaya yardımcı olmaktan sorumludur.
Proje yöneticisi rolü bulunmaz bu durum deneyimsiz bir scrum ekibinde sorunklara neden olur, bunun için bir scrum uzmanı gereklidir
Scrum’un günümüzde en çok kullanılan yöntem olma sebepleri; Yüksek esneklik sağlar, ürün kalitesinin artmasını sağlar, daha iyi takım çalışması,  karşılaşılan sorunların birlikte çözümü, sürekli geri bildirim olması risk oranını önemli ölçüde azaltır, yüksek yatırım getirisi sebebi ise her sürümde kullanıcılara sunulacak bir ürün olmasıdır

Hangi projede hangi modeli kullanmalıyım?
1-Bir yaşam döngüsü modeli seçmeden önce bu metodolojileri iyi tanımalı avantaj ve dezavantajlarını bilmeliyiz.

2- Takım arkadaşlarının endişelerini, kabiliyetlerini, iş önceliklerini, gereksinimlerini iyi değerlendirmeliyiz.

3- Hangi modeli kullanacağımıza karar verirken bağımsız değişkenlerden faydalanabiliriz;
-	Proje ekibimize uygun mu
-	Kullanacağımız proje için uygun mu
-	Yazılımı boyutu ve karmaşıklığı için uygun mu?
-	Coğrafi duruma uygun mu(Dağıtılmış bir ekipten oluşabilme ihtimali)
-	Müşteriye uygun mu(Süresi, maaliyeti, ihtiyaçları, istekleri vs. )
Örneğin; Kompleks sistemler, beceri sınırlaması ve dokümantasyon açısından agile metodu kötü bir seçimdir, belirsiz kullanıcı gereksinimi açısından, maaliyet sınırlaması açısından, ve üçlü proje yönetimi, güçlü takım iletişimi açısından iyi bir tercih olabilir
-	Kısa bir zaman diliminin olduğu bir projede spiral model kötü bir seçimdir.
-	Dökümantasyonun iyi olduğu, kompleks ve güvenilir sistemler, güçlü proje yönetiminin olduğu yazılımlar için Waterfall model tercih edilebilir.
-	Spiral ve agile metotda güçlü bir beceri kısıtlaması vardır.
