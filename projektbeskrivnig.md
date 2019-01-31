# Projektbeskrivning Training

Training projektet är en applikation tänkt för att underlätta hantering av
intern kurser som Alten håller för interna och externa konsulter.  


## Problemformulering

Idag använder de diverse excell dokument för att kunna planera deras kurser. De
hanterar allt från registrering av kund till fakturering genom olika dokument.
Appen skall inte skapas från scratch utan det finns en version av applikationen
men den är inte stabil nog att använda. Under förra LIA perioden optimerade vi
appen så att den klarar av att skala. Vi kommer under den här tiden fortsätta
optimering men också implementera följande funktioner som är krav från kunden.

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
* 