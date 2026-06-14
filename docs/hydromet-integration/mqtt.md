# MQTT för Hydromet i Home Assistant

Den här sidan dokumenterar hur Home Assistant tar emot Hydromet-data via MQTT.

## Syfte

MQTT används som brygga mellan loggrar, mätare, analyskomponenter och Home Assistant.

## Att dokumentera

- topics som Home Assistant prenumererar på
- payload-format
- vilka MQTT-sensorer som skapas i HA
- vilka topics som är rådata och vilka som är beräknade värden
- retain/QoS där det är relevant

## Principer

- Händelser, till exempel regntippar, bör inte behandlas som vanliga statusvärden utan tydlig tidsstämpel.
- Status och diagnostik kan hanteras separat från mätdata.
- Rådata bör kunna sparas även om Home Assistant startar om.
