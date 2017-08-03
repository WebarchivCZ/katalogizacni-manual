---
layout: default
title: Propojovací pole
---

## Propojovací pole

### 76X – 78X (Propojovací pole)

Propojovací pole obsahují informace, které identifikují další související bibliografické jednotky. Každé z propojovacích polí specifikuje jiný typ bibliografického propojení mezi základní jednotkou popsanou v bibliografickém záznamu a související popisnou jednotkou. Při popisu elektronických online zdrojů jsou nejčastěji využívána tato propojovací pole:

```
776	Vydání na jiném nosiči
780	Předcházející záhlaví
785	Následující záhlaví
787	Nespecifikované propojení
```


Propojovací pole 776 se používá v případě existence vydání dokumentu na jiném nosiči, kdy je uplatňován přístup tvorby dvou individuálních záznamů. Toto propojovací pole je zapisováno obvykle v kombinaci s poznámkou v poli 530.

```
např.:
propojení integračního zdroje
záznam pro online verzi dokumentu:
245 14 $a The Opera quarterly
530 ## $a Dostupné též v tištěné podobě.
776 1# $t Opera quarterly
       $x 0736-0053

záznam pro tištěnou verzi dokumentu:
245 04 $a The Opera quarterly
530 ## $a Dostupné též online.
776 1# $a Opera quarterly (Online)
       $x1486-2870
```


  Pole 780 a 785 jsou užívána pro zápis předcházejících a následujících názvů.

*Pro popis online zdrojů* se pole 7XX používají zcela výjimečně, přicházejí v úvahu pouze *pole 780 Předcházející záhlaví a 785 Následující záhlaví* (pro popis seriálů, příp. integračních zdrojů - hodnota 1. indikátoru je 0, hodnota 2. indikátoru určuje typ propojení). Při popisu metodou jednoho záznamu se může vyskytnout potřeba použít pole *776 Vydání na jiném nosiči*.

```
např.:
Měsíční deník a Měsíční deník II.

245 10 	$a Měsíční deník
785 00 	$a Gabzdyl, Pavel.
        $t Měsíční deník II.

245 10	$a Měsíční deník II.
780 00 	$a Gabzdyl, Pavel.
        $t Měsíční deník
```


Pokud je předcházející/následující záznam zkatalogizován pod hlavním záhlavím, uvede se v podpoli $a. Pokud je záznam zkatalogizován pod názvem, použije se pouze podpole $t (bez interpunkce na konci podpole).

Pokud katalogizátor považuje za účelné v záznamu **uvést informaci o vztahu k jinému popsanému dokumentu** (např. o seriálu vydávaném v rámci webové stránky), použije se pole 787.


```
např.:
245 10 	$a Česká společnost pro systémovou integraci
787 08	$i Součástí stránek je … (časopis/monografie):
        $a Hlavní návěští
        $t Systémová integrace : časopis České společnosti pro systémovou integraci
        $x/z ISSN/ISBN
```

Pokud jsou obsahem dokumentu dílčí samostatné dokumenty a katalogizátor považuje za účelné na jednotlivé dokumenty upozornit, zapíše jejich názvy v poli 520 (anotace).
Pokud považuje za důležité umožnit samostatné vyhledávání těchto částí, uvede je v poli 505 - Formalizovaná poznámka k obsahu (*neuvádí se ale duplicitně v poli 520*). (V tomto případě je však riziko, že se obsah webové stránky časem změní a uživatel pak příslušný dokument pod názvem zapsaným v záznamu a uvedeným v rejstříku již nenajde.)

```
např.:
Web Markéty Baňkové obsahuje 3 významné umělecké dokumenty různého typu.
varianta a/
520 $a Webová stránka obsahuje 3 významné umělecké dokumenty různého typu: New York City Map (emoční mapa), Senses of life (video) a Mesto.html (internetová kniha)
varianta b/
505 20 $t New York City Map
       $g (emoční mapa)
       $t Senses of life $g (video)
       $t Mesto.html $g (internetová kniha)
```
