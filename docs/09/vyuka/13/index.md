# 13: Servis počítače a řešení technických problémů

## Úvod

### Motivace
!!! question "Co dělat, když počítač stávkuje?"
    Určitě se to už stalo každému z vás: Hrajete oblíbenou hru nebo na poslední chvíli píšete úkol a najednou se počítač zasekne, internet spadne nebo větráček hučí jako startující letadlo. Jak zachránit situaci a nemuset hned volat drahého opraváře?

### Cíl hodiny
!!! success "Co se dnes naučíme"
    * Základy hardwarové údržby počítače (jak ho nezničit při čištění).
    * Jak zrychlit starší stroj (výměna komponent).
    * Udržování softwaru v kondici (aktualizace a bezpečnost).
    * První pomoc při zamrznutí systému.
    * Základní orientaci v nastavení domácího Wi-Fi routeru.

---

## Práce v hodině

### Servis počítače

#### Výměna disku, paměti
Máte doma starší a pomalý počítač? Často pomůže jednoduchý upgrade (vylepšení)!

* **Výměna disku:** Přechod ze starého mechanického HDD disku na moderní a rychlý **SSD disk** je nejznatelnější vylepšení, které můžete udělat. Systém pak nastartuje za pár sekund.
* **Přidání paměti (RAM):** Pokud máte otevřeno více oken (např. v prohlížeči) a počítač "nestíhá", přidání RAM zlepší jeho schopnost zpracovávat více úloh najednou.

!!! warning "Bezpečnost na prvním místě"
    Před jakýmkoliv zásahem do útrob počítače ho **vždy vypněte a odpojte ze zásuvky**! Vyvarujte se také statické elektřině (např. dotykem o topení před sáhnutím do PC).

#### Čištění od prachu
Prach funguje jako izolant a brání chlazení. Kvůli tomu se počítač přehřívá, zpomaluje se (aby se ochladil) a může se dokonce poškodit.

!!! tip "Správný postup čištění"
    * Používejte **stlačený vzduch ve spreji**.
    * **Nepoužívejte vysavač** (může způsobit statický výboj, který poškodí součástky).
    * Při ofukování ventilátorů je jemně přidržte prstem, aby se neroztočily do extrémních otáček (hrozí zničení ložiska).

#### Aktualizace - operační systém, ovladače, antivir
Software je nutné udržovat v aktuálním stavu nejen kvůli novým funkcím, ale hlavně kvůli **bezpečnosti**.

* **Operační systém:** Windows Update instaluje bezpečnostní záplaty na objevené zranitelnosti.
* **Ovladače (Drivers):** Například pro grafickou kartu (důležité pro hráče). Mohou zlepšit výkon a stabilitu her.
* **Antivir:** Systém Windows má v sobě zabudovaný kvalitní Windows Defender. Důležité je nevypínat ho a nechat ho stahovat nejnovější definice virů.

---

### Zamrznutí počítače

Jak postupovat, když obrazovka nereaguje a myš se zasekne?

#### Ukončení úlohy
Často nezamrzne celý počítač, ale jen jeden konkrétní program (např. hra nebo prohlížeč).

1. Stiskněte klávesovou zkratku **`Ctrl + Shift + Esc`** (otevře Správce úloh / Task Manager).
   * *Alternativa: `Ctrl + Alt + Delete` a vybrat "Správce úloh".*
2. Najděte program, který má u sebe poznámku *(Neodpovídá)*.
3. Klikněte na něj pravým tlačítkem a zvolte **Ukončit úlohu**.

#### Restartování celého zařízení
Když nepomáhá ani Správce úloh (nebo ho nelze otevřít), přichází na řadu klasický restart.

!!! info "Zázračné pravidlo IT"
    **„Zkusili jste to vypnout a zapnout?“** Většinu drobných softwarových chyb vyřeší pouhý restart počítače. Tím se uvolní zaplněná operační paměť a systém začne "s čistým štítem".

* **Měkký restart:** Pokud to jde, vždy provedeme přes nabídku Start -> Napájení -> Restartovat.
* **Tvrdý restart:** Zmáčkněte a podržte tlačítko napájení na bedně/přímo na notebooku po dobu cca **5 až 10 sekund**. Zařízení se natvrdo vypne. Používejte jen jako poslední záchranu, můžete přijít o neuloženou práci!

---

### Nastavení routeru

Router je ta krabička s anténami, která vám doma tvoří Wi-Fi a spojuje vás s internetem. 

**Jak se do něj dostat?**
1. Otevřete internetový prohlížeč.
2. Do adresního řádku napište IP adresu routeru (nejčastěji to bývá `192.168.1.1` nebo `192.168.0.1`).
3. Zadejte jméno a heslo (bývá zespodu zařízení na štítku – např. jméno: *admin*, heslo: *admin*).

**Co se tam dá nastavit?**
* Změna názvu Wi-Fi sítě (tzv. SSID).
* Změna hesla k Wi-Fi.
* Rodičovská kontrola (např. vypnutí Wi-Fi po 22:00).
* Restartování routeru (když "zlobí" internet, často stačí router vytáhnout ze zásuvky na 10 vteřin a zase zapojit).

---

## Závěr
Dnes jsme si ukázali, že ne každá chyba znamená nutnost kupovat nový počítač. Většinu drobných potíží zvládnete s chladnou hlavou vyřešit sami doma. 

!!! task "Úkol na doma"
    Zkuste si na svém domácím počítači otevřít Správce úloh (`Ctrl + Shift + Esc`) a podívejte se zhruba, jaké programy vám momentálně nejvíce vytěžují procesor a paměť RAM. Zeptejte se doma rodičů, kde a jak máte nastavený domácí Wi-Fi router.
