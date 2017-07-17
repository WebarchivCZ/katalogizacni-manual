---
layout: default
title: Název a další názvové údaje, nakladatelské údaje 
---
Název a další názvové údaje

222 (Klíčový název) (O)
Týká se jen zdrojů s přiděleným ISSN. Pro ty je povinným údajem. Pole vyplňujeme na základě údajů z databáze ISSN  https://aleph.techlib.cz/F/?func=find-b-0&local_base=stk02 .



245 Údaje o názvu (včetně údajů o odpovědnosti) (NO)
Údaje se zapisují přesně tak, jak se vyskytují na provedení – včetně chyb a překlepů. Správný údaj se pak zapisuje jako varianta názvu nebo do poznámky.
Slova se nezkracují, pokud tak ovšem nejsou na prameni uvedena; číslovky se zapisují také přesně – nevynechávají se, ani se nepřepisují na arabské číslice.
Psaní velkých písmen se řídí gramatickými pravidly daného jazyka viz. Příloha psaní velkých a malých písmen.
Zapisují se i použitá diakritická znaménka a úvodní členy. Jednopísmenné iniciály a akronymy se zapisují bez mezer.
Přesně podle provedení se zapisuje i interpunkce, symboly a značky. Vynechat lze pouze typografické značky, které slouží jako oddělovače a nemění smysl a obsah údaje.

Hlavní název
Je hlavním pojmenováním provedení a obvykle je typograficky zvýrazněn. Je-li na prameni popisu uveden název ve více jazycích a/nebo písmech, volí se za hlavní název vždy název v jazyce dokumentu (jediného či převažujícího). Ostatní se zapíší jako názvy souběžné.

Alternativní název je součástí hlavního názvu a odděluje se spojovacím výrazem (aneb, oder, atd.) s oboustrannými čárkami.
Příliš dlouhý název (či další názvová informace) může být zkrácen, a to nejdříve po prvních 5 slovech (členy se nepočítají), ale nesmí to mít vliv na ztrátu informací či identifikaci díla. Pro vynechanou část názvu se použije znak pro výpustku – tři tečky s oboustrannou mezerou.
Je-li gramaticky nedílnou součástí názvu či další názvové informace i údaj o odpovědnosti, zapíše se tam a již se neopakuje v údajích o odpovědnosti (pokud ovšem není na zdroji znovu uveden).

Údaje o odpovědnosti
Přebírají ze stejného pramene jako hlavní název, případně z dalších preferovaných pramenů. Uvádějí se osoby a/nebo korporace odpovědné za intelektuální nebo umělecký obsah popisovaného zdroje (autor, spoluautor, editor, překladatel, ilustrátor, atd.).
Zapisují se všichni autoři uvedení na preferovaném prameni popisu (včetně případné fráze/úvodního výrazu). Mají-li různou funkci, zapisují se v pořadí uvedeném na prameni popisu.
V údajích o odpovědnosti se vynechávají tituly, oslovení, afiliace, kvalifikace a podobné výrazy; zapisují se jen jména či jména s uvedenou frází. Označení junior, syn a další rodové vztahy se nevynechávají, zůstávají součástí zápisu.
Jako údaj o odpovědnosti se zapíše i údaj bez konkrétního jména (např.: napsal kolektiv autorů), je-li takto uveden na preferovaném prameni popisu.
Původci uvedení pouze v copyrightu	(např. významný překladatel podle národní interpretace) se zapisují do poznámky, nikoli v oblasti údajů o názvu a odpovědnosti

Př. 24510
$a...a život jde dál :$bvzpomínky Petra Látala na léta válečná

24514$aDie Schule der Frauen :$bLuftspiel in fünf Aufzügen /$c[Molière]
(Autor nebyl uveden nikde v popisovaném provedení ; chyba v podnázvu)
500$aSprávný podnázev je: Lustspie l in fünf Aufzügen


Indikátory:
- pokud v záznamu použijeme hlavní záhlaví (1XX), první indikátor je 1 (vedlejší záhlaví se vytváří), jinak bude první indikátor 0 (vedlejší záhlaví se nevytváří, tzn. dokument je zkatalogizován pod názvem)

