MOJA PEŇAŽENKA – OPRAVENÁ VERZIA

Nahraj do koreňového priečinka GitHub repozitára tieto súbory: index.html, manifest.webmanifest a sw.js. README.txt je návod.

Dôležité: priečinok icons ponechaj tak, ako je, vrátane icon-192.png a icon-512.png.

Opravy: po úspešnom odomknutí sa obnoví hlavná obrazovka; pri každom pokuse sa znovu načíta stav nastavenia PIN-u; service worker má novú verziu cache.

Zabezpečenie: AES-GCM 256-bit, kľúč odvodený z PIN-u cez PBKDF2-SHA-256. PIN sa neukladá. Automatické uzamknutie po 5 minútach.

Upozornenie: údaje sú uložené iba v tomto prehliadači a zariadení. Vymazanie dát prehliadača ich môže odstrániť. Bez PIN-u ich nemožno dešifrovať. Pred používaním na dôležité financie odporúčam doplniť a otestovať export a obnovu zálohy.

Po nahratí počkaj na dokončenie GitHub Pages a obnov stránku. Ak sa stále zobrazuje stará verzia, otvor stránku v súkromnom okne alebo vymaž údaje stránky, ale pozor: vymazanie údajov stránky odstráni aj lokálne uložené finančné záznamy.
