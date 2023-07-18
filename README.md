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

<details>

<summary>Stateful vs stateless nedir?</summary>

Stateful yapı, bir programın durum bilgisini saklayan ve bu duruma göre işlem yapan bir yapıdır. Stateful yapılar, geçmiş işlemlere bağlı olarak çalışan uygulamalar için kullanılır

ornek/ Bir anne alisveris sepetindeki tum urunleri ve evdeki tum urunleri bilir

Stateless yapı ise, her işlemi bağımsız olarak ele alan ve önceki işlemlerle bir ilişkisi olmayan bir yapıdır. Stateless yapılar, her işlemi bağımsız olarak ele alan ve hızlı yanıt veren uygulamalar için tercih edilir.

ornek/ Bir cocuk sadece canin istedigi urunleri alir

</details>

<details>

<summary>JDK ve JRE arasındaki farklar nelerdir?</summary>

JRE, Java runtime editioni bir java uygulamasını çalıştırmak için gerekli olan java komponentlerini ve kütüphanelerini içeren içersinde JVM de kurulu olan programa denir.

JDK, Java ile yazılım geliştirmek için ihtiyaç duyulan yazılım kitlerini içinde bulundurur. .java uzantılı dosyaların compile edilip .class uzantılı ara dosyaların oluşmasına olanak sağlar. JDK, içerisinde JVM,JRE ve Java Compiler'ını bulundurur.

</details>

<details>

<summary>Super ve this kavramları nedir?</summary>

1. **`super`**: Bir alt sınıfta üst sınıfın metotlarını veya değişkenlerini kullanmak için kullanılan bir referansdır. Alt sınıfın kendi metotlarında, üst sınıfın metotlarına erişmek için **`super`** anahtar kelimesi kullanılabilir. Aynı şekilde, alt sınıfta üst sınıfın değişkenlerini kullanmak için de **`super`** anahtar kelimesi kullanılır.
2. **`this`**: Bir sınıfın kendi nesnesine erişmek için kullanılan bir referanstır. Özellikle, bir sınıfta tanımlı olan değişkenlerle aynı isimli parametrelerin kullanıldığı durumlarda, **`this`** anahtar kelimesi kullanılarak sınıfın kendi değişkeni ifade edilir.

</details>

<details>

<summary><strong>Object oriented prensipleri nelerdir?</strong></summary>

1. Encapsulation (Kapsülleme): Verilerin ve işlevlerin bir arada tutulması ve gizlenmesi anlamına gelir. Bu prensip, verilerin ve işlevlerin nesnelerle ilgili olduğu ve diğer nesneler tarafından doğrudan erişilemez olduğu anlamına gelir. Bu, güvenli bir kod yazmak için önemlidir. or/ Araba sınıfı, verileri (marka, model, renk, hız vb.) ve fonksiyonları (hareket ettirmek, durdurmak, hızını artırmak veya azaltmak) bir arada tutar ve gizler. Bu şekilde, başka sınıfların doğrudan arabayla ilgili verilere veya fonksiyonlara erişmeleri engellenir.
2. Inheritance (Kalıtım): Bir sınıfın özelliklerinin, başka bir sınıfa aktarılması anlamına gelir. Kalıtım, kodun yeniden kullanılmasına olanak tanır ve sınıflar arasındaki ilişkileri belirler. Alt sınıflar, üst sınıfların özelliklerine sahip olabilirler. or/ Araba sınıfının, bir sedan sınıfı veya bir SUV sınıfı gibi alt sınıfları olabilir. Bu alt sınıflar, arabaya özgü özelliklerin yanı sıra kendi özelliklerine de sahip olabilirler.
3. Polymorphism (Çok biçimlilik): Çok biçimlilik, nesnelerin farklı biçimlerde davranabilmesi anlamına gelir. Aynı yöntem adı, farklı sınıflarda farklı şekillerde uygulanabilir. or/ Araba sınıfı, bir araba hareketi fonksiyonu içerebilir. Sedan sınıfı veya SUV sınıfı, arabayı farklı şekillerde hareket ettirebilir. Örneğin, sedan araba normal bir şekilde hareket edebilirken, SUV araba off-road koşullarına uygun olarak hareket edebilir.
4. Abstraction (Soyutlama): Karmaşık bir sistemdeki detayların gizlenmesi anlamına gelir. Bu prensip, sınıfların arasındaki bağımlılığı azaltır ve kodun daha anlaşılır olmasını sağlar. or/ Araba sınıfı, sadece arabayla ilgili özellikleri ve fonksiyonları içerir. Bu, başka sınıfların arabaya bağımlılığını azaltır ve kodun daha anlaşılır olmasını sağlar.

</details>

<details>

<summary>Method Overloading ve Method Overriding nedir?</summary>

Method Overloading: Aynı isimli farklı parametrelerle ayrı ayrı tanımlanan birden fazla metodun kullanılmasıdır. Bu durumda, aynı isimli farklı metotlar, farklı parametreler alarak aynı sınıf içerisinde tanımlanabilirler. Bu sayede, metot isimleri aynı kalır ve farklı amaçlar için kullanılabilirler.

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

Method Overriding: Bir sınıfta tanımlanan bir metot, alt sınıflar tarafından aynı isim ve parametrelerle yeniden tanımlanırsa, bu durumda Method Overriding gerçekleşir. Bu sayede, alt sınıfın aynı isimli metodunu çağırdığımızda, üst sınıfın değil, alt sınıfın metodunun çalıştırılması sağlanır.

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

