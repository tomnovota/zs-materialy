# 💻 Informatika - 6. ročník

## 📋 Obsah kapitol

- [🖥️ Představení počítače](#představení-počítače)
- [💾 Kódování informace](#kódování-informace)
- [🧰 Operační systém](#operacni-system)
- [📊 Práce s daty](#práce-s-daty)
- [🏢 Informační systémy](#informační-systémy)
- [🔒 Bezpečnost](#bezpečnost)
- [🧮 Algoritmizace](#algoritmizace)

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

## 🏢 Informační systémy {#informační-systémy}

### 🎯 Co je informační systém?

**Informační systém** = digitální řešení pro **správu dat organizace**

> **💡 Analogie:** IS je jako digitální sekretářka, která si pamatuje vše o organizaci, rychle najde potřebné informace a jednoduše provede námi požadované operace.

### 🏛️ Příklady podle institucí:

| Instituce       | Informační systém     | Účel                       |
| --------------- | --------------------- | -------------------------- |
| 🎓 **Škola**     | Bakaláři, Edupage     | Známky, rozvrh, komunikace |
| 🏢 **Firma**     | Účetní systém         | Finance, faktury, mzdy     |
| 🏥 **Nemocnice** | Zdravotní IS          | Pacienti, diagnózy, léčba  |
| 🏛️ **Stát**      | eDalnice, eGovernment | Služby pro občany          |

### 🎯 Účel IS:

#### ✅ Výhody digitalizace:

| Oblast         | Papír ❌       | Digitál ✅          |
| -------------- | ------------- | ------------------ |
| **Bezpečnost** | Zničitelné    | Záloha v cloudu    |
| **Rychlost**   | Ruční hledání | Okamžité vyhledání |
| **Sdílení**    | Kopírování    | Automatické        |
| **Úložiště**   | Fyzické místo | Virtuální          |

### 💻 Technologie IS:

#### 🖥️ Desktopové aplikace
- ✅ **Výhody:** Bez internetu, rychlé
- ❌ **Nevýhody:** Pouze jeden PC

#### 🌐 Webové aplikace  
- ✅ **Výhody:** Přístup odkudkoli
- ❌ **Nevýhody:** Potřeba internetu

### 👥 Uživatelé a práva

> **Každý uživatel má jiná oprávnění**

| Role          | Oprávnění    | Příklad        |
| ------------- | ------------ | -------------- |
| 👨‍🎓 **Student** | Čtení známek | Vidí jen své   |
| 👩‍🏫 **Učitel**  | Zápis známek | Jen svým žákům |
| 👨‍💼 **Ředitel** | Vše          | Celá škola     |

---

## 🔒 Bezpečnost {#bezpečnost}

### 🛡️ Soukromí na internetu

#### 🔐 Šifrování
- **Šifrování** = převod zprávy do tajného kódu
- **Klíč** = potřebujeme ho k dešifrování
- **Dešifrování** = převod zpět do původní zprávy

#### 🏛️ Caesarova šifra

> **Princip:** Posun každého písmena o stejný počet míst

```
📝 POSTUP:
1. Vyber posun (např. +3)
2. A→D, B→E, C→F...
3. AHOJ → DKRM

🔓 DEŠIFROVÁNÍ:
Posun opačným směrem (-3)
DKRM → AHOJ
```

**🎯 Praktická ukázka:**
```
Původní: TAJNE HESLO
Posun +5: YFQSJ MJXQT
```

> **💡 Analogie:** Šifrování je jako psaní tajnou abecedou, kterou znáš jen ty a tvůj přítel.

#### 👤 Uživatelský účet na službách

- Na většině služeb vystupujeme pod **uživatelským účtem**.
    - Zabraňuje přístupu k našim datům neoprávněným osobám:
        - 📨 Pouze my si můžeme číst vlastní emailovou schránku.
        - 🧑‍🏫 Pouze učitel může zapisovat známky žákům.
    - Každý uživatel má oddělené prostory:
        - 🛒 Košík v eshopu
        - 🎓 Známky v Bakaláři
        - 📸 Fotky v Google Photos

#### 👤 Autentikace (ověření identity)

Přihlášení k **uživatelskému účtu** se skládá z:
- 📝 **Uživatelské jméno** (identifikace)
- 🔑 **Heslo** (ověření)

##### 🔐 Bezpečná hesla

> **⚠️ ZLATÉ PRAVIDLO:** Heslo NIKDY nikomu nesděluj!

**✅ Bezpečné heslo obsahuje:**
- 📏 Více než 12 znaků
- 🔤 Malá i velká písmena (a-z, A-Z)
- 🔢 Čísla (0-9)
- 🎯 Speciální znaky (.,+-*/)
- 🚫 Nemá jasný význam

**🛡️ Dvoufázové ověřování:**

K heslu navíc potvrdíme naší identitu dalším způsobem.

- 📱 Potvrzení na telefonu
- 📧 Potvrzení na emailu
- 🔢 SMS kód
- 👆 Otisk prstu

---

### 💾 Zálohování

> **💡 Pravidlo:** Důležité soubory měj uložené na **dvou místech**!

**Možnosti zálohování:**
- ☁️ **Cloud** (OneDrive, Google Drive)
- 💽 **Externí disk**
- 📱 **Jiné zařízení**

---

### 🛡️ Ochrana před útoky

#### ⚔️ Druhy útoků:
- 🔓 Prolomení hesla
- 💣 Smazání souborů
- 🤖 Spouštění nežádoucích programů

#### 🛡️ Druhy obrany:
- 💾 **Zálohování**
- 🛡️ **Antivirus**
- 🔥 **Firewall**

---

### 📚 Informační gramotnost

#### ✅ Důvěryhodné zdroje:
- 📰 Velké tiskové agentury
- 🏛️ Neziskové organizace
- 📄 Uvedený původní zdroj

#### ❌ Nedůvěryhodné zdroje:
- 🚫 Dezinformační weby
- 👑 Média totalitářských režimů
### 🧠 Kritické přemýšlení na internetu

- Zamýšlej se nad obsahem, který čteš na internetu.
- Ověřuj fakta, porovnávej různé pohledy.
- Zvažuj, kdo a proč danou informaci zveřejnil.
- Pozor na stránky bez uvedení autora.

#### 🫧 Informační bubliny (filter bubbles)
- Doporučovací algoritmy na sociálních sítích nás mohou udržovat v informační bublině.
- Vidíme hlavně obsah, se kterým souhlasíme, ostatní názory se nám nemusí zobrazit.

> **💡 Tip:** Vždy si ověř informace z více zdrojů!

---

### 📱 Rizika digitálních služeb

#### 🕒 Závislost
- Rizika spojená s nadměrným používáním digitálních služeb.

- **Binge-watching:** Dlouhé sledování pořadů (Netflix, Twitch, YouTube).
- **Scrolling:** Nepřetržité prohlížení obsahu (TikTok, Instagram, Facebook).

---

### 🔒 Soukromí

- Citlivé informace/soubory ukládej do zabezpečených míst.
- Dávej si pozor, co zveřejňuješ veřejně.
    - Riziko vydírání.
    - Riziko stalkingu.

---

### 💬 Komunikace s cizími lidmi

- Buď opatrný při komunikaci s cizími lidmi.
    - Někteří nám mohou chtít ublížit (úchylové, zloději).

---

### 📝 Autorství na internetu

- Na některá díla na internetu se může vztahovat autorský zákon.
    - Omezení použití, jinak porušujeme zákon.
    - Použití určují licence.

---

## 🧮 Algoritmizace {#algoritmizace}

### 🎯 Co je problém?

Každý **problém** má:
- 📥 **Vstup** (co máme)
- 📋 **Zadání** (co chceme vyřešit)  
- 📤 **Řešení** (co chceme získat)

### 🔄 Co je algoritmus?

**Algoritmus** = postup, jak vyřešit problém

> 💡 Algoritmus je jako recept na vaření – přesný návod krok za krokem.

### 📝 Struktura algoritmu:

1. 📥 Definice vstupů (co potřebujeme)
2. ⚙️ Postup (jak to udělat)
3. 📤 Výstup (co dostaneme)

---

### 🧭 Symboly, se kterými budeme pracovat
- ▶️ START – začátek
- ➡️ KROK – udělej akci
- ❓ KDYŽ/JINAK – podmínka
- 🔁 OPAKUJ – opakování (cyklus)
- 🛑 STOP – konec

---

### 🧪 Příklady algoritmů

#### 1) 🫖 Připrav čaj (kombinace podmínky a čekání)
Vstupy: konvice, voda, hrnek, čajový sáček
Výstup: hrnek čaje
```
▶️ START
➡️ Naplň konvici vodou
➡️ Zapni konvici
❓ KDYŽ voda vře → POKRAČUJ, JINAK čekej
➡️ Dej sáček do hrnku
➡️ Nalij horkou vodu do hrnku
🔁 OPAKUJ 3 minuty: čekej
➡️ Vyjmi sáček
🛑 STOP
```

#### 2) 👣 Počítej 1 až 10 (cyklus)
Vstup: číslo 1 jako začátek, číslo 10 jako konec
Výstup: vypsaná čísla 1…10
```
▶️ START
➡️ i = 1
🔁 DOKUD i ≤ 10:
    ➡️ vypiš i
    ➡️ i = i + 1
🛑 STOP
```

#### 3) 🚦 Bezpečný přechod přes silnici (podmínka)
Vstupy: semafor (barva), přechod
Výstup: bezpečně přejdu
```
▶️ START
❓ KDYŽ je na semaforu ZELENÁ → jdi
JINAK → čekej
🛑 STOP
```

#### 4) 🔢 Najdi největší ze tří čísel A, B, C (porovnávání)
Vstup: tři čísla A, B, C
Výstup: největší číslo
```
▶️ START
➡️ max = A
❓ KDYŽ B > max → max = B
❓ KDYŽ C > max → max = C
➡️ vypiš max
🛑 STOP
```

#### 📊 Třídění pole (Sort)

```
📋 UNSORTED: [5, 2, 8, 1, 9]

🔄 PROCES:
Pass 1: [2, 5, 1, 8, 9]
Pass 2: [1, 2, 5, 8, 9]

✅ SORTED: [1, 2, 5, 8, 9]
```

#### 🔍 Binární vyhledávání

```
🎯 HLEDÁME: 7 v [1,3,5,7,9,11]

1. Střed: 5 (< 7) → hledej vpravo
2. Nový střed: 9 (> 7) → hledej vlevo  
3. Zůstal jen 7 → NALEZENO!
```

> **⚡ Výhoda:** Mnohem rychlejší než postupné hledání!


---

### 🧩 Úlohy

#### A) Samostatné úlohy – napiš algoritmus (vstup, postup, výstup)
1) 🥪 Sendvič s máslem a šunkou  
   - Přidej podmínku: KDYŽ nůž není čistý, umyj ho.
2) 🎒 Příprava aktovky na zítřek  
   - Použij cyklus: Pro KAŽDÝ předmět z rozvrhu přidej sešit a učebnici.
3) 🧼 Čištění zubů  
   - Napiš přesné kroky, aby to zvládl “robot” (žádné vynechané kroky).
4) 🧹 Úklid stolu po svačině  
   - Přidej podmínku: KDYŽ je drobek → setři ho, JINAK pokračuj.

#### B) Úlohy s podprogramem (opakované použití části postupu)
- Vytvoř podprogram: UMÝJ_RUCE
  ```
  PODPROGRAM UMÝJ_RUCE:
    ➡️ Otoč kohoutek
    ➡️ Namoč ruce
    ➡️ Naneste mýdlo
    ➡️ Tři ruce 20 s
    ➡️ Opláchni
    ➡️ Osuš
  ```

- Použij ho v těchto algoritmech:
  1) 🧁 Příprava svačiny (nejdřív UMÝJ_RUCE, pak připrav jídlo)
  2) 🎨 Malování temperami (UMÝJ_RUCE před a po malování)

- Vytvoř podprogram: PŘIDEJ_PŘEDMĚT_DO_AKTOVKY(předmět)  
  Použij ho pro všechny předměty v rozvrhu.

> Tip: Piš kroky konkrétně (co přesně, jak, jak dlouho). “Udělej to” nestačí.

---

## ⚙️ Programování

### 🏗️ Vývoj programu

#### 1️⃣ **Návrh řešení**
```
📝 PLÁNOVÁNÍ:
• Co má program dělat?
• Jaké vstupy budu zpracovávat?
• Jaké výstupy chci?
• Jak rozdělit program na menší části?
```

#### 3️⃣ **Testování**

> **Testovací případy** = různé situace, které program musí zvládnout

**📝 Typy testů:**
- ✅ **Běžné případy** - normální použití
- ⚠️ **Krajní případy** - extrémní hodnoty
- 🚫 **Chybné vstupy** - neplatná data

> **💡 Tip:** Vždy otestuj i neobvyklé situace!

#### 4️⃣ **Debugging (ladění chyb)**

**🐛 Časté chyby:**
- ❌ **Syntax Error** - překlepy, chybné odsazení
- 🔄 **Logic Error** - program funguje, ale dělá něco jiného
- 💥 **Runtime Error** - program spadne během běhu


---

*📅 Vytvořeno pro 6. ročník ZŠ | 🔄 Aktualizováno 2025*