Další názvová informace
Přebírá se pouze ze stejného pramene popisu jako hlavní název, je-li uvedena jinde, nezapisuje se, nebo jen velmi výjimečně a jen do poznámky, nikdy nedoplňujeme do [ ].

Při popisu elektronických zdrojů platí pro zápis dalších názvových informací obecná pravidla. Pokud je další názvová informace považována za důležitou, lze ji zapsat jako vedlejší názvové záhlaví do pole 246.


- Podnázev
Pokud pramen popisu obsahuje podnázev, zapíše se do $b. Podpole $a je ukončeno _: (mezera dvojtečka). Podpole $b začíná vždy malým písmenem, pokud nezačíná slovem, které se píše s velkým písmenem (řídí se jazykovými pravidly příslušného jazyka).
Podnázev se přebírá pouze ze stejného pramene popisu jako hlavní název, je-li uvedeno jinde, píše se do poznámky.

př. 245 10 $a Proudy :
	$b středoevropský časopis pro vědu a literaturu

- Souběžný název
Pokud dokument obsahuje názvy ve dvou nebo více jazycích, zapíše se do $a první/hlavní název, do $b se zapíše souběžný název. Za podpolem $a následuje _= (mezera rovnítko). Zapíše se také do podpole 246. Souběžné názvy se přebírají z celého provedení, nejen ze stejného pramene jako hlavní název, a nezapisují se do []


př. v prameni popisu Česká softballová organizace a Czech softball association
	245 10 $a Česká softballová asociace =
	$b Czech Softball Association
	246 31 $a Czech Softball Association

př. v prameni popisu Česká advokátní komora, Tschechische Rechtsanwaltskammer, La Barreau tcheque a Czech Bar Association
	245 10 $a Česká advokátní komora =
		$b Tsechische Rechtsanwaltskammer = La Barreau tcheque = Czech Bar Association
	246 31	$a Tsechische Rechtsanwaltskammer
	246 31	$a La Barreau tcheque
	246 31	$a Czech Bar Association

- WWW a úvodní slova v názvu
Slova, která uvádějí název a nejsou přitom jako součást názvu míněna, se nezapisují, např. „Vítejte na stránkách“. Hlavní název se zapisuje bez těchto úvodních frází a ve variantním názvu se zapisuje název celý.

př. na stránkách uvedeno „Vítejte na webových stránkách Tomáše Halíka“
	245 10	$a Tomáš Halík
	246 1#	$i Úvodní název webových stránek: $a Vítejte na webových stránkách Tomáše Halíka

Hlavní název se zapisuje přesně, pokud jde o stylistické znění, pořadí a pravopis, není však nutné přesně dodržet psaní velkých písmen a interpunkci obsaženou v názvu.

př. na stránkách uvedeno „Vítejte v jazykovém centru Filozofické fakulty!“
	245 10	$a Jazykové centrum Filozofické fakulty
	246 1#	$i Úvodní název webových stránek: $a Vítejte v jazykovém centru Filozofické fakulty!

Pokud je název koncipován jako URL adresa, zapisujeme www jako součást názvu (www.astronomie.cz).

př. 	245 00	$a Www.tuning.cz
	246 30 $a Tuning

- Datum součástí názvu
Pokud je součástí hlavního názvu datum, jméno, číslování apod., které se s dalšími vydáními/aktualizacemi mění (např. rok konference nebo festivalu), zapisuje se název bez tohoto údaje. Pokud je tento údaj nedílnou součástí názvu, zapisuje se místo něj znak pro výpustku (…).

U pokračujících zdrojů se výpustka na začátku názvu nebo na konci značí pouze pravostrannou mezerou:
př. 245 00 $a… ročník mezinárodního veletrhu PIVEX


př. 245 00	$a Jeden svět ... (název na zdroji: Jeden svět 2010)
	500	$a Součástí hlavního názvu je označení roku

ale
	245 00	$a… Mezinárodní filmový festival Karlovy Vary
	(název na zdroji: 45. Mezinárodní filmový festival Karlovy Vary)

- Zkratka v názvu
Pokud je hlavní název uveden v prameni popisu jednak v úplné a jednak ve zkrácené podobě (akronym nebo zkratka), hlavním názvem je plná forma názvu. Zkratka, akronym se zapíše jako podnázev a zároveň se uvede do pole 246 30 část názvu/Název části

