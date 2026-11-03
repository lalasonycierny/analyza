# analyza

Zjednotenie dát z repozitárov `idos-meskanie`, `idos-grafy`, `ba-livetraffic` a `mhd-stats`
a prvotná analýza vzťahov medzi nimi.

- `analyza.py` stiahne repozitáre, vyčistí dáta, zjednotí ich do hodinovej tabuľky a spočíta korelácie.
- `.github/workflows/analyza.yml` spúšťa skript denne a výsledky ukladá do `docs/`.
- `docs/` je webová stránka (GitHub Pages) s výsledkami.

Lokálne spustenie: `python analyza.py` (výstup do `vystup/`).
