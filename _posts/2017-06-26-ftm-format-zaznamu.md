---
layout: default
title: FMT (Formát záznamu)
---


## FMT (Formát záznamu)

Kód v poli FMT by měl být v souladu s kódem určujícím typ záznamu/obsah dokumentu v návěští (LDR/06 + LDR/07).

**Kód nevyplňuje katalogizátor, ale je dán typem šablony**

Pro potřeby Webarchivu používáme většinou formát záznamu SE. V případě textových dokumentů mají záznamy v poli FMT kód SE (bez ohledu na formu, podmínkou je hodnota LDR/06=a + LDR/07=s/i).

Pokud je u pokračujícího zdroje dominantní jiný než textový obsah (např. mapy, zvuk, obrázky apod.), uvádí se v poli FMT kód odpovídající příslušnému typu záznamu/obsahu dokumentu z návěští (LDR/06).  Např. u zdroje s kartografickými údaji, má záznam v poli FMT kód MP. Pokud jsou obsahem zdroje obrazové informace, má záznam v poli FMT kód GP. V těchto případech musí být ale v záznamu doplněna dvě pole 006:  první pro elektronický aspekt (pozice 006/00=„m“), druhé pro pokračující zdroj (pozice 006/00=„s“). Charakteristika seriálu se v tomto případě uvádí v poli 006 (kód pro seriál, periodicitu, pravidelnost vydávání atd.), odkud lze generovat kód SE pro vyhledávání. Viz též  006 (další charakteristiky dokumentu).

Přehled zkratek FMT používaných v NK ČR:

* MP    Kartografické dokumenty
* ER    Elektronické zdroje
* MU    Hudebniny
* AM    Zvukové záznamy
* GP    Grafika
* RE    Rešerše
* RP    Staré tisky
* MX    Smíšené dokumenty
* TD    Trojrozměrné objekty
* VM    Obrazové dokumenty
* FI    Filmy
* BX    Pracovní záznamy
