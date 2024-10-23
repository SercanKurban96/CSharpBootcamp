# 👋 C# EĞİTİM KAMPI
Merhabalar, oluşturmuş olduğum bu repo, Murat Yücedağ hocamızın YouTube üzerinden hazırlamış olduğu C# Eğitim Kampı süresince tamamlamış olduğum projeleri içermektedir. Bu eğitimde C# Konsol Uygulaması'ndan "Merhaba Dünya" ile başlayıp en son yapılan uygulamaya kadar detaylar anlatılmaktadır.

## C# Eğitim Kampı Ders 1 - Giriş, Merhaba Dünya, Yazdırma Komutları, String ve Int Değişkenler
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

