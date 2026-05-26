# Propojovací mapa — služby ↔ slovník

Návod, jak interně prolinkovat stránky služeb (`services.md`) a hesla slovníku (`dictionary.md`).

## Jak mapu používat

- Najdi si v tabulce řádek pro pojem nebo službu, kterou píšeš.
- Sloupec **Linky na služby** = které stránky služeb v textu zmínit a odkázat (cíl: `/sluzby/<slug>/`).
- Sloupec **Linky na pojmy** = která hesla slovníku v textu zmínit a odkázat (cíl: `/slovnik/<slug>/`).
- Linky vkládej jen tam, kde **přirozeně padnou do textu** — nesnaž se zařadit všechny. Když se některý link do textu nevejde, vynech ho.
- Mapa je strukturální (vznikla z kategorií, ne ze samotného textu). Až bude obsah hotový, projeď článek ještě jednou a doplň 1–2 linky, které dávají smysl podle textu.
- Rozsah linkování: striktně tematicky — typicky 2–4 služby a 3–6 pojmů na článek.

---

## 1) Tabulka — Služby → linky

### Tvorba webů a aplikací

| Zdroj (služba) | Linky na služby | Linky na pojmy |
|---|---|---|
| Tvorba webových stránek | Tvorba webu na WordPress, Redesign webu, Tvorba landing page, Správa a údržba webu | CMS, WordPress, Responzivní design, UX, UI, Frontend, HTML, CSS |
| Tvorba webové aplikace | Webová aplikace na míru (PHP, Laravel), Tvorba e-shopu, Napojení API a služeb třetích stran | Webová aplikace, Laravel, PHP, Backend, Frontend, API, Databáze, Framework |
| Tvorba e-shopu | Napojení platební brány, Migrace e-shopu, Tvorba a správa XML feedů pro zbožové srovnávače, Webhosting | WordPress, Plugin, Platební brána, XML feed, Zbožové srovnávače, SSL/TLS certifikát, GDPR |
| Webová aplikace na míru (PHP, Laravel) | Tvorba webové aplikace, Napojení API a služeb třetích stran, Správa serveru | Laravel, PHP, Composer, Framework, Backend, Databáze, MySQL, API, Git |
| Tvorba webu na WordPress | Tvorba webových stránek, Tvorba e-shopu, Školení práce s WordPressem, Aktualizace a zabezpečení webu | WordPress, CMS, Šablona, Plugin, PHP, Responzivní design |
| Tvorba e-learningu na Moodle | Školení práce s Moodlem, Správa serveru | Moodle, LMS, CMS, PHP, Databáze |
| Tvorba landing page | Tvorba webových stránek, Optimalizace rychlosti webu | Landing page, Responzivní design, SEO, PageSpeed, UX, UI |
| Redesign webu | Tvorba webových stránek, Tvorba webu na WordPress, Migrace webu na nový hosting | UX, UI, Wireframe, Prototyp, Responzivní design, CMS, WordPress |
| Převedení grafických návrhů do HTML a CSS | Tvorba webových stránek, Tvorba landing page | HTML, CSS, JavaScript, Frontend, Responzivní design, Mobile-first |

### Integrace a napojení

| Zdroj (služba) | Linky na služby | Linky na pojmy |
|---|---|---|
| Napojení platební brány | Tvorba e-shopu, Napojení API a služeb třetích stran | Platební brána, API, REST API, Webhook, JSON, SSL/TLS certifikát |
| Napojení API a služeb třetích stran | Tvorba webové aplikace, Webová aplikace na míru (PHP, Laravel), Napojení na fakturační a skladové systémy | API, REST API, JSON, Webhook, HTTP, HTTPS |
| Tvorba a správa XML feedů pro zbožové srovnávače | Tvorba e-shopu, Napojení API a služeb třetích stran | XML feed, Zbožové srovnávače, Webhook, SEO |
| Napojení na fakturační a skladové systémy | Tvorba e-shopu, Napojení API a služeb třetích stran, Webová aplikace na míru (PHP, Laravel) | API, REST API, JSON, Webhook, Databáze |

