# Studijní materiál předmětu Informatika pro základní školy

## 1. Počítač

Počítač je přístroj, na kterém můžeme dělat spoustu aktivit a pomáhá nám v životě a ve společnosti.

### Základní komponenty počítače:
- **Procesor** - mozek počítače, provádí výpočty a zpracovává instrukce
- **Operační paměť (RAM)** - hlavní paměť pro rychlý přístup k datům
- **Úložiště** - místo pro trvalé uložení dat
  - HDD (mechanický disk)
  - SSD (solid-state disk)
  - Cloud (cloudové úložiště)
  - Flash (USB flash disky, SD karty)

### Periferie:
**Vstupní zařízení:**
- Klávesnice
- Myš
- Mikrofon
- Kamera

**Výstupní zařízení:**
- Tiskárna
- Reproduktory
- Sluchátka

## 2. Informace a data

Všechny "informace" (z toho slova informatika) jsou zakódovány do **bitů** (binární soustava).

### Instrukce
- **Cesta signálu:** elektřina → kondenzátor → hradla → logické obvody → procesor
- Procesor poskytuje **instrukční sadu** (možné operace mezi daty)
- **Rozdíl mezi analogovým a digitálním** zpracováním

### Data
**Datové formáty/typy souborů** - způsob, jakým interpretovat bity:

#### Obrázky:
- JPG, PNG, PDF, GIF

#### Text (kódování):
- UTF-8, UNICODE

#### Čísla (kódy):
- Doplňkový
- Aditivní  
- Přímý

#### Soubory pro konkrétní aplikace:
- DOCX, PTX, XLSX

#### Program/aplikace:
- Počítač tento soubor interpretuje jako instrukce a provádí je

## 3. Operační systém

Hlavní program, který běží na zařízení.

### Příklady operačních systémů:
- **Mobily:** iOS, Android
- **Počítače:** Windows, macOS, Linux
- **Servery:** Linux

### Funkce operačního systému:

#### Správa hardwaru:
- Koordinuje práci hardwaru
- Zprostředkovává komunikaci mezi hardwarem

#### Uživatelské rozhraní:
Poskytuje rozhraní pro uživatele, přes které lze příjemně počítač využívat:
- Uživatelský účet
- Plocha
- Průzkumník souborů (náhled do filesystému)

#### Správa aplikací:
Poskytuje prostředí pro další aplikace, které v něm můžou běžet. Ty mají přidělenou:
- **Paměť**
- **Výkon** - střídají se na procesoru (multitasking)

### Filesystem

Způsob, kterým jsou uložená data na úložišti.

#### Struktura:
- **Složky** - stromová struktura
- **Soubory**

#### Typy souborů:
- Datové formáty
- Spustitelné
- Systémové

#### Metadata:
- Datum vytvoření
- Datum změny
- Vlastník

#### Operace:
- **Move** - přesun
- **Copy** - kopírování
- **Remove** - smazání
- **Create** - vytvoření

## 4. Síť

Způsob, jak propojit více zařízení.

### Výhody síťového propojení:

#### Výkon:
- **Data centra** - spojení úložišť
- **Clustery** - spojení výpočetních jednotek

#### Komunikace mezi zařízeními:
- Sdílení dat
- Vzájemná komunikace

### Síťové technologie:

#### Bezdrátové:
- **Bluetooth** - krátké vzdálenosti
- **WiFi** - místní síť
- **Sharing** - mezi telefony se stejným OS

#### Kabelové:
- **LAN** - Local Area Network
- **USB** - připojení periferií

## 5. Internet

Nejpoužívanější technologie, přes kterou si mohou zařízení vyměňovat informace přes celý svět.

### Způsob připojení do internetu:
**Síťová karta → WiFi/LAN → Router → ISP → NAT → celosvětová síť**

### Síťové protokoly:

#### Síťová vrstva:
Jak se zařízení identifikuje v celé síti:
- **IPv4** - starší standard
- **IPv6** - novější standard
- **Router** - směrování dat

#### Linková vrstva:
Jak se zařízení identifikuje uvnitř domácí sítě:
- **Ethernet** - MAC adresa

#### Fyzická vrstva:
Veškerá informace je zakódována do binární soustavy:
- **WiFi** - bezdrátové připojení
- **LAN** - kabelové připojení
- **Optické kabely** - vysokorychlostní přenos

### Webové stránky:
- **Zobrazitelné v prohlížeči** (Google Chrome, Microsoft Edge)
- **Dostupné přes URL**
  - Zabezpečení HTTPS
  - Součásti URL (doména atd.)
- **Formát HTML**
- **JavaScript** - pozor, může se lokálně spouštět kód (může být škodlivý)

> ⚠️ **Upozornění:** Existuje spousta dalších vrstev, ve kterých se posílají citlivé/osobní informace. Je třeba na to myslet, že je může v některých případech kdokoli odchytit a zneužít.

