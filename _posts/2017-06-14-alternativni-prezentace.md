---
layout: default
title: Alternativní prezentace, elektronické umístění
---

### Alternativní prezentace, elektronické umístění

## 856 (Elektronické umístění a přístup) (O)
Pokud je tentýž zdroj dostupný z více URL, další URL se zapisuje/-í vždy do nového pole 856

Pokud je/jsou starší URL již neplatné a zapisuje se nová (tj. platná) URL, zapíše se tato nová URL do 1. výskytu, před původní URL již neplatnou. Totéž platí, je-li původní URL přesměrována na nově zapisovanou URL (tj. nová URL = 1. výskyt, přesměrované URL = 2. a případně další výskyty).

**Pro odkaz do Webarchivu** se používá další výskyt pole 856, stejný zápis jako u běžné adresy v poli 856, ale komentář v podpoli $z hodnota „archivní verze stránek“ (text, který se zobrazuje za URL adresou). Návod pro URL:

```
např.:
856 40 $u [http://gvuhodonin.cz](http://gvuhodonin.cz)
       $q text/html
       $4 N
856 40 $u [http://wayback.webarchiv.cz/wayback/gvuhodonin.cz](http://wayback.webarchiv.cz/wayback/gvuhodonin.cz)
       $q text/html
       $z archivní verze stránek
       $4 N
```

**a) Ukončeno vydávání**
Pokud URL není funkční a stránky již neexistují (vůbec nebo jsou na jiné URL, příp. nevíme, zda opravdu skončily), zapíše se o této skutečnosti poznámka v 856 $z „adresa nedostupná k [datum, kdy byla nefunkčnost URL zjištěna]“. Je nutné změnit hodnotu 2. indikátoru „0“ na „#“ (tj. prázdný).

```
např.:
856 4#	$u [http://www.linuxbiz.cz](http://www.linuxbiz.cz)
        $z adresa nedostupná k 21.8.2007
        $4 N
```

Pokud se současně zapisuje v novém výskytu pole 856 URL, na které jsou nově webové stránky umístěny, zapíše se do téhož výskytu poznámka v $z „adresa platná k [datum]“.

Pokud se na původní URL objevily zcela nové nesouvisející webové stránky, zapíše se o této skutečnosti poznámka v 856$z „původní dokument na této adrese nedostupný k [datum, kdy byla nefunkčnost URL zjištěna]“. Je nutné změnit hodnotu 2. indikátoru „0“ na „#“ (tj. prázdný).


Pokud je původní URL funkční, ale obsahuje zcela odlišný dokument od původního a jedná se o významný dokument, může se tento dokument popsat novým katalogizačním záznamem.

**b) Stránky přesunuty**

```
např.:
856 40 $u [http://oldgeogr.muni.cz/ucebnice/kartografie/](http://oldgeogr.muni.cz/ucebnice/kartografie/)
       $q text/html
       $z adresa platná k [datum, kdy zapisujeme URL do záznamu]
       $4 N

856 4# $u [http://www.geogr.muni.cz/ucebnice/kartografie](http://www.geogr.muni.cz/ucebnice/kartografie)
       $q text/html
       $z adresa nedostupná k [datum, kdy byla nefunkčnost URL zjištěna]
       $4 N
```


U neplatné URL se v 856 mění hodnota 2. indikátoru z „0“ na „#“ (tj. prázdný).

**c) Přesměrování**
Pokud původní URL přesměrovává na nové URL, kde je nově umístěn původní, popisovaný zdroj, zapíšeme novou URL a starou neměníme.


```
např.:
856 40	$u [http://www.linuxbiz.cz](http://www.linuxbiz.cz)
        $q text/html
        $4 N

856 40	$u [http://www.linuxbiz.cz](http://www.linuxbiz.cz)
        $q text/html
        $4 N
```


**d) Souběžné vydávání na více URL**
Zapíší se všechny URL adresy

**2. indikátor vždy 0** (jedná se o původní elektronický zdroj)

*výjimky:*

**a) nefunkční URL**

```
např.:
856 4# $u [http://www.linuxbiz.cz](http://www.linuxbiz.cz)
       $z adresa nedostupná k [datum]
       $4 N
```


b) zápis URL do záznamu pro **tištěný dokument** (eventuálně elektronický zdroj na fyzickém nosiči)

```
např.: Ložiska nerostů (CD-ROM)
856 41 $3 Online verze
       $u [http://geologie.vsb.cz/loziska/loziska/index.html](http://geologie.vsb.cz/loziska/loziska/index.html)
       $4 N
```


c) považuje-li katalogizátor za důležité zapsat do záznamu vedle vlastní URL popisovaného dokumentu ještě URL **příbuzného dokumentu** (např. blog, na který je odkaz z popisovaného dokumentu, předchozí verze stránek)  

- v tomto případě je třeba zapsat do $3 vhodné návěští a v poznámce (anotaci) by měla být informace o tomto odkazovaném dokumentu.


```
např.:
856 40 $u [http://home.tiscali.cz/bovepul](http://home.tiscali.cz/bovepul)
       $4 N

856 42 $3 Blog
       $u [http://bovepul.blog.cz](http://bovepul.blog.cz)
       $4 N
```

+ 520 $a V rámci webových stránek je provozován také blog pro náboženství, filosofii a umění

**Vždy** (tj. i v každém opakovaném výskytu pole 856) uveďte podpole 4 hodnota N (znamená negenerovat obrazovku „copyright“ ).
