#  <img height="50" src="https://user-images.githubusercontent.com/25181517/121405384-444d7300-c95d-11eb-959f-913020d3bf90.png"> EĞİTİM KAMPI
👋 Merhabalar, oluşturmuş olduğum bu repo, Murat Yücedağ hocamızın YouTube üzerinden hazırlamış olduğu C# Eğitim Kampı süresince tamamlamış olduğum projeleri içermektedir. Bu eğitimde C# Konsol Uygulaması'ndan "Merhaba Dünya" ile başlayıp en son yapılan uygulamaya kadar detaylar anlatılmaktadır.

## 🖥️ C# Eğitim Kampı Ders 1 - Giriş, Merhaba Dünya, Yazdırma Komutları, String ve Int Değişkenler
### 📆 Tarih: 28 Eylül 2024
### 📋 C# Konsol Uygulamasından Yapılan Uygulamalar:

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

### Console.WriteLine ile Console.Write arasındaki fark nedir?
WriteLine() metodu, Console ekranına çıktı vermek için kullanılan metoddur.
Write() metodundan tek farkı çıktı verdikten sonra alt satıra iner.

### C# ile Region Kullanımı 
Region, kodların okunurluğunu arttırmak ve daha düzenli bir yapıda saklamak için kullanılmaktadır. Region eklenmek istenilen kodun üst tarafında #region, alt tarafında ise #endregion ifadesi bulunmaktadır. Kısayol için Ctrl + k + s ile region oluşturabilir.