<summary>equals() ve == arasındaki fark?</summary>

equals() bir methoddur ve değişkenler arasındaki değer kontrolünü yapar.

\== ifadesi ise değişkenlerin referanslarını karşılaştırır.

</details>

<details>

<summary>DAO nedir?</summary>

DAO, Data Access Object'ın kısaltmasıdır. Bu, bir yazılım uygulaması ile veritabanı arasındaki iletişimden sorumlu olan bir tasarım desenidir. DAO, uygulamanın veritabanına bağımlılığını azaltmak ve uygulama kodunu daha okunaklı, bakımı kolay ve test edilebilir hale getirmek için kullanılır.

Dao da crud islemleri yapilir

</details>

<details>

<summary>Dependency injection yöntemleri nelerdir?</summary>

*   **Dependency injection yöntemleri nelerdir?**

    Bağımlılığını en aza indirmek için kullanılır.

    1.  Constructor Injection: Bu yöntemde, bir bileşenin bağımlılıkları, bileşenin bir yapılandırıcı metodu kullanılarak enjekte edilir. Bu yöntem, bir sınıfın başlatılması için gereken tüm bağımlılıkların açıkça belirtilmesini sağlar ve kodun okunaklılığını artırır.

        ```java

        @Component
        public class MailService implements MessageService {
        private Repository repository;

        @Autowired
        public MailService(Repository repository) {
            this.repository = repository;
        }

        ```
    2.  Setter Injection: Bu yöntemde, bir bileşenin bağımlılıkları, bileşenin özellikleri üzerinden enjekte edilir. Bu yöntem, bir bileşenin başlatılması sırasında, tüm bağımlılıkların belirtilmesini gerektirmez. Bunun yerine, bileşenin özellikleri çağrılarak enjekte edilir.

        ```java
           
        @Component
        public class MailService implements MessageService {
        private Repository repository;

        	 @Autowired
        	 public void setRepository(Repository repository) {
         this.repository = repository;

        ```
    3.  Interface Injection: Bu yöntemde, bir bileşenin bağımlılıkları, bileşenin bir arayüzü kullanılarak enjekte edilir. Bu yöntemde, bileşenin arayüzü, bağımlılıkları tanımlar ve bileşenin başlatılması sırasında, arayüzü uygulayan bir sınıfın enjekte edilmesi gereklidir.

        ```java
           
        @Component
        public class MailService implements IMessageService {

        ```

</details>

<details>

<summary>Abstraction Vs Interface fark?</summary>

Abstraction tum insanlarin kolu ve bacagi olmasi

Interface bazi insanlarin dovmeli bazilarin dovmesiz kollari olmasi gibi

! 1 abstraction olur n tane interface olur

</details>

<details>

<summary>Docker nedir ve ne için kullanılır?</summary>

Docker, uygulamaları geliştirmek, dağıtmak ve çalıştırmak için kullanılan bir yazılım platformudur. Docker, uygulamaları bir konteyner içinde çalıştırarak uygulamaların yazılım ve donanım ortamlarından bağımsız olarak çalışmasını sağlar. Böylece uygulamanın farklı ortamlarda sorunsuzca çalışması mümkün olur.

</details>

<details>

<summary>@service ve @component arasindaki fark nedir?</summary>

@Component'in bir bileşenin genel anlamda işaretlenmesi için kullanılması, @Service'in ise özellikle iş katmanı bileşenleri için kullanılmasıdır.

Ama yaptiklarinda bir fark yok.

**@Service, @Controller, @Repository = {@Component + some more special functionality}**

</details>

<details>

<summary>@controller vs @restcontoller arasindaki fark?</summary>

@RestController, veri döndürmek için JSON veya XML formatını kullanarak HTTP isteklerine yanıt verir, @Controller ise genellikle HTML sayfaları oluşturmak için kullanılır.

</details>

<details>

<summary>Normalizasyon Kurallari nelerdir? ve Ornek bir db tasarimi</summary>

Normalizasyon; veri tabanı tasarım aşamasında veri tekrarını, veri kaybını veya veri yetersizliğini önlemek için gerçekleştirilen işlemlerdir.

Normalizayon uygulanan veri tabanlarının performansı artar, sabit diskteki boyutu azalır ve tablolarda ki satır ve sütun sayısı azalacağından veri tekrarı önlenmiş olur. Özellikle silme, güncelleme gibi işlemler de çıkabilecek sorunlar büyük oranda azaltılmış olur.

*   Normalizasyon Yapilmadan:

    Filmler

    | Film Adi              | Aciklamasi | Yonetmen | Kategori  | Tarih | Oyuncu 1 | Oyuncu 2 |
    | --------------------- | ---------- | -------- | --------- | ----- | -------- | -------- |
    | Yuzuklerin Efendisi 1 | ...        | Peter    | Fantastik | 2001  | Orlando  | Elijah   |
    | Dovus Kulubu          | ...        | David    | Dram      | 1999  | Brad     | Edward   |
*   Normalizasyon Yapilinca:

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

<details>

<summary>api nedir ? acilimi nedir</summary>

API'nin açılımı olan Application Programming Interface, Uygulama Programlama Arabirimi anlamına gelir.

Bir yazılımın başka bir yazılım tarafından kullanılmasını sağlayan bir dizi tanımlamalar ve protokoller kümesidir. API'ler, farklı yazılım sistemleri arasında veri alışverişi yapmayı, işlevsellik sağlamayı veya iletişimi kolaylaştırmayı amaçlar.

