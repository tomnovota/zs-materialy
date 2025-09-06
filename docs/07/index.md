# 💻 Informatika - 7. ročník

## 📋 Obsah kapitol

- [🖥️ Představení počítače](#představení-počítače)
- [🧰 Operační systém](#operacni-system)
- [🌐 Síť a Internet](#síť)
- [🏢 Informační systémy](#informační-systémy)
- [🎨 Tvorba digitálního obsahu](#tvorba-digitálního-obsahu)
- [🧮 Algoritmizace](#algoritmizace)
- [⚙️ Programování](#programování)

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

## 💾 Kódování informace

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

## 🌐 Síť {#síť}

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

### 🌍 Internet

#### 🔗 Připojení k internetu

```
📡 CESTA NA INTERNET
📱 Zařízení ──► 📡 Router ──► 🏢 ISP ──► 🌐 Internet
```

**Možnosti připojení k routeru:**
- 📶 **WiFi** (bezdrátové)
- 🔗 **LAN kabel** (drátové)

#### 🌐 Webové stránky

> **Webová stránka** = dokument dostupný přes internet pomocí **URL adresy**

- v prohlížeči (typicky nahoře) je adresní řádek, kam se zadávají právě URL adresy
- po zadání URL adresy jsme prohlížečem přesměrováni na danou webovou stránku.

#### 🔗 Struktura URL adresy

```
https://zshovorcovicka.cz/fotogalerie/skolni-akce/
│     │                │            │
│     └── doména        │            └── cesta
└── protokol            └── cesta
```

**Části URL:**
- 🔒 **Protokol:** `http://` nebo `https://` (zabezpečené)
- 🏠 **Doména:** `zshovorcovicka.cz`
  - Druhá úroveň: `zshovorcovicka`
  - První úroveň: `cz`
- 📁 **Cesta:** `/fotogalerie/skolni-akce/`

#### 🏗️ Obsah webové stránky

- 🏗️ **HTML** - struktura stránky
- 🎨 **CSS** - vzhled stránky  
- ⚙️ **JavaScript** - interaktivní prvky

**HTML - základní struktura:**
```html
<!DOCTYPE html>
<html>
<head>
    <title>Moje školní stránka</title>
</head>
<body>
    <h1>Vítejte na naší stránce!</h1>
    <p>Toto je můj první web.</p>
</body>
</html>
```

**JavaScript - interaktivita:**
```javascript
function zobrazPozdrav() {
    alert("Ahoj z JavaScriptu!");
}
```

> **⚠️ Pozor:** JavaScript se spouští na tvém počítači a může být nebezpečný!

#### 🕸️ DarkNet

**DarkNet** = decentralizovaná síť webových stránek přístupná přes speciální software

⚠️ **Varování:** Často používaný pro nelegální aktivity!

## 🔒 Bezpečnost

### 🛡️ Soukromí na internetu

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

## 🏢 Informační systémy {#informační-systémy}

### 🎯 Co je informační systém?

**Informační systém (IS)** = digitální řešení, které pomáhá **institucím spravovat data**

> **💡 Analogie:** IS je jako digitální sekretářka, která si pamatuje vše o organizaci, rychle najde potřebné informace a jednoduše provede námi požadované operace.

### 🏛️ Příklady podle institucí:

| Instituce       | Informační systém     | Účel                       |
| --------------- | --------------------- | -------------------------- |
| 🎓 **Škola**     | Bakaláři, Edupage     | Známky, rozvrh, komunikace |
| 🏢 **Firma**     | Účetní systém         | Finance, faktury, mzdy     |
| 🏥 **Nemocnice** | Zdravotní IS          | Pacienti, diagnózy, léčba  |
| 🏛️ **Stát**      | eDalnice, eGovernment | Služby pro občany          |

### 🎯 Účel informačních systémů

#### ✅ Výhody digitalizace:

| Oblast           | 📄 Papírová forma       | 💻 Digitální forma   |
| ---------------- | ---------------------- | ------------------- |
| **🔒 Bezpečnost** | Zničitelné ohněm/vodou | Záloha v cloudu     |
| **⚡ Rychlost**   | Ruční vyhledávání      | Okamžité hledání    |
| **📤 Sdílení**    | Fyzické kopírování     | Automatické sdílení |
| **📊 Analýza**    | Ruční počítání         | Automatické grafy   |
| **💰 Úspora**     | Papír, tisk, místo     | Virtuální úložiště  |

### 💻 Technologie informačních systémů

#### 🖥️ Desktopové aplikace

```
💻 DESKTOP APP
├── ✅ Výhody:
│   ├── Rychlá odezva
│   ├── Funguje bez internetu
│   └── Plná kontrola dat
└── ❌ Nevýhody:
    ├── Nutná instalace na každý PC
    └── Těžší sdílení dat
```

#### 🌐 Webové aplikace

```
🌐 WEB APP
├── ✅ Výhody:
│   ├── Přístup odkudkoli
│   ├── Automatické aktualizace
│   └── Snadné sdílení
└── ❌ Nevýhody:
    ├── Nutný internet
    └── Závislost na serveru
```

### 👥 Uživatelé a práva

> **Každý uživatel má jiná oprávnění**

| Role          | Oprávnění    | Příklad        |
| ------------- | ------------ | -------------- |
| 👨‍🎓 **Student** | Čtení známek | Vidí jen své   |
| 👩‍🏫 **Učitel**  | Zápis známek | Jen svým žákům |
| 👨‍💼 **Ředitel** | Vše          | Celá škola     |

---
### 🎯 Schémata

> **Schéma** = zjednodušený model, který pomáhá pochopit složitou realitu

#### 🗺️ Ohodnocený orientovaný graf
```
        50km
Praha ────────► Kutná Hora
  │                 │
 80km              30km
  ▼                 ▼
Brno  ◄────60km─── Jihlava
```

#### 👥 Entity-relation model
```
    ŽÁCI                PŘEDMĚTY
┌─────────────┐      ┌─────────────┐
│ jméno       │      │ název       │
│ věk         │ ──── │ obtížnost   │
│ třída       │      │ hodiny      │
└─────────────┘      └─────────────┘
        │                    │
      má známku           vyučuje
        │                    │
    ZNÁMKY  ◄────zadává──── UČITELÉ
┌─────────────┐      ┌─────────────┐
│ hodnota     │      │ jméno       │
│ datum       │      │ předmět     │
│ typ         │      │ kabinet     │
└─────────────┘      └─────────────┘
```

#### ⭕ Vennovy diagramy
```
      Žáci ve třídě (30)
    ┌─────────────────────┐
    │    Sportovci        │    Hudebníci
    │  ┌─────────────┐    │  ┌─────────────┐
    │  │      ┌──────┼────┼──┼──────┐      │
    │  │      │ Oba  │    │  │ Jen   │     │
    │  │ Jen  │ (5)  │    │  │hudba  │     │
    │  │sport │      │    │  │ (8)   │     │
    │  │ (10) │      │    │  │       │     │
    │  │      └──────┼────┼──┼──────┘      │
    │  └─────────────┘    │  └─────────────┘
    │                     │
    │  Ani sport ani hudba (7)
    └─────────────────────┘
```

---

## 🎨 Tvorba digitálního obsahu {#tvorba-digitálního-obsahu}

**📚 Citace:**
> Při použití cizího díla **VŽDY** uvedeme autora a zdroj podle licence!

### 📄 Dokumenty

#### 📝 Microsoft Word

**Využití:**
- 📋 Specifikace zadání projektu
- 📊 Závěrečná zpráva projektu
- 🎓 Školní práce a referáty

**🎨 Formátování textu:**

| Prvek          | Účel                | Příklad               |
| -------------- | ------------------- | --------------------- |
| **Nadpisy**    | Struktura dokumentu | H1, H2, H3            |
| **Zvýraznění** | Důležité informace  | **tučné**, *kurzíva*  |
| **Číslování**  | Logické pořadí      | 1., 2., 3.            |
| **Okraje**     | Vzhled stránky      | 2.5 cm ze všech stran |
| **Řádkování**  | Čitelnost           | 1.5 řádku             |

### 📊 Prezentace

#### 🎯 Microsoft PowerPoint

> **⚠️ Důležité:** Slidy jsou pouze **doprovod** pro prezentujícího!

**📈 Využití:**
- 🎪 Představení projektu
- 💼 Prezentace zkušeností
- 🎓 Školní referáty

**🎤 Klíčové dovednosti:**
- 🗣️ **Mluvit srozumitelně** - pomalé tempo, jasná výslovnost
- 👥 **Komunikace tělem** - oční kontakt, gesta
- ⏰ **Časové rozvržení** - nepřekračovat limity

**📐 Zásady dobrých slidů:**
```
✅ DOBRÉ SLIDY:
• Málo textu, více obrázků
• Velké písmo (min. 24pt)
• Kontrastní barvy
• Jednotný styl
• Jednoduchost

❌ ŠPATNÉ SLIDY:
• Příliš mnoho textu
• Malé písmo
• Křiklavé barvy
• Nepřehlednost
• Moc efektů
```

### 🎨 Grafika

#### 🖼️ Rastrová grafika
- **Malování** - Windows základní editor
- **GIMP** - profesionální editor zdarma

**Charakteristika:**
- Složena z pixelů (bodů)
- Při zvětšení ztrácí kvalitu
- Vhodná pro fotografie

#### 📐 Vektorová grafika
- **Inkscape** - profesionální editor zdarma

**Charakteristika:**
- Složena z matematických křivek
- Lze libovolně zvětšovat
- Vhodná pro loga, ikony

### 🛠️ Pomocné nástroje

#### 🔍 Webový vyhledávač
**Google efektivně:**
```
"přesná fráze"       ──► Hledá přesně tuto frázi
site:edu.cz          ──► Hledá pouze na .cz doménách
filetype:pdf         ──► Hledá pouze PDF soubory
informatika -hra     ──► Informatika, ale ne o hrách
```

#### 🤖 Chatboti (AI asistenti)

**Příklady:**
- 🤖 Microsoft Copilot
- 🤖 ChatGPT
- 🤖 Perplexity

**✅ Výhody:**
- Rychlé odpovědi na otázky
- Pomoc s formulací textu
- Vysvětlení složitých pojmů

**⚠️ Rizika:**
- Odpovědi nemusí být správné
- **VŽDY je nutné ověřit informace**
- Hrozí ztráta kritického myšlení

> **💡 Tip:** Používej AI jako pomocníka, ne jako náhradu za vlastní myšlení!

#### ☁️ Cloudové úložiště

**OneDrive výhody:**
```
☁️ CLOUD STORAGE
├── 💾 Automatické zálohy
├── 🔄 Synchronizace mezi zařízeními  
├── 👥 Sdílení s ostatními
├── 📱 Přístup z mobilu
└── 🔒 Bezpečné úložiště
```

#### 💬 Komunikační platformy

**Microsoft Teams:**
- 💬 Chat s učiteli a spolužáky
- 👥 Rozdělení do skupin
- 📁 Sdílení souborů
- 📅 Plánování úkolů

### 📜 Autorství a licence

> **Autorský zákon** = právní ochrana tvůrčích děl

**🎯 Typy licencí:**

| Licence                | Podmínky               | Příklad        |
| ---------------------- | ---------------------- | -------------- |
| **©️ Copyright**        | Jen s povolením autora | Knihy, filmy   |
| **🆓 Public Domain**    | Volně použitelné       | Staré knihy    |
| **🔓 Creative Commons** | Různé podmínky         | Wikipedie      |
| **💰 Komerční**         | Za peníze              | Adobe produkty |

### 🛡️ Ochrana osobních údajů

#### 🧠 Selský rozum
- 🚫 Nezveřejňuj cizí osobní údaje
- 📸 Nepublikuj fotky bez souhlasu
- 🔒 Chraň svá soukromá data

#### 🇪🇺 GDPR (General Data Protection Regulation)
> Evropská směrnice na ochranu osobních údajů

**Základní práva:**
- 🔍 Právo vědět, jaká data jsou o tobě sbírána
- ✏️ Právo na opravu nesprávných údajů  
- 🗑️ Právo na smazání dat ("právo být zapomenut")

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

## ⚙️ Programování {#programování}

### 🏗️ Vývoj programu

#### 1️⃣ **Návrh řešení**
```
📝 PLÁNOVÁNÍ:
• Co má program dělat?
• Jaké vstupy budu zpracovávat?
• Jaké výstupy chci?
• Jak rozdělit program na menší části?
```

#### 3️⃣ **Implementace v programovacím jazyce**

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

### 💬 Programovací jazyk

**Programovací jazyk** = způsob, jak "mluvit" s počítačem

> Počítač rozumí jen 0 a 1, programovací jazyk překládá naše instrukce do "řeči" počítače.

### 🧱 Základní prvky programu:

#### 📦 Proměnné (ukládání dat)
- `bool` - pravda/nepravda
- `int` - celá čísla  
- `double` - desetinná čísla
- `string` - text
- `pole` - seznam hodnot

#### 🔧 Operátory a výrazy
- `+, -, *, /` - matematické operace
- `=` - přiřazení hodnoty
- `==` - porovnání

#### 🔀 Podmínky (if-else)
```
KDYŽ (podmínka) POTOM
    udělej něco
JINAK  
    udělej něco jiného
```

#### 🔄 Cykly (opakování)
```
OPAKUJ 10×:
    udělej něco
```

#### 📋 Funkce (podprogramy)
- Nahrazují opakující se kód
- Dělí program na logické části

### 🧪 Experimentování v blokově-orientovaném jazyce

> Blokové programování (např. Scratch, MakeCode) umožňuje skládat program z barevných bloků jako z lega.

#### 🚀 Jak začít
1) Otevři editor bloků (online nebo ve škole).
2) Vyber si objekt (sprite) a scénu.
3) Přidej událost a pár bloků, spusť a sleduj výsledek.
4) Měň parametry a hned porovnej chování.

#### 🧱 Základní experiment
Pohyb postavy a reakce na okraj:
```
[událost] když kliknu na zelenou vlajku
opakuj stále:
  posuň se o 10 kroků
  když dotýká se okraje → odskoč
```
Zkus:
- změnit rychlost (5, 10, 20)
- přidat náhodu: změň směr o náhodně(-15, 15)
- místo “odskoč” otoč směr: nastav směr na (směr × -1)

#### 🎮 Ovládání z klávesnice
```
[událost] když je stisknuta klávesa ŠIPKA VPRAVO → změň x o 5
[událost] když je stisknuta klávesa ŠIPKA VLEVO  → změň x o -5
```
Rozšiř:
- přidej skok: při klávese SPACE → změň y o 10
- zpomalení: každé opakování → změň y o -1 (gravitace)

#### 🧮 Proměnné a parametry
Vytvoř proměnnou `rychlost` a zobraz ji na scéně:
```
[událost] při startu → nastav rychlost na 5
opakuj stále:
  posuň se o rychlost kroků
  když dotyk okraje → nastav rychlost na (rychlost × -1)
```
Experimentuj:
- posuvník pro rychlost
- tření: v každém kroku → změň rychlost o -0.1

#### 🧪 Mini–úkoly
- Náhodný chodec: postava náhodně mění směr, ale zůstává v poli.
- Honěná: dva spritéři, jeden utíká, druhý pronásleduje (směr k cíli).
- Počítadlo bodů: při dotyku mince → zvyšte skóre o 1 a mince se přesune.

#### 🔎 Testování a ladění v blocích
- Krokování: dočasně sniž rychlost/počet kroků, ať vidíš změny.
- Říkej/print: nech postavu “říkat” hodnoty proměnných.
- Izolace: vypni části skriptu a zkoušej je zvlášť.
- Hraniční případy: testuj okraje scény, nulovou rychlost, žádný vstup.

> Tip: Ukládej verze (remix). Malé změny, časté spuštění, rychlá zpětná vazba.



---

*📅 Vytvořeno pro 7. ročník ZŠ | 🔄 Aktualizováno 2025*