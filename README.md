# Home Assistant-dokumentation

Det här repot innehåller MkDocs-dokumentation för Home Assistant-systemet på Sännesholma.

## Syfte

Dokumentationen ska beskriva hur systemet sitter ihop, vilka principer som gäller och hur viktiga delar felsöks.

Den ska inte ersätta YAML-koden i `MikaelHoogen/home-assistant`, utan fungera som operatörsmanual och arkitekturkarta.

## Lokal körning

```bash
pip install -r requirements.txt
mkdocs serve
```

Bygg statisk sajt:

```bash
mkdocs build
```

## Huvuddelar

- Home Assistant-struktur
- Energi och elpris
- Hydromet-integration i Home Assistant
- Drift och felsökning
- Beslutslogg
