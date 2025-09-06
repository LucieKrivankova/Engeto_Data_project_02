# Bike Sharing System (Boston) – Power BI Projekt

Cílem projektu je analyzovat využívání služby sdílených kol v Bostonu a připravit přehledné vizualizace a doporučení pro vedení společnosti.

---

## Cíle projektu
- Vyhodnotit provoz služby **Bike Sharing System** v letech **2015 a 2016**.
- Zjistit chování uživatelů a identifikovat možné **zneužívání služby**.
- Posoudit efektivitu jednotlivých stanic a jejich vytížení.
- Zhodnotit vliv **počasí** na počet jízd.
- Odhalit možné **anomálie** v datech.
- Vizualizovat **rozložení stanic v Bostonu**.

---

## Zdroje dat
- **Hubway trip data**: [hubway-data](https://s3.amazonaws.com/hubway-data/index.html)  
  Obsahuje záznamy jednotlivých jízd (datum a čas začátku/ukončení, ID stanice, ID kola, typ uživatele, pohlaví, rok narození, atd.).
- **Boston Weather**: dataset s hodinovými meteorologickými údaji (teplota, vlhkost, rychlost větru).

---

## Analytické oblasti

1. **Nadstandardní využití kola**  
   - Identifikace uživatelů, kteří využívali kolo déle než 2 hodiny.  
   - Analýza podle typu uživatele, pohlaví a roku narození. 

2. **Využití stanic**  
   - Počet zahájení a ukončení jízd na jednotlivých stanicích.  
   - Hodnocení efektivity stanic (měsíčně i denně).  
   - Porovnání vytíženosti stanic mezi roky 2015 a 2016.

3. **Vliv počasí na počet jízd**  
   - Závislost denního počtu jízd na průměrné teplotě a vlhkosti.  

4. **Možné anomálie v datech**  
   - Statistické charakteristiky (minimum, maximum, medián, průměr, směrodatná odchylka).  
   - Odhalení neobvyklých hodnot v datech (extrémní délky jízd, věk uživatelů, geografické odchylky).

5. **Rozložení stanic v Bostonu**  
   - Mapová vizualizace stanic.  
   - Možnost sledování historického vývoje a pokrytí města.

---

## Jak otevřít projekt
1. Stáhněte soubor `BikeSharing_Boston.pbix`.  
2. Otevřete jej v aplikaci **Microsoft Power BI Desktop**.  
3. V případě potřeby aktualizujte cesty ke zdrojovým datům.  
