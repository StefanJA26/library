# JUnit & Byggverktyg

## Inlämningsuppgift 2

### Utvecklingsverktyg HT-26
<br></br>
I denna uppgift kommer du att arbeta med enhetstestning i Java med hjälp av JUnit 6, samt använda byggverktyg som Maven (och för VG även Gradle).

Syftet är att du ska förstå hur testning integreras i utvecklingsprocessen och hur man automatiserar bygg-, test- och paketeringssteg i ett Java-projekt.

Du kommer att få ett färdigt kodunderlag som ska struktureras i ett nytt Maven-projekt, och därefter implementera och köra tester för att säkerställa att programmet fungerar som förväntat.
<br></br>
### Betygskriterier

#### För betyget G

- Ni ska skriva klart tester markerade med //G i testklasserna.
- Testerna måste lyckas.
- Testerna måste testa korrekt och rätt sak.
- Maven måste fungera för compile, test, skapa javadoc och packaging och köra jarfilen som ni har skapat

#### För betyget VG

Alla krav för G, samt:
- Ni ska skriva tester markerade med //VG i test klasserna.
- Tester måste lyckas och vara korrekta.
- Använd ett ytterligare byggverktyg utöver maven (Gradle), automatisera compile, run, test, javadoc och packning.
- Ni måste lämna in uppgiften innan deadline:  klockan 23:59
<br></br>
### Inlämning

#### För G

Ni måste skicka en github länk som innehåller:
- Hela projektet Library (med target-katalogen som innehåller classes, javadoc, generated sources, test sources, reports och jar-filen)
- Om target-katalogen inte ligger i repositories, kommer inlämningen att skickas tillbaka till er för komplettering

#### En textfil.
Textfilen måste innehålla alla Maven Goals som du har använt och en förklaring av vad var och en av dem gör:
- clean
- compile
- javadoc
- testning
- paketering

#### För VG
För betyget Väl Godkänd (VG) krävs att ni uppfyller alla krav för Godkänt (G), samt att ni lägger till följande leveranser:
- En till github länk som innehåller: Hela gradle projektet

#### En textfil
- Textfilen måste innehålla alla Gradle kommandon som du har använt och en förklaring av vad var och en av dem gör.
- Build-katalogen som innehåller classes, docs, generated, reports och test reports
- Om build-katalogen inte ligger i repositories, kommer inlämningen att skickas tillbaka till er för komplettering
<br></br>
Nov 21 2026
