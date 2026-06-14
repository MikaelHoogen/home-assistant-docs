# Hydromet-integration

Den här delen beskriver hur Hydromet-data används i Home Assistant.

## Avgränsning

Hydromet är mätprogrammet för regn, nivå, flöde och markfukt.

Home Assistant är visualisering, lokal integration och eventuell automation.

Den här dokumentationen beskriver bara Home Assistant-sidan:

- MQTT-sensorer
- dashboards
- diagnostik
- status
- beroenden till AppDaemon/ESPHome där de används av HA

## Inte här

Följande hör hemma i Hydromet-dokumentationen:

- mätstrategi
- mätarval
- kalibrering
- rådatamodell
- IDF-/återkomsttidsanalys
- metodik för regn, nivå och flöde

## Viktig princip

Home Assistant får gärna visa Hydromet-data, men bör inte vara den enda långsiktiga lagringen av rådata.