### DarkNet:
- Decentralizovaná síť dostupná přes internet
- Často se vyskytuje nelegální aktivita

## 6. Aplikace

Vědět, na které problémy se vyplatí použít počítač.

## 7. Algoritmizace

Pomocí počítače můžeme řešit naše problémy.

### Struktura typického problému:
- **Vstupy** - co dostáváme
- **Popis/zadání** - co máme udělat
- **Výstup** - řešení problému

### Algoritmus
Postup, kterým získáme řešení problému (funkce v matematice).

#### Definice algoritmu:
- **Definice možných vstupů:**
  - Definiční obor
  - Formát

- **Definice výstupu:**
  - Obor hodnot

- **Postup:**
  - Jak pro konkrétní vstup získat požadovaný výstup
  - Máme omezené instrukce/operace, které můžeme použít

### Příklady základních algoritmů:
- **Sort** - řazení
- **Binary-search** - binární vyhledávání
- **Eratosthenovo síto** - hledání prvočísel

## 8. Programování

Způsob, kterým můžeme počítači předat instrukce.

### Programovací jazyk
Instrukce, které jsou blíže lidské řeči než instrukce počítače. Námi napsaný program se přeloží na instrukce počítače.

#### Základní prvky programovacího jazyka:
- **Proměnné** - ukládání hodnot
- **Výrazy + operátory** - výpočty
- **Podmínky** (if-else) - rozhodování
- **Cykly** (for, while) - opakování
- **Funkce** - znovupoužitelné bloky kódu

#### Nástroje:
- **Kompilátor** - překlad do strojového kódu
- **Syntax** - pravidla jazyka

### Vývoj programu:
1. **Návrh** - plánování řešení
2. **Implementace** - psaní kódu
3. **Testování** - ověření funkčnosti
## 9. Bezpečnost

### Soukromí

#### Šifrování:
- K přečtení informace potřebujeme **klíč**

#### Autentikace:
- **Hesla** - základní forma ověření
- **Dvoufázové ověřování** - vyšší bezpečnost

### Ochrana před útoky

#### Druhy útoků:
- Malware, viry, trojské koně
- Phishing
- DDoS útoky

#### Druhy obrany:
- **Zálohování** - ochrana dat
- **Antivirus** - detekce škodlivého softwaru
- **Firewall** - kontrola síťového provozu

## 10. Práce s daty

Pokud jsou informace strukturované a je jich dostatek, bavíme se o datech.

### Sběr dat

#### Databáze:
- **Tabulka** - strukturované ukládání
- **Jinak strukturovaná data** - JSON, XML atd.

### Vyhodnocení dat

#### Analýza:
- **Statistické charakteristiky** - průměr, medián, modus
- **Grafy** - vizualizace dat

#### Problémy s daty:
- **Chybějící** údaje
- **Falešná pozorování** - nesprávné hodnoty

### Zpracování dat

#### Pokročilé metody:
- **Strojové učení** - automatické učení z dat

## 11. Informační systémy

Správa dat nějaké instituce a komunikace s institucí.

### Příklady institucí:
- Škola
- Úřady
- Zaměstnavatel
- Volnočasové organizace
- Nemocnice

### Typy aplikací

#### Desktopové aplikace:
- **Výhody:** Není nutný přístup k internetu
- **Nevýhody:** Nutná kompatibilita s PC+OS

#### Webové aplikace:
- **Výhody:** Flexibilnější, multiplatformní
- **Nevýhody:** Nutný přístup k internetu

### Model skutečnosti
Informační systém reprezentuje a spravuje reálné procesy a data.
## 12. Praktické dovednosti

### Tvorba dokumentů

#### Textové dokumenty (Word):
- **Zadání** - formulace úkolů
- **Report** - zprávy a analýzy
- **Závěrečná práce** - strukturované dokumenty
- **Citování** - správné uvádění zdrojů

### Prezentace

#### Vytvoření prezentace:
- **MS PowerPoint** - tvorba slidů

#### Přednes:
- **Časové naplánování** - správné rozložení času
- **Komunikace tělem** - neverbální komunikace

### Grafická úprava
- **GIMP/Malování** - úprava obrázků

### Práce s internetem

#### Vyhledávání:
- **Google** - efektivní vyhledávání
- **Nápověda aplikací** - pomoc uvnitř programů (Word)

#### Prohlížeč (Chrome, Edge):
- **Základní nastavení** - konfigurace
- **Rozšíření** (add-ons) - dodatečná funkčnost
- **Záložky** - organizace stránek
- **Cookies** - správa dat
- **Správce hesel** (BitWarden) - bezpečné ukládání hesel

### Moderní nástroje

#### Chatboti:
- **Microsoft Copilot**
- **ChatGPT**

