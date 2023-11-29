# Mulakat-Sorulari

<details>

<summary>Senin sorman gereken sorular ?</summary>

1. Projenin amaci ve kapsami nedir?
2. Projede kullanilan teknolojiler nelerdir?
3. Proje ne zaman basladi ve ne zaman tamamlanmasi bekleniyor?
4. Proje ekibi ne kadar buyuk ve hangi rolleri iceriyordu?
5. Java versiyonu nedir?
6. Spring boot versiyonu nedir?
7. JPA , jdbc ne kullaniyorsunuz?
8. Github, gitlab vb ne kullaniyorsunuz?

</details>

---

### *Java ve OOP*

<details>

<summary>JDK ve JRE arasındaki farklar nelerdir?</summary>

JRE, Java runtime editioni bir java uygulamasını çalıştırmak için gerekli olan java komponentlerini ve kütüphanelerini
içeren içersinde JVM de kurulu olan programa denir.

JDK, Java ile yazılım geliştirmek için ihtiyaç duyulan yazılım kitlerini içinde bulundurur. .java uzantılı dosyaların
compile edilip .class uzantılı ara dosyaların oluşmasına olanak sağlar. JDK, içerisinde JVM,JRE ve Java Compiler'ını
bulundurur.

</details>

<details>

<summary>Super ve this kavramları nedir?</summary>

1. **`super`**: Bir alt sınıfta üst sınıfın metotlarını veya değişkenlerini kullanmak için kullanılan bir referansdır.
   Alt sınıfın kendi metotlarında, üst sınıfın metotlarına erişmek için **`super`** anahtar kelimesi kullanılabilir.
   Aynı şekilde, alt sınıfta üst sınıfın değişkenlerini kullanmak için de **`super`** anahtar kelimesi kullanılır.
2. **`this`**: Bir sınıfın kendi nesnesine erişmek için kullanılan bir referanstır. Özellikle, bir sınıfta tanımlı olan
   değişkenlerle aynı isimli parametrelerin kullanıldığı durumlarda, **`this`** anahtar kelimesi kullanılarak sınıfın
   kendi değişkeni ifade edilir.

</details>

<details>

<summary>Stateful vs stateless nedir?</summary>

Stateful yapı, bir programın durum bilgisini saklayan ve bu duruma göre işlem yapan bir yapıdır. Stateful yapılar,
geçmiş işlemlere bağlı olarak çalışan uygulamalar için kullanılır

ornek/ Bir anne alisveris sepetindeki tum urunleri ve evdeki tum urunleri bilir

Stateless yapı ise, her işlemi bağımsız olarak ele alan ve önceki işlemlerle bir ilişkisi olmayan bir yapıdır. Stateless
yapılar, her işlemi bağımsız olarak ele alan ve hızlı yanıt veren uygulamalar için tercih edilir.

ornek/ Bir cocuk sadece canin istedigi urunleri alir

</details>

<details>

<summary>equals() ve == arasındaki fark?</summary>

equals() bir methoddur ve değişkenler arasındaki değer kontrolünü yapar.

\== ifadesi ise değişkenlerin referanslarını karşılaştırır.

</details>

<details>

<summary>Abstraction Vs Interface fark?</summary>

Abstraction tum insanlarin kolu ve bacagi olmasi

Interface bazi insanlarin dovmeli bazilarin dovmesiz kollari olmasi gibi

! 1 abstraction olur n tane interface olur

</details>

<details>

<summary>Public, Private, Default and Protected ?</summary>

* `public`: Her yerden erişilebilir.
* `private`: Sadece ait olduğu sınıf içinden erişilebilir.
* `default` (package-private): Aynı paketten erişilebilir, farklı paketlerden erişilemez.
* `protected`: Ait olduğu sınıfın alt sınıfları ve aynı paket içindeki sınıflardan erişilebilir.

</details>

<details>

<summary><strong>Object oriented prensipleri nelerdir?</strong></summary>

1. Encapsulation (Kapsülleme): Verilerin ve işlevlerin bir arada tutulması ve gizlenmesi anlamına gelir. Bu prensip,
   verilerin ve işlevlerin nesnelerle ilgili olduğu ve diğer nesneler tarafından doğrudan erişilemez olduğu anlamına
   gelir. Bu, güvenli bir kod yazmak için önemlidir. or/ Araba sınıfı, verileri (marka, model, renk, hız vb.) ve
   fonksiyonları (hareket ettirmek, durdurmak, hızını artırmak veya azaltmak) bir arada tutar ve gizler. Bu şekilde,
   başka sınıfların doğrudan arabayla ilgili verilere veya fonksiyonlara erişmeleri engellenir.
2. Inheritance (Kalıtım): Bir sınıfın özelliklerinin, başka bir sınıfa aktarılması anlamına gelir. Kalıtım, kodun
   yeniden kullanılmasına olanak tanır ve sınıflar arasındaki ilişkileri belirler. Alt sınıflar, üst sınıfların
   özelliklerine sahip olabilirler. or/ Araba sınıfının, bir sedan sınıfı veya bir SUV sınıfı gibi alt sınıfları
   olabilir. Bu alt sınıflar, arabaya özgü özelliklerin yanı sıra kendi özelliklerine de sahip olabilirler.
3. Polymorphism (Çok biçimlilik): Çok biçimlilik, nesnelerin farklı biçimlerde davranabilmesi anlamına gelir. Aynı
   yöntem adı, farklı sınıflarda farklı şekillerde uygulanabilir. or/ Araba sınıfı, bir araba hareketi fonksiyonu
   içerebilir. Sedan sınıfı veya SUV sınıfı, arabayı farklı şekillerde hareket ettirebilir. Örneğin, sedan araba normal
   bir şekilde hareket edebilirken, SUV araba off-road koşullarına uygun olarak hareket edebilir.
4. Abstraction (Soyutlama): Karmaşık bir sistemdeki detayların gizlenmesi anlamına gelir. Bu prensip, sınıfların
   arasındaki bağımlılığı azaltır ve kodun daha anlaşılır olmasını sağlar. or/ Araba sınıfı, sadece arabayla ilgili
   özellikleri ve fonksiyonları içerir. Bu, başka sınıfların arabaya bağımlılığını azaltır ve kodun daha anlaşılır
   olmasını sağlar.

</details>

<details>

<summary>Method Overloading ve Method Overriding nedir?</summary>

Method Overloading: Aynı isimli farklı parametrelerle ayrı ayrı tanımlanan birden fazla metodun kullanılmasıdır. Bu
durumda, aynı isimli farklı metotlar, farklı parametreler alarak aynı sınıf içerisinde tanımlanabilirler. Bu sayede,
metot isimleri aynı kalır ve farklı amaçlar için kullanılabilirler.

Örneğin:

```java
public class HesapMakinesi {

    public int topla(int sayi1, int sayi2) {
        return sayi1 + sayi2;
    }

    public double topla(double sayi1, double sayi2) {
        return sayi1 + sayi2;
    }

    public int topla(int sayi1, int sayi2, int sayi3) {
        return sayi1 + sayi2 + sayi3;
    }
}

```

Method Overriding: Bir sınıfta tanımlanan bir metot, alt sınıflar tarafından aynı isim ve parametrelerle yeniden
tanımlanırsa, bu durumda Method Overriding gerçekleşir. Bu sayede, alt sınıfın aynı isimli metodunu çağırdığımızda, üst
sınıfın değil, alt sınıfın metodunun çalıştırılması sağlanır.

Örneğin:

```java
public class Sekil {
    protected double alan;

    public void hesaplaAlan() {
        System.out.println("Alan hesaplanıyor.");
    }
}

```

```java
public class Daire extends Sekil {
    private double yariCap;

    public Daire(double yariCap) {
        this.yariCap = yariCap;
    }

    @Override
    public void hesaplaAlan() {
        alan = Math.PI * yariCap * yariCap;
        System.out.println("Dairenin alanı hesaplandı.");
    }
}

```

</details>

<details>

<summary>Java'da static ve final nedir ve nerelerde kullanılıyor. Örnek verebilir misin?</summary>



static`ve`final\` anahtar kelimeleri, Java programlama dilinde farklı amaçlar için kullanılan önemli kavramlardır.

1. `static` Anahtar Kelimesi:

    * `static` anahtar kelimesi, bir değişkenin veya metotun sınıfa ait olduğunu belirtmek için kullanılır. Bu, o
      değişkenin veya metotun sınıfın herhangi bir örneği olmadan kullanılabileceği anlamına gelir.
    * `static` değişkenler, sınıfa ait olan değişkenlerdir ve her bir örneği tarafından paylaşılırlar. Değişkenin son
      değeri, tüm örnekler arasında aynıdır.
    * `static` metotlar, sınıfa ait olan metotlardır ve sınıf adıyla doğrudan çağrılabilirler. Bunlar örneklerle
      ilişkili olmadığından, sınıfın durumunu değiştiremezler.&#x20;
    * Örnek:

   ```java
    class MyClass {
          static int count; // Statik bir değişken

          public MyClass() {
              count++; // Her bir örneğin oluşturulmasıyla count değeri artar
          }

          public static void printMessage() {
              System.out.println("Statik metot");
          }
      }
      
      MyClass obj1 = new MyClass();
      MyClass obj2 = new MyClass();
      System.out.println(MyClass.count); // Çıktı: 2
      MyClass.printMessage(); // Çıktı: Statik metot
   ```


2. `final` Anahtar Kelimesi:

    * `final` anahtar kelimesi, bir değişkenin, metotun veya sınıfın değiştirilemez olduğunu belirtmek için kullanılır.
    * `final` değişkenler, bir kez değer atandıktan sonra değiştirilemezler. Sabit değerlere sahip değişkenlerdir.
    * `final` metotlar, alt sınıflar tarafından ezilemezler. Yani, bu metotlar alt sınıflar tarafından değiştirilemez
      veya yeniden uygulanamaz.
    * `final` sınıflar, alt sınıflara sahip olamazlar. Yani, başka bir sınıf bir `final` sınıfından türetilemez.&#x20;
    * Final degiskenler, class'larda ve methodlarda kullanilabilir.
    * Örnek:

   ```java
   final int MAX_VALUE = 100;
      // MAX_VALUE değeri bir kez atandıktan sonra değiştirilemez

      class BaseClass {
          public final void printMessage() {
              System.out.println("BaseClass'ten mesaj");
          }
      }

      class DerivedClass extends BaseClass {
          // Hata verecektir: "Cannot override the final method from BaseClass"
          public void printMessage() {
              System.out.println("DerivedClass'ten mesaj");
          }
      }

      final class FinalClass {
          // ...
      }

      // Hata verecektir: "Cannot inherit from final FinalClass"
      class DerivedClass extends FinalClass {
          // ...
      }
      
   ```

</details>

<details>

<summary>Java'da Set ve Map veri yapılarının ArrayList ile fark?</summary>

1. Veri Sıralaması: **`ArrayList`**, verileri eklenme sırasına göre saklar ve tekrarlı elemanlara izin verirken, **`Set`
   ** verileri sırasız bir şekilde saklar ve tekrarlı elemanlara izin vermez. **`Map`** ise anahtar-değer çiftlerini
   saklar ve her anahtarın yalnızca bir kez bulunmasına izin verir.
2. Eleman Erişimi: **`ArrayList`**, indeks numaraları kullanılarak elemanlara erişimi destekler. **`Set`** ve **`Map`**
   ise elemanlara anahtar değerleriyle erişimi destekler. Her bir elemanın benzersiz bir anahtarı olduğu için, hızlı
   erişim sağlarlar.
3. Tekrarlı Elemanlar: **`ArrayList`** aynı elemanın birden fazla kez bulunmasına izin verirken, **`Set`** ve **`Map`**
   her elemanın yalnızca bir kez bulunmasına izin verir.
4. Performans: Eleman ekleme ve silme işlemlerinde **`ArrayList`** daha hızlıdır, çünkü elemanların sırasını korumak
   için fazladan bir maliyeti yoktur. Ancak, elemanlara erişimde **`Set`** ve **`Map`** daha hızlıdır çünkü anahtar
   değerlerini kullanarak doğrudan elemanlara erişebilirler.

</details>

<details>

<summary>ArrayList and a LinkedList arasindaki fark?</summary>

**`ArrayList`** indeks tabanlı erişim ve sıralı veri depolama için daha uygundurken, **`LinkedList`** dinamik ekleme ve
silme işlemleri için daha uygundur.

</details>

<details>

<summary>HashMap'ın çalışma mantığını anlatırmısın. Neden equal ve hashCode methodlarını kullanmalıyız?</summary>

1. `HashMap`'in Çalışma Mantığı:
    * `HashMap`, bir anahtar-değer ikilileri koleksiyonudur. Her bir anahtar, benzersiz olmalıdır ve değerlere karşılık
      gelir.
    * `HashMap`, anahtarların hash değerlerine dayanarak verileri hızlı bir şekilde depolar ve erişir.
    * Bir anahtarın hash değeri, `hashCode()` metodunu kullanarak hesaplanır. Bu hash değeri, `HashMap` içindeki bir
      hücreye (bucket) karşılık gelir.
    * Eşleşen anahtarlar aynı hücreye atanabilir. Bu durumda, bu hücrede bir zincir (linked list) oluşur.
    * `HashMap`, `equals()` metodu aracılığıyla anahtarların eşitliğini kontrol eder. Eşit olan anahtarlar aynı hücrede
      aynı zincirde bulunur.
    * Bir değere erişmek istediğimizde, ilgili anahtarın hash değeri kullanılarak hedef hücreye ulaşılır ve zincirde
      gezinilir.
2. `equals()` ve `hashCode()` Metodlarının Önemi:
    * `equals()` metodu, iki nesnenin içeriklerinin eşit olup olmadığını kontrol eder. `HashMap` içinde anahtarları
      karşılaştırmak için kullanılır.
    * `hashCode()` metodu, bir nesnenin benzersiz bir hash değerini döndürür. Bu değer, `HashMap` içindeki hücreye
      yerleştirme ve erişimde kullanılır.
    * `HashMap`, iki anahtarın eşit olduğunu belirlemek için `equals()` metodunu kullanır. Eğer `equals()` metodu doğru
      bir şekilde uygulanmazsa, aynı anahtarın farklı hash değerleri olabilir ve bu da beklenmeyen sonuçlara yol
      açabilir.
    * `hashCode()` metodunun doğru bir şekilde uygulanması, aynı nesnelerin her zaman aynı hash değerine sahip olmasını
      sağlar. Bu, aynı anahtarın aynı hücreye atanmasını ve doğru değerin elde edilmesini sağlar.
    * `equals()` ve `hashCode()` metodlarının birlikte kullanılması, `HashMap` içinde anahtarların doğru şekilde
      çalışmasını sağlar. Eğer bir anahtarın `equals()` metodunu geçersiz kılarsanız, aynı anahtarın `hashCode()`
      metodunu da geçersiz kılmanız gerekir.

`equals()` ve `hashCode()` metodlarının doğru bir şekilde uygulanması, `HashMap`'in anahtarlarını güvenilir ve etkin bir
şekilde işlemesini sağlar. Bu nedenle, `HashMap` veya benzeri veri yapılarında anahtar olarak kullanılan sınıfların bu
metodları düzgün bir şekilde uygulamaları önemlidir. Aksi takdirde, beklenmeyen sonuçlara ve hatalı veri erişimine neden
olabilir.

</details>

<details>

<summary>Stack ve Heap memory Arasındaki Fark Nedir?</summary>

Eğer program esnasında boyutları bildirilmiş değişmez bir değer kullanıyorsak _stack_, değişebilir bir değer
kullanıyorsak _heap_ bizim için uygun olacaktır. _Stack_ ve _heap_ kullanımları farklı ve dikkat edilmesi gereken bir
konudur. _Stack_ kullanılır ve işi bittikten sonra kendini otomatik olarak bellekten yok eder. Fakat _heap_‘te bu işi
siz yapmalısınız.

Genel olarak, stack hafızası genellikle yerel değişkenler, metod çağrıları, işaretçiler gibi programın çalışma zamanında
dinamik olarak değişmeyen verileri depolamak için kullanılırken, heap hafızası daha büyük ve dinamik olarak değişen veri
yapılarını, nesneleri ve veri yapısı örneklerini depolamak için kullanılır.

</details>

<details>

<summary>Mutable ve Immutable nedir ?</summary>

Immutable (degismez), nesneler bir kez olusturulduktan sonra icerigi degistirilemeyen siniflardir. Tam tersi olarak,
degistirilebilen siniflar da Mutable (degisebilir) siniflardir. Kisacasi Immutable nesneler degismeyen nesnelerdir.
Onlari olusturursun, fakat onlari degistiremezsin.

Java'da immutability ornegi String sinifidir. String nesneleri bir kez olusturulduktan sonra degistirilemez. Eger bir
String nesnesini degistirirseniz, aslinda yeni bir String nesnesi olusturulur.

Immutabilite avantajlari sunlar olabilir:

1. **Thread Guvenligi:** Degismez nesnelerin thread guvenligi daha yuksektir, cunku bir kez olusturulduktan sonra durumu
   degistirilemedigi icin senkronizasyon sorunlari ortaya cikmaz.
2. **Cacheleme Kolayligi:** Degismez nesneler cacheleme (onbellege alma) icin uygundur, cunku bir kere olusturulduktan
   sonra degerleri degismedigi icin cacheleme islemleri daha etkili olabilir.
3. **Debug Kolayligi:** Degismez nesnelerin degerleri degismedigi icin programin durumu daha ongorulebilir ve hata
   ayiklama daha kolay olabilir.
4. **Referans Stabilitesi:** Degismez nesnelerin referanslari degismedigi icin bir nesnenin referansi uzerinde calisan
   diger kodlar icin beklenmeyen durumlar ortaya cikmaz.

Bu nedenlerden dolayi, ozellikle coklu is parcacigi iceren ortamlarda veya guvenilir, tahmin edilebilir kod yazma
ihtiyaci olan yerlerde immutabilite prensibi tercih edilebilir.

</details>

<details>

<summary>Multithreading nedir ?</summary>

Multithreading'in avantajları:

1. Performans Artışı: Multithreading, iş parçacıklarını eşzamanlı olarak çalıştırarak programın daha hızlı çalışmasını
   sağlar.
2. Paralel İşlemler: Birden fazla iş parçacığı sayesinde farklı görevler aynı anda yürütülebilir, bu da paralelizmi
   sağlar.
3. Daha iyi Yanıt Süresi: Multithreading, kullanıcı girişlerine daha hızlı yanıt verir ve daha duyarlı bir kullanıcı
   deneyimi sağlar.
4. Kaynak Verimliliği: İş parçacıklarının çekirdekler arasında dağıtılması, işlemci kaynaklarının daha verimli
   kullanılmasını sağlar.
5. İletişim ve Paylaşım: İş parçacıkları arasında bilgi ve veri paylaşımı yapabilir, iletişim kurabilirsiniz.

Multithreading'in dezavantajları:

1. Yarış Koşulları: Birden fazla iş parçacığı aynı kaynağı değiştiriyorsa, yarış koşulları ve veri uyumluluğu sorunları
   ortaya çıkabilir.
2. Senkronizasyon Zorlukları: İş parçacıkları arasında senkronizasyon gerektiğinde, senkronizasyon mekanizmalarını doğru
   şekilde kullanmak karmaşık olabilir.
3. Hata Ayıklama: Multithreading hataları genellikle daha zor tespit edilebilir ve hata ayıklama süreci daha karmaşık
   olabilir.
4. Kaynak Tüketimi: Birden fazla iş parçacığı, işlemci ve bellek kaynaklarını daha yoğun bir şekilde kullanır. Gereksiz
   iş parçacığı oluşturma veya verimsiz kodlamalar performans sorunlarına neden olabilir.
5. Karmaşıklık: Multithreading, programın karmaşıklığını artırabilir. İş parçacıklarının doğru bir şekilde senkronize
   edilmesi ve yönetilmesi gereklidir.

Sonuç olarak, multithreading'in avantajları arasında performans artışı, paralel işlemler, daha iyi yanıt süresi ve
kaynak verimliliği bulunurken, yarış koşulları, senkronizasyon zorlukları, hata ayıklama zorlukları ve kaynak tüketimi
gibi dezavantajları da vardır. Doğru bir şekilde kullanıldığında multithreading, verimli ve hızlı çalışan uygulamaların
geliştirilmesini sağlar.

</details>

<details>

<summary>Reflection nedir?</summary>

Reflection, bir programin calisma zamaninda kendi yapisini, ozelliklerini ve davranislarini inceleme yetenegidir. Yani,
bir Java programinin calisma zamaninda siniflari, metodlari, alanlari ve diger bilesenleri analiz edip manipule etmesini
saglayan bir ozelliktir. Reflection, genellikle siniflarin ve nesnelerin ozelliklerine dinamik olarak erisim saglamak,
nesne olusturmak, metodlari cagirmak gibi islemleri gerceklestirmek icin kullanilir.

Java'da Reflection, `java.lang.reflect` paketi icinde bulunan siniflar ve arayuzler araciligiyla gerceklestirilir. Bu
paket icinde yer alan `Class`, `Method`, `Field`, `Constructor` gibi siniflar, Reflection islemlerini gerceklestirmek
icin kullanilir.

Bir sinifin veya nesnenin ozelliklerine Reflection kullanarak erisebilir ve bu ozellikleri manipule edebilirsiniz.
Ancak, Reflection kullanmak genellikle performans maliyeti yuksek bir islemdir ve kodunuzu karmasik hale getirebilir. Bu
nedenle, Reflection'i kullanmadan once dikkatlice dusunmek ve ihtiyaciniz olup olmadigini degerlendirmek onemlidir.

Ornek bir Reflection kullanimi su sekilde olabilir:

```java
import java.lang.reflect.Method;

