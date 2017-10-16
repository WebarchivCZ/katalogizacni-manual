---
layout: default
title: Kontrolní pole
---
## Kontrolní pole

### 006 (Údaje pevné délky - další charakteristiky dokumentu) (O)
Umožňuje zapsat další charakteristiky elektronického zdroje, které nejsou zapsány v poli 008. Při katalogizaci elektronických zdrojů se v poli 006 na první pozici uvádí hodnota „m“ a na pozici 09 pak hodnota **d**.


```
např.:
elektronický časopis (seriál)  

FMT SE
LDR/06 a (textový dokument)
LDR/07 s (seriál)
006/00 m (druh dokumentu - počít. soubor/el.zdroj)
006/06 o (forma popisné jednotky - online)
006/09 d (typ počít. souboru - dokument)
008/23 o (konfigurace pro pokračující zdroj; forma popisné jednotky - online)

006  m-----o--d--------
```


### 007 (Pole pevné délky pro pro fyzický popis) (O)
**007/00 - kategorie dokumentu**  
&nbsp;&nbsp;&nbsp;&nbsp; c - elektronický zdroj


**007/01 - specifické označení dokumentu**  
&nbsp;&nbsp;&nbsp;&nbsp; r - dálkově přístupný zdroj  
&nbsp;&nbsp;&nbsp;&nbsp; u - nespecifikován  
&nbsp;&nbsp;&nbsp;&nbsp; z - jiný  
&nbsp;&nbsp;&nbsp;&nbsp; \|  - kód se neuvádí


**007/02 - nedefinován**


**007/03 - barva**  
&nbsp;&nbsp;&nbsp;&nbsp; a - jednobarevný  
&nbsp;&nbsp;&nbsp;&nbsp; b - černobílý  
&nbsp;&nbsp;&nbsp;&nbsp; c - vícebarevný


**007/04 - rozměry**  
&nbsp;&nbsp;&nbsp;&nbsp; u - není znám  
&nbsp;&nbsp;&nbsp;&nbsp; z - jiný  
&nbsp;&nbsp;&nbsp;&nbsp; \|  - kód se neuvádí


**007/05 - zvuk**  
&nbsp;&nbsp;&nbsp;&nbsp; \#	- bez zvuku  
&nbsp;&nbsp;&nbsp;&nbsp; u - není znám  
&nbsp;&nbsp;&nbsp;&nbsp; \|  - kód se neuvádí



```
např.:
007  cr-cn-
```


### 008 (Údaje pevné délky - pokračující zdroje) (NO)
Zápis údajů na pozici 18-34 odpovídá hodnotě kódu LDR/06.

**008/00-05 - datum uložení**  
&nbsp;&nbsp;&nbsp;&nbsp; Datum uložení se automaticky vygeneruje při ukládání záznamu.


**008/06 - typ data/publikační status**  
&nbsp;&nbsp;&nbsp;&nbsp; Kódy pro status pokračujícího zdroje mohou být následující:  
&nbsp;&nbsp;&nbsp;&nbsp; c - průběžně vydávaný  
&nbsp;&nbsp;&nbsp;&nbsp; d - s ukončeným vydáváním  
&nbsp;&nbsp;&nbsp;&nbsp; u - status není znám
&nbsp;&nbsp;&nbsp;&nbsp; s - jedno známé/pravděpodobné datum
&nbsp;&nbsp;&nbsp;&nbsp; q - neznámé datum (rok vydání neznámý, ale lze určit přibližně rozmezí let vydání)


**008/07-10 - datum 1**  
&nbsp;&nbsp;&nbsp;&nbsp; Kód označuje datum vydání zdroje. V případě nejasností se uvede pravděpodobné datum vydání. U neznámého data lze použít  
&nbsp;&nbsp;&nbsp;&nbsp; např. 199u, 200u, apod.


**008/11-14 - datum 2**  
&nbsp;&nbsp;&nbsp;&nbsp; V případě, že zdroj stále vychází ponechá se hodnota 9999. U zdroje s ukončeným vydáváním se zapíše dané datum ukončení.
&nbsp;&nbsp;&nbsp;&nbsp; Informace o ukončeném vydávání se zanese také do pole 264 a změní se hodnota
&nbsp;&nbsp;&nbsp;&nbsp; na pozici 008/06 status vydávání na **d** s ukončeným vydáváním.



**008/15-17 - místo vydání, produkce**  
&nbsp;&nbsp;&nbsp;&nbsp; xr	Česká republika  
&nbsp;&nbsp;&nbsp;&nbsp; xo	Slovensko  
&nbsp;&nbsp;&nbsp;&nbsp; xx  neznámé nebo neurčené místo


