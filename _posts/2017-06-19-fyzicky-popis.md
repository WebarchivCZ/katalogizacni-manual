---
layout: default
title: Údaje fyzického popisu
---
## Údaje fyzického popisu
Tato oblast obsahuje informace o fyzických vlastnostech popisovaného zdroje, tj. údaje o
jeho rozsahu, rozměru, vybavení ilustracemi, přílohami a/nebo doprovodným materiálem.

### 300 (elektronické zdroje - rozsah) (O)
*povinné pro minimální záznam*
Rozsah udává počet a typ jednotek a/nebo podjednotek tvořících zdroj. Jednotka rozsahu
je fyzická nebo logická složka zdroje, například svazek, digitální soubor (= online zdroj), atd.
Podjednotka rozsahu je fyzické nebo logické členění jednotky, například stránka svazku,
záznam v digitálním souboru, atd.

Pro elektronicky publikované textové monografie se v rozsahu používá výraz **1 online zdroj**. Pokud zdroj obsahuje jeden nebo více souborů, jejichž formát je paralelou tištěného protějšku (například .PDF), specifikuje se v kulaté závorce rozsah (tj. počet podjednotek) podle pravidel pro textové zdroje.


```
např.:
300 ## $a 1 online zdroj
300 ## $a 1 online zdroj (158 stran) - pro e-knihy, kartografické zdroje, grafiku
300 ## $a 1 online zdroj (2 video soubory)
```

### 310 (Současná periodicita) (NO)
Pole  označující současnou periodicitu

zapisujeme:
  * **„Aktualizováno průběžně“** (tzn. několikrát denně – tomu odpovídá kód „k“ v 008/18)
  * **„Časté aktualizace“** (tzn. denně nebo několikrát týdně)
  * **„Aktualizováno nepravidelně“** (tzn. v delších než týdenních intervalech – nerozhoduje, zda jsou nepravidelné či pravidelné)

### 336 (Typ obsahu) (O)
*povinné pro minimální záznam*

Typ obsahu je kategorizace pro základní formu komunikace, v níž je obsah vyjádřen, a lidský smysl,
jehož prostřednictvím má být vnímán. Používá se ve spojení s návěštím, znakovou pozicí 06  (LDR/06, typ záznamu)
označující typ obsahu zdroje. Pole 336 částečně nahrazuje pole 245$h obecné označení druhu dokumentu.

zapisujeme:
  * **$a text** (typ obsahu - termín)  
  * **$b txt** (typ obsahu - kód)  
  * **$2 rdacontent** (zdroj - vždy stejná hodnota)

```
např.:
336 ## $a text
       $b text
       $2 rdacontent
```



### 337 (Typ média) (O)
*nepovinné pro minimální záznam*

Typ média je kategorizace odrážející obecný typ zařízení, které je potřebné pro
zprostředkování (zobrazení, přehrání, spuštění atd.) obsahu zdroje.

Při zápisu typu média se vychází z údajů uvedených v samotném zdroji (či v doprovodném
materiálu nebo pouzdru). Další údaje lze převzít z jakéhokoli pramene popisu.

zapisujeme:
  * **$a počítač** (typ média - termín)  
  * **$b c** (typ média - kód)  
  * **$2** rdamedia (zdroj - vždy stejná hodnota)

```
např.:
337 ## $a počítač  
       $b c  
       $2 rdamedia  
```

### 338 (Typ nosiče) (O)
*povinné pro minimální záznam*

Typ nosiče je kategorizace odrážející formát paměťového média a jeho nosiče v kombinaci s typem zařízení,
které je potřebné pro zprostředkování (zobrazení, přehrání, spuštění atd.) obsahu zdroje.

Při zápisu typu nosiče se vychází z údajů uvedených v samotném zdroji (či v doprovodném materiálu nebo pouzdru).
Další údaje lze převzít z jakéhokoli pramene popisu.

zapisujeme:
  * **$a online zdroj** (typ nosiče - termín)    
  * **$b cr** (typ nosiče - kód)  
  * **$2 rdacarrier** (zdroj - vždy stejná hodnota)  

```
např.:
338 ## $a online zdroj  
       $b cr  
       $2 rdacarrier
```

### 362 (Údaje o číslování) (O)
*povinné pro minimální záznam*

Pole obsahuje informace o sekvenčním označení jednotlivých částí pokračujícího zdroje, vyplňuje se v případě, že katalogizujeme seriály, u itegračních zdrojů se údaje v této oblasti onvykle nezapisují. Číslování může být číselné (Band 1), abecední (Band A), chronologické (Leden 1973) nebo jejich kombinace (Volume 1 (1969))

Je-li číslování uvedeno ve více jazycích/písmech, zapisuje se pouze označení v jazyce hlavního názvu/písma. Nelze-li toto hledisko použít,
zapíše se označení uvedené jako první.

Jednotlivé údaje v oblasti jsou mezi sebou odděleny předepsanou interpunkcí ISBD. Mezi označením prvního a posledního sešitu se zapisuje spojovník
natěsno.

**Indikátory**

* **První indikátor:** označuje formu údajů uvedených v poli 362

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 0 označuje, že údaje jsou ve formátované podobě - zapisuje se číslování tak, jak je uvedeno na preferovaném  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; prameni prvního a posledního sešitu/části   
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 1 označuje, že údaje jsou v podobě neformátované poznámky – používáme tehdy, pokud nemáme k dispozici první  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; a/nebo poslední sešit a údaje o nich dohledáme v jiných zdrojích nebo odvodíme/odhadneme

* **Druhý indikátor:** není definován


```
např.:
362 0# $a Volume 1, number 1-
362 0# $a No. 1, no. 24(2012-)
```
