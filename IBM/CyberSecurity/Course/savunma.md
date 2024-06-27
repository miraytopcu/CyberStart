# Güvenlik olgunluğu yolculuğu
Bireyler gibi, kuruluşlar da zamanla değişir. Bu, siber güvenlikte olgunluk seviyesi veya deneyim olarak ifade edilir. Güvenlik olgunluğu yolculuğu açısından bir kuruluşun, bugün nerede olduğunu ve gelecekte nerede olacağını düşünmesi önemlidir.

Bazı kuruluşlar siber güvenliğe odaklanmamış olabilir ve bir sistem perspektifin bakıldığında olgun olmayabilirler. Öte yandan, daha uzun süredir siber güvenliği bir öncelik olarak aldıklarından "savaşla güçlenmiş" olan daha olgun kuruluşlar da vardır.

Siber Güvenliğin 10 Adımı şu şekildedir:
1. Risk yönetimi
2. Bağlılık ve Eğitim
3. Varlık Yönetimi
4. Mimari ve Yapılandırma
5. Güvenlik açığı yönetimi
6. Kimlik ve Erişim Yönetimi
7. Veri Güvenliği
8. Günlüğe Kaydetme ve İzleme
9. Olay Yönetimi
10. Tedarik Zinciri Güvenliği

-------------------------------------------------------------------------

# Saldırılara Karşı Korunma

## Çevrenin incelenmesi
Dikkate alınması gereken kavramlardan ilki, saldırı yüzeyiyle ilgili olandır. Siber güvenlikte bu terim, bir saldırganın saldırmayı seçebileceği, kuruluşun savunmasız durumda bulunan altyapı ve yazılım ortamının tamamını ifade eder. Saldırı yüzeyini korumak, kuruluşların varlıklarını dış dünyadan net bir şekilde ayıran belirlenmiş bir "çevreye" sahip oldukları zamanlarda çok daha az karmaşıktı. Şimdi ise bir saldırı yüzeyini olabildiğince küçük tutmak, temel bir güvenlik önlemi niteliği taşıyor. Bu, hangi hizmetlere dışarıdan erişebileceğini, hangi cihazlara bağlanabileceğini vb. sınırlayarak yapılabilir.

Son birkaç yılda kuruluşlar; uzaktan erişim yönetimi, misafir kablosuz bağlantı, kendi cihazını getir (BYOD) ilkeleri vb. nedeniyle çok daha karmaşık hale geldiler. Güvenli bir çevreye sahip olabilmek zor bir iştir. Minimum düzeyde kuruluşlar farkındalık sahibi olmalı ve çevrelerini daha geniş, daha kapsamlı bir siber güvenlik stratejisinin bir parçası olarak izlemelidirler.

## Ağ ayrıştırma
Daha güvenli bir sistem tasarlarken önemli bir yaklaşım, DMZ (arındırılmış bölge) kullanmaktır. Bu terim, ordudan alınmıştır. Ağ oluşturma dahilinde, ağ üzerinde kısmen denetlenen ve yönetilen bir 'orta yol' alanını ifade etmek için kullanılır. DMZ içindeki sunucular, hem iç hem de dış uygulamalar tarafından kullanılabilir.

Mimari, genellikle dışarıdan bir tarafın DMZ'deki verilere erişebileceği, ancak hassas ağ alanına erişemeyeceği şekilde düzenlenir. Örneğin şirket dışından bir müşteri, bir dijital ödeme sistemi için sipariş verebilir veya e-postalara erişebilir, ancak hassas şirket bilgilerine erişemez.

Kuruluşun ağının bir kısmı bir saldırıdan etkilenirse, bu durumda saldırı diğer hassas sistemlere hemen sıçramaz. DMZ'deki bir sunucuyu tehlikeye atan bir saldırganın, kuruluşta daha da ilerlemesi için ikinci bir başarılı saldırı gerekecektir.

## En düşük ayrıcalık
Kuruluşların, kuruluş dahilindeki uygulamalar ve kişilere ilişkin izin seviyelerini belirlemeleri önemlidir. Bunu yaparken temel unsurlardan biri, en düşük ayrıcalık kavramını devreye almaktır. Bu kavram, bir rolün yerine getirilmesi için en düşük seviyede izinlerin verilmesini ifade eder.

