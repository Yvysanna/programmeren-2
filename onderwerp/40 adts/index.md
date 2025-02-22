# Week 4: ADTs

Deze week gaat over *abstract data types* ofwel ADTs. In deze inleiding leggen we uit wat een ADT is zonder voorbeelden te geven. Het kan goed zijn dat je de uitleg daardoor niet direct begrijpt. Het is daarom zinvol de uitleg later in de week nogmaals te lezen en te checken of je het dan wel begrijpt.

Een abstract datatype beschrijft een datatype vanuit de **operaties** die je erop moet kunnen uitvoeren. Als je deze operaties en het bijbehorende gedrag vastlegt, kun je al redeneren over de mogelijkheden die zo'n datatype je biedt als programmeur. Nog sterker, als je de operaties definieert dan kun je in principe al code schrijven die gebruik maakt van zo'n datatype, zonder dat je verdere afspraken hoeft te maken over de details. Een ADT is dus een afspraak of **contract** over de mogelijkheden die het datatype biedt.

De details van de implementatie worden in het contract (of de beschrijving) van een ADT geheel weggelaten. Men kan in principe een ADT implementeren op een willekeurige manier, zolang alle verplichte operaties maar ondersteund worden. In de praktijk zullen ADTs vaak op een specifieke manier geïmplementeerd worden, omdat men heeft ontdekt dat de operaties op één manier zeer efficiënt kunnen werken, terwijl de ADT als deze op een andere manier wordt geïmplementeerd nodeloos traag is of andere beperkingen kent.

## Leerdoelen

Je gaat deze week:

- Goed begrijpen wat een ADT is
- Enkele basisvoorbeelden van ADT's leren kennen
- Ervaren hoe je classes en objecten kunt gebruiken voor het implementeren van ADT's

## Lesstof

Uit het boek lees je hoofdstuk 2 tot je het zo goed mogelijk begrijpt. Paragraaf 2.6 over unit testing mag je overslaan, want wij gebruiken een ander framework om unit tests te programmeren.

- 2.1 Overview
- 2.2 ADTs
- 2.3 ADTs and objects
- 2.4 Dataset
- 2.5 Rational
- 2.6 (overslaan, dit komt op een andere manier terug in de opdrachten)

## Puntentelling

- Twee implementaties: 2 punten (indien helemaal gedaan)
- 21: 4 punten (volle punten indien voldoende code)
- Codekwaliteit: 4 punten
    - 4: Zeer diverse wijzigingen gedaan
    - 3: Voldoende wijzigingen gedaan met gevraagde documentatie
    - 0: Te grote screenshots, onoverzichtelijk, lastig te begrijpen
