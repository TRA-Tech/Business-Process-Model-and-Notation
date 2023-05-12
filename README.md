# Business Process Model and Notation (BPMN)
*İş Süreç Modelleme Notasyonu*, organizasyonların iş süreçlerini yönetmek ve modellemek amacıyla tasarlanan iş akış şemasıdır. Şirketlerde bulunan birçok birimin faydalanabileceği bir iş sürecinin başlangıç aşamasından son aşamasına kadar belirlendiği görsel modelleme dili kullanılmış akış şemalardır. BPMN, bir işlemi tamamlamak için gerekli faaliyetlerin ve bilgi akışının şema haline getirerek detaylandırılmasını sağlar. 

![cfe17b36-8a3a-467a-8260-c44b4bf89b6e](https://github.com/TRA-Tech/Business-Process-Model-and-Notation/assets/123966022/04a2a71e-ebfc-49fb-af2a-cd3a8e9421e6)


BPMN, iş akış sürecinin her bir aşamasının adım adım detaylandırılmasını sağlayarak belli bir sıralamayla ilerlenmesini sağlar. BPMN’ın amacı; rekabet avantajlarını arttırmak, iş akışında yeni ya da beklenmedik durumları gözlemleyebilmek için modeller oluşturmaktadır. 
BPMN ilk olarak 2004 yılından Business Process Management Initiative (BPMI) tarafından yayınlanmıştır. 2005 yılından BPMI ve BPMN organizasyonlarının birleşmesi ardından süreçler OMG (The Object Management Group) tarafından yönetilmeye başlamıştır. 2006 yılında OMG, BPMN Spesifikasyonu belgesi yayınladı. 2010 yılında BPMN 2.0 sürümü geliştirildi ardından 2013 yılında Aralık ayında yeni bir spesifikasyon sürüm yayınlandı. ISO tarafından resmi olarak yayınlanan BPMN 2.0.2 en son sürümüdür: *ISO/IEC 19510*

## Business Process Model and Notation (BPMN) Faydaları
BPMN, İş Süreç Modelleme Notasyonu, iş süreçlerini anlaşılır, dinamik ve tutarlı bir şekilde şemalaştırma imkânı sağlar. Bu sayede, BPMN ile iş sahipleri, iş analistleri, geliştiriciler gibi şirketin birçok biriminin yararlanacağı bir modelleme ortaya çıkar. 
Paydaşların da dahil edildiği bu süreçte, tespit edilen sorunların etkili ve efektif bir şekilde yanıt verilebilir ve öngörülen ya da öngörülmeyen her sorun karşısında modelleme şeması iş akışının aksamamasını sağlar. Kapsamlı ve bilgi bakımından zengin notasyonlar sebebiyle, teknik bir bilgi eksikliği olan ya da olmayan tüm paydaşlar iş akış sürecini kolayca anlayabilir. 

![BPMN-2](https://github.com/TRA-Tech/Business-Process-Model-and-Notation/assets/123966022/c2f49e2f-b61a-429d-9523-528f35e495c2)

Bu kapsamda iş sürecinin şirketler ve organizasyonlar bakımından birçok faydası bulunmaktadır: 

- OMG (The Object Management Group) konsorsiyumu tarafından geliştirilen bir endüstri standardı,
- İş Süreçleri Diyagramları sayesinde prosedürleri kolayca tanımlama ve anlama olanağı,
- İş paydaşlarının kolayca anlayabileceği standart bir şema sağlama,
- İş süreci tasarımı ile uygulama arasında sık sık görülen iletişim boşluğunu kapama,
- İş sürecinde meydana gelecek potansiyel karmaşıklıkları betimlemeye yetecek kadar kol ve güçlü,
- Kâr amacı gütmeyen bir kuruluş tarafından desteklendiği ve geliştirildiği için geniş araç desteğine sahiptir. 

BPMN, işletmelere iş süreçlerini anlama, belgeleme, iletişim kurma ve analiz etme konularında önemli avantajlar sağlamaktadır. 
 
## Business Process Model and Notation Nasıl Çalışır? 
BPMN, İş Süreç Modelleme Notasyonu; iş süreçlerini anlaşılır, dinamik ve tutarlı bir şekilde şemalaştırma imkânı sağlar. BPMN, iş süreçlerini modelleme dili dört kategoriye ayrılmaktadır: 

### Akış Elemanları (Flow Elements)
Akış elemanları, iş süreçlerinde bağlantı noktalarını ifade etmektedir. Üç çeşit akış elemanı bulunmaktadır: *Olay* (Event), *Aktivite* (Activity) ve *Geçit* (Gateaways). 

**Olaylar (Events)** 
- İş sürecindeki olayları temsil eder. Örneğin, başlangıç ve bitiş noktaları. 
- Olaylar; genel anlamda bir süreci başlatan, sürdüren ve tamamlayan tetikleyicilerdir. Olay türleri arasında mesaj türleri, hata uyarıları, sinyal, iptaller gibi birçok bağlantı yer alır. Olay tiplerine göre diğer sembolleri içeren dairelerle gösterilmektedir.

![9fedf54f-ccf1-469e-acd6-546675816a73](https://github.com/TRA-Tech/Business-Process-Model-and-Notation/assets/123966022/14b62d02-c9ca-4bc9-94da-b91a69dc78b0)

**Aktiviteler (Activity)**
- İş sürecindeki etkileşimleri temsil eder. Örneğin, görev ve yapılan işlemler.
- Bir kişi ya da sistem tarafından yapılan görevleri belirtir. Kenarları yuvarlak dikdörtgenle gösterilir. Alt iş süreçleri, telafiler gibi ek aktivitelerle daha detaylı hale getirilir. 

![5280decc-8129-49be-a01a-4aa7f4c25fd9](https://github.com/TRA-Tech/Business-Process-Model-and-Notation/assets/123966022/cca07e43-fd5e-40fd-8f0e-f7c2bbd8a6c3)

**Geçit (Gateaways)** 
- İş sürecindeki farklı yol ve yöntemleri temsil eder. Örneğin, bir seçim ya da birleştirme noktaları. 
- Koşullara ve olaylara bağlı olarak yolun düzenlenebileceği karar noktalarıdır. Elmas şeklinde gösterilirler. 

![efc2969c-a156-4f2a-89b5-de963a785cbd](https://github.com/TRA-Tech/Business-Process-Model-and-Notation/assets/123966022/bfeecb15-112a-4bdc-9e01-7540d302fb4d)

### Bağlantı Nesneleri (Connecting Objects)
Bağlantı nesneleri, akış elemanlarını birbirine bağlayan mesaj akışı, sıralama akışı gibi sembolleri ifade etmektedir. Dört çeşit bağlantı nesnesi bulunmaktadır: Sekans Akışları (Sequence Flow), Mesaj Akışları (Message Flow), İlişkilendirilmeler (Associations), Veri İlişkileri (Data Associations). 

![flows-1024x563](https://github.com/TRA-Tech/Business-Process-Model-and-Notation/assets/123966022/f7c9e25f-0b64-40e0-8867-21b5eb00f896)

**Sekans (Sıra) Akışları (Sequence Flow)**
- İş sürecinde bağlantılı noktaları temsil eder. Örneğin, bulunduğunuz noktayla bir sonraki noktanın nasıl bağlandığı. 
- Yapılacak aktivitelerin sırasını belirtirler. Düz ok şeklinde gösterilirler. 

**Mesaj Akışları (Message Flows)**
- Farklı havuzlar arasındaki mesajların nasıl taşındığını temsil eder.
- Bölümler ve departmanlar arasındaki mesaj akışını belirtirler. Olaylara veya aktivitelere bağlanmamalıdır. Ucu daire kesik çizgili ok ile gösterilmektedir.

**İlişkilendirmeler (Associations)**
- Bir akış nesnesi ile bir veri nesnesi arasındaki bağlantıyı temsil eder. 
- Bir nesne veya metnin bir olaya, aktiviteye veya ağ geçidine bağlanmasını sağlar. Kesik çizgi ile gösterilmektedir. 

### Kulvarlar (Swimlanes)
Kulvarlar, iş sürecinde yer alan katılımcıları ifade etmektedir. Havuz ve Şerit elementlerini kapsamaktadır. Dikdörtgen olarak gösterilmektedir. Swimlane'lar yatay ve dikey olarak iki türlü gösterimi bulunmaktadır. Anlam olarak aynıdır, temsil edilmeleri farklıdır. Yatay swimlane süreci, soldan sağa doğru akmaktadır. Dikey swimlane süreci, yukarıdan aşağıya doğru akmaktadır. 

**Havuz (Pool)**
- İş sürecindeki ana katılımcıları (rolleri ve departmanları) temsil eder. 
- Havuzların içerisinde kendi flow elementleri bulunmaktadır. Havuz flow elementleri, iş süreci boyunca havuzun yapması gereken işleri ifade etmektedir. Flow elementleri bulunmayan havuz türü de yer almaktadır. Bu tür havuz türüne *blackbox pool* denmektedir. Bu tür havuzlar, iş sürecinin dışındaki varlıkları temsil etmektedir. 

![lyNXJ](https://github.com/TRA-Tech/Business-Process-Model-and-Notation/assets/123966022/ea8334c8-3bc8-4fbc-9310-bf74d22e5efd)

**Şerit (Lane)**
- İş sürecindeki görev ve işlevleri temsil eder.
- Havuzun içerisinde yer alan şeritler, iş sürecinde hangi bölümlerden kimin ya da kimlerin sorumlu olacağını belirtir ve rol veya katılımcılar için aktiviteleri ve akışları gösterir.

### Artifacts 
Artifacts, iş sürecinde geliştiricilerin ayrıntılı olarak verdiği ek bilgileri ifade etmektedir. 
Üç çeşidi bulunmaktadır: Veri Nesneleri (Data Objects), Grup (Group) ve Açıklama (Annotation).

![bpmn-artifacts-symbol](https://github.com/TRA-Tech/Business-Process-Model-and-Notation/assets/123966022/4acd08f0-e8ab-447e-9443-8a2b805bbd07)

**Veri Nesnesi (Data Objects)**
- Bir aktivite ve akış sürecinde hangi verilerin gerektiğini ifade eder. 

**Grup (Group)** 
- Aktivitelerin mantıksal olarak gruplandırılmasını belirtir, ancak akışa hiçbir müdahalesi yoktur. 

**Açıklama (Annotation)** 
- Diyagramda belli kısımlarda daha fazla açıklama sağlar. 

## BPMN Diyagramı İçerisinde Yer Alan Alt Modeller 
BPMN, karmaşık iş süreçlerinin baştan sonuna kadar nasıl bir vizyonda ilerlediğine dair net bir içgörüye sahip olmanızı sağlar. İş süreçlerinde, performansı ve verimliliğinizi arttırmanıza ve süreçleri performansa dayalı olarak kolaylaştırmanıza yardımcı olur. Diyagramda yer alan ana katılımcıları gözlemleyebileceğiniz, hataları minimuma indireceğiniz süreçte inovasyona olanak sağlar. 

BPMN diyagramlarında teknik olan ya da teknik olmayan çeşitli hedefler ve farklı ana katılımcı kitleleriyle iletişim kurmak gerekir. BPMN alt modelleri, farklı katılımcıların diyagramın bölümlerini kolayca ayırt etmesini ve katılımcıların kendilerine uygun bölümleri bulmasını sağlamaktadır. 

BPMN alt model türleri üçe ayrılır: 

**Özel İş Süreçleri** 
- Özel iş süreçleri, belirli bir kuruluşa özel olup havuzları veya kurumsal sınırlar dışına çıkamaz. 

**Soyut İş Süreçleri** 
- Soyut İş Süreçleri, özel/iç süreç ve farklı katılımcı veya süreç arasında gerçekleşmektedir. Soyut İş Süreçleri, dış dünyaya özel süreçle etkileşim için gereken mesajların sırasını belirtmektedir. 

**İşbirliği İş Süreçleri**
- İki veya daha fazla iş birimi arasındaki etkileşimleri belirtmektedir. 

## BPMN'de Bulunan Diyagram Türleri 

**Koregrafi Diyagramı** 
- İki veya daha fazla katılımcı arasındaki etkileşimleri ifade etmektedir. Alt koreografilerle genişletilmektedir. 

**İşbirliği Diyagramı** 
- Birden fazla havu kullanılarak iki veya daha fazla süreç arasındaki etkileşimleri göstermektedir. İşbirliği diyagramında havuzlar, süreçler ve koregrafi kombinasyonları herhangi biri kullanılmaktadır. 

**Konuşma Diyagramı** 
- İşbirliği diyagramı basitleştirilmiş versiyonudur. İş süreci boyunca bir grup ilişkili mesaj alışverişini belirtmektedir. Alt konuşmalarla genişletilebilmektedir. 

İş süreçlerinde kullanılan diyagram türleri dışında iki farklı diyagram sınıflandırma türü de bulunmaktadır: 

**Basit Diyagramlar**
- Bu diyagram türü, temel araç setlerini kullanarak iş sürecinin anlaşılmasını kolaylaştırmaktadır. Temel araçlar; ana katılımcıların görevleri, geçiş noktalarını ve süreli etkinliklerin oluşturulmasında kullanılan zamanlayıcı unsurlarını içermektedir. Karmaşık diyagram modellerini de basitçe anlaşılması kolaylaşmaktadır. 

**Karmaşık Diyagramlar**
- Karmaşık diyagram türü, BPMN standardının bütün araç setlerini kullanmaktadır. BPMN standardının sağladığı araçların kullanılmasının avantajı, ana katılımcıların her iş durumunu tanımlayabilmesidir. Karmaşık diyagram türünde, katılımcıların BPMN araçlarına dair bilgisinin olması ve nasıl çalıştığını bilmesi ve araçların birbiriyle nasıl etkileşimde bulunduğunu detaylı bir şekilde bilmesi gerekmektedir. 










