# Arkitekturöversikt

Den här delen beskriver hur Home Assistant-systemet är organiserat och vilka arkitekturprinciper som styr arbetet.

## Mål

Dokumentationen ska göra det lätt att förstå:

- var olika typer av kod hör hemma
- vilka systemdelar som är beroende av varandra
- vilka delar som är stabila respektive under ombyggnad
- hur nya funktioner bör läggas till utan att skapa oreda

## Övergripande modell

Home Assistant-repot är kod- och konfigurationsrepot för det som körs i eller nära Home Assistant.

Home Assistant-docs är den läsbara systemdokumentationen.

## Viktig avgränsning

Hydromet kan på sikt bli ett bredare mätprogram. Tills vidare dokumenterar den här sajten bara Home Assistant-sidan av Hydromet: integration, visning, sensorer och drift.
