# Osobní webová stránka – Jakub Eliášek

Osobní portfolio vytvořené s důrazem na přístupnost (WCAG 2.2 AA) a přizpůsobení systémovým nastavením uživatele pomocí CSS media rules.

## Media rules

| Pravidlo | Co se mění a proč |
| :--- | :--- |
| `@media (min-width: ...)` | Přizpůsobuje rozvržení navigace a mřížku projektů od nejmenšího mobilu po široký monitor, aby nikde nevznikal vodorovný posuvník. |
| `@media (prefers-color-scheme: dark)` | Přepíná barevné proměnné stránky i posuvníky prohlížeče do tmavého schématu pro pohodlné čtení v šeru a tmě. |
| `@media (prefers-contrast: more)` | Zvyšuje kontrast na černobílé hodnoty úrovně AAA, zesiluje ohraničení, podtrhává odkazy a odstraňuje barevné přechody na pozadí. |
| `@media (prefers-reduced-motion: reduce)` | Vypíná plynulé rolování a všechny animace či přechody prvků, aby pohyb na obrazovce nezpůsoboval nevolnost. |
| `@media (prefers-reduced-transparency: reduce)` | Nahrazuje poloprůhledné pozadí karet plnou barvou a ruší rozostření pozadí pro maximální čitelnost textu. |
| `@media (forced-colors: active)` | Nastavuje systémové barvy a výrazné okraje prvků, aby zůstaly viditelné i bez stínů v režimu vysokého kontrastu Windows. | 