př. 245 10	$a Asociace neprofesionálních komorních a symfonických těles :
	$b ANKST
	246 30	$a ANKST

Pokud název obsahuje zároveň souběžný název a další názvovou informaci, zapište další názvovou informaci za tou částí hlavního či souběžného názvu, k níž náleží.

Zkratka a souběžný název
př. v prameni popisu Národní technická knihovna, National technical library, NTK
	245 10	$a Národní technická knihovna :
		$b NTK = National technical library
	246 31	$a National technical library
	246 30	$a NTK

Zkratka a podnázev
př. 245 10	$a Společnost pro zahradní a krajinářskou tvorbu :
	$b SZKT : občanské sdružení
	246 30	$a SZKT
v případě, že název obsahuje více podnázvů uvádějí se za dvojtečkou

Změna názvové informace
Při změně další názvové informace, která je považována za významnou, by se změna měla promítnout v bibliografickém záznamu v poli 245$b. Další názvovou informaci ve tvaru, v jakém se vyskytovala v předchozích interacích, lze zapsat do pole 246. Na rozdíl od změny hlavního názvu, kdy se dříve platný hlavní název zapisuje do pole 247.

246 (Variantní názvy) (O)
Indikátory:
 indikátor
1	Generuje se poznámka i vedlejší záhlaví (generuje se poznámka znamená, že se ve standardním zobrazení záznamu v OPACu objeví také variantní název, jinak je pole 246 vidět pouze v MARC zobrazení).
př. pokud je název ve zdrojovém kódu jiný (a smysluplný), je vhodné ho zobrazit
Generuje se vedlejší záhlaví, negeneruje se poznámka
př. pokud v 246 píšeme varianty názvu bez www, pomlček apod., není potřeba poznámku zobrazovat; to platí také pro souběžný název, podnázev
 indikátor
246 1#	- typ názvu není specifikován (ze zdrojového kódu...)
2246 30	- část názvu/název části – podnázev, zkratka
46 31	- souběžný název
246 13	- další variantní název

Častým problémem u elektronických zdrojů je výskyt různých variant názvu ve zdroji. Po zvolení hlavního názvu by ostatní varianty názvu měly být uvedeny v poli 246, pokud jsou považovány za důležité pro identifikační nebo selekční účely. Variantní názvy se zapisují do pole 246.

Pokud je potřeba zobrazit specifické návěští, zapíše se pramen variantního názvu do pole 246$i a vlastní název do podpole 246$a generuje poznámka (první indikátor 0 (negeneruje se vedlejší záhlaví) nebo 1) a je vhodné uvést upřesnění, použijte podpole i.

Př.: $i  Název ve zdrojovém kódu:
$a České akční hry
$i  Název na titulní obrazovce:
$a MagPortal.cz

- Diakritika
př.: 	245	00	$a Www.cinnostni–uceni.cz
	246	30	$a Cinnostni-uceni.cz
	246	3#	$a Činnostní učení
	246	1#	$i Název ve zdrojovém kódu:
	$a Vzdělávání-učitelů.cz


- WWW a úvodní slova v názvu viz 245
Z důvodů vyhledatelnosti vždy zapisujeme název včetně úvodních slov, která byla vypuštěna v poli 245 (např. www nebo Vítejte...). Hodnotu prvního indikátoru volíme v závislosti na tom, zda chceme zobrazovat také jako poznámku či nikoliv – pokud vynechaná slova zásadně nemění název (viz příklad u pole 245), není třeba poznámku zobrazovat. V ostatních případech je vhodné poznámku zobrazit.

Variantní název se zapisuje vždy, pokud je název ve zdrojovém kódu smysluplný odlišný od názvu na obrazovce.

Pokud dojde ke změně variantního názvu a jestliže je tato změna považována za významnou, lze zapsat do pole 246 předchozí variantu názvu popř. jinou názvovou informaci.


247 (Předchozí název) (O)
Do pole 247 zapisujeme názvovou informaci  v případě, že došlo ke změně hlavního názvu webové stránky. Pole 247 slouží k uchování původního hlavního názvu webové stránky, zatímco do pole 245 zapíšeme název nový. První indikátor pole 247 musí být vždy 1 .
př.: 	245 00 $a Gestalt Praha
	247 10 $a Gestalt.cz

