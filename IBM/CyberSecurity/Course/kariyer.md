# SOC analisti
SOC analisti, şirketin güvenlik operasyonları merkezinde (SOC) bulunan giriş seviyesinde bir iş rolüdür.

Aynı zamanda siber güvenlik analisti veya öncelik belirleme analisti olarak da bilinir.
Bu "reaktif" bir roldür, çünkü analisti tek tek uyarılara müdahale eder ve tıpkı bir dedektif gibi, delillere dayanarak incelemelerde bulunur.
SOC analisti rolünden "1. Seviye" bir pozisyon olarak bahsedildiğini görebilirsiniz. Artan düzende numaralandırılan seviyeler, genelde sorumluluk seviyelerini ve karşılık gelen deneyim gereksinimlerini göstermek için kullanılır. Ayrıca "Junior" bir pozisyon olarak da adlandırılabilir.
Tipik bir günde neler yaparlar?

Bilgisayar korsanlarının veya truva atları ve fidye amaçlı yazılımlar gibi kötü niyetli yazılımların varlığını gösterebilecek şüpheli faaliyetleri tespit etmek için bilgisayar ağı trafiğini izlerler.
Bir güvenlik olayı ve olay izleme (SIEM) aracı (IBM Security QRadar gibi) tarafından tetiklenen uyarıları inceler ve bunların yanlış pozitif mi (yanlış alarm) yoksa doğru pozitif mi (ilgilenilmesi gereken gerçek zamanlı bir güvenlik olayı) olduğunu belirlerler. Gerçek pozitif bir uyarı söz konusuysa bu; bağlamı, nedeni ve etkilenen kullanıcıyı ve kullanıcıları belirlemeyi de kapsar.
Güvenlik olayının önem düzeyini değerlendirir ve bu olaylara uygun risk derecelendirmesini (örn. düşük veya yüksek önem düzeyi) atarlar.
Yüksek önem düzeyine sahip olayları olay müdahale personeline yönlendirirler.
Bir SOC analistinin yapacağı şeylere dair bir örnek ne olabilir?

SIEM aracında bir uyarının geldiğini varsayalım. SOC analisti, uyarının kuruluştaki üst düzey yöneticilerden birinin bilgisayarına bir kötü amaçlı yazılım bulaşmasıyla alakalı olduğunu saptar. İnceleme sonucunda, SOC analisti bunun bir doğru pozitif olduğu sonucuna varır. Oldukça hassas bilgilere erişimi olan bir yöneticiyi etkileyen bir saldırı olduğundan, SOC analisti bu saldırıya yüksek önem düzeyi atar.

Bu iş rolü için sahip olunması gereken temel beceriler nelerdir?

Bilgisayar ağı oluşturma ve sistem denetimi becerileri
Örneğin bir bağlantı bir IP adresinden geçerek ağ, yönlendirici ve ağla ilgili cihazlardan nasıl akar? Bir Windows sunucusu ve Linux sunucusu nasıl yönetilir? Veritabanı sunucusu nedir? Bir cihaz, yönlendirici, güvenlik duvarı vb. için tüm olay ve işlemlerin sistem log'larına nasıl bakılır ve bu log'lar nasıl anlaşılır?
Not: Bu rol için bilgisayar programcılığı becerileri gerekmez. Kodlama, bu rol için bir zorunluluk değildir.

# Olay müdahale görevlisi
Yine SOC içerisindeki bir diğer rol, orta seviye bir iş rolü olan olay müdahale görevlisidir.

Ayrıca olay müdahale analisti olarak da bilinir.
Bu rol, bildirilen bir uyarının bir kuruluş saldırısı mı, yoksa  şirketin ağına yönelik sürekli bir tehdit mi olduğunu belirler ve düzeltilmesini sağlar.
Tipik bir günde neler yaparlar?

