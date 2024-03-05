---
title : 'Programlamakategorideneme'
date : 2024-02-28T02:15:06+03:00
categories : ["programlama", "python", "temel kavramlar"]
draft : true
series: ["python-temel"]
series_order: 1

---

# Python Deep Dive

# Temeller

## Python Kurulumu ve Çalışma Ortamı

### Python Kurulumu

### Ide ve Metin Editörleri

## Temel Python Söz dizimi - syntax

Python'un sözdizimi, diğer programlama dillerine göre daha okunabilir ve basittir.

### → Yorum

Yorumlar, kodun okunabilirliğini arttırmak, kod içinde açıklamalar yapmak için kullanılır. Kod blokları gibi işleme konulmaz, yok sayılırlar.

<aside>
💡 Tek satır yorum : # işareti ile başlar

</aside>

```python
#Örnek python yorum satırı.
```

<aside>
💡 Çok satırlı yorumlar ise : “”” yada ‘’’ işaretleri ile çevrildir. Bu yapı stringlerde de kullanılır.

</aside>

```python
"""
çok satırlı
python
yorumu.
Bu yapıyı kullanıyoruz çünkü ide de alt satıra geçtiğimizi görmüş olmak yeterli
değildir. Alt satıra geçtiğimizi bazı imgelerle belirtmemiz gereklidir.
"""
```

### Değişkenler ve veri türleri

Python’da veri türlerini 4 başlıkta açıklayabiliriz.

int : integer → Tam sayılar.

float : float → Virgüllü / ondalık sayılar.

str : string → Metinsel ifadeler.

bool : boolean → Mantıksal (Doğru/yanlış).

Kullandığımız verinin ne tipte olduğunu bilmek son derece önemlidir. Çünkü yapacağımız işlemler buna bağlıdır. Örneğin “+” operatörünü sayısal veriler ile kullanırsak toplama işlemi gerçekleşir ancak string ifadeleriyle kullandığımızda iki değer ardarda yazılarak birleştirilir.

### → String Veri tipi :

Programlama dilinde metin parçaları string olarak adlandırılır. Her bir kelime de stringdir tek bir harf de. Stringler karakter dizilerilerdir.

Stringler birkaç farklı şekilde tanımlanabilirler.

<aside>
💡 Tek Tırnak kullanarak :

</aside>

```python
'String ifadesi'
```

<aside>
💡 Çift tırnak kullanarak :

</aside>

```python
"String ifadesi"
```

<aside>
💡 3lü tırnak yapısı

</aside>

```python
"""
string 
ifadesi
"""

'''
string 
ifadesi
'''
```

İlk iki yöntemde bir değişiklik yokken, 3lü tırnak yapısında satırları kullandığımıza dikkat edin. Bu örnekleri az önce öğrendiğimiz yorum ile karıştırmayın. Bunlar programlamada kullanacağımız string değişkenlerinin içerikleri olacak veriler. Örnek üzerinde görmeden önce print() fonksiyonunu öğrenelim.

### → Print() Fonksiyonu

Kısaca yazıcı gibi düşünebiliriz. İçerisine girilen değerin çıktısını verir. Ancak dikkat edilmesi gerekilen nokta içeri veri girerken belli başlı kurallara uymamız gerektiğidir.

```python
print("Hello World!")
```

Programlamada işlem sırası her zaman sağdan sola doğrudur. Çift tırnak arasındaki Hello World! yazısı önce okunur ve tırnak yapısı sayesinde string tipinde olduğu anlaşılır.  Ardından print fonksiyonu bize şu şekilde çıktıyı verir ; 

```python
Hello World!
```

Peki neden hem “ hemde ‘ kullanımı var ? İkiside aynı işe yarıyorsa ikisinin de olması saçma değil mi ?

Gelin bunu bir örnekle pekiştirelim. 

Print fonksiyonu ile String birleştirme işlemi “+” operatörü ile gerçekleştirilir yazdırmak istiyorum. Hadi deneyin bakalım.

