# Workshops
## Workshop 1
Greenfoot: dit is een programma dat gebruikt wordt voor kinderen om hen Java te leren.

De terminal kun je gebruiken om commando’s uit te voeren.
PWD: waar sta je in de directory (map)
LS: List files, je ziet de files die in je huidige directory staat

Java is een programmeertaal. Deze wordt bij de belastingdienst gebruikt. Je kunt er van alles mee programmeren. Java is een generieke programmeertaal. Deze wordt ook gebruikt binnen bijvoorbeeld Android.

Normaal heb je een programmeertaal en normaal moet je die tekst zelf programmeren. Je programmacode bestaat uiteindelijk uit allemaal textfiles. Die voldoen aan allerlei structuurtjes zodat Java compiler weet hoe hij ermee om moet gaan. De java programmeertaal is niet meteen door de computer te gebruiken. De compiler zet hem om zodat de computer het wel kan gebruiken. Hier wordt ook geverifieerd dat je geen fouten in je code hebt gemaakt. Er komt dan een programma wat de computer kan uitvoeren. De Javacode kan je schrijven in een willekeurige editor, zijn er specifieke editors die precies weten wat die regels zijn voor een javacode. Je wordt zo eigenlijk geholpen met het schrijven van je code.

Greenfoot is een editor. Deze heeft een mooie grafische omgeving en een world met actors. Normaal heb je dat niet. Dit is specifiek gericht op het leren van Java dus het is wat mooier ingericht om het wat aantrekkelijker te maken. Greenfoot is eigenlijk een leeromgeving. De applicatie greenfoot is ervoor om je programmacode te editen en uit te voeren. Zij compileren het ook voor jou.

Aan de zijkant zie je classes. Als je aan het bakken bent, dan heb je een vormpje en het koekje zelf. Een class is een vormpje en objecten. In dit voorbeeld zijn de mieren de objecten. Je programmeert met classes en als het programma uitgevoerd wordt, dan wordt het uitgevoerd op basis van objecten. Je hebt een wereld en dat is eigenlijk de achtergrond. De actor is de hoofdklasse die meerdere klassen bevat. Deze programmeer je. Op runtime heb je daar objecten van en die maken het programma.

Een class kun je zien als een blauwdruk/ontwerp tekening en daarmee kunnen objecten/instances gemaakt worden. Met één ontwerptekening (van een auto) kun je daarna vele auto's maken. Met een koekjes vorm, kun je vele koekjes maken.

Je hebt in dit voorbeeld 2 klassen: world en actor. Je geeft de classes zelf een naam. Het zijn vaak zelfstandige naamwoorden.

Pheromone: het spoor wat de mieren achterlaten qua geur.

Slack kan je gebruiken net zoals mattermost

Huiswerk:
Werk de 6 tutorials door van greenfoot. Dit geeft de basisbeginselen mee van java + joy of code
Vragen noteren of stellen via slack

Java is vrijuitgebreid in het schrijven van dingen. Als je het wil leren, dan kun je het beste beginnen bij java.


` # Hier achter maak je een heading `

Github is een portaal van git repositories. Hierin kun je source code opslaan.

Een commit is een toestand van alle (in versiebeheer) files op dat moment. Je maakt als het ware een momentopname van alle files op dat moment.

We zijn begonnen met een aantal files maken op het werkstation van mijn macbook. Vervolgens hebben we een git repository aangemaakt `git init`. Vervolgens hebben we aan de git repository de files in de staging area gezet, die we willen gaan commiten `git add *`. * of naam van een file. Sterretje betekent hier alle files. Vervolgens kunnen we met `git status` wat de stand van zaken is. Vervolgens hebben we om een snapshot om van de huidige files die in staging area staan gemaakt met `git commit -m "message"`. Hiermee geeft de message weer welke wijzigen er zijn in de files die we willen committen. Als we deze wijzigingen ook op de remote git repository willen zien, dan pushen we ze daarnaar toe met `git push`. `git diff` geeft de wijzingen weer.

## 24-12-2020
SDKman (software development kit)
- Meerdere versies van Java
- Per project dat je wil developen, kan je switchen

Je hebt ook de JAVA sdk. Dit is de java software development kit. We hebben de SDK man gedownload en geinstalleerd. Daarna hebben we een java versie geinstalleerd met de SDKman.

`sdk install java 11.0.9.hs-adpt` = met behulp van `sdk` een de java versie geïnstalleerd. De editie `11.0.9.hs-adpt`.
`sdk list java` geeft overzicht van alle java edities en dit heet ook wel java identifiers. En geeft ook weer welke versies geinstalleerd zijn, en welke op dit moment in gebruik is.
`sdk current` geeft aan wat er nu (in de huidige terminal) actief is.
`java -version` geeft ook aan welke Java versie in de huidige terminal actief is.

## 07-01-2021
Indien je meerdere kolommen tegelijk wil gebruiken, dan druk je shift-control tegelijk in en vervolgens scroll je doormiddel van de pijltjestoetsen. Je kunt dan bijvoorbeeld spaties zetten of andere characters.

In teksten worden vaak commando's gebruikt om aan te geven welke gebruiker uit moet voeren.

`$` - Geeft aan normale gebruiker  
`#` - Geeft aan administrator (root user)

Maven is een build tool. Dit helpt je om de applicatie te bouwen. Aan de ene kant moeten de java files gecompileerd worden. De human readable files worden omgezet van `*.java` files naar `*.class` files.  

De java files zijn leesbaar voor developers. De class files zijn leesbaar voor de java virtual machine (jvm). Dit is een virtuele computer en ieder besturingssysteem heeft zijn eigen jvm. Op die jvm kunnen weer de standaard gecompileerde java classes draaien. 
