# Jak psát články do slovníku

Návod pro kolegy, kteří zpracovávají úkoly ze souboru `dictionary.md`.

## K čemu slovník slouží

Slovník fondly.cz je sada vzdělávacích článků. Každý článek vysvětluje jeden pojem,
cílí na konkrétní vyhledávací dotaz („co je …“) a nenásilně vede čtenáře k našim
službám. Píšeme ho tak, aby ho dohledali lidé ve vyhledávači (SEO) i aby ho citovaly
AI nástroje jako ChatGPT, Perplexity nebo Google AI Overviews (GEO).

## Základní pravidlo: 1 pojem = 1 článek = 1 URL

Každý úkol (i podúkol) ve Freelu = jeden samostatný článek na vlastní URL
(např. `/slovnik/spf-zaznam/`). Nikdy nedáváme víc pojmů na jednu stránku.

## Struktura článku

Dodržuj u každého hesla stejnou, předvídatelnou strukturu:

1. **Nadpis H1** – přesný název pojmu, nic víc (např. „SPF záznam“).
2. **Definice v první větě** – hned a přímo odpověz „co to je“. Žádný úvod typu
   „v dnešní digitální době…“. Tuto větu si bere Google do snippetu a AI ji cituje –
   musí dávat smysl i vytržená z kontextu.
3. **Úvodní odstavec** – 2–4 věty, rozvedení definice.
4. **Nadpisy H2/H3 jako otázky** – „Jak SPF záznam funguje?“, „Proč je SPF důležitý?“,
   „Jak SPF nastavit?“. Kopíruje to, jak se lidé ptají vyhledávače i AI.
5. **Tělo** – krátké odstavce (2–4 věty), odrážky, tabulky, příklady. Žádné dlouhé
   bloky textu.
6. **Praktický kontext** – jak pojem souvisí s tím, co řešíme u zákazníků; odkaz na
   související službu (viz „Cílová služba“ u dané kategorie v `dictionary.md`).
7. **Související pojmy** – na konci 3–5 odkazů na další hesla slovníku.
8. **FAQ** – 2–4 časté otázky a stručné odpovědi.
9. **Patička** – jméno autora a datum poslední aktualizace.

## SEO pravidla

- **Klíčové slovo** = název pojmu. Použij ho v H1, v první větě, v title i v URL.
- **Title tag**: „[Pojem] – co to je a k čemu slouží | fondly.cz“ (do ~60 znaků).
- **Meta description**: 1–2 věty shrnující článek, do ~155 znaků, vychází z definice.
- **URL**: krátká, bez diakritiky, obsahuje pojem (`/slovnik/dkim/`).
- **Nadpisy**: jen jeden H1, dál H2/H3 hierarchicky; klíčové slovo a jeho varianty
  v nadpisech.
- **Obrázky**: vždy vyplň alt text.
- **Interní odkazy**: prolinkuj na související hesla a alespoň na jednu službu.

## GEO pravidla (aby článek citovaly AI)

- **Odpověz hned** – definice v první větě, žádné omáčky.
- **Samostatnost** – článek musí plně odpovědět na „co je X“ bez nutnosti číst další
  stránky.
- **Fakta, ne marketing** – konkrétní, ověřitelná tvrzení; čísla, hodnoty, příklady
  (např. ukázka konkrétního formátu SPF záznamu).
- **Struktura** – krátké celky, odrážky, tabulky a otázkové nadpisy se dobře
  strojově zpracovávají.
- **Aktuálnost** – uváděj datum aktualizace, obsah drž aktuální.
- **Důvěryhodnost (E-E-A-T)** – uveď autora, piš z pozice odborníka, vycházej
  z reálné praxe.

## Strukturovaná data (zadání pro vývoj / redakční systém)

- Heslo slovníku: `DefinedTerm` / `DefinedTermSet`.
- FAQ sekce: `FAQPage`.
- Drobečková navigace: `BreadcrumbList`.

## Rozsah a styl

- **Délka**: orientačně 300–800 slov podle složitosti pojmu. Raději kratší
  a výstižné než natahované.
- **Jazyk**: česky, spisovně, srozumitelně. Vysvětluj i laikovi, ale nelži
  zjednodušením.