Iki programin birbiriyle iletisime gecmesini saglar.

</details>

<details>

<summary>rest api vs soap fark?</summary>

**RESTful**

Bu muhtemelen en yaygın türdür ve HTML ve JSON gibi standart web protokollerini kullanır. Kullanımı kolaydır ve başlamanıza yardımcı olacak çok sayıda kitaplık mevcuttur.

**SOAP**

SOAP, Simple Object Access Protocol’ü (SOAP) kullanır ve uygulamaların XML mesajları kullanarak iletişim kurmasını sağlar. RESTful kadar yaygın değildir, ancak daha fazla özellik ve işlevsellik sunar.

</details>

<details>

<summary>orm nedir?</summary>

ORM (Object-Relational Mapping), ilişkisel veritabanıyla nesne tabanlı programlama arasındaki uyumu sağlayan bir yazılım tasarımı ve programlama tekniğidir. ORM, veritabanı tablolarını nesne modele dönüştürmeyi ve veritabanı işlemlerini nesne tabanlı olarak gerçekleştirmeyi sağlar.

</details>

<details>

<summary>jpa nedir?</summary>

JPA (Java Persistence API), Java tabanlı uygulamalarda nesne tabanlı veri erişimi için bir API'dir. JPA, veritabanı işlemlerini gerçekleştirmek için ORM (Object-Relational Mapping) prensibine dayanır. ORM, ilişkisel veritabanı ile nesne tabanlı programlama arasındaki uyumu sağlar ve veritabanı işlemlerini nesneler üzerinden yapmayı mümkün kılar.

JPA, veritabanı tablolarını Java sınıflarıyla eşleştirir ve veritabanı işlemlerini gerçekleştirmek için standartleştirilmiş bir yöntem seti sunar. Bu sayede, geliştiriciler veritabanı işlemlerini SQL sorgularıyla değil, JPA'nın sağladığı API ile yapabilir. JPA, veri okuma, yazma, güncelleme ve silme gibi temel CRUD (Create, Read, Update, Delete) işlemlerini kolaylaştırır ve veritabanı işlemlerinin daha hızlı ve daha sürdürülebilir bir şekilde gerçekleştirilmesini sağlar.

JPA'nın popüler uygulamalarından biri Hibernate'dir. Hibernate, JPA spesifikasyonunu uygulayan ve JPA tabanlı veri erişimini sağlayan bir ORM çözümüdür.

Persistence, bilgisayar programlamasında verinin kalıcı bir şekilde saklanması ve erişilebilir olması anlamına gelir.

</details>

<details>

<summary>hibernate nedir?</summary>

JPA'nın popüler uygulamalarından biri Hibernate'dir. Hibernate, JPA spesifikasyonunu uygulayan ve JPA tabanlı veri erişimini sağlayan bir ORM çözümüdür.

</details>

<details>

<summary>JpaRepository, CrudRepository vs PagingeAndSortingRepository fark?</summary>

* CrudRepository sadece Crud işlemlerini barındırır.
* PagingAndSortingRepository sadece sıralama ve sayfalama fonksiyonlarını barındırır.
* JpaRepository, CrudRepository ve PagingAndSortingRepository sahip olduğu tüm fonksiyonları barındırır.

</details>

<details>

<summary>Solid ilkeleri?</summary>

#### S— Single-responsibility principle

**ÖZET**: Single responsibility prensibi sınıflarımızın iyi tanımlanmış tek bir sorumluluğu olması gerektiğini anlatmaktadır. Bir sınıf (nesne) yalnızca bir amaç uğruna değiştirilebilir, o amaçta o sınıfa yüklenen sorumluluktur, yani bir sınıfın yapması gereken yalnızca bir işi olması gerekir.

or/ Elbise mağazası sınıfı, yalnızca elbise stoklarını takip etmek ve elbise satışlarıyla ilgilenmekle sorumludur. Örneğin, elbiselerin stok seviyelerini güncellemek, yeni elbise eklemek, elbise satışlarını kaydetmek gibi işlemleri yapabilir.

#### O— Open-closed principle

**ÖZET**: Bir sınıf ya da fonksiyon halihazırda var olan özellikleri korumalı ve değişikliğe izin vermemelidir. Yani davranışını değiştirmiyor olmalı ve yeni özellikler kazanabiliyor olmalıdır.

or/ Elbise mağazası sınıfı, yeni elbiselerin eklenmesine açık olmalıdır. Yeni bir elbise türü eklenmek istendiğinde, mevcut mağaza sınıfı değiştirilmeden yeni elbise türü sınıfı oluşturularak eklenir.

#### L— Liskov substitution principle

**ÖZET**: Kodlarımızda herhangi bir değişiklik yapmaya gerek duymadan alt sınıfları, türedikleri(üst)(ana) sınıfların yerine kullanabilmeliyiz.

or/ Elbise mağazasında farklı türde elbiseler bulunabilir, örneğin elbiseler, gömlekler, pantolonlar gibi. Bu durumda, her tür elbisenin kullanılabilirliği ve davranışları aynı olmalıdır. Yani, her tür elbise, mağaza işlemlerinde birbirinin yerine geçebilmelidir.

#### I— Interface segregation principle

