---
layout: default
title: LDR (Návěští)
---

## LDR (Návěští) (NO)

### LDR/00-04 délka záznamu
### LDR/05 - status záznamu

```
        a - doplněný záznam
        c - opravený záznam
        d - zrušený záznam
        n - nový záznam
        p - doplněný prozatímní záznam
```

Při katalogizaci se používá hodnota **„n“**, dojde-li k významné změně v záznamu (např. změna názvu), je třeba změnit hodnotu **„n“** – nový záznam na **„c“** – opravený záznam, popř. **„a“** – doplněný záznam, nebo **„d“**- zrušený záznam. Toto se neprovádí pro každou drobnou změnu v záznamu, pouze pro opravdu podstatné změny. Zároveň je třeba vytvořit nové pole IST 1 (viz poznámka pro pole IST).

### LDR/06 - typ záznamu

Pro běžný online elektronický zdroj s převažující textovou podobou se uvádí hodnota **„a“** - textový dokument. Hodnota **„m“** - elektronický zdroj - se požívá pouze pro určité typy zdrojů, jako je např. počítačový software, číselná data, počítačově orientovaná multimédia, systémy online nebo síťové služby aj.

### LDR/07 - bibliografická úroveň

```
    a - analytická část (monografie)
    i - integrační zdroj
    m - monografie
    s - seriál
```    

**Za seriály považujeme pouze zdroje „vydávané po částech, které jsou číselně nebo chronologicky označeny“** (MARC 21 : Bibliografický formát, Praha 2003). Tedy ne všechny zdroje, jimž bylo přiděleno ISSN. Vzhledem k možnostem, které prostředí internetu nabízí, je však v některých případech obtížné rozhodnout, zda se ještě jedná o seriál nebo už o integrační zdroj. Řada seriálů v internetovém prostředí nabízí kromě vlastních článků také další služby.

### LDR/08 - typ kontroly

```
     # - není specifikován
     a - archivní dokument
```

### LDR/09 - použitá znaková řada
    a - UCS/Unicode

### LDR/10 - délka indikátorů

### LDR/11 - délka označení podpole

### LDR/12-16 - bázová adresa údajů

### LDR/17 - úroveň úplnosti záznamu

```
\# - Úplná úroveň
1 - úplná úroveň, bez dokumentu
2 - méně než úplná úroveň, bez dokumentu
3 - zkrácený záznam
4 - základní úroveň
5 - částečně zpracovaný/dočasný záznam
7 - minimální úroveň
8 - před vydáním dokumentu
u - není znám
z - nelze použít
```


### LDR/18 - forma katalogizačního popisu

```
# - jiná než ISBD
a - AACR2
**i - ISBD**
u - není známa
```