- **Tón**: věcný, odborný, vstřícný; bez balastu a klišé.
- **Zkratky**: při prvním použití rozepiš (např. „SPF (Sender Policy Framework)“).

## Checklist před odevzdáním

- [ ] H1 = přesný název pojmu
- [ ] První věta je úplná definice a dává smysl samostatně
- [ ] Aspoň 2 nadpisy formulované jako otázky
- [ ] Krátké odstavce, použité odrážky / tabulky
- [ ] Vyplněný title a meta description
- [ ] 3–5 odkazů na související hesla + odkaz na službu
- [ ] FAQ sekce (2–4 otázky)
- [ ] Uveden autor a datum aktualizace
- [ ] Text bez gramatických chyb, fakticky ověřený


# Prompt pro generování slovníkových pojmů — fondly.cz

Zkopíruj celý blok níže, změň `[POJEM]` na požadovaný termín a vlož do Claude nebo jiného AI.

---

```
Jsi copywriter pro digitální agenturu fondly.cz. Agentura se zabývá tvorbou webových stránek (hlavně WordPress + Elementor), vývojem webových aplikací a informačních systémů na míru, správou serverů a e-shopů. Tým tvoří Martin Kokeš (koordinace, weby, trendy) a Honza Pilař (developer, servery). Sídlo je v Kolíně.

Napiš slovníkový článek pro pojem: [POJEM]

Dodržuj tato pravidla:

1. STRUKTURA ČLÁNKU:
   - Úvodní odstavecß: Jasná,ß srozumitelná definice pojmu. Co to je jednou větou, a hned druhá věta proč to existuje / jaký problém to řeší.
   - Sekce "K čemu to slouží": Vysvětli praktický účel pojmu. Proč by to mělo zajímat někoho, kdo si nechává dělat web nebo aplikaci.
   - Sekce "Jak to používáme ve fondly": Konkrétně popiš, jak s tímto pojmem / technologií / principem pracujeme my při našich projektech — tvorba webů, aplikací, e-shopů, správa serverů. Buď konkrétní, ale nevymýšlej si specifické projekty nebo klienty.
   - Sekce "Proč je to důležité": 2–3 věty shrnující, proč by čtenář měl tento pojem znát a jak mu porozumění pomůže lépe komunikovat s vývojáři nebo se rozhodovat o svém projektu.

2. STYL:
   - Konverzační, neformální, přátelský — jako by to vysvětloval kamarád, který tomu rozumí.
   - Piš v 1. osobě množného čísla ("my", "u nás", "děláme") když mluvíš za fondly.
   - Žádný korporátní jazyk, žádné buzzwordy bez vysvětlení.
   - Pokud pojem má anglický originál, uveď ho v závorce.
   - Pokud existuje běžná zkratka, vysvětli ji.
   - Používej přirovnání a příklady ze skutečného života, aby to pochopil i úplný laik.

3. FORMÁTOVÁNÍ:
   - Délka celého textu: 100–200 slov.
   - Nepoužívej odrážkové seznamy — piš v odstavcích.
   - Na konci článku přidej krátkou větu ve stylu: "Chcete se dozvědět víc nebo potřebujete s výše uvedeným pojmem pomoct? Ozvěte se nám." s odkazem na kontakt.

4. SEO:
   - Přirozeně zakomponuj pojem a jeho variace do textu (ale ne násilně).
   - Úvodní věta by měla fungovat jako meta description — výstižná, informativní, do 155 znaků.
   - Pokud se pojem přirozeně váže na jiné pojmy ze světa webů/IT, zmiň je (budou se propojovat interními odkazy).
```

---

## Příklad použití

Změníš `[POJEM]` na konkrétní slovo, např.:

- `[POJEM]` → `WordPress`
- `[POJEM]` → `Responzivní design`
- `[POJEM]` → `API`
- `[POJEM]` → `SSL certifikát`
- `[POJEM]` → `CMS`
- `[POJEM]` → `Hosting`
- `[POJEM]` → `DNS`
- `[POJEM]` → `Framework`
- `[POJEM]` → `Git`

A prompt ti vygeneruje konzistentní text připravený k vložení do WordPressu jako nový pojem v CPT Slovník.