**ÖZET**: Sorumlulukların hepsini tek bir arayüze toplamak yerine daha özelleştirilmiş birden fazla arayüz oluşturmalıyız.

or/ Elbise mağazası sınıfı, müşteriye satış yapmak, stok durumunu kontrol etmek ve raporlama gibi işlemleri gerçekleştirebilir. Ancak, tüm bu işlemler için tek bir genel arayüz kullanmak yerine, müşteri satışları için ayrı bir arayüz, stok kontrolü için ayrı bir arayüz ve raporlama için ayrı bir arayüz gibi daha özelleştirilmiş arayüzler oluşturulabilir.

#### D— Dependency Inversion Principle

**ÖZET**: Sınıflar arası bağımlılıklar olabildiğince az olmalıdır özellikle üst seviye sınıflar alt seviye sınıflara bağımlı olmamalıdır.

or/ Elbise mağazası sınıfı, doğrudan stok veritabanına veya satış işlemlerinin gerçekleştirildiği başka bir sınıfa bağımlı olmamalıdır. Bunun yerine, bir arayüz üzerinden bağımlılık oluşturulabilir ve ilgili işlemler bu arayüz üzerinden gerçekleştirilebilir. Bu sayede, farklı veritabanları veya satış işlemlerini gerçekleştiren farklı sınıflar, bu arayüzü uygulayarak kullanılabilir hale gelir.

</details>

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

<summary>spring bootta katmanli mimari</summary>

1. Veri Erişim Katmanı (Data Access Layer): Veri erişim katmanı, veritabanı veya diğer veri kaynaklarıyla etkileşimde bulunur. Bu katmanda, veritabanına erişim sağlamak için JPA (Java Persistence API) veya Spring Data JPA kullanılabilir. Veri erişim katmanı, veri tabanına sorguları yürütme, veri kaydetme/güncelleme/silme işlemlerini gerçekleştirme gibi görevleri yerine getirir.
2. Hizmet Katmanı (Service Layer): Hizmet katmanı, iş mantığının uygulandığı katmandır. İş kurallarının uygulandığı işlemler burada gerçekleştirilir. Hizmet katmanı, veri erişim katmanından gelen verileri işleyerek, iş kurallarına uygun şekilde işlemleri gerçekleştirir. Bu katmanda, işlemler genellikle iş mantığına odaklanır, veri erişimi ve veri dönüşümü gibi işlemler hizmet katmanı tarafından yönetilir.
3. Sunum Katmanı (Presentation Layer): Sunum katmanı, kullanıcı arayüzünün bulunduğu katmandır. Kullanıcı ile etkileşimi sağlayan API'ler, web sayfaları veya diğer istemci uygulamaları bu katmanda yer alır. Sunum katmanı, gelen istekleri alır, hizmet katmanı aracılığıyla işlemleri gerçekleştirir ve sonuçları kullanıcıya sunar.

* Sunum/Presentation için MVC - @Controller
* İş/business için Service -@Service
* Veri erişim/data access için Repository - @Repository

</details>

<details>

<summary>JPA (Java Persistence API) ve JPA Repository, Spring Framework ile birlikte kullanılan veritabanı erişim teknolojileridir. İkisi arasındaki fark?</summary>

Özet olarak, JPA Java tabanlı uygulamalarda veritabanı erişimi sağlayan bir spesifikasyonken, JPA Repository ise Spring Data JPA tarafından sunulan ve JPA teknolojisini kullanarak veritabanı işlemlerini kolaylaştıran bir bileşendir. JPA Repository, CRUD işlemlerini otomatik olarak sağlar ve özel sorguların tanımlanmasını kolaylaştırır.

</details>

<details>

<summary>Public, Private, Default and Protected ?</summary>

* `public`: Her yerden erişilebilir.
* `private`: Sadece ait olduğu sınıf içinden erişilebilir.
* `default` (package-private): Aynı paketten erişilebilir, farklı paketlerden erişilemez.
* `protected`: Ait olduğu sınıfın alt sınıfları ve aynı paket içindeki sınıflardan erişilebilir.

</details>

<details>

<summary>Spring ve Spring Boot arasındaki farklar ?</summary>

1. Proje Başlatma ve Yapılandırma: Spring, geliştiricilerin daha fazla yapılandırma seçeneği sunarken, Spring Boot, otomatik yapılandırmayı ve varsayılan ayarları kullanarak projenin hızlı bir şekilde başlatılmasını sağlar.
2. Bağımlılıklar ve Konfigürasyon: Spring, projenin bağımlılıklarını ve yapılandırmasını geliştiricinin belirlemesine olanak tanırken, Spring Boot, bağımlılıkları ve yapılandırmayı otomatik olarak yönetir. Bu sayede, geliştirici daha az ayar yaparak projeyi hızlı bir şekilde başlatabilir.
3. Standartlaştırma: Spring, esneklik ve özelleştirme seçenekleri sunarken, Spring Boot, standart yapılandırma ve proje yapısı sunarak projelerin hızlı bir şekilde geliştirilmesini sağlar. Spring Boot, konvansiyonları takip eden bir yapıya sahiptir ve "opinionated" (belirli bir yaklaşımı tercih eden) bir yaklaşım sergiler.
4. Geliştirme Deneyimi: Spring Boot, otomatik yapılandırma ve dahili sunucu gibi özellikleriyle geliştirme sürecini kolaylaştırır. Ayrıca, Spring Boot, aktif geliştirme topluluğu ve hazır örnek projeleri sayesinde başlangıç seviyesi ve hızlı prototip oluşturma için popüler bir seçenektir.

