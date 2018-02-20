# ACPaaS UI als open-source

## Intro

In dit document schetsen we waarom we kiezen om ACPaaS UI, het [Design System](https://www.invisionapp.com/blog/guide-to-design-systems/) van Digipolis open te stellen op GitHub.  

## Van een interne source code...

Tot voor kort bewaarde Digipolis de code van ACPaaS UI op een intern Source Code systeem. Dit gaf enkele nadelen:

1. Externe ontwikkelaars moesten vaak wachten totdat ze een Digipolis account kregen.
2. Bijkomende developers gebruikte andere hun Digipolis account omdat dit gewoon sneller gaat. Zo weten we niet wie precies wat aanpast
3. Vanop afstand moest er gewerkt worden met een VPN, wat toch wat trager werkt en dikwijls storend werkte op hun dev pc's.
4. Wanneer startups, leveranciers aan een [challenge](https://antwerpen.digipolis.be/nl/opdrachten) willen meedoen, kunnen ze nog niet gaan kijken bij ACPaaS UI, dit gaat enkel wanneer ze gekozen zijn als opdrachtnemer. Dan krijgen ze pas een Digipolis account?

Teveel drempels....Hierdoor werd er snel gewerkt met locale copies van ACPaaS UI. Als er vervolgens bugfixes werden gedaan, stroomde die niet vaak terug naar de bron.

## ...naar GitHub

We verhuizen ACPaaS UI naar GitHub en werken samen met de startups. Dit past perfect in onze visie, [buy-from-startups](https://www.digipolis.be/projecten/antwerpen-koopt-it-aan-van-start-ups), moeten we de de leefwereld van hen hanteren, hier is GitHub een essentieel deel ervan. Enkele voordelen:

- De ACPaaS UI core branding staat [reeds op GitHub](https://github.com/a-ui)
- Developers kunnen van bij Digipolis of erbuiten kunnen mee bugs fixen, features toevoegen en zelfs nieuwe componenten bij creeëren.  
- Developers hoeven niet via VPN of het Wi-Fi netwerk van de Stad Antwerpen te gaan.
- Er zijn nagenoeg geen fricties, drempels, GitHub staat bij wijze van spreken steeds open op een developer pc
- Personen die willen inschrijven voor challenges kunnen op voorhand al eens proberen en ontdekken.
- Developers zijn fier op hun contributies op GitHub, ze werken mee aan een groter geheel, je ziet het ook aan hun eigen contribution diagram.
- Alles is meer op persoonlijke naam van de Developers. We weten wie welke bijdrage levert (contributors), wat er met de code gebeurt (forks). We krijgen zo ook een beter totaalbeeld van de community die eraan werkt. 


## Wat kan je hier terug vinden

Een Design system is een verzameling van herbruikbare componenten maar ook  richtlijnen. Je kan op GitHub het volgende terugvinden:

- De componenten zelf
- Documentatie over de individuele componenten
- Guidelines voor het gebruik van de componenten
- Een praktische handleiding hoe je kan contribueren aan ACPaaS UI
- Design elementen zoals Sketch files, Axure assets, SVG's, PNG's
- UI/UX patterns & guidelines


## Hoe gaan we te werk

### Code contribueren

ACPaaS UI is een mono-repository, wat wil zeggen dat alle componenten op één GitHub repository staat. Door een fork te maken en te werken met Pull Requests, kan je code (features, bug fixes, ...) aanbieden aan Digipolis. Het ACPaaS UI team (Jasper, Lieven, Tom) bekijkt en evalueeert deze code en na goedkeuring wordt zo opgenomen. 

### Nieuwe componenten

Ook hier gaat het ACPaaS UI team de PR's bekijken van nieuwe code, zo kan er gechecked worden of het kwalitatief is en/of de documentatie aanwezig is, etc.

### Issues, vragen, features

Het ACPaaS UI team volgt de community op, en samen met de andere community leden beantwoorden ze de vragen en issues. Nieuwe feautures en issues worden beheerd via [GitHub milestones](https://help.github.com/articles/about-milestones/).

Soms zijn er features of vragen waarbij we eerst bij Digipolis verder over moeten aligneren. Hiervoor bestaat er een UI/UX Guild bij Digipolis die twee-wekelijks een meeting houdt waarin deze openstaande topics besproken kunnen worden.


## To do's

- Product ownership rules opstellen
- Contribueren in visual gieten
- Nodige guidelines uitschrijven
  - contributing guidelines [via het gihub systeem](https://help.github.com/articles/setting-guidelines-for-repository-contributors/)
- Nodige assets bekijken
