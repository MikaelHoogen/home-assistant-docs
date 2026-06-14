# Repo-struktur

Den här sidan beskriver hur kod och dokumentation bör organiseras.

## Kodrepo

```text
home-assistant/
  packages/
  dashboards/
  esphome/
  appdaemon/
```

## Dokumentationsrepo

```text
home-assistant-docs/
  mkdocs.yml
  docs/
    home-assistant/
    energi/
    hydromet-integration/
    drift/
    beslut/
```

## Princip

Koden bor där den körs eller förvaltas. Dokumentationen bor här.

## När ny dokumentation behövs

Ny dokumentation bör skapas när en ändring påverkar:

- flera filer eller packages
- viktiga entiteter
- energistyrning
- dashboards
- felsökning
- Hydromet-kopplingen
- framtida underhåll
