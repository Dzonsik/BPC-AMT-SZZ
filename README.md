# Státnicové otázky BPC-AMT
Tento repozitář a jeho funkce je založena na repozitáři s otázkami ke státní závěrečné zkoušce od oboru Informační bezpečnost na FEKT VUT. Jejich původní repozitář najdete zde: [MPC-IBE-SZZ](https://github.com/VUT-FEKT-IBE/MPC-IBE-SZZ).

Státnicové předměty pro rok 2024/25 jsou následující

- [BPC-MVE](#BPC-MVE) Měření v elektrotechnice
- [BPC-LOS](#BPC-LOS) Logické obvody a systémy
- [BPC-MIC](#BPC-MIC) Mikrokontroléry a vestavěné systémy
- [BPC-PPA](#BPC-PPA) Prostředky průmyslové automatizace
- [BPC-RR1](#BPC-RR1) Regulace a řízení 1
- [BPC-RR2](#BPC-RR2) Regulace a řízení 2
- [BPC-SNI](#BPC-SNI) Snímače
- [BPC-UIN](#BPC-UIN) Umělá inteligence
- [BPC-ZVS](#BPC-ZVS) Zpracování vícerozměrných signálů

- [ ] Pro rok 2024/2025 je potřeba zkontrolovat/doplnit/přepsat otázky a okruhy.

## Seznam předmětů a jejich otázek

### BPC-MVE

- [ ] Chyby měření (rozdělení, výpočet, chyby metody, chyby měřicích přístrojů). Nejistoty měření - typy, výpočet nejistoty A, B, kombinovaná a rozšířená nejistota. Nejistoty nepřímých měření.
- [ ] Analogově-číslicové převodníky pro měřicí techniku – rozdělení, princip základní typů AD převodníků, vlastnosti, použití. 
- [ ] Měření napětí a proudu. Změna rozsahů voltmetrů a ampérmetrů. Rušení u měřicích přístrojů.
- [ ] Měření výkonu v jednofázové a třífázové soustavě. Wattmetry – princip, typy, vlastnosti.
- [ ] Číslicové osciloskopy – princip, vlastnosti, jejich příslušenství.
- [ ] Měření frekvence, časového intervalu a fáze. Univerzální čítač – princip, vlastnosti.
- [ ] Měření pasivních el. veličin (R,L,C,Z) – metody s přímým údajem, principy mostových metod.
- [ ] Měření magnetických veličin. Snímače magnetických veličin (princip základních magnetických převodníků – měřicí cívka, Hallova sonda). Měření parametrů feromagnetik (hysterezní smyčka, ztráty) pomocí osciloskopu.

### BPC-LOS

- [ ] Logická funkce, její vyjádření pomocí tabulky, algebraického výrazu a map. Úplný součtový a součinový tvar algebraického vyjádření logické funkce. Metody a principy minimalizace logických funkcí. Úprava logické funkce pro realizaci pomocí členů NAND a NOR.
- [ ] Kombinační logické obvody: binární dekodér, multiplexor, demultiplexor, kodér, prioritní kodér, číslicový komparátor, binární sčítačka a odčítačka. Druhý doplněk. Logické obvody s třístavovým výstupem a s otevřeným kolektorem. Připojování zařízení na sběrnici.
- [ ] Přechodné děje v kombinačních logických obvodech, hazardní stavy (souběhový, dynamický a statický hazard), metody detekce a řešení statického hazardu ve dvoustupňové struktuře NAND-NAND, konsensus, řešení hazardu pomocí sekvenčních obvodů.
- [ ] Rozdíl mezi kombinačním a sekvenčním logickým obvodem. Klopné obvody: RS, D, JK, T, hladinové, hranové a master-slave, pravdivostní tabulka, pojem metastabilita v sekvenčních logických obvodech.
- [ ] Sekvenční logické obvody: posuvný registr, posuvné registry se zpětnou vazbou (kruhový čítač, Johnsonův čítač, lineární čítač - LFSR), asynchronní a synchronní čítače, popis jejich funkce pomocí jazyka HDL. Vysvětlete pojmy HDL jazyka: souběžný a sekvenční příkaz, okamžité a odložené přiřazení.
- [ ] Konečné stavové automaty: Obecný (Huffmanův) model sekvenčního logického obvodu, přechodová funkce, výstupní funkce, budicí funkce. Mealyho, Mooreho a autonomní automat. Popis konečného automatu pomocí stavového diagramu, tabulky přechodů a tabulky výstupů. Návrhová tabulka (budicí funkce KO).

### BPC-MIC

- [ ] Von Neumannovy principy, blokové schéma Von Neumannova počítače. Rozdíl mezi Von Neumannovou, harvardskou a modifikovanou harvardskou architekturou.
Procesory CISC a RISC. Rozdíl mezi obvodovým a mikroprogramovým řadičem. Řetězové zpracování instrukcí (pipelining), skokový a datový konflikt.
Jak se liší a pro jaké typy úloh je určen mikroprocesor pro všeobecné použití, mikrokontrolér, signálový procesor a signálový kontrolér (DSC), SoC (System on a Chip), ASIC.
- [ ] Rozdíl mezi izolovanými a paměťově mapovanými periferiemi. Způsoby obsluhy V/V: aktivní čekání, přerušení, DMA.
Přerušení: řadič přerušení, činnost procesoru při zahájení obsluhy přerušení a návratu z přerušení, tabulka vektorů přerušení. Asynchronní a synchronní přerušení. Maskovatelné, nemaskovatelné a pseudomaskovatelné přerušení. Vnořené přerušení. RESET, činnost procesoru po RESETu.
- [ ] Princip a vlastnosti pamětí ROM, EEPROM, FLASH. Rozdíl mezi paměťmi NOR FLASH a NAND FLASH. Princip pamětí MRAM a FeRAM.
- [ ]  Princip a vlastnosti statických pamětí RAM (SRAM) a dynamických pamětí RAM (DRAM), synchronní paměti DRAM (SDRAM).
Připojování paralelních pamětí SRAM, FLASH ke sběrnicím mikroprocesoru. Adresový dekodér.
Hierarchie paměti, paměti cache, specializované paměti cache.
- [ ] Pojem logická a fyzická adresa, ochrana paměti, memory management unit (MMU). Stránkování (princip, transformace logické adresy na fyzickou, stránkovací tabulka). Virtuální adresový prostor. Zrychlení překladu adres pomocí Translation Look-aside Buffer (TLB).

### BPC-PPA

- [ ] Úrovně řízení výroby a jejich funkce. Zařazení komponent do jednotlivých vrstev a možnosti jejich propojení. Způsoby řízení výroby (centralizované a distribuované). Toky dat (informací) v systému a jejich popis. Vlastnosti a možnosti nadřazených výrobních systémů (MES, ERP).
- [ ] Standardní rozhraní průmyslových signálů - typy, obvodové provedení, vlastnosti a použití. Logika digitálních signálů. Zpracování analogové veličiny. Standardizace a destandardizace. Senzory - popis, typy a jejich použití. Možnosti zapojení snímačů do systému.
- [ ] Průmyslové pohony (elektrické, pneumatické) - typy, vlastnosti a způsoby řízení. Zapojení průmyslových pohonů do systému.
- [ ] Řídicí členy (PLC, DCS, průmyslová PC, průmyslové regulátory, vestavné systémy, HMI aj.) – vlastnosti a použití. Typy provedení komponentů. Možnosti jejich programování (parametrizace, reprezentace veličin, struktura projektu, struktura programu, stavový automat). Postup programování technologických procesů.
- [ ] Průmyslové komunikační sítě (sběrnice a protokoly) – dělení, vlastnosti a použití. Referenční model ISO/OSI. Způsoby komunikace. Průmyslový Ethernet. Bezdrátový přenos dat v průmyslovém prostředí.
- [ ] Spolehlivost a bezpečnost průmyslových zařízení a systémů. Metody vyhodnocení spolehlivosti. Komponenty a metody zajišťující funkční bezpečnost průmyslových strojů a zařízení. Aspekty kybernetické bezpečnosti. Kybernetické útoky a metody jejich zmírnění.
- [ ] Systémy reálného času – vlastnosti a použití v průmyslové automatizaci. Pojmy determinismus, včasnost a jitter. Metody zajištění determinismu.

### BPC-RR1

- [ ] Definice ovládání, řízení a regulace (řízení bez a se zpětnou vazbou), výhody a nevýhody. Základní veličiny a přenosy. Rozdělení řízení podle různých kritérií. PID regulátory, základní složky a vlastnosti. Statická analýza zpětnovazebních obvodů. Standardní přenosy ve zpětnovazebním řízení, charakteristický polynom. Věta o počáteční a konečné hodnotě, požadavky na ustálené hodnoty. 
- [ ] Standardní struktury regulačních obvodů. Stabilita obvodů se zpětnou vazbou. Frekvenční charakteristiky v komplexní rovině, Nyquistovo kritérium stability, jeho zjednodušená verze a řešení v logaritmických souřadnicích, použití algebraických kritérií.
- [ ] Analýza dynamických vlastností zpětnovazebních obvodů. Metoda geometrického místa kořenů. Zásoba stability v amplitudě, ve fázi a v modulu. Integrální kritéria kvality regulace, praktická kritéria.
- [ ] Návrh PID regulátorů různými metodami (metoda standardních tvarů frekvenčních charakteristik, metoda optimálního modulu, metoda Zieglera-Nicholse, metoda standardních tvarů charakteristického polynomu, metoda požadovaného rozložení pólů uzavřeného obvodu).
- [ ] PSD regulátory, základní složky a vlastnosti. Aproximace vzorkovače s tvarovačem, diskretizace PID regulátoru. Rozvětvené regulační obvody. Obvod s pomocnou regulovanou veličinou, s pomocnou akční veličinou, s měřením poruchy, s modelem regulované soustavy (kompenzace dopravního zpoždění). Vícerozměrové řídicí systémy. 

### BPC-RR2

- [ ] Základní nelinearity a popis nelineárních systémů (popis statických a dynamických nelineárních systémů, vliv parazitních nelinearit na průběh regulačního děje).
- [ ] Ustálené chování nelineárních dynamických systémů (rovnovážné stavy, mezní cyklus, metoda harmonické rovnováhy, stabilita mezního cyklu).
- [ ] Stabilita nelineárních systémů (definice, metody vyšetření, věty o nestabilitě,stabilita uzavřené regulační smyčky).
- [ ] Reléová regulace (on-off regulátory, řízení v klouzavém režimu).
- [ ] Linearizace nelineárních dynamických systémů (rozvoj do Taylorovy řady, exaktní zpětnovazební linearizace).

### BPC-SNI

- [ ] Měření polohy - principy odporové, indukčnostní, kapacitní  
- [ ] Měření polohy - principy optické, magnetické, ultrazvukové 
- [ ] Měření vibrací, rychlosti, zrychlení, akcelerometry, snímače úhlové rychlosti 
- [ ] Tenzometry, snímače síly, hmotnosti, momentu a tlaku 
- [ ] Měření průtoku, základní principy objemových, rychlostních a hmotnostních průtokoměrů
- [ ] Kontaktní snímače teploty (dilatační, odporové, termoelektrické)
- [ ] Měření záření (tepelné a kvantové snímače IR záření, snímače ionizujícího záření)
- [ ] Chemické snímače

### BPC-UIN

- [ ] Umělá inteligence (UI) - definice, úzká UI, obecná UI, superinteligence, strojové učení.
- [ ] Umělé neuronové sítě - paradigmata, perceptron, algoritmus učení Backpropagation, Kohonenova samoorganizační mapa, konvoluční neuronová síť.
- [ ] Expertní systémy (ES) - definice, architektura, teoretické zdroje pro realizaci ES, tvorba a ladění báze znalostí, průběh konzultace.
- [ ] Počítačové vidění - předzpracování obrazu, segmentace obrazu, popis a klasifikace obrazu. 

### BPC-ZVS

- [ ] Diskrétní obraz, jeho vlastnosti a reprezentace (model kamery, projekce, digitalizace, metriky), binární, šedotónový a
barevný obraz - barevné formáty, souborové formáty.
- [ ] Konvoluční integrál, korelace obrazových signálů, okolí bodu, lineární a nelineární filtry (masky - detekce hran a rohů,
filtrace šumu), typy šumu.
- [ ] Jasové transformace (histogram, kumulovaný histogram - ekvalizace, jasové korekce), geometrické transformace
(aproximace, bilineární a afinní transformace, homogenní souřadnice, interpolace souřadnic, korekce zkreslení, rotace /
měřítko).
- [ ] Morfologické operace a integrální transformace (využití FT pro zpracování vícerozměrných signálů - vzorce,
vlastnosti, výhody a nevýhody, typy a tvorba filtrů, korelace a autokorelace).
