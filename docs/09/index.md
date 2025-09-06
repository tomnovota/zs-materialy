# 💻 Informatika - 9. ročník

## 📋 Obsah kapitol

- [🖥️ Představení počítače](#představení-počítače)
- [💾 Kódování informace](#kódování-informace)
- [🧰 Operační systém](#operacni-system)
- [🌐 Síť a Internet](#sit)
- [🔧 Řešení technických problémů](#řešení-technických-problémů)
- [🔒 Bezpečnost](#bezpečnost)
- [👤 Digitální identita](#digitální-identita)

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

#### 🎯 Hlavní komponenty

| Komponent         | Funkce             | Příklady                |
| ----------------- | ------------------ | ----------------------- |
| 🧠 **CPU**         | Procesor - výpočty | Intel i5, AMD Ryzen     |
| 💾 **RAM**         | Operační paměť     | 8GB, 16GB DDR4          |
| 💿 **Disk**        | Úložiště dat       | SSD 256GB, HDD 1TB      |
| 🎮 **GPU**         | Grafická karta     | NVIDIA GTX, AMD Radeon  |
| 🔌 **Motherboard** | Základní deska     | Propojuje všechny části |

#### 🛠️ Ostatní důležité části

```
🖥️ POČÍTAČ
├── 🧊 Chladič
├── 🔊 Zvuková karta
├── 🌐 Síťová karta (WiFi + Ethernet)
├── ⚡ PSU (napájecí zdroj)
└── 🏠 Case (skříň)
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

#### 🔑 Uživatelské účty a práva

> **Administrátor vs. Standardní uživatel**

| Typ účtu       | Oprávnění                   | Rizika   |
| -------------- | --------------------------- | -------- |
| 👑 **Admin**    | Instalace SW, změny systému | ⚠️ Vysoká |
| 👤 **Standard** | Běžná práce, omezené změny  | ✅ Nízká  |

---
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


## 🌐 Síť {#sit}

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

#### 🏢 Datová centra
- 💽 **Spojení disků** - navýšení kapacity
- ⚡ **Clustering** - zvýšení výkonu

#### ☁️ Cloudové služby

- Aplikace a soubory nejsou uloženy přímo na našem zařízení.
- Využíváme vzdálené servery připojené k internetu.
- Přístup k datům je možný odkudkoli, kde je internet.
- Typické příklady:
    - **Microsoft 365** – online kancelářské aplikace
    - **Netflix** – sledování filmů a seriálů
    - **Spotify** – poslech hudby

**Výhody:**
- 📍 Dostupnost odkudkoli (stačí internet)
- 🤝 Snadné sdílení souborů
- 👥 Jednoduchá spolupráce s ostatními
- 💸 Úspora prostředků (není nutný výkonný počítač)

**Nevýhody:**
- 🌐 Závislost na internetovém připojení
- 🔒 Potenciální ztráta kontroly nad daty
- 🏢 Závislost na poskytovateli služby

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

#### 📡 Typy připojení domácnosti

| Typ            | Rychlost    | Výhody                     | Nevýhody         |
| -------------- | ----------- | -------------------------- | ---------------- |
| 🌟 **Optika**   | až 10 Gbps  | **Velmi rychlá**, stabilní | **Dražší**       |
| 📺 **Koaxiál**  | až 1 Gbps   | Dostupná                   | Sdílená kapacita |
| 🔗 **Ethernet** | až 1 Gbps   | **Levná**                  | Pomalejší        |
| 📡 **Bezdrát**  | až 500 Mbps | Flexibilní                 | **Nestabilní**   |

### 🔧 OSI Model

- při komunikaci přes internet se kromě samotných dat posílají ještě další informace důležité k doručení zprávy
- existuje několik úrovní, které tyto informace organizují.

> **Každá vrstva přidává své informace** (enkapsulace)

```
📦 DATA PACKET
┌─────────────────────┐
│ 7️⃣ Application     │ ← HTTP/HTTPS
│ 6️⃣ Presentation    │ ← Šifrování  
│ 5️⃣ Session         │ ← Relace
│ 4️⃣ Transport       │ ← TCP/UDP
│ 3️⃣ Network         │ ← IP adresy
│ 2️⃣ Data Link       │ ← MAC adresy
│ 1️⃣ Physical        │ ← Kabel/WiFi
└─────────────────────┘
```

> **Tip:** Je důležité si uvědomit, že se spolu s obsahem, který posíláme po internetu posílají i další informace, které může zneužít kdokoli, kdo je při cestě odchytí.

#### 🎯 Klíčové protokoly

| Vrstva            | Protokol      | Účel                               | Zařízení   |
| ----------------- | ------------- | ---------------------------------- | ---------- |
| 🌐 **Síťová**      | **IPv4/IPv6** | Identifikace zařízení              | **Router** |
| 🔗 **Linková**     | Ethernet      | Komunikace sousedů, **MAC adresa** | **Switch** |
| 📡 **Fyzická**     | **WiFi/LAN**  | Přenos bitů                        | AP         |
| 🚚 **Transportní** | TCP/UDP       | Spolehlivost vs. rychlost          | Server     |

##### 🔄 TCP vs UDP

| TCP                 | UDP           |
| ------------------- | ------------- |
| ✅ Spolehlivý přenos | ⚡ Bez garance |
| 🐌 Pomalejší         | 🚀 Rychlejší   |
| 📧 Email, web        | 🎮 Hry, video  |

---

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

## 🔧 Řešení technických problémů {#řešení-technických-problémů}

### 🛠️ Bezpečný servis zařízení

#### 🔧 Hardware opravy

| Problém      | Řešení                         | Na co si dát pozor                        |
| ------------ | ------------------------------ | ----------------------------------------- |
| 🐌 Pomalý PC  | ➕ RAM, 🔄 SSD                   | Kompatibilita s naším hardwarem           |
| 🔥 Přehřívání | 🧹 Čištění od prachu, 🧊 chladič | Být opatrný (křehké součástky, elektřina) |
| 📡 Slabá WiFi | 🔄 Vyměnit starý router         | Nový router je nutné nastavit             |

#### 💻 Software opravy

```
🔄 ÚDRŽBA PC
├── 🆙 Aktualizace OS
├── 🛡️ Antivirus scan
├── 🗑️ Vyčištění disku
├── 🔄 Defragmentace
└── 💾 Záloha dat
```

### 🚨 Typické problémy a řešení

#### 🐌 Pomalý výkon
```
DIAGNÓZA:
1. 📊 Task Manager - high CPU/RAM?
2. 🗑️ Disk space < 10%?
3. 🦠 Malware scan
4. 🔄 Restart required?

ŘEŠENÍ:
- 🗑️ Smaž nepotřebné soubory
- ❌ Zavři nevyužité aplikace  
- 🔄 Restartuj systém
- ➕ Upgrade hardware
```

#### ❄️ Zamrznutý program
```
POSTUP:
1. ⏰ Počkej 30 sekund
2. 🔄 Ctrl+Alt+Del
3. ❌ Task Manager → End task
4. 🔄 Restart PC (krajní řešení)
```

#### 🌐 Problémy s internetem
```
DIAGNOSTIKA:
1. 💡 Router LED kontrola
2. 🔗 Kabel kontrola  
3. 📡 WiFi signál síla
4. 🌐 Ping test

ŘEŠENÍ:
- 🔄 Restart router (30s off)
- 🔗 Zkus kabel místo WiFi
- 📞 Kontakt ISP
```

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

## 👤 Digitální identita {#digitální-identita}

### 👣 Digitální stopa

> **Veškerá naše činnost na internetu se shromažďuje a ukládá.**

#### 📊 Co se o tobě sbírá?

| Typ dat           | Příklady          | Využití                |
| ----------------- | ----------------- | ---------------------- |
| 📍 **Poloha**      | GPS, WiFi sítě    | Mapy, reklamy          |
| 🔍 **Vyhledávání** | Google, YouTube   | Personalizace          |
| 🛒 **Nákupy**      | E-shopy, aplikace | Doporučení             |
| 👥 **Sociální**    | Likes, komentáře  | Doporučovací algoritmy |

#### 🍪 Cookies

```
🍪 COOKIE = malý soubor s informacemi
┌─────────────────────────┐
│ 🆔 ID uživatele        │
│ 🕐 Čas návštěvy        │  
│ 🛒 Obsah košíku        │
│ ⚙️ Nastavení jazyka    │
└─────────────────────────┘
```

### ⚠️ Rizika digitální identity

#### 🚫 Nesmazatelnost

> **Jednou na internetu, navždy na internetu**

```
❌ SMAZAL JSI POST
      ↓
🤖 Už ho má bot
💾 Archivní služby  
📸 Screenshots
🔄 Sdílení
```

#### 😱 Kyberšikana

**Formy:**
- 💬 Nenávistné komentáře
- 📸 Sdílení privátních fotek
- 👥 Vyloučení ze skupin
- 🎭 Fake profily

**Jak se bránit:**
- 🚫 Blokuj útočníky
- 📸 Dokumentuj důkazy
- 👨‍👩‍👧‍👦 Řekni dospělým
- 💪 Nehraj jejich hru

### 📱 Sociální sítě - bezpečnost

#### ✅ Bezpečné používání

| Činnost         | ✅ Bezpečné    | ❌ Rizikové      |
| --------------- | ------------- | --------------- |
| 📸 **Fotky**     | Veřejná místa | Domov, škola    |
| 📍 **Poloha**    | Vypnuto       | Stálé sdílení   |
| 👤 **Přátelé**   | Známí lidé    | Cizí profily    |
| 💬 **Informace** | Obecné        | Adresa, telefon |

#### 🎯 Doporučovací algoritmy a filter bubbles

```
SOCIÁLNÍ SÍŤ ALGORITMUS:
👁️ Sleduje co klikáš
    ↓
🧠 Učí se tvoje zájmy  
    ↓
📊 Ukazuje podobný obsah
    ↓
🔄 Vytváří "bublinu"
```

> **💡 Tip:** Občas hledej různorodý obsah, abys neuváznul v bublině!

---

## 🤖 Umělá inteligence {#umelá-inteligence}

### 🧠 Co je umělá inteligence?

> **Umělá inteligence (AI)** = programy, které dokážou řešit úlohy stejně dobře nebo lépe než člověk

#### 🔧 Oblasti využití AI

| Oblast              | Příklady použití                | Výhody             |
| ------------------- | ------------------------------- | ------------------ |
| 🏥 **Zdravotnictví** | Diagnostika, analýza snímků     | Rychlost, přesnost |
| 🚗 **Doprava**       | Autonomní vozidla, GPS navigace | Bezpečnost         |
| 🛒 **E-commerce**    | Doporučení produktů             | Personalizace      |
| 🎮 **Zábava**        | Herní AI, doporučení filmů      | Lepší zážitek      |
| 🔍 **Vyhledávání**   | Google Search, Siri, Alexa      | Pohodlí            |

#### ⚖️ Etické otázky AI

**✅ Pozitiva:**
- 🚀 Zvyšuje produktivitu
- 🩺 Pomáhá v medicíně
- ♿ Zpřístupňuje technologie

**⚠️ Rizika:**
- 💼 Ztráta pracovních míst
- 🕵️ Narušení soukromí
- ⚖️ Zaujatost algoritmů
- 🤖 Ztráta lidské kontroly

---

## 📚 Strojové učení {#strojové-učení}

### 🧠 Princip strojového učení

> **Strojové učení** = algoritmy, které se zlepšují na základě zkušeností (dat)

```
📊 PROCES UČENÍ:
📈 Data ──► 🧠 Učící algoritmus ──► 🎯 Natrénovaný model ──► 📊 Predikce na novém příkladu
```

#### 🎓 Typy učení

| Typ učení           | Popis                         | Příklady             |
| ------------------- | ----------------------------- | -------------------- |
| 👨‍🏫 **Supervised**    | S učitelem (vzorové odpovědi) | Rozpoznávání obrázků |
| 🔍 **Unsupervised**  | Bez učitele (hledání vzorců)  | Shlukování zákazníků |
| 🎮 **Reinforcement** | Učení odměnami/tresty         | Herní AI, robotika   |

#### 🛠️ Praktické aplikace

**🎯 Rozpoznávání vzorců:**
- 📧 Spam filter v emailu
- 🗣️ Rozpoznávání řeči (Siri, Google Assistant)
- 👁️ Rozpoznávání tváří na fotkách

**📊 Predikce:**
- 🌤️ Předpověď počasí
- 📈 Ceny akcií
- 🛒 Doporučení produktů

**🔧 Automatizace:**
- 🚗 Autonomní řízení
- 🏭 Průmyslová robotika
- 📝 Automatický překlad

---

## 🤖 Robotika a drony {#robotika-drony}

### 🤖 Co je robot?

> **Robot** = programovatelný stroj, který dokáže vykonávat úkoly autonomně nebo na příkaz

#### 🏗️ Složení robota

```
🤖 ROBOT
├── 🧠 Řídící jednotka (procesor)
├── 👁️ Senzory (kamery, mikrofony)
├── 🦾 Akční členy (motory, ramena)
├── 🔋 Napájení (baterie)
└── 📡 Komunikace (WiFi, Bluetooth)
```

#### 🎯 Typy robotů

| Typ robota         | Prostředí    | Příklady použití       |
| ------------------ | ------------ | ---------------------- |
| 🏭 **Průmyslové**   | Továrny      | Svařování, montáž      |
| 🏠 **Domácí**       | Domov        | Vysávání, sekání trávy |
| 🏥 **Zdravotnické** | Nemocnice    | Operace, rehabilitace  |
| 🚗 **Mobilní**      | Venku/uvnitř | Doprava, průzkum       |
| 🤝 **Sociální**     | S lidmi      | Asistence, vzdělávání  |

### 🚁 Drony (UAV)

> **Dron** = bezpilotní létající prostředek řízený na dálku nebo autonomně

#### 📱 Typy dronů

| Typ drona        | Velikost | Použití              |
| ---------------- | -------- | -------------------- |
| 📷 **Spotřební**  | Malé     | Fotografie, zábava   |
| 🚁 **Komerční**   | Střední  | Filming, monitoring  |
| 🏭 **Průmyslové** | Velké    | Doprava, zemědělství |
| ⚔️ **Vojenské**   | Různé    | Průzkum, obrana      |

#### 🎯 Využití dronů

**📸 Kreativní:**
- 🎬 Filmování z výšky
- 📷 Letecká fotografie
- 🏃‍♂️ Sportovní záběry

**🏢 Komerční:**
- 📦 Doručování balíků
- 🌾 Monitoring plodin
- 🔍 Kontrola infrastruktury

**🚨 Bezpečnostní:**
- 🔍 Pátrání a záchrana
- 🔥 Hasičský průzkum
- 👮‍♂️ Policejní dohled

---

## 👁️ Zpracování obrazu a počítačové vidění {#zpracovani-obrazu}

### 📷 Co je počítačové vidění?

> **Počítačové vidění** = schopnost počítače "vidět" a rozumět obsahu obrázků a videí

#### 🔍 Základní úlohy

```
🖼️ OBRÁZEK ──► 🧠 AI ──► 📊 ANALÝZA
                    │
                    ├── 🏷️ Klasifikace (co je na obrázku?)
                    ├── 📍 Detekce (kde jsou objekty?)  
                    ├── 🎯 Segmentace (hranice objektů)
                    └── 👁️ Rozpoznávání (kdo je to?)
```

#### 🛠️ Praktické aplikace

| Oblast           | Aplikace             | Příklady           |
| ---------------- | -------------------- | ------------------ |
| 📱 **Smartphony** | Rozpoznávání tváří   | Odemykání telefonu |
| 🏥 **Medicína**   | Analýza rentgenů     | Diagnostika chorob |
| 🚗 **Doprava**    | Rozpoznávání značek  | Autonomní vozidla  |
| 🛒 **Retail**     | Automatické pokladny | Amazon Go          |
| 🏭 **Průmysl**    | Kontrola kvality     | Vadné výrobky      |
| 👮‍♂️ **Bezpečnost** | Kamerové systémy     | Rozpoznávání lidí  |

#### 🖼️ Zpracování obrazu - kroky

**1️⃣ Načtení obrázku:**
- 📊 Převod na číselnou matici (pixely)
- 🌈 RGB hodnoty pro každý bod

**2️⃣ Preprocessing:**
- 📐 Změna velikosti
- 🔆 Úprava jasu/kontrastu  
- 🔄 Rotace, ořez

**3️⃣ Feature extraction:**
- 📏 Detekce hran a tvarů
- 🎨 Analýza textur a barev
- 📊 Matematické deskriptory

**4️⃣ Analýza:**
- 🤖 Strojové učení
- 🧠 Neurální sítě
- 📊 Klasifikační algoritmy

---

## 🔊 Zvukové zpracování {#zvukové-zpracování}

### 🎵 Digitální zvuk

> **Digitální zvuk** = zvukové vlny převedené na číselné hodnoty

#### 📊 Vlastnosti digitálního zvuku

```
🎵 ZVUKOVÁ VLNA ──► 📊 DIGITALIZACE
                      │
                      ├── 📏 Vzorkovací frekvence (Hz)
                      ├── 🎚️ Bitová hloubka (bit) 
                      └── 🔊 Počet kanálů (mono/stereo)
```

| Parametr             | Hodnoty    | Kvalita         |
| -------------------- | ---------- | --------------- |
| 📏 **Vzorkování**     | 44.1 kHz   | CD kvalita      |
| 🎚️ **Bitová hloubka** | 16 bit     | Standardní      |
| 🔊 **Kanály**         | 2 (stereo) | Prostorový zvuk |

#### 🛠️ Aplikace zpracování zvuku

**🎙️ Rozpoznávání řeči:**
- 📱 Siri, Google Assistant, Alexa
- 📝 Automatické titulkování
- 🌐 Překladače v reálném čase

**🎵 Hudební aplikace:**
- 🎸 Shazam (rozpoznávání skladeb)
- 🎧 Spotify doporučení
- 🎹 Automatické ladění nástrojů

**🔊 Audio efekty:**
- 🎚️ Potlačení šumu
- 🔁 Echo a reverb
- 🎛️ Equalizér

**🩺 Zdravotnictví:**
- ❤️ Analýza srdečních ozve
- 🫁 Diagnostika dýchání
- 👂 Audiometry

#### 🎯 Technologie

| Technologie | Účel             | Příklady             |
| ----------- | ---------------- | -------------------- |
| 🤖 **ASR**   | Speech-to-Text   | Diktování, titulky   |
| 🗣️ **TTS**   | Text-to-Speech   | Čtečky, navigace     |
| 🎵 **MIR**   | Analýza hudby    | Doporučovací systémy |
| 🔊 **DSP**   | Digitální filtry | Hi-Fi systémy        |

---

## 🥽 Virtuální a rozšířená realita {#virtualni-realita}

### 🌐 Typy realit

#### 🥽 VR (Virtual Reality)

> **Virtuální realita** = kompletně umělé 3D prostředí

```
🥽 VR HEADSET
├── 📺 Displeje pro oči
├── 🎧 Prostorový zvuk
├── 📍 Sledování pohybu
└── 🎮 Ovladače
```

**Využití:**
- 🎮 **Gaming** - immerzivní hry
- 🎓 **Vzdělávání** - virtuální exkurze
- 💼 **Trénink** - simulace nebezpečných situací
- 🏥 **Terapie** - léčba fobií

#### 📱 AR (Augmented Reality)

> **Rozšířená realita** = digitální prvky přidané do reálného světa

**Typy AR:**
- 📱 **Mobilní AR** - přes kameru telefonu
- 🥽 **Smart brýle** - průhledný displej
- 🎯 **Projekce** - promítání do prostoru

**Příklady:**
- 📸 **Instagram filtry** - digitální masky
- 🗺️ **Pokémon GO** - virtuální objekty v reálném světě
- 🛋️ **IKEA Place** - nábytek ve tvém pokoji
- 🚗 **GPS navigace** - šipky na silnici

#### 🔄 MR (Mixed Reality)

> **Smíšená realita** = interakce mezi reálnými a virtuálními objekty

### 🛠️ Technologie a hardware

| Zařízení          | Typ | Příklady           | Cena        |
| ----------------- | --- | ------------------ | ----------- |
| 🥽 **VR headsety** | VR  | Meta Quest, PS VR  | 10-50k Kč   |
| 👓 **AR brýle**    | AR  | Microsoft HoloLens | 100k+ Kč    |
| 📱 **Mobily**      | AR  | iPhone, Android    | Máš už doma |

#### 🎯 Budoucnost XR

**Trendy:**
- 👓 **Lehčí brýle** - jako běžné brýle
- 🧠 **Lepší sledování** - pohyb očí, výraz tváře  
- 🤲 **Hmatová zpětná vazba** - pocit doteku
- ☁️ **Cloud rendering** - výpočty na serveru

---

## 🌐 Internet věcí {#internet-věcí}

### 🔗 Co je IoT?

> **Internet věcí (IoT)** = běžné předměty připojené k internetu a vzájemně komunikující

```
🏠 CHYTRÉ ZAŘÍZENÍ ──► 📡 Internet ──► ☁️ Cloud ──► 📱 Aplikace
```

#### 🏠 Smart Home (Chytrá domácnost)

| Zařízení             | Funkce                 | Výhody             |
| -------------------- | ---------------------- | ------------------ |
| 💡 **Chytré žárovky** | Ovládání přes telefon  | Úspora energie     |
| 🌡️ **Termostat**      | Automatická regulace   | Pohodlí, úspory    |
| 🔒 **Zámky**          | Odemykání mobilem      | Bezpečnost         |
| 📹 **Kamery**         | Monitoring domova      | Dohled na dálku    |
| 🔊 **Reproduktory**   | Hlasové ovládání       | Hands-free control |
| 🧼 **Pračka**         | Notifikace o dokončení | Pohodlí            |

#### 🏥 Zdravotní IoT

```
👤 UŽIVATEL
├── ⌚ Smartwatch (tepová frekvence)
├── 📱 Fitness tracker (kroky)  
├── 🩺 Glukometr (cukr v krvi)
└── 💊 Smart pilulky (dávkování)
     ↓
📊 Zdravotní aplikace
```

#### 🏭 Průmyslové IoT (IIoT)

**Využití v průmyslu:**
- 📊 **Monitoring** - stav strojů v reálném čase
- 🔧 **Prediktivní údržba** - předpověď poruch
- ⚡ **Optimalizace** - úspora energie
- 📈 **Analytika** - zlepšení procesů

#### 🚗 Dopravní IoT

| Aplikace               | Popis                      | Přínosy             |
| ---------------------- | -------------------------- | ------------------- |
| 🚦 **Smart semafory**   | Adaptivní řízení provozu   | Plynulejší doprava  |
| 🅿️ **Chytré parkování** | Detekce volných míst       | Úspora času         |
| 🚌 **Veřejná doprava**  | Tracking autobusů/tramvají | Lepší informovanost |
| 🛣️ **Silniční senzory** | Monitoring dopravy         | Bezpečnost          |

### ⚖️ Výhody a rizika IoT

#### ✅ Výhody
- 🏠 **Pohodlí** - automatizace domácnosti
- ⚡ **Efektivita** - úspora energie a času
- 📊 **Data** - lepší rozhodování na základě dat
- 🔧 **Údržba** - predikce poruch

#### ⚠️ Rizika
- 🔒 **Bezpečnost** - hackování chytrých zařízení
- 🕵️ **Soukromí** - sledování chování
- 🌐 **Závislost** - na internetovém připojení
- 🔋 **Spotřeba** - baterie a energie

#### 🛡️ Bezpečnostní opatření

```
🔐 ZABEZPEČENÍ IoT:
├── 🔑 Silná hesla
├── 🔄 Pravidelné aktualizace
├── 🌐 Zabezpečená WiFi síť
├── 🚫 Vypnutí nepotřebných funkcí
└── 🔍 Monitoring síťového provozu
```

> **💡 Tip:** Před koupí IoT zařízení si zjisti, jak výrobce řeší bezpečnost a aktualizace!

---

*📅 Vytvořeno pro 9. ročník ZŠ | 🔄 Aktualizováno 2025*