### Migrace

| Zdroj (služba) | Linky na služby | Linky na pojmy |
|---|---|---|
| Migrace webu na nový hosting | Webhosting, Serverhosting (pronájem serveru), Správa a údržba webu | Webhosting, DNS, A záznam, Propagace DNS, Záloha, Deployment, Migrace |
| Migrace e-shopu | Migrace webu na nový hosting, Tvorba e-shopu | Databáze, MySQL, SSL/TLS certifikát, Záloha, DNS, Propagace DNS |
| Migrace z WordPressu na řešení na míru | Tvorba webové aplikace, Webová aplikace na míru (PHP, Laravel) | WordPress, Laravel, PHP, Migrace, Databáze, MySQL |
| Migrace e-mailových schránek | Zřízení a správa e-mailových schránek, Nastavení e-mailové doručitelnosti (SPF, DKIM, DMARC) | E-mailová schránka, IMAP, POP3, SMTP, MX záznam, DNS |

### Domény

| Zdroj (služba) | Linky na služby | Linky na pojmy |
|---|---|---|
| Registrace domény | Správa a prodlužování domén, Webhosting | Doména, Registrátor domény, DNS, Nameserver, A záznam, Propagace DNS |
| Správa a prodlužování domén | Registrace domény, Převod (transfer) domény | Doména, Registrátor domény, DNS, Nameserver |
| Převod (transfer) domény | Registrace domény, Správa a prodlužování domén | Doména, Registrátor domény, Transfer (převod) domény, Nameserver, Propagace DNS |

### Hosting a servery

| Zdroj (služba) | Linky na služby | Linky na pojmy |
|---|---|---|
| Webhosting | Serverhosting (pronájem serveru), Správa serveru, Registrace domény | Webhosting, Sdílený hosting, Managed hosting, Diskový prostor, Uptime, FTP, SFTP, PHP-FPM |
| Serverhosting (pronájem serveru) | Webhosting, Správa serveru | Serverhosting, VPS, Dedikovaný server, Cloudový hosting, Datové centrum, Load balancing, IP adresa |
| Správa serveru | Serverhosting (pronájem serveru), Webhosting, Bezpečnostní audit webu | Webový server (Apache, Nginx), PHP-FPM, Cron (cron job), SSH, FTP, SFTP, Logy, Firewall |

### E-maily a doručitelnost

| Zdroj (služba) | Linky na služby | Linky na pojmy |
|---|---|---|
| Zřízení a správa e-mailových schránek | Migrace e-mailových schránek, Nastavení e-mailové doručitelnosti (SPF, DKIM, DMARC) | E-mailová schránka, E-mailový alias, Catch-all schránka, Autoresponder, IMAP, POP3, SMTP, MX záznam |
| Nastavení e-mailové doručitelnosti (SPF, DKIM, DMARC) | Audit doručitelnosti e-mailů a spam score, Zřízení a správa e-mailových schránek | Doručitelnost e-mailů, SPF, DKIM, DMARC, BIMI, Reverzní DNS (rDNS), TXT záznam |
| Audit doručitelnosti e-mailů a spam score | Nastavení e-mailové doručitelnosti (SPF, DKIM, DMARC), Řešení zařazení domény na blacklist | Doručitelnost e-mailů, Reputace odesílatele, Spam, Spam score (spamminess), Blacklist, Whitelist |
| Řešení zařazení domény na blacklist | Nastavení e-mailové doručitelnosti (SPF, DKIM, DMARC), Audit doručitelnosti e-mailů a spam score | Blacklist, Whitelist, Reputace odesílatele, Spam, Bounce (vrácený e-mail), Reverzní DNS (rDNS) |

### Provoz, správa a podpora

