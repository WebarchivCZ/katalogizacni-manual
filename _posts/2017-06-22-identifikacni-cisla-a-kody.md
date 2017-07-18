---
layout: default
title: Identifikační čísla a kódy
---
## Identifikační čísla a kódy

### 022 (ISSN) (O)
Pokud má zdroj přidělené ISSN, uvede se toto identifikační číslo do pole 022, bez ohledu na to, zda se jedná o integrační zdroj nebo elektronický časopis). Pro integrační zdroje je povinný též údaj v poli 222 Klíčový název (je vázán na ISSN).


### 041 (Kód jazyka) (O)
Je-li pouze jeden jazyk dokumentu, je pole 041 nepovinné, ale musí se pečlivě vyplnit pole 008. Je-li zdroj (popřípadě jeho část) publikován ve dvou a více jazycích, do pole 008 se zapíše první, případně dominantní z nich a v poli 041 bude tolik výskytů podpole „a“, kolik je nezbytné.

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
  648 7	$a 20. stol.

  045	$a x3-x4
  648 7	$a 1939-1945

  045	$a x4-x4
  648 7	$a 1948

  045	$a f-g-
  648 7	$a 2.-3. stol.

  045	$a d9d9
  648 7	$a 1. stol. př. Kr.
  ```

### 072 (Konspekt) (O)
Na základě použitých znaků MDT je třeba vybrat příslušný znak Konspektu. Vybírá se **vždy jedna** podkategorie Konspektu, který nejlépe vystihuje obsah dokumentu. S tímto znakem musí též  korespondovat vybrané předmětové heslo uvedené v poli 080/650 (tj. uvedené předmětové heslo musí obsahově náležet do této konkrétní skupiny Konspektu).

**Indikátory**  
*První indikátor*: nedefinován  
*Druhý indikátor*: hodnota 7, zdroj specifikován v podpoli $2

Pole 072 má ve výjimečných případech povolené dva výskyty. Zvláště u webových stránek vycházejících z tištěných novin a dalších periodik - se připouští dva znaky, například znaky Konspektu pro http://www.reflex.cz/  
394 - Veřejný a společenský život. Každodenní život  
050 - Seriálové publikace. Periodika  

```
např.:
072 7 $a821.162.3-1
      $xČeská poezie
      $2Konspekt$925

072 7 $a821-93
      $xLiteratura pro děti a mládež (beletrie)
      $2Konspekt$926
```
### 080 (MDT) (O)
Je třeba vytvořit odpovídající znaky MDT pro všechna předmětová hesla z polí 648, 650, 651, 655 **ve stejném pořadí**, v jakém jsou uvedena v těchto polích.