Bu kontrolü devreye alan kuruluş, daha az kısıtlı bir sisteme kıyasla başarılı bir saldırının sonuçlarını azaltmış olur. Risk açısından, bu örnekte sonucu azaltmış oluyoruz. "Patlama çapı" olarak bilinen askeri terimin de bu bağlamda kullanıldığını duyabilirsiniz; burada çap, bir saldırının etki alanını ifade eder. İzinlerin azaltılması, "patlama çapını" sınırlamanın iyi bir yoludur.

## Yama ve güvenlik açığı yönetimi
Yama yönetimi yazılım güncelleme sürecini, güvenlik açığı yönetimi ise yazılım dahilindeki hataları belirleme sürecini ifade eder. Zaman içerisinde eski yazılımlarda güvenlik açıkları keşfedilebilir. Güncel olmayan yazılımları kullanan kuruluşlar, daha eski açıklardan yararlanma eylemlerine karşı savunmasızdırlar. Ayrıca yazılımın yeni sürümleri de yeni güvenlik açıkları getirebilir. Genel olarak yazılım ve uygulamaların en son sürüme güncelleştirilmesi, onların başarılı bir saldırıya uğrama riskini önemli ölçüde azaltır.

Yazılım yaşamının sonuna geldiğinde ve artık desteklenmediğinde, bu yazılımı yönetmek güvenlik çalışanları için önemli bir sorun haline gelir. Bir güvenlik açığı keşfedilirse, yazılım satıcısı düzeltici yama yayınlamayabilir.

Hangi yazılımın belirli bir saldırıya açık olduğunu değerlendirmek için kuruluş bir güvenlik açığı tarayıcısı kullanabilir. Bu, bir sunucu veya uygulamada herhangi bir güvenlik açığı olup olmadığını değerlendiren bir yazılımdır. Güvenlik açığı tarayıcıları, aktif test yoluyla güvenlik açıklarını incelemek üzere ağ tabanlı olabilir ya da bunun yerine olası hatalar için statik kaynak kodunu tarayabilir. Her iki tarayıcı tipi de, hataları bir saldırgandan önce tespit etme konusunda değerli bilgi sağlar.

Telafi edici kontroller fikri ile güvenlik açığı yönetimi fikri birbiriyle bağlantılıdır. Bir yamanın düzeltemeyeceği bir güvenlik açığı keşfedildiğinde, geçici bir çözüm oluşturulabilir. Bu çözüm, eski bir sürüme geçmeyi veya bir özelliği devre dışı bırakmayı içerebilir.

## Derinlemesine savunma
Savunma konusunda son önemli husus, kuruluşların katmanlı bir yaklaşım kullanmalarıdır. Aslen ordudan alınmış olan derinlemesine savunma terimi, tek bir savunma tipi yerine bunları katmanlı hale getirme fikrini ifade eder. BT için bu, bir kuruluşun güvenlik duvarları gibi ağ savunmaları ile kötü amaçlı yazılım tarayıcıları gibi cihaz savunmaları ve şifreleme kullanarak önemli veriler etrafında kontroller yerleştirebilmesi anlamına gelir.

Başarılı bir saldırının gerçekleşmesi için, savunmanın tüm katmanlarının tehlikeye girmesi veya aşılması gerekir ki, bu da oldukça zordur.

 ----------------------------------------------------------

# Log kaydı
Bir kuruluşun saldırıların saptanmasına yönelik tesis edebileceği en önemli unsur, bir tür log kaydıdır. Log kaydı, eylemlerin doğru bir şekilde güvenli bir konumda kaydedildiği bir işlemdir. Log kayıtları değiştirilemez olmalı ve bir ağda gerçekleşenlere ilişkin kalıcı bir kayıt işlevi görmelidir. Bu log kaydı işlemi, tek tek makinelerde veya uygulamalarda yapılabilir.

Tek bir log girdisi yalıtımda çok değerli olmasa da, bir kuruluş hem meşru kullanıcıların hem de saldırganların faaliyetlerini izlemek için daha geniş bir koleksiyon kullanabilir.

# Ağ izleme
Sunucularda gerçekleşen olayların kaydedilmesine ek olarak, kuruluşlar ayrıca ağları genelindeki iletişimleri de izleyebilirler. Bu yaklaşım, trafik analizi olarak bilinir. Trafik analizi, şifreleme kullanıldığı sırada pasif olarak bile bir ağda nelerin yapıldığını belirlemek için kullanılabilir.

Cihazdan cihaza geçiş yapan belirli kötü amaçlı yazılım türleri, çok göze battıkları için iyi bir ağ izleme çözümü sayesinde kendilerini ele verebilir.

