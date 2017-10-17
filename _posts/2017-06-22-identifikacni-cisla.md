---
layout: default
title: Identifikační čísla a kódy
---
## Identifikační čísla a kódy

### 022 (ISSN) (O)
Pokud má zdroj přidělené ISSN, uvede se toto identifikační číslo do pole 022, bez ohledu na to, zda se jedná o integrační zdroj nebo elektronický časopis). Pro pokračující zdroje je povinný též údaj v poli 222 Klíčový název (je vázán na ISSN).


### 041 (Kód jazyka) (O)
Je-li popisná jednotka originálem v jediném jazyce, uvádí se kód tohoto jazyka pouze v poli 008/35-37 a pole 041 se již nezapisuje. V případě dokumentu ve více jazycích, překladu, s cizojazyčnými resumé, apod. se všechny kódy jazyků zapisují do příslušných podpolí v poli 041 a na pozicích 008/35-37 se zapisuje pouze kód dominantního jazyka popisné jednotky. Používá se
kódovník MARC.

V případě vícejazyčného zdroje postupuje následovně:  

a) jde o **paralelní verzi** v jiném jazyce (většina stránek, které mají cizojazyčné verze) – jedná se o nejčastější případ

  ```
  např.:
  041 0	$a cze
        $a eng
  ```
b) zdroj je/obsahuje **překlad** – první indikátor 1, v podpoli h musí být zapsáno, z kterého jazyka přeloženo
  ```
  např.:
  041 1	$a eng
        $h cze
  ```

c) zdroj má cizojazyčný jen **abstrakt**
  ```
  např.:
  041 0	$a cze
        $b eng
  ```

### 043 (Kód geografické oblasti) (NO)
Pole se použije pouze v případech, když se zdroj obsahově týká určité geografické oblasti. Vyplní-li se pole musí být údaj zapsán také v poli 080 (MDT) a  651 (Vedlejší věcné záhlaví - geografické jméno).
  ```
  např.:
  043	$a e-xr---
	$b e-xr-zl (specifikovaná oblast v ČR)
	$2 czenas (zapisuje se, jen pokud je zapsán údaj v $b)
  ```

### 045 (Časové období obsahu dokumentu) (NO)
Pole se vyplní pouze v případě, že se zdroj obsahově týká určitého data/časového období.
Údaj musí být současně zapsán v poli 080 (MDT) a 648 (Vedlejší věcné záhlaví - chronologický termín).

  ```
  např.:
  045	$a x1x9
  648 7	$a 20. století

  045	$a x3x4
  648 7	$a 1939-1945

  045	$a x4x4
  648 7	$a 1948

  045	$a f-g-
  648 7	$a 2.-3. století

  045	$a d9d9
  648 7	$a 1. století př. Kr.
  ```

### 072 (Konspekt) (O)
Na základě použitých znaků MDT je třeba vybrat příslušný znak Konspektu. Vybírá se **vždy jedna** podkategorie Konspektu, který nejlépe vystihuje obsah dokumentu. S tímto znakem musí též  korespondovat vybrané předmětové heslo uvedené v poli 080/650 (tj. uvedené předmětové heslo musí obsahově náležet do této konkrétní skupiny Konspektu).

**Indikátory**  
*První indikátor*: nedefinován  
*Druhý indikátor*: hodnota 7, zdroj specifikován v podpoli $2

Ve výjimečných případech jsou povoleny dvě skupiny Konspektu:

**1.** spadá-li obsah dokumentu do dvou odlišných tematických oblastí a nelze určit převládající
tematickou oblast - jen ve výjimečných případech

**2.** k vyjádření určitých formálních charakteristik (v pořadí druhý znak skupiny Konspektu,
jako první v pořadí se uvádí hlavní téma dokumentu, tedy obor - za obor se považuje i
národní literatura) při popisu
*  literatury pro děti a mládež
*  učebnic
*  jazykových slovníků
*  bibliografií
*  biografií
*  rukopisů, starých tisků a vzácných dokumentů
*  map, atlasů, glóbů a starých map

```
např.:
072 7 $a 821.162.3-1
      $x Česká poezie
      $2 Konspekt$925

072 7 $a 821-93
      $x Literatura pro děti a mládež (beletrie)
      $2 Konspekt$926
```
### 080 (MDT) (O)
Pole obsahuje znak Mezinárodního desetinného třídění (MDT). Pole 080 se opakuje, je-li
potřeba přidělit popisné jednotce více znaků MDT.
Při katalogizaci Je se uvádějí znaky MDT pro všechna předmětová hesla z polí 648, 650, 651, 655 ve stejném pořadí, v jakém jsou uvedena v těchto polích.

```
např.:
080 $u lékařství
    $a 61
    $2 MRF

080 $u Česko
    $a (437.3)
    $2 MRF

080 $u www.dokumenty
    $a (0.034.2)004.738.12
    $2 MRF

080 $u elektronické časopisy
    $a (0.034.2:051)
    $2 MRF
```
