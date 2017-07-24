---
layout: default
title: Údaje fyzického popisu
---
## Údaje fyzického popisu

### 300 (elektronické zdroje - rozsah) (O)
* počet a typ jednotek a/nebo podjednotek tvořících zdroj
* používá se obvyklá terminologie
* pro elektronicky publikované textové monografie se v rozsahu používá výraz **1 online zdroj**. Pokud zdroj obsahuje jeden nebo více souborů, jejichž formát je paralelou tištěného protějšku (například .PDF), specifikuje se v kulaté závorce rozsah (tj. počet podjednotek) podle pravidel pro textové zdroje.

```
např.:
300 ## $a1 online zdroj
300 ## $a1 online zdroj (158 stran) - pro e-knihy, kartografické zdroje, grafiku
300 ## $a1 online zdroj (2 video soubory)
```

### 310 (Současná periodicita) (NO)
**Integrační zdroje**

Zapisujeme:
  * **„Aktualizováno průběžně“** (tzn. několikrát denně – tomu odpovídá kód „k“ v 008/18)
  * **„Časté aktualizace“** (tzn. denně nebo několikrát týdně)
  * **„Aktualizováno nepravidelně“** (tzn. v delších než týdenních intervalech – nerozhoduje, zda jsou nepravidelné či pravidelné)

### 336 (Typ obsahu) (O)
*povinné pro minimální záznam*

* pole obsahuje kategorizaci pro základní formu komunikace, v níž je obsah vyjádřen, a lidský smysl, jehož prostřednictvím má být vnímán
* používá se ve spojení s návěštím, znakovou pozicí 06 (LDR/06, typ záznamu) označující typ obsahu zdroje

 $a text (typ obsahu - termín)  
 $b txt (typ obsahu - kód)  
 $2 rdacontent (zdroj - vždy stejná hodnota)  

### 337 (Typ média) (O)
*nepovinné pro minimální záznam*

$a počítač (typ média - termín)  
$b c (typ média - kód)  
$2 rdamedia (zdroj - vždy stejná hodnota)

```
např.:
337 ## $a počítač  
       $b c  
       $2 rdamedia  
```

### 338 (Typ nosiče) (O)
*povinné pro minimální záznam*

pole obsahuje kategorizaci odrážející formát paměťového média a jeho nosiče v kombinaci s typem zařízení, které je potřebné pro zprostředkování (zobrazení, přehrání, spuštění atd.)

$a online zdroj (typ nosiče - termín)    
$b cr (typ nosiče - kód)  
$2 rdacarrier (zdroj - vždy stejná hodnota)  

```
např.:
338 ## $a online zdroj  
       $b cr  
       $2 rdacarrier
```