Bir siber güvenlik olayının kapsamını belirlerler. Örneğin insan kaynakları departmanındaki bir kişinin iş istasyonu bilgisayarında kötü amaçlı yazılım saptanırsa, bu departmandaki diğer bilgisayarlara yayılmış mıdır? Peki ya şirketin diğer kısımlarına? Kötü niyetli davranışı otomatik savunmalar (virüs koruması yazılımı veya güvenlik duvarları gibi) yoluyla kontrol altına alındı mı, yoksa şirket varlıkları tehlikeye girdi mi?
Siber güvenlik olayının kapsamına göre düzeltmeyi planlarlar. Bu planlama, olayın niteliğinin araştırılmasını (örn. kötü amaçlı yazılım tarafından hedeflenen kötü amaçlı eylem tipi) ve buna en iyi nasıl müdahale edileceğinin belirlenmesini kapsar.
Uygun ekiplerle birlikte, virüsten etkilenen bilgisayarlar için yeniden görüntü oluşturulması konusunda BT sorun kayıtları açılması, son kullanıcıların kimlik avı e-posta eklerine tıklamama konusunda eğitilmesi veya veri ihlalinin boyutunun ilgili yöneticilere zamanında iletilmesi gibi düzeltmeleri uygularlar.
Bir olay müdahale görevlisinin yapacaklarına dair nasıl bir örnek verilebilir?

Bir yöneticinin bilgisayarında yüksek önem düzeyine sahip bir kötü amaçlı yazılım olayının bildirildiğini varsayalım. Olay müdahale görevlisi, başka çalışanların kötü amaçlı yazılımdan etkilenip etkilenmediğini, buna nasıl en iyi şekilde müdahale edilebileceğini belirler ve düzeltmek için diğer kişilerle işbirliği yapar.

Bu iş rolü için sahip olunması gereken temel beceriler nelerdir?

Bilgisayar ağı oluşturma ve sistem denetimi becerileri
Şirket ve kurum ilkelerine (örn. veri, gizlilik, yasal) aşinalık
Doğru teknik ve teknik olmayan düzenleyici eylemleri seçmeye yönelik düzeltme becerileri

# Tehdit avcısı
Yine SOC içerisindeki bir diğer rol, orta seviye bir iş rolü olan tehdit avcısıdır.

Tehdit analisti olarak da bilinir.
Bu "proaktif" bir roldür, çünkü tehdit avcısı en son tehditler ve bu tehditlerin nasıl geliştiğine ilişkin bilgileri takip eder ve şirketin SIEM aracında uyarıların tetiklenmesine yönelik kuralları kodlar.
Tipik bir günde neler yaparlar?
IBM X-Force Exchange gibi çeşitli tehdit kaynaklarını sürekli olarak izleyerek, "tehdit ortamını" proaktif olarak araştırırlar.
Hedef alınan sektörler, faydalanılan güvenlik açıkları ve tehditlerin kullandığı taktikler gibi kriterlere dayalı olarak, hangi yeni ve yükselen tehditlerin kuruluşlarına yönelik en yüksek riski oluşturduğunu değerlendirirler.
Aşağıdaki eylemlerle bu tehditlere müdahale ederler:
Sistem yapılandırma değişikliklerinin uygulanması.
Bu tehditlerin ayırıcı özellikleri olan etkinliği otomatik olarak saptamak için güvenlik araçlarında otomasyonun programlanması.
Kuruluşun potansiyel saldırılara duyarlı kılınması.
Bir tehdit avcısının yapacağı şeylere dair bir örnek ne olabilir?

Yeni bir fidye yazılımı tehdidinin kamuya duyurulduğunu varsayalım. Bir tehdit avcısı bu tehdidi araştırır, tehdidin kuruluşa sızmasını engellemek ve sızması durumunda tehdidi saptamak için otomasyon uygular.
Bu iş rolü için sahip olunması gereken temel beceriler nelerdir?

Bilgisayar ağı oluşturma ve sistem denetimi becerileri
Tehdit zekası bilgilerinin kaynaklarının anlaşılması ve şüpheli davranışın saptanması için otomasyon uygulanması
Not: Tehdit avcıları genelde SOC analisti, olay müdahale görevlisi, sızma testi uzmanı ve güvenlik açığı analisti gibi diğer güvenlik rollerinde deneyim sahibidir.

