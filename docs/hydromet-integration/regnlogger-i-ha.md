# Regnlogger i Home Assistant

Den här sidan beskriver hur regnloggern syns och används i Home Assistant.

## Syfte

Home Assistant ska kunna visa aktuell status, diagnostik och beräknade värden från regnloggern.

## Exempel på data i HA

- senaste puls
- antal råpulser
- accepterade pulser
- ignorerade pulser
- total nederbörd
- rullande regnvolymer
- loggerstatus

## Viktig avgränsning

Home Assistant är inte nödvändigtvis primär lagring för råpulsserien. Rådata bör kunna lagras i en mer analysvänlig databas om projektet går vidare med TimescaleDB eller liknande.

## Dashboard

En framtida dashboard kan delas upp i:

- Live
- Grafer
- Diagnos
