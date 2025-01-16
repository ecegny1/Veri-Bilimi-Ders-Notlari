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

## VsCode uygulaması
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

Makine Öğrenmesi : Elde edilen bilgiden öğrenilebilen, algoritmalarla ilgilenen yapay zekanın bir alt dalıdır. 6 adımdan oluşmaktadır.

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
1. String : Metinsel ifadeleri tanımlamak için kullanılmaktadır. Örneğin ; "Ali" , string türünde tanımlanmış ve Ali değeri atanmış bir değişkendir. Bir ifadenin tırnak içinde ("") belirtilmiş olması, string ifade olduğu anlamına gelmektedir.
2. Integer : Tam sayıları tanımlamak için kullanılmaktadır. Örneğin; yas = 25, yaş değişkenine 25 sayısı atanmıştır. 
3. Float : Ondalıklı sayıların tanımlanmasında kullanılır. Örneğin; sicaklik = 25,5.  Sıcaklık değişkenine 25,5 atanmıştır. 
4. Boolean : 2'li ifadelerde True, False olarak atanmaktadır.

Veri tipinin ne olduğundan emin olunamadığında type() ifadesi kullanılıp parantez içine değişken yazılarak değişkenin türünü öğrenebiliriz. 

!! Dikkat edilmesi gereken bir diğer husus ise kodlama dillerinde türkçe karakter kullanımına önem verilmesi ve ingilizce karakterle kodlama yapılmasıdır. 

 # Lineer Regresyon 

Veri bilimi de regresyona örnek olarak gösterilebilmektedir. Veriye düzgün çizgiler çizdirebilmek veri biliminin tanımıdır diyebilir ve lineer regresyonu şu şekilde de tanımlayabiliriz:

Bir veya daha fazla bağımsız değişken (özellik) ile bir bağımlı değişken (tahmin edilmek istenen değer) arasındaki doğrusal ilişkiyi modellemektedir.  

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

```bash
model.fit(veri_adi[["veri1"]], veri_adi["veri2"])
```











