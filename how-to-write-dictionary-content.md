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
