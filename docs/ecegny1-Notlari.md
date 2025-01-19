# BT Akademi Veri Bilimi Ders Notları

## Eğitmen :  M. Ali Bayram

Böyle bir eğitime başlarken teknik bilgileri edinmenin yanısıra pratik yapmakta çok önemlidir. 

Bu nedenle bildiğiniz teorik bilgilerinizi uygulayabilmeniz veri bilimi alanında ilerlemenizde büyük katkı sağlayacaktır.

Teorik bilgilere geçmeden önce bilgisayarınızda veri bilimine dair nelerin kurulu olması gerektiğinden hangi platformlardan ne amaçla yararlanabileceğinizden bahsetmek gerekir. 

Öncelikle her profesyonel insan bu işe kendini adamaya karar verdiğinde amatörce başlar, bu nedenle en büyük tavsiyemiz yaptığınız çalışmaları paylaşmaktan asla kaçınmayın.

Peki nerede pratik yapacak, kodlarınızı nerede mi yazacaksınız? İşte size çalışabileceğiniz iki harika platform:

## Google Colab 

https://colab.research.google.com/ 
Bu linkten gmail adresiniz ile hesap oluşturabilir ve kod çalışmalarınızı burada gerçekleştirebilirsiniz.

Google Colab'e ek olarak;

## VsCode Uygulaması

Bu uygulamayı bilgisayarınıza indirerek de yine kod çalışmalarınızı buradan da gerçekleştireebilirsiniz. 
VsCode için ise "https://code.visualstudio.com/download" bu linki kullanabilir, bilgisayarınız için uygun sürümü indirebilirsiniz. 

Dosyalarınızı kaydederken kullanmış olduğunuz programlama diline göre kaydetmelisiniz. Örneğin, Python ile bir kod yazdıysanız kayıt edeceğiniz dosya uzantısı .py olmalıdır. 

Kodlarınızı açıklamak için kod bloklarınızın içine açıklamalar eklemek isterseniz tek satırlık yorumlar için # kullanabilir veya çok satırlı bir yorum yazacaksanız """ """ şeklinde üç çift tırnak kullanmalısınız. 

VsCode Jupyter Notebook ile çalışıyorsanız, uzantınız .ipynb olmalıdır.

Tavsiyemiz her türlü platforma aşina olmanız ve kullanılabilirliğinizi ne kadar arttırabilirseniz konfor alanınız genişleyecek, çalışmalarınız ise daha üst kademelere taşınacaktır. 

## Peki ya bu platformlardaki kodlarımızı halka açık bir şekilde nerede yayınlayabiliriz?

"https://github.com/" Github platformuna, VsCode veya Google Colab'e giriş yaptığınız e-mail adresiniz ile kayıt olursanız yaptığınız çalışmaları daha konforlu bir şekilde paylaşabilirsiniz.

Bunlara ek olarak amacımız makine öğrenmesini, derin öğrenmeyi anlamak ve veri bilimine adım atarak ileri düzey projeler oluşturabilmek. 
Bu projelerimizin yapıtaşlarından biri ise elde ettiğimiz verilerdir. Başlangıç düzeyindeki bir veri bilimci için en büyük problem "Nasıl veri bulacağım, nasıl verilerle, neler yapacağım?" sorularına yanıt bulmaktır.

Öncelikli olarak hazır çalışmaları inceleyebilir, hazır veri setleri üzerinden çalışmalarınızı gerçekleştirebilirsiniz. 
Bunun için ise "Kaggle" : https://www.kaggle.com  ve "Hugging Face" :https://huggingface.co/ platformlarını inceleyebilir, verisetlerini indirebilir ve kendi çalışmalarınızı yapabilirsiniz.
Dilerseniz kaynak erişimine açık sitelerden örneğin "TÜİK, KAP, IETT, vb. veri sitelerinden kendi ihtiyaçlarınız doğrultusunda verilerinizi excel formatında kendinize göre düzenleyebilir ve excel formatını ".csv" olarak kaydederek yazacağınız kodlar için veri seti olarak kullanabilirsiniz.

## Yapay Zeka Nedir?

Yapay zeka, verilen bilgilere göre bir sonraki adımı tahmin eden bir sistemdir. 
Belli bir yapıyı, belli bir bütünü oluşturan dallardan, birimlerden her birine örüntü denir. 
Sentez ise bir araya getirmek, parçalardan bütün oluşturmaktır. 
Örüntü bulmaya çalıştığımız şey, ulaşmaya çalıştığımız hedef olarak adlandırılabilir. Örüntü olmazsa yapay zeka olamaz.