# Ek iş rolleri
Güvenlik danışmanı
Üst düzey bir danışmanın rehberliğinde siber güvenlik sorunlarının çözülmesinden sorumlu bir giriş veya orta seviye pozisyonu.
Bir projenin yaşam döngüsü boyunca gerekli olan görevleri yerine getirirler.
Genellikle uzman kaynak olarak şirket dışından görevlendirilirler.
Strateji danışmanı, operasyon danışmanı vb. gibi birçok özel alan mevcuttur.

Güvenlik yöneticisi
Yine SOC kapsamında çalışan, ancak bir SOC analistinden oldukça farklı bir rol olan, orta seviye bir pozisyondur.
Bir sistem yöneticisi gibidir, ancak bu rol SIEM araçları gibi güvenlik araçlarıyla çalışır.
Yamalar uygulayıp bu yamaları doğru performans gösterecek şekilde ayarlayarak, güvenlik araçlarının bakımını gerçekleştirir.
Güvenlik sistemlerinde görevleri otomatikleştirmeye yönelik komut dosyaları yazar.
Olayları araştırmaz.

Kimlik ve erişim yönetimi (IAM) yöneticisi
Bir şirkette farklı grupları destekleyen giriş veya orta seviye bir pozisyondur.
Uygulama/sistem yetkileri ve ayrıcalıklarının yönetiminden, tekli oturum açmadan, uygulamalara ilişkin bildirimde bulunmadan ve yeni uygulamalar için kimlik ve erişim yönetimi özelliklerini uygulamak amacıyla geliştiricilerle birlikte çalışmaktan sorumludur.
IAM araçları ve ağ yönetimi becerisine sahip olmalıdır.

Sızma testi uzmanı
Sızma testi uzmanı olarak da bilinen, "kötü adamları" taklit eden, daha gelişmiş bir pozisyondur.
Bir bilgisayar korsanının yararlanabileceği güvenlik açıklarını bulmak üzere bilgisayar sisteminin, ağın veya uygulamanın test edilmesinden sorumludur.
Bir kalite kontrol ve dışarıdan değerlendirme sağlamak üzere şirketin sistemlerine "sızmak" üzere genellikle şirket dışından görevlendirilir.

Mobil cihaz yöneticisi
Çalışanların mobil cihazlarına yönelik güvenlik korumasını yöneten, giriş seviyesindeki bir pozisyondur.
Bir sistem yöneticisi geçmişi olması gerekir.

Uyumluluk analisti
Bir şirketin güvenlik ilkelerine, gizlilik ilkelerine ve ülke kanunlarına uygun hareket edip etmediğine dair iç denetim yapan, büyük bir şirketteki giriş seviyesi pozisyondur.
Ayrıca kuruluşların, sektöre (örn. sağlık, finans vb.) bağlı olarak zorunlu olan bir dış denetime hazır olmalarına yardımcı olur.

---------------------------------------------------------------------------

CompTIA Security+
Bu, uygulayıcıların temel güvenlik işlevlerini yerine getirmek ve bir BT güvenlik kariyeri yolundan gitmek için ihtiyaç duydukları temel becerileri doğrulayan küresel bir sertifikasyondur.
Bu, giriş seviyesindeki siber güvenlik iş rolleri için en iyi sertifikasyondur.
CompTIA Security+ sertifikasyonu, şu iş rollerine yöneliktir: sistem yöneticisi, ağ yöneticisi, güvenlik yöneticisi, kıdemsiz BT denetçisi ya da sızma testi uzmanı, güvenlik uzmanı, güvenlik danışmanı ve güvenlik mühendisi.
CompTIA Network+ sertifikasyonuyla birlikte güvenliğe odaklanmış iki yıllık bir BT yönetimi deneyimine sahip olunması önerilir.

