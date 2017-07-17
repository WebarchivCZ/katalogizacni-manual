---
layout: default
title: Kontrolní pole
---
# Kontrolní pole

## 006 (Údaje pevné délky - další charakteristiky dokumentu) (O)
Umožňuje zapsat další charakteristiky elektronického zdroje, které nejsou zapsány v poli 008 (neopakovatelné). V praxi NK ČR se uvádí pole 006 v následujících případech:
* a) v záznamech *všech elektronických zdrojů s výjimkou popisu SW*, her apod. (tj. **s výjimkou, kdy je v LDR/06 údaj "m"**); v poli 006 je na první pozici hodnota "m", ostatní pozice jsou vesměs prázdné

```
	např. elektronický časopis (seriál)
	FMT SE
	LDR/06 a (textový dokument)
	LDR/07 s (seriál)
	006/00 m (druh dokumentu - počít. soubor/el.zdroj)
	006/09 d (typ počít. souboru - dokument)
	008/23 s (specifikace pro pokračující zdroj; "s" = elektronický zdroj)
```

* b) v záznamech *pokračujících elektronických zdrojů, jejichž obsah není text* (např. mapa, obrazové dokumenty, zvuk) pro zápis "seriálové" charakteristiky dokumentu - jedná se **o další výskyt pole 006**.

```
	např. mapa v elektronické podobě vycházející na pokračování (seriál)
	FMT  MP
	LDR/06 e (kartografický dokument)
	LDR/07 i
 výskyt 006
 006/00 m (údaje pro počít. soubor/el.zdroj)
  006/06 o (online)
  006/09 c (typ počít. souboru - reprezentativní) – používá se v souvislosti s kartografickým dokumentem


  výskyt 006
  006/00 s (údaje pro seriál)
  006/06 o (online)
	007/00 c (údaje pro el. zdroj)
	008/29 s (specifikace pro kartografický dokument; "s" = elektronický zdroj)
  V typologii elektronických zdrojů jsou k  dispozici tři pole pro typ obsahu, média a nosiče. Typ obsahu: souvislost s návěštím LDR/06, poskytuje jemnější členění.
```

## 007 (Pole pevné délky pro pro fyzický popis) (O)

007/00 - kategorie dokumentu
* c - Elektronický zdroj

007/01 specifické označení dokumentu
* r   Dálkově přístupný zdroj
* u   Nespecifikován
* z   Jiný
* |   Kód se neuvádí

007/02 nedefinován

007/03 - barva
* a  Jednobarevný
* b  Černobílý
* c  Vícebarevný

007/04 - rozměry
* u   Není znám
* z   Jiný
* |   Kód se neuvádí

007/05 - zvuk
* \#	Bez zvuku
* u     Není znám
* |      Kód se neuvádí

## Zápis údajů v tomto poli odpovídá hodnotě kódu v LDR/06
008/00-05 - datum uložení
Datum uložení se automaticky vygeneruje při ukládání záznamu.
008/06 - typ data/publikační status
Status pokračujícího zdroje:
* c - Průběžně vydávaný
* d - S ukončeným vydáváním
* u - Status není znám

008/07-10 - datum 1
Kód označuje datum vydání zdroje. V případě nejasností se uvede pravděpodobné datum vydání (přestože je nejesné), anebo např. 199u, 200u, apod.

008/11-14 - datum 2
V případě, že zdroj stále vychází ponechá se hodnota 9999. U zdroje s ukončeným vydáváním se zapíše dané datum ukončení, informace o ukončeném vydávání se zanese také do   vydávání a změní se na pozici 008/06 status vydávání na „d“ – s ukončeným vydáváním

008/15-17 - místo vydání, produkce
* xr	Česká republika
* xo	Slovensko
* xx neznámé nebo neurčené místo

Hodnota kódu označuje místo vydání, produkce nebo realizace, obvykle se odvozuje z informací uvedených v poli 264. Zdrojem kódu je MARC Code List
for Countries, který spravuje Library of Congress - viz http://www.loc.gov/marc/countries

008/18 - periodicita
* \#  – neurčeno
* a – ročně
* b –  jednou za dva měsíce
* d – denně
* f – pololetně
* m – měsíčně
* q – čtvrtletně
* u – není známa
* z – jiná periodocita

008/19 - pravidelnost
*  r - Pravidelný
* x - Nepravidelný
* | - Kód se neuvádí

U integračních zdrojů se většinou uvádí hodnota “x” . nepravidelný.

008/21 – typ pokračujícího zdroje
* w - Aktualizovaná website
* | - Kód se neuvádí

008/22 - forma popisné jednotky
* Pole zůstává nevyplněno.

008/23 - forma popisné jednotky
* o - Online

008/24 - povaha celého díla
Pole zůstává nevyplněno.

008/25-27 - povaha obsahu
Pole zůstává nevyplněno.

008/28 – vládní publikace
* \#    Nejedná se o vládní publikaci

008/29 – dokument z konference
* 0 – nejedná se o materiál z konference
* 1 – materiál z konference
* | kód se neuvádí

008/30-32 - nedefinováno

008/33 - původní abeceda/písmo z názvu
* b - rozšířená latinka

008/34 - Konvence tvorby záznamu
* 2 - integrační záznam

008/35-37 – jazyk dokumentu
Kód označuje jazyk popisné jednotky, odpovídá poli 041 – pokud je dokument v češtině, uvede se tento údaj pouze v poli 008, a nikoli již v poli 041. Zdrojem kódu je MARC Code List for Languages, který spravuje Library of Congress - viz http://www.loc.gov/marc/languages.

008/38 - kód modifikace záznamu
Pole zůstává prázdné, záznam nebyl modifikován.

008/38 - zdroj katalogizace
* \# - Národní bibliografická agentura
* c - Program kooperativní katalogizace
* d - Jiný
* u - Není znám
* | - Kód se neuvádí
Zpracovává li bibliografický záznam NK ČR zůstává pole prázdné.
