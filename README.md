## DAT216 - Design and implementation of graphical interfaces

Designkurs son ingår i programmet Informationsteknik på Chalmers tekniska högskola.

### Syfte me kursen

I princip alla datorprogram som ska användas av människor använder sig idag av grafiska gränssnitt. Att utveckla dessa innebär inte bara en förståelse av hur dessa kan implementeras utan även att man har en förståelse för de som ska använda programmen. Kursen ger praktisk erfarenhet i dessa två aspekter genom ett grupprojekt som ger en fördjupning av delmomentet kring grafiska komponenter från kursen Objektorienterad programvaruutveckling. Projektets mål är att utveckla en applikation för en specifik användargrupp och att genom att låta dessa testa programmet iterativt förbättra det.


### Installation av imat26 projektet

1. Öppna IntelliJ. Om du är på startsidan och inte har några projekt uppe, klicka på "Check out from Version Control."
2. Om du har projekt uppe, klicka på VCS längst upp i menyfältet och sedan "Check out from Version Control."
3. Välj "GitHub". 
4. Logga in i ditt konto/Ange alla nödvändiga uppgifter
5. För Git Repository URL kan ni välja "https://github.com/Tithera/DAT216-Design-and-implementation-of-graphical-interfaces".
6. Välj var ni vill ha projektet lokalt på datorn.
7. Clone!
8. Kompilera projektet en gång via ⇧⌘F9

Om det blir felmeddelanden kan det bero på några saker som självklart går att åtgärda.
a) Projektet har inte tillgång till the framework som kom med. Fixa det genom att gå till File> Project Structure> Problems. Där står det biblioteket inte har lagts till och då är det bara att fixa det genom att klicka på Fix it> add to dependencies> imat26

b) Projektet känner inte igen resursmappen, så man måste manuellt ange det själv. File> Project Structure> Modules. Klicka på/Markera mappen resources och ange den som en resursmapp genom att klicka på Resources (med pengar som ikon) (Mark as:).

c) IMatDataHandler kommer inte åt databasen på grund av dålig backend. Åtgärda det genom att läsa http://www.ixdcth.se/courses/2016/dat216/backend (under installation med imat.zip).
