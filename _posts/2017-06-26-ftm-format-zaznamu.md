---
layout: default
title: FMT (Formát záznamu)
---


## FMT (Formát záznamu)

Kód v poli FMT odpovídá typu záznamu uvedenému v poli LDR/06. Jedná-li se o zdroj s textovým obsahem, tj. LDR/06=a, je v poli FMT uvedena hodnota SE.    

Kód nevyplňuje katalogizátor, je dán typem šablony.  

Pro potřeby Webarchivu používáme většinou formát záznamu **SE**. V případě textových dokumentů mají záznamy v poli FMT kód SE (bez ohledu na formu, podmínkou je hodnota LDR/06=a + LDR/07=s/i).


Pokud jsou obsahem zdroje kartografické údaje, má záznam v poli FMT kód MP. Pokud jsou obsahem zdroje obrazové informace, má záznam v poli FMT kód GP. V těchto případech musí být ale v záznamu doplněna dvě pole 006:  první pro elektronický aspekt (pozice 006/00=„m“), druhé pro pokračující zdroj (pozice 006/00=„s“).

**Přehled zkratek FMT používaných v NK ČR:**

* SE    Seriály
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