Sonuç olarak, Spring ve Spring Boot, Java tabanlı uygulamaların geliştirilmesinde kullanılan framework'lerdir. Spring, esneklik ve özelleştirme seçenekleri sunarken, Spring Boot ise hızlı başlatma, otomatik yapılandırma ve standartlaştırma gibi özellikleriyle projelerin hızlı bir şekilde geliştirilmesini sağlar. Spring

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

<summary>Web socket nedir ? ne için kullanılır ?</summary>

WebSocket: Bu yöntem, web sayfasındaki bir tarayıcı ve bir başka yapı arasında bir bağlantı kurar ve bu bağlantı sayesinde tarayıcı anlık olarak bilgi alarak ekranı güncellemesini sağlar. Böylece, web sayfasının yenilenmesine gerek kalmadan ekran anlık olarak güncellenebilir.

</details>

<details>

<summary>Java'da Set ve Map veri yapılarının ArrayList ile fark?</summary>

1. Veri Sıralaması: **`ArrayList`**, verileri eklenme sırasına göre saklar ve tekrarlı elemanlara izin verirken, **`Set`** verileri sırasız bir şekilde saklar ve tekrarlı elemanlara izin vermez. **`Map`** ise anahtar-değer çiftlerini saklar ve her anahtarın yalnızca bir kez bulunmasına izin verir.
2. Eleman Erişimi: **`ArrayList`**, indeks numaraları kullanılarak elemanlara erişimi destekler. **`Set`** ve **`Map`** ise elemanlara anahtar değerleriyle erişimi destekler. Her bir elemanın benzersiz bir anahtarı olduğu için, hızlı erişim sağlarlar.
3. Tekrarlı Elemanlar: **`ArrayList`** aynı elemanın birden fazla kez bulunmasına izin verirken, **`Set`** ve **`Map`** her elemanın yalnızca bir kez bulunmasına izin verir.
4. Performans: Eleman ekleme ve silme işlemlerinde **`ArrayList`** daha hızlıdır, çünkü elemanların sırasını korumak için fazladan bir maliyeti yoktur. Ancak, elemanlara erişimde **`Set`** ve **`Map`** daha hızlıdır çünkü anahtar değerlerini kullanarak doğrudan elemanlara erişebilirler.

</details>

<details>

<summary>ArrayList and a LinkedList arasindaki fark?</summary>

**`ArrayList`** indeks tabanlı erişim ve sıralı veri depolama için daha uygundurken, **`LinkedList`** dinamik ekleme ve silme işlemleri için daha uygundur.

</details>

<details>

<summary>Stack ve Heap memory Arasındaki Fark Nedir?</summary>

Eğer program esnasında boyutları bildirilmiş değişmez bir değer kullanıyorsak _stack_, değişebilir bir değer kullanıyorsak _heap_ bizim için uygun olacaktır. _Stack_ ve _heap_ kullanımları farklı ve dikkat edilmesi gereken bir konudur. _Stack_ kullanılır ve işi bittikten sonra kendini otomatik olarak bellekten yok eder. Fakat _heap_‘te bu işi siz yapmalısınız.

Genel olarak, stack hafızası genellikle yerel değişkenler, metod çağrıları, işaretçiler gibi programın çalışma zamanında dinamik olarak değişmeyen verileri depolamak için kullanılırken, heap hafızası daha büyük ve dinamik olarak değişen veri yapılarını, nesneleri ve veri yapısı örneklerini depolamak için kullanılır.

</details>

<details>

<summary>Mutable ve Immutable nedir ?</summary>

Immutable (değişmez), nesneler bir kez oluşturulduktan sonra içeriği değiştirilemeyen sınıflardır. Tam tersi olarak, değiştirilebilen sınıflar da Mutable (değişebilir) sınıflardır. Kısacası Immutable nesneler değişmeyen nesnelerdir. Onları oluşturursun, fakat onları değiştiremezsin.

</details>

<details>

<summary>Multithreading nedir ?</summary>

Multithreading'in avantajları:

1. Performans Artışı: Multithreading, iş parçacıklarını eşzamanlı olarak çalıştırarak programın daha hızlı çalışmasını sağlar.
2. Paralel İşlemler: Birden fazla iş parçacığı sayesinde farklı görevler aynı anda yürütülebilir, bu da paralelizmi sağlar.
3. Daha iyi Yanıt Süresi: Multithreading, kullanıcı girişlerine daha hızlı yanıt verir ve daha duyarlı bir kullanıcı deneyimi sağlar.
4. Kaynak Verimliliği: İş parçacıklarının çekirdekler arasında dağıtılması, işlemci kaynaklarının daha verimli kullanılmasını sağlar.
5. İletişim ve Paylaşım: İş parçacıkları arasında bilgi ve veri paylaşımı yapabilir, iletişim kurabilirsiniz.

Multithreading'in dezavantajları:

