# Dotazník nového zaměstnance

Jednostránkový webový formulář (čeština + další jazyky přepínané tlačítky) pro sběr údajů od nového zaměstnance.

## Struktura
- `index.html` – celá aplikace (HTML + inline CSS + inline JS), bez build kroku a bez závislostí.
- `DOTAZN~1.HTM` – identická kopie `index.html` (artefakt nahrání z Windows). Při změně `index.html` kopii buď nech být, nebo ji smaž; neupravuj ji zvlášť.

## Pravidla
- Uživatelský text a komentáře piš česky; zachovej překlady jazykového přepínače při přidávání/změně textů.
- Zůstaň u jednoho souboru bez frameworků a build nástrojů, pokud uživatel nepožádá jinak.
- Formulář je mobile-first (max šířka 640 px) – po úpravách ověř vzhled na úzkém displeji.
- Formulář sbírá osobní údaje – nepřidávej externí skripty ani odesílání dat na třetí strany bez výslovného zadání.

## Spuštění / test
Otevři `index.html` v prohlížeči, nebo `python3 -m http.server` v kořeni repozitáře.
