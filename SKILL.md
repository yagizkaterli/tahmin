---
name: tahmin
description: >
  Tahmin etmenin disiplini. Tetik: "tahmin edebilir misin", "sence ne olacak",
  "bil bakalim", "/tahmin", ya da bir is baslamadan once sonucunun ongorulmesi
  gerektiginde.

  Cekirdek ilke: TAHMIN, HATIRLAMA DEGILDIR. Kayitli olani soylemek tahmin
  degil erisimdir. Tahmin ancak YAZILI OLMAYAN yerde baslar -- ve ancak
  YANLISLANABILIR yazilirsa tahmindir.

  Her tahmin bir kayit birakir (isabet/iska); o kayit, ileride kurulacak
  ogrenen-modelin egitim verisidir. Yanlis tahmin degerlidir: modelin
  ogrendigi sey odur.
---

# tahmin — ongorunun disiplini

## 0 · TEK CUMLE

**Tahmin, hatirlama degildir.** Kayitli olani soylemek bir erisimdir; tahmin
ancak **yazili olmayan** yerde baslar.

## 1 · ILK FREN — "bu zaten yazili mi?"

*Olculmus dogum: ajan, operatorun fikrini uc kez "tahmin" etti. Ucu de makul,
ucu de yanlis. Operatorun cevabi: "bunlar yeni degil, konusmustuk." Ajan
hatirladigini tahmin sanmisti.*

```
TAHMIN ETMEDEN ONCE ARA:
  1  proje notlari / indeks
  2  fikir-havuzu, tohumlar
  3  vizyon/karar kayitlari
  4  konusma gecmisi -- KONUSULDU MU?

Cikan her sey tahmin kumesinden DUSER.
Tahmin, kalan boslukta uretilir.
```

**Bu adim atlanirsa uretilen sey tahmin degil OZET olur** -- ve ozet, tahmin diye
sunuldugunda iki kez zarar verir: yanlis guven uretir, ve gercek bosluk gorunmez kalir.

## 2 · NE TAHMIN EDILIR

```
ZAYIF TAHMIN    "operator ne dusunuyor"        -> zihin okuma, yanlislanamaz
GUCLU TAHMIN    "operator hangi KARARI verecek" -> gozlenebilir, yanlislanabilir

ZAYIF           "bu is iyi mi"                  -> olcut yok
GUCLU           "bu is ILK DENEMEDE kapiyi gecer mi" -> gecer/gecmez, kayitli
```

**Kural: tahmin bir GOZLENEBILIR SONUCA baglanir.** Gozlenemeyen sey tahmin edilmez;
o bir sezgidir ve sezgi kaydedilmez, tahmin kaydedilir.

## 3 · TAHMIN FORMU

```
TAHMIN     <tek cumle, gozlenebilir sonuc>
GUVEN      dusuk / orta / yuksek        <- kalibrasyon icin zorunlu
DAYANAK    neye bakarak? (dosya, olcum, desen -- "sezgi" MESRU ama YAZILIR)
           dis kaynaksa GUVENILIRLIK notu: hakemli mi, orneklem ne, kim yazdi
YANLISLAR  bu tahmin neyle CURUR? tek cumle
ELENEN     arama sonucu dusen adaylar (zaten yazili olanlar)
BILINMEYEN olculmemis girdiler + YON: asagi / yukari / iki-yonlu
PENCERE    ne zaman sonuc belli olur
```

*`BILINMEYEN` alani: ELENEN "zaten yazili"yi duserken, BILINMEYEN "hic
olculmemis"i yazar. Ve YON zorunlu: bir bilinmeyen tahmini yalniz asagi
cekebiliyorsa sunulan sayi UST SINIR'dir, bu acikca soylenir. Olculmus
dogum: dort adayli kume sunuldu, karsi taraf "ikimizin de X'i olculmedi"
dedi; dogruydu ve tek yonluydu -- kume dogruydu ama ust-sinir oldugunu
soylememisti.*

*`ELENEN` alani skill'in kalbi: **neyi tahmin ETMEDIGINI** yazmadan tahmin sunmak,
hatirlamayi tahmin diye satmaktir.*

## 4 · COKLU TAHMIN — tek tahmin degil, SIRALI KUME

Bir tahmin tek basina bir bahistir; **uc tahmin bir modeldir**.

```
uret     3-5 aday, birbirini DISLAYAN
sirala   olasiliga gore, ve sirayi GEREKCELENDIR
isaretle "buyuk ihtimalle hicbiri" secenegini KOY -- cikarsa o da bilgidir
```

*Olculdu: iki turda alti tahmin uretildi, hicbiri tam tutmadi -- ama adaylardan biri
dogru fikrin ta kendisine bitisikti. **Iska bile kume icinde bilgi tasir**; tek
tahmin bunu yapamaz.*

## 4b · SONUC SATIRI — kume cevap degildir

