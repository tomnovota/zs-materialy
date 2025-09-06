# 💻 Informatika - 8. ročník

## 📋 Obsah kapitol

- [🖥️ Představení počítače](#představení-počítače)
- [💾 Kódování informace](#kódování-informace)
- [🧰 Operační systém](#operacni-system)
- [📊 Práce s daty](#práce-s-daty)
- [📊 MS Excel](#ms-excel)

---

## 🖥️ Představení počítače {#představení-počítače}

### 📖 Základní pojmy

> **Hardware** = fyzické části počítače (to, co můžeme "chytnout do ruky")

### 💾 Co znamená digitální zařízení

Digitální zařízení pracuje s informacemi ve formě **čísel** (0 a 1):

- 📸 Fotografie = mřížka s čísly reprezentující barvy
- 🎵 Hudba = sekvence čísel reprezentující zvukové vlny
- 📝 Text = čísla podle kódovací tabulky

---

### 📱 Příklady digitálních zařízení

| Typ zařízení     | Popis            | Použití              |
| ---------------- | ---------------- | -------------------- |
| 🖥️ **Desktop**    | Stolní počítač   | Práce, škola, hry    |
| 💻 **Laptop**     | Přenosný počítač | Práce na cestách     |
| 📱 **Tablet**     | Dotykový počítač | Čtení, zábava        |
| 📞 **Smartphone** | Chytrý telefon   | Komunikace, aplikace |
| ⌚ **Smartwatch** | Chytré hodinky   | Zdraví, notifikace   |

---

### 🔧 Složení počítače

Každý počítač se skládá z několik klíčových **komponent**:

```
🖥️ POČÍTAČ
├── 🧠 CPU (Procesor) - "výpočetní jednotka"
├── 💾 RAM (Paměť) - "krátkodobá paměť pro procesor"  
└── 💿 HDD/SSD (Disk) - "dlouhodobé úložiště dat"
```

### 🔌 Periferie

Periferie jsou zařízení, která **připojujeme k počítači**:

#### 📤 Vstupní zařízení (zadáváme informace)
- ⌨️ **Klávesnice** - psaní textu
- 🖱️ **Myš** - ovládání kurzoru  
- 📷 **Kamera** - snímání obrazu
- 🎤 **Mikrofon** - nahrávání zvuku
- 🖨️ **Skener** - digitalizace papírů

#### 📥 Výstupní zařízení (dostáváme informace)
- 🖥️ **Monitor** - zobrazení obrazu
- 🔊 **Reproduktory** - přehrávání zvuku
- 🎧 **Sluchátka** - soukromý zvuk
- 🖨️ **Tiskárna** - tisk na papír

---

### 🎯 Účel počítačů

| Oblast             | Příklady použití                    |
| ------------------ | ----------------------------------- |
| 📁 **Ukládání dat** | Fotky z dovolené, školní známky     |
| 🔬 **Řešení úkolů** | Předpověď počasí, vědecké výpočty   |
| ⏰ **Úspora času**  | Vyhledávání informací, automatizace |
| 🤝 **Komunikace**   | Videohovory, zasílání zpráv         |
| 🎨 **Zábava**       | Filmy, hry, hudba                   |

---

### ⚠️ Bezpečnost při práci s počítačem

#### ✅ ANO:
- 🧽 Pravidelně čisti od prachu a bakterií
- 🍿 Jez až po ukončení práce
- 💧 Dávej pozor na nápoje

#### ❌ NE:
- ⚡ **NIKDY** nesahej na elektrické komponenty
- 🍕 Nejez přímo u počítače
- ☔ Nevylévej tekutiny na elektroniku

> **⚠️ Varování:** Voda a elektřina si nerozumějí!

---

## 💾 Kódování informace {#kódování-informace}

### 🔢 Digitální vs. Analogové

> **Klíčový princip:** Všechny "informace" jsou v počítači zakódovány do **bitů** (0 a 1)

| Typ             | Charakteristika         | Příklad            |
| --------------- | ----------------------- | ------------------ |
| 📻 **Analogové** | Plynulé hodnoty         | Klasické rádio     |
| 💻 **Digitální** | Diskrétní hodnoty (0,1) | Počítačové soubory |

### 📁 Datové typy

> **Datový typ** = způsob, jakým počítač interpretuje bity

#### 🎯 Hlavní kategorie:

| Typ dat        | Formáty              | Popis                  | Použití              |
| -------------- | -------------------- | ---------------------- | -------------------- |
| 🖼️ **Obrázek**  | JPG, PNG, GIF        | Digitální fotografie   | Fotky, grafika       |
| 📝 **Text**     | UTF-8, UNICODE       | Kódované znaky         | Dokumenty, zprávy    |
| 🔢 **Čísla**    | Přímý, doplňkový kód | Matematické hodnoty    | Výpočty              |
| 🎵 **Zvuk**     | MP4, WAV             | Audio data             | Hudba, nahrávky      |
| 🎨 **Barvy**    | RGB                  | Barevné hodnoty        | Displeje, tisk       |
| 📋 **Aplikace** | DOCX, XLSX           | Specializované formáty | Kancelářské programy |
| ⚙️ **Program**  | EXE                  | Spustitelný kód        | Software             |

#### 🌈 RGB Barevný model

```
🎨 RGB BARVA
├── 🔴 R (Red): 0-255
├── 🟢 G (Green): 0-255  
└── 🔵 B (Blue): 0-255

Příklady:
• Červená: (255, 0, 0)
• Bílá: (255, 255, 255)
• Černá: (0, 0, 0)
```

### 🗜️ Komprese dat

#### 📊 Typy komprese:

| Typ               | Ztráta kvality | Příklady | Kdy použít         |
| ----------------- | -------------- | -------- | ------------------ |
| **🔄 Bezztrátová** | ❌ Žádná        | ZIP, RAR | Důležité dokumenty |
| **⚡ Ztrátová**    | ✅ Částečná     | JPG, MP3 | Multimédia         |

---

## 🧰 Operační systém {#operacni-system}

**Software** = aplikace/programy, které na počítači používáme.

### 🖥️ Co je operační systém
Operační systém je program, který řídí celý počítač:
- 🧩 Říká hardwaru, co má dělat
- 🔗 Propojuje komponenty mezi sebou (např. převádí pohyb myši na pohyb kurzoru)
- 🪟 Poskytuje uživatelské rozhraní, přes které počítač ovládáme

#### 📚 Příklady
- 📱 Mobily: iOS, Android
- 💻 Počítače: Windows, macOS, Linux

### 🧩 Prvky uživatelského rozhraní

#### 👤 Uživatelský účet
- Každý uživatel má svůj účet, pod kterým počítač používá.
- Přístup k účtu je chráněn přihlášením:
    - 📝 Uživatelské jméno
    - 🔑 Heslo

#### 🖼️ Plocha
- První místo, kam se po přihlášení dostaneme.
- Často používané soubory a složky (zástupci) na dosah.

#### 🪟 Nabídka (Start)
- Přehled všech nainstalovaných aplikací a přístup do Nastavení.
- Akce napájení:
    - ⏻ Vypnout počítač
    - 🔁 Restartovat (vypnout a hned znovu zapnout)
    - 🌙 Režim spánku (sníží spotřebu, ale úplně nevypne)
    - 🔒 Zamknout (odhlásí z účtu a zobrazí přihlašovací obrazovku)

#### 🧰 Hlavní panel
- Zobrazuje právě spuštěné aplikace (rychlé přepínání mezi nimi).
- Ukazuje stav počítače:
    - ⌨️ Jazyk klávesnice
    - 🌐 Připojení k internetu
    - 🔊 Hlasitost
    - 🔌 Napájení / 🔋 Stav baterie
    - 🕒 Čas a datum

#### 🗂️ Průzkumník souborů
- Náhled do systému souborů uložených na disku (úložišti).
- Soubory patří do **složek** ("obálky"), složky tvoří stromovou strukturu:
    - Disk má kořenovou složku
    - Složky mohou obsahovat další složky

##### 📄 Typy souborů
- Každý soubor má **jméno** a **příponu** (určuje typ souboru).

1) Uchovávající data/informace
     - 🖼️ Obrázky: .JPG, .PNG, .PDF, .GIF
     - 📝 Text: .TXT
     - 🔊 Zvuk: .MP4
     - 📦 Pro konkrétní aplikace: .DOCX, .PTX, .XLSX

2) Spustitelné (programy, aplikace)
     - 🧪 .EXE

##### 🏷️ Metadata (informace o souboru)
- Datum vytvoření
- Datum změny
- Vlastník

##### 🔧 Základní operace se soubory
1) Složky
     - ➕ Vytvořit složku
     - 🗑️ Smazat složku (pozor: smaže se i celý její obsah)
     - 🚚 Přesunout složku (zachová se obsah)

2) Soubory
     - ➕ Vytvořit soubor
     - 🗑️ Smazat soubor
     - 🚚 Přesunout soubor
     - 📋 Kopírovat a vložit do jiné složky

### 🧱 Aplikace
- Operační systém poskytuje prostředí pro další programy (aplikace), které na počítači běží.

#### 🕹️ Používání aplikací
- Aplikaci musíme mít nejdříve nainstalovanou.
- Spuštění např. kliknutím na zástupce na ploše.
- Otevře se nové okno, ve kterém aplikaci používáme.
- Každou aplikaci lze zavřít (vypne se).
- Na počítači může běžet více aplikací zároveň (multitasking).
- Vybereme, které okno chceme mít zrovna na obrazovce; ostatní jsou minimalizované.

#### 🧰 Základní aplikace
- 🌐 Webový prohlížeč (browser) – zobrazení webových stránek
- 🗂️ Průzkumník souborů
- ⚙️ Nastavení
    - Obrázek na ploše
    - Jas
    - Hlasitost zvuku
- 📝 Poznámkový blok (notepad)
- 🎨 Malování

---

## 🌐 Síť

### 🎯 Co je síť?

**Síť** = propojení více zařízení za účelem **výměny informací**

### 🔗 Účely sítí

#### 👥 Komunikace mezi uživateli (client-client)
- 💬 Poslat zprávu kamarádovi
- 📧 Poslat email učitelovi

#### 📂 Sdílený přístup k datům
- 📁 OneDrive složka pro skupinový projekt
- 📸 Google Photos s fotkami ze školního výletu

#### 🖥️ Přístup ke službám (client-server)
- 🎓 Bakaláři (školní systém)
- 🌤️ Předpověď počasí
- 🎬 YouTube videa

### 🌍 Příklady sítí

| Typ sítě        | Dosah             | Příklady              |
| --------------- | ----------------- | --------------------- |
| 🌐 **Internet**  | Celý svět         | Web, email            |
| 📶 **Bluetooth** | Krátká vzdálenost | Sluchátka, myš        |
| 📱 **Sharing**   | Mezi zařízeními   | AirDrop, Wi-Fi Direct |

---

## 🌐 Internet

### 🔗 Základní připojení

```
📱 ZAŘÍZENÍ ──► 📡 ROUTER ──► 🌐 INTERNET
```

**Možnosti připojení:**
- 📶 **WiFi** - bezdrátové
- 🔗 **LAN** - kabelové

### 🌐 Webové stránky

**URL struktura:**
```
https://zshovorcovicka.cz/fotogalerie/skolni-akce/
├── https:// (protokol)
├── zshovorcovicka.cz (doména)
└── /fotogalerie/skolni-akce/ (cesta)
```

---

## 📊 Práce s daty {#práce-s-daty}

### 📈 Co jsou data?

**Data** = strukturovaně sesbírané a uložené **informace**

### 📋 Typy datasetů

| Formát        | Popis                 | Příklad           |
| ------------- | --------------------- | ----------------- |
| 📊 **Tabulky** | Řádky a sloupce       | Excel spreadsheet |
| 📈 **Grafy**   | Vizuální reprezentace | Sloupcový graf    |
| 📄 **Textové** | Nestrukturovaný text  | Kniha, článek     |
| 🖼️ **Obrázky** | Vizuální data         | Fotografie        |
| 🎵 **Audio**   | Zvukové nahrávky      | Rozhovor          |

### 🔍 Sběr dat

#### 📝 Metody sběru:

1. **👁️ Pozorování**

   - Měření teploty ve třídě
   - Počítání aut na silnici

2. **📋 Dotazníky**

   - Online formulář
   - Telefonní rozhovor

3. **📱 Elektronická zařízení**

   - Senzory, GPS
   - Aplikace na telefonu

### 🔍 Vyhledávání dat

> **⚠️ Pozor:** Vždy ověř důvěryhodnost zdrojů a jednat v souladu s licencí!

#### ✅ Důvěryhodné zdroje:

| Zdroj           | Typ                 | Příklad             |
| --------------- | ------------------- | ------------------- |
| 🏛️ **Eurostat**  | Evropské statistiky | Ekonomické údaje EU |
| 📊 **ČSÚ**       | České statistiky    | Demografické údaje  |
| 🏢 **Instituce** | Oficiální data      | Ministerstva, úřady |
| 🌐 **Open Data** | Otevřená data       | Veřejné databáze    |

### 💾 Ukládání dat

#### 🗄️ Databáze formáty:

#### 📊 Tabulkový formát (CSV)
```
jmeno,vek,trida,prumer
Anna,13,8.A,1.5
Tomáš,14,8.B,2.1
Marie,13,8.A,1.8
```

#### 📋 Dokumentová databáze (JSON)
```json
{
  "student": {
    "jmeno": "Anna",
    "vek": 13,
    "trida": "8.A",
    "znamky": [1, 2, 1, 2, 1]
  }
}
```

#### 📊 Datové typy sloupců:

| Typ                     | Popis   | Příklad       |
| ----------------------- | ------- | ------------- |
| 🔢 **Číslo (celé)**      | Integer | 42, -15, 0    |
| 🔢 **Číslo (desetinné)** | Float   | 3.14, -2.5    |
| 📝 **Text**              | String  | "Ahoj světe"  |
| 🎯 **Kategorie**         | Enum    | "Muž", "Žena" |
| 🎨 **Barva**             | RGB/Hex | #FF0000       |


#### ☁️ Cloudové úložiště

```
☁️ CLOUD STORAGE
├── 📁 OneDrive (Microsoft)
├── 📁 Google Drive
├── 📁 iCloud (Apple)
└── 📁 Dropbox

VÝHODY:
✅ Dostupné z internetu
✅ Automatické zálohy
✅ Sdílení s ostatními
✅ Spolehlivější než lokální disk
```

### ⚠️ Problémy v datech

> **Před analýzou je třeba data vyčistit!**

| Problém              | Příklad            | Řešení            |
| -------------------- | ------------------ | ----------------- |
| 🕳️ **Chybějící**      | Prázdné buňky      | Doplnit/odstranit |
| 🤥 **Falešná**        | Věk 150 let        | Ověřit zdroj      |
| ❌ **Chybné**         | "Pondělí" v čísle  | Opravit formát    |
| 🔄 **Nekonzistentní** | "Praha" vs "PRAHA" | Sjednotit         |

### 📈 Vyhodnocení dat

#### 📊 Statistické charakteristiky:

| Charakteristika | Význam             | Vzorec           | Příklad pro data: '5, 10, 15' |
| --------------- | ------------------ | ---------------- | ----------------------------- |
| 📏 **Rozsah**    | Rozpětí hodnot     | Max - Min        | 15 - 5 = 10                   |
| ➗ **Průměr**    | Typická hodnota    | Součet ÷ Počet   | (5+10+15) ÷ 3 = 10            |
| 📊 **Medián**    | Prostřední hodnota | Střed seřazených | 5, **10**, 15                 |
| 📏 **Rozptyl**   | Variabilita        | -                | Jak moc se hodnoty liší       |

#### 📈 Typy grafů:

📊 Sloupcový graf

🥧 Koláčový graf

📈 Histogram

📉 Spojnicový graf

### 🧠 Závěry z dat

> **Hypotéza** = náš odhad, který chceme daty ověřit

**Proces analýzy:**
```
1. 💭 HYPOTÉZA: "Žáci více čtou v zimě"
       ↓
2. 📊 SBĚR DAT: Výpůjčky z knihovny  
       ↓
3. 📈 ANALÝZA: Porovnání měsíců
       ↓
4. ✅ ZÁVĚR: Hypotéza potvrzena/vyvrácena
```

#### 🚫 Časté chyby v interpretaci:
- Zaměňování korelace za kauzalitu
- Ignorování jiných faktorů
- Malý vzorek dat
- Subjektivní výběr dat

### 🤖 Zpracování dat

> **Strojové učení** = počítače se z dat naučí vzory

**Příklady:**
- 📧 Rozpoznání spamu v emailech
- 🎵 Doporučení hudby na Spotify
- 🛒 Návrhy produktů v eshopu

---

## 📊 MS Excel {#ms-excel}

### 1️⃣ Ruční vkládání obsahu
#### 🎨 Formátování textu:

| Funkce         | Účel               |
| -------------- | ------------------ |
| **Ohraničení** | Rám kolem buněk    |
| **Vybarvení**  | Zvýraznění pozadí  |
| **Zarovnání**  | Střed/vlevo/vpravo |
| **Sloučení**   | Spojí více buněk   |
| **Zalamování** | Text na více řádků |

#### 🔢 Formátování čísel:

```
FORMÁTY ČÍSEL:
┌────────────┬──────────────────┐
│ Obecný     │ 1234.56          │
│ Číslo      │ 1 234,56         │
│ Měna       │ 1 234,56 Kč      │
│ Procento   │ 56%              │
│ Datum      │ 24.8.2025        │
│ Čas        │ 14:30:00         │
└────────────┴──────────────────┘
```

> Tip: Lze nastavit počet zobrazovaných desetinných míst.

#### 🔧 Užitečné funkce:

**📐 Rozšířit + Vyplnit:**
```
A1: Pondělí
A2: [vyplní automaticky] Úterý
A3: [vyplní automaticky] Středa
```

**🎨 Kopírovat formát:**
```
1. Označit buňku se správným formátem
2. Ctrl+Shift+C (zkopíruj formát)
3. Označit cílové buňky
4. Ctrl+V (vlož formát)
```

### 2️⃣ Načtení dat ze souboru

```
📁 IMPORT DAT:
Data → Z textu/CSV → Vybrat soubor → Import
```

**Podporované formáty:**
- 📊 CSV (hodnoty oddělené čárkami)
- 📋 TXT (obyčejný text)
- 🗂️ XML (strukturovaná data)

### 3️⃣ Řazení dat

```
📊 ŘAZENÍ:
1. Označit data včetně záhlaví
2. Data → Řadit
3. Vybrat sloupec pro řazení
4. Vzestupně (A→Z) nebo Sestupně (Z→A)
```

### 4️⃣ Filtrování dat

```
🔍 AUTOFILTR:
1. Označit data
2. Data → Filtr  
3. Kliknout na šipku v záhlaví sloupce
4. Zrušit označení nežádoucích hodnot
```

**Příklad filtru:**
```
PŘED FILTREM:        PO FILTRU (pouze 8.A):
┌─────────┬─────┐    ┌─────────┬─────┐
│ Jméno   │Třída│    │ Jméno   │Třída│
├─────────┼─────┤    ├─────────┼─────┤
│ Anna    │ 8.A │    │ Anna    │ 8.A │
│ Tomáš   │ 8.B │    │ Marie   │ 8.A │
│ Marie   │ 8.A │    └─────────┴─────┘
│ Pavel   │ 8.C │
└─────────┴─────┘
```

### 5️⃣ Podmíněné formátování

```
🎨 BAREVNÉ ZVÝRAZNĚNÍ:
Domů → Podmíněné formátování → Zvýraznit buňky

Pravidla:
• Větší než... → 🟢 zelená
• Menší než... → 🔴 červená
• Mezi hodnotami... → 🟡 žlutá
```

**Praktický příklad:**
```
ZNÁMKY S PODMÍNĚNÝM FORMÁTOVÁNÍM:
┌─────────┬─────────────┐
│ Jméno   │ Průměr      │
├─────────┼─────────────┤
│ Anna    │ 1.2 🟢      
│ Tomáš   │ 3.8 🔴      
│ Marie   │ 2.1 🟡       
└─────────┴─────────────┘
```

### 6️⃣ Pravidla a omezení

```
🛡️ OVĚŘENÍ DAT:
Data → Ověření dat

Typy omezení:
• Celé číslo mezi 1 a 5
• Datum mezi 1.1.2025 a 31.12.2025
• Seznam hodnot: "Ano", "Ne", "Možná"
• Vlastní vzorec
```

### 7️⃣ Kontingenční tabulky

> **Kontingenční tabulka** = souhrn četností kategorií

```
📊 PŘÍKLAD KONTINGENČNÍ TABULKY:

ZDROJOVÁ DATA:           KONTINGENČNÍ TABULKA:
┌──────┬──────┬────┐    ┌─────────────┬─────┬─────┬──────┐
│Jméno │Třída │Zn. │    │Třída/Známka │  1  │  2  │Celkem│
├──────┼──────┼────┤    ├─────────────┼─────┼─────┼──────┤
│Anna  │ 8.A  │ 1  │    │     8.A     │  2  │  1  │  3   │
│Tomáš │ 8.A  │ 2  │    │     8.B     │  0  │  2  │  2   │
│Marie │ 8.A  │ 1  │    │    Celkem   │  2  │  3  │  5   │
│Pavel │ 8.B  │ 2  │    └─────────────┴─────┴─────┴──────┘
│Jana  │ 8.B  │ 2  │
└──────┴──────┴────┘
```

### 8️⃣ Funkce v Excelu

#### 🧮 Základní matematické funkce:

```excel
=SUM(A1:A10)           // Součet hodnot v rozsahu A1 až A10
=AVERAGE(B1:B5)        // Průměr hodnot v rozsahu B1 až B5
=COUNT(C1:C20)         // Počet číselných hodnot v rozsahu
=MAX(D1:D15)           // Největší hodnota v rozsahu
=MIN(E1:E8)            // Nejmenší hodnota v rozsahu
```

#### 🎯 Podmínková funkce IF:

```excel
=IF(A1>5; "Vysoký"; "Nízký")
//     ↑       ↑        ↑
//  podmínka hodnota1 hodnota2

Příklad:
A1 = 8 → výsledek "Vysoký"
A1 = 3 → výsledek "Nízký"
```

**Komplexní příklad:**
```excel
=IF(B1>=1; IF(B1<=2;"Výborný"; IF(B1<=3;"Dobrý";"Slabý")); "Chyba")

B1 = 1.5 → "Výborný"
B1 = 2.8 → "Dobrý"  
B1 = 4.2 → "Slabý"
```

#### 📊 Pokročilé funkce:

```excel
=COUNTIF(A1:A100;">5")      // Počet buněk s hodnotou > 5
=SUMIF(B1:B50;"Výborný";C1:C50) // Součet jen pro "Výborný"
=VLOOKUP(D1;A1:B100;2;0)    // Vyhledání hodnoty v tabulce
```

### 9️⃣ Vizualizace dat

#### 📈 Typy grafů v Excelu:

| Graf             | Kdy použít            | Příklad              |
| ---------------- | --------------------- | -------------------- |
| 📊 **Sloupcový**  | Porovnání kategorií   | Počet žáků v třídách |
| 🥧 **Koláčový**   | Části celku           | Oblíbené předměty    |
| 📈 **Spojnicový** | Vývoj v čase          | Teplota během roku   |
| 📊 **Histogram**  | Rozložení hodnot      | Rozložení známek     |
| 📉 **Plošný**     | Vývoj více řad        | Srovnání tříd v čase |
| 📊 **Bodový**     | Vztah dvou proměnných | Výška vs váha        |

#### 🎨 Vytvoření grafu:

```
📊 POSTUP VYTVOŘENÍ:
1. Označit data včetně popisků
2. Vložit → Grafy → Vybrat typ
3. Upravit název, osy, barvy
4. Umístit na list nebo nový list
```

---

*📅 Vytvořeno pro 8. ročník ZŠ | 🔄 Aktualizováno 2025*