Pokud dojde pouze ke změně vedlejšího názvu a tento je považován za důležitý pro vyhledávání, může se původní vedlejší název zapsat do pole 246 (variantní názvy).

264 (Nakladatelské údaje, údaje o vytvoření díla a údaje o autorských právech) (O)
Indikátory:
První indikátor: pořadí údajů
# Neuvádí se první údaj (jednotka katalogizována poprvé, příp. ukončené monografické dílo)
2 Dočasný údaj (pokud se nakladatelé mění, mezi prvním a posl. nakladatelem)
3 Současný/poslední údaj (pokud se změnilo místo nebo jméno spojené s vydáním zdroje)
Druhý indikátor: funkce
0 Vytvoření/vznik (pro nezveřejněná díla)
1 Nakladatel
2 Distributor
3 Výrobce
4 Údaje o autorských právech

Povinné je vždy pole 264 s druhým indikátorem 1

Pro publikované zdroje jsou povinnými údaji místo vydání, jméno nakladatele a datum vydání. Datum copyrightu je doporučeným údajem tehdy, pokud není známo ani datum vydání, ani datum distribuce. Toto datum se zapisuje včetně symbolu copyrightu © nebo symbolu fonogramu ℗.
264#1 $a Praha :
$b Nakladatelství Lidové noviny,
$c [2014]
264#4 $c ©2014

Údaje se přebírají z celého popisovaného provedení - primárně ovšem ze stejného pramene jako hlavní název; případně z dalších jiných pramenů či se logicky odvodí. Každý údaj z jiného zdroje či odvozený se zapisuje do vlastní hranaté závorky.
Údaje se zapisují přesně tak, jak jsou na prameni popisu uvedeny, nic se nezkracuje ani nevynechává (ani členy), neopravuje (správná podoba se uvede do poznámky). Datum vydání uvedené slovně či římskými číslicemi se přepisuje na arabské číslice.

Pokud potřebné údaje nejsou v popisovaném provedení uvedeny, vždy se snažíme alespoň přibližně určit místo (obec či státní území v současném pojetí) a datum vydání (přibližný rok či rozmezí let). Tyto údaje patří do hranatých závorek, případně jsou doplněny otazníkem. Až jako poslední, velmi výjimečnou variantu zapisujeme frázi: [Místo vydání není známé]. Pokud nelze zjistit nakladatele, zapisujeme frázi: [nakladatel není známý]. Frázi [datum vydání není známé] se nedoporučuje vůbec používat, vždy bychom měli doplnit nějaké přibližné datum vydání.

Př.: 	264 #1	$a [Česko] :
$b [nakladatel není známý],
$c [2003?]-

Pokud zdroj nemá ukončené vydávání, zapisuje se na konci pomlčka, po ukončení vydávání se dopíše rok vydání poslední verze:

Velká Lhota : Miroslav Urban, [2009?]-
Praha : Národní knihovna ČR, 1999-2004

Každý údaj přejatý z jiného zdroje je ve vlastních hranatých závorkách
264 #1 $a [Česko] :
$b Fortuna,
$c [2006]-
264 #1 $a [Česko] :
$b [nakladatel není známý],
$c [2003]

Pokud má zdroj dvě místa vydání a jednoho nakladatele, zapíše se takto:
např.:	264 #1	$a Praha ;
	$a Litomyšl :
	$b Paseka,
	$c 2003

Pokud má zdroj dvě místa vydání a více nakladatelů, zapíše se takto:
např.:	264 #1	$a Brno :
	$b ERA, s.r.o. :
	$b Státní památkový ústav v Brně ;
	$a Olomouc :
	$b Státní památkový ústav v Olomouci,
	$c 2001-

- změna vydavatele
Pokud došlo k změně vydavatele, zapíše se to takto:
	264 #1	$a místo vydání :
$b první vydavatel,
$c rok-
	264 31	$3 rok- $a místo vydání současného vydavatele : $b současný vydavatel
např. Paidagogos (001636711)

Pokud došlo k další změně vydavatele, zapíše se takto:
	264 #1	$a místo vydání :
