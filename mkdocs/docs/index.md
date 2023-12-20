# Doğal Dil İşlemenin Temel Prensipleri



### Doğal Dil İşleme (Neuro Linguistic Programming-NLP)

Doğal dil işleme dil bilimi ve yapay zekanın ortaklaşa geliştirdiği çalışmalar sonucu hayatımıza girmiş bir terimdir. Doğal denmesinin nedeni insan ve makine dilinin farklı olduğunu ve aradaki farklı belirlemek içindir. Makineler için diller yazılım ve programlama dilleri iken; örneğin Java, Python gibi insanlar için ise konuşulan Japonca, İngilizce gibi doğal dillerdir.
Doğal dil işlemenin temel amacı konuşulan insan dillerinin kurallı yapısını makinelere öğretmek, yorumlatmak, işletmek ve üretmesini sağlamaktır. Dil işleme bu yetenekler üzerine ortaya çıkan bir disiplindir. Temel amacı insan-makine iletişimini arttırmak ve kolaylaştırmaktır. 
Dil işlemenin en eski örnekleri makineye verilen bir insan dilini başka bir insan diline çevirmesi örneğidir. Bu günlerde en çok kullanılan çeviri siteleri dil işlemenin sonucunda ortaya çıkmıştır. Çevrilen metinlerdeki başarı oranları NLP’ nin her geçen gün geliştiğinin kanıtıdır. 

Dil işlemedeki temel kavramlar ve işlemler ise şöyle sıralanabilir:



#### 1.	Tokenizasyon:
Bir metni daha anlamlı hale getirmek için kelimelere veya cümlelere bölme işlemine denir. Bu bölünen parçalara ‘token’ denir. Bu tokenler genellikle kelime, cümle veya karakter olabilir. Bu işlemin amacı metin verilerinin daha işlenebilir olması ve dil işleme algoritmaların yüksek verimlilikte sonuç almasını sağlamaktır. 

     Örneğin:
     Selam, nasılsın? İfadesinin tokenlara ayrılması:
     •	‘Selam’
     •	‘,’
     •	‘nasılsın’
     •	‘?’
Böyle gözükecektir. Böylece kelimeler üzerinden daha iyi işlem yapılabilir.


#### 2.	Morfolojik Analiz:

Morfolojik analiz, bir metindeki kelimelerin yapısını anlamak amacıyla eklerini, köklerini ve yapılarını inceleyen bir işlemdir.’ koşmak’ kelimesi ele alındığına kelimenin kökü olan ‘koş’ bulunur. Ek bulma örneklerinde ise ‘koştu’ kelimesinde ‘-tu’ geçmiş zaman eki bulunur. 

Morfolojik analiz, metin madenciliği, dil çevirisi, duygu analizi gibi uygulamalarda kullanılarak verilerin daha iyi işlenmesini ve derin anlamlar çıkarılmasını sağlar. 

Bu aşamada makinenin kafa karışıklığına neden olmamak için anlamsız ve kökü bulunmayan ‘ama’, ‘fakat’ gibi kelimelerin stop kelimesi olarak çıkarılması analizi hızlandırır ve daha anlamlı sonuçlara ulaşmada yardımcı olur.


#### 3.	Syntax (Söz Dizimi) Analizi:

Cümlenin gramatik yapısını anlamak için kullanılır. Cümleyi oluşturan morfolojik öğelere bakarak dilin kurallarına uyup uymadığının kontrolü yapılır. Böylece söz diziliminin anlamlı olup olmadığını ölçer ve düzenleyici süreç gerçekleştirir. 
Türkçede en basit şekilde özne, nesne ve yüklem bileşenlerinden oluşur. Cümle komplikasyonu arttıkça yer tamlayıcısı, zarf tamlayıcısı gibi bileşenler eklenir. Anlamları kuvvetleştirmek ve cümleleri birleştirmek için bağlaç, edat (ama, fakat, ve) gibi cümle dışı bileşenler bulunur.


#### 4.	Semantics(Anlam Bilim) Analizi:

Cümlelerin, kelimelerin, eklerin hatta köklerin anlamlarını ve bunların birlikte kullanımından çıkan anlamların neler olduğunu kavramaya yönelik yapılan işlemdir.


#### 5.	Sentiment(Duygu) Analizi:

Metnin içerisindeki duyguyu anlamak için kullanılır. Metnin pozitif, negatif veya nötr duygularından hangilerini içerdiği anlamak için kullanılır. 
Bu analizin en çok kullanıldığı yerlerden birisi ürün incelemeleri yorumlarıdır. 


#### 6.	Makine Çevirisi:

Google Translate veya benzeri çeviri siteleri gibi bir insan dilini başka bir insan diline çevirme işlemidir.


#### 7.	Bilgi Çıkarma:

Metin içerisinde bilgi çıkarmaya yarar. Örneğin haber sitelerinden alınan verilerin mekan, saat ve haber başlığına göre sıralaması yapılabilinir. 


#### 8.	Entity Recognition(Konsept Çıkarma):

Metin içerisinde geçen önemli öğeleri sıralamak, sınıflandırmak için kullanılır.


#### 9.	Metin Sınıflandırma:

Genellikle kategorileştirme işlemleri için kullanılır. En büyük örneği Spam kutularıdır.


