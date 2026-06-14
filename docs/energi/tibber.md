# Tibber och elpriser

Den här sidan dokumenterar elprislogiken och pågående migrering från äldre prisentiteter.

## Nuläge

Det finns äldre logik kopplad till `electricity_price_sannesholma_2181_quarter_prices` som ska fasas ut till förmån för nyare Tibber Price Information & Ratings-logik.

## Att dokumentera

- aktiv prisentitet
- gamla entiteter som inte längre ska användas
- templates som bygger på prisdata
- dashboards som visar prisdata
- automationer eller styrsignaler som påverkas

## Risker

- gamla sensorer kan ligga kvar i templates
- dashboards kan visa gamla eller brutna värden
- logik över dygnsgräns kan skilja mellan gammal och ny källa
- prisdata för imorgon kan saknas eller publiceras senare än förväntat

## Relaterat arbete

- Inventera alla referenser till gamla quarter prices-sensorn.
- Dokumentera ny datamodell för elpris.
- Testa dashboards och templates över dygnsgräns.
