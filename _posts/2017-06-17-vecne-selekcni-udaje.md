---
layout: default
title: Věcné selekční údaje
---

## Věcné selekční údaje

### 600 (Vedlejší věcné záhlaví – osobní jméno) (O)
Údaje se zapisují ve stejné podobě jako v poli 100 (Hlavní záhlaví - osobní jméno). Zdroj pojednává o konkrétní osobě.


### 610 (Vedlejší věcné záhlaví – jméno korporace) (O)
Údaje se zapisují ve stejné podobě jako v poli 110 (Hlavní záhlaví - jméno korporace). Zdroj pojednává o konkrétní instituci.


### 611 (Vedlejší věcné záhlaví – jméno akce) (O)
Údaje se zapisují ve stejné podobě jako v poli 111 (Hlavní záhlaví - jméno akce). Zdroj pojednává o akci, konferenci.


### 648 (Vedlejší věcné záhlaví – chronologický termín) (O)
Pole se vyplňuje pokud je použito pole 045. Do pole zapisujeme chronologické vymezení tématu zdroje např. „1945-1948“. Jedná se o autoritní termín (chronologický údaj). V poli 648 se zapisují konkrétní data, jsou-li v popisovaném dokumentu snadno k nalezení.


```
např.:
648 7	$a 20. stol.
648 7	$a 1939-1945
648 7	$a 1948
648 7	$a 2.-3. stol.
648 7	$a 1. stol. př. Kr.
```


### 650 (Vedlejší věcné záhlaví – věcné téma) (O)
Do pole se zapisují česká předmětová hesla. Termíny se přebírají ze souboru autorit. Hodnota indikátorů je pak následující:  
**1. indikátor - 0 nespecifikován**  
**2. indikátor - 7 zdroj specifikovaný v podpoli $2**

V případě anglických předmětových hesel je hodnota indikátorů:  
**1. indikátor - 0 nespecifikován**  
**2. indikátor - 9 zdroj specifikovaný v podpoli $2**


```
např.: dokument pojednává o lidských právech
650 07 $a lidská práva
       $7 ph122331
       $2 czenas
650 09 $u lidská práva
       $a human rights
       $2 czenas
```


### 651 (Vedlejší věcné záhlaví – geografické jméno) (O)
Pole se vyplňuje pokud je použito pole 043. Termíny se přebírají ze souboru autorit.

V případě českých předmětových hesel je hodnota indikátorů:  
**1. indikátor - \ #  nedefinovaný**  
**2. indikátor - 7 zdroj specifikovaný v podpoli $2**

V případě anglických předmětových hesel je hodnota indikátorů:  
**1. indikátor - \ # nedefinovaný**  
**2. indikátor - 9 zdroj specifikovaný v podpoli $2**


```
651 #7 $a Česko
       $7 ge128065
       $2 czenas
651 #9 $u Česko
       $a Czechia
       $2 czenas		
```


### 655 (Vedlejší věcné záhlaví - žánr/forma) (O)
Při katalogizaci elektronických zdrojů se používají převážně následující hesla: www dokumenty, elektronické časopisy, fotogalerie, blogy, (elektronické mapy, zvukové záznamy).
V případě zdrojů, které mají z hlediska knihovnického charakter integračního zdroje, ale v podstatě jsou nečíslovanými seriály, se zapisují obě formy dokumentu (elektronické seriály + www dokumenty).


V případě českých předmětových hesel je hodnota indikátorů:  
**1. indikátor - \ # nespecifikován**  
**2. indikátor - 7 zdroj specifikovaný v podpoli $2**

V případě anglických předmětových hesel je hodnota indikátorů:  
**1. indikátor - \ # nespecifikován**  
**2. indikátor - 9 zdroj specifikovaný v podpoli $2**


```
651 #7 $a www dokumenty
       $7 fd186892
       $2 czenas
651 #9 $u www dokumenty
       $a www documents
       $2 eczenas		
```