CompTIA Cybersecurity Analyst (CySA+)
Siber güvenlik tehditlerinin önlenmesi, algılanması ve bu tehditlerle mücadeleye yönelik olarak ağlara ve cihazlara davranış analitiği uygulayan bir BT iş gücü sertifikasyonudur.
CySA+, 2014 sonrası siber güvenlik ortamında gelişmiş sürekli tehditleri kapsayan, en güncel güvenlik analisti sertifikasyonudur.
CompTIA CySA+ serfitikasyonu şu iş rollerine yöneliktir: BT güvenlik analisti, SOC analisti, güvenlik açığı analisti, siber güvenlik uzmanı, tehdit istihbaratı analisti, güvenlik mühendisi, siber güvenlik analisti ve güvenlik izleme.
Network+, Security+ ya da eşdeğer bilgiye sahip olunması önerilir. En az 3-4 yıllık uygulamalı bilgi güvenliği deneyimine veya ilgili bir deneyime sahip olunmalıdır. Zorunlu bir önkoşul olmasa da CySA+, CompTIA Security+ sertifikasyonunu ya da eşdeğer bir deneyimi takip edecek şekilde tasarlanmıştır ve teknik, uygulama odaklıdır.

IT Infrastructure Library (ITIL) Sertifikasyonu
ITIL, BT Hizmet Yönetimi (ITSM) için küresel olarak kabul edilmiş bir en iyi uygulama çerçevesidir.
IITL sertifikasyonu şeması, ITIL çerçevesine yönelik modüler bir yaklaşım sağlar. Temel seviyeden Usta seviyesine olmak üzere, birden fazla sertifikadan oluşan katmanlı bir yapıya sahiptir. Bu da, ITIL'in farklı öğretileri ve alanlarına dair esnekliğin yanı sıra, çalışmaları temel ilgi alanlarına odaklayabilme olanağı sağlar.
Yalnızca belirli bir rolün gerekmesi durumunda geçerli olan giriş seviyesinde sertifikasyonlar vardır.

Certified Ethical Hacker (CEH)
Certified Ethical Hacker (Sertifikalı Etik Bilgisayar Korsanı), hedef sistemlerdeki zayıflıkları ve güvenlik açıklarını anlayan, bunları nasıl arayacağını bilen ve kötü amaçlı bir bilgisayar korsanıyla aynı bilgileri ve araçları kullanmasına rağmen, bunu hedef sistem(ler)in güvenlik duruşunu değerlendirmek adına yasal ve meşru bir şekilde yapan becerikli bir uzmandır.
CEH yeterlilik belgesi, Etik Bilgisayar Korsanlığı adlı ağ güvenliği öğretisi konusunda kişileri satıcı bakımından tarafsız bir perspektif kullanarak tasdik eder.
Bu güvenilir ve saygın program, tüm siber güvenlik çalışanlarına fayda sağlayabilir.

Certified Information Systems Security Professional (CISSP)
CISSP sertifikasyonu, bir siber güvenlik programının tasarımı, uygulanması ve yönetilmesi konusunda uygulayıcının becerilerini ve uzmanlığını tasdik eder.
Bilgi güvenliğinden sorumlu başkan (CISO), güvenlik direktörü, güvenlik analisti, güvenlik mimarı, güvenlik danışmanı vb. gibi pozisyonlar dahil olmak üzere geniş bir güvenlik uygulama ve ilke yelpazesi dahilinde bilgilerini kanıtlamak isteyen güvenlik uygulayıcıları, müdürler ve yöneticiler için idealdir.
Not: Beş yıllık deneyim gereklidir.

Certified Information Security Manager (CISM)
ISACA; kanıtlanmış, çok boyutlu uzmanlıklarını ve işletmelere dair karmaşık, zorlu güvenlik yönetimi problemlerini anlama yeteneklerini kanıtlamak isteyen uygulayıcılar için CISM sertifikasyonu sunar.
Yakın zamanda gerçekleştirilen bağımsız çalışmalarda CISM, getirisi en yüksek ve en fazla talep edilen BT sertifikasyonlarından biri olarak derecelendirilmiştir.
Not: Beş yıllık deneyim gereklidir.



