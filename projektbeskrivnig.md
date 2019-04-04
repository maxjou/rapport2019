# Projektbeskrivning Training

Training projektet är en applikation tänkt för att underlätta hantering av
kurser som Alten håller för interna och externa konsulter.  


## Problemformulering

Idag använder trainingteamet på alten diverse exceldokument för att kunna
planera deras kurser. De hanterar allt från registrering av kund till
fakturering genom olika dokument. Appen skall inte skapas från scratch utan det
finns en version av applikationen men den är inte stabil nog att använda. Under
förra LIA perioden optimerade vi appen så att den klarar av att skala. Vi kommer
under den här tiden fortsätta med optimeringen samt också implementera följande
funktioner som är krav från kunden.

* Sökfunktion
* Filtrering 
* Olika roller
    * National Manager
    * Koordinator
    * Account manager
    * Business Controller
    * Invoice-team
* Det skall gå att använda för fakturering
* Business Controller skall kunna göra forecast
* Sätta upp mål i antal kurser, omsättning och marginal, både på individnivå
  samt avdelningsnivå och ha en visuell översikt över måluppfyllnad

Utöver kravlistan skall följande punkter implementeras som är krav från
Projectowner.

* Testmiljö för applikationen
* Pipeline i jenkins
* Outlook integration
* Budget vy.
* Buggfixar

Ovanstående punkter är det som är planerat nu. Det kommer förmodligen ändras och
"tickets" kommer läggas till.

## Mål

Punkter som kommer beröras.

* Devops - då vi kommer skapa en testmiljö samt dockerisera produktionsmiljön.
  Samt få upp det i molnet med AWS -amazon web services.
* Security - vi kommer skapa en fungerande roll system och olika vyer beroende
  på vem det är som är inloggad.
* Ad sync kommer implemeneteras för outlook in i vår applikation. 
* Java backend, endpoints, logik.
* Angular frontend för applikationen.

## Önskemål om litteratur

Spring in Action verkar vara en bra bok.

## Tidsplan
Som det ser ut just nu. 

* v1 - 2 test miljö och säkerhet.
* v3 - 4 buggfixar och lanserinng av en version.
* v5- 6 outlook.

Utöver det vet vi inte i dagsläget. Kan komma att ändras beroende på vad kunden
vill att vi satsar på.


I och med att projektbeskrivnignen skall vara i direkt anknytning till rapporten
samt redovisningen kommer detta dokument uppdateras vid ett senare skede. 