1. Yarış Koşulları: Birden fazla iş parçacığı aynı kaynağı değiştiriyorsa, yarış koşulları ve veri uyumluluğu sorunları ortaya çıkabilir.
2. Senkronizasyon Zorlukları: İş parçacıkları arasında senkronizasyon gerektiğinde, senkronizasyon mekanizmalarını doğru şekilde kullanmak karmaşık olabilir.
3. Hata Ayıklama: Multithreading hataları genellikle daha zor tespit edilebilir ve hata ayıklama süreci daha karmaşık olabilir.
4. Kaynak Tüketimi: Birden fazla iş parçacığı, işlemci ve bellek kaynaklarını daha yoğun bir şekilde kullanır. Gereksiz iş parçacığı oluşturma veya verimsiz kodlamalar performans sorunlarına neden olabilir.
5. Karmaşıklık: Multithreading, programın karmaşıklığını artırabilir. İş parçacıklarının doğru bir şekilde senkronize edilmesi ve yönetilmesi gereklidir.

Sonuç olarak, multithreading'in avantajları arasında performans artışı, paralel işlemler, daha iyi yanıt süresi ve kaynak verimliliği bulunurken, yarış koşulları, senkronizasyon zorlukları, hata ayıklama zorlukları ve kaynak tüketimi gibi dezavantajları da vardır. Doğru bir şekilde kullanıldığında multithreading, verimli ve hızlı çalışan uygulamaların geliştirilmesini sağlar.

</details>

<details>

<summary>Spring IOC nedir?</summary>

Spring IOC (Inversion of Control), Spring Framework'ün temel bir prensibidir ve bir tasarım desenidir. IOC, bir bileşenin (bean) oluşturulması, yapılandırılması ve yönetilmesi sürecinin kontrolünü programcıdan alarak, bu görevi Spring Framework'e devretmeyi sağlar.

IOC'nin temel felsefesi, bağımlılıkların tersine çevrilmesidir. Geleneksel olarak, bir bileşen diğer bileşenlerle doğrudan ilişkilerini kurar ve bunları oluşturur veya yönetir. Ancak, IOC ile bileşenlerin bağımlılıkları tersine çevrilir ve Spring konteyneri tarafından yönetilen bir IOC konteyneri kullanılır.

Spring IOC, aşağıdaki şekillerde sağladığı avantajlara sahiptir:

1. Bağımlılıkların Yönetimi: IOC sayesinde, bileşenlerin bağımlılıklarını yönetmek kolaylaşır. Bileşenler, Spring konteynerine tanımlanır ve bağımlılıkları otomatik olarak çözülür.
2. Gevşek Bağlılık: IOC, bileşenler arasındaki bağımlılığı gevşek hale getirir. Bileşenler, aralarında sıkı bağlantılar oluşturmak yerine, Spring konteyneri tarafından yönetilen arayüzler veya sözleşmeler üzerinden etkileşimde bulunurlar.
3. Test Edilebilirlik: IOC, bağımlılıkları enjekte etme mekanizması sunar, bu da bileşenlerin daha kolay test edilmesini sağlar. Bağımlılıkların taklitleri (mocks) kullanılarak bileşenlerin test edilmesi daha kolay hale gelir.
4. Modülerlik: IOC, bileşenlerin bağımsız olarak geliştirilmesini ve yeniden kullanılmasını sağlar. Bileşenlerin işlevselliği birbirinden bağımsız olarak geliştirilebilir ve daha sonra IOC konteyneri tarafından birleştirilir.

Inversion of control;

* Strategy Pattern
* Service Lacator Pattern
* Factory Pattern
* Dependency Injection

gibi mekanizmalarla uygulanabilir.

</details>

<details>

<summary>Spring Bean nedir?</summary>

Spring Bean, Spring Framework tarafından yönetilen ve IOC konteyneri tarafından oluşturulan, yönetilen ve yapılandırılan bir nesnedir. Bean'ler, Spring uygulamalarında kullanılan temel yapı taşlarıdır ve Spring konteyneri tarafından oluşturulurlar ve yönetilirler.

Spring Bean'lerin temel özellikleri şunlardır:

1. Yaşam Döngüsü Yönetimi: Spring Bean'ler, IOC konteyneri tarafından yönetilen bir yaşam döngüsüne sahiptir. Konteyner, bean'in oluşturulması, yapılandırılması, kullanılması ve sonlandırılması gibi adımları otomatik olarak gerçekleştirir.
2. Bağımlılıkların Otomatik Çözülmesi: Bean'ler arasındaki bağımlılıklar, IOC konteyneri tarafından otomatik olarak çözülür. Bağımlı bean'ler, uygun şekilde enjekte edilir veya referansları çözülür.
3. Yapılandırma ve Ayarlanabilirlik: Bean'ler, Spring konteynerine yapılandırma metadataları ile tanımlanır. Bu metadatalar, XML veya Java tabanlı konfigürasyon dosyaları, Java Annotation'ları veya Spring Boot gibi modern araçlar aracılığıyla sağlanabilir. Bu sayede bean'lerin özellikleri, bağımlılıkları ve davranışları kolayca ayarlanabilir.
4. Ölçeklenebilirlik ve Modülerlik: Spring Bean'ler, uygulamaların ölçeklenmesi ve modüler bir yapıya sahip olması için kullanışlıdır. Bileşenlerin ayrı ayrı geliştirilebilmesi ve ardından IOC konteyneri tarafından birleştirilmesi sağlanır.

Spring Bean'ler, Spring Framework'ün sunduğu çeşitli özelliklerden yararlanabilirler. Örneğin, AOP (Aspect-Oriented Programming) ile güvenlik, transaksiyon yönetimi, önbellekleme gibi ilave işlevselliği uygulamak mümkündür.

