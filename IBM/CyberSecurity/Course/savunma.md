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

 