![Untitled](Python%20Deep%20Dive%201fe1219d4de14d25954602f59ffc9228/Untitled.png)

Görüldüğü üzere + işareti kayboldu. Peki neden ? Veri tiplerini anlatırken bundan bahsetmiştim aslında. + operatörü stringleri ardarda birleştirmek için kullanılır. Stringler ise tırnak yapısı ile tanımlanır. Yazdığımız kodda mor ile işaretli kısım bir string , yeşil ile işaretli kısım ise başka bir string olarak anlaşıldı. Ve aradaki operatör + olduğu için birleştirildi.  Peki bir yolu yok mu bu karmaşıklığı çözmenin ? Farklı tırnak yapıları belki o kadar da kullanışsız değildir ha ? 

![Untitled](Python%20Deep%20Dive%201fe1219d4de14d25954602f59ffc9228/Untitled%201.png)

Bakın ne oldu. Tek tırnak ile başlayan string’imiz tek tırnak ile bitti. Böylece karmaşıklık kalmadı. String içerisinde başka bir string olamayacağı için + nın yakınındaki tırnaklar belirteç olarak tanımlanmadı. Böylece istediğimiz çıktıyı almış olduk. 

<aside>
💡 Boşluk karakteri de bir stringdir. Çünkü o da yer kaplar ihmal edilemez. “a” ne ise “ “ da odur.

</aside>

<aside>
💡 “” boş bir karakter dizisi iken. “    “ içerisinde boşluk barındıran bir karakter dizisidir. Bu farkı unutmayın.

</aside>

### → String Manipülasyonu

 

<aside>
💡 \n operatörü kendisinden sonra gelen ifadelerin alt satıra geçmesini sağlar.

</aside>

![Untitled](Python%20Deep%20Dive%201fe1219d4de14d25954602f59ffc9228/Untitled%202.png)

<aside>
💡 + operatörü metinleri ardarda yazarak birleştirir.

</aside>

![Untitled](Python%20Deep%20Dive%201fe1219d4de14d25954602f59ffc9228/Untitled%203.png)

String ifadelerinin sonunda yada başında boşluk bırakmadığımızda yazımda oluşan duruma dikkat edin. Kimi zaman kelimeleri boşluklu, kimi zaman bitişik yazdırmamız gerekecek.

![Untitled](Python%20Deep%20Dive%201fe1219d4de14d25954602f59ffc9228/Untitled%204.png)

Peki + operatörü olmadan nasıl birleşti bu stringler ? Python’un özelliklerinden biri. Dikkat edin her dilin kendine özgü syntaxleri vardır. Her özellik her dilde olmayabilir. Ancak + işareti kullandığımızda kodlarımız daha okunaklı ve düzenli oluyor.

<aside>
💡 * Çarpma operatörü ile stringler birden fazla kez yanyana yazılabilir.

</aside>

### → Input() Fonksiyonu

Input fonksiyonu için şu benzetmeyi yapabiliriz. Print fonksiyonu bir yazıcının çıktı işleviyse input ise tarayıcı işlevidir. Kullanıcıdan veri almamızı sağlar. 

![Untitled](Python%20Deep%20Dive%201fe1219d4de14d25954602f59ffc9228/Untitled.jpeg)

Program önce yeşil kısımdaki input içeriğini bize verdi. Bizde değer olarak bizden istediğii adımızı yazdık. Ardından print fonksiyonunu bizden aldığı veri ile birlikte yazdırdı. Print fonksiyonu ile inputu birbirlerine + operatörü ile bağladık.

```python
name = input("Adın ne ?")
```

Bu örnekte ise name adında bir değişken oluşturduk. Input fonksiyonu önce Adın ne ? yazısını kullanıcıya gösterdi ve alınan değeri name değişkenine atadı. 

### → len() Fonksiyonu

len fonskiyonu içerisine girilen dizinin uzunluğunu hesaplar. Giriş verisi stringdir çıkış verisi ise integerdır.