Spring Bean'leri, IOC konteynerine tanımlanan bir isim veya tip aracılığıyla elde edebilir ve uygulamanın farklı bölgelerinde kullanabilirsiniz. Bu sayede bean'lerin oluşturulması ve yönetimi Spring tarafından otomatik olarak gerçekleştirilirken, programcılar bean'lerin işlevselliği üzerinde odaklanabilir ve kolayca uygulama geliştirebilir.

</details>

<details>

<summary>Java'da static ve final nedir ve nerelerde kullanılıyor. Örnek verebilir misin?</summary>



static`ve`final\` anahtar kelimeleri, Java programlama dilinde farklı amaçlar için kullanılan önemli kavramlardır.

1.  `static` Anahtar Kelimesi:

    * `static` anahtar kelimesi, bir değişkenin veya metotun sınıfa ait olduğunu belirtmek için kullanılır. Bu, o değişkenin veya metotun sınıfın herhangi bir örneği olmadan kullanılabileceği anlamına gelir.
    * `static` değişkenler, sınıfa ait olan değişkenlerdir ve her bir örneği tarafından paylaşılırlar. Değişkenin son değeri, tüm örnekler arasında aynıdır.
    * `static` metotlar, sınıfa ait olan metotlardır ve sınıf adıyla doğrudan çağrılabilirler. Bunlar örneklerle ilişkili olmadığından, sınıfın durumunu değiştiremezler.&#x20;
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


2.  `final` Anahtar Kelimesi:

    * `final` anahtar kelimesi, bir değişkenin, metotun veya sınıfın değiştirilemez olduğunu belirtmek için kullanılır.
    * `final` değişkenler, bir kez değer atandıktan sonra değiştirilemezler. Sabit değerlere sahip değişkenlerdir.
    * `final` metotlar, alt sınıflar tarafından ezilemezler. Yani, bu metotlar alt sınıflar tarafından değiştirilemez veya yeniden uygulanamaz.
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

<summary>@ComponentScan, @Component, @Bean, @Repository, @Service, @Controller ve @RestController annotation neden kullanıyoruz?</summary>

Java Spring framework'ü, uygulama geliştirme sürecini kolaylaştıran ve düzenleyen bir dizi annotasyon (işaretleyici) sağlar. İşte bu annotasyonlardan bazılarının kullanım amacı:

1. `@ComponentScan`: Bu annotasyon, Spring uygulamasının bileşenlerini (component) taramak için kullanılır. Belirtilen paket veya paketlerdeki sınıfları tarayarak, Spring tarafından yönetilen bean'leri bulur ve otomatik olarak yaratır.
2. `@Component`: Bu annotasyon, bir sınıfın bir Spring bileşeni olduğunu belirtmek için kullanılır. Spring, bu annotasyonu gördüğünde ilgili sınıfı bir bean olarak yönetir ve Spring uygulaması içinde kullanılabilir hale getirir.
3. `@Bean`: Bu annotasyon, bir metodu Spring tarafından yönetilen bir bean olarak kaydetmek için kullanılır. Genellikle yapılandırma sınıflarında veya @Configuration annotasyonu ile işaretlenmiş sınıflarda kullanılır. Bu şekilde, ilgili metot tarafından dönülen nesne Spring konteynerine dahil edilir ve uygulama içinde kullanılabilir hale gelir.
4. `@Repository`: Bu annotasyon, veri erişim katmanı (data access layer) sınıflarını belirtmek için kullanılır. Bir veritabanına erişmek, sorguları yürütmek veya veri işleme işlemlerini gerçekleştirmek gibi veri tabanı işlemleriyle ilgili sınıfları işaretlemek için kullanılır.
5. `@Service`: Bu annotasyon, iş mantığı katmanı (business logic layer) sınıflarını belirtmek için kullanılır. Uygulama iş mantığını uygulayan servis sınıflarını ifade eder. Veri işleme, hesaplamalar, dış hizmetlere erişim vb. gibi işlemleri gerçekleştirmek için kullanılabilir.
6. `@Controller`: Bu annotasyon, Spring MVC (Model-View-Controller) tabanlı web uygulamalarında kullanılan kontrol sınıflarını belirtmek için kullanılır. İstemci taleplerini karşılamak, işlemek ve uygun bir yanıt döndürmek için kullanılır.
7. `@RestController`: Bu annotasyon, RESTful web hizmetleri sunmak için kullanılan kontrol sınıflarını belirtmek için kullanılır. Hem `@Controller` hem de `@ResponseBody` annotasyonlarının birleşimidir. Bu sayede, ilgili sınıfın tüm yöntemleri JSON veya XML gibi veri formatlarında yanıtlar üretir.

Bu annotasyonlar, Spring framework'ü içinde uygulama bileşenlerini belirtmek ve yapılandırmak için kullanılır. Bu sayede Spring, otomatik olarak sınıfları yönetir, bağımlılıkları çözer ve uygulamanın düzgün çalışmasını sağlar. Her annotasyonun kendine özgü bir amacı ve kullanım senaryosu vardır ve projenin ihtiyaçlarına göre doğru bir şekilde kullanılması önemlidir.

</details>

<details>

<summary>HashMap'ın çalışma mantığını anlatırmısın. Neden equal ve hashCode methodlarını kullanmalıyız?</summary>

1. `HashMap`'in Çalışma Mantığı:
   * `HashMap`, bir anahtar-değer ikilileri koleksiyonudur. Her bir anahtar, benzersiz olmalıdır ve değerlere karşılık gelir.
   * `HashMap`, anahtarların hash değerlerine dayanarak verileri hızlı bir şekilde depolar ve erişir.
   * Bir anahtarın hash değeri, `hashCode()` metodunu kullanarak hesaplanır. Bu hash değeri, `HashMap` içindeki bir hücreye (bucket) karşılık gelir.
   * Eşleşen anahtarlar aynı hücreye atanabilir. Bu durumda, bu hücrede bir zincir (linked list) oluşur.
   * `HashMap`, `equals()` metodu aracılığıyla anahtarların eşitliğini kontrol eder. Eşit olan anahtarlar aynı hücrede aynı zincirde bulunur.
   * Bir değere erişmek istediğimizde, ilgili anahtarın hash değeri kullanılarak hedef hücreye ulaşılır ve zincirde gezinilir.
2. `equals()` ve `hashCode()` Metodlarının Önemi:
   * `equals()` metodu, iki nesnenin içeriklerinin eşit olup olmadığını kontrol eder. `HashMap` içinde anahtarları karşılaştırmak için kullanılır.
   * `hashCode()` metodu, bir nesnenin benzersiz bir hash değerini döndürür. Bu değer, `HashMap` içindeki hücreye yerleştirme ve erişimde kullanılır.
   * `HashMap`, iki anahtarın eşit olduğunu belirlemek için `equals()` metodunu kullanır. Eğer `equals()` metodu doğru bir şekilde uygulanmazsa, aynı anahtarın farklı hash değerleri olabilir ve bu da beklenmeyen sonuçlara yol açabilir.
   * `hashCode()` metodunun doğru bir şekilde uygulanması, aynı nesnelerin her zaman aynı hash değerine sahip olmasını sağlar. Bu, aynı anahtarın aynı hücreye atanmasını ve doğru değerin elde edilmesini sağlar.
   * `equals()` ve `hashCode()` metodlarının birlikte kullanılması, `HashMap` içinde anahtarların doğru şekilde çalışmasını sağlar. Eğer bir anahtarın `equals()` metodunu geçersiz kılarsanız, aynı anahtarın `hashCode()` metodunu da geçersiz kılmanız gerekir.

`equals()` ve `hashCode()` metodlarının doğru bir şekilde uygulanması, `HashMap`'in anahtarlarını güvenilir ve etkin bir şekilde işlemesini sağlar. Bu nedenle, `HashMap` veya benzeri veri yapılarında anahtar olarak kullanılan sınıfların bu metodları düzgün bir şekilde uygulamaları önemlidir. Aksi takdirde, beklenmeyen sonuçlara ve hatalı veri erişimine neden olabilir.

</details>

<details>

<summary>Hibernate'de Fetch typelar nelerdir? Açıklayabilir misin?</summary>

Hibernate, Java tabanlı bir ORM (Object-Relational Mapping) çerçevesidir ve veritabanı işlemlerini kolaylaştırır. Fetch türleri, Hibernate'de nesne ilişkileri ve ilişkili verilerin nasıl alınacağını belirtmek için kullanılan kavramlardır. İşte Hibernate'de kullanılan fetch türlerinin açıklamaları:

1. `FetchType.LAZY`:
   * Bu fetch türü, ilişkili verilerin gerektiğinde yani kullanıldığında yüklenmesini sağlar.
   * İlişkili veriler, ilgili nesneye erişilmeye çalışıldığında veya verilerin çağrılması gerektiğinde yüklenir.
   * Bu, performans açısından faydalı olabilir çünkü ilişkili veriler yalnızca ihtiyaç duyulduğunda getirilir ve gereksiz yüklenme önlenebilir.
2. `FetchType.EAGER`:
   * Bu fetch türü, ilişkili verilerin ana nesne yüklenirken hemen yüklenmesini sağlar.
   * İlişkili veriler, ana nesnenin yüklendiği aşamada otomatik olarak getirilir.
   * İhtiyaç duyulmasa bile tüm ilişkili veriler yüklenir, bu nedenle büyük veri kümesi veya performans endişeleri oluşabilir.
3. `FetchType.DEFAULT`:
   * Bu fetch türü, belirli bir fetch türü belirtilmediğinde varsayılan olarak kullanılır.
   * Genellikle `FetchType.LAZY` ile aynıdır, yani ilişkili veriler gerektiğinde yüklenir.

Fetch türleri, Hibernate'in ilişkili nesneleri veritabanından nasıl getireceğini belirler. `LAZY` fetch türü, veri erişimini daha tembel bir şekilde yapar ve performansı artırabilirken, `EAGER` fetch türü, ilişkili verileri hemen getirerek veritabanı erişimlerini artırabilir. Seçilecek olan fetch türü, uygulamanın ihtiyaçlarına ve performans gereksinimlerine bağlıdır.

Fetch türleri, genellikle Hibernate'de ilişkili nesneler arasında `@OneToMany`, `@OneToOne`, `@ManyToMany` gibi ilişki annotasyonları kullanıldığında belirtilir. Bu annotasyonlar üzerinde `fetch` parametresi kullanılarak fetch türü belirtilebilir.

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

Bu örnek, `Order` sınıfında `OrderItem` ile `@OneToMany` ilişkisinin olduğunu ve ilişkili verilerin `LAZY` fetch türüyle yükleneceğini belirtir.

</details>

> Kafka vs RabbitMq

<figure><img src=".gitbook/assets/image.png" alt=""><figcaption></figcaption></figure>