| Zdroj (služba) | Linky na služby | Linky na pojmy |
|---|---|---|
| Správa a údržba webu | Aktualizace a zabezpečení webu, Technická podpora, Zálohování a obnova dat | WordPress, CMS, Plugin, Záloha (backup), Logy, Produkční prostředí |
| Aktualizace a zabezpečení webu | Správa a údržba webu, Bezpečnostní audit webu | WordPress, Plugin, SSL/TLS certifikát, Dvoufaktorové ověření (2FA), CAPTCHA, Malware, Zranitelnost, HTTPS |
| Technická podpora | Správa a údržba webu, Programátorské práce a servisní zásahy na míru | Logy, Vývojové prostředí, Staging |
| Zálohování a obnova dat | Správa a údržba webu, Migrace webu na nový hosting | Záloha (backup), Databáze, MySQL, Logy |
| Bezpečnostní audit webu | Aktualizace a zabezpečení webu, Správa serveru | Bezpečnostní audit, Zranitelnost, Malware, DDoS útok, Firewall, SSL/TLS certifikát, GDPR |
| Optimalizace rychlosti webu | Tvorba webových stránek, Správa a údržba webu | Optimalizace rychlosti webu, PageSpeed, Core Web Vitals, Cache (mezipaměť), Komprese, Lazy loading, CDN |
| Programátorské práce a servisní zásahy na míru | Webová aplikace na míru (PHP, Laravel), Technická podpora | PHP, Laravel, Git, Verzovací systém, Vývojové prostředí, Staging, Produkční prostředí |

### Školení a konzultace

| Zdroj (služba) | Linky na služby | Linky na pojmy |
|---|---|---|
| Školení základů HTML a CSS | Tvorba webových stránek, Školení práce s WordPressem | HTML, CSS, Frontend, Responzivní design |
| Školení práce s WordPressem | Tvorba webu na WordPress, Školení základů HTML a CSS | WordPress, CMS, Šablona, Plugin |
| Školení práce s Moodlem | Tvorba e-learningu na Moodle | Moodle, LMS, CMS |
| Individuální školení na míru | Školení práce s WordPressem, Školení práce s Moodlem, Školení základů HTML a CSS | WordPress, CMS, HTML, CSS, Moodle |
| Technická konzultace k webu nebo e-shopu | Konzultace k výběru technologie a dodavatele, Bezpečnostní audit webu | WordPress, CMS, Webhosting, SEO, Framework |
| Kontrola cenové nabídky od jiného dodavatele | Konzultace k výběru technologie a dodavatele, Revize zadání a poptávky na web | CMS, WordPress, Framework |
| Revize zadání a poptávky na web | Konzultace k výběru technologie a dodavatele, Technická konzultace k webu nebo e-shopu | CMS, Framework, UX, UI |
| Nezávislý technický posudek webu (second opinion) | Bezpečnostní audit webu, Technická konzultace k webu nebo e-shopu | SEO, PageSpeed, Bezpečnostní audit, Zranitelnost, Optimalizace rychlosti webu |
| Konzultace k výběru technologie a dodavatele | Kontrola cenové nabídky od jiného dodavatele, Revize zadání a poptávky na web, Technická konzultace k webu nebo e-shopu | CMS, WordPress, Framework, Laravel |

---

## 2) Tabulka — Slovník → linky

### 1. Domény a DNS

