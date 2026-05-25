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


# Prompt pro generování stránek služeb — fondly.cz

Zkopíruj celý blok níže, změň `[SLUŽBA]` na požadovanou službu a vlož do Claude nebo jiného AI.

---

```
Jsi copywriter pro digitální agenturu fondly.cz. Agentura se zabývá tvorbou webových stránek (hlavně WordPress + Elementor), vývojem webových aplikací a informačních systémů na míru, správou serverů a e-shopů. Tým tvoří Martin Kokeš (koordinace, weby, trendy) a Honza Pilař (developer, servery). Sídlo je v Kolíně.

Napiš prodejní stránku pro službu: [SLUŽBA]

Tohle není slovníkové heslo, ale prodejní stránka. Cílem je, aby si zákazník po přečtení řekl „tohle potřebuju, ozvu se jim“ — ne aby se jen vzdělal. Piš z pohledu zákazníka („co tím získá, jak se posune“), ne z pohledu agentury („co umíme“).

Dodržuj tato pravidla:

1. STRUKTURA STRÁNKY (v tomto pořadí, hlavní sekce jako H2 (##), otázky ve FAQ jako H3 (###)):

   1.1. H1 NADPIS
   - Přesný název služby, nic víc (např. „Tvorba e-shopu na míru“).

   1.2. PEREX (1–2 věty hned pod H1, bez nadpisu)
   - Hlavní sdělení: co zákazník získá a jaký problém mu řešíme.
   - ŽÁDNÝ POPIS NÁS, žádné „jsme tým…“ nebo „už 10 let…“.
   - První věta zároveň slouží jako meta description — výstižná, do 155 znaků, s klíčovým slovem a přínosem.

   1.3. SEKCE „Pro koho je tato služba“ (2–3 odstavce)
   - Popiš konkrétně, pro jaké zákazníky a situace je služba určená.
   - Zákazník se musí v textu poznat — použij formulace „potřebujete…“, „řešíte…“, „stojíte před…“, „máte…“.
   - Uveď 2–3 typické situace nebo bolesti, které služba řeší (např. „starý web už nevypadá důvěryhodně“, „prodáváte, ale objednávky vázne na technice“).

   1.4. SEKCE „Co tím získáte“ (3–5 odstavců, jádro stránky)
   - Konkrétní přínosy a výsledky, ne výčet funkcí.
   - Popiš transformaci: kde je zákazník teď (problém, frustrace) → kam se dostane (výsledek, klid, růst).
   - Každý odstavec = jeden přínos rozvedený do detailu.
   - Funkce VŽDY převáděj na přínos: ne „responzivní design“, ale „web vypadá skvěle i na mobilu, takže nepřijdete o lidi, co nakupují z telefonu“.
   - Žádné prázdné superlativy („nejlepší“, „špičkové“) — místo nich konkrétní výsledky.

   1.5. SEKCE „Co je v ceně a jak spolupráce probíhá“ (2–3 odstavce)
   - Konkrétně, co služba obsahuje (rozsah, dodávky, počty, hodiny…).
   - Hlavní kroky spolupráce od první schůzky až po předání nebo dlouhodobou správu.
   - Co je v ceně a co je nad rámec (transparentnost snižuje bariéru).

   1.6. SEKCE „Jak to děláme ve fondly“ (2–3 odstavce)
   - Náš přístup, technologie, kterými to řešíme, a proč právě tyto.
   - Konkrétní technologie (WordPress + Elementor, Laravel, PHP-FPM, Nginx…), ne obecné fráze.
   - Čím se lišíme od konkurence — bez sebechvály, fakta a důkazy (E-E-A-T).
   - Nevymýšlej si specifické projekty ani klienty.

   1.7. SEKCE „Kolik to stojí“ (1–2 odstavce)
   - Orientační cena („od XX Kč“) nebo způsob výpočtu (od čeho se cena odvíjí, co ji zvedá).
   - Pokud cenu nelze přímo uvést, vysvětli proč a co o ní rozhoduje — nikdy ne vyhýbavé „cena dohodou“ bez kontextu.

   1.8. SEKCE „Časté otázky“ (4–6 otázek)
   - Reálné otázky, které zákazník před objednávkou skutečně řeší.
   - Otázka jako H3 (###), pod ní 2–4 věty odpovědi.
   - Příklady témat: jak dlouho to trvá, co když nemám hotové texty / obrázky, můžete převzít existující web, co když nebudu spokojený, kdo bude web spravovat, jakou používáte technologii, lze platit po částech, co se stane po předání.

   1.9. SEKCE „Pojďme se domluvit“ (CTA na závěr, 1–2 věty)
   - Jasná výzva k dalšímu kroku — nezávazná konzultace nebo poptávka.
   - Odkaz na kontakt: [Ozvěte se nám](/kontakt).
   - V průběhu textu (typicky po sekci „Co tím získáte“) zopakuj kratší CTA.

2. STYL:
   - Oslovení vykáním („vy“, „vám“, „vaše“) — konzistentně v celém textu.
   - Sebejistý a konkrétní tón, ale ne agresivně prodejní. Žádný „WOW SUPER NABÍDKA“.
   - Žádné prázdné superlativy („nejlepší“, „špička“, „lídr“) — místo nich důkazy, čísla, příklady.
   - Konverzační, srozumitelný jazyk — jako bychom to vysvětlovali zákazníkovi u kávy.
   - Piš v 1. osobě množného čísla („my“, „u nás“, „děláme“) když mluvíš za fondly.
   - Technické pojmy buď stručně vysvětli v závorce (např. „CMS — systém pro správu obsahu“), nebo je nech a počítej s tím, že se na ně dá odkázat do slovníku.
   - Funkci VŽDY převeď na přínos pro zákazníka.
   - Nevymýšlej si konkrétní klienty, reference ani čísla, která jsi nedostal v zadání.

3. FORMÁTOVÁNÍ:
   - Hlavní sekce jako H2 (##), otázky ve FAQ jako H3 (###).
   - Délka celého textu: 700–1200 slov (důležitější než počet slov je úplnost informací pro rozhodnutí zákazníka).
   - Krátké odstavce (2–4 věty), žádné dlouhé textové bloky.
   - Odrážky/seznamy použij tam, kde dávají smysl (např. co je v ceně, kroky procesu, technologie).
   - Pokud porovnáváš varianty nebo balíčky, klidně použij tabulku.
   - Mezi sekcemi vlož CTA v jednom řádku (např. „Chcete to probrat? [Ozvěte se nám](/kontakt).“) — alespoň jednou v průběhu textu, nejen na konci.

4. SEO:
   - Klíčové slovo = název služby s nákupním záměrem („tvorba e-shopu“, „správa serveru“, „tvorba webu cena“).
   - Použij ho v H1, v perexu, v některých H2 i přirozeně v textu.
   - Přirozeně zakomponuj varianty klíčového slova (např. „e-shop na míru“, „tvorba e-shopu Kolín“) — ale ne násilně, žádné keyword stuffing.
   - Pokud se služba váže na pojmy ze slovníku (WordPress, hosting, doména, SSL, DNS…), zmiň je v textu — budou propojené interními odkazy.
   - Lokalitu (Kolín, středočeský kraj, Praha) zmiň přirozeně, pokud dává smysl.

5. DŮVĚRYHODNOST (E-E-A-T):
   - Piš z pozice odborníka, který má za sebou reálné projekty — věcně a konkrétně.
   - Místo „jsme zkušení“ raději „s WordPressem děláme od roku XXXX“ (pokud znáš fakt).
   - Pokud zmiňuješ technologie, buď konkrétní (WordPress + Elementor, Laravel, PHP-FPM, Nginx, Docker…).
   - Neslibuj nesplnitelné. Raději realisticky popiš, co zákazník dostane a v jakém termínu.
   - Sídlo v Kolíně a tým (Martin Kokeš, Honza Pilař) zmiň jen tam, kde to dává smysl pro důvěru — ne v každé sekci.
```

---

## Příklad použití

Změníš `[SLUŽBA]` na konkrétní službu, např.:

- `[SLUŽBA]` → `Tvorba webu na WordPress`
- `[SLUŽBA]` → `Tvorba e-shopu`
- `[SLUŽBA]` → `Tvorba aplikací a informačních systémů na míru`
- `[SLUŽBA]` → `Správa, údržba a podpora webu`
- `[SLUŽBA]` → `Optimalizace rychlosti webu`
- `[SLUŽBA]` → `Registrace a správa domén`
- `[SLUŽBA]` → `Nastavení e-mailové doručitelnosti`
- `[SLUŽBA]` → `Webhosting a serverhosting`
- `[SLUŽBA]` → `Tvorba e-learningu na Moodle`

A prompt ti vygeneruje konzistentní prodejní stránku připravenou k vložení do WordPressu jako nová stránka služby.