public class ReflectionExample {
    public static void main(String[] args) {
        try {
            // Reflection ile bir sinifin Class nesnesini almak
            Class<?> clazz = Class.forName("com.example.MyClass");

            // Reflection ile bir sinifin metotlarini almak
            Method[] methods = clazz.getDeclaredMethods();

            // Alinan metotlari yazdirmak
            for (Method method : methods) {
                System.out.println("Method Name: " + method.getName());
            }
        } catch (ClassNotFoundException e) {
            e.printStackTrace();
        }
    }
}
```

Bu ornekte, `Class.forName` metodu ile belirtilen sinifin `Class` nesnesini aliyoruz. Daha sonra `getDeclaredMethods`
metodu ile bu sinifin tum metotlarini alip yazdiriyoruz. Bu, basit bir Reflection ornegidir.

</details>

<details>

<summary>Idempotence nedir?</summary>

Idempotans (idempotence), ayni islemin bir veya daha fazla kez uygulanmasinin sonucunu degistirmeyecek veya
etkilemeyecek bir ozelliktir. Idempotent bir islem, bir kez uygulandiginda sonucunun ne oldugu onemli olmaksizin, ayni
islemi tekrar tekrar uygulamak, sonucu degistirmeyecek veya sistemde istenmeyen etkiler yaratmayacaktir.

Idempotansin temel ozellikleri sunlardir:

1. **Tekrarlilik:** Bir islem idempotentse, ayni islemi bir veya daha fazla kez uygulamak sonucu degistirmeyecek veya
   etkilemeyecektir.
2. **Guvenli Uygulama:** Idempotent islemler, guvenli bir sekilde tekrar tekrar uygulanabilir. Ornegin, ayni HTTP istegi
   bir veya daha fazla kez gonderildiginde, sistemde istenmeyen sonuclar olmamalidir.
3. **Durumsuzluk:** Idempotent islemler durumsuzdur, yani bir islemi uygulamak icin sistemdeki gecmis durumu bilmeye
   ihtiyac duymazlar. Herhangi bir anda, ayni islemi uygulamak, gecmisteki uygulamalarla baglantili degildir.

Bu ozellik, ozellikle dagitik sistemlerde, ag hatalari ve tekrar denemelerle basa cikma gibi senaryolarda onemli bir rol
oynar.

HTTP protokolu icinde bazi metotlar idempotenttir. Ornegin, GET, PUT, HEAD ve DELETE idempotent islemlerdir. PUT metodu,
bir kaynagi belirtilen konumda guncellemek icin kullanildiginda idempotenttir cunku ayni veriyi tekrar tekrar gondermek
sonucu degistirmeyecektir. Ancak, POST metodu genellikle idempotent degildir cunku genellikle yeni bir kaynak olusturmak
icin kullanilir, ve ayni POST istegi tekrar tekrar gonderildiginde her seferinde yeni bir kaynak olusturabilir.

</details>

---

### *Spring ve Spring Boot*

<details>

<summary>Spring ve Spring Boot arasındaki farklar ?</summary>

1. Proje Başlatma ve Yapılandırma: Spring, geliştiricilerin daha fazla yapılandırma seçeneği sunarken, Spring Boot,
   otomatik yapılandırmayı ve varsayılan ayarları kullanarak projenin hızlı bir şekilde başlatılmasını sağlar.
2. Bağımlılıklar ve Konfigürasyon: Spring, projenin bağımlılıklarını ve yapılandırmasını geliştiricinin belirlemesine
   olanak tanırken, Spring Boot, bağımlılıkları ve yapılandırmayı otomatik olarak yönetir. Bu sayede, geliştirici daha
   az ayar yaparak projeyi hızlı bir şekilde başlatabilir.
3. Standartlaştırma: Spring, esneklik ve özelleştirme seçenekleri sunarken, Spring Boot, standart yapılandırma ve proje
   yapısı sunarak projelerin hızlı bir şekilde geliştirilmesini sağlar. Spring Boot, konvansiyonları takip eden bir
   yapıya sahiptir ve "opinionated" (belirli bir yaklaşımı tercih eden) bir yaklaşım sergiler.
4. Geliştirme Deneyimi: Spring Boot, otomatik yapılandırma ve dahili sunucu gibi özellikleriyle geliştirme sürecini
   kolaylaştırır. Ayrıca, Spring Boot, aktif geliştirme topluluğu ve hazır örnek projeleri sayesinde başlangıç seviyesi
   ve hızlı prototip oluşturma için popüler bir seçenektir.

Sonuç olarak, Spring ve Spring Boot, Java tabanlı uygulamaların geliştirilmesinde kullanılan framework'lerdir. Spring,
esneklik ve özelleştirme seçenekleri sunarken, Spring Boot ise hızlı başlatma, otomatik yapılandırma ve standartlaştırma
gibi özellikleriyle projelerin hızlı bir şekilde geliştirilmesini sağlar. Spring

</details>

<details>

<summary>Spring Application Context nedir?</summary>

Spring Framework'te `ApplicationContext`, Spring uygulamalarindaki nesnelerin yasam dongusunu ve bagimliliklarini
yoneten merkezi bir konteynerdir. Bu konteyner, bir Java EE uygulamasinin ortami icin yapilandirma bilgilerini,
servisleri ve bilesenleri icerir. `ApplicationContext`, Spring IoC (Inversion of Control) konteynerinin en kapsamli
uygulamasidir.

`ApplicationContext`, genellikle uygulamanin baslangicinda olusturulur ve uygulamanin yasam suresi boyunca varligini
surdurur. Bu konteyner, Spring bilesenlerini (bean'leri), tanimli servisleri ve diger uygulama bilesenlerini yonetir.

`ApplicationContext`'in temel ozellikleri sunlardir:

1. **IoC Konteyneri:**
    * IoC prensibine dayanir. Bu, uygulama kodunun nesneleri olusturmak ve bunlari bagimliliklariyla iliskilendirmek
      yerine, bu islemlerin konteyner tarafindan yonetilmesi anlamina gelir.
2. **Bean Yonetimi:**
    * Spring uygulamalarindaki nesneler genellikle "bean" olarak adlandirilir. `ApplicationContext`, bu bean'leri
      olusturur, yonetir ve gerektiginde saglar. Bean'ler, genellikle XML veya Java tabanli konfigurasyonlarla
      tanimlanir.
3. **AOP (Aspect-Oriented Programming) Destegi:**
    * `ApplicationContext`, AOP prensiplerine uygun olarak cesitli nesne yonlendirmeleri ve kesme noktalari tanimlama
      yetenegi saglar. Bu, uygulamanin modulerligini artirir.
4. **Olay Yayini ve Dinleme:**
    * `ApplicationContext`, uygulama icindeki olaylari yayinlamak ve dinlemek icin bir olay mekanizmasi saglar. Bu,
      uygulama icindeki farkli bilesenlerin haberlesmesini kolaylastirabilir.
5. **Uygulama Duzeyinde Hata Yonetimi:**
    * `ApplicationContext`, uygulama duzeyinde hata yonetimi saglar. Bu, ozel hata durumlari icin tanimlanmis olan hata
      isleyicileri ve stratejileri kullanma yetenegi anlamina gelir.
6. **Cevre (Environment) Destegi:**
    * `ApplicationContext`, uygulamanin calistigi cevreyi (development, production, test vb.) belirleyen bir cevre
      nesnesi saglar. Bu, cesitli konfigurasyonlarin uygulama uzerinde farkli sekillerde etki gostermesini saglar.

Spring uygulamalarinin cogu, `ApplicationContext`'in ozel bir turu
olan `AnnotationConfigApplicationContext`, `ClassPathXmlApplicationContext` veya `GenericWebApplicationContext` gibi
turlerle olusturulan bir `ApplicationContext` kullanir.

</details>

<details>

<summary>Spring Context nedir?</summary>

Spring Context, Spring Framework'de önemli bir rol oynayan ve uygulama bileşenlerini yöneten temel yapıdır. Spring
Context, IOC (Inversion of Control) prensibini uygular ve Spring Bean'lerinin oluşturulması, yapılandırılması ve
yönetilmesinden sorumlu olan bir konteynerdir.

Spring Context, genellikle "ApplicationContext" adlı bir arayüzü veya onun uygulamasını temsil eder. Bu, Spring tabanlı
uygulamaların çalışma zamanında oluşturulan ve Spring Bean'lerini barındıran bir ortamdır. Uygulama, Spring Context
üzerinden Spring Bean'lerine erişebilir ve Spring Context tarafından yönetilen nesnelerin yaşam döngüsünü kontrol
edebilir.

Spring Context, XML veya Java tabanlı yapılandırmayla oluşturulabilir. XML tabanlı yapılandırmada, "
applicationContext.xml" gibi bir dosyada bean tanımlamaları yapılırken, Java tabanlı yapılandırmada ise "
AnnotationConfigApplicationContext" veya diğer uygun uygulamalar kullanılarak yapılandırma sınıfı belirtilir.

Spring Context, aşağıdaki işlevleri sağlar:

1. **Dependency Injection (Bağımlılık Enjeksiyonu):** Spring Context, Spring Bean'lerine diğer bağımlılıklarını enjekte
   eder. Böylece, nesneler arasındaki bağımlılıkları azaltır ve uygulamanın esnekliğini artırır.
2. **Bean Yaratma ve Yönetimi:** Spring Context, Spring Bean'lerinin yaşam döngüsünü yönetir ve istemci tarafından elle
   oluşturulması ve yönetilmesi gerekmez. İlgili yapılandırmalara göre Spring Context, bean'leri önceden oluşturabilir
   veya istemci talebine göre onları oluşturabilir.
3. **AOP (Aspect-Oriented Programming) Desteği:** Spring Context, AOP prensiplerini uygulamayı sağlar. Bu sayede,
   uygulama işlevselliğini temel iş mantığından ayrı olarak modüle edebilir ve belirli işlemleri yatay olarak keserek
   tekrar kullanabilir.
4. **Internationalization (I18N) Desteği:** Spring Context, uygulama içinde metinlerin çevirisini ve yerelleştirmeyi
   kolaylaştıran I18N desteği sunar.

Spring Context, uygulama tarafından oluşturulur ve genellikle uygulama ömrü boyunca varlığını sürdürür. Bu sayede,
Spring Bean'lerini yönetir ve uygulama bileşenlerinin etkileşimini kolaylaştırır. ApplicationContext, birçok farklı tipi
destekler ve Spring tarafından sağlanan çeşitli özellikleri kullanarak uygulamanın ihtiyaçlarına uygun şekilde
yapılandırılabilir.

</details>

<details>

<summary>Spring AOP?</summary>

Aspect-oriented programming (AOP) Faydaları:

* Daha temiz bir kod oluşur
* Kodları okumak kolaylaşır
* Sürdürülmesi daha kolaydır
* Kod tekrarından kaçınır
* Kodları test etmek daha kolay
* Geliştirme yapmayı hızlandırır

</details>

<details>

<summary>Spring IOC nedir?</summary>

Spring IOC (Inversion of Control), Spring Framework'ün temel bir prensibidir ve bir tasarım desenidir. IOC, bir
bileşenin (bean) oluşturulması, yapılandırılması ve yönetilmesi sürecinin kontrolünü programcıdan alarak, bu görevi
Spring Framework'e devretmeyi sağlar.

IOC'nin temel felsefesi, bağımlılıkların tersine çevrilmesidir. Geleneksel olarak, bir bileşen diğer bileşenlerle
doğrudan ilişkilerini kurar ve bunları oluşturur veya yönetir. Ancak, IOC ile bileşenlerin bağımlılıkları tersine
çevrilir ve Spring konteyneri tarafından yönetilen bir IOC konteyneri kullanılır.

Spring IOC, aşağıdaki şekillerde sağladığı avantajlara sahiptir:

1. Bağımlılıkların Yönetimi: IOC sayesinde, bileşenlerin bağımlılıklarını yönetmek kolaylaşır. Bileşenler, Spring
   konteynerine tanımlanır ve bağımlılıkları otomatik olarak çözülür.
2. Gevşek Bağlılık(Loosely coupled?): IOC, bileşenler arasındaki bağımlılığı gevşek hale getirir. Bileşenler, aralarında
   sıkı bağlantılar oluşturmak yerine, Spring konteyneri tarafından yönetilen arayüzler veya sözleşmeler üzerinden
   etkileşimde bulunurlar.
3. Test Edilebilirlik: IOC, bağımlılıkları enjekte etme mekanizması sunar, bu da bileşenlerin daha kolay test edilmesini
   sağlar. Bağımlılıkların taklitleri (mocks) kullanılarak bileşenlerin test edilmesi daha kolay hale gelir.
4. Modülerlik: IOC, bileşenlerin bağımsız olarak geliştirilmesini ve yeniden kullanılmasını sağlar. Bileşenlerin
   işlevselliği birbirinden bağımsız olarak geliştirilebilir ve daha sonra IOC konteyneri tarafından birleştirilir.

Inversion of control;

* Strategy Pattern
* Service Lacator Pattern
* Factory Pattern
* Dependency Injection

gibi mekanizmalarla uygulanabilir.

</details>

<details>

<summary>Spring Bean nedir?</summary>

Spring Bean, Spring Framework tarafından yönetilen ve IOC konteyneri tarafından oluşturulan, yönetilen ve yapılandırılan
bir nesnedir. Bean'ler, Spring uygulamalarında kullanılan temel yapı taşlarıdır ve Spring konteyneri tarafından
oluşturulurlar ve yönetilirler.

Spring Bean'lerin temel özellikleri şunlardır:

1. Yaşam Döngüsü Yönetimi: Spring Bean'ler, IOC konteyneri tarafından yönetilen bir yaşam döngüsüne sahiptir. Konteyner,
   bean'in oluşturulması, yapılandırılması, kullanılması ve sonlandırılması gibi adımları otomatik olarak
   gerçekleştirir.
2. Bağımlılıkların Otomatik Çözülmesi: Bean'ler arasındaki bağımlılıklar, IOC konteyneri tarafından otomatik olarak
   çözülür. Bağımlı bean'ler, uygun şekilde enjekte edilir veya referansları çözülür.
3. Yapılandırma ve Ayarlanabilirlik: Bean'ler, Spring konteynerine yapılandırma metadataları ile tanımlanır. Bu
   metadatalar, XML veya Java tabanlı konfigürasyon dosyaları, Java Annotation'ları veya Spring Boot gibi modern araçlar
   aracılığıyla sağlanabilir. Bu sayede bean'lerin özellikleri, bağımlılıkları ve davranışları kolayca ayarlanabilir.
4. Ölçeklenebilirlik ve Modülerlik: Spring Bean'ler, uygulamaların ölçeklenmesi ve modüler bir yapıya sahip olması için
   kullanışlıdır. Bileşenlerin ayrı ayrı geliştirilebilmesi ve ardından IOC konteyneri tarafından birleştirilmesi
   sağlanır.

Spring Bean'ler, Spring Framework'ün sunduğu çeşitli özelliklerden yararlanabilirler. Örneğin, AOP (Aspect-Oriented
Programming) ile güvenlik, transaksiyon yönetimi, önbellekleme gibi ilave işlevselliği uygulamak mümkündür.

Spring Bean'leri, IOC konteynerine tanımlanan bir isim veya tip aracılığıyla elde edebilir ve uygulamanın farklı
bölgelerinde kullanabilirsiniz. Bu sayede bean'lerin oluşturulması ve yönetimi Spring tarafından otomatik olarak
gerçekleştirilirken, programcılar bean'lerin işlevselliği üzerinde odaklanabilir ve kolayca uygulama geliştirebilir.

</details>

<details>

<summary>Spring Bean nedir?</summary>

Spring Bean, Spring Framework'in temel yapı taşlarından biridir. Spring, Java tabanlı bir uygulama geliştirme
çerçevesidir ve işletim ortamı bağımsızlığı ve hafiflik sunar. Spring Bean, Spring konteyneri tarafından yönetilen ve
yönetilen nesnelerin bir örneğidir.

Spring Bean'ler, Spring IOC (Inversion of Control) prensibiyle yönetilir. Bu prensip, uygulama nesnelerinin
oluşturulması, yapılandırılması ve yönetilmesinin doğrudan uygulama tarafından değil, dış bir konteyner tarafından
gerçekleştirilmesini sağlar. Bu, uygulama kodunun daha esnek ve kolay test edilebilir olmasına yardımcı olur.

Spring Bean'leri tanımlamak için genellikle XML tabanlı ya da Java tabanlı yapılandırma kullanılır. XML tabanlı
yapılandırmada, "applicationContext.xml" gibi bir dosya içinde bean tanımları yapılırken, Java tabanlı yapılandırmada
ise "@Component" veya "@Bean" gibi Spring tarafından sağlanan belirteçler kullanılarak tanımlamalar yapılır.

Örnek olarak, aşağıdaki gibi bir Spring Bean tanımı düşünelim:

```xml

<bean id="exampleBean" class="com.example.ExampleBean">
    <!-- Bean properties and dependencies -->
</bean>
```

veya Java tabanlı yapılandırmada:

```java

@Component
public class ExampleBean {
    // Bean properties and dependencies
}
```

Bu tanımlamalar, "exampleBean" adında bir Spring Bean'in oluşturulduğunu belirtir. Bu nesneye, sınıfının adı olan "
com.example.ExampleBean" veya Java tabanlı yapılandırmada sınıfın kendisi atanarak bağımlılıklar ve özellikler
belirtilir.

Spring Bean'ler, Spring uygulamalarındaki farklı bileşenler arasında veri ve hizmetlerin paylaşılmasını sağlar. Aynı
zamanda, bu bileşenlerin yaşam döngüsü, Spring konteyneri tarafından yönetilir, bu nedenle geliştirici tarafından elle
oluşturulup yönetilmesine gerek kalmaz.

Spring'de bean'leri olusturmanin birkac yolu vardir:

#### 1. **XML Tabanli Konfigurasyon:**

Spring, XML tabanli konfigurasyon kullanarak bean'leri tanimlamaniza olanak tanir. Ornegin:

```xml
<!-- applicationContext.xml -->
<beans>
    <bean id="myBean" class="com.example.MyBean"/>
