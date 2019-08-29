# Övningar - Media Queries

## Övning 1
a) Använd media queries för att ändra texten från **Company Title Inc.** till **Company**
när browserfönstret understiger 600 pixlar.

b) Lägg till att titeln ändras till **Company Title Incorporated** om fönsterstorleken
överstiger 1200 pixlar.

## Övning 2

Använd media queries för att ändra så att sidebaren uppfyller följande:
* Om storleken på fönstret är mindre än 600 pixlar ska sidebaren ändra storlek till 20% av fönstrets storlek.
* Om storleken är mindre än 400 pixlar ska sidebaren gömmas helt.

## Övning 3

a) Implementera med hjälp av media queries så att headern göms vid utskrifter.

b) Implementera med hjälp av media queries så att sidebaren göms vid utskrifter.

## Övning 4
Implementera så att sidebaren hamnar på höger sida istället för vänster om:

a) Fönstrets storlek är i porträttläge.

b) Fönstrets storlek är i porträttläge **och** bredden på fönstret är mindre än 700 pixlar.

c) Fönstrets storlek är i porträttläge **och** bredden på fönstret är mindre än 700 pixlar **eller** att fönstret är i landskapsläge, oavsett storlek på fönstret.

## Övning 5

När kommer CSS-koden i följande media queries att användas?

a) `@media (max-width: 500px) { ... }`

b) `@media all, (max-width: 500px) { ... }`

c) `@media screen and (max-width: 500px) { ... }`

d) `@media all and (max-width: 500px) { ... }`

e) `@media all and not (max-width: 500px) { ... }`

## Övning 6
Skapa en sida som ändrar bakgrundsfärg beroende på skärmstorlek mellan 500px och 1200px. Sidan ska byta mellan Röd, Orange, Gul, Grön, Cyan, Blå och Violett.

(T.ex. När sidan är < 500 pixlar är bakgrunden röd, < 600 pixlar Orange, < 700 pixlar Gul o.s.v.)

## Övning 7

Du har fått i uppdrag att skapa ett bildgalleri enligt följande specifikationer:

* 10 bilder ska visas på sidan.
* Bildernas bredd ska vara flytande.
* Om fönsterbredden är mindre än 1000px ska det visas tre bilder per rad.
* Om fönsterbredden är mindre än 700px ska det visas två bilder per rad.
* Om fönsterbredden är mindre än 500px ska det visas en bild per rad.

Implementera enligt ovanstående specifikation. Du kan själv välja vilka bilder som ska visas.