## Yapay Zeka ve Makine Öğrenmesi ile İlgili Bazı Kavramlar

Veri : Elde edilen bilgi olarak tanımlanabilir. Verinin boyutu ne kadar artarsa yapılan yorumun başarısı da bir o kadar artar. Verideki özellikler, sütunlar, verinin boyutu ne kadar geliştirilirse bakış açısı o kadar artar. Yorumun doğruluk oranı o kadar artar. 

İstatistikte Veri ikiye ayrılmaktadır:
  1. Numerik Veri
  2. Kategorik Veri
     
Not: Kategorik veri ile lineer bir şey çizmek kolay değildir.

Analitik Düşünme : Parçalara ayırarak detaylı bakabilmektir. 

Veri Analizi : Günümüz dilinde eldeki olayı anlamak olarak kullanılabilmekle birlikte, veri analizi elimizdeki verilerle olayları anlayabilmektir.

Veri Bilimi : Veri analizinin yanısıra veri analizinde elimizde bir bilgiyi analiz edebilirken, veri biliminde amaç elde olmayanı tahmin etmektir.

## Makine Öğrenmesinin Temelleri

Makine Öğrenmesi : Elde edilen bilgiden öğrenilebilen, algoritmalarla ilgilenen yapay zekanın bir alt dalıdır. Makine öğrenmesi bir modeldir ve o modeldeki sayılardan oluşmaktadır.  6 adımdan oluşmaktadır.

  1. Problemin Belirlenmesi : Çözülmek istenen temel sorun nedir?
  2. Veri Toplama
  3. Veri Temizleme/ Hazırlama
  4. Özellik Mühendisliği
  5. Modelin Değerlendirilmesi
  6. Sonuçların Sunulması ve Aksiyon Alınması

Veri Maskeleme (Anonimleştirme): Toplanan veriler kişisel veriler olabileceğinden maskeleme olmalıdır. 

Eğer elde edilen veriler gerçek verilerse veri temizleme/hazırlama yani ön işlem adımı bu tür verilerde daha az yapılır. 

## Sigmoid Fonksiyonu :

Matematikte ve makine öğrenmesinde yaygın olarak kullanılan, S şeklindeki  bir eğriye sahip olan ve özellikle lojistik regresyon ve sinir ağlarında kullanılan bir fonksiyondur. 
Fonksiyonun matematiksel formülü şu şekildedir: 