</beans>
```

#### 2. **Component Scanning ve `@Component` Annotation:**

Spring, siniflari otomatik olarak taramak ve tanimlamak icin bilesen tarama (component scanning) ozelligini sunar.
Siniflari tanimlamak icin `@Component` veya ozel olarak belirlenmis diger stereotype anotasyonlari kullanabilirsiniz.

```java
// Sinif tanimi
@Component
public class MyComponent {
    // ...
}
```

#### 3. **`@Service`, `@Repository`, ve `@Controller` Annotasyonlari:**

`@Service`, `@Repository`, ve `@Controller` gibi anotasyonlar, sinifin ozel bir rol oynadigini belirten ozel stereotype
anotasyonlardir. Bu anotasyonlar, `@Component` anotasyonunu genisletir.

```java
// @Service anotasyonuyla isaretlenmis bir sinif
@Service
public class MyService {
    // ...
}
```

#### 4. **JavaConfig ve `@Bean` Annotasyonu:**

JavaConfig kullanarak bean'leri tanimlamak da mumkundur. Bu, bir konfigurasyon sinifinda `@Bean` anotasyonu kullanarak
gerceklestirilir.

```java

@Configuration
public class AppConfig {

    @Bean
    public MyBean myBean() {
        return new MyBean();
    }
}
```

Bu yontemlerin her biri, Spring konteynerinin yonetimine girecek bean'leri belirlemenin bir yolunu saglar. Secim,
uygulamanizin ihtiyaclarina ve tercih ettiginiz konfigurasyon tarzina baglidir.

</details>

<details>

<summary>Dependency injection yöntemleri nelerdir?</summary>

* **Dependency injection yöntemleri nelerdir?**

  Bağımlılığını en aza indirmek için kullanılır.

    1. Constructor Injection: Bu yöntemde, bir bileşenin bağımlılıkları, bileşenin bir yapılandırıcı metodu kullanılarak
       enjekte edilir. Bu yöntem, bir sınıfın başlatılması için gereken tüm bağımlılıkların açıkça belirtilmesini sağlar
       ve kodun okunaklılığını artırır.

       ```java

       @Component
       public class MailService implements MessageService {
       private Repository repository;

       @Autowired
       public MailService(Repository repository) {
           this.repository = repository;
       }

       ```
    2. Setter Injection: Bu yöntemde, bir bileşenin bağımlılıkları, bileşenin özellikleri üzerinden enjekte edilir. Bu
       yöntem, bir bileşenin başlatılması sırasında, tüm bağımlılıkların belirtilmesini gerektirmez. Bunun yerine,
       bileşenin özellikleri çağrılarak enjekte edilir.

       ```java
          
       @Component
       public class MailService implements MessageService {
       private Repository repository;

            @Autowired
            public void setRepository(Repository repository) {
        this.repository = repository;

       ```
    3. Interface Injection: Bu yöntemde, bir bileşenin bağımlılıkları, bileşenin bir arayüzü kullanılarak enjekte
       edilir. Bu yöntemde, bileşenin arayüzü, bağımlılıkları tanımlar ve bileşenin başlatılması sırasında, arayüzü
       uygulayan bir sınıfın enjekte edilmesi gereklidir.

       ```java
          
       @Component
       public class MailService implements IMessageService {

       ```

</details>

<details>

<summary>Spring’te Bean scope’lari nedir?</summary>

    https://medium.com/tapu-com-bak%C4%B1%C5%9F-a%C3%A7%C4%B1s%C4%B1/spring-boot-bean-scope-kavram%C4%B1-ve-%C3%B6nemi-d67cb6396270

Spring Framework, uygulama icindeki beanlerin yasam dongusunu ve kullanim kapsamlarini yonetmek icin bean scope'larini
tanimlar. Bean scope'u, bir bean'in bir uygulama icindeki belirli bir baglam icindeki yasam suresini ve gorunurlugunu
belirler. Iste Spring'te bulunan bazi yaygin bean scope'lari:

1. **Singleton:**
    * **Aciklama:** Singleton scope'u, bir uygulama icinde yalnizca bir tek ornegi olusturulacak ve paylasilacak olan
      beanler icin kullanilir.
    * **Tanimlama:** `@Scope("singleton")` veya sadece `@Singleton` anotasyonu kullanilarak belirlenir (varsayilan
      scope).
2. **Prototype:**
    * **Aciklama:** Prototype scope'u, her talepte yeni bir ornek olusturacak ve kullanacak olan beanler icin
      kullanilir.
    * **Tanimlama:** `@Scope("prototype")` veya sadece `@Prototype` anotasyonu kullanilarak belirlenir.
3. **Request:**
    * **Aciklama:** Request scope'u, her HTTP isteginde bir kere olusturulan ve o istegin yasam suresi boyunca
      paylasilan beanler icin kullanilir (yalnizca web uygulamalari icin gecerlidir).
    * **Tanimlama:** `@Scope(value = WebApplicationContext.SCOPE_REQUEST)` veya `@RequestScope` anotasyonu kullanilarak
      belirlenir.
4. **Session:**
    * **Aciklama:** Session scope'u, bir kullanicinin bir oturumu boyunca bir kez olusturulan ve o oturum suresince
      paylasilan beanler icin kullanilir (yalnizca web uygulamalari icin gecerlidir).
    * **Tanimlama:** `@Scope(value = WebApplicationContext.SCOPE_SESSION)` veya `@SessionScope` anotasyonu kullanilarak
      belirlenir.
5. **Application/Singleton (Spring 4+):**
    * **Aciklama:** Spring 4 ve sonraki surumlerde "application" ismiyle Singleton scope'u belirtilebilir. Bu, beanin
      bir uygulama icinde yalnizca bir kez olusturulup paylasilmasi anlamina gelir.
    * **Tanimlama:** `@Scope(value = ConfigurableBeanFactory.SCOPE_SINGLETON)` veya `@Scope("singleton")`
      kullanilabilir.
6. **WebSocket (Spring 4.2+):**
    * **Aciklama:** Spring 4.2 ve sonraki surumlerde "websocket" ismiyle bir scope tanimlandi. Bu scope, bir WebSocket
      baglantisi icin bir beanin yasam suresini belirler.
    * **Tanimlama:** `@Scope(value = "websocket", proxyMode = ScopedProxyMode.TARGET_CLASS)` kullanilabilir.

Bu scope'lar, Spring konteyneri tarafindan yonetilen beanlerin nasil olusturuldugu, paylasildigi ve ne kadar sureyle var
oldugu gibi konularda onemli bir rol oynar. Bean scope'larini secerken uygulamanin ihtiyaclarina ve kullanim
senaryolarina dikkat etmek onemlidir.

</details>

<details>

<summary>Spring framework ile gelistirilen bir uygulamada <code>@Service</code> anotasyonu tanimlandiginda, framework nasil davranir?</summary>

1. **Bean Olarak Yonetme:** Spring, `@Service` anotasyonu kullanildiginda sinifi bir Spring bean'i olarak yonetir. Bu,
   sinifin Spring tarafindan yonetilen bir bilesen oldugu anlamina gelir.
2. **Application Context'e Tanitma:** Sinif, Spring'in genel uygulama konteksti (application context) icinde tanitilir.
   Application context, uygulamanin genelindeki tum Spring bilesenlerini yoneten bir konteynerdir.
3. **Bean'in Olusturulmasi:** Application context, ilgili sinif icin bir nesne olusturur. Bu nesne, `@Service`
   anotasyonu ile isaretlenen sinifin bir ornegidir. Bu ornek, uygulama calistigi surece kullanilmaya hazir bir sekilde
   saklanir.

Bu adimlar, Spring'in `@Service` anotasyonu kullanilarak isaretlenen siniflari ele alir ve bunlari Spring konteynerinde
yonetilebilen, uygulamanin genelinde kullanilabilen bilesenlere donusturur.

</details>

<details>

<summary>spring bootta katmanli mimari</summary>

1. Veri Erişim Katmanı (Data Access Layer): Veri erişim katmanı, veritabanı veya diğer veri kaynaklarıyla etkileşimde
   bulunur. Bu katmanda, veritabanına erişim sağlamak için JPA (Java Persistence API) veya Spring Data JPA
   kullanılabilir. Veri erişim katmanı, veri tabanına sorguları yürütme, veri kaydetme/güncelleme/silme işlemlerini
   gerçekleştirme gibi görevleri yerine getirir.
2. Hizmet Katmanı (Service Layer): Hizmet katmanı, iş mantığının uygulandığı katmandır. İş kurallarının uygulandığı
   işlemler burada gerçekleştirilir. Hizmet katmanı, veri erişim katmanından gelen verileri işleyerek, iş kurallarına
   uygun şekilde işlemleri gerçekleştirir. Bu katmanda, işlemler genellikle iş mantığına odaklanır, veri erişimi ve veri
   dönüşümü gibi işlemler hizmet katmanı tarafından yönetilir.
3. Sunum Katmanı (Presentation Layer): Sunum katmanı, kullanıcı arayüzünün bulunduğu katmandır. Kullanıcı ile etkileşimi
   sağlayan API'ler, web sayfaları veya diğer istemci uygulamaları bu katmanda yer alır. Sunum katmanı, gelen istekleri
   alır, hizmet katmanı aracılığıyla işlemleri gerçekleştirir ve sonuçları kullanıcıya sunar.

* Sunum/Presentation için MVC - @Controller
* İş/business için Service -@Service
* Veri erişim/data access için Repository - @Repository

</details>

<details>

<summary>Spring framework icinde kullanilan tasarim desenleri neler?</summary>

1. **Singleton Tasarim Deseni:**
2. **Prototype Tasarim Deseni:**
3. **Factory Method Tasarim Deseni:**
4. **Dependency Injection (Bagimlilik Enjeksiyonu) Tasarim Deseni:**
5. **Observer Tasarim Deseni:**
6. **Proxy Tasarim Deseni:**
7. **Template Method Tasarim Deseni:**
8. **Inversion of Control(IoC):**
9. **AOP (Aspect-Oriented Programming):**

</details>

<details>

<summary>Spring MVC <code>DispatcherServlet</code> nedir?</summary>

Spring MVC'nin merkezi bilesenlerinden biri olan `DispatcherServlet`, gelen HTTP isteklerini isleyen ve uygun
kontrolcuye yonlendiren bir on denetleme (pre-processing) mekanizmasidir. Spring MVC, bir Model-View-Controller (MVC)
tasarim deseni uzerine kurulmustur ve `DispatcherServlet` bu tasarim deseninin uygulanmasini saglayan onemli bir
bilesendir.

`DispatcherServlet`, gelen HTTP isteklerini alir, bu istekleri isler ve sonuc olarak bir "Model" nesnesi olusturur. Bu
model nesnesi, bir "View" ile eslestirilerek HTML sayfasi veya baska bir turde kullanici arayuzu
olusturulur. `DispatcherServlet`, bu sureci baslatir ve sonuc olarak kullaniciya geri donecek olan HTML veya diger
icerikleri olusturur.

`DispatcherServlet`'in temel gorevleri sunlardir:

1. **Istek Yonlendirme (Request Mapping):**
    * Gelen HTTP isteginin URL'sine ve diger bilgilerine bakarak uygun kontrolcuyu belirler. Bu islem, konfigurasyon
      dosyalarinda (ornegin, `@RequestMapping` anotasyonlari) tanimlanan istek eslemeleri temelinde gerceklesir.
2. **Model ve View Olusturma:**
    * Belirlenen kontrolcu tarafindan islenen istek sonucunda bir model ve bir gorunum (view) olusturur. Model,
      kontrolcu tarafindan doldurulan verileri icerir.
3. **View Cozumleme (View Resolution):**
    * Olusturulan model ve view, belirtilen view cozuculeri tarafindan islenir ve gercek HTML sayfasi veya baska bir
      turdeki kullanici arayuzu olusturulur.
4. **HTTP Yaniti Olusturma:**
    * Istegin islenmesi sonucunda olusturulan view, yanit olarak kullaniciya gonderilir.

`DispatcherServlet`, genellikle Spring uygulamalarinda `web.xml` konfigurasyon dosyasinda veya daha modern bir yaklasim
olan Java tabanli konfigurasyon siniflarinda (JavaConfig) yapilandirilir.

Asagidaki ornekte, basit bir `DispatcherServlet` konfigurasyonu gosterilmektedir:

```xml
<!-- web.xml dosyasi -->
<servlet>
    <servlet-name>myDispatcherServlet</servlet-name>
    <servlet-class>org.springframework.web.servlet.DispatcherServlet</servlet-class>
    <init-param>
        <param-name>contextConfigLocation</param-name>
        <param-value>/WEB-INF/spring-mvc-config.xml</param-value>
    </init-param>
    <load-on-startup>1</load-on-startup>
</servlet>

<servlet-mapping>
<servlet-name>myDispatcherServlet</servlet-name>
<url-pattern>/</url-pattern>
</servlet-mapping>
```

Bu ornekte, `myDispatcherServlet` isimli bir `DispatcherServlet` konfigure edilmistir. `contextConfigLocation`
parametresi ile bu servlet icin kullanilacak olan Spring MVC konfigurasyon dosyasinin yolu belirtilmistir.

</details>

<details>

<summary>@service ve @component arasindaki fark nedir?</summary>

@Component'in bir bileşenin genel anlamda işaretlenmesi için kullanılması, @Service'in ise özellikle iş katmanı
bileşenleri için kullanılmasıdır.

Ama yaptiklarinda bir fark yok.

**@Service, @Controller, @Repository = {@Component + some more special functionality}**

</details>

<details>

<summary>@controller vs @restcontoller arasindaki fark?</summary>

@RestController, veri döndürmek için JSON veya XML formatını kullanarak HTTP isteklerine yanıt verir, @Controller ise
genellikle HTML sayfaları oluşturmak için kullanılır.

</details>

<details>

<summary>@ComponentScan, @Component, @Bean, @Repository, @Service, @Controller ve @RestController annotation neden kullanıyoruz?</summary>

Java Spring framework'ü, uygulama geliştirme sürecini kolaylaştıran ve düzenleyen bir dizi annotasyon (işaretleyici)
sağlar. İşte bu annotasyonlardan bazılarının kullanım amacı:

1. `@ComponentScan`: Bu annotasyon, Spring uygulamasının bileşenlerini (component) taramak için kullanılır. Belirtilen
   paket veya paketlerdeki sınıfları tarayarak, Spring tarafından yönetilen bean'leri bulur ve otomatik olarak yaratır.
2. `@Component`: Bu annotasyon, bir sınıfın bir Spring bileşeni olduğunu belirtmek için kullanılır. Spring, bu
   annotasyonu gördüğünde ilgili sınıfı bir bean olarak yönetir ve Spring uygulaması içinde kullanılabilir hale getirir.
3. `@Bean`: Bu annotasyon, bir metodu Spring tarafından yönetilen bir bean olarak kaydetmek için kullanılır. Genellikle
   yapılandırma sınıflarında veya @Configuration annotasyonu ile işaretlenmiş sınıflarda kullanılır. Bu şekilde, ilgili
   metot tarafından dönülen nesne Spring konteynerine dahil edilir ve uygulama içinde kullanılabilir hale gelir.
4. `@Repository`: Bu annotasyon, veri erişim katmanı (data access layer) sınıflarını belirtmek için kullanılır. Bir
   veritabanına erişmek, sorguları yürütmek veya veri işleme işlemlerini gerçekleştirmek gibi veri tabanı işlemleriyle
   ilgili sınıfları işaretlemek için kullanılır.
5. `@Service`: Bu annotasyon, iş mantığı katmanı (business logic layer) sınıflarını belirtmek için kullanılır. Uygulama
   iş mantığını uygulayan servis sınıflarını ifade eder. Veri işleme, hesaplamalar, dış hizmetlere erişim vb. gibi
   işlemleri gerçekleştirmek için kullanılabilir.
6. `@Controller`: Bu annotasyon, Spring MVC (Model-View-Controller) tabanlı web uygulamalarında kullanılan kontrol
   sınıflarını belirtmek için kullanılır. İstemci taleplerini karşılamak, işlemek ve uygun bir yanıt döndürmek için
   kullanılır.
7. `@RestController`: Bu annotasyon, RESTful web hizmetleri sunmak için kullanılan kontrol sınıflarını belirtmek için
   kullanılır. Hem `@Controller` hem de `@ResponseBody` annotasyonlarının birleşimidir. Bu sayede, ilgili sınıfın tüm
   yöntemleri JSON veya XML gibi veri formatlarında yanıtlar üretir.

Bu annotasyonlar, Spring framework'ü içinde uygulama bileşenlerini belirtmek ve yapılandırmak için kullanılır. Bu sayede
Spring, otomatik olarak sınıfları yönetir, bağımlılıkları çözer ve uygulamanın düzgün çalışmasını sağlar. Her
annotasyonun kendine özgü bir amacı ve kullanım senaryosu vardır ve projenin ihtiyaçlarına göre doğru bir şekilde
kullanılması önemlidir.

</details>

<details>

<summary>@Builder vs @SuperBuilder</summary>

Java'da, Lombok kutuphanesi siniflarin olusturulmasi sirasinda tekrar eden ve sikici olan kodlamayi azaltmak icin
kullanilir. `@Builder` ve `@SuperBuilder` gibi Lombok anotasyonlari, builder desenini uygulamak icin kullanilir. Her iki
anotasyon da siniflarin nesnelerini olusturmak icin kolay bir yol saglar, ancak bazi temel farkliliklari vardir. Iste
her ikisinin de temel ozellikleri:

1. **@Builder:** Bu anotasyon, Lombok tarafindan saglanir ve sinifin uzerine eklendiginde, derleme zamaninda o sinifa
   bir Builder sinifi ekler. Bu Builder sinifi, sinifin tum alanlarini icerir ve bu alanlari kullanarak nesneleri
   olusturmaniza olanak tanir. Ancak, bu sinifin ust siniflardan gelen alanlarla basa cikma yetenegi sinirlidir.
2. **@SuperBuilder:** Bu anotasyon da Lombok tarafindan saglanir ve `@Builder`'in genisletilmis bir versiyonudur. Bu
   anotasyon, sinifin uzerine eklendiginde, derleme zamaninda o sinifa bir Builder sinifi ekler. Bu Builder sinifi,
   sinifin tum alanlarini icerir ve ayrica ust siniflardan gelen alanlarla basa cikabilir. Bu, miras alinan siniflarla
   calisirken builder desenini kullanmayi daha kolay hale getirir.

Genel olarak, `@SuperBuilder`'in `@Builder`'dan daha guclu bir versiyonu oldugunu soyleyebiliriz. `@SuperBuilder`, ust
siniflardan gelen alanlarla calisirken daha esneklik ve kolaylik saglar. Bu nedenle, miras alinan siniflarin builder
desenini kullanirken `@SuperBuilder` tercih edilebilir.

</details>

<details>

<summary>@Transactional anotasyonu nedir? @Transactional anotasyonunda propagation type'lar nelerdir?</summary>

`@Transactional` anotasyonu, Spring Framework tarafindan saglanan bir islem yonetimi anotasyonudur. Bu anotasyon, bir
metodu veya bir servis sinifini saran bir islem icinde calistirmak icin kullanilir. Islem (transaction), bir dizi
veritabani islemini (ornegin, ekleme, guncelleme, silme) tek bir mantiksal islem olarak ele alir ve bu islemlerin
atomik (tamamlayici), tutarli, izole edilmis ve kalici olmasini saglar.

`@Transactional` anotasyonu ayni zamanda `propagation` (yayilma) parametresini kullanarak islemlerin nasil yayilacagini
belirlemenize olanak tanir. Propagation tipi, bir islem icinde baska bir islem cagrildiginda, cagrilan islemin var olan
islemle nasil etkilesime girecegini belirtir. Iste propagation type'lar:

1. **REQUIRED:**
    * **Aciklama:** Eger bir transaction zaten mevcutsa, mevcut transactionde devam eder. Aksi takdirde yeni bir
      transaction baslatir.
    * **Kullanim:** `@Transactional(propagation = Propagation.REQUIRED)`
2. **SUPPORTS:**
    * **Aciklama:** Mevcut bir transaction icinde calisir. Ancak, mevcut bir transaction yoksa transaction baslatmaz.
    * **Kullanim:** `@Transactional(propagation = Propagation.SUPPORTS)`
3. **MANDATORY:**
    * **Aciklama:** Bir transaction icinde calisir. Ancak, mevcut bir transaction yoksa bir istisna firlatilir.
    * **Kullanim:** `@Transactional(propagation = Propagation.MANDATORY)`
4. **REQUIRES\_NEW:**
    * **Aciklama:** Her zaman yeni bir transaction baslatir, var olan bir transaction varsa bu transactioni askiya alir.
    * **Kullanim:** `@Transactional(propagation = Propagation.REQUIRES_NEW)`
5. **NOT\_SUPPORTED:**
    * **Aciklama:** Her zaman mevcut bir transaction icinde calisir. Ancak, bu transactioni askiya alir.
    * **Kullanim:** `@Transactional(propagation = Propagation.NOT_SUPPORTED)`
6. **NEVER:**
    * **Aciklama:** Her zaman mevcut bir transaction icinde calisir. Ancak, mevcut bir transaction varsa bir istisna
      firlatilir.
    * **Kullanim:** `@Transactional(propagation = Propagation.NEVER)`
7. **NESTED:**
    * **Aciklama:** Var olan bir transaction icinde calisir, ancak ic ice gecmis bir transaction olarak ele alinir. Eger
      distaki transaction commit edilirse, icteki transaction de commit edilir.
    * **Kullanim:** `@Transactional(propagation = Propagation.NESTED)`

</details>

<details>

<summary>JpaRepository, CrudRepository vs PagingeAndSortingRepository fark?</summary>

* CrudRepository sadece Crud işlemlerini barındırır.
* PagingAndSortingRepository sadece sıralama ve sayfalama fonksiyonlarını barındırır.
* JpaRepository, CrudRepository ve PagingAndSortingRepository sahip olduğu tüm fonksiyonları barındırır.

</details>

<details>

<summary>Entity Inheritance’ın Püf Noktaları (@MappedSuperclass,@Inheritance,@DiscriminatorValue)</summary>

[https://medium.com/kodgemisi/entity-inheritance%C4%B1n-p%C3%BCf-noktalar%C4%B1-65ed7fdf93c](https://medium.com/kodgemisi/entity-inheritance%C4%B1n-p%C3%BCf-noktalar%C4%B1-65ed7fdf93c)

</details>

---

### *Hibernate*

<details>

<summary>orm nedir?</summary>

ORM (Object-Relational Mapping), ilişkisel veritabanıyla nesne tabanlı programlama arasındaki uyumu sağlayan bir yazılım
tasarımı ve programlama tekniğidir. ORM, veritabanı tablolarını nesne modele dönüştürmeyi ve veritabanı işlemlerini
nesne tabanlı olarak gerçekleştirmeyi sağlar.

</details>

<details>

<summary>jpa nedir?</summary>

JPA (Java Persistence API), Java tabanlı uygulamalarda nesne tabanlı veri erişimi için bir API'dir. JPA, veritabanı
işlemlerini gerçekleştirmek için ORM (Object-Relational Mapping) prensibine dayanır. ORM, ilişkisel veritabanı ile nesne
tabanlı programlama arasındaki uyumu sağlar ve veritabanı işlemlerini nesneler üzerinden yapmayı mümkün kılar.

JPA, veritabanı tablolarını Java sınıflarıyla eşleştirir ve veritabanı işlemlerini gerçekleştirmek için
standartleştirilmiş bir yöntem seti sunar. Bu sayede, geliştiriciler veritabanı işlemlerini SQL sorgularıyla değil,
JPA'nın sağladığı API ile yapabilir. JPA, veri okuma, yazma, güncelleme ve silme gibi temel CRUD (Create, Read, Update,
Delete) işlemlerini kolaylaştırır ve veritabanı işlemlerinin daha hızlı ve daha sürdürülebilir bir şekilde
gerçekleştirilmesini sağlar.

JPA'nın popüler uygulamalarından biri Hibernate'dir. Hibernate, JPA spesifikasyonunu uygulayan ve JPA tabanlı veri
erişimini sağlayan bir ORM çözümüdür.

Persistence, bilgisayar programlamasında verinin kalıcı bir şekilde saklanması ve erişilebilir olması anlamına gelir.

</details>

<details>

<summary>hibernate nedir?</summary>

JPA'nın popüler uygulamalarından biri Hibernate'dir. Hibernate, JPA spesifikasyonunu uygulayan ve JPA tabanlı veri
erişimini sağlayan bir ORM çözümüdür.

</details>

<details>

<summary>JPA (Java Persistence API) ve JPA Repository, Spring Framework ile birlikte kullanılan veritabanı erişim teknolojileridir. İkisi arasındaki fark?</summary>

Özet olarak, JPA Java tabanlı uygulamalarda veritabanı erişimi sağlayan bir spesifikasyonken, JPA Repository ise Spring
Data JPA tarafından sunulan ve JPA teknolojisini kullanarak veritabanı işlemlerini kolaylaştıran bir bileşendir. JPA
Repository, CRUD işlemlerini otomatik olarak sağlar ve özel sorguların tanımlanmasını kolaylaştırır.

</details>

<details>

<summary>Hibernate'de Fetch typelar nelerdir? Açıklayabilir misin?</summary>

Hibernate, Java tabanlı bir ORM (Object-Relational Mapping) çerçevesidir ve veritabanı işlemlerini kolaylaştırır. Fetch
türleri, Hibernate'de nesne ilişkileri ve ilişkili verilerin nasıl alınacağını belirtmek için kullanılan kavramlardır.
İşte Hibernate'de kullanılan fetch türlerinin açıklamaları:

1. `FetchType.LAZY`:
    * Bu fetch türü, ilişkili verilerin gerektiğinde yani kullanıldığında yüklenmesini sağlar.
    * İlişkili veriler, ilgili nesneye erişilmeye çalışıldığında veya verilerin çağrılması gerektiğinde yüklenir.
    * Bu, performans açısından faydalı olabilir çünkü ilişkili veriler yalnızca ihtiyaç duyulduğunda getirilir ve
      gereksiz yüklenme önlenebilir.
2. `FetchType.EAGER`:
    * Bu fetch türü, ilişkili verilerin ana nesne yüklenirken hemen yüklenmesini sağlar.
    * İlişkili veriler, ana nesnenin yüklendiği aşamada otomatik olarak getirilir.
    * İhtiyaç duyulmasa bile tüm ilişkili veriler yüklenir, bu nedenle büyük veri kümesi veya performans endişeleri
      oluşabilir.
3. `FetchType.DEFAULT`:
    * Bu fetch türü, belirli bir fetch türü belirtilmediğinde varsayılan olarak kullanılır.
    * Genellikle `FetchType.LAZY` ile aynıdır, yani ilişkili veriler gerektiğinde yüklenir.

Fetch türleri, Hibernate'in ilişkili nesneleri veritabanından nasıl getireceğini belirler. `LAZY` fetch türü, veri
erişimini daha tembel bir şekilde yapar ve performansı artırabilirken, `EAGER` fetch türü, ilişkili verileri hemen
getirerek veritabanı erişimlerini artırabilir. Seçilecek olan fetch türü, uygulamanın ihtiyaçlarına ve performans
gereksinimlerine bağlıdır.

Fetch türleri, genellikle Hibernate'de ilişkili nesneler arasında `@OneToMany`, `@OneToOne`, `@ManyToMany` gibi ilişki
annotasyonları kullanıldığında belirtilir. Bu annotasyonlar üzerinde `fetch` parametresi kullanılarak fetch türü
belirtilebilir.

Örneğin:

```java

@Entity
public class Order {
    // ...
    @OneToMany(fetch = FetchType.LAZY)
    private List<OrderItem> items;
    // ...
}
```

Bu örnek, `Order` sınıfında `OrderItem` ile `@OneToMany` ilişkisinin olduğunu ve ilişkili verilerin `LAZY` fetch türüyle
yükleneceğini belirtir.

---
Hibernate, Java'da bir ORM (Object-Relational Mapping) aracidir ve veritabani islemlerini nesne yonelimli programlama (
OOP) modeline entegre etmek icin kullanilir. Fetch tipi (Fetch Type), bir Hibernate iliskisi tanimlandiginda, bu
iliskinin iliskilendirilmis nesnelerin nasil alinacagini belirleyen bir ozelliktir. Iki temel fetch tipi vardir: Eager
Fetching ve Lazy Fetching.

1. **Eager Fetching (Istahli Alim):**

    * Eager Fetching, bir iliskiye ait iliskilendirilmis nesnelerin, ana nesneyle birlikte hemen alinmasi anlamina
      gelir. Yani, bir sorgu calistirildiginda, iliskili nesneler de aninda yuklenir.
    * Ornegin, bir `@ManyToOne` iliskisi icin Eager Fetching kullanildiginda, bir nesne alindiginda bu nesnenin iliskili
      oldugu diger nesneler de otomatik olarak alinir.
    * Eager Fetching kullanimi, performans sorunlarina neden olabilir, cunku iliskili nesneleri surekli olarak almak,
      gereksiz veri alimina ve performans kaybina yol acabilir.

   ```java
   @Entity
   public class Author {
       // ...
       @OneToMany(mappedBy = "author", fetch = FetchType.EAGER)
       private List<Book> books;
       // ...
   }
   ```
2. **Lazy Fetching (Tembel Alim):**

    * Lazy Fetching, bir iliskiye ait iliskilendirilmis nesnelerin, ana nesne uzerinden erisilmeye calisildiginda
      alinmasi anlamina gelir. Yani, iliskili nesneler yalnizca ihtiyac duyuldugunda yuklenir.
    * Lazy Fetching, performansi artirabilir cunku iliskili nesneler, ihtiyac duyulmadikca yuklenmez. Ancak, kullanici
      tarafindan dikkatli bir sekilde yonetilmelidir, aksi takdirde "LazyInitializationException" gibi sorunlar ortaya
      cikabilir.

   ```java
   @Entity
   public class Author {
       // ...
       @OneToMany(mappedBy = "author", fetch = FetchType.LAZY)
       private List<Book> books;
       // ...
   }
   ```

Fetch tipi, belirli bir Hibernate iliskisi uzerinde nasil veri alindigini kontrol etmek icin onemlidir. Eager Fetching
ve Lazy Fetching'in her birinin avantajlari ve dezavantajlari vardir, ve secim genellikle uygulamanin ihtiyaclarina ve
performans gereksinimlerine baglidir.

</details>

<details>

<summary>Hibernate “Lazy Initialization Exception” Nedir?</summary>

    https://medium.com/@metinalniacik/hibernate-lazy-initialization-exception-hatas%C4%B1-ve-onun-%C3%A7%C3%B6z%C3%BCm%C3%BC-38515c4f98d0

Hibernate "LazyInitializationException", Hibernate'in tembel yukleme (lazy loading) stratejisini kullandigi durumlarda
ortaya cikan bir istisnadir. Tembel yukleme, bir iliskilendirilmis nesnenin (ornegin, bir koleksiyon veya baska bir
iliskili varlik) sadece kullanildigi zaman yuklenmesini saglayan bir stratejidir. Bu, performansi artirmak ve gereksiz
veritabani sorgularini onlemek icin kullanilir.

Ancak, eger Hibernate bir nesnenin tembel yuklenmesini gerceklestirirken ilgili Hibernate oturumu (session) kapandiysa
veya nesne oturum disinda kullanilmaya calisiliyorsa, "LazyInitializationException" ortaya cikar. Bu durumda, Hibernate
tembel yuklenen nesneyi almak icin gerekli olan veritabani sorgularini gerceklestiremez cunku oturum kapalidir.

Bu durumu anlamak icin su ornek dusunulebilir:

```java

@Entity
public class Author {
    @Id
    @GeneratedValue(strategy = GenerationType.IDENTITY)
    private Long id;

    private String name;

    @OneToMany(mappedBy = "author", fetch = FetchType.LAZY)
    private List<Book> books;

    // getter ve setter metotlari
}

@Entity
public class Book {
    @Id
    @GeneratedValue(strategy = GenerationType.IDENTITY)
    private Long id;

    private String title;

    @ManyToOne(fetch = FetchType.LAZY)
    @JoinColumn(name = "author_id")
    private Author author;

    // getter ve setter metotlari
}
```

Yukaridaki ornekte, `Author` sinifinda `books` adinda tembel yuklenen bir koleksiyon bulunmaktadir. Eger bir `Author`
nesnesi yaratilip Hibernate oturumu kapandiktan sonra, bu nesnenin tembel yuklenen koleksiyonu olan `books`'a erisilmeye
calisilirsa, "LazyInitializationException" alinabilir:

```java
// Hibernate oturumu acilir
Session session=sessionFactory.openSession();
        Transaction tx=session.beginTransaction();

        Author author=session.get(Author.class,1L);

// Hibernate oturumu kapatilir
        session.close();

// Asagidaki satir "LazyInitializationException" hatasina neden olabilir
        List<Book> books=author.getBooks();
```

Bu hatayi onlemek icin birkac yaklasim vardir:

1. **Eager Loading (Ileri Yukleme):** Iliskili nesneleri oturum icinde aninda yukleyerek bu hatayi onleyebilirsiniz.
   Ancak bu, performans sorunlarina yol acabilir cunku tum iliskili nesneleri her zaman yuklemeniz gerekebilir.

    ```java
    @ManyToOne(fetch = FetchType.EAGER)
    ```

2. **Oturum Acikken Calisma (Open Session in View):** Hibernate oturumunun bir HTTP istegi boyunca acik kalmasini
   saglayarak bu hatayi cozebilirsiniz. Ancak, bu yontem bazi durumlarda guvenlik ve performans sorunlarina neden
   olabilir.

3. **DTO (Data Transfer Object) Kullanma:** Iliskili nesneleri yuklemek yerine sadece gerekli verileri iceren bir DTO
   kullanabilirsiniz.

4. **Hibernate.initialize() Metodu:** Iliskili nesneleri elle yuklemek icin Hibernate'in `initialize()` metodunu
   kullanabilirsiniz.

    ```java
    Hibernate.initialize(entity.getRelatedObject());
    ```

Hangi yontemin kullanilacagi uygulamanin ihtiyaclarina ve gereksinimlerine baglidir.

</details>

<details>

<summary>Hibernate N+1 problemi nedir ?</summary>

Hibernate N+1 problemi, bir ORM (Object-Relational Mapping) aracı olan Hibernate'in performansla ilgili bir sorunudur.
Bu problem, ilişkisel veritabanı tabloları arasındaki ilişkilerin getirilmesi sırasında ortaya çıkar ve genellikle
birleştirilmiş sorgu (join fetch) veya entity graph kullanılmadığında meydana gelir.

N+1 problemi şu şekilde özetlenebilir: Bir ana nesne (örneğin, bir Entity sınıfı) alındığında, bu ana nesnenin ilişkili
olduğu diğer nesneler ayrı ayrı sorgularla çekilir. Bu durumda, birinci sorgu ana nesneyi getirirken, N adet ek sorgu,
bu ana nesnenin ilişkili olduğu diğer nesneleri getirir. Bu durumu bir örnek üzerinden açıklayalım.

```java

@Entity
public class Author {
    @Id
    @GeneratedValue(strategy = GenerationType.IDENTITY)
    private Long id;

    private String name;

    @OneToMany(mappedBy = "author", fetch = FetchType.LAZY)
    private List<Book> books;

    // Getter ve Setter metotları
}

@Entity
public class Book {
    @Id
    @GeneratedValue(strategy = GenerationType.IDENTITY)
    private Long id;

    private String title;

    @ManyToOne
    @JoinColumn(name = "author_id")
    private Author author;

    // Getter ve Setter metotları
}
```

Yukarıdaki örnekte, `Author` sınıfı ile `Book` sınıfı arasında One-to-Many ilişkisi bulunmaktadır. Bir yazarın tüm
kitaplarını getirmek için şu şekilde bir sorgu yapılabilir:

```java
List<Author> authors=entityManager.createQuery("SELECT a FROM Author a",Author.class).getResultList();

        for(Author author:authors){
        System.out.println("Author: "+author.getName());

        for(Book book:author.getBooks()){
        System.out.println("Book: "+book.getTitle());
        }
        }
```

Bu sorgu, ilk olarak tüm yazarları getirir (1. sorgu). Ancak, her bir yazarın kitaplarına ulaşmak için ayrı ayrı
sorgular yapılır (N adet sorgu). Bu durumda, toplamda N+1 sorgusu gerçekleşir.

N+1 probleminden kaçınmak için genellikle şu yöntemler kullanılır:

1. **Eager veya Lazy Yüklenme Ayarları:**
    - İlişkili varlıkları getirirken FetchType.EAGER veya FetchType.LAZY ayarlarını kullanarak hangi durumlarda ilişkili
      varlıkların getirileceğini belirleyebilirsiniz.

2. **Birleştirilmiş Sorgular (Join Fetch):**
    - İlişkili varlıkları tek bir sorguda getirmek için birleştirilmiş sorgular (join fetch) kullanabilirsiniz. Bu, N+1
      problemini önler ve performansı artırır.

---

Hibernate N+1 problemi, bir nesne ilişkisel eşlemesi (object-relational mapping - ORM) aracı olan Hibernate'in
performans sorunlarına neden olan bir durumu ifade eder. Bu sorun, ilişkili nesnelerin veritabanından alınması için
gereken sorgu sayısının aşırı artmasıyla ortaya çıkar.

Örneğin, bir ilişkisel veritabanında "Kitap" ve "Yazar" tabloları olduğunu düşünelim. Her bir kitap bir yazar tarafından
yazılmıştır ve bu nedenle "Kitap" tablosu ile "Yazar" tablosu arasında bir ilişki vardır. Hibernate, bu ilişkiyi
kullanarak bir kitabı alırken ilişkili yazar bilgilerini de getirebilir.

N+1 problemi, bir sorgu yürütüldüğünde Hibernate'in önce ana tabloyu (örneğin "Kitap" tablosu) sorgulaması ve ardından
her bir kitap için ayrı ayrı yazarın bilgilerini almak için ek sorgular yürütmesiyle ortaya çıkar. Bu durumda, N sayısı
kitap sayısına eşittir ve her bir kitap için 1 adet ek sorgu yürütülür. Bu, veritabanı üzerinde gereksiz yük oluşturur
ve performansı düşürebilir.

Hibernate'de N+1 problemi çözmek için birkaç yaklaşım vardır:

1. Eager loading (acele yükleme): İlişkili verilerin önceden yüklenmesini sağlayarak, ek sorguların önüne
   geçebilirsiniz. Örneğin, sorgunuzu Hibernate'in `fetch` özelliğini kullanarak ilişkili verilerin otomatik olarak
   yüklenmesini sağlayabilirsiniz.
2. Lazy loading (geç yükleme): İlişkili verileri talep edildiği anda yüklemek için tembel yükleme kullanabilirsiniz.
   Hibernate, ilişkili verileri gerektiğinde yükler ve böylece gereksiz sorgu sayısını azaltır.
3. Batch loading (toplu yükleme): Hibernate, veritabanından toplu olarak veri getirmek için `@BatchSize`
   veya `@OneToMany` gibi özellikleri kullanabilirsiniz. Bu, bir sorguda birden çok nesnenin verilerini getirerek
   performansı artırabilir.
4. Join fetch: İlişkili verileri tek bir sorguda getirmek için `JOIN FETCH` ifadesini kullanabilirsiniz. Bu, N+1
   probleminden kaçınmanın etkili bir yoludur.

</details>

<details>

<summary>Spring Boot JPA kullanilarak veritabani islemleri gerceklestirirken, neden Java Records siniflarini entity olarak kullanmakta zorlaniriz?</summary>

Spring Boot ile JPA (Java Persistence API) kullanilarak veritabani islemleri gerceklestirirken, Java Records siniflarini
entity olarak kullanmakta zorlanma durumu, Records'in bazi ozellikleri ve JPA'nin beklentileri arasindaki
uyumsuzluklardan kaynaklanabilir. Iste bu zorluklari anlamak icin bazi nedenler:

1. **Records'in Immutable (Degistirilemez) Dogasi:**
    - Records, immutable yani degistirilemez nesnelerdir. Bu ozellik, JPA'nin entity siniflarinda genellikle sahip
      olunan mutable (degistirilebilir) nesneler ile cakisabilir. JPA, entity siniflarindaki alanlarin get ve set
      metotlarina erisim saglamayi beklerken, Records'lar otomatik olarak final alanlar ve get metotlari olusturur. Bu
      durum, JPA'nin bekledigi standart getter ve setter yapilarina uymayabilir.

2. **Records'in Ozel Metotlari:**
    - Records, otomatik olarak equals(), hashCode(), ve toString() gibi ozel metotlari olusturur. Ancak, bu metotlar
      entity siniflarinda ozel bir sekilde uygulandiginda JPA'nin beklentileriyle cakisabilir. Ozellikle, JPA'nin entity
      siniflarinda equals ve hashCode metotlarinin ozel bir sekilde implement edilmesi gerekebilir.

3. **JPA Lifecycle Yonetimi:**
    - JPA, entity siniflarinin yasam dongusunu yonetir. Records siniflari, otomatik olarak bir builder metodu
      olusturdugu icin JPA'nin bu yasam dongusu yonetimine uygun olmayabilir.

4. **Proxy Olusturma:**
    - JPA, lazy loading gibi ozellikleri kullanabilmek icin proxy nesneler olusturabilir. Records siniflari, final
      alanlara sahip oldugu icin bu tur proxy olusturma mekanizmalari ile uyumsuz olabilir.

Bu sorunlardan dolayi, Spring Boot JPA projelerinde genellikle daha geleneksel sinif yapilari veya JavaBeans kullanimi
tercih edilir. Ancak, Java Records'larin kullanimi ve JPA entegrasyonu konusundaki destek ilerleyen donemlerde
gelisebilir, bu nedenle guncel dokumantasyon ve versiyonlara goz atmak her zaman faydali olacaktir.
</details>

---

### *Veritabani*

<details>

<summary>DAO nedir?</summary>

DAO, Data Access Object'ın kısaltmasıdır. Bu, bir yazılım uygulaması ile veritabanı arasındaki iletişimden sorumlu olan
bir tasarım desenidir. DAO, uygulamanın veritabanına bağımlılığını azaltmak ve uygulama kodunu daha okunaklı, bakımı
kolay ve test edilebilir hale getirmek için kullanılır.

Dao da crud islemleri yapilir

</details>

<details>

<summary>Iliskisel (relational) ve iliskisel olmayan (non-relational veya NoSQL) veritabanlari arasindaki temel farklar  nedir?</summary>

Iliskisel (relational) ve iliskisel olmayan (non-relational veya NoSQL) veritabanlari arasindaki temel farklar
sunlardir:

**Iliskisel Veritabanlari:**

1. **Yapisi:** Iliskisel veritabanlari tablolardan olusur ve bu tablolar arasinda iliskiler vardir. Genellikle SQL (
   Structured Query Language) kullanilarak sorgulanir.
2. **Sema:** Iliskisel veritabanlari, veri semasina sahiptir. Bu, veri yapisinin onceden tanimlanmis ve belirlenmis bir
   yapiya sahip oldugu anlamina gelir. Ornek olarak, bir MySQL veya PostgreSQL veritabani iliskisel bir veritabanidir.
3. **ACID Ilkeleri:** Iliskisel veritabanlari ACID (Atomicity, Consistency, Isolation, Durability) ilkelerine uyar ve bu
   da veritabaninin guvenilirligini saglar. ACID, veri butunlugunu ve guvenilirligini korumak icin tasarlanmis bir dizi
   ozelliktir.
4. **Kullanim Alanlari:** Iliskisel veritabanlari genellikle karmasik sorgulara ve tablolar arasi iliskilere ihtiyac
   duyulan durumlar icin uygundur. Is transaksiyonlari, finansal uygulamalar ve genel is uygulamalari gibi alanlarda
   yaygin olarak kullanilir.

**Iliskisel Olmayan (NoSQL) Veritabanlari:**

1. **Yapisi:** Iliskisel olmayan veritabanlari genellikle belgelere, anahtar-deger ciftlerine, sutun tabanli yapiya veya
   grafiklere dayanabilir. JSON, BSON gibi formatlari kullanabilirler.
2. **Sema:** Iliskisel olmayan veritabanlari genellikle semasizdir veya esnek bir semaya sahiptir. Yeni veri alanlari
   eklemek veya mevcut alanlari degistirmek daha esnektir.
3. **ACID Ilkeleri:** Iliskisel olmayan veritabanlari genellikle ACID yerine CAP teoremine (Consistency, Availability,
   Partition Tolerance) dayanir. Bu, sistemlerin tutarlilik, erisilebilirlik ve bolumlenmis aglara dayaniklilik arasinda
   bir denge kurdugu anlamina gelir.
4. **Kullanim Alanlari:** Iliskisel olmayan veritabanlari, buyuk veri, dagitik sistemler, hizli ve olceklenebilir veri
   depolama ihtiyaci olan projelerde daha yaygin olarak kullanilir. Ornegin, MongoDB (belge tabanli), Redis (
   anahtar-deger tabanli) ve Cassandra (sutun tabanli) gibi veritabanlari iliskisel olmayan veritabanlarina ornektir.

**Hangi Durumlarda Hangisini Kullanmali:**

* Iliskisel veritabanlari, karmasik sorgulara ve tablolar arasi iliskilere ihtiyac duyulan geleneksel is uygulamalari ve
  transaksiyonel sistemler icin uygun olabilir.
* Iliskisel olmayan veritabanlari, buyuk veri, dagitik sistemler, hizli ve olceklenebilir veri depolama ihtiyaci olan
  projeler icin daha uygun olabilir.

Genellikle, projenin gereksinimleri, veri yapisi ve olceklenebilirlik ihtiyaclari, iliskisel veya iliskisel olmayan
veritabani seciminde belirleyici olabilir.

</details>

<details>

<summary>Database 'de DML ve DDL nedir?</summary>

DDL (Data Definition Language) ve DML (Data Manipulation Language), veritabani yonetim sistemlerinde kullanilan iki
farkli SQL dilidir. Her biri farkli amaclara hizmet eder ve belirli veritabani islemlerini gerceklestirmek icin
kullanilir.

1. **DDL (Data Definition Language - Veri Tanimlama Dili):**
    * DDL, veritabani semasini tanimlamak, degistirmek ve silmek icin kullanilir. Bu tur komutlar veritabani yapisini
      olusturan nesneleri (tablo, indeks, view, trigger vb.) tanimlar ve yonetir.
    * DDL komutlari genellikle asagidaki gibi ifadeler icerir: `CREATE`, `ALTER`, `DROP`.
    * Ornek DDL komutlari:
        * Tablo olusturma: `CREATE TABLE my_table (id INT, name VARCHAR(255));`
        * Tablo degistirme: `ALTER TABLE my_table ADD COLUMN age INT;`
        * Tablo silme: `DROP TABLE my_table;`
2. **DML (Data Manipulation Language - Veri Manipulasyon Dili):**
    * DML, veritabanindaki verileri sorgulamak, eklemek, guncellemek ve silmek icin kullanilir. Temel amaci, veritabani
      icindeki kayitlarla etkilesimde bulunmaktir.
    * DML komutlari genellikle asagidaki gibi ifadeler icerir: `SELECT`, `INSERT`, `UPDATE`, `DELETE`.
    * Ornek DML komutlari:
        * Veri sorgulama: `SELECT * FROM my_table WHERE age > 18;`
        * Veri ekleme: `INSERT INTO my_table (id, name, age) VALUES (1, 'John', 25);`
        * Veri guncelleme: `UPDATE my_table SET age = 26 WHERE name = 'John';`
        * Veri silme: `DELETE FROM my_table WHERE id = 1;`

DDL ve DML, bir veritabanini olusturmak, degistirmek ve sorgulamak icin temel araclardir. Ikisi birbirinden farkli
islevlere sahiptir ve genellikle farkli baglamlarda kullanilirlar.

</details>

<details>

<summary>Normalizasyon Kurallari nelerdir? ve Ornek bir db tasarimi</summary>

Normalizasyon; veri tabanı tasarım aşamasında veri tekrarını, veri kaybını veya veri yetersizliğini önlemek için
gerçekleştirilen işlemlerdir.

Normalizayon uygulanan veri tabanlarının performansı artar, sabit diskteki boyutu azalır ve tablolarda ki satır ve sütun
sayısı azalacağından veri tekrarı önlenmiş olur. Özellikle silme, güncelleme gibi işlemler de çıkabilecek sorunlar büyük
oranda azaltılmış olur.

* Normalizasyon Yapilmadan:

  Filmler

  | Film Adi              | Aciklamasi | Yonetmen | Kategori  | Tarih | Oyuncu 1 | Oyuncu 2 |
                                                                                      | --------------------- | ---------- | -------- | --------- | ----- | -------- | -------- |
  | Yuzuklerin Efendisi 1 | ...        | Peter    | Fantastik | 2001  | Orlando  | Elijah   |
  | Dovus Kulubu          | ...        | David    | Dram      | 1999  | Brad     | Edward   |
* Normalizasyon Yapilinca:

  Filmler

  | id | Film Adi              | Aciklamasi | Yonetmen | Kategori | Tarih |
                                                                                      | -- | --------------------- | ---------- | -------- | -------- | ----- |
  | 1  | Yuzuklerin Efendisi 1 | ...        | 1        | 1        | 2001  |
  | 2  | Dovus Kulubu          | ...        | 2        | 2        | 1999  |

  Yonetmenler

  | id | Ad    |
                                                                                      | -- | ----- |
  | 1  | Peter |
  | 2  | David |

  Kategori

  | id | Ad        |
                                                                                      | -- | --------- |
  | 1  | Fantastik |
  | 2  | Dram      |

  Oyunucu

  | id | Ad      |
                                                                                      | -- | ------- |
  | 1  | Orlando |
  | 2  | Elijah  |
  | 3  | Brad    |
  | 4  | Edward  |

  Film Oyunculari

  | Film id | Oyuncu id |
                                                                                      | ------- | --------- |
  | 1       | 1         |
  | 1       | 2         |
  | 2       | 3         |
  | 2       | 4         |

</details>

---

### *Design Patterns*

<details>

<summary>Solid ilkeleri?</summary>

#### S— Single-responsibility principle

**ÖZET**: Single responsibility prensibi sınıflarımızın iyi tanımlanmış tek bir sorumluluğu olması gerektiğini
anlatmaktadır. Bir sınıf (nesne) yalnızca bir amaç uğruna değiştirilebilir, o amaçta o sınıfa yüklenen sorumluluktur,
yani bir sınıfın yapması gereken yalnızca bir işi olması gerekir.

or/ Elbise mağazası sınıfı, yalnızca elbise stoklarını takip etmek ve elbise satışlarıyla ilgilenmekle sorumludur.
Örneğin, elbiselerin stok seviyelerini güncellemek, yeni elbise eklemek, elbise satışlarını kaydetmek gibi işlemleri
yapabilir.

#### O— Open-closed principle

**ÖZET**: Bir sınıf ya da fonksiyon halihazırda var olan özellikleri korumalı ve değişikliğe izin vermemelidir. Yani
davranışını değiştirmiyor olmalı ve yeni özellikler kazanabiliyor olmalıdır.

or/ Elbise mağazası sınıfı, yeni elbiselerin eklenmesine açık olmalıdır. Yeni bir elbise türü eklenmek istendiğinde,
mevcut mağaza sınıfı değiştirilmeden yeni elbise türü sınıfı oluşturularak eklenir.

#### L— Liskov substitution principle

**ÖZET**: Kodlarımızda herhangi bir değişiklik yapmaya gerek duymadan alt sınıfları, türedikleri(üst)(ana) sınıfların
yerine kullanabilmeliyiz.

or/ Elbise mağazasında farklı türde elbiseler bulunabilir, örneğin elbiseler, gömlekler, pantolonlar gibi. Bu durumda,
her tür elbisenin kullanılabilirliği ve davranışları aynı olmalıdır. Yani, her tür elbise, mağaza işlemlerinde
birbirinin yerine geçebilmelidir.

#### I— Interface segregation principle

**ÖZET**: Sorumlulukların hepsini tek bir arayüze toplamak yerine daha özelleştirilmiş birden fazla arayüz
oluşturmalıyız.

or/ Elbise mağazası sınıfı, müşteriye satış yapmak, stok durumunu kontrol etmek ve raporlama gibi işlemleri
gerçekleştirebilir. Ancak, tüm bu işlemler için tek bir genel arayüz kullanmak yerine, müşteri satışları için ayrı bir
arayüz, stok kontrolü için ayrı bir arayüz ve raporlama için ayrı bir arayüz gibi daha özelleştirilmiş arayüzler
oluşturulabilir.

#### D— Dependency Inversion Principle

**ÖZET**: Sınıflar arası bağımlılıklar olabildiğince az olmalıdır özellikle üst seviye sınıflar alt seviye sınıflara
bağımlı olmamalıdır.

or/ Elbise mağazası sınıfı, doğrudan stok veritabanına veya satış işlemlerinin gerçekleştirildiği başka bir sınıfa
bağımlı olmamalıdır. Bunun yerine, bir arayüz üzerinden bağımlılık oluşturulabilir ve ilgili işlemler bu arayüz
üzerinden gerçekleştirilebilir. Bu sayede, farklı veritabanları veya satış işlemlerini gerçekleştiren farklı sınıflar,
bu arayüzü uygulayarak kullanılabilir hale gelir.

</details>

<figure><img src="assets/solid.gif" alt=""><figcaption></figcaption></figure>

<details>

<summary>clean code ?</summary>

1. İsimlendirme:
2. Fonksiyon Boyutu:
3. Tek Sorumluluk İlkesi:
4. Kod Duplicasyonunun Önlenmesi:
5. Fonksiyon ve Sınıf Boyutu:
6. Yorum Kullanımı:
7. Test Edilebilirlik:
8. Bir fonksiyon birden fazla iş yapmamalı

</details>

<details>

<summary>CAP teoremi nedir?</summary>

CAP teoremi (Consistency, Availability, Partition Tolerance), bir dagitik sistemde uc onemli ozelligi tanimlayan bir
teoremidir. Bu uc ozellik sunlardir:

1. **Consistency (Tutarlilik):**
    * Her dugumun ayni veriyi ayni anda gormesini ifade eder. Tutarlilik, bir yazma islemi tamamlandiginda, okuma
      islemleri tarafindan hemen yansitilmalidir.
2. **Availability (Erisilebilirlik):**
    * Her istekte bir cevap alinmalidir. Sistem her zaman calisir durumda olmali ve kullanicilarin isteklerine cevap
      verebilmelidir.
3. **Partition Tolerance (Bolum Toleransi):**
    * Bir sistemde bir veya birden fazla dugum arasindaki iletisim kayboldugunda bile sistem calismaya devam etmelidir.
      Sistemdeki bir dugumun veya ag baglantisinin kopmasi durumunda bile diger dugumlerle iletisim surdurulmelidir.

CAP teoremi, bir dagitik sistemde bu uc ozelligin ayni anda saglanamayacagini belirtir. Sistem tasariminda, bu
ozelliklerden en fazla ikisini bir arada saglayabilirsiniz. Bu durumu ifade etmek icin CAP teoremi, bir ucgen seklinde
gosterilir ve her iki kenarin bir arada olmadigi durumlar aciklanir.

* CA (Consistency, Availability): Bolge icindeki tum dugumlerle surekli tutarlilik saglanir ancak bolge bolundugunde
  erisilebilirlik azalabilir.
* CP (Consistency, Partition Tolerance): Bolge bolundugunde bile tutarlilik saglanir ancak bu durumda erisilebilirlik
  azalabilir.
* AP (Availability, Partition Tolerance): Bolge bolundugunde bile erisilebilirlik saglanir ancak bu durumda tutarlilik
  azalabilir.

CAP teoremi, sistem tasariminda uzlasma ve tercih yapma ihtiyacini vurgular. Farkli uygulamalar, ihtiyaclarina gore bu
ozellikler arasinda bir denge kurarlar.

</details>

<details>

<summary>Transaction Saga Pattern'e neden ihtiyac duyuyoruz ? </summary>

Dagitik sistemlerdeki islemlerin karmasikligi ve zorluklari, geleneksel monolitik sistemlerden farklidir. Bu nedenle,
tek bir buyuk islemi atomik bir sekilde gerceklestirmek yerine, buyuk islemleri kucuk, bagimsiz ve yonetilebilir
parcalara bolmek gerekir. Bu bagimsiz parcalar, dagitik sistemlerde "Saga Pattern" veya "Transaction Saga" kullanilarak
yonetilebilir. Iste Distribution Transaction Saga'nin neden ihtiyac duyuldugu ile ilgili bazi nedenler:

1. **Dagitik Islemlerin Karmasikligi:**
    * Dagitik sistemlerde, islemler genellikle birden cok servis arasinda bolunmus durumdadir. Bu durum, geleneksel
      monolitik sistemlerde oldugu gibi basit bir islem yapisini zorlastirir. Her servisin kendi baglamini ve
      sorumlulugunu tasidigi bir senaryoda, butunlugu saglamak daha karmasiktir.
2. **Bagimsizlik ve Skalabilite:**
    * Dagitik sistemlerdeki bagimsiz servislerin gelistirme, dagitim ve olceklendirme surecleri daha kolay olabilir.
      Fakat bu durum, islemlerin butunlugunu saglamak adina koordinasyon ve senkronizasyon mekanizmalarina ihtiyac
      duyulmasina neden olabilir.
3. **Hata Durumlarinin Yonetimi:**
    * Dagitik sistemlerde hata durumlari daha sik gorulebilir. Bu durumda, bir islemde bir hata meydana geldiginde,
      islemi geri almak veya duzeltmek icin koordineli bir yaklasim gerekebilir. Transaction Saga, hata durumlarini
      yonetme ve islemleri geri alma yetenekleri sunar.
4. **Performans ve Olceklenebilirlik:**
    * Dagitik sistemlerin performans ve olceklenebilirlik avantajlarindan yararlanmak icin, buyuk islemleri kucuk
      parcalara bolme ve paralel olarak isleme koyma ihtiyaci vardir. Transaction Saga, bu parcalar arasinda
      koordinasyonu saglar.
5. **Asenkron ve Uzun Sureli Islemler:**
    * Dagitik sistemlerde asenkron ve uzun sureli islemlerle daha sik karsilasilir. Transaction Saga, bu tur islemlerin
      yonetilmesini kolaylastirir.

Transaction Saga, bir dizi adimin (islem) basariyla tamamlanmasi veya bir hata durumunda geri alinmasi gereken
senaryolarda, dagitik sistemlerde islemlerin daha etkili bir sekilde yonetilmesini saglayan bir desen ve yonetim
modelidir.

</details>

<details>

<summary>CQRS Pattern'e neden ihtiyac duyuyoruz ?</summary>

CQRS (Command Query Responsibility Segregation), bir yazilim mimarisidir ve genellikle gelismis veya olceklenebilir
uygulamalarda kullanilir. Bu desenin temel amaci, bir uygulamanin yazma (komut) ve okuma (sorgu) islemlerini farkli
modellere ayirmaktir. Iste CQRS Design Pattern'e neden ihtiyac duydugumuzun bazi nedenleri:

1. **Performans ve Olceklenebilirlik:**
    * Geleneksel tek model mimarilerinde, yazma ve okuma islemleri genellikle ayni veri modelini paylasir. Bu durum,
      olceklenebilirlik ve performans konularinda sorunlara yol acabilir. CQRS, yazma ve okuma islemlerini farkli
      modellerde gerceklestirerek olceklenebilirlik sorunlarini azaltabilir.
2. **Farkli Veri Ihtiyaclari:**
    * Yazma (komut) islemleri genellikle sadece veri guncellemeleri yapar ve is kurallarini uygular. Ote yandan, okuma (
      sorgu) islemleri genellikle farkli veri ihtiyaclarina sahiptir ve ogrenilmis verilerin hizli bir sekilde
      alinmasini gerektirir. CQRS, bu farkli ihtiyaclari karsilamak icin uygun modellerin kullanilmasina olanak tanir.
3. **Is Kurallarinin Karmasikligi:**
    * Gelismis uygulamalarda is kurallari oldukca karmasik olabilir. CQRS, yazma tarafinda is kurallarini yonetirken,
      okuma tarafinda daha basit ve optimize edilmis modeller kullanilmasina olanak tanir.
4. **Daha Iyi Surdurulebilirlik:**
    * CQRS, yazma ve okuma islemlerini ayri model ve servislerde gerceklestirerek, her biri kendi alaninda
      degisikliklere izin verir. Bu, yazma islemlerinin ve okuma islemlerinin surdurulebilirligini artirabilir, cunku
      degisiklikler bir tarafi etkilemeden diger taraf uzerinde gerceklestirilebilir.
5. **Denetim ve Izleme Kolayligi:**
    * CQRS, yazma islemleri ve okuma islemleri arasinda ayrim yaparak, her iki tarafin denetimi ve izlenmesini
      kolaylastirir. Ornegin, okuma tarafindaki modeller uzerinde yapilan sorgularin performansini izlemek daha basit
      hale gelir.

CQRS, genellikle karmasik, buyuk olcekli ve ozel veri ihtiyaclarina sahip uygulamalarda kullanilir. Ancak, her uygulama
icin uygun olmayabilir ve dikkatli bir tasarim ve uygulama gerektirebilir. Bu nedenle, ihtiyaclara ve projenin
gereksinimlerine bagli olarak CQRS kullaniminin dusunulmesi onemlidir.

</details>

<details>

<summary>CQRS Kullanirken Iki Veritabanini Senkronize Etmenin Bir Yolu Olmadan Nasil Cozum Uretirsiniz?</summary>

"Debezium" ve "Kafka Connect" gibi araclari kullanarak, veritabanlari arasinda gercek zamanli veri senkronizasyonunu
saglayabilirsiniz. Bu araclar, veritabanlari arasinda degisiklikleri izlemek ve bunlari bir Kafka akisina donusturmek
icin kullanilir.

</details>

<details>

<summary>Outbox Pattern'e neden ihtiyac duyuyoruz ?</summary>

Outbox Pattern, bir sistemdeki veri degisikliklerini ve olaylari kaydetmek icin kullanilan bir tasarim desenidir. Bu
desen, ozellikle dagitik sistemlerde, mikroservis mimarilerinde ve olaya dayali sistemlerde kullanislidir. Iste Outbox
Pattern'e neden ihtiyac duydugumuzun bazi nedenleri:

1. **Atomik Islemler:**
    * Outbox Pattern, islemleri atomik bir sekilde gerceklestirmeyi saglar. Bir islem icinde hem veritabanina yazma hem
      de mesaj kuyruguna bir olay gonderme gibi iki aksiyonun bir arada ve atomik bir sekilde yapilmasini saglar.
2. **Uygulama Durumu ve Veri Tutarliligi:**
    * Outbox Pattern, uygulama durumunu ve veri tutarliligini korumak icin kullanilir. Bir islem basarili bir sekilde
      gerceklestirildiginde, ilgili veri degisiklikleri ve olaylar guvenli bir sekilde kaydedilir. Eger bir hata meydana
      gelirse, islem geri alinabilir ve veri tutarliligi saglanabilir.
3. **Hassas Iliskiler:**
    * Veritabani guncellemeleri ve olay gonderimleri arasinda hassas bir iliski varsa, Outbox Pattern bu iliskiyi koruma
      konusunda yardimci olabilir. Ozellikle, bir olayin gonderilip gonderilmedigi ve gonderildiyse basariyla mi oldugu
      gibi durumlar hassas bir bicimde yonetilebilir.
4. **Sistematik Bir Yaklasim:**
    * Outbox Pattern, veritabani ve mesaj kuyrugu entegrasyonu gibi dagitik sistem tasarimlarinda sistematik bir
      yaklasim sunar. Bu tasarim, dagitik sistemlerdeki hata durumlarini, geri alma senaryolarini ve durum takibini
      kolaylastirir.
5. **Ileriye Donuk Uyum ve Esneklik:**
    * Outbox Pattern, sistemi gelecekteki degisikliklere karsi uyumlu hale getirir. Ornegin, bir olay gonderimi yapisi
      degisirse veya baska bir sistemle etkilesim bicimi degisirse, bu degisiklikleri Outbox Pattern uzerinden kolayca
      uygulayabilirsiniz.
6. **Mesaj Siralamasi:**
    * Outbox Pattern, mesajlarin sirasini garanti altina alabilir. Veritabaninda yapilan bir degisiklik ve ardindan
      gonderilen bir olay arasindaki sira, sistem tarafindan guvence altina alinabilir.

Outbox Pattern, sistemlerin daha guvenilir, tutarli ve esnek bir sekilde calismasini saglamak icin kullanilir. Bu
ozellikle dagitik sistemlerde, mikroservis mimarilerinde ve olaya dayali sistemlerde onemli bir rol oynar.

</details>

<details>

<summary>Circuit Breaker pattern nedir?</summary>

"Circuit Breaker" (Devre Kesici) tasarim deseni, bir yazilim sisteminin istikrarsiz veya hatali bir bileseni nedeniyle
devamli hata almasi durumunda sistemi korumak ve hatalarin yayilmasini engellemek amaciyla kullanilan bir desenidir. Bu
desen, ozellikle mikroservis mimarileri gibi dagitik sistemlerde kullanilan bir stratejidir.

Circuit Breaker deseni, geriye dusuk maliyetli bir hata kontrol stratejisi sunar. Calismayan bir sistem bileseni
nedeniyle surekli hatalar alindiginda, Circuit Breaker mekanizmasi devreye girer ve hatali bileseni gecici olarak izole
eder. Bu, hatalarin diger sistem bilesenlerine yayilmasini ve daha buyuk bir sistem hatasina neden olmasini engeller.

Circuit Breaker deseninin temel prensipleri sunlardir:

1. **Closed (Kapali) Durum:**
    * Baslangicta devre kapalidir ve normal islemler devam eder.
    * Sistemde hata orani belirli bir esigi astiginda devre acilir.
2. **Open (Acik) Durum:**
    * Devre acik durumda, hata orani asildigi icin sistem belirli bir sure boyunca hatalari tolere etmez.
    * Hatalarin yayilmasini onlemek icin devre acik durumda hata firlatilir.
3. **Half-Open (Yari Acik) Durum:**
    * Belirli bir sure sonra devre otomatik olarak yari acik duruma gecer.
    * Yari acik durumda, bir miktar trafik gecirilir ve sistemdeki hata durumu izlenir.

Circuit Breaker deseni, sistemin belirli bir hata esigini astiginda hatalari tolere eden, hata orani dustugunde tekrar
normal islemlere donen bir mekanizma saglar. Bu, hata toleransi ve sistem dayanikliligini artirir ve genellikle hata
durumlarinin daha kontrollu bir sekilde ele alinmasina olanak tanir.

Populer Java kutuphaneleri ve framework'ler, ozellikle mikroservis mimarileri icin Circuit Breaker desenini uygulamak
icin kullanilabilir. Bu araclar arasinda Netflix Hystrix, Resilience4j ve Spring Cloud Circuit Breaker bulunmaktadir.

</details>

<details>

<summary>Bir Servisten Gec Cevap Geldiginde Diger API'leri Etkilememek Icin Ne Yaparsiniz?</summary>

"Circuit breaker" tasarim desenini uygulayarak, hatali veya yavas hizmetlerin etkisini sinirlayabilirsiniz. Bu sayede
diger API'lerin etkilenmemesini saglamis olursunuz.

</details>

---

### *Microservices*

<details>

<summary>Spring Cloud nedir?</summary>

Spring Cloud, mikroservis mimarileri icin gelistirilmis bir projedir ve temelde dagitik sistemlerin gelistirilmesi ve
yonetilmesini kolaylastirmak uzere tasarlanmis bir dizi arac ve kutuphaneyi icerir. Iste Spring Cloud icinde sikca
kullanilan bazi bilesenlerden bazilari: Eureka Server, Config Server, Api Gateway Service

</details>

<details>

<summary>Spring Cloud Config Server nedir?</summary>

Spring Cloud Config Server, mikroservis mimarilerinde kullanilan bir bilesendir ve uygulama yapilandirma bilgilerini
merkezi bir konumdan yonetmek ve dagitmak icin kullanilir. Bu, mikroservis uygulamalarinin ortak bir yapilandirma
kaynagini kullanmasini saglar, bu da uygulama yapilandirmalarini merkezi bir konumda depolayarak ve guncelleyerek
sistemdeki tum servislerin ayni yapilandirmayi kullanmasina olanak tanir.

Spring Cloud Config Server'in temel ozellikleri sunlardir:

1. **Merkezi Konfigurasyon Depolama:**
    * Config Server, uygulama yapilandirma bilgilerini merkezi bir depoda (genellikle bir Git deposu) tutar. Bu depo,
      uygulama yapilandirma dosyalarini icerir ve servisler bu dosyalara Config Server uzerinden erisir.

    2. **Dinamik Yeniden Yukleme:**
        * Config Server, yapilandirma bilgileri guncellendiginde, servislerin dinamik olarak bu guncellemeleri almasini
          saglar. Bu sayede uygulamalar yeniden baslatilmadan, sadece Config Server'daki yapilandirma dosyalarini
          guncelleyerek sistemi yonetmek mumkun olur.
    3. **Cevre (Environment) ve Profil Destegi:**
        * Config Server, uygulama yapilandirmalarini cevre ve profil bazinda yonetme yetenegine sahiptir. Bu, farkli
          cevreler (development, production vb.) veya profiller (test, staging vb.) icin farkli yapilandirmalarin
          kullanilmasini saglar.
    4. **Yapilandirma Basvuru (Configuration References):**
        * Config Server, servislerin ihtiyac duydugu yapilandirma degerlerini belirli bir referans uzerinden almalarini
          saglar. Bu, servislerin sadece kendi ihtiyaclari olan yapilandirmalara odaklanmasini saglar.

Config Server, Spring Cloud projesinin bir parcasidir ve Spring Boot tabanlidir. Spring Cloud Config Server, mikroservis
mimarilerinde yapilandirma yonetimini kolaylastirarak sistemdeki servislerin tutarli bir sekilde yapilandirilmasini
saglar.

</details>

<details>

<summary>Spring Cloud Eureka Server nedir? </summary>

Bir mikroservis mimarisinde calisan tum mikroservislerin listesini tutar. Bu servislerin hangi IP adreslerinde
calistiklarini ve hangi portlardan erisebileceklerini bilir. Bu bilgi diger servisler tarafindan kullanilarak bir
servisin calistigi makineye baglanilabilir. Servislerin calisma durumunu izleyerek calismama durumunda diger servisleri
uyararak bu servis yerine baska bir servisin calismasini saglar. Mikroservis mimarisinde servisler arasi iletisimi
kolaylastirir. Eureka server bir REST API sunar. Bu API eureka server ‘ a kaydedilen mikroservislerin listesini dondurur
ve mikroservislerin durumunu izler. Sonuc olarak eureka server, bir mikroservis mimarisinde kullanilan bir servis
registry ‘ dir.

Spring Cloud Netflix Eureka'nin temel ozellikleri sunlardir:

1. Hizmet kaydi ve kesfi: Hizmetler, Eureka sunucusuna kaydedilir ve diger hizmetler bu sunucudan kayitli hizmetleri
   bulabilir.
    2. Yuk dengeleme: Eureka, yuk dengeleme islemlerini kolaylastirir ve hizmetler arasinda yuku dagitabilir.
    3. Hata toleransi: Eureka, sistemdeki hizmetlerin durumunu izler ve hata durumlarinda otomatik olarak yeniden
       dengeleme yapabilir.
    4. Dinamik olceklendirme: Eureka, yeni hizmetlerin otomatik olarak tespit edilmesini ve sistemdeki degisikliklere
       dinamik olarak uyum saglamayi mumkun kilar.
    5. Kendi kendine iyilestirme: Eureka, hizmetlerin durumunu izleyebilir ve gerektiginde sorunlari tespit edip
       cozebilir.

</details>

<details>

<summary>Spring Cloud Api Gateway Service nedir?</summary>

Spring Cloud Gateway, mikroservis mimarilerinde kullanilan bir API Gateway cozumudur. API Gateway, gelen istekleri alir,
belirli bir is mantigina gore yonlendirir ve ardindan uygun mikroservislere yonlendirir. Bu, istemcilerin birkac farkli
mikroservisi tek bir noktadan yonetmelerini saglar. Ayni zamanda API Gateway, kimlik dogrulama, yetkilendirme, guvenlik,
gunlukleme gibi islevleri merkezi olarak yonetebilir.

Spring Cloud Gateway'in temel ozellikleri sunlardir:

1. **Routinge ve Filtreleme:**
    * Spring Cloud Gateway, gelen istekleri belirli yollar ve filtreler uzerinden yonlendirme yetenegine sahiptir. Bu,
      bir istegi belirli bir mikroservise yonlendirmek veya istegi degistirmek icin kullanilabilir.

    2. **Kimlik Dogrulama ve Yetkilendirme:**
        * API Gateway, gelen istekleri kimlik dogrulama ve yetkilendirme icin kontrol edebilir. Bu, guvenlik
          politikalarini merkezi olarak yonetmeyi ve korumayi saglar.
    3. **Rate Limiting (Hiz Sinirlama):**
        * Belirli bir sure icinde belirli bir kullaniciya veya istemciye yapilan istek sayisini kontrol etme yetenegi.
          Bu, kotu niyetli kullanima karsi koruma saglayabilir.
    4. **Retry ve Circuit Breaker:**
        * Hata durumlarinda otomatik olarak yeniden deneme (retry) ve hata durumlarini ele alma (circuit breaker)
          yetenekleri.
    5. **Yapilandirilabilirlik ve Dinamik Yeniden Yukleme:**
        * Gateway, yapilandirma dosyalarini kullanarak genis bir yapilandirma secenekleri sunar ve yapilandirma
          dosyalarinin dinamik olarak yeniden yuklenmesine olanak tanir.
    6. **Yuk Dengeleme ve Hata Toleransi:**
        * API Gateway, arkadaki mikroservislere gelen istekleri dengeleyebilir ve hata durumlarini ele alabilir. Bu,
          hizmetin daha yuksek kullanilabilirlik ve guvenilirlik saglamasina yardimci olur.

Spring Cloud Gateway, Spring Boot tabanlidir ve Spring Cloud projelerinin bir parcasidir. API Gateway, mikroservis
mimarilerinde istemcilerle servisler arasindaki etkilesimi yonetmek, guvenlik politikalarini uygulamak ve servisleri
daha etkili bir sekilde kullanmak icin yaygin olarak kullanilir.

</details>

<details>

<summary>Spring Cloud Feign Client nedir?</summary>

Servislerimiz arasindaki iletisimi klasik yontem diyebilecegimiz RestTemplate ile yaparak saglabiliyoruz. RestTemplate
ile yapilan iletisim yontemini kullanarak metotlarimiz icerisinde ilgili api istegini kullanarak metotlarimizi bagimli
hale getiriyoruz.

OpenFeign kullanarak servis iletisimi interface templateler uzerinden yonetip, daha okunabilir ve configurasyonel olarak
kullanabilmeyi saglamaktayiz.

Bu kullanabilirlik sayesinde cok fazla kullanilan servislerin yonetilebilmesi ve olasi degisiklerde daha hizli ve kolay
mudahale edebilmemizi saglamaktadir.

Feign'in bazi temel ozellikleri sunlardir:

1. Deklaratif API: Feign, RESTful servislerle etkilesimde bulunmak icin basit bir deklaratif API saglar. Bu sayede,
   gelistiricilerin uzak servislere istekler gondermek icin ayrintili kodlar yazmalari gerekmez.
    2. Annotasyonlar: Feign, metotlari ve parametreleri isaretlemek icin anotasyonlar kullanir. Bu anotasyonlar,
       isteklerin nasil yapilacagini ve hedef servislerin nerede oldugunu belirtir.
    3. Yapilandirilabilirlik: Feign, yapilandirilabilir ozelliklerle gelir, bu sayede gelistiricilerin isteklerin zaman
       asimi surelerini, yeniden deneme politikalarini ve diger baglamsal ayarlari kolayca belirlemelerine olanak tanir.

</details>

<details>

<summary>Resilience4j Nedir ?</summary>

[`https://umitsamimi.medium.com/circuit-breaker-resilience4j-7e1082610c52`](https://umitsamimi.medium.com/circuit-breaker-resilience4j-7e1082610c52)`-> Cok iyi anlatiyor`

### 🎯 Resilience4j Nedir ?

* Bilindiği üzere, arka-plan (back-end) servislerinin giderek karmaşıklaşması ve tek parça halinde sürdürülebilirliğinin
  zorlaşmasının sonucunda, mikroservis mimarisi kullanılarak arka-plan servislerinin birbirleriyle iletişim halinde
  olan, nispeten daha küçük servisler halinde düzenlenmesi oldukça popüler hale gelmiştir.
    * Bu servisler, birbirleriyle kapalı bir ağ üzerinde, çoğunlukla HTTP protokolünü kullanarak haberleşmektedirler.
    * Lakin, birbirleriyle HTTP üzerinden haberleşen servisler, bazı ek problemleri de beraberinde getirebilirler.
    * Projemden örnek verirsem user-service servisi, kendisine gelen istekleri karşılamak üzere department-service
      servisiyle iletişime geçiyor olsun.
    * department-service servisinde oluşabilecek bir sistem hatası, servisin yeni bir sürümünün sunucuya yüklenmesi veya
      yeni sürümde çıkabilecek istikrar sorunları gibi bir çok nedenden ötürü, department-service servisine giden
      isteklerin zamanlı bir biçimde yanıtlanamadığını ve bazı çağrılarda uygun bir cevap nesnesi yerine sunucu
      hatalarının döndürüldüğünü düşünün.
    * Bu durumda, department-service servisinin döndürdüğü hata user-service servisine de sıçrayacaktır.
    * Ardından, söz konusu hata department-service servisine çağrı yapılan katmandan itibaren üst katmanlara (servis,
      denetici (controller)vs.) fırlatılacak ve user-service servisine çağrı gerçekleştiren servisin de uygun bir yanıt
      alamamasına neden olacaktır.
    * Bu şekilde oluşan bir hata yayılım zinciri, son kullanıcının söz konusu web uygulamasını arzu ettiği bir biçimde
      kullanamamasıyla sonuçlanacaktır.
    * Bu durumlar ne gibi yöntemlerle giderilebilir.

### 📌 Retry

* Beklenmedik bir yanıtın - ya da yanıt alınamamasının - isteği tekrar göndererek düzeltilebileceğini varsaydığımızda,
  yeniden deneme kalıbını kullanmak yardımcı olabilir. Bu, işlem başarısız olarak işaretlenmeden önce başarısız
  isteklerin yapılandırılabilir sayıda yeniden denendiği çok basit bir modeldir.
    * Aşağıdaki durumlarda yeniden denemeler yararlı olabilir:
    * Paket kaybı gibi geçici ağ sorunları.
    * Hedef hizmetin dahili hataları, örneğin bir veritabanı kesintisinden kaynaklanan.
    * Hedef hizmete yönelik çok sayıda talep nedeniyle yanıt alınamaması veya yavaş yanıt alınması.

### 📌 Fallback

* Geri dönüş kalıbı, hizmetinizin başka bir hizmete yapılan başarısız bir istek durumunda yürütmeye devam etmesini
  sağlar. Eksik bir yanıt nedeniyle hesaplamayı iptal etmek yerine, bir geri dönüş değeri doldururuz.

### 📌 Timeout

* Zaman aşımı modeli oldukça basittir ve birçok HTTP istemcisinin yapılandırılmış varsayılan bir zaman aşımı vardır.
  Amaç, yanıtlar için sınırsız bekleme sürelerinden kaçınmak ve böylece zaman aşımı içinde yanıt alınamayan her isteği
  başarısız olarak değerlendirmektir.

### 📌 Circuit breaker

* Circuit Breakers deseni, adından anlaşılacağı üzere elektronik devrelerdeki, devre kesici şalt cihazlar gibi
  kurgulanan bir yöntemdir.
    * Devre kesiciler, elektronik devreyi korumak için sistemde meydana gelen bir aksaklık durumunda (yük akımını veya
      kısa devre akımları) yük geçişini durdururlar.
    * Circuit Breakers deseni uygulandığında, servisler arasında haberleşmeyi kapsayacak şekilde inşaa edilir.
    * Servisler arasındaki iletişimi (Event, Message, Http, vb.) izler ve haberleşmedeki meydana gelen hataları takip
      eder.
    * Request yapılan bir API ucunun, http 500 hata kodu dönmesi veya fırlatılan bir event’in handle edilememesi bu hata
      duruma örnek olarak gösterilebilir.
    * Sistemde meydana gelen hata durumu belirli bir eşik değerini geçtiğinde ise Circuit Breakers açık duruma geçer ve
      haberleşmeyi keser, daha önce belirlenen hata mesajlarını döndürür.
    * Bir süre bekledikten sonra devre yarı açık duruma geçer. Bu durumda bir isteğin geçmesine izin verir ve başarısız
      olması durumunda açık duruma veya başarılı olması durumunda kapalı duruma geri döner.
    * Circuit Breakers açık durumdayken haberleşme trafiğini izlemeye devam eder ve istek yapılan servis veya fırlatılan
      bir event başarılı sonuçlar dönmeye başlamışsa kapalı duruma geçer.
    * Circuit Breakers’ın üç durumu vardır. Bu durumlar: Açık (Open), Kapalı (Closed) ve Yarı-Açık (Half-Open).

#### Closed

* Sigorta tamamen kapalıdır. Bütün çağrıların yapılmasına izin verilir ve hatalı çağrılar kurtarma metoduna
  yönlendirilebilir (fallback). Hatalı çağrıların sayısının (veya oranının) belirli bir sayının üstünde olması
  takdirinde, sigorta, açık konuma getirilir.

#### Open

* Sigorta aktif konumdadır ve çağrıların tamamını reddetmektedir. Reddedilen çağrılar, mikroservis içerisinde yer alan
  bir kurtarma metoduna yönlendirilerek çağrının sorunsuz bir biçimde sonuçlanması sağlanabilir.

#### Half-Open

* Sigortanın açık konuma geçmesinden belirli bir süre sonra, sigorta, kendini yarı açık konuma getirir. Bu durumda
  belirli sayıda (veya oranda) çağrının gerçekleştirilmesine izin verilir. Eğer hatalı çağrıların oranı (veya sayısı)
  belirli bir sayının üzerinde olursa, tekrardan açık konuma geçilir; aksi takdirde sigorta tamamen kapatılır.

</details>

---

### *Kafka*

<details>

<summary>Kafka Nedir ve Temel Kavramlari Nelerdir Acikla</summary>

Kafka, yuksek olcekli ve dayanikli bir veri akisi (streaming) platformudur. Baslangicta LinkedIn tarafindan gelistirilen
ve su anda Apache Software Foundation tarafindan acik kaynak olarak yonetilen Kafka, buyuk miktarda veriyi guvenilir bir
sekilde, hizli bir sekilde ve olceklenebilir bir bicimde islemek icin tasarlanmistir. Iste Kafka'nin temel kavramlari:

1. **Broker:**
    - Kafka'nin temel yapi tasidir.
    - Verilerin depolandigi ve akisini kontrol ettigi sunuculardir.
    - Bir Kafka kumesinde birden fazla broker bulunabilir.
    - Brokerlar, yonetim ve liderlik icin Zookeeper ile iletisim kurar.

2. **Topic:**
    - Veri ureten uygulamalardir.
    - Belirli bir topic'e mesaj gonderirler.
    - Mesajlar, belirli bir partition icine yazilir.

3. **Producer:**
    - Veri ureten veya yayinlayan uygulamalardir.
    - Belirli bir topic'e mesaj gonderirler.

4. **Consumer:**
    - Veriyi tuketen uygulamalardir.
    - Belirli bir topic'den mesajlari alirlar.
    - Her bir consumer, belirli bir partition'dan mesajlari okur.

5. **Consumer Group:**
    - Birden cok consumer'i bir araya getiren mantiksal bir gruptur.
    - Ayni topic'ten gelen mesajlari paylasan consumer'lar arasinda is bolumu yapilmasini saglar.
    - Her partition'a sadece bir consumer atanir, bu sayede paralel isleme imkani saglanir.

6. **Partition:**
    - Bir topic icindeki verilerin fiziksel olarak bolundugu birimlerdir.
    - Her partition, sirali bir sekilde sirali mesajlari icerir.
    - Paralel isleme ve olceklenebilirlik saglar.

7. **Offset:**
    - Her partition icindeki bir mesajin benzersiz bir tanimlayicisidir.
    - Consumer'lar, okuduklari son mesajin offset'ini hatirlar, boylece bir sonraki mesajdan okumaya devam edebilirler.

8. **Zookeeper:**
    - Kafka kumesinin koordinasyonunu saglayan bir aractir.
    - Broker'larin durumunu ve konfigurasyonunu yonetir.
    - Kafka'nin sagligini izler ve failover islemlerini yonetir.

Kafka, genellikle buyuk veri akislari, loglama sistemleri, uygulama olaylari ve gercek zamanli analitikler gibi
senaryolarda kullanilir. Dayaniklilik, olceklenebilirlik ve yuksek performans gibi avantajlari, Kafka'nin populerligini
artirmistir.

</details>

<figure><img src="assets/kafka.png" alt=""><figcaption></figcaption></figure>

<details>

<summary>Kafka Topic Nedir?</summary>

Kafka'da bir "topic", veri akisini (streaming) duzenlemenin ve kategorize etmenin bir yoludur. Temel olarak, belirli bir
turdeki veri akisini ifade eden adlandirilmis bir kanaldir. Kafka'nin temel mantigi, veriyi konseptsel olarak bir veya
daha fazla topik icinde duzenlemektir.

Iste Kafka topic'inin temel ozellikleri:

1. **Adlandirma:**
    - Topic'lere anlamli ve aciklayici adlar verilir. Ornegin, "loglar", "kullanici etkinlikleri" gibi.
    - Adlar, veri akisinin icerigini temsil eder ve veriyi kategorize eder.

2. **Iletisim:**
    - Producer'lar belirli bir topige mesajlar gonderir.
    - Consumer'lar belirli bir topigi dinler ve mesajlari alir.

3. **Paralel Isleme:**
    - Kafka topic'leri, icerdikleri verinin sirali ve paralel islenmesine izin veren partition'lara bolunebilir.
    - Partition'lar, belirli bir sirayla mesajlarin islenmesini saglar ve ayni anda birden cok tuketiciye hizmet
      verebilir.

4. **Olceklenebilirlik:**
    - Bir konu, birden fazla broker uzerinde bolumlere ayrilabilir ve bu da olceklenebilirlik saglar.
    - Her bir partition, ayri bir fiziksel depolama birimine karsilik gelir.

5. **Veri Saklama:**
    - Mesajlar, topic icindeki partition'larda saklanir.
    - Belirli bir sure boyunca veya belirli bir boyuta ulasana kadar saklanabilir.

6. **Yayin ve Abonelik Modeli:**
    - Kafka, yayin/abonelik (publish/subscribe) modelini benimser. Producer'lar mesajlari belirli bir topic'e gonderir
      ve Consumer'lar belirli bir topic'den mesajlari alir.

Ornegin, bir "sensor_verileri" topic'i, bir IoT (Internet of Things) uygulamasinda bir dizi sensor tarafindan uretilen
verileri icerebilir. Bu sayede, sensor verilerini islemek isteyen uygulamalar bu belirli topic uzerinden verilere
erisebilirler.

</details>

<details>

<summary>Kafka'ya Event Gonderirken Neden "Key" Gondeririz?</summary>

"Key", mesajlari gruplamak ve belirli bir sirayla islemek icin kullanilir. Key, mesajin hangi partisyon icinde
depolanacagini belirlemek icin kullanilabilir.

</details>

<details>

<summary>Zookeeper ve Kafka Iliskisi Nedir?</summary>

Zookeeper ve Kafka arasindaki iliski, Kafka'nin koordinasyon ve yonetiminde onemli bir rol oynayan Zookeeper tarafindan
saglanan hizmetlere dayanir. Iste bu iki sistem arasindaki temel iliskiler:

1. **Koordinasyon ve Broker Yonetimi:**
    - Kafka, bir veri akisi platformu olarak calisir ve bircok broker icerir. Bu broker'larin koordinasyonunu saglamak
      icin Zookeeper kullanilir.
    - Zookeeper, Kafka broker'larinin durumunu ve konfigurasyonunu takip eder. Her bir broker, Zookeeper znodes adi
      verilen kucuk veri dugumlerine sahip olur ve bu dugumler araciligiyla durum bilgilerini paylasir.

2. **Leader Secimi:**
    - Zookeeper, Kafka partition'larinda lider (leader) ve takipci (follower) rolleri arasinda lider secimi islevini
      yonetir.
    - Her bir partition icin bir lider belirlenir ve Zookeeper, lider degisimini ve partition durumunu izleyerek tum
      broker'lar arasinda liderligi korur.

3. **Broker Discovery:**
    - Zookeeper, Kafka broker'larinin dinamik olarak eklendigi veya kaldirildigi durumlari yonetir. Yeni broker'lar
      eklenirse veya mevcut broker'lar cikartilirsa, Zookeeper bunu tum sistemle paylasir ve gerekli guncellemeleri
      yapar.

4. **Group Coordinator:**
    - Kafka, consumer gruplari adi verilen gruplarda tuketici (consumer) islemlerini destekler. Zookeeper, consumer
      gruplari arasinda bir koordinasyon rolu ustlenir ve consumer'larin durumunu izler.

5. **Offset Takibi:**
    - Kafka, tuketici gruplari icin konum bilgisini (offset) Zookeeper uzerinde saklar. Bu, tuketici gruplarinin
      kaldiklari yerden devam etmelerini saglar.

Bu Zookeeper ve Kafka iliskisi, Kafka'nin dagitik dogasini yonetmek, koordinasyonu saglamak ve yuksek kullanilabilirlik
saglamak icin onemlidir.



</details>

<details>

<summary>Kafka Partisyonu Nedir?</summary>

Kafka'da bir partition (partisyon), bir topic icindeki verilerin fiziksel olarak bolundugu birimidir. Her bir partition,
icindeki mesajlarin sirali bir sekilde saklandigi bir veri depolama birimidir. Kafka, partisyonlari kullanarak
olceklenebilirlik, paralel isleme ve yuksek performans saglar. Iste Kafka partisyonlarina dair temel bilgiler:

1. **Paralel Isleme:**
    - Bir topic'teki veriler, partition'lara bolunerek paralel isleme imkani saglanir.
    - Her bir partition, sirali olarak mesajlari icerir, ancak farkli partition'lar arasinda mesajlar eszamansiz bir
      sekilde islenebilir.

2. **Olceklenebilirlik:**
    - Bir topic icindeki verilerin coklu partitionlara bolunmesi, yuksek olceklenebilirlik saglar.
    - Bu sayede Kafka kumesi, cok sayida broker ve partition ile genis bir veri yukunu ele alabilir.

3. **Durabilite ve Dayaniklilik:**
    - Her bir partition, kendi basina bir dayaniklilik seviyesine sahiptir. Mesajlar bir partition icinde sirali olarak
      saklanir ve gerektiginde tekrar okunabilir.
    - Mesajlar bir partition icinde belirli bir sure boyunca veya belirli bir boyuta ulasana kadar saklanabilir.

4. **Mesaj Siralamasi:**
    - Her bir partition icindeki mesajlar, belirli bir sira ile saklanir.
    - Ancak, farkli partition'lar arasindaki mesajlar eszamansiz bir sekilde islenebilir.

5. **Consumer Gruplari ile Is Bolumu:**
    - Farkli consumer gruplari, ayni topic'ten farkli partition'lari tuketebilir. Bu, paralel isleme ve yuksek
      olceklenebilirlige olanak tanir.

6. **Mesajlarin Dagilimi:**
    - Mesajlar, belirli bir partition icindeki offset'e gore siralanir.
    - Her bir partition, bir Kafka kumesindeki birden fazla broker uzerinde dagitilabilir.

Partisyonlar, Kafka'nin esnek ve olceklenebilir bir yapiya sahip olmasini saglar. Veri akisinin islenmesindeki paralel
isleme, olceklenebilirlik ve dayaniklilik gibi avantajlar, Kafka partisyonlarinin kullanimini onemli kilar.
</details>

<details>

<summary>Iki Servis Arasinda Hata Olustugunda Nasil Yonetirsiniz?</summary>

"Retry" mekanizmasini kullanarak, belirlenen bir sure icinde tekrar deneme yapilabilir. Bu, hata olustugunda otomatik
olarak tekrar deneme yapilmasini saglayan bir yaklasimdir.

</details>

<details>

<summary>Kafka'ya Event Gonderdiniz Fakat Kafka Coktu, Bunu Nasil Yonetirsiniz?</summary>

"Outbox" deseni kullanarak, Kafka'nin cokmesi durumunda gonderilen mesajlarin gecici bir yerde saklanarak daha sonra
tekrar gonderilmesini saglayabilirsiniz.

</details>

<details>

<summary>Kafka Replication Nedir ve Neden Onemlidir?</summary>

Kafka replication, Kafka'nin dayanikliligini artirmak ve yuksek kullanilabilirlik saglamak amaciyla kullanilan bir
ozelliktir. Replication, verilerin bir broker'dan digerine kopyalanmasini ve saklanmasini ifade eder. Bu, bir brokerun
cokmesi veya veri kaybi durumunda sistemin calismaya devam etmesini saglar. Iste Kafka replication'in onemi ve nasil
calistigiyla ilgili bazi ana noktalar:

1. **Dayaniklilik:**
    - Replication, her bir partition'in birincil ve bir veya daha fazla ikincil kopyasinin olusturulmasini icerir. Bu
      sayede bir broker coktugunde veya bir partition kayboldugunda, veri kaybi onlenir.

2. **Yuksek Kullanilabilirlik:**
    - Replication, yuksek kullanilabilirlik saglamak icin birden cok broker uzerinde yedek kopyalar olusturarak sistemin
      cokmesi durumunda kesintiye ugramamasini saglar.

3. **Lider ve Takipci Modeli:**
    - Her bir partition icin bir lider (leader) ve bir veya daha fazla takipci (follower) belirlenir.
    - Producer'lar ve consumer'lar genellikle lider ile etkilesimde bulunur. Takipci kopyalar, liderin durumu izleyerek
      ve onunla eszamanli olarak guncellenerek dayanikliligi saglar.

4. **Kafka Broker'larin Cokmesi Durumunda:**
    - Bir broker coktugunde, o broker uzerindeki partition'lar devralinabilir ve bir baska broker uzerindeki takipci
      kopyalardan devralan bir lider atanabilir.
    - Bu sayede sistem calismaya devam eder.

5. **Lider Degisimi:**
    - Replication, lider broker'da bir hata olmasi durumunda liderin otomatik olarak bir takipciye gecmesini saglar. Bu,
      kesintisiz bir hizmet saglamaya yardimci olur.

6. **Performans Iyilestirmeleri:**
    - Replication, paralel olarak birden cok broker uzerinde veri kopyalama islemlerini destekler. Bu, yuksek talep
      durumlarinda performansin artirilmasina yardimci olabilir.

Replication, Kafka'nin guvenilir ve dayanikli bir veri akisi platformu olarak kullanilmasinda kritik bir rol oynar.
Ozellikle buyuk olcekli uygulamalarda ve kritik sistemlerde, veri kaybini onlemek ve yuksek kullanilabilirlik saglamak
icin replication stratejileri onemlidir.

</details>

<details>

<summary>Herhangi Bir Servisten Hata Geldiginde Bu Hata Durumunu Nasil Tolere Edersiniz?"Kafka Shovel"</summary>

"Kafka Shovel" terimi, Kafka'nin dayanikliligini artirmak ve hata durumlarina tolerans gostermek amaciyla kullanilan bir
yaklasimi ifade edebilir. Ancak, bu terim spesifik bir Kafka icerigiyle genel olarak iliskilendirilmemistir, bu nedenle
benzer bir kavrami aciklayarak yardimci olmaya calisacagim.

Hata durumlarina tolerans gostermek ve sistemdeki hatalarla basa cikmak icin birkac genel strateji vardir. Iste
bunlardan bazilari:

1. **Retry Mekanizmalari:**
    - Hata durumlarinda, hatali islemleri tekrar denemek icin bir "retry" mekanizmasi kurulabilir. Eger hata gecici bir
      durumsa, belirli araliklarla tekrar deneme stratejisi kullanilabilir.

2. **Backoff Stratejileri:**
    - Hata durumlarina karsi, belirli bir sure boyunca tekrar deneme yapmamak veya tekrar deneme araliklarini artirmak
      gibi "backoff" stratejileri kullanilabilir. Bu, asiri yuk altindaki sistemlere karsi daha direncli olabilir.

3. **Hata Kuyruklari (Error Queues):**
    - Hatali islemler, bir kuyruga yonlendirilebilir ve daha sonra manuel mudahale veya otomatik bir surecle
      incelenebilir. Bu, hatalari izleme ve cozme surecini kolaylastirabilir.

4. **Dead Letter Queues (Olu Mektup Kuyruklari):**
    - Hatali islemler, bir "olu mektup kuyrugu"na yonlendirilebilir. Bu kuyruk, islenmeyen veya basarisiz olan islemleri
      saklamak icin kullanilir. Bu sekilde, hatali islemler incelenebilir ve sorunlarin cozulmesi icin analiz
      yapilabilir.

5. **Circuit Breaker Pattern:**
    - Hatalar belirli bir esigi astiginda, sistem bir "circuit breaker" devreye alabilir ve islemleri gecici olarak
      durdurabilir. Bu, sistemin asiri yuklenmesini ve daha fazla hasari onleyebilir.

6. **Hata Kayitlari ve Izleme:**
    - Hatalarin ayrintili kayitlari tutulabilir ve bir izleme sistemi araciligiyla hatalarin gercek zamanli olarak takip
      edilmesi saglanabilir.

Bu stratejilerin kombinasyonu, hata toleransi ve dayanikliligi artirabilir. Kafka'nin replication, partitioning ve
yuksek kullanilabilirlik ozellikleri, sistemlerin hata durumlarina karsi daha dayanikli olmasina yardimci olabilir.

</details>

<figure><img src="assets/kafka-use.gif" alt=""><figcaption></figcaption></figure>


> Kafka vs RabbitMq

<figure><img src="assets/image.png" alt=""><figcaption></figcaption></figure>

---

### *Redis*

<details>

<summary>Redis Nedir ve Temel Kavramlari Nelerdir?</summary>

- *Redis Nedir:* Redis, acik kaynakli ve anahtar-deger tabanli bir in-memory veri depolama sistemidir. Hizli, esnek ve
  yuksek performansli bir NoSQL veritabani olarak kullanilir.
- *Temel Kavramlar:*
    - *String:* Tek bir degeri temsil eder.
    - *List:* Sirali veri koleksiyonudur.
    - *Set:* Tekil degerlerin koleksiyonudur.
    - *Hash:* Alan/deger ciftlerini iceren bir veri koleksiyonudur.
    - *Zset (Sorted Set):* Sirali bir settir, her ogrenin bir siralama skoru vardir.

</details>

<details>

<summary>Redis ile Iliskisel Veritabanlari (RDBMS) Arasindaki Temel Farklar Nelerdir?</summary>

- *Veri Modeli:* Redis, anahtar-deger tabanli bir model kullanir; iliskisel veritabanlari tablo ve satir modeline
  dayanir.
- *Performans:* Redis, verileri bellekte tuttugu icin yuksek performans saglar; RDBMS disk tabanli calisir.
- *Veri Iliskileri:* Redis, basit veri yapilari kullanir ve karmasik iliskisel yapilari desteklemez; RDBMS kompleks
  iliskileri yonetir.
- *Veri Depolama Mekanizmasi:* Redis, verileri genellikle RAM'de tutar; RDBMS disk uzerinde depolama yapar.
- *Kullanim Senaryolari:* Redis hizli okuma/yazma islemleri ve cache icin uygundur; RDBMS kompleks sorgular ve iliskisel
  veri modelleri icin uygundur.

</details>

<details>

<summary>Redis Publish/Subscribe Modelini Aciklayin. Nasil Calisir?</summary>

- Redis Publish/Subscribe (Pub/Sub) modeli, bir yayin yapan (publisher) ve bu yayini dinleyen (subscriber) ogelerden
  olusur.
- Bir publisher, belirli bir kanala (channel) mesaj gonderir.
- Subscribers, ilgilendikleri kanallara abone olur ve bu kanallardan gelen mesajlari alir.
- Pub/Sub modeli, asenkron mesajlasma, olay bildirimi ve gercek zamanli iletisim gibi senaryolarda kullanilir.

</details>

<details>

<summary>Redis Cache Nedir ve Nasil Kullanilir?</summary>

- Redis, hafiza tabanli bir veritabani oldugu icin dogal olarak cache olarak kullanilabilir.
- Ozellikle sik erisilen veya maliyetli olan verilerin hizli erisim icin kullanilir.
- Cache olarak kullanilirken, verilerin belirli bir sure boyunca (TTL - Time-To-Live) tutulmasi sikca tercih edilen bir
  stratejidir.

</details>

<details>

<summary>Redis'in Genis Olcude Cache Olarak Kullanilmasinin Avantajlari Nelerdir?</summary>

- *Hizli Erisim:* Redis, verileri hafizada tuttugu icin cok hizli erisim saglar.
- *Performans:* Cache olarak kullanildiginda, sik kullanilan verilere tekrar tekrar disk uzerinden erisme maliyetinden
  kacinilir.
- *Yuk Dengeleme:* Veritabani yukunu azaltarak genel sistem performansini artirir.
- *Onbellege Alma Stratejileri:* Onbellege alma stratejileri sayesinde istenen verilere daha hizli erisim saglanabilir.
- *Maliyet Azalmasi:* Sik kullanilan verileri her defasinda diskten okuma yerine bellekte tutmak, genel sistem
  maliyetini azaltabilir.

Bu cevaplar, Redis'in temel kavramlari, kullanim alanlari ve cache olarak kullanilmasinin avantajlari hakkinda genel bir
anlayis saglamayi amaclamaktadir.

</details>

<details>

<summary>Redis'te TTL (Time-To-Live) Nedir ve Neden Kullanilir?</summary>

TTL (Time-To-Live), Redis (Remote Dictionary Server) veri tabaninda bir ozelliktir ve bir anahtarin ne kadar sureyle
saklanacagini belirten bir sure degeridir. Bu sure, bir anahtarin Redis veri tabaninda kalma suresini sinirlar.
Anahtarin belirtilen sure boyunca kullanilmamasi durumunda, Redis otomatik olarak bu anahtari kaldirir.

TTL'nin kullanilmasinin bazi temel nedenleri sunlardir:

1. **Cache Yonetimi:**
    - Redis, hafiza icinde calisan bir veri deposu (in-memory data store) oldugu icin, sik kullanilan verileri bellekte
      tutmak icin yaygin olarak kullanilir. TTL, ozellikle gecici verilerin (ornegin, onbellek verileri) yonetiminde
      onemlidir. Bu sayede bellekte gereksiz veri birikimi onlenir.

2. **Onbellek Yonetimi:**
    - Redis, hizli okuma ve yazma performansi sagladigi icin sikca onbellek olarak kullanilir. TTL, onbellekteki
      verilerin belirli bir sure boyunca gecerliligini korumasini saglar. Bu, eski veya guncelligini yitirmis verilerin
      onbellekte tutulmasini onler.

3. **Gecici Veri Depolama:**
    - Bazi durumlarda, gecici olarak depolanmasi gereken veriler vardir. TTL, bu tur gecici verilerin otomatik olarak
      temizlenmesini saglar.

4. **Oturum Yonetimi:**
    - Redis, oturum yonetimi icin kullanilabilir. Kullanici oturumlarini takip etmek ve belirli bir sure boyunca
      kullanici oturumlarini tutmak amaciyla TTL kullanilabilir. Kullanici oturumu belirli bir sure boyunca etkilesim
      olmadiginda otomatik olarak sona erer.

TTL degeri, Redis'teki `EXPIRE` veya `SETEX` komutlari ile belirlenir. Ornegin:

```redis
SET mykey "myvalue"
EXPIRE mykey 3600  # 3600 saniye (1 saat) boyunca sakla
```

Bu ornekte `mykey` anahtari, 1 saat boyunca saklanacaktir. Bu sure zarfinda bu anahtar uzerinde islem yapilmazsa,
otomatik olarak silinecektir. TTL, Redis veri tabanindaki bellek yonetimini daha etkili bir sekilde yonetmeye ve gecici
verilerin kontrollu bir sekilde kullanilmasina olanak tanir.

</details>

---

### *Elasticsearch*

<details>

<summary>Elasticsearch Nedir?</summary>

Elasticsearch, veri arama, analiz ve gorsellestirme islemlerini hizli ve etkili bir sekilde gerceklestirmenizi saglayan
bir acik kaynakli veri arama ve analiz platformudur.
Elasticsearch, buyuk miktardaki verileri duzenli bir sekilde saklayabilen, hizli ve olceklenebilir bir veritabani ve
arama motoru(**full-text search**) olarak dusunulebilir.

</details>

<figure><img src="assets/full-text-search.png" alt=""><figcaption></figcaption></figure>


<details>

<summary>Elasticsearch'un Avantajlari</summary>

- `High Performance(Yuksek Performans):`

  Elasticsearch, guclu tam metin arama yetenekleriyle bilinir. Apache Lucene altyapisi kullanarak ters indeksleme ve
  gelismis arama algoritmalari kullanarak hizli ve dogru arama sonuclari saglar. Tipik bir SQL veritabanindan daha
  hizlidir.


- `Near Real-Time Operations(Neredeyse Gercek Zamanli Islemler):`

  Veri okuma veya yazma gibi Elasticsearch islemleri genellikle bir saniyeden daha kisa surede tamamlanir. Bu nedenle
  Elasticsearch'ten uygulama izleme ve anormallik algilama gibi neredeyse gercek zamanli kullanim amaclari dogrultusunda
  faydalanabilirsiniz.


- `Lots of Search Options(Cok Sayida Arama Secenegi):`

  Elasticsearch, arama konusunda bircok ozellik sunar. Full-text search(tam metin arama),auto-complete(otomatik
  tamamlama), instant search(anlik arama) ve daha fazlasini alabilirsiniz.

  Autocompletion(Otomatik tamamlama) ve instant search(anlik arama), yazarken oneriler sunar. Oneriler, arama gecmisi
  veya ilgilige dayali olarak tahmin edilir. Ayrica yazim hatasi varsa bile kullanicilar ilgili aramalar alir.


- `Distributed Approach(Dagitik mimari):`

  Elasticsearch, dagitik bir mimaride calisir. Sonuc olarak, buyuk miktarda veriyi hizli bir sekilde isleyebilir.
  Diziler parcalara ayrilir. Parcalar tam islevli bir dizin gibi calisir. Her parcada cok sayida kopya olabilir. Bu
  parcalari Elasticsearch kumesinin herhangi bir yerine barindirabilirsiniz.


- `Cluster and Backup Support (Cluster ve Yedekleme Destegi):`

  Elasticsearch, coklu dugumlerden (nodes) olusan bir kume (cluster) icinde calisabilir. Bu, yuksek kullanilabilirlik
  saglamak ve veri kaybini onlemek icin onemlidir. Ayrica, verilerin yedeklenmesi icin kapsamli bir sistem sunar.


- `Plugins and Integrations(Eklentiler ve Entegrasyonlar):`

  Elasticsearch, eklentiler ve entegrasyonlarla yuksek uyumludur. Eklentiler, islevselligi artirmak ve aramalari
  ozellestirmek icin kullanilir. Ozel eslemeler, analizciler ve kesifler eklemeye yardimci olur.


- `RESTful API:`

  Elasticsearch, sundugu basit REST tabanli API'ler sayesinde hizmeti hizla kullanmaya baslamanizi ve farkli kullanim
  orneklerine uygun uygulamalar tasarlamanizi saglar.


- `Security(Guvenlik):`

  Elasticsearch, kullanici kimlik dogrulama, erisim kontrolu ve veri sifreleme gibi guvenlik onlemlerini destekler.


- `Easy Application Development:`

  Kolay uygulama gelistirme Java, Python, PHP, JavaScript, Node.js, Ruby ve daha bircok dil icin destek sunar.

</details>

<details>

<summary>Elasticsearch Kullanim Alanlari</summary>

`1. Web Arama ve Indeksleme`<br>

`2. Metin Analizi ve Madencilik`<br>

`3. Log Yonetimi`<br>

`4. Muzik ve Medya Isleme`<br>

`5. E-ticaret ve Pazarlama`<br>

`6. Urun ve Icerik Onerileri`<br>

`7. Finansal Veri Analizi`<br>

</details>

<details>

<summary>Elasticsearch Temel Kavramlari Neler?</summary>

`index = database`<br>
`field = column`<br>
`document = row`<br>
`type = table`<br>

<details>
<summary>Index</summary>
Elasticsearch'te verilerin duzenli bir sekilde depolandigi birimdir ve genellikle bir kutuphane koleksiyonunu temsil eder. Ornegin, bir kutuphane sistemi, kitaplarin depolandigi bir "kitaplar" endeksi olusturabilir.
</details>

<details>
<summary>Document</summary>
Elasticsearch endekslerinde saklanan verilerin temel yapi tasidir. Genellikle JSON formatinda bilgileri icerir ve bir kitabin tum ayrintilarini icerebilir, bu da kitap adi, yazar, yayin tarihi gibi bilgileri icerir.
</details>

<details>
<summary>Field</summary>
Elasticsearch dokumanlari icindeki verileri temsil eden bilesendir. Ornegin, bir kitap dokumaninda "kitap adi" veya "yazar" gibi alanlar birer field'dir.
</details>

<details>
<summary>Type (Tur, Artik Onerilmemektedir)</summary>
Elasticsearch 6.0 ve sonraki surumlerde kullanimdan kaldirilmis olsa da, Elasticsearch 5.0 ve onceki surumlerde bulunan bir kavramdir. Type, bir dizindeki belgelerin altinda bulunan turdur.
</details>

<details>
<summary>Indexing</summary>
Elasticsearch'te yeni dokumanlarin endekslendigi veya mevcut dokumanlarin guncellendigi islemdir. Veri eklemek veya degistirmek icin kullanilir.
</details>

<details>
<summary>Query</summary>
Elasticsearch'te veri sorgulamak icin kullanilan bir terimdir. Belirli kriterlere uyan dokumanlari aramak veya filtrelemek icin kullanilir.
</details>

<details>
<summary>Mapping</summary>
Elasticsearch'te veri yapisini tanimlayan bir yapidir. Hangi alanlarin hangi veri turlerini icerdigini ve hangi analizleri uyguladiginizi belirtir. Ornegin, bir alanin metin veya sayi veri turunde oldugunu ve dil analizi uygulandigini belirtmek icin kullanilir.
</details>

<details>
<summary>Analysis</summary>
Elasticsearch'te metin verilerinin islenme surecidir. Metinleri dil analizi ve belirli kriterlere gore ayristirma islemi icerir. Bu, metin tabanli aramalari daha etkili hale getirir.
</details>

<details>
<summary>Cluster</summary>
Elasticsearch sunucularinin bir araya gelerek olusturdugu bir yapidir. Verilerin guvenli bir sekilde depolanmasi ve sorgulanmasi icin kullanilir.
</details>

<details>
<summary>Node</summary>
Elasticsearch kumesinin bir parcasi olan bir sunucu veya dugumdur. Verileri depolar ve sorgulari isler. Birden cok node, bir cluster olusturur.
</details>

<details>
<summary>Shard</summary>
Elasticsearch endekslerinin bolundugu fiziksel veya mantiksal birimlerdir. Veri dagitimini ve performansi optimize etmeye yardimci olur.
</details>

<details>
<summary>Replica</summary>
Bir endeksin yedek kopyasidir ve veri yedeklemesi saglar. Arizali bir nodenin yerine gecebilir ve veri kaybini onler.
</details>

</details>

<details>

<summary>Elasticsearch Sorgu Tipleri</summary>

<details>
<summary>Match Query</summary>
Belirli bir metin terimini veya sorgu ifadesini arar ve eslesen belgeleri dondurur.
</details>

<details>
<summary>Term Query</summary>
Belirli bir alanin degerinin tam eslesme icin kullanilir.
</details>

<details>
<summary>Bool Query</summary>
Mantiksal operatorleri (AND, OR, NOT) kullanarak birden cok sorguyu birlestirmek icin kullanilir.
</details>

<details>
<summary>Range Query</summary>
Bir alanin belirli bir araliga dusup dusmedigini kontrol eder.
</details>

<details>
<summary>Fuzzy Query</summary>
Benzer ancak kesin olmayan terimleri aramak icin kullanilir.
</details>

<details>
<summary>Wildcard Query</summary>
Jokert karakterler (* veya ?) kullanarak eslesen terimleri bulmak icin kullanilir.
</details>

<details>
<summary>Prefix Query</summary>
Belirli bir on ek ile baslayan terimleri aramak icin kullanilir.
</details>

<details>
<summary>Autocomplete Suggester</summary>
Otomatik tamamlama islevselligi icin kullanilir ve kullanicinin yazmaya basladigi terimleri tamamlamak icin kullanilir.
</details>

<details>
<summary>Highlighting</summary>
Eslesen terimleri veya metni vurgulamak icin kullanilir.
</details>

<details>
<summary>Aggregations</summary>
Verileri toplamak, gruplamak ve analiz etmek icin kullanilir.
</details>

<details>
<summary>Ranking Functions</summary>
Elasticsearch'in belgeleri siralamak icin kullanabileceginiz cesitli siralama islevleri vardir.
</details>

<details>
<summary>Match Phrase Query</summary>
Metin teriminin tamamini iceren belgeleri dondurmek icin kullanilir.
</details>

</details>

---

### *Diger Konular*

<details>

<summary>Docker nedir ve ne için kullanılır?</summary>

Docker, uygulamaları geliştirmek, dağıtmak ve çalıştırmak için kullanılan bir yazılım platformudur. Docker, uygulamaları
bir konteyner içinde çalıştırarak uygulamaların yazılım ve donanım ortamlarından bağımsız olarak çalışmasını sağlar.
Böylece uygulamanın farklı ortamlarda sorunsuzca çalışması mümkün olur.

</details>

<details>

<summary>api nedir ? acilimi nedir</summary>

API'nin açılımı olan Application Programming Interface, Uygulama Programlama Arabirimi anlamına gelir.

Bir yazılımın başka bir yazılım tarafından kullanılmasını sağlayan bir dizi tanımlamalar ve protokoller kümesidir.
API'ler, farklı yazılım sistemleri arasında veri alışverişi yapmayı, işlevsellik sağlamayı veya iletişimi
kolaylaştırmayı amaçlar.

Iki programin birbiriyle iletisime gecmesini saglar.

</details>

<details>

<summary>rest api vs soap fark?</summary>

**RESTful**

Bu muhtemelen en yaygın türdür ve HTML ve JSON gibi standart web protokollerini kullanır. Kullanımı kolaydır ve
başlamanıza yardımcı olacak çok sayıda kitaplık mevcuttur.

**SOAP**

SOAP, Simple Object Access Protocol’ü (SOAP) kullanır ve uygulamaların XML mesajları kullanarak iletişim kurmasını
sağlar. RESTful kadar yaygın değildir, ancak daha fazla özellik ve işlevsellik sunar.

</details>

<details>

<summary>Web socket nedir ? ne için kullanılır ?</summary>

WebSocket: Bu yöntem, web sayfasındaki bir tarayıcı ve bir başka yapı arasında bir bağlantı kurar ve bu bağlantı
sayesinde tarayıcı anlık olarak bilgi alarak ekranı güncellemesini sağlar. Böylece, web sayfasının yenilenmesine gerek
kalmadan ekran anlık olarak güncellenebilir.

</details>

<details>

<summary>Exception vs Error arasindaki fark nedir?</summary>

1. **Exception (Istisna):**
   - Genellikle programin normal akisinin disindaki bir durumu belirtir.
   - Programin calisma zamaninda ortaya cikan ozel bir durumu temsil eder.
   - Ornekler arasinda dosya bulunamamasi, bolme hatasi (zero division error), tip hatasi (type error) gibi durumlar bulunabilir.
   - Genellikle programcinin kontrolu altinda islenebilir ve try-catch (veya try-except) bloklari kullanilarak ele alinabilir.

2. **Error (Hata):**
   - Genellikle daha ciddi durumlari belirtir.
   - Programin calisma zamaninda ortaya cikan bir hata veya sorunun genel bir adidir.
   - Sistem seviyesinde veya programin mantiksal yapisinda bir sorunu ifade edebilir.
   - Ornekler arasinda hafiza hatasi (memory error), sintaks hatasi (syntax error), isim hatasi (name error) gibi durumlar bulunabilir.
   - Genellikle programcinin kontrolu disinda olup, programin calismasini durdurabilir.

Ozetle, "exception" genellikle programcinin beklenmeyen durumlarla basa cikmasina izin veren ve programin devam etmesine olanak taniyan bir mekanizmayi ifade ederken, "error" genellikle daha ciddi ve genellikle programin devam etmesine izin vermeyen sorunlari ifade eder. Ancak bu ayrim, bazi durumlarda kullanimlarinin ortustugu ve baglamin onemli oldugu bir konsepttir.

</details>

---

### *Code*

<details>

<summary>Ciktisi ne olur?</summary>

```java
public class Test {
    public static void main(String[] args) {
        Base obj = new Child();
        obj.func();
    }

    public static class Base {
        public Base() {
            func();
        }

        public void func() {
            System.out.println("Inside base");
        }
    }

    public static class Child extends Base {
        public Child() {
            func();
        }

        public void func() {
            System.out.println("Inside child");
        }
    }
}
```

```java
Cevap:
Inside child
Inside child
Inside child
```

</details>

<details>

<summary>Ciktisi ne olur?</summary>

```java
class C1 {
   int x = 50;
}

class C2 extends C1 {
   int x = 40;
}

public class Check {
   public static void main(String[] args) {
      C2 c2 = new C2();
      System.out.println(c2.x);

      C1 c1 = new C1();
      System.out.println(c1.x);

      C1 c3 = new C2();
      System.out.println(c3.x);
   }
}
```

```java
Cevap:
40
50
50
```

</details>
