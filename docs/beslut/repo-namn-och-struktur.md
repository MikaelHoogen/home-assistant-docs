# Repo-namn och struktur

## Beslut just nu

Byt inte namn på `home-assistant` just nu.

## Bakgrund

Repot heter `home-assistant`, vilket är tydligt för HA-konfiguration men kan kännas snävt om repot även innehåller ESPHome, AppDaemon, Hydromet-kopplingar och dokumentation.

## Nuvarande väg

- Behåll `home-assistant` som kodrepo.
- Använd `home-assistant-docs` för dokumentation av Home Assistant-systemet.
- Dokumentera Hydromet här endast utifrån Home Assistant-integrationen.
- Avvakta separat Hydromet-repo tills nyttan tydligt överstiger krånglet.

## Omprövas när

- Hydromet-delen växer kraftigt.
- AppDaemon/ESPHome-kod blir mer fristående från Home Assistant.
- dokumentationen behöver delas upp tydligare.
- separat CI/test/deploy behövs för Hydromet.
