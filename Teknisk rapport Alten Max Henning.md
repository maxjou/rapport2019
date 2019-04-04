# Inledning
## Bakgrund
Alten har en avdelning, Training, som arbetar med att sälja kurser främst till andra företag men även internt samt öppna kurser. I dagsläget sker planeringen av dessa kurser i Excel-dokument som skickas fram och tillbaka mellan Training och Invoice-avdelningen. Detta arbetssätt har varit rörigt och lätt att det blivit fel. 
Training har då önskat ett system som de ska kunna använda för att planera kurser med alla kostnader och intäkter, kommunicera med Invoice samt göra budgetar.
Projektet påbörjades av lia-studenter 2017. Henning och Max blev tilldelad projektet under båda våra lia-perioder.
Efter 10 veckor av vår andra lia-period blev vi dock tilldelade ett annat projekt så vi har totalt arbetat med detta i 20 veckor.
Arbetet skedde agilt med kundmöten nästan veckovis. Under dessa möten Visade vi upp vad som gjorts och diskuterade vad vis kulle fokusera på här näst för att så snabbt som möjligt nå en första version som skulle kunna användas. 
## Mål
Målet vi hade var alltså att få ut en första version av systemet som skulle kunna användas.
För detta krävdes
* Roller. De olika användarna av systemet ska kunna göra olika saker. Invoice ska t.ex inte kunna komma åt eller kunna ändra något i kurserna förutom att lägga till "workorder number". Totalt ska det vara fem olika roller som alla har olika behörigheter.
* Säkerhet. För att implementera roller ska även säkerhetsbiten ses över och delvis bytas ut. Vi ska användas oss av Json Web Tokens.
* Budget-vy. För att systemet ska vara användbart behövdes en ny budget-vy. I denna vyn ska budgetar kunna sättas för de olika säljarna, för öppna kurser samt en total budget.
Här ska det också gå att se hur mycket av budgeten som sålts, hur mycket som är kvar samt gross margin.
* Bifoga dokument. Deta ska gå att bifoga och ladda ner dokument för varje kurstillfälle.
* Sökning på kurser. För att arbetsflödet ska gå smidigt behövs även en sökfunktion där det ska gå att söka på kursnummer, plats, kursnamn samt datumintervall.
* Testmiljö. Sätta upp en testmiljö där alla har tillgång att testa systemet och se att det fungerar som tänkt.
* Buggar.


