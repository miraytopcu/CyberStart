Günümüzde çoğu veritabanı, birbirine bağlı birden fazla veri kümesi veya tablosundan oluşan koleksiyonlar olan ilişkisel veritabanlarıdır. Örneğin bir tablo isim ve adresleri listelerken, diğeri özelliklerini ve sahiplerini listeleyebilir. Sahiplerinden bazıları isim ve adres tablosunda da görülüyorsa, iki tablo birbirine bağlanarak ilişkisel bir veritabanı oluşturabilir. İlişkisel Veritabanı Yönetimi Sistemleri (RDMS), veri bilimcilerin veritabanındaki tüm tablolardan bilgileri ilintilendirmelerine, ilgili verileri değiştirmelerine veya yapısını bozmadan veritabanında veri ekleme veya silme işlemleri gerçekleştirmelerine yardımcı olur.

# Verileri saklamak ve sıralamak için bir veritabanı kullanın
Çoğu veritabanı yönetimi sistemi, soru sormak veya "veritabanını" sorgulamak veya içeriğini düzenlemek için bir tür Yapılandırılmış Sorgu Dili veya SQL kullanır. İnanılmaz derecede yararlı olan SQL'i bir kitap, çevrimiçi bir ders veya bir bilgisayar kulübünden öğrenebilirsiniz. Nasıl çalıştığına bir bakalım.

Şehrinizdeki kayıtlı oy kullananlardan oluşan bir tabloda bir milyon veri satırınızın olduğunu düşünün. (Çoğu veritabanı bu kadar büyüktür, hatta daha da büyük olabilir!) Tablo, her seçmenin oy verme yeri, parti üyeliği ve yaşı hakkında bilgi içerir. 21 yaş altı tüm seçmenler hakkında bilgi almak isterseniz, bunun için basit bir arama yapan bir SQL sorgusu yazabilirsiniz. Bu sorgu, şöyle görünecektir:

![Image](https://bundles.yourlearning.ibm.com/skills/learn/assets/XVZNYYMWWNQVPP7X/SQL%20query.svg)

Evet, bu sorunun cevabı basit bir aramayla alınabilirdi. Ancak, farklı yaştan kişilerin ne sıklıkta seçimlere katıldığını araştırmak üzere belirli bir coğrafi bölgede yaşayan seçmenleri ortaya çıkarmak isterseniz, sorgunuz basit bir aramaya fazla gelecektir. Ancak SQL bu işi halledebilir!

SQL, ilişkisel veritabanlarında yapılan çoğu işi yöneten dil olsa da, bu işi yapabileceğiniz birçok İlişkisel Veritabanı Yönetim Sistemi mevcuttur. Bu alana giriş yaptığınızda, şu gibi isimlerle karşılaşacaksınız:

- MySQL
- Microsoft Access
- PostgreSQL
- Oracle
- IBM DB2
- MongoDB

# Verilerin yönetilmesi için doğru araçları seçin
Nereden başlayacaksınız? Onlarca faydalı veri bilimi aracı ve platformu var! İşte kendi veri bilimi serüveninize başlamak için kullanabileceğiniz bazı popüler ve yeni açık kaynak platformlarının bir listesi.

## R, iyi bir başlangıç noktasıdır
R, istatistik analizi ve veri bilimi için sık sık kullanılan bir programlama dili ve ücretsiz donanım ortamıdır. Birçok geleceğin veri bilimcisi, bu araçla veya popüler R arabirimlerinden biriyle başlar ve R içerisinde, ggplot2 gibi veri görselleştirmesi konusunda yardımcı olacak yüzlerce paket mevcuttur.

RStudio'nun görünümü şu şekildedir. Bu, R'de çalışma konusunda popüler bir arabirimidir.

![Image](https://bundles.yourlearning.ibm.com/skills/learn/assets/XVZNYYMWWNQV2EZQ/Rstudio.png)

## Python genel amaçlar için kullanılır
Python, veri bilimi için de kullanılabilen popüler, genel amaçlı bir programlama dilidir. Python'u pandas  gibi bir kitaplıkla ve yararlı bir kullanıcı arabirimiyle birleştirdiğinizde, yeni içgörüler ve veri görselleştirmeleri oluşturmanıza yardımcı olabilir.

## MATLAB zor hesaplar yapmanıza yardımcı olur
MATLAB, sayısal hesaplamaya odaklanmak üzere tasarlanmıştır. Genellikle yüksek öğretimde kullanılır.

## Apache Spark büyük veri ve makine öğrenimini destekler
Apache Spark, aşırı derecede büyük veri setleri ve bu setleri kullanan makine öğrenimi için özellikle kullanışlı olabilen, tescilli bir genel amaçlı çerçevedir.

İstatistikler için grafikleri kullanın
İlişkiler için haritaları kullanın

# Veri görselleştirmesi için doğru aracı seçin
Çoğu hesap tablosu programında, grafikler ve çizelgeler gibi basit veri görselleştirmeleri oluşturabilirsiniz. Ancak veriler karışık hale geldikçe, başka araçlara yöneleceksiniz. Bazıları bağımsız görselleştirme ürünleri olarak satılırken, bazıları ise veri yönetimi sistemlerinin eklentileridir.

Ayrıca basılı ve çevrimiçi formda, görselleştirmelerinizi daha kullanışlı kılmanıza yardımcı olacak harika kitaplar bulacaksınız. Size bir ipucu: Bir görselleştirme ustası olan Edward Tufte'nin çalışmalarına göz atın!

## Tableau interaktif görselleştirmeler oluşturur
Tableau, kod yazmadan interaktif görselleştirmeler oluşturmanıza yardımcı olabilir. Çoğu çevrimiçi kuruluş tarafından kullanılması, bu aracı keşfetmeniz için harika bir araç haline getirir.

## ggplot2 karmaşık verilerde yardımcı olur
En popüler R çalışma alanlarından birisi olan ggplot2, daha az güçlü diğer programlar için daha karmaşık olan verilerin görselleştirilmesine yardımcı olabilir.

## Matplotlib, Python ile birlikte iyi çalışır
Matplotlib, Python programlama diliyle çalışan popüler bir görselleştirme aracıdır. Programcıların birçok farklı formatta çizelge, grafik ve harita oluşturmalarına yardımcı olur.

# Veri bilimi, makine öğrenimine güç katıyor
Bir veri bilimi dersinde neden yapay zeka hakkında bir şeyler okuduğunuzu merak mı ediyorsunuz? Çünkü makine öğrenimi için, devasa miktarda veri ve bu veriden anlam çıkarma yeteneği gerekir. Bu, çok büyük ölçekte veri bilimidir! Günümüzün veri bilimcileri, dünyadaki devasa veri depolarından içgörüler elde etmek için makine öğrenimi algoritma ve tekniklerini kullanırlar.

Makine öğrenimi büyük miktarda veriyi analiz ettiğinde öğrenebileceklerimize dair iki örnek:

- Regresyon, bir olgu kümesinin veya rakamın diğer ilgili faktörler veya rakamlar değiştiğinde nasıl değişeceğini inceler. Örneğin, makine öğrenimi, alandaki diğer benzer evlerin satışlarına dayanarak yeni bir evin satış fiyatını tahmin edebilir.
  
- Sınıflandırma, rastgele görünen bilgi kümeleri içerisinde saklı grupları belirler. Örneğin, makine öğrenimi binlerce sokak kamerasından alınan videolara bakabilir ve belirli bir cinsiyet, ırk veya görünümdeki insanların kullandığı yolları izleyebilir.