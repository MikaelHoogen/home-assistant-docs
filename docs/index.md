# Home Assistant-dokumentation

Den här dokumentationen beskriver Home Assistant-systemet för Sännesholma: struktur, viktiga integrationer, dashboards, energioptimering, drift och kopplingar till Hydromet.

Målet är inte att upprepa varje rad YAML. Målet är att förklara hur systemet sitter ihop, varför det är byggt som det är och hur det felsöks.

## Snabblänkar

- [Systemöversikt](systemoversikt.md)
- [Repo-struktur](arkitektur/repo-struktur.md)
- [Tibber och elpriser](energi/tibber.md)
- [Hydromet-integration](hydromet-integration/oversikt.md)
- [Felsökning](drift/felsokning.md)

## Huvudprincip

Home Assistant-repot innehåller konfiguration och kod som används i eller nära Home Assistant.

Hydromet beskrivs här bara utifrån Home Assistant-perspektivet: vilka data Home Assistant tar emot, visar och eventuellt använder. Själva mätstrategin och analysmetodiken hör hemma i Hydromet-dokumentationen.
