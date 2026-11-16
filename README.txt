MOJA PENAZENKA – VERZIA SO ZALOHOU A OBNOVOU

Nahraj do koreňového priečinka GitHub repozitára tieto tri súbory:
- index.html
- manifest.webmanifest
- sw.js

Priečinok icons ponechaj v repozitári bez zmeny (icon-192.png a icon-512.png).

NOVE FUNKCIE:
- V peňaženke pribudne sekcia „Záloha a prenos“.
- „Stiahnuť zálohu“ vytvorí JSON súbor, ktorý obsahuje iba ZAŠIFROVANÉ finančné záznamy a údaje potrebné na ich obnovenie.
- „Obnoviť zo zálohy“ načíta záložný JSON, vyžiada pôvodný PIN a pred prepísaním údajov zobrazí potvrdenie.
- Na obnovenie v inom prehliadači najprv otvor aplikáciu, nastav/odomkni ju a potom v sekcii Záloha a prenos zvoľ „Obnoviť zo zálohy“. Zadaj PIN použitý pri vytvorení zálohy.

DÔLEŽITÉ:
- Záloha je šifrovaná. Bez pôvodného PIN-u ju nemožno obnoviť.
- Obnovenie nahradí údaje v aktuálnom prehliadači údajmi zo zálohy.
- Zálohu si ulož na bezpečné miesto; neposielaj ju verejne.
- Pred každou väčšou zmenou alebo pravidelne si vytvor novú zálohu.
- Údaje sa automaticky nesynchronizujú medzi prehliadačmi.
- Aplikácia používa lokálne úložisko prehliadača; vymazanie dát stránky môže odstrániť lokálnu kópiu.

Po nahratí počkaj na dokončenie GitHub Pages a obnov aplikáciu. Ak sa zobrazí stará verzia, zavri kartu a otvor odkaz znova. Nemaž údaje stránky, pokiaľ nemáš bezpečne uloženú zálohu.