# Güvenlik bilgisi ve olay yönetimi (SIEM) araçları
Çok fazla bilginin toplanmasıyla, ilintilendirme kuruluşlar için oldukça zorlu, ancak bir o kadar da yararlı hale gelmektedir. Bir güvenlik bilgisi ve olay yönetimi (SIEM) ürünü, kuruluşun teknoloji altyapısı genelinde tüm bilgileri toplar ve siber güvenlik ekibinin olayları ve potansiyel saldırı kalıplarını belirleyip analiz edebilmesi için bu bilgileri bir araya getirir.

Bu, IBM QRadar on Cloud adlı bir SIEM hizmetinden alınmış ekran görüntüsüdür. Bu hizmet, tehditleri ve köstebek saldırılarını izlemeye yönelik bir istihbarat ve analitik yazılımıdır.

# Güvenlik operasyonları merkezi (SOC)
Genellikle, bir kuruluşun güvenliğinden sorumlu grup, güvenlik operasyonları merkezinin (SOC) bir parçasıdır. SOC'nin temel hedeflerinden biri, SIEM'leri ve diğer izleme araçlarını kullanarak devam etmekte olan saldırıları tespit etmektir. 

Güvenlik analistleri, SOC'de bir kuruluşun güvenliğini değerlendirmekten sorumlu ekibin üyelerini oluşturur. Bir saldırı veya potansiyel saldırı gözlemlenmesi halinde, güvenlik analistleri kurumsal prosedürleri izleyerek duruma nasıl müdahale edileceğine karar verecektir.

# Yanlış alarmlar
SOC'deki ince dengeleme eylemlerinden birisi belirli eşiklerin duyarlılığının ayarlanmasıdır. Eylem meşru olduğunda da bir uyarının tetiklenebildiği durumlar yaşanır. Buna yanlış pozitif denir ve bu tür durumlarda bir olay, kötü amaçlı değilken öyleymiş gibi kaydedilir.

Bir uyarının yanlış pozitif olup olmadığının doğrulanması, güvenlik analistinin görevidir. Bir uyarı çok fazla yanlış pozitifi tetikliyorsa eşikleri daha yüksek olacak şekilde ayarlamak yararlı olabilir.

------------------------------------------------------------------------------------

# Olaylara müdahaleye giriş
SANS Institute, birçok çevrimiçi eğitim kursu, etkinlik ve kaynak sunmaktadır. Patrick Kral'ın kaleme aldığı ve olaylara müdahaleye ilişkin iyi bir çerçeve sunan Incident Handler’s Handbook, enstitünün yayınladığı kaynaklardan biridir. Siber güvenlik çalışanlarının bir olaya müdahale etmek için birlikte kullanabilecekleri altı aşamaya kısaca göz atalım.

1. Hazırlık
Bu aşamada, kuruluş bir olay durumunda ne yapacağını planlamaya başlamalıdır.
Kaynakların hazırlanması ve prosedürlerin test edilmesi, tipik adımlardan bazılarıdır.

2. Belirleme
Bir olaya müdahale etmenin ilk adımı, olayın saptanmasıdır.
Olay doğrulandıktan sonra süreç bir sonraki adımla devam eder.

3. Kontrol Altında Tutma
Olay gözlemlenir gözlemlenmez, öncelik durumun daha kötüye gitmesini önlemektir.
Ağların ayrılması ya da erişim yollarının veya bazı sistemlerin kapatılması, bu konudaki adımlardan bazılarıdır.

4. Ortadan Kaldırma
Güvende olmak adına, bazı kötü amaçlı yazılımlar ya da saldırganların tıpkı insan vücudundaki bir hastalık gibi tamamen ortadan kaldırılması gerekir.
Ortadan kaldırma adımı sırasında, cihazlar tamamen temizlenebilir ya da güvenli duruma geri yüklenebilir.
Tamamen ortadan kaldıramamanın, kötü amaçlı yazılımların yeniden ortaya çıkmasına yol açtığı sayısız örnek vardır; bu nedenle titiz olmak kritik önem taşır.

5. Kurtarma
Olay çözüldüğünde, standart işletime geri dönülmesi gerekir.
Bu, geçici düzeltmelerin kaldırılmasını ya da bazı sistemlerin geri yüklenmesini kapsayabilir.

