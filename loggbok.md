## Sprint 1 vecka 39

### Vad jag arbetade med 
- Logga in från frontend
- Välkomssida efter inloggning 
- Privata sidor 

### Eventuella problem och hur jag löste dem
Första veckan kändes de inte som de va några stora problem då vi hade haft bra Code Along innan så kunde man kolla tillbaka hur uppbyggnaden skulle vara. Skapade components för `Loginform` och `ProtectedRoute` sedan skapade jag `page` för `LoginPage` och `WelcomePage` det gick bra, de va bara lite att lära mig om tailwind för CSS, för hade inte använt de innan.

### Samarbete och agilt arbete
Första sprintplaneringen gick bra de kändes som vi alla röstade likande och de flöt på, dock va vi bara 3 på flrsta sprintplanerignsmöte 4 personen va inte med. 
I våra Daily Scrum gick de bra, det är en enkelt grupp vi kommer alla överräns. Tyckte första retro va lite svårt att komma på en punkt till Start, Stop, Continue. Då de va första veckan om de va inget avvikande som dök upp. 

## Sprint 2 vecka 40

### Vad jag arbetade med 
- Skapa en lägga till nya produkter för Admin

### Eventuella problem och hur jag löste dem
Va lite kluven hur jag skulle style den så knappar och fälten så tydliga ut samt så den matcha resterande webshop som redan va skapade, men de gick bra gick med samma färg och likande text så de matcha. 

### Samarbete och agilt arbete
Andra sprintpalnering gick lika bra, vi va överräns om dom flesta punkterna och alla ställde upp och tog de dom ville för veckan samt va alla i gruppen med denna gång. Daily scum vi va effektiva och snabb. Andra retro bättre än första för då hade alla bättre koll va de går ut på. 

## Sprint 3 vecka 41

### Vad jag arbetade med 
- Uppdatera så att formuläret som skapar nya produkter inkluderar category och imageUrl
- Uppdatera som man ser image i `/products` och `/admin`
- Koppla frontend med Payment och skapa `PaymentSuccess` och `PaymentCancel` sidor

### Eventuella problem och hur jag löste dem
Denna veckans börja va enklare då de va att lägga till i redan färdiga sidor men Category och imageUrl. Sen resterande vecka höll jag på med payment och det gick ändå bra, de va en lite testande så man ser att allt fungerar men allt i backend va klart så detta va som sista steget.  

### Samarbete och agilt arbete
Christoffer och Jimmy kämpade men payment och gjorde ett jätte bra jobba i backend all logik jag fixade bara de sista koppla till frontend och skapade sidor för `payment/success` sant `payment/cancel`! Men där kändes de som just denna veckan hade iallafall vi tre så bra sammarbete. 

## Sprint 4 vecka 42

### Vad jag arbetade med 
- Skapa Docker image i workflow
- Pusha Docker image till Docker Hub
- Snygga till i frontend
- Kommentera bort så email ej skickas i `email-service`

### Eventuella problem och hur jag löste dem
Docker gick jätte bra, fick feedback att de är bättre att skapa ny docker image vid merge till main så efter en PR har blivit godkänd och när man klickar på merge så skappar en ny docker image. Det fick jätte bra att lägga till ett till Projekt i min render så behövde inte skapa ett nytt konto. 

### Samarbete och agilt arbete
Sprintplaneringen gick bra vi höll tiden och vi alla va bra överäns om poäng för varje punkt. 
Det ända denna vecka så va inte alla med på daily Scrum. Det är inte för vi inte meddelar som exempelvis på torsdag så hade vi ju genomgång med dig håkan kl 09 sen skulle vi ha igen kl 11 då flera hade möte med Jennie kl 13. Så vi skrev i vår grupp att vi ändra mötet till 10:30 så vi kunde ha mötet innan genomgången men en dök inte upp och skrev inget på teams så de va inte så bra för då vet vi inte hur alla ligger till samma hände i tisdags vi hade ju klass möte med jennie och det drog ut på tiden så vi skrev i gruppen att vi har möte efter 13 efter din genomgång men då va han inte med igen och vi skrev i vår grupp igen om detta. Vi andra tre hade väldigt bra sammarbete och döck de upp något och man behöver flytta från något möte va vi andra vädlgit bra på att säga till i god tid. 

## Sprint 5 vecka 43

### Vad jag arbetade med 
- Avkommenterade Email så den är aktiv
- Fixade email (den va aktiv men skickade inte ut mejl)
- Undersök integrationstestning
- Konfigurera MSW
- Undersök end-to-end-testning

### Eventuella problem och hur jag löste dem
Min första uppgift för veckan va inga problem med men sen när jag hade gjort de och email va aktiv och allt fungerade på render så skickades de inte ut mejl plus så kom de inte upp någon konstigt på Render om något error eller likande. Sen va de applösenordet som jag la en ny och då fungerade det nästan pågrund att vi har grattis version på render så blockar render porten för utskick men orderbekräftelsen sysns i Logs på render. 
När den kommer till Undersöka integrationstestning och end-to-end-testing, gick de bra då det finns mycket bra information på officiella sidorna, plus mycket. Vi hade delat word dokument så vi alla skrev vad vi hitta och förklarade hur dom olika testen fungerade och vad användes till vad. 

### Samarbete och agilt arbete
När jag hade problem med email så hjälpte Jimmy och Christoffer till jätte mycket vi kollade på det tillsammans och kom fram till lösningen. Jimmy la in en fake order via Postman sen kollade Christoffer att den kom in i kön och sen såg jag på render att den kom ut i Logs. Jätte bra sammarbete. Scrumplaneringen gick bra men denna gång va vi igen bara 3 inte alla i gruppen. Så vi kunde inte dela ut alla uppgifter för veckan. Men sedan på Daily skrum va vi alla, och vi pratade om små förändringar man kan göra så frontend set bättre ut och alla kom med sina idéer och de gick jätte bra.

## Sprint 6 vecka 44

### Vad jag arbetade med 
- Skapa och skriva README-fil för Frontend och Gateway
- Dokumentera med Javadoc i Gateway
- Skapa och började med Powerpoint 

### Eventuella problem och hur jag löste dem
Skulle inte säga de som problem men undersökte hur man bäst ska lägga upp en README-fil så en annan utvecklare skulle förstå det och att de är lätt läst. Skrev den på engelska för alla olika sidor jag läste om de sa att det är bäst att göra de så alla kan förstå den. Vi skulle ju presentera vårt projekt för JUV26 klassen så jag skapa en Powerpoint som vi alla kunde ändra och lägga till slides för presentationen. 

### Samarbete och agilt arbete
Vi hade en bra Sprintplanering, de va en vecka med lite färre tasks och de vi va snabbt överens om "poäng" för veckans task och delade ut. Det mest logiska va att personerna som jobbade med `Auth`, `Product` och `Order` gjorde `README`-fil för sina egna samt `JAVADOC` så jag tog Frontend och skrev `README`.fil och tog `Gateway`. Sen va jimmy snabb och tog `Payment`. Sen planerade vi hur upplägget för presentationen nästa vecka tillsammans och vi diskuterade lite hur djupt i allt man ska gå in då JUV26 har inte gått igenom mycket av de så vi bestämde att de är bra med mindre kod block och ha mer flödesschema bilder så man ser flödet mer och förstår hur allt händer ihop. 
