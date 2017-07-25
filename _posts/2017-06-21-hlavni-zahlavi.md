---
layout: default
title: Hlavní záhlaví
---
## Hlavní záhlaví

1XX záznamy se přebírají  z AUT - [Databáze národních autorit NK ČR](http://aleph22.nkp.cz/F/?func=file&file_name=find-b&local_base=aut).

Pokud se záznam v databázi nachází, je nutné uvádět autoritní tvar. V případě, že v databázi není, a katalogizátor usoudí, že se jedná o významnou autoritu, může vyhotovit její návrh. Pole lze také doplnit autoritou, která se v databázi nenachází, ani není vyhotoven její návrh.


### 100 (Hlavní záhlaví – osobní jméno) (NO)
Osobní jméno použité jako hlavní záhlaví je jméno osoby s hlavní odpovědností (tvůrce, další osoba spojená s dílem, přispěvatel). Jsou-li autoři (přímí i nepřímí) uvedeni na titulní stránce, zapisují se všichni jak do pole 245, tak do polí 100/700 jako selekční údaje (bez ohledu na počet uvedených autorů je vždy první z nich uveden v hlavním záhlaví), jsou-li na titulní stránce uvedeni pouze nepřímí autoři (např. editor), zapisují se do 245 a 700 a přímí autoři se již nedohledávají.

V záznamu smí být pouze jedno pole 100 a s ním se nesmí v jednom záznamu vyskytovat ani pole 110, ani 111.
V případě, že na zdroji není uveden žádný autor, nedohledává se. Výjimkou jsou díla, jejichž tvůrce je obecně znám/tvůrci jsou známi, pouze nejsou v určitém provedení uvedeni. V těchto případech se zapíší v poli 245 v hranaté závorce a v příslušném poli 100/700 jako selekční údaj.

```
např.:
Dílo má pět tvůrců se stejnou mírou autorské odpovědnosti.  

100 1   $a Žemlička, Jan
245 10  $a Celní zákon a předpisy související v praxi
        $c Jan Žemlička, Pavel Hruška, Helena Nováková, Jana Zelená, Květoslav Horák
700 1   $a Hruška, Pavel
700 1   $a Nováková, Helena
700 1   $a Zelená, Jana
700 1   $a Horák, Květoslav
```
Nově se vytváří záznam v bázi autorit - návod viz [dokument](http://sps/aleph/SitePages/Home.aspx)

Metodika: [Korporativní autority podle RDA](http://www.nkp.cz/o-knihovne/odborne-cinnosti/zpracovani-fondu/katalogizacni-politika/rda) a [Autority podle RDA](http://www.nkp.cz/o-knihovne/odborne-cinnosti/zpracovani-fondu/katalogizacni-politika/rda)

Pro volbu správné podoby jména (pravopis, iniciály, rozepsané iniciály apod.) se používá
přednostně Databáze národních autorit.

Jedná-li se o anonymní dílo, tj. dílo, u kterého se neuvádí žádný tvůrce, nezapisuje se do pole 700, ale do pole 730.

### 110 (Hlavní záhlaví – jméno korporace) (NO)
Jako hlavní/vedlejší záhlaví se zapisují korporace, které mají autorský podíl na vzniku díla/vyjádření/provedení. Je-li korporace zapsána jako selekční údaj v poli 110 nebo 710, měla by o ní být zmínka také v popisných údajích – obvykle buď v poli 245 nebo v poznámkách (pole oblasti 5XX).  

Do pole 110 se zapisuje korporace s hlavní autorskou odpovědností za vznik díla. V záznamu smí být pouze jedno pole 110 a současně s ním se nesmí v jednom záznamu vyskytovat ani pole 100, 111 nebo 130.


Vyskytuje-li se jméno korporace v několika jazycích, zapíše se v jazyce korporace. Pokud je oficiálních jazyků několik a jedním z nich je čeština, v poli 100/700 bude jméno zapsáno česky.

**Popis pod jurisdikcí:** Státní instituce, jako je vláda, parlament, magistrát atd., se zapisují pod státním/správním celkem, jehož jsou orgánem. V podpoli $a potom používáme jako vstupní prvek konvenční jméno příslušného správního celku; to by mělo být zapsáno v české formě, pokud existuje.

V těchto případech má první indikátor hodnotu 1.

```
např.:
$aČesko. $bParlament
$aPardubice (Česko). $bMagistrát
$aBavorsko (Německo). $bStaatsministerium der Finanzen
```

**Změna jména korporace:** Změní-li se jméno korporace, z hlediska katalogizace se potom jedná o jinou korporaci. V poli **110/710** tedy bude zapsané jméno odpovídající době, kdy byl zdroj publikován. Současně se do pole **510 – odkaz viz  též jméno korporace** – uvede jméno související korporace (nejčastěji jde o dřívější nebo novější podobu jména při změně názvu korporace). Pole směruje na záhlaví souvisejícího autoritního záznamu. Forma jména korporace v poli 510 je vždy totožná s autoritní podobou jména korporace v záhlaví souvisejícího autoritního záznamu (pro nový název se vždy vytvoří nové autoritní záhlaví a to se uvede do pole 510).

Pro vysvětlení vzájemných vztahů mezi autoritním záhlavím a odkazy viz též, zejména u „českých“ korporací, se doporučuje použít poznámku v poli **655**.

```
např.:
110 2   $a Muzeum české hudby (Praha, Česko)
        $7 kn20010709073
510 2   $w b
        $a České muzeum hudby (Praha, Česko)
        $7 ko2004175709
665     $a Novější název korporace: České muzeum hudby (od r.2001).
```



Kódy rolí v podpoli 4 jsou doporučené, hodnota „pbl“ (publisher), příp „aut“ (autor).



### 111 (Hlavní záhlaví – jméno akce) (NO)
Jméno akce, konference nebo festivalu použité jako hlavní záhlaví, např. FIS Mistrovství světa v klasickém lyžování Liberec 2009 ([001824203](http://aleph.nkp.cz/F/?func=direct&doc_number=001824203&local_base=nkc)).  
Z hlediska katalogizačních pravidel je 111 druhem korporace (110). Kódy rolí v podpoli 4 jsou doporučené, hodnota „pbl“ (publisher).