| Zdroj (pojem) | Linky na služby | Linky na pojmy |
|---|---|---|
| Doména | Registrace domény, Správa a prodlužování domén, Převod (transfer) domény, Webhosting | DNS, Nameserver, Registrátor domény, A záznam, MX záznam, SSL/TLS certifikát |
| Registrace domény | Registrace domény, Správa a prodlužování domén | Doména, Registrátor domény, Nameserver, DNS, Propagace DNS |
| Prodloužení domény | Správa a prodlužování domén | Doména, Registrátor domény |
| Transfer (převod) domény | Převod (transfer) domény, Správa a prodlužování domén | Doména, Registrátor domény, Nameserver, Propagace DNS |
| Registrátor domény | Registrace domény, Správa a prodlužování domén | Doména, DNS, Nameserver, Transfer (převod) domény |
| DNS | Registrace domény, Webhosting, Nastavení e-mailové doručitelnosti (SPF, DKIM, DMARC) | Doména, Nameserver, A záznam, MX záznam, CNAME záznam, TXT záznam, Propagace DNS |
| Nameserver | Registrace domény, Webhosting | DNS, Doména, A záznam, Propagace DNS, NS záznam |
| Propagace DNS | Registrace domény, Migrace webu na nový hosting | DNS, Nameserver, A záznam, Migrace |
| DNS záznamy | Registrace domény, Nastavení e-mailové doručitelnosti (SPF, DKIM, DMARC) | A záznam, AAAA záznam, CNAME záznam, MX záznam, TXT záznam, NS záznam, SOA záznam, PTR záznam (reverzní DNS) |
| A záznam | Registrace domény, Webhosting | DNS, DNS záznamy, IP adresa, Nameserver, AAAA záznam |
| AAAA záznam | Registrace domény, Webhosting | DNS, DNS záznamy, IP adresa, A záznam |
| CNAME záznam | Registrace domény | DNS, DNS záznamy, A záznam, Doména |
| MX záznam | Registrace domény, Nastavení e-mailové doručitelnosti (SPF, DKIM, DMARC) | DNS, DNS záznamy, SMTP, Poštovní server |
| TXT záznam | Nastavení e-mailové doručitelnosti (SPF, DKIM, DMARC) | DNS, DNS záznamy, SPF, DKIM, DMARC |
| NS záznam | Registrace domény | DNS, DNS záznamy, Nameserver |
| SOA záznam | Registrace domény | DNS, DNS záznamy, Nameserver |
| PTR záznam (reverzní DNS) | Nastavení e-mailové doručitelnosti (SPF, DKIM, DMARC), Správa serveru | DNS, DNS záznamy, IP adresa, Reverzní DNS (rDNS), Doručitelnost e-mailů |

### 2. Webhosting a servery

| Zdroj (pojem) | Linky na služby | Linky na pojmy |
|---|---|---|
| Webhosting | Webhosting, Správa serveru | Sdílený hosting, Managed hosting, Diskový prostor, Přenesená data (traffic), Uptime, FTP, PHP-FPM |
| Sdílený hosting | Webhosting | Webhosting, Managed hosting, Diskový prostor |
| Managed hosting | Webhosting, Správa serveru | Webhosting, Sdílený hosting, VPS |
| Diskový prostor | Webhosting | Webhosting, Záloha (backup) |
| Přenesená data (traffic) | Webhosting | Webhosting, CDN, Cache (mezipaměť) |
| Uptime | Webhosting, Serverhosting (pronájem serveru) | Datové centrum, Load balancing, Logy |
| Serverhosting | Serverhosting (pronájem serveru), Správa serveru | VPS, Dedikovaný server, Cloudový hosting, Datové centrum |
| VPS | Serverhosting (pronájem serveru), Správa serveru | Serverhosting, Dedikovaný server, Cloudový hosting, Webový server (Apache, Nginx) |
| Dedikovaný server | Serverhosting (pronájem serveru), Správa serveru | VPS, Cloudový hosting, Datové centrum |
| Cloudový hosting | Serverhosting (pronájem serveru), Webhosting | VPS, Dedikovaný server, Load balancing |
| Datové centrum | Serverhosting (pronájem serveru) | Uptime, Load balancing, IP adresa |
| Load balancing | Serverhosting (pronájem serveru), Správa serveru | VPS, Webový server (Apache, Nginx), Uptime |
| Webový server (Apache, Nginx) | Správa serveru | PHP-FPM, HTTP, HTTPS, SSL/TLS certifikát, Cache (mezipaměť) |
| PHP-FPM | Webhosting, Správa serveru | PHP, Webový server (Apache, Nginx) |
| Cron (cron job) | Správa serveru | SSH, Webový server (Apache, Nginx), Logy |
| FTP | Webhosting | SFTP, SSH |
| SFTP | Webhosting | FTP, SSH |
| SSH | Správa serveru | FTP, SFTP, Cron (cron job) |
| CDN | Optimalizace rychlosti webu | Cache (mezipaměť), Komprese, Lazy loading, PageSpeed |
| IP adresa | Serverhosting (pronájem serveru), Registrace domény | A záznam, AAAA záznam, Reverzní DNS (rDNS), DNS |

