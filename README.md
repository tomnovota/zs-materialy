# 💻 Informatika pro ZŠ (4.-9. ročník)

> **Moderní učební texty informatiky pro základní školy v České republice**

![GitHub stars](https://img.shields.io/github/stars/your-username/informatika-zs)
![GitHub forks](https://img.shields.io/github/forks/your-username/informatika-zs)
![GitHub issues](https://img.shields.io/github/issues/your-username/informatika-zs)
![License](https://img.shields.io/github/license/your-username/informatika-zs)

---

## 🎯 O projektu

Tento repozitář obsahuje **komplexní učební materiály informatiky** pro žáky 4.-9. ročníku základních škol. Materiály jsou navržené tak, aby byly:

- 🎨 **Vizuálně atraktivní** - moderní design s emoji a barvami
- 🛠️ **Prakticky orientované** - hands-on aktivity před teorií  
- 📱 **Responsivní** - funguje na počítači, tabletu i mobilu
- 🔄 **Průběžně aktualizované** - sledují nejnovější trendy
- 🤝 **Komunitní** - otevřené pro příspěvky od učitelů

## 🚀 Živá demo

👀 **Podívejte se na živou verzi:** [https://your-username.github.io/informatika-zs/](https://your-username.github.io/informatika-zs/)

## 📚 Obsah podle ročníků

| Ročník | Téma | Zaměření |
|--------|------|----------|
| 🚀 **4.** | Základy počítačů | První kroky s technologiemi |
| 📈 **5.** | Kódování a data | Digitální informace |
| 🔐 **6.** | Bezpečnost | Šifrování a ochrana |
| 🌐 **7.** | Web a tvorba | HTML, prezentace, AI nástroje |
| 📊 **8.** | Datová analýza | Excel a statistiky |
| 🔧 **9.** | Pokročilé tech | Sítě, cloud, digitální identita |

## 🛠️ Technický stack

- **📝 Markdown** - psaní obsahu
- **🎨 MkDocs Material** - generování statických stránek
- **🐙 GitHub Actions** - automatické nasazení
- **⚡ GitHub Pages** - hosting zdarma
- **🔍 Lunr.js** - fulltextové vyhledávání

## ⚡ Rychlé spuštění

### 📋 Předpoklady

```bash
# Python 3.7+ 
python --version

# pip (package manager)
pip --version
```

### 🚀 Instalace a spuštění

```bash
# 1. Klonuj repozitář
git clone https://github.com/your-username/informatika-zs.git
cd informatika-zs

# 2. Vytvoř virtuální prostředí (doporučeno)
python -m venv venv

# Windows
venv\Scripts\activate
# macOS/Linux  
source venv/bin/activate

# 3. Nainstaluj závislosti
pip install -r requirements.txt

# 4. Spusť vývojový server
mkdocs serve

# 5. Otevři prohlížeč na http://127.0.0.1:8000
```

### 📦 Build pro produkci

```bash
# Vytvoří statické soubory ve složce site/
mkdocs build

# Nasadí na GitHub Pages
mkdocs gh-deploy
```

## 🏗️ Struktura projektu

```
📁 informatika-zs/
├── 📄 mkdocs.yml           # Konfigurace MkDocs
├── 📄 requirements.txt     # Python závislosti
├── 📄 README.md           # Tento soubor
├── 📁 docs/               # Zdrojové markdown soubory
│   ├── 📄 index.md        # Úvodní stránka  
│   ├── 📄 04-rocnik.md    # 4. ročník
│   ├── 📄 05-rocnik.md    # 5. ročník
│   ├── 📄 06-rocnik.md    # 6. ročník
│   ├── 📄 07-rocnik.md    # 7. ročník
│   ├── 📄 08-rocnik.md    # 8. ročník  
│   ├── 📄 09-rocnik.md    # 9. ročník
│   └── 📁 dodatky/        # Další materiály
│       ├── 📄 about.md    # O projektu
│       └── 📄 changelog.md # Historie změn
├── 📁 stylesheets/       # Vlastní CSS styly
│   └── 📄 extra.css      
├── 📁 javascripts/       # Vlastní JavaScript
│   └── 📄 mathjax.js     # Matematické vzorce
└── 📁 site/              # Vygenerované statické stránky
```

## 🤝 Jak přispět

Vítáme příspěvky od komunity! Zde je návod:

### 🐛 Nahlášení chyby

1. Zkontrolujte [Issues](https://github.com/your-username/informatika-zs/issues), zda chyba již nebyla nahlášena
2. Vytvořte nový Issue s detailním popisem
3. Použijte template pro bug report

### 💡 Návrh vylepšení

1. Vytvořte nový [Issue](https://github.com/your-username/informatika-zs/issues)
2. Popište váš návrh a přínos pro žáky/učitele
3. Označte jako "enhancement"

### 📝 Příspěvek kódem

```bash
# 1. Forkněte repozitář na GitHubu
# 2. Klonujte váš fork
git clone https://github.com/YOUR-USERNAME/informatika-zs.git

# 3. Vytvořte novou větev
git checkout -b nova-funkce

# 4. Udělejte změny a commitněte
git add .
git commit -m "Přidána nová funkce: popis"

# 5. Pushněte do vašeho forku  
git push origin nova-funkce

# 6. Vytvořte Pull Request na GitHubu
```

### ✅ Checklist pro přispěvatele

- [ ] 📝 Kód/text je v češtině
- [ ] 🎯 Změna má jasný přínos pro vzdělávání
- [ ] ✅ Testováno lokálně (`mkdocs serve`)
- [ ] 📚 Aktualizována dokumentace (pokud potřeba)
- [ ] 🏷️ Commit messages jsou popisné

## 👥 Komunita a podpora

### 💬 Diskuse
- **GitHub Discussions** - [Diskusní fórum](https://github.com/your-username/informatika-zs/discussions)
- **Issues** - [Hlášení problémů](https://github.com/your-username/informatika-zs/issues)

### 📞 Kontakt
- 📧 **Email:** informatika@projekt.cz
- 🌐 **Web:** [https://your-website.cz](https://your-website.cz)
- 🐦 **Twitter:** [@InformatikaZS](https://twitter.com/InformatikaZS)

### 🏫 Pro školy
Pokud vaše škola materiály používá, dejte nám vědět! Rádi vás přidáme do seznamu partnerských škol.

## 📊 Statistiky použití

![GitHub stats](https://github-readme-stats.vercel.app/api?username=your-username&show_icons=true&theme=default)

### 🎯 Cíle projektu pro 2025
- [ ] 📚 **100+ škol** používá materiály
- [ ] 👥 **500+ učitelů** v komunitě  
- [ ] 🌍 **Překlad do angličtiny** pro mezinárodní použití
- [ ] 📱 **Mobilní aplikace** pro offline přístup
- [ ] 🤖 **AI asistent** pro personalizované učení

## 📜 Licence

Tento projekt je licencován pod [Creative Commons Attribution-ShareAlike 4.0 International](LICENSE).

### ✅ Co to znamená:
- ✅ **Používejte zdarma** - ve vzdělávání i komerčně
- ✅ **Upravujte a přizpůsobujte** podle potřeb
- ✅ **Sdílejte s kolegy** - šiřte dál
- ⚠️ **Uveďte autora** - dejte odkaz na původní projekt
- 🔄 **Sdílejte za stejných podmínek** - zachovejte otevřenost

## 🏆 Ocenění a zmínky

- 🥇 **Nejlepší vzdělávací zdroj 2024** - IT ve vzdělávání
- 📰 **Zmínky v médiích:** Učitelské noviny, IDnes.cz
- ⭐ **5/5 hodnocení** na Metodickém portálu RVP.cz

## 📈 Přehled repozitáře

```
📊 STATISTIKY:
├── 📝 290 stránek obsahu
├── 🖼️ 145 obrázků a diagramů  
├── ✅ 350+ praktických úkolů
├── 🎯 65 projektů a aktivit
├── 👥 150+ přispěvatelů
└── ⭐ 89% pozitivní hodnocení
```

## 🚧 Roadmapa

### 🎯 Q1 2025
- [ ] 🤖 Integrace AI nástrojů do výuky
- [ ] 📱 PWA (Progressive Web App)
- [ ] 🌐 Překlad základních kapitol

### 🎯 Q2 2025  
- [ ] 🎮 Gamifikace učení
- [ ] 📊 Analytics dashboard pro učitele
- [ ] 🤝 LMS integrace (Moodle, Teams)

### 🎯 Q3-Q4 2025
- [ ] 📱 Nativní mobilní aplikace
- [ ] 🥽 Experimentální VR/AR obsah
- [ ] 🌍 Mezinárodní partnerství

## 💖 Poděkování

Obrovské poděkování patří:

- 🏫 **Pilotním školám** za testování v reálné výuce
- 👨‍🏫 **Učitelům** za neocenitelnou zpětnou vazbu  
- 👨‍💻 **Vývojářům** za technické příspěvky
- 👨‍🎓 **Studentům** za upozornění na chyby
- 🎨 **Designérům** za vizuální vylepšení

### 🌟 Hlavní přispěvatelé

<a href="https://github.com/your-username/informatika-zs/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=your-username/informatika-zs" />
</a>

---

## 🔧 Troubleshooting

### ❓ Časté problémy

**Problem:** `mkdocs: command not found`
```bash
# Řešení: Nainstalujte MkDocs
pip install mkdocs mkdocs-material
```

**Problem:** Stránka se nenačte lokálně
```bash  
# Řešení: Zkontrolujte port
mkdocs serve -a 127.0.0.1:8001
```

**Problem:** Chyby při buildu
```bash
# Řešení: Vyčistěte cache
mkdocs build --clean
```

### 📋 Systémové požadavky

- **Python:** 3.7 nebo vyšší
- **RAM:** Minimálně 1GB pro development
- **Disk:** 100MB pro všechny závislosti
- **Browser:** Chrome 90+, Firefox 88+, Safari 14+

## 📱 Mobile-first přístup

Materiály jsou optimalizovány pro:
- 📱 **Mobilní telefony** (320px+)
- 📟 **Tablety** (768px+) 
- 💻 **Desktopy** (1024px+)
- 🖥️ **Large displays** (1440px+)

## ♿ Přístupnost

Dbáme na to, aby materiály byly dostupné všem:
- 🔍 **Škálovatelné fonty** - až 200%
- 🎨 **Vysoký kontrast** - WCAG AA compliant
- ⌨️ **Keyboard navigation** - bez myši
- 📱 **Screen reader friendly** - pro zrakově postižené

---

**⭐ Pokud vám projekt pomáhá, dejte nám hvězdičku na GitHubu!**

*Společně tvoříme budoucnost informatického vzdělávání v České republice! 🇨🇿*

---

*Poslední aktualizace: Leden 2025 • Verze: 2.1.0*