Kume bir MODELDIR; okuyan kisi modelden cevabi kendi cikarmak zorunda
kalmamali. Her tahmin turu, kumeden SONRA tek blokla biter:

```
SONUC     <tek cumle: en olasi aday, duz dille, sayi varsa sayiyla>
EYLEM     <simdi ne yapilir / ne zaman ne yapilir -- en fazla iki madde>
CURUME    <hangi gozlem gelirse bu sonuc gecersiz olur>
```

*Olculmus dogum: dort adayli, guvenli, pencereli tam bir kume sunuldu;
operatorun cevabi "sonuc soylememissin ki, ne anlicaz bundan" oldu. Kume
dogruydu, cevap yoktu. Kume SONUC satiri olmadan sunulmaz.*

## 5 · KAYIT — bu skill'in asil urunu

Her tahmin turu sonunda tek satir:

```
araclar/tahmin/GOZLEM.md   (append-only)

<tarih> | <tahmin> | guven | isabet: TAM/KISMI/ISKA | gercek-cikan | dayanak-tutu-mu
```

**Kalibrasyon:** on tahminden sonra `guven` sutunu ile `isabet` sutunu karsilastirilir.
*"Yuksek guvenli tahminlerin kacini tutturdum"* -- bu sayi, tahmin yeteneginin
kendisidir ve kimse onu bilmeden iyi tahminci olamaz.

## 6 · ISKA'NIN DEGERI

```
TAM ISABET   en az bilgi tasir -- model zaten biliyordu
KISMI        yon dogru, ayrinti yanlis -> DAYANAK saglam, cozunurluk dusuk
ISKA         en cok bilgi -> hangi BOSLUK gorulmemis, o boslugun adi yazilir
```

*Bir iska yazilirken tek soru: **"bunu tahmin edebilmem icin neyi bilmem
gerekirdi?"** Cevap bir dosyaysa -> arama rotasi eksik. Cevap bir konusmaysa ->
gecmis taranmamis. Cevap "hicbir sey" ise -> **o zaten tahmin edilemezdi ve
bu da bir olcumdur.***

## 7 · YASAKLAR

```
- SONRADAN TAHMIN YASAK. Sonuc belliyken "ben zaten dusunmustum" bir kayit degil,
  bir anlatidir. Tahmin, sonuctan ONCE yazilmadiysa YOKTUR.
- GUVENSIZ TAHMIN YASAK. Guven yazilmayan tahmin kalibre edilemez.
- TEK TAHMIN sunulmaz (bkz. §4) -- kume sunulur.
- TAHMIN CERTIFY ETMEZ. Tahmin bir KAPI degildir: "model gecmez dedi" bir isi
  dusurmez; yalniz SIRA ve DIKKAT yonlendirir.
- SONUCSUZ KUME YASAK. Kume sunup "hangisi?" sorusunu okuyana birakmak,
  tahmin etmemektir.
- YONSUZ BILINMEYEN YASAK. Olculmemis girdi varsa yonu yazilir; tek yonluyse
  sayi "ust sinir" diye etiketlenir.
- KANDIRILABILIR TAHMIN YASAK: tahmin bir kapiya baglanirsa uretici onu kandirmaya
  optimize olur. Tahmin SALT-ONERI kalir, onay-yetkisi disarida.
```

## 8 · MAKINE UCUNA BAGLANTI

Bu skill iki ucu olan bir borunun **insan ucu**:

```
INSAN UCU (bu skill)   operator/ajan tahmin eder -> GOZLEM.md
MAKINE UCU (ileride)   ogrenen model tahmin eder -> sonuc + guven

BULUSMA NOKTASI: ayni sema (tahmin · guven · isabet), ayni defter disiplini.
```

**Fren:** etiket gurultusu. *Yorgunken ya da baglam kirikken yapilan tahminler
`[karantina]` isaretiyle yazilir, silinmez -- bozuk etiketten ogrenen model
arizayi ogrenir ve kalicilastirir.*

## 9 · KOSUM — 60 saniye

```
1  ARA        zaten yazili mi?
2  ELE        cikanlari dusur, ELENEN alanina yaz
3  URET       3-5 aday, birbirini dislayan, "hicbiri" dahil
4  BAGLA      her adayi GOZLENEBILIR bir sonuca bagla
5  GUVEN      her adaya dusuk/orta/yuksek
6  YANLISLA   her aday icin: bu neyle curur
7  SUN        sirali, gerekceli
7b SONUCLA    tek cumle sonuc + eylem; kume cevabin yerine gecmez
8  KAYDET     GOZLEM.md'ye satir; sonuc gelince isabet sutunu doldurulur
```

---

*graf: hatirlama-degil · karari-tahmin-et · kume-sun · sonucla · bilinmeyeni-yonuyle-yaz · guveni-yaz ·
iskayi-degerlendir · kaydet-ki-model-ogrensin · tahmin-certify-etmez.*