Hodnota kódu označuje místo vydání, produkce nebo realizace, obvykle se odvozuje z informací uvedených v poli 264. Zdrojem kódu je MARC Code List
for Countries, který spravuje Library of Congress - viz [http://www.loc.gov/marc/countries](http://www.loc.gov/marc/countries).


**008/18 - periodicita**  
&nbsp;&nbsp;&nbsp;&nbsp; \#  – neurčeno  
&nbsp;&nbsp;&nbsp;&nbsp; a – ročně  
&nbsp;&nbsp;&nbsp;&nbsp; b – jednou za dva měsíce  
&nbsp;&nbsp;&nbsp;&nbsp; d – denně  
&nbsp;&nbsp;&nbsp;&nbsp; f – pololetně  
&nbsp;&nbsp;&nbsp;&nbsp; m – měsíčně  
&nbsp;&nbsp;&nbsp;&nbsp; q – čtvrtletně  
&nbsp;&nbsp;&nbsp;&nbsp; u – není známa  
&nbsp;&nbsp;&nbsp;&nbsp; z – jiná periodocita  


**008/19 - pravidelnost**  
&nbsp;&nbsp;&nbsp;&nbsp; r - pravidelný  
&nbsp;&nbsp;&nbsp;&nbsp; x - nepravidelný  
&nbsp;&nbsp;&nbsp;&nbsp; \|   - kód se neuvádí  


U integračních zdrojů se většinou uvádí hodnota **x** nepravidelný.


**008/21 – typ pokračujícího zdroje**  
&nbsp;&nbsp;&nbsp;&nbsp; w - aktualizovaná website  
&nbsp;&nbsp;&nbsp;&nbsp; \|   - kód se neuvádí


**008/22 - forma popisné jednotky**  
&nbsp;&nbsp;&nbsp;&nbsp; pozice zůstává nevyplněno


**008/23 - forma popisné jednotky**  
&nbsp;&nbsp;&nbsp;&nbsp; o - online


**008/24 - povaha celého díla**  
&nbsp;&nbsp;&nbsp;&nbsp; pozice zůstává nevyplněno


**008/25-27 - povaha obsahu**  
&nbsp;&nbsp;&nbsp;&nbsp; pozice zůstává nevyplněno


**008/28 – vládní publikace**  
&nbsp;&nbsp;&nbsp;&nbsp; \#   - nejedná se o vládní publikaci


**008/29 – dokument z konference**  
&nbsp;&nbsp;&nbsp;&nbsp; 0 – nejedná se o materiál z konference  
&nbsp;&nbsp;&nbsp;&nbsp; 1 – materiál z konference  
&nbsp;&nbsp;&nbsp;&nbsp; \|   - kód se neuvádí

**008/30-32 - nedefinováno**

**008/33 - původní abeceda/písmo z názvu**  
&nbsp;&nbsp;&nbsp;&nbsp; b - rozšířená latinka

**008/34 - Konvence tvorby záznamu**  
&nbsp;&nbsp;&nbsp;&nbsp; 2 - integrační záznam

**008/35-37 – jazyk dokumentu**  
&nbsp;&nbsp;&nbsp;&nbsp; je-li popisná jednotka originálem v jediném jazyce, uvádí se kód tohoto jazyka pouze zde a pole 041 se
&nbsp;&nbsp;&nbsp;&nbsp; již nezapisuje. V případě dokumentu ve více jazycích, překladu, s cizojazyčnými resumé, apod. se všechny kódy jazyků zapisují do &nbsp;&nbsp;&nbsp;&nbsp; příslušných podpolí v poli 041 a na pozicích 008/35-37 se zapisuje pouze kód dominantního jazyka popisné jednotky.  
&nbsp;&nbsp;&nbsp;&nbsp; Zdrojem kódu je MARC Code List for Languages, který spravuje  
&nbsp;&nbsp;&nbsp;&nbsp; Library of Congress - viz [http://www.loc.gov/marc/languages](http://www.loc.gov/marc/languages).

**008/38 - kód modifikace záznamu**  
&nbsp;&nbsp;&nbsp;&nbsp; pozice zůstává prázdná, záznam nebyl modifikován

**008/39 - zdroj katalogizace**  
&nbsp;&nbsp;&nbsp;&nbsp; \# - Národní bibliografická agentura  
&nbsp;&nbsp;&nbsp;&nbsp; c - program kooperativní katalogizace  
&nbsp;&nbsp;&nbsp;&nbsp; d - jiný  
&nbsp;&nbsp;&nbsp;&nbsp; u - není znám  
&nbsp;&nbsp;&nbsp;&nbsp; \|   - kód se neuvádí

Zpracovává-li bibliografický záznam NK ČR, zůstává pozice prázdné.