$b první vydavatel,
$c rok-
	264 21	$3 rok od do $a místo vydání předchozího vydavatele : $předchozí vydavatel (vydával dílo mezi prvním a současným vydavatelem)
	264 31	$3 rok- $a místo vydání současného vydavatele : $b současný vydavatel
např.
264#1 $aPraha : $bSvoboda, n.p.,$c1964-
26421 $31975-1989$aPraha :$bMladá fronta
26431 $31990-$aPraha ;$aLitomyšl :$bPaseka

Pokud není počáteční datum vydání jednoznačně zapsáno nebo je nejisté, do podpole $c se zapisuje nejisté datum (někdy jen odhadovaný rok) v hranatých závorkách a s otazníkem. Toto pravděpodobné datum se uvede i v poli 008/7-10.
	264 #1	$a Vlašim : $b Konopářský svaz České republiky, $c [2005?]-

Pokud je datum ukončení vydávání známé (264 $c), je třeba upravit také příslušné údaje v poli 008 (poz. 06 + 11-14) .


Vročení (zahájení a ukončení vydávání)
Integrační zdroje:
Pro odhad počátečního nebo konečného data vydávání lze jako určitý indikátor použít data  copyrightu, je třeba ale postupovat obezřetně. Pokud je např. ve zdroji uvedeno rozpětí dat copyrightu, lze zapsat první datum jako pravděpodobné datum zahájení vydávání (datum uvedené na druhém místě však nelze považovat za datum ukončení vydávání). Pokud je však ve zdroji uvedeno pouze jedno datum copyrightu, nelze jednoznačně doporučit zapsat ho jako pravděpodobné počáteční datum vydávání. Je častou praxí, že se datum copyrightu na webových zdrojích aktualizuje pro právě probíhající rok, přestožestránky mohou být v provozu již delší dobu.

Příkladem elektronických interací jsou webové stránky. Datum na nich většinou nebývá uvedeno, a pokud ano, nemusí se nutně nacházet na hlavní stránce. Je proto nutno hledat i v jiných částech zdroje, např. „O nás“, „Historie projektu“  apod. Je-li datum uvedeno ve zdroji, zapisuje se do 264$c bez hranatých závorek. Jestliže datum vydání není uvedeno ve zdroji, lze ho zjistit pomocí archivů elektronických zdrojů  Internet archive https://www.archive.org/, popř. Webarchiv http://www.webarchiv.cz/cs. Zjištěné datum se zapisuje do hranatých závorek.

Pokud je u seriálu dostupné první číslo nebo u integračních zdrojů první interace, zapisuje se v poli 260$c počáteční datum a za ním se doplní spojovník.


Datum zahájení
a/ Datum zahájení vydávání je uvedeno ve zdroji
př.	264 #1	$a Praha : $b Petr Jandík, $c 2006-

b/ Datum zahájení vydávání není jednoznačně zapsáno nebo není uvedeno vůbec (dohledáváme v Internet Archive https://archive.org/ nebo ve Webarchivu http://webarchiv.cz/cs  )
př.	264 #1	$a Praha : $b Petr Jandík, $c [2006?]-

c/ Pokud je ve zdroji uvedeno pouze datum copyrightu, zapíše se rok do hranaté závorky a copyright včetně symbolu „©“.
př.  264 #1 $a [Česko] : $b Fortuna, $c [2006?]-
264 #4 $c ©2006-

Datum ukončení
a/ Datum zahájení i ukončení je uvedeno ve zdroji
př.	264 #1	$a Praha : $b Petr Jandík, $c 2006-2008

b/ Datum zahájení je uvedeno ve zdroji, datum ukončení odhadované (např. podle Waybacku, podle data zjištění nedostupnosti stránek)
   př. 264 #1	$a Praha : $b Petr Jandík, $c 2006-[2008?]

c/ Datum zahájení vydávání není uvedeno ve zdroji, datum ukončení je ve zdroji uvedeno
př.	264 #1	$a Praha : $b Petr Jandík, $c [2006?]-2008

d/ Datum zahájení vydávání ani datum ukončení není uvedeno ve zdroji ani nejsou data známa; data jsou zjištěna explicitně (např. dotazem na vydavatele)
př.	264 #1	$a Praha : $b Petr Jandík, $c [2006-2008]