### 3. E-maily a doručitelnost

| Zdroj (pojem) | Linky na služby | Linky na pojmy |
|---|---|---|
| E-mailová schránka | Zřízení a správa e-mailových schránek | E-mailový alias, IMAP, POP3, SMTP, Poštovní server, MX záznam |
| E-mailový alias | Zřízení a správa e-mailových schránek | E-mailová schránka, Catch-all schránka |
| Catch-all schránka | Zřízení a správa e-mailových schránek | E-mailová schránka, E-mailový alias, Spam |
| Autoresponder | Zřízení a správa e-mailových schránek | E-mailová schránka, SMTP |
| Poštovní server | Nastavení e-mailové doručitelnosti (SPF, DKIM, DMARC), Správa serveru | SMTP, IMAP, POP3, MX záznam |
| SMTP | Nastavení e-mailové doručitelnosti (SPF, DKIM, DMARC) | IMAP, POP3, Poštovní server, MX záznam |
| IMAP | Zřízení a správa e-mailových schránek | POP3, SMTP, E-mailová schránka, Poštovní server |
| POP3 | Zřízení a správa e-mailových schránek | IMAP, SMTP, E-mailová schránka |
| Doručitelnost e-mailů | Nastavení e-mailové doručitelnosti (SPF, DKIM, DMARC), Audit doručitelnosti e-mailů a spam score | SPF, DKIM, DMARC, Reputace odesílatele, Spam score (spamminess), Blacklist |
| SPF | Nastavení e-mailové doručitelnosti (SPF, DKIM, DMARC) | DKIM, DMARC, BIMI, TXT záznam, Doručitelnost e-mailů |
| DKIM | Nastavení e-mailové doručitelnosti (SPF, DKIM, DMARC) | SPF, DMARC, BIMI, TXT záznam, Doručitelnost e-mailů |
| DMARC | Nastavení e-mailové doručitelnosti (SPF, DKIM, DMARC) | SPF, DKIM, BIMI, TXT záznam, Doručitelnost e-mailů |
| BIMI | Nastavení e-mailové doručitelnosti (SPF, DKIM, DMARC) | SPF, DKIM, DMARC, TXT záznam, Reputace odesílatele |
| Reverzní DNS (rDNS) | Nastavení e-mailové doručitelnosti (SPF, DKIM, DMARC), Správa serveru | PTR záznam (reverzní DNS), IP adresa, DNS, Doručitelnost e-mailů |
| Reputace odesílatele | Audit doručitelnosti e-mailů a spam score, Nastavení e-mailové doručitelnosti (SPF, DKIM, DMARC) | Doručitelnost e-mailů, Spam score (spamminess), Blacklist, Whitelist |
| Spam | Audit doručitelnosti e-mailů a spam score | Spam score (spamminess), Blacklist, Whitelist, Greylisting, Reputace odesílatele |
| Spam score (spamminess) | Audit doručitelnosti e-mailů a spam score | Spam, Doručitelnost e-mailů, Reputace odesílatele, Blacklist |
| Blacklist | Řešení zařazení domény na blacklist, Audit doručitelnosti e-mailů a spam score | Whitelist, Reputace odesílatele, Spam, Spam score (spamminess) |
| Whitelist | Audit doručitelnosti e-mailů a spam score | Blacklist, Reputace odesílatele, Greylisting |
| Greylisting | Nastavení e-mailové doručitelnosti (SPF, DKIM, DMARC) | Spam, Whitelist, Doručitelnost e-mailů |
| Bounce (vrácený e-mail) | Audit doručitelnosti e-mailů a spam score | Doručitelnost e-mailů, SMTP, Reputace odesílatele, Spam |
| Hromadný e-mail (mailing) | Nastavení e-mailové doručitelnosti (SPF, DKIM, DMARC), Audit doručitelnosti e-mailů a spam score | Doručitelnost e-mailů, SPF, DKIM, DMARC, Reputace odesílatele |