### Komunikační nástroje

#### Microsoft Teams:
**Kanály pro každou strukturu na škole:**
- Třídy
- Předměty
- Předmětové skupiny
- Ročníky
- Celá škola
- Vedení
- Pedagogové
- Zaměstnanci

**Funkce:**
- Odevzdávání úkolů

#### Cloudové služby:
- **OneDrive** - cloudové úložiště
- **Outlook:**
  - Organizace emailů
  - Kalendář

### Práce s operačním systémem

#### Efektivní používání:
- **Klávesové zkratky** - rychlejší práce
- **Multitasking** - práce s více aplikacemi
- **Organizace souborů** - správa dat
- **Personalizace** - přizpůsobení prostředí
## 13. Informační a digitální gramotnost

### Informační gramotnost

#### Ověřování informací:
**Rozpoznání důvěryhodnosti zdroje:**
- ✅ **Důvěryhodné zdroje:**
  - Velké tiskové agentury
  - Neziskové organizace
  - Uvedení zdrojů

- ❌ **Nedůvěryhodné zdroje:**
  - Dezinformační média
  - Média totalitářských režimů
  - Zdroje bez uvedení původu

## 14. Bezpečnost práce s technologiemi

### Fyzická bezpečnost

#### Bezpečná práce s počítačem:
- **Elektrická bezpečnost:** Nesahat na elektrické komponenty
- **Pravidelné čištění:**
  - Prach (povrch, ventilátory)
  - Bakterie
- **Prevence poškození:**
  - Nejíst při práci na PC
  - Pít v blízkosti elektroniky opatrně

### Údržba a opravy

#### Základní opravy zařízení:
- **Výměna disku:** pomalého/nefunkčního/malého
- **Upgrade RAM** - zvýšení výkonu

### Bezpečnost na internetu

#### Ochrana soukromí:
- **Citlivé informace** ukládat do zabezpečených míst
- **Pozor na veřejné sdílení** - riziko:
  - Vydírání
  - Stalking

#### Komunikace s cizími lidmi:
⚠️ **Pozor na:**
- **Sexuální predátory:**
  - Pedofilové
  - Fetišisti
- **Zloději** - podvodníci

#### Nelegální aktivity:
❌ **Vyhýbat se:**
- **Nelegálnímu prodeji:**
  - Bez licence
  - Nelegální předměty (zbraně, drogy)

## 15. IT legislativa

### Autorský zákon
- **Licence** - práva k používání
- **Duševní vlastnictví** - ochrana tvůrců
- **Citace** - správné uvádění zdrojů

### Ochrana osobních údajů
- GDPR a související předpisy
- Práva uživatelů

### Zabezpečení
- Povinnosti při správě dat
- Odpovědnost za bezpečnost
## 16. Pracovní dovednosti

### Samostatná práce

#### Schopnosti:
- **Úkol v hodině** - efektivní plnění zadání
- **Projekt** - dlouhodobější samostatná práce

### Spolupráce v týmu

#### Klíčové aspekty:
- **Týmový úkol** - společné dosažení cíle
- **Rozdělení rolí** - efektivní využití schopností
- **Průběžná komunikace/koordinace** - udržení synchronizace
- **Řešení konfliktů** - konstruktivní přístup k problémům

## 17. Projektová práce

### Typy projektů:
- **Zjistit, jak něco funguje** - výzkum a analýza
- **Vytvořit něco** - kreativní tvorba
- **Vyřešit problém** - praktické řešení

> 💡 **Důležité:** Není důležité, jak jsme se k výsledku dostali, ale abychom mu rozuměli a ověřili jeho správnost!

### Fáze projektu:

#### 1. Plánování
**Rozmyslet téma projektu:**
- Kontext
- Cíle

#### 2. Návrh
**Podrobný návrh projektu:**
- Kroky k jeho splnění
- Použité technologie
- Časový plán

#### 3. Implementace
**Práce na projektu** - realizace navržených kroků

#### 4. Finalizace
**Finální verze** - dokončení a testování

#### 5. Dokumentace
**Závěrečné zpracování:**
- Dokumentace projektu
- Report
- Závěrečná prezentace

#### 6. Reflexe
**Ohodnotit svou práci** - sebehodnocení a poučení

---

## Závěr

Tento studijní materiál poskytuje ucelený přehled základních témat informatiky pro žáky základních škol. Materiál je strukturován tak, aby postupně budoval znalosti od základních konceptů po pokročilejší témata a praktické dovednosti.

### Pro další studium doporučujeme:
- Praktické procvičování jednotlivých témat
- Zapojení do projektové práce
- Sledování aktuálních trendů v IT
- Dodržování bezpečnostních zásad

---

*Materiál bude průběžně aktualizován a rozšiřován podle potřeb výuky.*