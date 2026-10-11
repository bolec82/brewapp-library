# BrewApp – knihovna receptů

Online index receptů pro aplikaci BrewApp.

- `index.json` – seznam receptů (formát 1)
- `recipes/<zdroj>/<id>.xml` – recepty v BeerXML
- `report.txt` – report generátoru (vynechané recepty, kalibrace)

## Zdroje
- **BrewDog DIY Dog** (https://www.brewdog.com/diydog), převzato z dat Punk API. Recepty patří BrewDogu,
  jsou zde jen pro nekomerční domácí vaření. Převedeno generátorem `tools/library-builder` z BrewApp;
  chybějící hodnoty (alfa chmelů, barvy sladů, výtěžnost) jsou dopočítané tak, aby seděly původní OG a IBU –
  podrobnosti v poznámkách každého receptu.