### 4. Vývoj webů, aplikací a e-shopů

| Zdroj (pojem) | Linky na služby | Linky na pojmy |
|---|---|---|
| Frontend | Tvorba webových stránek, Převedení grafických návrhů do HTML a CSS | Backend, HTML, CSS, JavaScript, Responzivní design, UX, UI |
| HTML | Tvorba webových stránek, Převedení grafických návrhů do HTML a CSS, Školení základů HTML a CSS | CSS, JavaScript, Frontend |
| CSS | Tvorba webových stránek, Převedení grafických návrhů do HTML a CSS, Školení základů HTML a CSS | HTML, JavaScript, Frontend, Responzivní design, Mobile-first |
| JavaScript | Tvorba webových stránek, Tvorba webové aplikace | HTML, CSS, Frontend, REST API |
| Responzivní design | Tvorba webových stránek, Tvorba e-shopu, Redesign webu | Mobile-first, Frontend, CSS, UX |
| Mobile-first | Tvorba webových stránek, Redesign webu | Responzivní design, CSS, UX |
| Backend | Tvorba webové aplikace, Webová aplikace na míru (PHP, Laravel) | Frontend, PHP, Laravel, Databáze, API, Framework |
| PHP | Webová aplikace na míru (PHP, Laravel), Tvorba webu na WordPress | Laravel, Composer, Framework, Backend |
| Laravel | Webová aplikace na míru (PHP, Laravel), Tvorba webové aplikace | PHP, Composer, Framework, Backend, Databáze, MySQL |
| Framework | Webová aplikace na míru (PHP, Laravel), Tvorba webové aplikace | Laravel, PHP, Knihovna (library), Backend, Frontend |
| Composer | Webová aplikace na míru (PHP, Laravel) | PHP, Laravel, Knihovna (library), Open source |
| Databáze | Webová aplikace na míru (PHP, Laravel), Tvorba webové aplikace, Tvorba e-shopu | MySQL, SQL, Backend, Záloha (backup) |
| MySQL | Webová aplikace na míru (PHP, Laravel), Webhosting | Databáze, SQL, PHP, Laravel |
| SQL | Webová aplikace na míru (PHP, Laravel) | Databáze, MySQL |
| API | Napojení API a služeb třetích stran, Tvorba webové aplikace | REST API, JSON, Webhook, HTTP, HTTPS |
| REST API | Napojení API a služeb třetích stran | API, JSON, Webhook, HTTP, HTTPS |
| JSON | Napojení API a služeb třetích stran, Webová aplikace na míru (PHP, Laravel) | API, REST API, Webhook |
| Webhook | Napojení API a služeb třetích stran, Tvorba a správa XML feedů pro zbožové srovnávače | API, REST API, JSON |
| Verzovací systém | Webová aplikace na míru (PHP, Laravel), Programátorské práce a servisní zásahy na míru | Git, Vývojové prostředí, Deployment (nasazení), Open source |
| Git | Webová aplikace na míru (PHP, Laravel), Programátorské práce a servisní zásahy na míru | Verzovací systém, Vývojové prostředí, Deployment (nasazení), Open source |
| HTTP | Tvorba webových stránek | HTTPS, HTTP stavové kódy (404, 500 a další), URL, SSL/TLS certifikát, Webový server (Apache, Nginx) |
| HTTPS | Aktualizace a zabezpečení webu | HTTP, SSL/TLS certifikát, Šifrování, URL |
| HTTP stavové kódy (404, 500 a další) | Optimalizace rychlosti webu, Bezpečnostní audit webu | HTTP, Přesměrování (redirect), Webový server (Apache, Nginx), Logy |
| URL | Tvorba webových stránek | Doména, HTTP, HTTPS, Přesměrování (redirect) |
| Cookie | Tvorba webových stránek, Tvorba e-shopu | Session, GDPR, HTTPS |
| Session | Tvorba webové aplikace, Webová aplikace na míru (PHP, Laravel) | Cookie, Backend, PHP |
| Přesměrování (redirect) | Migrace webu na nový hosting, Optimalizace rychlosti webu | HTTP stavové kódy (404, 500 a další), URL, HTTPS |
| Zdrojový kód webu | Tvorba webových stránek | HTML, CSS, JavaScript, Frontend, Backend, Open source |
| Fullstack | Tvorba webové aplikace, Webová aplikace na míru (PHP, Laravel) | Frontend, Backend, Framework, Laravel, PHP |
| Knihovna (library) | Webová aplikace na míru (PHP, Laravel) | Framework, Composer, Open source |
| Open source | Tvorba webu na WordPress | WordPress, Moodle, Knihovna (library), Git |
| UX | Tvorba webových stránek, Redesign webu | UI, Wireframe, Prototyp, Responzivní design |
| UI | Tvorba webových stránek, Redesign webu | UX, Wireframe, Prototyp, Responzivní design |
| Wireframe | Tvorba webových stránek, Redesign webu | UX, UI, Prototyp |
| Prototyp | Tvorba webových stránek, Redesign webu, Tvorba webové aplikace | UX, UI, Wireframe |
| Webová aplikace | Tvorba webové aplikace, Webová aplikace na míru (PHP, Laravel) | Backend, Frontend, Framework, Laravel, PHP, Databáze |
| Landing page | Tvorba landing page | Responzivní design, SEO, PageSpeed, UX |
| Platební brána | Napojení platební brány, Tvorba e-shopu | API, REST API, Webhook, SSL/TLS certifikát |
| XML feed | Tvorba a správa XML feedů pro zbožové srovnávače | Zbožové srovnávače, API, Webhook |
| Zbožové srovnávače | Tvorba a správa XML feedů pro zbožové srovnávače | XML feed, SEO |

