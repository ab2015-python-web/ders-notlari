Liste Oluşturmak

>>> liste = []

In [1]: teksayilar=[1,3,5]

In [2]: teksayilar[1]
Out[2]: 3



Pyhton'da array ayrı bir kütüphanedir. Listede farklı tipte veri tiplerini bir arada tutabiliyoruz. Bu diğer dillerdeki bağlı listelerle aynı işlevi görür.

ipyhton kuruldu.
pycharm community edition kuruldu.
github.com/lyk2014-python/bootstrap Usage altındaki kodlar çalıştırıldı.

----
listenin öğe sayısını,  len() fonksiyonu yardımıyla elde edebiliriz:

In [1]: isimler=["doga","halit","emre"]

In [2]: print len(isimler)
3

----
Listeye Öğe Eklemek

Python’da herhangi bir listeye öğe eklemek için append() metodundan yararlanabiliriz.

In [3]: isimler.append("fatih")

In [4]: print isimler
['doga', 'halit', 'emre', 'fatih']

In [5]: print len (isimler)
4

----
in Deyimi
In [6]: for i in range(10):
   ....:     print i
   ....:     
0
1
2
3
4
5
6
7
8
9

in deyimini kullanarak bir şeyin başka bir şeyin içinde olup olmadığını sorgulayabiliriz:

In [7]: isimler
Out[7]: ['doga', 'halit', 'emre', 'fatih']

In [8]: "ayse" in isimler
Out[8]: False

In [9]: "doga" in isimler
Out[9]: True

In [10]: for isim in isimler :
   ....:     print isim
   ....:     
doga
halit
emre
fatih

---
Liste Öğelerine Erişmek

In [1]: sayilar=[11,22,30,15,14,12]

In [2]: sayilar[2]
Out[2]: 30

In [3]: sayilar[0:3]
Out[3]: [11, 22, 30]

In [4]: sayilar[3:]
Out[4]: [15, 14, 12]

In [5]: sayilar[::]
Out[5]: [11, 22, 30, 15, 14, 12]

In [6]: sayilar[-1]
Out[6]: 12

In [7]: sayilar[-2] #sondan 2.elemana eriştik -2 diyerek
Out[7]: 14


In [8]: a="Python"

In [9]: print a[2:]
thon

----
Fonksiyon Tanımlamak
Python'da fonksiyon tanımlarken def anahtar kelimesi kullanılır.

def fonk_adi():

Python'da fonksiyonlar parametre olarak  fonksiyon alabilirler.

--- Hmap

In [1]: sozluk={"elma":"apple","portakal":"orange"}

In [2]: sozluk["elma"]
Out[2]: 'apple'

ekleme..
In [3]: sozluk["bilgisayar"]="computer"

In [4]: sozluk
Out[4]: {'bilgisayar': 'computer', 'elma': 'apple', 'portakal': 'orange'}

silme..

In [5]: del sozluk["elma"]

In [6]: sozluk
Out[6]: {'bilgisayar': 'computer', 'portakal': 'orange'}

---Demo --
sozluk = {"elma": "apple", "portakal": "orange"}

while True:
    istek = raw_input("bir kelime giriniz : ")

    if istek in sozluk:
        print sozluk[istek]
    else:
        istek2 = raw_input("yokmus bir kelime ekleyiniz")
        sozluk[istek] = istek2
----

Python kitapları indirebilinecek github linki = https://github.com/lyk2014-python/pykitap

---Class'lar---
class Window (object):
  pass    # en baş obje,window class'ı yaratıyoruz ve onun boş olduğunu pass ile belirtiyoruz

w1=Window()
w2=Window()  #Window class'ından obje yaratıp w1 ve w2'ye atamış olduk.

Python dilinde özel anlamı olan metodlar vardır.BUnlardan biri de __init__ metodudur.BU metod java dilindeki constructur ile aynı göreve sahiptir.
BU metod 2 parametre alır ,ilk aldığı parametre yaratılan nesnedir.

Örn= def __init__(self,title):
   self.title=title             # Buradaki self,javadaki this'e karşılık gelmektedir.

w1=window("python kursu")
w2=window("chrome")
  print w1.title
  print w2.title

--maximize örneği

def maximize(self):
   self.height=1920 #max height

>>w1=Window("dogan cecen")
>>w1.title
  'dogan cecen'
>>w1.maximaze()
>>w1.height
  1920

--örnek
 class Kisi(object):
   def __init__(self,isim):
   self.isim=isim
 class Ogrenci(kisi):
   pass
   

(devamı eklenecek)