6. Üzerinde Düşünme
Olay sonrasında, sadece saldırının nedeni üzerinde değil, müdahalenin ne kadar etkili olduğu üzerinde de düşünmeye vakit ayırmak önemlidir.
Bu aşama, genellikle "alınan dersler" aşaması olarak da bilinir. Ancak, değişiklik yapılmazsa "tespit edilen dersler" daha iyi bir başlık olacaktır!

# Olaylara hazırlanma
Standart iş faaliyetlerinin bir parçası olarak çoğu kuruluş, hazırlık seviyelerini test etmek için simüle edilmiş çeşitli aktivitelerden geçer. Bu tabloda, bu tür testlerden üçü açıklanmaktadır.

Belge tabanlı testler		
Bu testte güvenlik ekiplerine anket yapılır ve hazırlık seviyeleri hakkında sorular sorulur. Bu aşama önemli personelin belirlenmesini, yedeklerin alınmasının sağlanmasını ve talep üzerine işlem belgelerinin üretilmesini içerebilir.	

Masa üstü alıştırmaları
Bu daha katılımcı bir test biçimidir. Bu testte birkaç önemli personel bir araya getirilir ve olaylara müdahale süreci uçtan uca simüle edilir. Bu test tipi, ekiplerin birbirleriyle etkileşim kurmalarını ve daha geniş bir senaryonun nasıl gelişeceğini görmelerini sağlar.	

Canlı testler
En gerçekçi test tipi, canlı sistemlerde bir alıştırma yapılmasıdır. Kuruluşlar, çeşitli hataları ve ekiplerinin nasıl müdahale ettiklerini test etmek için bazı önemli sistemleri kapatabilirler.

# İş sürekliliği ve olağanüstü durum kurtarması
Olaylara müdahaleye ilişkin olarak hakkında bilgi sahibi olmanız gereken iki önemli terimi inceleyelim.

İş sürekliliği, kuruluşun bir olaya rağmen faaliyetlerine devam edebilme yeteneğine dayanır. Bu, hizmetlerin sunulmasını devralacak yedek yerlere ya da bir teknolojinin arızalanması durumunda görevi devralacak yedek bir teknolojiye sahip olmayı içerebilir.

Olağanüstü durum kurtarması, kuruluşun olağanüstü durumda kurtarma gerçekleştirebilme yeteneğine dayanır. Siber güvenlikle ilgili olağanüstü bir durum, kuruluştaki tüm bilgisayarların boşaltılmasını ya da veritabanlarının tamamen silinmesini kapsayabilir. Bu kurtarma planlaması sürecinde, kuruluşların neredeyse sıfırdan başlamaya hazırlıklı olmaları gerekir.

Hem süreklilik planlaması hem de kurtarma süreçleri, diğer güvenlik işlevleriyle yüksek seviyede örtüşür. Geçmişte endişeler genellikle sel, deprem veya yangın gibi doğal afetler hakkında olsa da, siber saldırıların da doğal muadilleriyle aynı, hatta daha yüksek seviyede kesintiye yol açabileceği gittikçe daha açık hale geldi. Çok uluslu bir kuruluşun tüm tesislerinin aynı anda bir enerji kesintisinden etkilenmesi düşük bir ihtimalken, kurumsal dosya paylaşımları ya da etki alanı yönetimi sistemleri gibi önemli genel hizmetlerin kapanmasına neden olacak bir siber saldırı ihtimali daha yüksektir.

-----------------------------------------------------------------

Kriptografi, bilgi güvenliği kapsamındaki hayati kavramların temelini oluşturur ve başarılı olmak isteyen tüm siber güvenlik uzmanlarınca anlaşılması gerekir.

Kriptografi, kod yazma ve çözme sanatı olarak tanımlanır.

Güvenli iletişim kurmak için gözetilmesi gereken üç temel özellik vardır.

1. Özellik: Gizlilik
2. Özellik: Gerçeklik
3. Özellik: Bütünlük

# Şifreleme
Şifreleme, bir mesajın süreci tersine çevirecek şifre çözme anahtarına sahip kişiler haricinde anlaşılamayacak farklı bir şeye dönüştürülmesidir. Bir mesaj okunamayacak duruma getirildiğinde, şifrelendiği söylenir. Genel hatlarıyla, günümüz dünyasında kullanılan iki şifreleme biçimi bulunur: simetrik ve asimetrik.

