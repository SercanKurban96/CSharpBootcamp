#  <img height="50" src="https://user-images.githubusercontent.com/25181517/121405384-444d7300-c95d-11eb-959f-913020d3bf90.png"> EĞİTİM KAMPI
👋 Merhabalar, oluşturmuş olduğum bu repo, Murat Yücedağ hocamızın YouTube üzerinden hazırlamış olduğu C# Eğitim Kampı süresince tamamlamış olduğum projeleri içermektedir. Bu eğitimde C# Konsol Uygulaması'ndan "Merhaba Dünya" ile başlayıp en son yapılan uygulamaya kadar anlatılmaktadır.

## 🖥️ C# Eğitim Kampı Ders 1 - Giriş, Merhaba Dünya, Yazdırma Komutları, String ve Int Değişkenler
### 📆 Tarih: 28 Eylül 2024
### 📋 C# Konsol Uygulaması ile Yapılan Uygulamalar:

İlk olarak Visual Studio 2022 programımızı açıyoruz. Daha eski versiyonlarını da kullanabilirsiniz. Programımız açıldıktan sonra şu şekilde karşımıza çıkacaktır.

![image](https://github.com/user-attachments/assets/3a35e7f7-bfce-494e-ab43-0be89631a1f7)

Açılışta sol tarafta yer alan daha önceki yaptığım uygulamaları göstermektedir. Daha önce uygulama yapmadıysanız burası sizde boş gözükecektir. Yeni bir proje oluşturmak için sağ alt tarafta yer alan "Create a new project" kısmına tıklıyoruz.

![image](https://github.com/user-attachments/assets/4f9682ff-9e2b-4f64-b44f-b589cd1ddb01)

Burada ise daha önceden kullanmış olduğum şablonlar yer almaktadır. Burası sizde boş gözükecektir. Bu eğitimde ilk olarak konsol uygulamalarından başlayacağız. İlk olarak bütün projeleri tek bir çatı altında toplamak için arama çubuğundan "Blank Solution" yazıp buradaki şablonu seçip Next diyoruz. 

![image](https://github.com/user-attachments/assets/9bedfba8-8a5f-4fd6-8b4a-d07debe358da)

Burada istediğiniz bir proje ismini verebilirsiniz ve istediğiniz proje yolunu ayarlayabilirsiniz. Create diyoruz.

![Ekran görüntüsü 2024-10-23 205001](https://github.com/user-attachments/assets/a938f0f1-d2ec-4d4d-a6c7-65c27956cca3)

Projemiz ilk olarak bu şekilde gözükecektir. Eğitimde yapılan tüm uygulamalar burada yer alacaktır. Yeni bir proje oluşturmak için ilk olarak Solution kısmına sağ tıklayıp Add kısmından New Project diyoruz. 

![image](https://github.com/user-attachments/assets/07ce6e54-91bf-4736-b779-b1e9aaf60003)

İsterseniz yukarıda yer alan arama çubuğundan veya altta yer alan seçeneklerden de seçebilirsiniz. Bizim seçmemiz gereken ise "All languages" kısmından C#, "All platforms" kısmından Windows, "All project types" kısmından Console olanı seçiyoruz.

Burada 2 tane Console App şablonu bulunmaktadır. Bizim seçmemiz gereken şablon ise Console App (.NET Framework) olanıdır. Next diyoruz.

![image](https://github.com/user-attachments/assets/997f16a2-9d06-4c9c-85b3-c60be607ac2f)

Burada istediğiniz proje adını verebilirsiniz. Oluşturduğunuz projeler burada hazırlamış olduğumuz şablona kaydedilecektir. Create diyoruz. 

![image](https://github.com/user-attachments/assets/72b3a570-7a95-4140-82aa-9c45b1cb7891)

Proje oluşturma bu şekildeydi. Daha önceden bir proje oluşturduğum için burayı sadece örnek olarak anlattım. Şimdi yapmış olduğum projenin detayları aşağıda yer verilmiştir.

![image](https://github.com/user-attachments/assets/33b954f7-b2fb-47d5-aeca-3bfbd7d23a90)

Bu projede ilk olarak Yazdırma Komutları başlığından "Merhaba Dünya" kodunu yazdırdım. Yazdırma işleminden önce burada bir tane #region ve #endregion ifadelerini kullandım.

## 📍 Console.WriteLine ile Console.Write arasındaki fark nedir?
WriteLine() metodu, Console ekranına çıktı vermek için kullanılan metoddur.
Write() metodundan tek farkı çıktı verdikten sonra alt satıra iner.

## 📍 C# ile Region Kullanımı 
Region, kodların okunurluğunu arttırmak ve daha düzenli bir yapıda saklamak için kullanılmaktadır. Region eklenmek istenilen kodun üst tarafında #region, alt tarafında ise #endregion ifadesi bulunmaktadır. Kısayol için Ctrl + k + s ile region oluşturabilir.

![image](https://github.com/user-attachments/assets/eefcb3ff-9190-4375-b6a5-3e8e5d55e309)

Projeyi çalıştırmak için yukarıda yer alan Start tuşuna veya kısayoldan F5 ile çalıştırabiliriz. Ancak program çalıştıktan sonra hemen kapanacaktır. Bunun için ek olarak en alt satıra Console.Read(); komutunu ekliyoruz.

## 📍 Console.Read() nedir?
Console.Read(): Bu metod tek bir karakter okur. Geriye okunan karakterin ascii karşılığı olan bir sayı döndürür. Döndürülen değer sayı olduğundan değer sayı veri tipinde bir değişkene aktarılabilir.

![image](https://github.com/user-attachments/assets/b1f6c9d4-107e-436a-82ea-0e6bac47620f)

Programımızı çalıştırdıktan sonra karşımıza bu şekilde çıkacaktır.

![image](https://github.com/user-attachments/assets/d32f63db-0eb9-4d13-994c-2b00737d7be6)

Burada sadece Console.WriteLine komutunu kullanarak Yemek Kategorileri adında mini bir program tasarladık. Daha önceki Merhaba Dünya komutunda ise program çalıştığı zaman kodu ekrana göstermemesi için yorum satırına aldık.

## 📍 Yorum Satırı
Kodlarınızı yazarken, yazılan ifade ve satırlarla ilgili yorumlar eklemek istiyorsanız // operatörünü kullanabilirsiniz. // ile başlayan satırlar, işlenecek kod olarak kabul edilmez, yani bu satırlara yazdığınız ifadelerin programın çalışmasına bir etkisi olmaz. Yorum satırları, yapılan işlerin neden ve nasıl yapıldığını açıklamak için kullanılır ve bu anlamda çok önemlidir. Daha sonra, yazılan kodların yazan kişi ya da bir başkası tarafından anlaşılmasına yardımcı olabilir.

// operatörüyle oluşturulan tek satırlık yorumların yanı sıra, istenirse birden çok yorum satırı, en başa /* ve en sonra */ operatörleri konularak belirtilebilir. Bu iki operatör arasındaki ifadelerin tümü birer yorum satırı olarak değerlendirilir.

## 📍 String Değişkenler
Stringler yazı metni depolamak için kullanılır. Bir değişken belirleyip ve ona değer atandıktan sonra string ifadesi oluşturabiliriz.
String oluşturmak için Değişken_türü değişken_adı; olarak kullanırız. 

![image](https://github.com/user-attachments/assets/ea2d0d80-ba40-4007-8485-269d96f8b8f4)

String ile örnek kullanım bu şekildedir. Değişkenin adını isimSoyisim olarak belirledik. Burada tanımlayacağımız değerler tırnak içinde yazılmalıdır. En sonda konsola yazdırmak için tanımladığımız değişkeni kullanıyoruz.

![image](https://github.com/user-attachments/assets/b567c241-a948-45f7-a44a-d3394f55cff0)

Direkt tek satır olarak da yazılabilir.

## 📍 Int Değişkenler
Uygulama geliştirirken en sık kullandığımız değişkenlerden biri "int" türüdür. Bunda en önemli etken tam sayı değer tutabilmesi ve veri aralığının geniş olmasıdır.
int türündeki değişkenler 32 bitlik işaretli veri depolarlar. Int değişkeni -2.147.483.648 ile 2.147.483.647 arasında değer depolayabilmektedir.

![image](https://github.com/user-attachments/assets/2da3a509-00a2-43a9-80a3-5b9591ec4ba1)

İlk konuda yer alan diğer örnekler için repomu inceleyebilirsiniz.

### ✅ Bu eğitimde yazdırma komutlarını, string ve int değişkenlerinin kullanımını öğrendim ve uyguladım.

## 🖥️ C# Eğitim Kampı Ders 2 - String, Int, Double, Char Değişkenler, Klavye Veri Girişleri, Dönüşümler
### 📆 Tarih: 1 Ekim 2024
### 📋 C# Konsol Uygulaması ile Yapılan Uygulamalar:

## 📍 Double Değişkenler
Çok sayıda ondalık basamak içeren reel sayılar için kullanılır. Double türündeki değişkenler 64 bitlik (8 byte) gerçek sayı depolarlar. Double değişkeni 1.7E +/- 308 (15 basamak) arasında değer depolayabilmektedir.

![image](https://github.com/user-attachments/assets/e09137a1-053b-4a85-b6e8-c8c98a6f1534)

Burada oluşturduğumuz ondalık sayı örneğinde ondalığı belirtmek için nokta kullanırız.

## 📍 Char Değişkenler
Char veri türü 16 bit uzunluğunda Unicode standartlarında karakterlerin karşılıklarını tutan veri tipidir. Her bir karakterin Unicode standartları çerçevesinde bir karşılığı bulunmaktadır ve char tipinde değişken değer atandıktan sonra bir karakteri temsil etmektedir. Char veri türü çift tırnak yerine tek tırnak kullanılır.

![image](https://github.com/user-attachments/assets/ced45bba-a994-4c7e-b5e0-1ec3710429d0)

## 📍 Klavyeden Veri Girişleri String Değişkenler (Console.ReadLine())
Bu metod ile kullanıcını klavyeden girdiği değer okunur. Okunan değer metin (string) tipinde bir ifade olarak geri döndürür. Döndürülen değer string olduğundan dönene değer string tipinde bir değişkene atanabilir.

![image](https://github.com/user-attachments/assets/36c766f6-5b7a-4a27-bdc3-0b37aee5a956)

Burada string tipinde isim ve soyisim ismiyle iki tane değişken atadık. Kullanıcıdan veri almak için bu kez Console.ReadLine metodunu kullandık. Programımızı çalıştırdıktan sonra ismimizi ve soyismimizi girdikten sonra ekran çıktısına Merhaba "İsim" "Soyisim" olarak karşımıza çıkacaktır.

## 📍 Klavyeden Tam Sayı Girişleri ve Dönüşümler
Burada direkt Console.ReadLine() metodunu kullanırsak hata verecektir. Dönen değer ile aritmetiksel işlem yapılacak ise tip dönüşümü yapılarak gerekli veri tipine (int, float) dönüştürülerek kullanılabilir. Int veri tipini dönüştürmek için int.Parse veya Convert.ToInt32 metodu kullanılabilir.

![image](https://github.com/user-attachments/assets/14dc3f82-0f03-4194-a755-da8d0f644856)

## 📍 Klavyeden Ondalık Sayı İşlemleri
![image](https://github.com/user-attachments/assets/a580e771-c82e-4e9b-94f0-61615c257c2d)
Bu örnekte ise kullanıcıdan alınan 3 tane sınav notunu ondalık sayı veya tam sayı olarak giriyoruz ve girdiğimiz bu değerleri 3'e bölüyoruz.

## 📍 Klavyeden Karakter Girişleri
![image](https://github.com/user-attachments/assets/189a7d65-22c9-4ed3-9286-205b14679af1)
Bu örnekte ise kullanıcıdan char tipinde bir tane harf giriyoruz, eğer bir harf dışında birden fazla harf ile girerken program hata verecektir. Burada herhangi bir harf girdiğimiz zaman ekran çıktısında o girdiğimiz harfi gösterecektir.

### ✅ Bu eğitimde Double - Char değişkenlerini, klavyeden String değişkenlerden veri girişlerini, tam sayı girişleri ve dönüşümleri, ondalıklı sayı işlemlerini ve karakter girişlerini öğrendim ve uyguladım.

## 🖥️ C# Eğitim Kampı Ders 3 - Karar Yapılar, If Else, Switch Case, Break
### 📆 Tarih: 5 Ekim 2024
### 📋 C# Konsol Uygulaması ile Yapılan Uygulamalar:

## 📍 If - Else
if else kodları C# yazılımda karar verme yapılarıdır. Programın akışı if else ile belirlenir. Belirli bir şarta bağlı olarak işlemler yapılacaksa if else kontrolleri kullanılır. Burada if ifadesi içerisinde şart belirtilir, eğer şart doğru ise if kod bloğunun içerisindeki komutlar çalıştırılır. Eğer şart doğru değilse else kod bloğunun içerisindeki komutlar çalıştırılır. Birden fazla şartın olduğu durumlarda iç içe if else yapıları kullanılır.

![image](https://github.com/user-attachments/assets/9882e6ab-ef0e-4d07-ae1c-5d0ac4c0362a)

Buradaki örnekte kullanıcıdan bir şifre girilmesi istenecektir. Şifre ise "abcd" olarak belirlenmiştir. Eğer girilen metin abcd ise if bloğun içindeki kod çalışacaktır. Yanlış girildiyse else bloğun içindeki kod çalışacaktır.

![image](https://github.com/user-attachments/assets/4f477dc0-e5aa-40ad-a9b3-6847cb4998a9)

Bu örnekte ise bu kez iki tane veri girişi uyguladık. İlk olarak başkenti, daha sonra ise ülkeyi kullanıcıdan aldık. Eğer girilen bilgilerin ikisi de doğruysa if bloğu, herhangi biri veya her ikisi de yanlışsa else bloğundaki kod çalışacaktır.

## 📍 Mod İşlemleri
Bir sayının başka bir sayıya bölümünden kalana mod denir. Mod alma işlemi de kalan bulma işlemi olarak ifade edilebilir. C# dilinde mod almak için % operatörü kullanılır.

![image](https://github.com/user-attachments/assets/a1b2a76e-f5de-4649-9d8d-dfdc4576ec46)

Burada number değişkenini 26 olarak atadık. Result değişkenine ise number değişkenini 26 olarak belirlediğimiz sayının 5 ile bölümünden kalan değerini belirledik.

![image](https://github.com/user-attachments/assets/e764a302-4256-4d1a-9155-199523c05634)

Bu örnekte ise hem mod operatörünü hem de karar yapılarını birlikte kullandık. Kullanıcıdan bir tane sayı girmesini istedik. Eğer girilen sayının 2 ile bölümünden kalan 0 ise sayı çift, kalan 1 ise tek olarak belirten bir tane örnek uyguladık.

## 📍 Char Değişkenler ile Karar Yapıları

![image](https://github.com/user-attachments/assets/0e7f6cc4-d24a-494e-8c87-7911b751f48a)

Bu örnekte ise char değişkenine göre kullanıcıdan veri alma işlemini yaptık. Burada küçük veya büyük harfe göre girme işlemini yaptık.

## 📍 Mantıksal Operatörler
Mantıksal Operatörler (Logical Operators)
Mantıksal operatörler tanımladığımız değişkenler ya da değerler arasında ki mantığı belirlemek için kullanılır. "true" ya da "false" değerleri üretirler.

"&&" operatörü:  Dizide işlem sırasında bir yanlış bile görürse sonucu "false" olarak çıkarılır.

"||" operatörü: İşlem sırasında bir tane doğru varsa sonuç "true" olarak çıkarılır.

"!" operatörü:  Değerlerin  sonucu ters çevirir.

## 📍 Switch-Case
Switch-Case deyimi if-else deyimleri gibi karar kontrol yapılarıdır. Switch-Case ifadeleri yapabileceğiniz her şeyi if-else blokları ile de yapabiliriz. Bir ifade üç veya daha fazla koşula göre ayrıştırıldığında genel olarak if-else'e alternatif olarak switch case kullanılır.
Bir koşul sağlandığında gerekli komutlar çalıştırıldıktan sonra break; ifadesi ile kontrol sonlandırılır. Bu demek oluyor ki her case ifadesi birbirinden farklı olmalıdır. Ve bir switch-case ifadesinde yalnızca bir case çalışmalıdır.

Kontrol edilen değişken hiçbir sabit ifadeye eşit değilse default kodunu kullanıyoruz. Bu durumda kod default kısmında belirtilen kod bloğunu çalıştırır.

Switch-Case ifadelerinde dikkat edilmesi gereken durumlar aşağıdaki gibidir:

Case ifadelerinin sırası önemli değildir.

Bilinenin aksine default ifadesi en son yazılmak zorunda değildir.

Default ifadesi zorunlu değildir. Yazılmasa da olur.

![image](https://github.com/user-attachments/assets/b02b6efa-c7b9-4cf0-aee4-c0b233b57997)

Bu örnekte ise kullanıcıdan 1-12 arasında bir tane sayı giriyoruz. Girilen sayıya göre o sayının kaçıncı ay olduğunu göstermektedir. Eğer bu sayıların dışında başka bir sayı girersek default bloğunda yer alan kod çalışacaktır.

### ✅ Bu eğitimde if - else yapılarını, switch case yapılarını ve break komutunu öğrendim ve uyguladım.

## 🖥️ C# Eğitim Kampı Ders 4 - Döngüler, For, While
### 📆 Tarih: 8 Ekim 2024
### 📋 C# Konsol Uygulaması ile Yapılan Uygulamalar:

## 📍 Döngüler
C#'da döngüler; Programı çalıştırdığımızda birden fazla olan komutları tek tek yazmak yerine döngü kavramlarını kullanabiliriz. Döngüler belirtilen komutların tekrar tekrar çalışmasını sağlar. Örneğin; 1'den 5'e kadar olan sayıları ekrana yazdırmayı denersek komutlarımız az olduğu için fazla zorlanmayız ancak 1'den 500 arası olan sayıları tek tek yazamayacağımız için döngü yapıları işimizi kolaylaştırır.

### 📍 For Döngüsü
For döngüsü, belirtilen komutların istenen koşullar sağlandığı sürece kodların tekrarlanmasını sağlar. En sık kullanılan döngü çeşididir. For döngüsünde ki başlangıç, bitiş ve artış (azalış) gibi değerleri istediğimiz kadar tekrarlamasını sağlayan yapıdır. Kullanımı şu şekildedir: for (x;y;z)
x: başlangıç
y: bitiş
z: artış-azalış

![image](https://github.com/user-attachments/assets/0bcb394c-887a-4660-aafb-7942b87b9dde)

Örneğimizde ilk olarak int değerinde i adında bir değişken ismi tanımladık. Daha sonra for döngüsü için parametrelerimizi yazdık. i değişkeninin başlangıç değerini 1 olarak ayarladık, bitiş değerini ise 5 olarak ayarladık, buradaki <= işareti ise bitiş değerinin de dahil olduğu anlamına gelir, arttırma işlemi olarak birer birer arttırdık. For döngüsünde parametreleri yazdıktan sonra noktalı virgül kullanmak yerine süslü parantezleri kullandık. Süslü parantezin içine ise ekrana "C# Eğitim Kampı" yazdırdık. Program çalıştırıldığı zaman ekrana 5 defa "C# Eğitim Kampı" yazdırılacaktır.

![image](https://github.com/user-attachments/assets/d68ca105-150c-4c6f-bd00-10c6ffa1dd9e)

Buradaki örnekte ise bu kez i değerini 3'ten başlatıp bitiş değerini 50 olarak ayarladık, ancak bu kez arttırma işlemini üçer üçer olarak belirledik. Daha sonra ekrana i değerini yazdırdığımız zaman program çıktısında üçer üçer yazdırılacaktır.

![image](https://github.com/user-attachments/assets/46dd4310-a028-445c-a290-dfe320f89299)

Bir diğer örneğimizde ise bu kez bitiş değerini kullanıcıdan almayı denedik. Değişken ismini tekrardan i olarak belirledik. i değeri başlangıçta 1 olarak belirledik, bitiş değeri ise kullanıcının girdiği değere göre belirledik ve artış değerini bir olarak belirledik. Programı çalıştırdıktan sonra kullanıcıdan bitiş değeri almamız istenecektir. Örneğin 5 girdiğimizde program çıktısında 5 defa "Yaşasın Cumhuriyet" yazdırılacaktır.

### 📍 For Döngüsü ile Karar Yapıları
For döngüsünde sadece yazdırma işlemlerinde değil, aynı zamanda karar yapılarında da kullanabiliriz.

![image](https://github.com/user-attachments/assets/c16ecc3d-6649-4aa4-b082-0f9f5e1702da)

Bu örneğimizde başlangıç değeri 1, bitiş değeri 100 ve artış değeri 1 olan parametreleri girdik, ancak burada bir şart belirledik. Eğer i değeri 5 ile bölümünden kalan 0 ise ekrana sadece 5 ile bölünenleri gösterecektir.

![image](https://github.com/user-attachments/assets/3420dd3f-4b9e-4b2e-ae82-312c1554e348)

Bu örneğimizde 1 ile 10 arasında olan sayıların toplamını veren bir program yazdık. İlk olarak toplamını vermesi için totalValue değişkenini 0 olarak belirledik. Daha sonra döngüde i değişkeninin değerlerini belirledik. Başlangıç değeri 1, bitiş değeri 10 ve artış değerini 1 olarak belirledik. Her bir döngü işleminde kendisinden bir önceki değeri toplayacaktır. Döngü işlemi bittikten sonra döngüden çıkacak ve toplam değerini ekrana yazdırılacaktır.

### 📍 While Döngüsü
While döngüsü, belirtilen komutların istenen koşullar sağlandığı sürece tekrar tekrar çalıştırılması için kullanılan döngü çeşididir. For döngüsünden farkı ise verilen şartı kontrol etmesidir. Genellikle dongünün kaç kez tekrarlanacağı bilinmediği durumlarda kullanılır. Döngünün çalışması için belirtilen koşulların "false" olması durumda döngü çalışmaz. Kullanımı şu şekildedir;
int x;
while(y)
{
işlemler
z
}
x: başlangıç
y: bitiş
z: artış-azalış

![image](https://github.com/user-attachments/assets/5e961a33-8d6e-4338-9578-fc87384731fa)

Burada ilk olarak int değerinde i değişkenini 1 olarak belirledik. Daha sonra while döngüsünün kullanımına geçtik. Burada i değerini 10'a kadar belirledik. While döngüsü kullanımından sonra süslü parantezin içerisine "Merhaba Döngüler" yazdırdık. İşlemler bittikten sonra burada artış miktarını belirlememiz gereklidir. Burada artış miktarını birer olarak belirledik. Program çalıştırıldığında ekrana 10 defa "Merhaba Döngüler" yazacaktır.

![image](https://github.com/user-attachments/assets/44c23d8d-00d9-479d-8e1d-949a40e7a8e2)

Bu örneğimizde de karar yapılarını kullandık. 1'den 10'a kadar olan değerin 3 ile tam bölünebilenleri ekrana yazdırdık.

### 📍 Örnek Sınav Sorusu

![image](https://github.com/user-attachments/assets/8eb2ba52-639a-4669-9f8b-efcfe1eaa9f0)

Bu örneğimizde daha önceki konularda yer alan bilgilerle öğrendiklerimizi pekiştirmek için bir tane uygulama yaptık. Uygulamamızda 3 basamaklı bir sayının basamaklarını ayırmayı ve basamak değerleri toplamını hesaplayan bir uygulama yaptık.
Örneğimizde ilk olarak kullanıcıdan bir sayı girme işlemini yaptık. Sayı değişkenini number olarak belirledik.
Basamaklarını ayırabilmek için birler, onlar ve yüzler değerlerini almamız gerekmektedir. Bunun için değişken isimlerini de ingilizce olarak belirledik.
Toplam değerini hesaplarken hata çıkmaması için toplam değişkenini başlangıçta 0 olarak belirledik.

Basamaklarını ayırabilmek için birler basamağını sayının mod 10'una eşitledik.
Onlar basamağını ise sayının önce mod 100'ünü daha sonra 10'a bölme işlemini yaptık.
Yüzler basamağını ise sayının 100'e bölme işlemini yaptık. (Örnek olarak 456 sayısının 100'e bölümünden kalan 4.56 ancak int değeri tam sayı değerini tuttuğu için 4 olarak alacaktır.)
Daha sonra konsola tek tek değerlerini yazdırdık ve basamak değerlerini toplattırıp ekrana yazdırdık.

### ✅ Bu eğitimde for, while döngülerini ve örnek sınav uygulamasının adımlarını öğrendim ve uyguladım.

## 🖥️ C# Eğitim Kampı Ders 5 - Döngülerle Pratik Uygulamalar, Yıldızlarla Şekil Çizme
### 📆 Tarih: 8 Ekim 2024
### 📋 C# Konsol Uygulaması ile Yapılan Uygulamalar:

Bu eğitimde döngülerden oluşan 10'a yakın örnek uygulamalar yaptım.

![image](https://github.com/user-attachments/assets/72ffef9e-0acc-4da8-a52a-5685528273ad)

Bu örnekte 1'den 10'a kadar olan alt alta 10 tane yıldız oluşturma uygulaması yaptım. Eğer yan yana 10 tane yıldız oluşturmak istiyorsak Console.WriteLine() kısmını Console.Write() olarak değiştirmemiz yeterli olacaktır.

![image](https://github.com/user-attachments/assets/d0591be5-e133-4072-a509-889713093268)

Bu örnekte bir tane dik üçgen uygulaması oluşturdum. Burada ilk for döngüsünde 1'den 5'e kadar olan parametreyi belirledik. Ancak bizim burada bir tane daha döngü oluşturmamız gerekecektir. Bu kez iç içe bir tane daha döngü oluşturduk ve değişken ismini j olarak belirledik. j değeri 1'den başlayıp i değerine kadar olan parametreyi belirledik. Yazdırmak için Console.Write() metodunu kullanarak * şeklini yazdırdık. İkinci döngüden çıkarak bu kez boş bir tane Console.WriteLine() metodu yazarak alta boşluk bırakmasını sağladık.

Kalan örneklere bakmak için repomu inceleyebilirsiniz.

### ✅ Bu eğitimde for döngüleri ile alt alta - yan yana 10 tane yıldız oluşturmayı, dik üçgen - ters dik üçgen oluşturmayı, baklava dilimi oluşturmayı, piramit oluşturmayı öğrendim ve uyguladım.

## 🖥️ C# Eğitim Kampı Ders 6 - Diziler
### 📆 Tarih: 12 Ekim 2024
### 📋 C# Konsol Uygulaması ile Yapılan Uygulamalar:

## 📍 Diziler (Arrays)
Diziler, farklı değerler için ayrı değişkenler atamak yerine birden çok değeri aynı değişken türünde depolamak için kullanılır. Dizi belirtmek için değişken türünü köşeli pantezlerle tanımlarız. Diziler 0'dan başlar. String ifadeler de dizi belirtir.

Örnek kullanımı şu şekildedir: DeğişkenTürü [] DiziAdı = new DeğişkenTürü[ElemanSayısı];

![image](https://github.com/user-attachments/assets/ec6ef51e-81f9-4e68-9cf5-e1a165323ea4)

Burada colors adında bir tane dizi tanımladık ve dizi elemanını 4 olarak belirledik. Dizi elemanı 0'dan başladığı için 0'ıncı değerini "Kırmızı", 1'inci değerini "Sarı", 2'nci değerini "Beyaz" ve 3'üncü değerini "Mavi" olarak belirledik. Eğer burada colors[4] olarak herhangi bir değer tanımlasaydık program hata verecekti, çünkü dizinin eleman değerini aşmış olacaktı. Ekrana herhangi bir değerini yazdırabiliriz. Burada "Beyaz" elemanını yazdırdık.

![image](https://github.com/user-attachments/assets/b794acc5-ef51-4eee-8bd1-189253b5372d)

Burada ise int tipinde bir dizi tanımladık. Elemanını 10 olarak belirledik. Burada 10 tane eleman oluşturmak zorunda değiliz. Birkaç eleman oluşturup bu değerlerden birini veya birkaçını yazdırabiliriz.

![image](https://github.com/user-attachments/assets/8993d0bf-852f-4354-b272-fa4ce2fdcb6e)

Dizilerin bir diğer kullanım şekli ise direkt değerini yazmak yerine elemanların isimlerini de girebiliriz. Burada cities[2] değerini çağırdığımız zaman 3. sıradaki elemanı yazdıracaktır, bunun nedeni dizi değerinin 0'dan başlamasıdır.

## 📍 Dizideki Tüm Elemanları Listeleme

![image](https://github.com/user-attachments/assets/a6308893-e0a0-4809-8117-64096cb60283)

Bu örnekte colors adında bir tane değişken tanımlayıp içerisine renkleri belirledim. Daha sonra dizideki tüm elemanlarını listelemek için döngünün içine girerek başlangıç değerini 0'dan başlatıp bitiş değerini renklerin tamamını listelemek için colors değişkeninden sonra Length fonksiyonunu kullandım. Programımızı çalıştırdıktan sonra dizi içerisinde yer alan tüm renkler listelenecektir.

![image](https://github.com/user-attachments/assets/84bd2c64-9b7b-4441-ae86-2d7bbf51319d)

Bu örneğimizde ise numbers değişkeninde yer alan elemanların sadece 3 ile bölünenleri listeleyen bir program yazdım. Bunun dışında char fonksiyonundan da elemanlar listelenebilir.

![image](https://github.com/user-attachments/assets/cd131911-a835-4aef-85b6-ff42e659f65b)

Bu örneğimizde ise direkt persons listesinde yer alan elemanların kaç tane olduğunu gösteren bir program yazdım.

![image](https://github.com/user-attachments/assets/0699a6e9-97ee-40a1-914b-71c4670113ad)

### 📍 Array.Sort
Diziler üzerinden sıralama işlemi yapar. Eğer string bir dizi ise alfabetik olarak olarak A'dan Z'ye sıralar. Eğer numeric bir dizi ise dizi elemanlarını küçükten büyüğe sıralar. Örnek kullanım aşağıda verilmiştir.

![image](https://github.com/user-attachments/assets/64dcb7ac-cc72-4507-8b3e-2f8ceb3aa7f2)

Bu örneğimizde ise listede yer alan sayıları küçükten büyüğe sıralamak için Array.Sort metodunu uyguladım.

### 📍 Array.Reverse
Dizinin ortasını belirleyerek elemanlarını aynalar gibi düşünebilirsiniz. Yani dizinin ilk elemanı ile son elemanını yer değiştirir. Örnek kullanım aşağıda verilmiştir.

![image](https://github.com/user-attachments/assets/c8647d47-c2a6-4500-9ed1-757f0f882dca)

Bu örneğimizde listede yer alan sayıları sondan başa olan değerleri yazdırmaktadır.

## 📍 Dizi Metotlar
### 📍 Array.IndexOf
Verilen dizinin verilen elemanının indexini getirir. Eğer dizi içerisinde elemanı bulamazsa -1 döner. Örnek kullanım aşağıda verilmiştir.

![image](https://github.com/user-attachments/assets/611ac0e5-138f-4e44-a1a0-2ac491639811)

Bu örneğimizde customers listesinde yer alan kişiler listelenmiştir. Burada Array.IndexOf metodu ile listede yer alan kişilerden birinin ismini giriyoruz. Eğer yazdığımız isim listede yer alıyorsa dizinin indeksine göre değer dönderecektir. Örneğin "merve" değerini yazdığımız zaman listede var ise "merve" ismi 3. indekste yer aldığı için program çıktısı 3 olarak gösterecektir. Eğer listede ismi olmayan bir değer girersek -1 olarak dönderecektir.

### 📍 Max Min Metodu
Max: dizideki en büyük elemanı döndürür.

Min: en küçük değeri döndürür.

![image](https://github.com/user-attachments/assets/d86f6851-7f98-49e4-8b24-e4e299819f86)

Bu örneğimizde listede yer alan sayılardan en büyük ve en küçük elemanları bulmak için Max ve Min metodlarını kullandım.

## 📍Kullanıcıdan Değer Alma
Bilgilerimizi pekiştirerek bir tane örnek yapalım.

![image](https://github.com/user-attachments/assets/eaa87525-46d4-4b3d-822f-82adddc478a7)

Bu örneğimizde ilk olarak string türünde bir tane dizi oluşturalım ve ismini cities olarak belirleyelim. Burada 5 tane değer oluşturalım.
Daha sonra döngü işlemlerimizi yapıyoruz. Burada i değeri 0'dan başlatıp cities değişkeninin uzunluğuna kadar olan değerlerimizi yazıyoruz.
Şehir ismini kullanıcıdan almak için cities[i] değişkenine aktarıyoruz.
Şehirleri yazdıktan sonra bir tane Console.WriteLine() metodu ile bir boşluk bırakıyoruz.
Bu kez ekranda yazdıklarımızı görüntülemek için yukarda yer alan döngüyü tekrar yazıyoruz ve en sonunda yazdırma işlemini uyguluyoruz.

### ✅ Bu eğitimde dizilerin tanımını ve kullanımını, dizideki tüm elemanlarını listelemeyi ve sıralamayı, dizi metotlarını ve dizilerle kullanıcıdan değer almayı öğrendim ve uyguladım.

## 🖥️ C# Eğitim Kampı Ders 7 - Foreach Döngüsü
### 📆 Tarih: 15 Ekim 2024
### 📋 C# Konsol Uygulaması ile Yapılan Uygulamalar:

## 📍 Foreach Döngüsü
for döngüsü gibi yaygın kullanılan bir diğer döngü de foreach döngüsüdür. foreach, dizi (array) ve koleksiyon (collection) tabanlı nesnelerin elemanları üzerinden ilerleyen, iterasyon gerçekleştirerek bu elemanlara erişip iş katmanınızı oluşturabileceğiniz bir döngüdür. Bu döngünün genel kullanımı aşağıdaki gibidir:

foreach (tip değişken in koleksiyon)

{

yapılacak işler

}

değişken: foreach döngüsü içinde iterasyon için kullanılacak değeri temsil eder.

koleksiyon: Dizi, ArrayList, Generic List, Dictionary gibi aynı tipleri barındıran liste yapılarıdır.

tip: Her döngüde kullanılacak ve içinde farklı değerlerin bulunacağı değişkenin string, int, byte gibi ilgili tipinin belirtildiği alan.

![image](https://github.com/user-attachments/assets/f9b93118-c1d5-4525-a547-60846605b297)

Burada string türünden bir tane dizi oluşturduk ve ismini cities olarak belirledik. Yazdığımız şehirleri listelemek için bu kez foreach döngüsü kullandık. Burada x adında rastgele bir değişken ismi belirledik ve değerleri cities koleksiyonundan aldık. Yazdırmak için en son tanımlamış olduğumuz x değişkenini yazdırıyoruz.
Aynı zamanda int değişkeni ile foreach döngüsü oluşturulabilir, şartlı ifadeler de kullanılabilir.

Bu dersimizde ise bir tane Örnek Sınav Sistemi Uygulaması oluşturdum. Örneği incelemek için repomu inceleyebilirsiniz.

### ✅ Bu eğitimde foreach döngüsünün tanımını ve kullanımını ve bir tane Örnek Sınav Sistemi Uygulaması ile öğrencilerin sayısını kullanıcıdan almayı, isimlerini ve not ortalamalarını saklayacak dizilerin kullanımını ve her bir öğrenci için 3 tane sınav notu girişinin nasıl yapıldığını öğrendim ve uyguladım.

## 🖥️ C# Eğitim Kampı Ders 8 - Metotlar
### 📆 Tarih: 19 Ekim 2024
### 📋 C# Konsol Uygulaması ile Yapılan Uygulamalar:

## 📍 Metotlar
Metotlar, belirli bir işlevi yerine getirmek için hazırlanmış belirli bir kod bloğunu bir isim altında toplayıp kodu çalıştırmak istediğimiz yerde vermiş olduğumuz isimle çağırıp içerisindeki kodun yeniden kullanılmasına izin veren programlama yapılarıdır.

### 📍 Parametresiz Metotlar
C# parametresiz metotlar tanımlanırken herhangi bir parametre değerine bağlı olmadan içerisinde bulunan kod parçalarının çalıştırılmasına imkan veren metot türleridir.

