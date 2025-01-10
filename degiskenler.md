# Değişkenler

_Bir ifadeye değişebilir başka bir ifade tanımlarlar._
_Değişken, bilgisayarın RAM'ine kaydedilir._

---

## 1. String Değişkenler (Metinsel Değişkenler)

```python
isim = "Alper"
```
_isim değişkeni Alper ifadesine atanır._

## 2. Integer Değişkenler (Tam Sayı Değişkenler)
_En çok kullanılan değişken tipidir._
```python
x = 3
```
_x değişkenine 3 Integer (Tam Sayı)'sını tanımlar._

## 3-Float Değişkenler (Ondalık Değişkenler)
_Float ondalık demektir._

```python
fiyat = 5.24
```

_fiyat değişkeni 5,24 float (ondalık)'ına atanır._

- **DİKKAT:** . yerine , kullanılırsa float değil tuple olur tuple sayıların sıra sıra dizilimidir._

## 4-Boolean Değişkenler (Mantıksal Değişkenler)
_Mantıksal Değikenler true yada false olur._

```python
alındımı = True
```
_alındımı değişkenini True'ya tanımlar._

```python
varmı = False
```
_varmı değişkenini False'a tanımlar._

# Örnek:

Kırtasiye sahibi olduğunuzu düşünün ve kırtasiyenize yeni bir kitap geliyor.

Kitabın Özellikleri: İsmi: 5 Adımda Java Script  Sayfası: 205 Fiyatı: 143,50 Yenimi: Yeni

Bu özellikleri değişkenlere tanımlayın. **(İlk önce kendiniz deneyin sonra çözümü okuyun ve yanlışlarınızı düzeltin)**

## Çözüm:

```python
İsim = "5 Adımda Java Script" #string
SayfaSayısı = 205 #integer
Fiyatı = 143.50 #float
Yenimi = True #boolean
```

# Değişkenlerin Türünü Anlama 
_**Type Fonksiyonu** değişkenlerin türünü anlamak için bir komuttur_

print(type(Fiyatı))
_Fiyatı değişkeni float olduğu için float çıktısı gelir_
