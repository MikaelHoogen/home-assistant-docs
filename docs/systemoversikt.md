# Systemöversikt

Den här sidan beskriver Home Assistant-systemet på en hög nivå.

## Huvudkomponenter

| Del | Roll |
|---|---|
| Home Assistant | Central integration, automation och visualisering |
| Mosquitto/MQTT | Meddelandebuss för lokala sensorer och loggrar |
| Zigbee2MQTT | Zigbee-enheter och lokal enhetshantering |
| ESPHome | Firmware och lokala noder, bland annat framtida Hydromet-loggrar |
| AppDaemon | Python-baserad logik där Home Assistant-automationer inte räcker |
| Tibber/Nordpool | Elprisdata och energirelaterade styrsignaler |
| Fronius/BYD | Solcells- och batteridata |
| Netatmo | Väderdata och eventuell jämförelsekälla för regn |
| Hydromet | Lokalt mätprogram för regn, nivå, flöde och markfukt |

## Viktiga gränser

Home Assistant är inte tänkt att vara ensam källa för all historik och analys. För mätdata som ska kunna analyseras långsiktigt, till exempel råpulser från regnmätare, bör Home Assistant främst vara visning och lokal integration.

## Principer

- Håll lokal funktion så robust som möjligt.
- Dokumentera beroenden mellan sensorer, templates och dashboards.
- Skilj på rådata, beräknade värden och presentation.
- Undvik att bygga kritisk logik på otydliga eller gamla entiteter.