![Untitled](Python%20Deep%20Dive%201fe1219d4de14d25954602f59ffc9228/Untitled%205.png)

1.Satırda sağdan sola doğru ilerleyelim. String değeri tırnak içerisinde olduğu için string değişkeni tanımlandı ve len fonksiyonu ile uzunluğu hesaplandı. Hesaplanan 6 değeri çıktı verildi.

4.satırdaysa denemedeneme2 birleşimi sağlandı 13 değeri çıktı alındı. 

Değişkenler aslında her daim kullanılan bir kavramdır. Örneğin input fonksiyonunda girdiğimiz değer geçiçi bir değişkende depolanır. Compiler bu geçici değişkeni bizden gizler, ancak verinin ramde geçici depolanabilmesi için bir değişkene atanmış olması gerekmektedir. Değişkenlerin sözel sayısal vs farklı farklı türleri vardır. Üstte len fonksiyonu için a ve b gibi birkaç değişken kullanmıştık. Değeri değişkene atadığımızda bu değeri sonsuz kez kullanabiliriz. Oysa inputun içine girilen geçici değişken sadece tek kullanımlıktır.

![Untitled](Python%20Deep%20Dive%201fe1219d4de14d25954602f59ffc9228/Untitled%201.jpeg)

name isminde bir değişken atayıp bu değişkende input tarafından girilen değeri tutacağız.

Önceki bilgilerimizide birleştirirsek 

![Untitled](Python%20Deep%20Dive%201fe1219d4de14d25954602f59ffc9228/Untitled%202.jpeg)

Görüldüğü üzere tek bir veri ile hem ismi yazdırdık hemde ismin uzunluğunu öğrendik. 

![Untitled](Python%20Deep%20Dive%201fe1219d4de14d25954602f59ffc9228/Untitled%203.jpeg)

Girilen isim name değişkenine atanır. Len fonksiyonunda girilen name değişkeninin uzunluğu hesaplanır ve length değişkenine atanır. Ardından length değişkeni çıktı alınır. 

Değişken atamak tıpkı bir telefon defteri gibidir. Bir numara kaydedildiğinde tekrar tekrar her amaçla kullanılabilir.

Adındanda anlaşılabileceği gibi değişkenler yani variable değiştirilebilir.

### → Integer Veri tipi

Tam sayılardan oluşan veri tipleridir.

### → Float Veri tipi

Virgüllü sayılardan oluşan veri tipleridir.

### → Sayısal Veri tiplerinin Manipülasyonu / Matematiksel Operatörler

![Untitled](Python%20Deep%20Dive%201fe1219d4de14d25954602f59ffc9228/Untitled%204.jpeg)

input ile kullanıcıdan verileri aldık. A değişkeni : 3 , B değişkeni ise : 5 girdisini aldı. İki variable’ın değerlerini takaslamak istiyoruz bu yüzden swap için kullanacağımız C isimli bir variable oluşturduk. Aktarım tıpkı fonksiyonlardaki gibi sağdan soladır. A değeri C ye atandı. B’nin değerini A’ya atadık. Sırada A’nın orjinal değerini B’ye aktarmak kaldı. A’nın orjinal değerini C’de yedeklemiştik. Onuda B’ye aktardık.

Bunu a bardağındaki kahveyi b bardağındaki çay ile değiştirmek gibi düşünebiliriz. Aktarım için bir swap bardağına ihtiyacımız olacak.

## Değişken Adlandırma

Değişken adı tek bir kelimeden oluşmaktadır. Yani birden fazla kelime arada boşluk olacak şekilde yanyana gelemez. Örneğin user name gibi. user_name olabilir. user_Name olamaz. Caps’e dikkat.

Sayılar değişken isimlerinin başında yer alamaz. 1number olamaz, number1 olabilir.

Fonksiyon isimleri değişken adları olamaz, karışıklığa yol açar. Örneğin print, input gibi 

### Temel Operatörler