![](https://www.gstatic.com/education/formulas2/553212783/tr/sigmoid_function.svg)

x : Sigmoid fonksiyonuna koymak istediğimiz sayıdır. 0 ile 1 arasında yer almaktadır. 
e : Doğal logaritma tabanı olan eular sayısıdır, yaklaşık değeri 2.71828'e eşittir.

Yukarıda verilen formülün amacı sayıları bir düzene oturtmaktır. 

## Sınıflandırma modellerinde tahminlerin doğruluğunu(accuracy) değerlendirmek için kullanılan temel kavramlar:

  * True Positive
  * False Positive 
  * True Negative
  * False Negative

Yalnız bazı durumlarda doğruluk ölçütleri her zaman doğru olmayabilir.

## Kayıp Fonksiyonu (Loss Function)

Makine öğrenmesi ve derin öğrenme modellerinde, modelin yaptığı tahminler ile gerçek değerler arasındaki farkı ölçmek için kullanılan matematiksel bir fonksiyondur. Modelin başarısızlık derecesini belirler ve amacı, bu hatayı minimize etmektir.

Regresyon Analizlerinde Mean Square Error(MSE) ve Mean Absolute Error(MAE) sıklıkla kullanılmaktadır. 

# Değişkenler

Veri biliminde değişkenler ele alınan gözlemlerdir. 

Örnek : isim = "Ece"

Bu örnek ele alındığında değişkenin adı isim, değişkene atanan değer Ece, atama operatörü ise ='dir.İsim değişkenini Ece'ye atıyoruz.  Değişken ve değer ile birlikte tanımlama işlemi yapılmaktadır. 

## Değişken Tanımlama 

Değişkenler tanımlanırken iki tane fonksiyon kullanılabilir. Bunlardan biri define(), diğeri ise declare() fonksiyonudur. Tanımlanmak istenen değişkenler parantez içlerine yazılmalıdır. 

## Değişken Türleri 

1. String : Metinsel ifadeleri tanımlamak için kullanılmaktadır. Örneğin ; "Ali" , string türünde tanımlanmış ve Ali değeri atanmış bir değişkendir. Bir ifadenin tırnak içinde ("") belirtilmiş olması, string ifade olduğu anlamına gelmektedir. Python'da tırnak içinde yazılmış her ifade string veri türüne girmektedir.
2. Integer : Tam sayıları tanımlamak için kullanılmaktadır. Örneğin; yas = 25, yaş değişkenine 25 sayısı atanmıştır. 
3. Float : Ondalıklı sayıların tanımlanmasında kullanılır. Örneğin; sicaklik = 25,5.  Sıcaklık değişkenine 25,5 atanmıştır. 
4. Boolean : 2'li ifadelerde True, False olarak atanmaktadır.

Veri tipinin ne olduğundan emin olunamadığında type() ifadesi kullanılıp parantez içine değişken yazılarak değişkenin türünü öğrenebiliriz. 

!! Dikkat edilmesi gereken bir diğer husus ise kodlama dillerinde türkçe karakter kullanımına önem verilmesi ve ingilizce karakterle kodlama yapılmasıdır. Buna ek olarak ise bütün adımları gerçekleştirip hiçbir zaman çalışmayan kodlara ise ölü kod denir.

 # Lineer Regresyon 

Veri bilimi de regresyona örnek olarak gösterilebilmektedir. Veriye düzgün çizgiler çizdirebilmek veri biliminin tanımıdır diyebilir ve lineer regresyonu şu şekilde de tanımlayabiliriz:

Bir veya daha fazla bağımsız değişken (özellik) ile bir bağımlı değişken (tahmin edilmek istenen değer) arasındaki doğrusal ilişkiyi modellemektedir.  

Lineer regresyon bir yapay zeka modelidir.

![](https://miro.medium.com/v2/resize:fit:1400/format:webp/1*sZl820GxVJwjHYzA4LObJw.png)

Lineer regresyonda 2 boyutlu bir uzayda 2 noktalı bir çizgi mevcuttur. Çizgi 2 boyutlu düzlemi/uzayı bölmektedir. Bu çizgi elde edilen gözlemler sayesinde çizilir ve her gözlem birer nokta ile gösterilir. Çizginin üzerinde veya çizgiye en yakın gözlem en doğru gözlem olmakla birlikte, gözlemlerin çizgiye olan uzaklıkları ise hata terimini(residual) ortaya koymaktadır. 

Lineer regresyon ile ilgili VsCode Jupyter Notebook'ta bir örnek yapmak istediğimizi varsayalım.

Öncelikle excelde çalışmak istediğimiz anlamlı veri setimizi oluşturalım, lineer regresyon için topladığımız verileri bir excel dosyasında satır ve sütun olarak tablolaştırarak derleyelim  ve excel dosyamızı lineer_regresyon.csv olarak kaydedelim. CSV uzantısı virgülle ayrılmışd değerler(comma seperated value) demektir. CSV dosyanızı vscode'da açtığınızda virgülle ayrılmış sütunlardan oluşan tablonuz karşınıza çıkacaktır. CSV dosyanızı açtığınızda bir satırda kaç virgül varsa o kadar sütun var demektir. 

Ardından Vscode veya colab çalışma ortamında çalışmamızı lineer_regresyon.ipynb olarak olması gereken ortama kaydedelim ve kodlarımızı yazmaya başlayalım.

Bu tür kod blokları ile çalışırken bize yardımcı olacak bazı kütüphaneler mevcuttur. Kodlarımızı yazmaya başlamadan önce onları indirmeli ve içe aktarmalıyız. 

1. Pandas ile gruplama, ekleme, birleştirme, kaynaştırma, bir araya getirme işlemlerini gerçekleştirebilir. Ayrıca bu kütüphane veri temizleme için veri doldurma, değiştirme ve varsayma özelliklerini de gerçekleştirebilirsiniz. Pandas kütüphanesi kullandığınız platformda yüklü değilse ;

```bash
pip install pandas
```
Yukarıdaki kod bloğu ile kütüphaneyi programınıza kurabilirsiniz. Ardından kullanabilmek için kütüphaneyi içe aktarmanız gerekmektedir, onun içinde ; 

```bash
import pandas as pd 
```
Kodunu kullanmalıyız. 

Çalışmamızda kullanabilmemiz için hazırlamış olduğumuz veri dosyamızı okuyalım. 

```bash
veri_adi = pd.read_csv("dosya_adi")
```
Aşağıdaki kod bloğunda parantez içine herhangi bir sayı yazarsak tablomuzdaki ilk  o kadar sayıdaki satırları ekrana yazdırır.

```bash
veri_adi.head()
```

2. Eğer verilerimizle grafik çizdirmek istersek aşağıdaki kodu kullanabiliriz. Fakat öncesinde grafik çizdirmek için sahip olmamız gereken kütüphanenin yüklü olduğundan emin olmalıyız, eğer yüklü değilse ;

```bash
pip install matplotlib
```
kütüphaneyi indirmeli. 

Ardından ;

```bash
import matplotlib.pyplot as plt 
```
kütüphaneyi yukarıdaki kod bloğu ile içe aktarıp ardından aşağıdaki kod bloğu ile grafiğimizi çizdirebiliriz.

```bash
plt.scatter(veri_adi["veri1"], veri_adi["veri2"])
plt.xlabel("Veri 1")
plt.ylabel("Veri 2")
plt.title("Scatter Plot")
plt.show()
```

Kodlamalardaki ana amacımız oluşturduğumuz modelleri tahminlemektir. Bir yapay zeka modeli formül ve formüldeki parametrelerden oluşmaktadır. Modeli oluşturabilmek için gerekli kütüphaneler yüklenmeli ve model ondan sonra oluşturularak test edilmelidir.

3. Numpy bilimsel hesaplamalar ve veri analizi için kullanılan güçlü bir kütüphanedir.Kurulu olmadığı durumlarda öncelikle indirmek gerekmektedir.
   
```bash
pip install numpy
```
Ardından kütüphaneyi içe aktarmalıyız.

```bash
import numpy as np
```

4. Tahminleme için kullanacağımız kütüphane Scikit-Learn(sklearn) kütüphanesidir. Scikit-Learn kütüphanesinin indirilmesi.

```bash
pip install scikit-learn
```
Ardından kütüphaneyi kullanılacak model ile birlikte içe aktarmalıyız.

```bash
from sklearn.linear_model import LinearRegression
```
Modeli tanımlayalım.

```bash
model = LinearRegression()
```
Modeli Eğitelim 

Modellerin ilk eğitilmesine pre-train denilmektedir. 
Elimizdeki verilerle bulduğumuz lineer regresyon denklemindeki (Y=ax+b+ϵ) a ve b'nin güncellenip doğru sonuca ulaşabilmemiz için a ve b'yi doğru şekilde bulmak için datayı fit ediyoruz. a ve b değişkenlei modelimizin parametreleri olarak adlandırılmaktadırlar.

```bash
model.fit(veri_adi[["veri1"]], veri_adi["veri2"])
```

Lineer regresyonda a=5, b=4 bu sayılar elimde varsa tahminleme yapabiliyorum. 

Modele tahmin etme fonksiyonu tanımladığımızda a ve b belli iken biz modele x'i verirsek model bize y'yi tahminleyecek.

```bash
def tahmin_et(x, a, b):
    y = a * x + b  # Doğru lineer regresyon formülü
    return y
```

## Lojistik Regresyon 

Kaç değişken kullanıldıysa o değişkenlerin = operatörü ile tek tek ataması yapılması gerekmektedir. Ardından lojistik regresyon tanımlanmaktadır.
Önce kaç a tanımlayacağını belirt ardından b'yi tanımla.
Ardından lojistik regresyon tanımlanır.
Her bir x(boyut) için ayrı ayrı değerlendirme gerçekleştirilir.

Örnek :

```bash
a1 = 2.5
a2 = 3.6
a3 = 4.6
a4 = 5.8
a5 = 9.6

b = 8.8

def lojistik_regresyon_(x, a1, a2, a3, a4, a5, b):
    #Doğrusal model: x[0] * a1 + x[1] * a2 + ... + x[4] * a5 + b
    y = a1 * x[0] + a2 * x[1] + a3 * x[2] + a4 * x[3] + a5 * x[4] + b
    return y
```

## Koleksiyonlar (Collections)

Birden çok veriyi bir arada tutmak için kullanılan veri koleksiyonlarıdır. 

## 1. Listeler (Lists)

Stringlerden oluşan listeler ve dinamik listeler olarak ikiye ayrılmaktadır. 
Sıralı ifadelerden oluşurlar.
Değiştirilebilir (Mutable) elemanlara sahiptirler. 
Aynı listede farklı türde elemanlar bulunabilir.
Yinelenen (duplicate) elemanlara izin verir.
Python dilinde listeler köşeli paratez ile belirtilmektedir. 

Örnek: 
```bash
alinacak = ["elma","armut","muz","çilek"]
```

## 2. Demetler (Tuples)

Demetler değişmeyecek verilerin kümelenmesinde kullanılırlar.
Demetler de listeler de olduğu gibi sıralı ifadelerden oluşmaktadır. 
Elemanlar değiştirilemez (immutable).
Farklı türde elemanlar içerebilirler.
Yinelenen elemanlara izin verilir.
Python dilinde demetler yuvarlak paratez ile belirtilmektedir. 

Örnek: 
```bash
alinacak = ("elma","armut","muz","çilek")
```

## 3. Kümeler (Sets)

Sırasız veri setleridir.
Elemanlar değiştirilebilir (mutable).
Yinelenen elemanlara izin verilmez.
Benzersiz elemanların saklanmasında kullanılmaktadır. 
Python dilinde kümeler süslü parantez ile ifade edilmektedir.

Örnek: 
```bash
alinacak = {"elma","armut","muz","çilek"}
```
## 4. Diziler (Arrays)

Diziler de birden fazla veriyi saklayan yapılardır.
Aynı türden elemanları içerir.
Koleksiyonların alt kümesi olarak görülebilir.
Sıra sayıları ve aynı olan verilerin bulundukları yerler farklıdır.

Örnek: 
```bash
alinacak = {"elma","armut","muz","çilek","elma"}
```

```bash
import numpy as np
dizi = np.array([1, 2, 3, 4, 5])
```

## 5. Dictionary (Sözlükler)

Elemanlar anahtar ve değer olarak tutulmaktadır. 
Sırasızdır (Python 3.6+ itibariyle sıralıdır).
Anahtar-değer (key-value) çiftleri şeklinde veriler saklanmaktadır.
Anahtarlar benzersizdir; ancak değerler tekrarlanabilir.
Etiketli veri saklama (örneğin, JSON formatı) gibi durumlarda kullanılmaktadırlar. 

Örnek:
```bash
my_dict = {"isim": "Ali", "yaş": 25, "meslek": "mühendis"}
```

# Döngüler

## 1. For Döngüsü

For döngüsünde sayısal değeri döngüye sokmak için "in range" ifadesi kullanılmaktadır. 

Örnek:
```bash
for i in range (1000):
  print ("Beni affet.")
```
- Bu döngü, range(1000) ifadesi sayesinde 0'dan başlayarak 999'a kadar toplamda 1000 kez tekrarlanır.
- Her döngüde i değişkeni bir önceki değerden bir artırılır.
- İlk döngüde i = 0
- İkinci döngüde i = 1
...
- Son döngüde i = 999
Her döngü iterasyonunda, ekrana "Beni affet." yazdırılır.
Bu işlem, toplamda 1000 kez tekrarlanır.

```bash
for i in range (1000):
i = 0
while i<1000:
  print ("Beni affet.")
```

- Bu bir for döngüsü, 0'dan 999'a kadar toplamda 1000 kez çalışır.
- Ancak, i = 0 satırı, i değişkenini her döngüde sıfırlamaktadır. Bu, for döngüsünün anlamını kaybetmesine neden olur.
- while i < 1000:

- For döngüsünün her iterasyonunda, i = 0 ile sıfırlandığından, bu while döngüsü sonsuza kadar çalışır.
- Çünkü i < 1000 her zaman doğru olur ve i hiçbir zaman artmaz (veya while döngüsü içinde artırılmaz).

- Sonsuz Döngü: Bu kod, sonsuz bir döngüye girer ve sürekli olarak "Beni affet." yazdırır. Çıkış tuşuna basmadıkça programdan çıkamazsınız.

Örnek :
```bash
for alinacaklar in alinacaklar_listesi:
```
Yukarıdaki örnek kodda kod listenin uzunluğu kadar döngüye girer. 
Koleksiyonun bütün elemanları için çalıştırırken kullanılır. 

# Koşul İfadeleri 

Koşul : Değişen durumun kontrolü için geçerlidiri kontrolün sağlanması için kullanılır.

## 1. If Koşul İfadesi

En temel koşul ifadesidir.
Döngü kapsamında olay gerçekleşir ve son bulur. 

Örnek :

```bash
if len(isim)<5:
  print ("İsim 5 karakterden küçüktür.")
else :
  print ("İsim 5 karakterden küçük değildir.")
```
Not: len() fonksiyonu, verilen bir dizinin (örneğin bir string'in) uzunluğunu döndürür.


## Komutlar 

Continue Komutu : Net olarak döngü içinde koşul sağlanırsa adım atlama komutudur. Her koşulda kullanılan bir komut değildir, belli koşullarda yazılmaktadır. 

Break Komutu : Döngüyü bitir komutudur. Döngü dışında da yazılabilir.

Continue ve break komutları döngü içinde yazılırlar ve genelde koşul içinde kullanılırlar.

## Operatörler

Operatörler değerleri değişkene atarlar. 
= : Atama operatörüdür.
== :Koşul durum sorgulama operatörüdür.

Operatörler koşul, matematiksel, mantıksal operatörler olmak üzere üçe ayrılmaktadırlar.

## Koşul Operatörleri
Koşul şu anda bilmediğimiz bir şey, koşul bir durum kontrolüdür.

Koşul operatörlerinde elde edilen cevap True veya False'dur. 
Ünlem(!) işaretini hangi operatörün başına koyarsak tersi anlamına gelmektedir.

Eşittir (==): İki değeri karşılaştırır ve eşit olup olmadığını kontrol eder. Örnek: a == b

Eşit Değildir (!=): İki değerin eşit olup olmadığını kontrol eder. Örnek: a != b

Not: Eşit (==) ve Eşit değil (!=) operatörleri bütün veri tipleri ile kullanılmaz fakat çoğu veri tipinde kullanılabilir. Bazı veri tipleri (örneğin, float ve int) karşılaştırıldığında küçük farklar nedeniyle beklenmedik sonuçlar verebilir. Bu nedenle, örneğin kayan noktalı sayılarla çalışırken dikkatli olunmalıdır.

Büyüktür (>): Bir değerin diğerinden büyük olup olmadığını kontrol eder. Örnek: a > b
Küçüktür (<): Bir değerin diğerinden küçük olup olmadığını kontrol eder. Örnek: a < b
Büyüktür veya Eşittir (>=): Bir değerin diğerinden büyük veya eşit olup olmadığını kontrol eder. Örnek: a >= b
Küçüktür veya Eşittir (<=): Bir değerin diğerinden küçük veya eşit olup olmadığını kontrol eder. Örnek: a <= b

Bir şeyin birden fazla koşulunun sağlanmasını isteriz.

## Matematiksel Operatörler
Toplama (+): İki sayıyı toplar. Örnek: a + b
Çıkarma (-): Bir sayıdan diğerini çıkarır. Örnek: a - b
Çarpma (*): İki sayıyı çarpar. Örnek: a * b
Bölme (/): Bir sayıyı diğerine böler. Örnek: a / b
Üs () veya Pow()**: Bir sayıyı üssünü alır. Örnek: a ** b
Mod Alma (%): Bölümün kalanını verir. Örnek: a % b

Örnek : 
```bash
i = 4 
if i % 2 == 0:
    print("Çift sayı")
else:
    print("Tek sayı")
```
## Mantıksal Operatörleri
Koşul ifadeleriyle çalışırken kullanılan operatörlerdir.

Genellikle koşul ifadelerinde birden fazla koşulu birleştirirken kullanılır.
3 ana mantıksal operatör vardır: 

- Ve (and(∧)), koşulun gerçekleşmesi için iki tarafında doğru olması gerekmektedir.
- Veya (or(∨)), koşullardan birinin sağlanması doğruluk açısından yeterlidir.
- Değil (not(')), koşulların sağlanamadığı durumlarda kullanılmaktadır.

Bunlar, koşul ifadelerinin (if-else gibi) sonucunu kontrol etmek ve daha karmaşık mantıksal ifadeler oluşturmak için kullanılır.

Örnek:
```bash
i = 8  
if i % 2 == 0 and i > 6:
    print("Çift ve 6'dan büyük")
else:
    print("Koşul sağlanmadı")
```