# Simetrik şifreleme
Simetrik şifrelemede, bilginin şifrelenmesine yönelik algoritma, şifre çözme işlemiyle aynı anahtarı kullanır. Simetrik şifreleme hızlıdır ve uygulanması kolaydır. Hem göndericinin hem de alıcının aynı anahtara erişimi olmasına dayanır, gizli bilgi bağlantısını korumaya yönelik bir tür parola veya "paylaşılan gizli anahtar" gibidir. Günümüzde kullanılan ve simetrik modelleri izleyen algoritmalar, Otomatik Şifreleme Standardının (AES) versiyonlarını içerir. Tarayıcınız da bu sayfayı güvenli olarak görüntülemek için muhtemelen bunu kullanıyor!

# Asimetrik şifreleme
Asimetrik şifrelemede, bilgiyi şifreleme işlemi, bilginin şifresini çözmek için farklı bir anahtar kullanır. Bu anahtarlar, genel anahtarlar ve özel anahtarlar olarak bilinir. Aynı anda üretilirler. Bir genel anahtar üretildiğinde, bunu herkesle paylaşabilirsiniz. Genel anahtarın bir kopyasına sahip herkes mesajı şifreleyebilir, bu mesajın şifresi ise sadece özel anahtara sahip kişi tarafından çözülebilir. Asimetrik şifrelemenin sunduğu temel avantaj, kuruluşların daha önce bir "anahtar" alışverişinde bulunmadıkları bir kişi veya kurumla gizli olarak iletişim kurabilmeleridir. Ayrıca bu şifreleme türü, bir mesajın doğru kişiye gönderilmesini garanti edebilir. 

----------------------------------------------------------------------

# Tehdit istihbaratı nedir?
Birleşik Krallık Savunma Bakanlığı, istihbaratı en basit şekliyle, “Tüm seviyelerde liderler tarafından kullanılmak üzere yeteneklerin, niyetin ve fırsatların değerlendirilmesi amacıyla bilgilerin yönetilen ve koordine bir şekilde elde edilip incelenmesi” olarak tanımlıyor. 
Bu durumda, siber tehdit istihbaratı da bir kuruluş tarafından siber saldırganların nedenlerini ve davranışlarını anlamak için toplanan ve analiz edilen veriler demektir. Bu, daha ayrıntılı olarak keşfedeceğimiz istihbarat ortamının bir alt kümesidir.

Siber güvenlik açısından istihbarat, genellikle saldırgan taktiklerine, tekniklerine ve prosedürlerine (TTP'ler) ya da diğer ihlal göstergelerine (IOC'ler) odaklanır. Peki, bu terimler ne anlama geliyor?

Taktikler, "neden" sorusunun yanıtıdır ve bir düşmanın bir eylemi gerçekleştirmeye yönelik taktiksel hedefi ya da sebebidir. Örneğin bir düşman, ayrıcalıklarını artırmak isteyebilir.

Teknikler, "nasıl" sorusunun yanıtıdır ve bir düşmanın bir eylem gerçekleştirerek hedefine ulaşmak için kullandığı yolları ifade eder. Örneğin bir düşman, ayrıcalıklarını artırmak için erişim denetimlerini atlamak isteyebilir.

Prosedürler ise bir düşmanın teknikler için kullandığı özel uygulama yollarıdır. Örneğin bir düşman, ayrıcalıklarını artırmak için bir araç ya da program kullanabilir.