#### 10.	Konuşma Tanıma:

Bu alanda ise ses verilerinin metin verilerine dönüştürüp işleme yapılır. Bu sistem bankacılıkta ve sekreterlikte önemli kolaylıklara neden olmuştur. Sekretere ihtiyaç duymadan birçok kolay işlem helledilebilinir.



# Doğal Dil İşleme Endüstri Uygulamaları

Doğal dil işleme birçok çeşit endüstriyel uygulama alanlarında kullanılmıştır. Müşteri ve ürün çeşitliliği fazla olan sektörlerde, yapay zekâ teknolojileri arasında yer alan, doğal dil işleme ve makine öğrenmesi çalışmaları oldukça artmıştır. Kullanılan uygulama alanlarından bazıları şunlardır:

### 1.	Finans Sektöründe Dil İşleme:

Tüm sektörlerde olduğu gibi finans sektörü için de şirket içi raporlama yapıları önemli bir ihtiyaçtır. Büyük operasyonel süreçlerin ilerleyebilmesi, yönetimsel kararların sayısal veriler ile desteklenmesi, çok fazla konunun ve ürünün anlaşılabilir hale gelmesi için görsel panoların oluşturulması finans sektöründe yer alan şirketlerin raporlama ortamlarına olan ihtiyaçlarını doğrudan arttırmaktadır.
Finansal raporlarda, müşteri geri bildirimleri ve haber makaleleri gibi metin verilerini analiz ederek önemli bilgiler çıkarma yapılmaktadır. 
Ek olarak bankacılıklarda kullanılan dil işleme tabanlı sekreterler işleri kolaylaştırmakta ve çalışan sayısını azaltmaktadır.


### 2.	Sağlık Sektöründe Kullanılması:

NLP kullanımı son yıllarda birçok farklı uzmanlık alanında önemli araştırmalara konu olmuştur. Bazı belirtilere göre teşhis koyma ve raporları yorumlama gibi birçok alanda kullanılmıştır. İnternette yapılan araştırmalara göre 5 yıl içerisinde oluşabilecek hastalıklar belirlenmiş ve ilaç sanayi o yöne yatırım yapmaya başlamıştır.
Ayrıca ilaç içeriklerini literatürden taratıp yeni içeriklerin oluşturulmasında katkıda bulunmuştur. İlaç etiketleri, besin takviyeleri, ilaçların ve takviyelerin güvenliği ve etkinliği hakkında bilgi sağlamaktadır.
Özellikle, hastaların tedavi süreçleri ve sağlık hizmetleri hakkındaki deneyimlerini anlamak için yapılan çalışmalar, sağlık hizmetlerinin kalitesini artırmak için kritik bir rol oynamaktadır.



### 3.	E-Ticarette Müşteri Hizmetleri ve Öneri Sistemleri:

Son yıllarda her zaman için her yerden ürün satın alma kolaylığı sağladığı ve ürünleri satın alan diğer kullanıcıların incelemelerinden kolayca ürün karşılaştırması sağladığından dolayı E-ticaret sitelerinden yapılan satın alma işlemleri oldukça artmıştır. Bu nedenle, e-ticaret platformları için müşteri yorumları, önemli bir veri kaynağı ve satış artırıcı bir faktör olarak karşımıza çıkmaktadır.
Müşteri yorumları, bir ürünün kalitesi, fiyat, teslimat süresi gibi özelliklerini değerlendirmek isteyen potansiyel müşteriler için önemli bir bilgi kaynağıdır. Bu nedenle, e-ticaret platformlarında müşteri yorumlarının varlığı, ürünlerin satın alma kararlarını önemli ölçüde etkilemektedir.

Müşteri yorumları, e-ticaret platformları için de önemli bir veri kaynağıdır. Bu yorumlar, satıcıların müşteri beklentilerini anlamalarına ve satışlarını artırmalarına yardımcı olur. Örneğin, müşteri yorumları incelenerek, hangi ürünlerin daha popüler olduğu, hangi ürünlerin iyileştirilmesi gerektiği gibi bilgiler elde edilebilir. Bu bilgiler, satıcıların ürün ve hizmetlerini geliştirmesine ve müşteri memnuniyetini artırmasına yardımcı olur.


## KAYNAKÇA

* 1)	https://aws.amazon.com/tr/what-is/nlp/
* 2)	https://bulutistan.com/blog/nlp-natural-language-processing/
* 3)	https://medium.com/@mehmethilmi81/nlp-temel-kavramlar-a862128e7e82
* 4)	https://tr.wikipedia.org/wiki/Do%C4%9Fal_dil_i%C5%9Fleme
* 5)	https://dergipark.org.tr/tr/download/article-file/207209
* 6)	https://acikerisim.sakarya.edu.tr/handle/20.500.12619/98832
* 7)	https://ekmob.com/blog/nlp-nedir-anlik-alarmlar-ile-verimlilik-ve-yonetim-stratejileri/#nlp-uygulama-alanlari
* 8)	https://acikerisim.sakarya.edu.tr/bitstream/handle/20.500.12619/98832/T10043.pdf?sequence=1
* 9)	https://dergipark.org.tr/tr/download/article-file/3299151
* 10)	https://istanbulbogazicienstitu.com/nlp-nedir-nlp-ne-demek