### 5. WordPress, CMS a e-learning

| Zdroj (pojem) | Linky na služby | Linky na pojmy |
|---|---|---|
| CMS | Tvorba webu na WordPress, Tvorba webových stránek | WordPress, Šablona (template), Plugin (rozšíření), Modul, LMS (systém pro řízení výuky), Moodle |
| WordPress | Tvorba webu na WordPress, Školení práce s WordPressem, Aktualizace a zabezpečení webu | CMS, Šablona (template), Plugin (rozšíření), PHP, Open source |
| Šablona (template) | Tvorba webu na WordPress | WordPress, CMS, Plugin (rozšíření), UI, Responzivní design |
| Plugin (rozšíření) | Tvorba webu na WordPress, Aktualizace a zabezpečení webu | WordPress, CMS, Modul, Šablona (template) |
| Modul | Tvorba e-learningu na Moodle, Webová aplikace na míru (PHP, Laravel) | Plugin (rozšíření), CMS, Moodle, LMS (systém pro řízení výuky) |
| LMS (systém pro řízení výuky) | Tvorba e-learningu na Moodle, Školení práce s Moodlem | Moodle, CMS |
| Moodle | Tvorba e-learningu na Moodle, Školení práce s Moodlem | LMS (systém pro řízení výuky), CMS, PHP, Open source |

### 6. Provoz, údržba a bezpečnost