İhlal göstergeleri (IOC'ler), bir saldırgan faaliyetiyle ilgili işaretlerdir. Örneğin belirli IP adresleri, tehdit gruplarıyla ya da bazı dosyalarla ilişkilendirilebilir. Bir ihlal göstergesinin varlığı, adından anlaşılacağı üzere, kuruluşun hali hazırda ihlal edildiğini gösterebilir.

# Tehdit istihbaratının yararları

Uyarı sağlama
- Tehdit istihbaratının getirdiği önemli bir avantaj, kuruluşların saldırılara karşı hazırlanmalarına olanak tanımasıdır.
- Belirli jeopolitik ya da teknik gelişmeler, bir kuruluşun risk profilini oldukça hızlı bir şekilde geliştirme potansiyeline sahiptir.
- Önceden haberdar olmak, kuruluşlara bir saldırıyı henüz gerçekleşmeden durdurmak için savunmalarını daha iyi hazırlama olanağı tanır.

İhlal göstergeleri sağlama
- Tehdit istihbaratı, ihlal göstergeleri sağlayarak saptama faaliyetlerine yardımcı olur.
- Bunlar saldırganlar tarafından kullanılan IP adresleri, sağlama dosyaları ya da etki alanları olabilir.
- Bir kuruluştaki savunucu, bu işaretleri arayabilir ve bu işaretler algılandığında uyarı vermesi için birtakım algılama kuralları ekleyebilir.

Bağlam sağlama
- Bir kuruluş bilinmeyen bir yer veya gruptan saldırıya uğradığını keşfederse saldırganı anlamak için istihbarat kaynaklarından yararlanabilir.
- Bağlam, gelecekte nelerin bekleneceğine yönelik ilişkilendirme ve rehberliğe yardımcı olacak yararlı bilgileri içerebilir.

Emsallerden öğrenme
- Bazı şeyler en iyi başkalarından öğrenilir.
- Kuruluşlar, saldırganların kendilerine nasıl saldırdığı, kendilerini nasıl savundukları ve yaklaşımlarının ne kadar etkili olduğu hakkında bilgi paylaşabilirler.
- Paylaşılan bu hikayeler, sektörün tamamını güçlendirmek için harika bir yöntemdir.


# Tehdit istihbaratının kaynakları

Tehdit alışverişi platformları
- Siber güvenlik uzmanlarının, toplanan bilgilerden ve analizlerden oluşan veritabanlarına erişmelerine olanak sağlayan bir dizi çevrimiçi platform bulunur.
- Bunlar ücretsiz platformlardan abonelik yöntemiyle sağlanan platformlara ya da kapalı sektör gruplarına kadar uzanabilir.
- IBM X-Force Exchange platformu, bu platformlara bir örnektir.

Konferanslar
- Konferanslar, siber güvenlik uzmanlarının sektördeki en yeni gelişmeleri paylaşabilecekleri iyi bir yöntemdir.
- Bazı araştırmacılar, bir etkinlikte daha geniş bir yankı yaratmak için keşifleri kamuya açıklamayı ertelerler.
- Ayrıca konferanslarda gayri resmi görüşmelerden bilgi edinme ve ağ oluşturma fırsatları da bulunur.
- Black Hat, RSA Conference ve CYBERUK, bu konferanslardan bazılarıdır.

Makaleler ve haberler
- Bazı yayın organları, BT dünyasındaki gelişmelere yer verme konusunda önemli çaba sarf ederler. Security Intelligence bunlara bir örnektir.
- Belirli güvenlik sorunları daha yüksek profilli hale geldiğinden, basında bunlarla ilgili haberlere verilen yer de önemli ölçüde artmıştır.
- Daha özel bir kitleye yönelik geleneksel yayın organlarının yanı sıra küçük sitelerden oluşan iyi bir koleksiyon da mevcuttur. Krebs on Security ve Graham Cluley, bu bloglara birer örnektir.

Ürün satıcıları
- Microsoft, Google ve Apple gibi çok sayıda yazılım üreten kuruluşlar, sık sık ürünlerine ilişkin periyodik güvenlik tavsiye raporları hazırlarlar.
- Bu bildiriler çok önemli bilgiler içerebilir ve sistem yöneticilerinin bunları kesinlikle okumaları gerekir.

# İş rolleri
Siber tehdit istihbaratı dünyasında, iş rolleri genel olarak üretim ve yorumlama şeklindeki iki alana ayrılır.    

Üretim tarafında, bilginin toplanıp zenginleştirilmesini kapsayan bir dizi iş rolü vardır. Bu rollerden bazıları teknik odaklıdır; örneğin tarayıcı ya da web bilgi toplayıcılarının geliştirilmesiyle ya da yazılım analizlerinin gerçekleştirilmesiyle ilgili olan roller gibi. Bazı roller ise daha fazla manevrayı, suç çetelerine ve piyasalara sızmayı içerebilir. Son olarak; çeviri, dil analizi ve psikometri (mental kapasite ve süreçleri ölçme bilimi) ile alakalı roller de vardır. Bu rollerin her biri bilgi toplar ve bu bilgiden istihbarat oluşturur.

Yorumlama tarafında ise, istihbarat geliştirme "şirket içinde" ya da bir komisyon tarafından yapılmadıkça istihbaratın, analistlere öğrenmek istedikleri her şeyi söylemesi ender bir durumdur. Güvenlik analistleri bir dizi konuya ilişkin çeşitli uyarılar alabilirler. Ardından bu bulguları incelemeleri ve önerilebilecek en iyi eyleme karar vermeleri gerekir. Yorumlamanın etkili olması için kişiye özel ya da gizli bilgiler gibi benzersiz, organizasyonel nitelikler göz önünde bulundurulmalıdır. Her şeye uygun bir model yoktur!

