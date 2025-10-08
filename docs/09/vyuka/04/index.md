# 04: Datové typy a komprese dat

## Opakování z minula

- Co znamená kódování?
- Jak se kóduje v počítači text?

## Úvod

### Motivace

Každý den pracujeme se soubory (fotky, dokumenty, hudba). V této hodině se zaměříme na formáty souborů (přípony) — co jednotlivé formáty znamenají, jaké mají vlastnosti (kvalita, velikost, kompatibilita) a kdy který formát použít. To vám pomůže rozhodnout, jaký formát zvolit pro sdílení, tisk nebo archivaci.

### Cíl hodiny

- Naučit se rozpoznat běžné přípony a formáty souborů (např. .txt, .pdf, .jpg, .png, .mp3, .wav, .svg, .zip, .mp4) a pochopit jejich hlavní vlastnosti.
- Umět vybrat vhodný formát pro konkrétní situaci (tisk, sdílení, úpravy, archivace).
- Vysvětlit rozdíl mezi bezztrátovou a ztrátovou kompresí a uvést příklady formátů, které je používají.
- Procvičit jednoduché porovnání kvality a velikosti souborů.

## Práce v hodině

1) Formáty souborů (10 min)

- Stručný přehled
	- Textové formáty: `.txt`, `.md`, `.pdf`, `.docx` — rozdíl mezi prostým textem a formátovanými dokumenty.
	- Obrázkové formáty: `PNG` (bezztrátový, vhodný pro grafiku/ikony), `JPG/JPEG` (ztrátový, vhodný pro fotografie), `SVG` (vektorová grafika, škálovatelná bez ztráty kvality).
	- Zvukové formáty: `WAV` (bezztrátový/nekomprimovaný), `MP3` (ztrátové, vhodné pro sdílení).
	- Video: `MP4`.
	- Archivy a přenos: `ZIP`, `RAR` — balení více souborů a bezztrátová komprese pro přenos.

	- Praktická pravidla: když chcete tisknout nebo editovat → používejte bezztrátové formáty (PNG, PDF, WAV); když chcete šetřit místo nebo posílat rychle → ztrátové formáty (JPG, MP3) s rozumným nastavením kvality.

    **Aktivita:**
    - najděte na webu soubory s výše zmíněnými příponami a podívejte se na jejich vlastnosti (velikost, kvalita, kde se používají)
    > Nápověda: do vyhledávacího pole zadejte např. `strom filetype:png` nebo `strom filetype:mp4`

2) Komprese dat (10 min)

- Princip: komprese se snaží zmenšit počet bitů potřebných k uložení informace. Dva hlavní přístupy:
	- Bezztrátová komprese: po dekompresi získáme původní data přesně (např. ZIP, PNG).
	- Ztrátová komprese: některé informace se trvale odstraní pro menší velikost a často nepostřehnutelnou ztrátu kvality (např. JPG, MP3).

- Příklady, kdy co použít:
	- Dokumenty, archivy, programy → bezztrátová (ZIP)
	- Fotky na web, streamované audio → ztrátová (JPG, MP3)

3) Ukázka: RLE (run‑length encoding) – jednoduchá bezztrátová metoda (5 min)

- Princip: u opakujících se symbolů zapisujeme symbol + počet opakování. Např. pro řetězec AAAAABBBCC → A5B3C2.
- Předvedení na černobílé (binární) obrazové řadě: 00000011110000 → 06 4 04 (nebo 0×6,1×4,0×4) — výhoda JSON/TXT vysvětlení.

4) Praktická aktivita (15 min)

- Úkol 1: Najděte fotku v JPG formátu na internetu. Uložte kopii fotky v PNG formátu. Obě fotky stáhněte a nahrajte je na [Office 365 OneDrive](https://zshovorcovicka-my.sharepoint.com/my?). 
- Úkol 2: Máte dvě verze fotografie: `foto.jpg` (ztrátová) a `foto.png` (bezztrátová). Kterou zvolíte pro tisk o velikosti A4 a proč? Kterou pro zaslání e‑mailem, když je potřeba ušetřit kapacitu?
- Úkol 3: Zabalte oba soubory do ZIP archivu a porovnejte velikost s původními soubory.

## Cvičení (k vyučování / domácí úkol)

Pro domácí procvičení nechte žáky udělat následující úkoly; uložte je na papír nebo do elektronického dokumentu.

1) RLE (úroveň: rozumné porozumění)
	 - Aplikujte run‑length encoding na binární řetězec: 11110000000011111

## Závěr (5 min)

Klíčové body k zopakování:
- Různé formáty souborů mají různé vlastnosti a použití.
- Bezztrátová komprese zachovává původní data, ztrátová komprese je efektivnější, ale s určitými ztrátami.
- Vhodný formát závisí na účelu použití (tisk, sdílení, archivace).

### Ověření znalostí

1) Vysvětlete, jak zjistíte typ souboru a včem se liší soubory s různými typy.
2) Který typ souboru zvolíte, když chcete fotku vytisknout v původní kvalitě?
3) Který typ souboru je možné otevřít v Microsoft Word?
4) Jak mohu poslat více souborů najednou v jednom souboru?