| Zdroj (pojem) | Linky na služby | Linky na pojmy |
|---|---|---|
| Vývojové prostředí | Webová aplikace na míru (PHP, Laravel), Programátorské práce a servisní zásahy na míru | Lokální prostředí, Staging, Produkční prostředí, Docker, Git |
| Lokální prostředí | Programátorské práce a servisní zásahy na míru | Vývojové prostředí, Staging, Docker |
| Staging | Programátorské práce a servisní zásahy na míru, Správa a údržba webu | Vývojové prostředí, Produkční prostředí, Deployment (nasazení) |
| Produkční prostředí | Správa a údržba webu | Vývojové prostředí, Staging, Deployment (nasazení), Logy |
| Docker | Webová aplikace na míru (PHP, Laravel), Programátorské práce a servisní zásahy na míru | Vývojové prostředí, Lokální prostředí, Deployment (nasazení) |
| Deployment (nasazení) | Programátorské práce a servisní zásahy na míru, Migrace webu na nový hosting | Git, Verzovací systém, Vývojové prostředí, Staging, Produkční prostředí |
| Migrace | Migrace webu na nový hosting, Migrace e-shopu | Deployment (nasazení), Záloha (backup), DNS, Propagace DNS |
| Záloha (backup) | Zálohování a obnova dat, Správa a údržba webu | Databáze, Diskový prostor, Migrace |
| Logy | Správa serveru, Technická podpora | Webový server (Apache, Nginx), Bezpečnostní audit, Vývojové prostředí |
| SSL/TLS certifikát | Aktualizace a zabezpečení webu, Webhosting | HTTPS, Šifrování, Doména, Webový server (Apache, Nginx) |
| Šifrování | Aktualizace a zabezpečení webu | SSL/TLS certifikát, HTTPS, Dvoufaktorové ověření (2FA) |
| Firewall | Správa serveru, Aktualizace a zabezpečení webu | Bezpečnostní audit, DDoS útok, Malware |
| Dvoufaktorové ověření (2FA) | Aktualizace a zabezpečení webu | Šifrování, CAPTCHA |
| CAPTCHA | Aktualizace a zabezpečení webu | Dvoufaktorové ověření (2FA), Spam, Malware |
| Malware | Bezpečnostní audit webu, Aktualizace a zabezpečení webu | Zranitelnost, Firewall, DDoS útok |
| DDoS útok | Bezpečnostní audit webu, Správa serveru | Firewall, Malware, Zranitelnost, Uptime |
| Zranitelnost | Bezpečnostní audit webu, Aktualizace a zabezpečení webu | Malware, Firewall, Bezpečnostní audit |
| Bezpečnostní audit | Bezpečnostní audit webu | Zranitelnost, Malware, Firewall, GDPR |
| GDPR | Aktualizace a zabezpečení webu, Tvorba e-shopu | Cookie, Šifrování, SSL/TLS certifikát, Bezpečnostní audit |

### 7. SEO a výkon webu

| Zdroj (pojem) | Linky na služby | Linky na pojmy |
|---|---|---|
| SEO | Optimalizace rychlosti webu, Tvorba webových stránek | Indexace, Sitemap.xml, robots.txt, Meta tagy, Meta description, Title, Nadpisy H1–H6, Strukturovaná data |
| Indexace | Optimalizace rychlosti webu | SEO, Sitemap.xml, robots.txt |
| Sitemap.xml | Optimalizace rychlosti webu | SEO, Indexace, robots.txt |
| robots.txt | Optimalizace rychlosti webu | SEO, Indexace, Sitemap.xml |
| Meta tagy | Tvorba webových stránek, Optimalizace rychlosti webu | SEO, Meta description, Title |
| Meta description | Tvorba webových stránek | SEO, Meta tagy, Title |
| Title | Tvorba webových stránek | SEO, Meta tagy, Meta description |
| Nadpisy H1–H6 | Tvorba webových stránek | SEO, HTML, Meta tagy |
| Strukturovaná data | Tvorba webových stránek, Optimalizace rychlosti webu | SEO, JSON, HTML |
| Webová analytika | Tvorba webových stránek | SEO, Cookie, GDPR |
| Optimalizace rychlosti webu | Optimalizace rychlosti webu | PageSpeed, Core Web Vitals, Cache (mezipaměť), Komprese, Lazy loading, CDN |
| PageSpeed | Optimalizace rychlosti webu | Core Web Vitals, Cache (mezipaměť), Komprese, Lazy loading |
| Core Web Vitals | Optimalizace rychlosti webu | PageSpeed, Cache (mezipaměť), Lazy loading |
| Cache (mezipaměť) | Optimalizace rychlosti webu, Webhosting | PageSpeed, Komprese, CDN |
| Komprese | Optimalizace rychlosti webu | Cache (mezipaměť), PageSpeed, CDN |
| Lazy loading | Optimalizace rychlosti webu | PageSpeed, Core Web Vitals, Cache (mezipaměť) |
