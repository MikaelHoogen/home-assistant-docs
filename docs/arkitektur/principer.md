# Principer

Den här sidan samlar principer för hur Home Assistant-systemet bör utvecklas.

## Home Assistant

- Använd modern YAML-syntax.
- Håll packages tydligt avgränsade.
- Undvik att duplicera samma logik på flera ställen.
- Dokumentera entiteter som används av flera dashboards eller automationer.

## Data

- Skilj på rådata och beräknade värden.
- Skilj på mätvärde, mottagningstid och presentation.
- Låt inte Home Assistant-historiken vara enda sanningen för långsiktigt viktiga mätdata.

## Dokumentation

- Dokumentera varför något finns, inte bara vad koden gör.
- Skriv kort hellre än perfekt.
- Uppdatera dokumentationen när viktiga beroenden ändras.