![image](https://github.com/user-attachments/assets/eefcb3ff-9190-4375-b6a5-3e8e5d55e309)

Projeyi çalıştırmak için yukarıda yer alan Start tuşuna veya kısayoldan F5 ile çalıştırabiliriz. Ancak program çalıştıktan sonra hemen kapanacaktır. Bunun için ek olarak en alt satıra Console.Read(); komutunu ekliyoruz.

### Console.Read() nedir?
Console.Read(): Bu metod tek bir karakter okur. Geriye okunan karakterin ascii karşılığı olan bir sayı döndürür. Döndürülen değer sayı olduğundan değer sayı veri tipinde bir değişkene aktarılabilir.

![image](https://github.com/user-attachments/assets/b1f6c9d4-107e-436a-82ea-0e6bac47620f)

Programımızı çalıştırdıktan sonra karşımıza bu şekilde çıkacaktır.

![image](https://github.com/user-attachments/assets/d32f63db-0eb9-4d13-994c-2b00737d7be6)

Burada sadece Console.WriteLine komutunu kullanarak Yemek Kategorileri adında mini bir program tasarladık. Daha önceki Merhaba Dünya komutunda ise program çalıştığı zaman kodu ekrana göstermemesi için yorum satırına aldık.

### Yorum Satırı
Kodlarınızı yazarken, yazılan ifade ve satırlarla ilgili yorumlar eklemek istiyorsanız // operatörünü kullanabilirsiniz. // ile başlayan satırlar, işlenecek kod olarak kabul edilmez, yani bu satırlara yazdığınız ifadelerin programın çalışmasına bir etkisi olmaz. Yorum satırları, yapılan işlerin neden ve nasıl yapıldığını açıklamak için kullanılır ve bu anlamda çok önemlidir. Daha sonra, yazılan kodların yazan kişi ya da bir başkası tarafından anlaşılmasına yardımcı olabilir.

// operatörüyle oluşturulan tek satırlık yorumların yanı sıra, istenirse birden çok yorum satırı, en başa /* ve en sonra */ operatörleri konularak belirtilebilir. Bu iki operatör arasındaki ifadelerin tümü birer yorum satırı olarak değerlendirilir.

## String Değişkenler
Stringler yazı metni depolamak için kullanılır. Bir değişken belirleyip ve ona değer atandıktan sonra string ifadesi oluşturabiliriz.
String oluşturmak için Değişken_türü değişken_adı; olarak kullanırız. 

![image](https://github.com/user-attachments/assets/ea2d0d80-ba40-4007-8485-269d96f8b8f4)

String ile örnek kullanım bu şekildedir. Değişkenin adını isimSoyisim olarak belirledik. Burada tanımlayacağımız değerler tırnak içinde yazılmalıdır. En sonda konsola yazdırmak için tanımladığımız değişkeni kullanıyoruz.

![image](https://github.com/user-attachments/assets/b567c241-a948-45f7-a44a-d3394f55cff0)

Direkt tek satır olarak da yazılabilir.

## Int Değişkenler
Uygulama geliştirirken en sık kullandığımız değişkenlerden biri "int" türüdür. Bunda en önemli etken tam sayı değer tutabilmesi ve veri aralığının geniş olmasıdır.
int türündeki değişkenler 32 bitlik işaretli veri depolarlar. Int değişkeni -2.147.483.648 ile 2.147.483.647 arasında değer depolayabilmektedir.

![image](https://github.com/user-attachments/assets/2da3a509-00a2-43a9-80a3-5b9591ec4ba1)

İlk konuda yer alan diğer örnekler için repomu inceleyebilirsiniz.


## 🖥️ C# Eğitim Kampı Ders 2 - String, Int, Double, Char Değişkenler, Klavye Veri Girişleri, Dönüşümler
### 📆 Tarih: 1 Ekim 2024
### 📋 C# Konsol Uygulamasından Yapılan Uygulamalar:

Bu eğitimde Double - Char değişkenlerini, klavyeden String değişkenlerden veri girişlerini, tam sayı girişleri ve dönüşümleri, ondalıklı sayı işlemlerini ve karakter girişlerini öğrendim ve uyguladım.

## Double Değişkenler
Çok sayıda ondalık basamak içeren reel sayılar için kullanılır. Double türündeki değişkenler 64 bitlik (8 byte) gerçek sayı depolarlar. Double değişkeni 1.7E +/- 308 (15 basamak) arasında değer depolayabilmektedir.

![image](https://github.com/user-attachments/assets/e09137a1-053b-4a85-b6e8-c8c98a6f1534)

Burada oluşturduğumuz ondalık sayı örneğinde ondalığı belirtmek için nokta kullanırız.

## Char Değişkenler
Char veri türü 16 bit uzunluğunda Unicode standartlarında karakterlerin karşılıklarını tutan veri tipidir. Her bir karakterin Unicode standartları çerçevesinde bir karşılığı bulunmaktadır ve char tipinde değişken değer atandıktan sonra bir karakteri temsil etmektedir. Char veri türü çift tırnak yerine tek tırnak kullanılır.

![image](https://github.com/user-attachments/assets/ced45bba-a994-4c7e-b5e0-1ec3710429d0)

## Klavyeden Veri Girişleri String Değişkenler (Console.ReadLine())
Bu metod ile kullanıcını klavyeden girdiği değer okunur. Okunan değer metin (string) tipinde bir ifade olarak geri döndürür. Döndürülen değer string olduğundan dönene değer string tipinde bir değişkene atanabilir.

![image](https://github.com/user-attachments/assets/36c766f6-5b7a-4a27-bdc3-0b37aee5a956)

Burada string tipinde isim ve soyisim ismiyle iki tane değişken atadık. Kullanıcıdan veri almak için bu kez Console.ReadLine metodunu kullandık. Programımızı çalıştırdıktan sonra ismimizi ve soyismimizi girdikten sonra ekran çıktısına Merhaba "İsim" "Soyisim" olarak karşımıza çıkacaktır.

## Klavyeden Tam Sayı Girişleri ve Dönüşümler
Burada direkt Console.ReadLine() metodunu kullanırsak hata verecektir. Dönen değer ile aritmetiksel işlem yapılacak ise tip dönüşümü yapılarak gerekli veri tipine (int, float) dönüştürülerek kullanılabilir. Int veri tipini dönüştürmek için int.Parse veya Convert.ToInt32 metodu kullanılabilir.

![image](https://github.com/user-attachments/assets/14dc3f82-0f03-4194-a755-da8d0f644856)

## Klavyeden Ondalık Sayı İşlemleri
![image](https://github.com/user-attachments/assets/a580e771-c82e-4e9b-94f0-61615c257c2d)
Bu örnekte ise kullanıcıdan alınan 3 tane sınav notunu ondalık sayı veya tam sayı olarak giriyoruz ve girdiğimiz bu değerleri 3'e bölüyoruz.

## Klavyeden Karakter Girişleri
![image](https://github.com/user-attachments/assets/189a7d65-22c9-4ed3-9286-205b14679af1)
Bu örnekte ise kullanıcıdan char tipinde bir tane harf giriyoruz, eğer bir harf dışında birden fazla harf ile girerken program hata verecektir. Burada herhangi bir harf girdiğimiz zaman ekran çıktısında o girdiğimiz harfi gösterecektir.

## 🖥️ C# Eğitim Kampı Ders 3 - Karar Yapılar, If Else, Switch Case, Break
### 📆 Tarih: 5 Ekim 2024
### 📋 C# Konsol Uygulamasından Yapılan Uygulamalar:

Bu eğitimde if - else yapılarını, switch case yapılarını ve break komutunu öğrendim ve uyguladım.

## If - Else
if else kodları C# yazılımda karar verme yapılarıdır. Programın akışı if else ile belirlenir. Belirli bir şarta bağlı olarak işlemler yapılacaksa if else kontrolleri kullanılır. Burada if ifadesi içerisinde şart belirtilir, eğer şart doğru ise if kod bloğunun içerisindeki komutlar çalıştırılır. Eğer şart doğru değilse else kod bloğunun içerisindeki komutlar çalıştırılır. Birden fazla şartın olduğu durumlarda iç içe if else yapıları kullanılır.

![image](https://github.com/user-attachments/assets/9882e6ab-ef0e-4d07-ae1c-5d0ac4c0362a)

Buradaki örnekte kullanıcıdan bir şifre girilmesi istenecektir. Şifre ise "abcd" olarak belirlenmiştir. Eğer girilen metin abcd ise if bloğun içindeki kod çalışacaktır. Yanlış girildiyse else bloğun içindeki kod çalışacaktır.

![image](https://github.com/user-attachments/assets/4f477dc0-e5aa-40ad-a9b3-6847cb4998a9)

Bu örnekte ise bu kez iki tane veri girişi uyguladık. İlk olarak başkenti, daha sonra ise ülkeyi kullanıcıdan aldık. Eğer girilen bilgilerin ikisi de doğruysa if bloğu, herhangi biri veya her ikisi de yanlışsa else bloğundaki kod çalışacaktır.

## Mod İşlemleri
Bir sayının başka bir sayıya bölümünden kalana mod denir. Mod alma işlemi de kalan bulma işlemi olarak ifade edilebilir. C# dilinde mod almak için % operatörü kullanılır.

![image](https://github.com/user-attachments/assets/a1b2a76e-f5de-4649-9d8d-dfdc4576ec46)

Burada number değişkenini 26 olarak atadık. Result değişkenine ise number değişkenini 26 olarak belirlediğimiz sayının 5 ile bölümünden kalan değerini belirledik.

![image](https://github.com/user-attachments/assets/e764a302-4256-4d1a-9155-199523c05634)

Bu örnekte ise hem mod operatörünü hem de karar yapılarını birlikte kullandık. Kullanıcıdan bir tane sayı girmesini istedik. Eğer girilen sayının 2 ile bölümünden kalan 0 ise sayı çift, kalan 1 ise tek olarak belirten bir tane örnek uyguladık.

## Char Değişkenler ile Karar Yapıları

![image](https://github.com/user-attachments/assets/0e7f6cc4-d24a-494e-8c87-7911b751f48a)

Bu örnekte ise char değişkenine göre kullanıcıdan veri alma işlemini yaptık. Burada küçük veya büyük harfe göre girme işlemini yaptık.

## Mantıksal Operatörler
Mantıksal Operatörler (Logical Operators)
Mantıksal operatörler tanımladığımız değişkenler ya da değerler arasında ki mantığı belirlemek için kullanılır. "true" ya da "false" değerleri üretirler.

"&&" operatörü:  Dizide işlem sırasında bir yanlış bile görürse sonucu "false" olarak çıkarılır.

"||" operatörü: İşlem sırasında bir tane doğru varsa sonuç "true" olarak çıkarılır.

"!" operatörü:  Değerlerin  sonucu ters çevirir.

## Switch-Case
Switch-Case deyimi if-else deyimleri gibi karar kontrol yapılarıdır. Switch-Case ifadeleri yapabileceğiniz her şeyi if-else blokları ile de yapabiliriz. Bir ifade üç veya daha fazla koşula göre ayrıştırıldığında genel olarak if-else'e alternatif olarak switch case kullanılır.
Bir koşul sağlandığında gerekli komutlar çalıştırıldıktan sonra break; ifadesi ile kontrol sonlandırılır. Bu demek oluyor ki her case ifadesi birbirinden farklı olmalıdır. Ve bir switch-case ifadesinde yalnızca bir case çalışmalıdır.

Kontrol edilen değişken hiçbir sabit ifadeye eşit değilse default kodunu kullanıyoruz. Bu durumda kod default kısmında belirtilen kod bloğunu çalıştırır.

Switch-Case ifadelerinde dikkat edilmesi gereken durumlar aşağıdaki gibidir:

Case ifadelerinin sırası önemli değildir.

Bilinenin aksine default ifadesi en son yazılmak zorunda değildir.

Default ifadesi zorunlu değildir. Yazılmasa da olur.

![image](https://github.com/user-attachments/assets/b02b6efa-c7b9-4cf0-aee4-c0b233b57997)

Bu örnekte ise kullanıcıdan 1-12 arasında bir tane sayı giriyoruz. Girilen sayıya göre o sayının kaçıncı ay olduğunu göstermektedir. Eğer bu sayıların dışında başka bir sayı girersek default bloğunda yer alan kod çalışacaktır.
