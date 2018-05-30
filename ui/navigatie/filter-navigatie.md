# Filter navigatie

## Probleemstelling
Je hebt een pagina met een complexe tabel waarop je verschillende filters kan toepassen om de records in de tabel te verfijnen. Dit kan een simpel zoekveld zijn, alsook iets complexere auto-complete dropdowns. Vanuit de tabel kan je in elke rij doorklikken naar een detailpagina voor het desbetreffende record. Vanaf deze detailpagina kan je op verschillende manieren terug navigeren naar de pagina met de tabel.

## Geschikt voor
Sommige tabellen bevatten zoveel data records dat filtering een absolute noodzaak wordt.

## Zo te implementeren
Om terug te navigeren vanaf de detailpagina naar de tabel met filters zijn er enkele opties:
- Indien de gebruiker terug wil naar de tabel waar de filters nog actief staan, dan zal deze gebruik maken van de standaard "terug" knop van de browser. We voorzien zelf geen "Terug naar overzicht"-knop.
- Indien er ook een breadcrumb aanwezig is in de pagina, dan wordt deze enkel gebruikt om terug te navigeren naar de pagina met de tabel waar geen filters actief staan.
- Indien er op de pagina nog andere links staan die uitkomen op de pagina waar de tabel staat, dan komen die ook steeds uit op de pagina met de tabel waar geen filters actief staan.
