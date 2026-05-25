# Jak psát obsah služeb

Návod pro kolegy, kteří zpracovávají obsah ze souboru `services.md`.

## K čemu stránky služeb slouží

Stránky služeb jsou prodejní stránky. Každá popisuje jednu službu, kterou si může
zákazník koupit, pomáhá mu rozhodnout se a vede ho k poptávce. Na rozdíl od slovníku
(který vzdělává) je cílem stránky služby **získat poptávku**. Píšeme je tak, aby je
dohledali lidé ve vyhledávači (SEO) i aby je doporučovaly AI nástroje jako ChatGPT,
Perplexity nebo Google AI Overviews (GEO).

## Základní pravidlo: 1 služba = 1 stránka = 1 URL

Každá služba ze `services.md` = jedna samostatná stránka na vlastní URL
(např. `/sluzby/tvorba-eshopu/`). Sekce v `services.md` slouží jako tematické skupiny –
z nich mohou vzniknout nadřazené rozcestníkové stránky.

## Hlavní princip: piš o zákazníkovi, ne o sobě

Tohle je nejdůležitější. Zákazníka nezajímá, co umíme – zajímá ho, **co tím získá
a jak se posune**. Každý odstavec si ověř otázkou „a co z toho zákazník má?“.

- Špatně: „Vytváříme e-shopy na míru v Laravelu.“
- Dobře: „Spustíte e-shop, který prodává od prvního dne a zvládnete ho spravovat sami.“

## Struktura stránky služby

Dodržuj u každé služby stejnou strukturu:

1. **Nadpis H1** – název služby (např. „Tvorba e-shopu“).
2. **Hlavní sdělení (perex)** – první 1–2 věty řeknou, co zákazník získá a jaký problém
   mu řešíme. Žádný popis nás.
3. **Pro koho služba je a jaký problém řeší** – zákazník se musí v textu poznat
   („potřebujete…“, „řešíte…“).
4. **Co tím získáte / jak se posunete** – jádro stránky. Konkrétní přínosy a výsledky,
   ideálně „před a po“ (kde je zákazník teď × kam se dostane).
5. **Co služba obsahuje a jak spolupráce probíhá** – rozsah, kroky, co je v ceně.
   Funkce sem patří, ale vždy navázané na přínos.
6. **Proč fondly** – reference, zkušenosti, čím se lišíme, záruky. Budí důvěru (E-E-A-T).
7. **Cena** – aspoň orientační („od…“) nebo jak se cena tvoří. Transparentnost snižuje
   bariéru.
8. **Časté otázky (FAQ)** – 3–5 otázek, které zákazník reálně řeší před objednávkou.
9. **Výzva k akci (CTA)** – jeden jasný další krok (nezávazná poptávka, konzultace).
   Zopakuj ji i v průběhu textu.
10. **Související služby** – prolink na navazující služby a relevantní hesla slovníku.

## Jak psát o přínosech, ne o funkcích

Funkce = co děláme. Přínos = co zákazník získá. Vždy převáděj funkci na přínos:

| Funkce | Přínos pro zákazníka |
| --- | --- |
| Responzivní web | Web vypadá skvěle na mobilu i počítači – nepřijdete o zákazníky nakupující z telefonu |
| Napojení platební brány | Zákazník zaplatí online hned – méně nedokončených objednávek |
| Migrace bez výpadku | Přejdete k nám a web ani na chvíli nespadne – nepřijdete o návštěvnost ani pozice |
| Optimalizace rychlosti | Web se načítá rychle – návštěvníci neodcházejí a Google web lépe hodnotí |

**„Jak se posune“** = popiš transformaci. Kde je zákazník dnes (problém, frustrace)
a kam ho služba dostane (výsledek, klid, růst).

## SEO pravidla

- **Klíčové slovo** = název služby, často s nákupním záměrem („tvorba e-shopu“,
  „tvorba webu cena“). Použij ho v H1, perexu, title i URL.
- **Title tag**: „[Služba] – [hlavní přínos] | fondly.cz“ (do ~60 znaků).
- **Meta description**: 1–2 věty s přínosem a výzvou k akci, do ~155 znaků.
- **URL**: krátká, bez diakritiky, obsahuje službu (`/sluzby/tvorba-eshopu/`).
- **Nadpisy**: jeden H1, dál H2/H3 hierarchicky, s klíčovým slovem a jeho variantami.
- **Obrázky**: reálné ukázky práce, vždy s alt textem.
- **Interní odkazy**: prolinkuj na související služby a na vysvětlující hesla slovníku.

## GEO pravidla (aby službu doporučovaly AI)

- **Hned je jasné, o co jde** – v prvních větách co služba je, pro koho a co řeší.
- **Konkrétní fakta** – co je v ceně, jak dlouho to trvá, v jakém rozsahu. AI
  i zákazník chtějí konkrétní údaje, ne sliby.
- **Struktura** – krátké odstavce, odrážky, tabulky, otázkové nadpisy.
- **Důvěryhodnost (E-E-A-T)** – reference, zkušenosti, autor, kontakt. AI doporučuje
  důvěryhodné zdroje.
- **Aktuálnost** – uváděj datum aktualizace, ceny a rozsah drž aktuální.

## Strukturovaná data (zadání pro vývoj / redakční systém)

- Stránka služby: `Service` (+ `Offer` / `AggregateOffer` s cenou).
- FAQ sekce: `FAQPage`.
- Drobečková navigace: `BreadcrumbList`.
- Reference / hodnocení: `Review` / `AggregateRating`.

## Rozsah a styl

- **Délka**: orientačně 400–1000 slov podle rozsahu služby. Hlavní je úplnost informací
  pro rozhodnutí, ne počet slov.
- **Oslovení**: vykání („vy“), konzistentně na celém webu.
- **Tón**: sebejistý a konkrétní, ale ne agresivně prodejní. Žádné prázdné superlativy
  („nejlepší“, „špička“) – místo nich důkazy a čísla.
- **Jazyk**: česky, spisovně, srozumitelně; technické pojmy buď vysvětli, nebo odkaž
  na heslo ve slovníku.

## Checklist před odevzdáním

- [ ] H1 = název služby
- [ ] Perex říká, co zákazník získá – ne co děláme
- [ ] Je jasné, pro koho služba je a jaký problém řeší
- [ ] Sekce „co získáte / jak se posunete“ s konkrétními přínosy
- [ ] Funkce jsou převedené na přínosy
- [ ] Uvedená orientační cena nebo způsob výpočtu
- [ ] FAQ sekce (3–5 otázek)
- [ ] Jasná výzva k akci (CTA)
- [ ] Odkazy na související služby a hesla slovníku
- [ ] Vyplněný title a meta description
- [ ] Uveden autor / datum aktualizace, text bez chyb
