# Hoofdnavigatie

## Probleemstelling
Als je een basis structuur wil opzetten met navigatie kan je deze laatste op verschillende manieren weergeven. Het zal ook verschillend zijn afhankelijk van het soort, gaat het hier over een `content web sites` voor marketing doeleinden of eerder een `functionele applicatie`? 

## Geschikt voor
Dit patroon is geschikt voor de meeste content websites en functionele applicaties. Het is niet verplicht maar wel aangeraden.

## Implementation

### Meta navigation
De eerste balk aan de bovenzijde van het scherm is voorbehouden voor de meta navigatie, waar we o.a. volgende zaken op terugvinden:

- logo
- taal switch
- applicatie level search
- contact info
- app switcher
- username en avatar van de aangemelde gebruiker

Deze metanavigatie gaat de consistentie tussen alle content sites en functionele applicaties verhogen. 

### Hoofdmenu
In het hoofdmenu kan je uw applicatie specifieke navigatie aanbrengen. We bekijken de 2 situaties hier.

#### Content web sites

Content websits hebben een 2e horizontale balk die onder de meta navigatie staat. Menu items zijn horizontaal uitgelijnd naast elkaar. In mobile view staan alle menu items onder elkaar.

![Plaatsing A-logo](../assets/main-menu-content.png)

#### Functionele applicaties

Voor functionele applicaties staat het hoofdmenu links in desktop mode en onderaan in mobile mode. Je kan hier gebruik maken van iconen, die komen dan respectievelijk voor of boven de menu item tekst.
![Plaatsing A-logo](../assets/main-menu-app.png)

In desktop mode kan je een menu ook dichtklappen zodat enkel de icons over blijven.
![Plaatsing A-logo](../assets/main-menu-app-2.png)