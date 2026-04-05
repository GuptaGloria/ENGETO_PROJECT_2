# ENGETO_PROJECT_2
Project 2 focused on Power BI to gain ENGETO certification

Úvod

Tento Power BI dashboard přináší komplexní analýzu hudebních trendů platformy Spotify pro rok 2025, přičemž se zaměřuje na propojení popularity interpretů s technickými parametry jejich skladeb. Projekt demonstruje pokročilé zpracování dat ze dvou hlavních zdrojů (umělci a skladby), která jsou v interaktivním prostředí obohacena o vlastní DAX metriky a dynamické vizualizace. Cílem reportu je poskytnout uživateli intuitivní nástroj pro sledování úspěšnosti žánrů, loajality fanoušků a audio vlastností globálních hitů v moderním vizuálním stylu inspirovaném přímo estetikou Spotify. Pro zpracování projektu bylo nutné splnit kritéria, která jsou shrnuta níže.

1. Rozsah 2-5 stránek
- Projekt je koncipován jako vícestránkový report, což umožňuje oddělit globální statistiky od detailních pohledů na jednotlivé skladby a obsahuje 2 funkční strany:
-   Dashboard: Přehled klíčových metrik a žánrové popularity.
-   Additional Info: Další detaily.



2. Použití minimálně 5 různých typů vizuálů
- Skládaný sloupcový graf (Stacked Bar Chart): Pro srovnání počtu streamů v jednotlivých zemích.
- Tabulka: Pro detailní výpis skladeb s jejich pořadím a metrikami.
- Stromová mapa: Ideální pro zobrazení podílu žánrů na celkovém trhu (plocha odpovídá popularitě).
- Karty: Pro okamžité zobrazení hlavních KPI, jako jsou celkové miliardy streamů.
- Průřezy: Filtrace podle roku vydání.
- Koláčový graf: Pro interprety (jestli se jedná o může, ženu, kapelu)
- Tečkový graf: analyzuje korelaci streamů a followerů.



3. Filtrování pomocí průřezů/slicerů
- Interaktivita je postavena na Slicerech, které uživateli umožňují okamžitě měnit kontext celého dashboardu. Hlavní filtr je zaměřen na Země (Country) a Žánry (Primary Genre). Díky správně nastaveným vazbám v modelu se při výběru konkrétního státu automaticky přepočítají všechny grafy, tabulky i celkové součty na kartách.



4. Využití interaktivních prvků
- Report využívá pokročilé funkce Power BI pro zvýšení uživatelského komfortu:
- Navigace: Propojení stránek pomocí navigačních prvků v dolní části reportu (šipky).
- Cross-filtering: Vizuály jsou vzájemně propojeny – kliknutím na konkrétní žánr v grafu se automaticky vyfiltruje tabulka skladeb pouze pro tento žánr.
- Image URL: Sloupec s obrázky je nastaven jako webová adresa, což umožňuje dynamické načítání vizuálů interpretů přímo z externích zdrojů.



5. Propojení několika datových tabulek
- V datovém modelu jsou integrovány dvě hlavní tabulky (artists a songs), které jsou propojeny skrze společný klíč (jméno umělce).



6. Vytvoření alespoň 1 measure (metrika/míra) a 1 kalkulovaného sloupce/tabulky
- Measure: Na slidu Dashboard je vypočítaný celkový počet streamů v miliardách.
- Kalkulovaný sloupec: Poslední sloupec v tabulce Additional info s názvem Energy dance score, který násobí hodnoty energy a danceability, pokud je skóre blízko 100, je to "párty píseň"



7. Grafická úprava použitých vizuálů, zvolení správných typů vizuálů a vizuálně přívětivý výsledný report
- Celý report prošel výraznou estetickou úpravou, aby odpovídal brandu Spotify:
- Barevné schéma: Dominantní tmavé pozadí (Dark Mode) se sytě zelenými akcenty.
- Minimalismus: Odstranění zbytečných okrajů a pozadí u vizuálů, aby report působil čistě a profesionálně.
- Typografie a popisky: Sjednocení fontů a úprava názvů os, aby byly srozumitelné i pro laického uživatele.
- Funkčnost: Volba vizuálů (např. Treemap místo koláčového grafu) byla podřízena nejlepším praktikám pro zobrazení velkého množství kategorií (žánrů).



Tento projekt potvrzuje schopnost komplexního zpracování dat od importu a čištění v Power Query až po finální vizualizaci. Vytvořený dashboard poskytuje přehledný a interaktivní pohled na světovou hudební scénu roku 2025. Kombinace technické správnosti modelu a moderního designu zajišťuje, že výsledný report je nejen funkčním analytickým nástrojem, ale i vizuálně konzistentním výstupem splňujícím standardy moderní datové analytiky.
