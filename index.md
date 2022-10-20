## Praksis - Sikri
Håvard, Mehmet og Bjørnar


### Våre forventninger

Få godt læringsutbytte og lære noe som jeg kommer til å ha bruk for videre i arbeidslivet.Vi ønsker å lære om utvikling og hvordan det er å jobbe i som team på en bedrift. 
Vi forventer oss et arbeidsmiljø som legger til rette for god kvalitet i produkt. Fra Sikri forventer vi å få god oppfølging om muligheten til å utforske samt vokse som utviklere. 

### Oppgavebeskrivelse

Hvordan gjennomføre søk som går på tvers av systemer levert 
av forskjellige leverandører? Mange sitter med historiske 
arkiver som kan være levert av en annen leverandør enn Sikri. 
Også nyere data kan ligge i flere systemer. Spesielt ved 
saksbehandling av byggesøknader er det aktuelt å gå også til 
andre kilder for å hente ut tidligere saker som gjelder samme 
eiendom. Oppgaven går ut på å finne ut hvordan dette kan 
gjøres teknisk og på en for bruker god måte. 
Arbeidshypotesen vår er at saksbehandleren ønsker å gjøre 
søket via fritekstsøk (i dag Solr i Elements), men vi er åpne for 
andre løsninger. Oppgaven inkluderer også vurdering av 
datatilgang – hvordan hindre at saksbehandler får innsyn i 
data vedkommende ikke burde ha sett?

### Status 1

### Bransje, hva driver de med, særtrekk? evt størrelse, omsetning ++

Sikri er en av norges leverandører innen saksbehandling, dokumentforvaltning og arkivering. Bedriften sier at de sine viktigste mål er å sikre godt samarbeid med offentlig sektor og fortsette partnerskap strategien med privat sektor. Sikri vil hjelpe offentlige sektorer til å nå sine målsettinger. I desember 2019 ble selskapet splittet ut av EVRY og fikk navnet Sikri. Sikri har mange forskjellige tjenester som konsulent/spesialbistand, tekniske tjenester, automasjon, personverntjenester og opplæring. Sikri har kontorer i Oslo, Kristiansand, Bergen Harstad og i Sandefjord.

### Dine/våre arbeidsoppgaver

Først og fremst sette oss inn i forskjellig programvare, samt den kildekoden for systemet vi skal bygge på. Foreløpig skjer det søk i kun én kilde i Elements, mens vår oppgave blir å legge til muligheten for søk i flere. Dette har til nå vist seg å være et svært komplekst system og prosjekt, som vil kreve mye tid i å sette seg inn i og forstå språk, logikk, og funksjonalitet før vi kan bygge videre.

### Spesielle utfordringer eller spennende ting å trekke frem annet

Gruppen har fått i oppgave å sette seg inn i C#, DotNet, Visual Studio 2022 og Azure DevOps. Dette blir sett på som en spesiell oppgave/utfordring for gruppen da ingen har noen/liten erfaring innen dette. C# er ikke så mye annerledes en Java, men noe nytt. DotNet er et nytt framework som blir brukt hos Sikri. Dette krever en del arbeid for å sette seg inn i. IDE som blir brukt er Visual Studio 2022, noe som setter gruppen inn i en opplæringsprosess. Azure DevOps er svært likt github (bruker github) noe som fører til at dette ble mestret svært raskt av gruppen. Er også verdt å nevne at selve oppgaven gruppen har fått er noe som bygges mer eller mindre fra scratch og som ikke eksisterer i Sikri. Oppgavene blir å kunne bygge videre på Elements å utvide søkefunksjonen med en innlogget bruker gitt en token i databaser som er utenfor elements. 


### Status 2

#### Arbeidsplassen

Etter nå å ha tilbrakt lengre tid hos Sikri, har vi fått flere inntrykk av forskjellige aspekter. Kontoret er fylt av flinke og hyggelige mennesker, som titter inn på møterommet i ny og ne og sier hei. De har fra første stund vært tydelige på at hvis vi trenger hjelp med noe er det bare å spørre. Til tross for dette, og med tanke på at praksisveilederen våres sitter i Oslo, har vi hatt større behov for å kommunisere med Sikri sin avdeling i hovedstaden. Dette gjorde det litt vanskelig i startfasen av prosjektet, men ettersom vi ble mer kjent med det tekniske har det fungert fint. Veileder har også vært dyktig på å legge til rette for at vi kan opprettholde kontakt utenom avsatt møtetid, som har resultert i meldinger over Teams. Det er tydelig at veileder også har brukt tid på egenhånd for å hjelpe oss på veien, blant annet i form av et eget repository for eksempelkode. Det har kommet mer og mer frem at Sikri har en tydelig tilrettelegging for praksis. 


#### Vårt arbeid

Hovedoppgaven våres har vært tydelig presentert fra første dag. Vi skal utvikle en minimalisert utgave av søkefunksjonen de allerede har i bruk, men muliggjøre søk på tvers av flere datakilder. Grunnet mye kompleksitet, har det til nå blitt brukt tid på å utvikle en en versjon av det nåværende systemet, som vi kommer til å bygge ut etterhvert (venter fortsatt på informasjon for å kommunisere med de andre kildene). Derav har vi nå en ASP.NET core API som kommuniserer med datakilden og henter ut søkeresultat, og en React.js frontend som sender requests til APIen. Per dags dato er det mye som fungerer, men fortsatt arbeid å gjøre.

Gjennom arbeidsprosessen våres har vi blant annet erfart viktigheten ved å gjøre ting sammen. Altså, vi programmerer på en skjerm og alle ser på, mens vi har muligheten å gjøre individuelt arbeid utenom avsatt tid. Denne metoden kom som resultat av forskjellig kompetanse i programutvikling, samt forskjellig tidsbruk på prosjektet. Det var gjerne litt “knall og babb” i startfasen, men det ser ut til at vi er på et godt spor for øyeblikket. Vi føler vi har lært mye frem til nå, mest i henhold til programmering i .NET og React.js.

Videre fortsetter vi i samme bane vi er i nå. Vi håper på å få nødvendig informasjon angående påkobling til de andre datakildene, samt innloggingskode til det nåværende systemet, så raskt som mulig. Da vil det by på nye utfordringer som vi kan lære nytt av. For øyeblikket er vi godt fornøyde med forholdene i praksisoppholdet våres, så vi satser på å fortsette i samme dur. 


### Vår praksis hos Sikri

Vi har vært så heldige å fått muligheten av å være i praksis hos Sikri. Her jobber vi med utviklingen av et system som tar utgangspunkt i deres opprinnelige sakarkiv-søkesystem til å kunne søke på tvers av forskjellige datakilder. Gjennom praksisoppholdet har vi fått god introduksjon til rammeverket ASP.NET, programvaren C#, lært oss React.js, og generelt bygget opp mer kunnskap innen programutvikling. 

![Funker ikke](/IMG_1433.JPG?raw=true "Oss")

#### Bjørnar Sømme, 21 år
Så langt har jeg likt mest backend-utviklingen. Det er alltid gøy å møte på nye problemer, og kjenne på følelsen av å løse disse. Noe jeg har tatt med meg fra tidligere studier inn i dette arbeidet er generell kunnskap innen programutvikling. Grunnet relativt tidligere lite erfaring med utvikling av et komplette systemer, har det vært spennende å få gjort dette i praksis, hos en bedrift med mye kompetanse innen feltet. Til tross for dette har jeg fått bruk for kompetanse jeg har bygget opp gjennom studiet. For eksempel, så har programmeringsprosjektet, flere fag innen Java-programmering og databaserelaterte emner forberedt meg på flere av utfordringene jeg har møtt på. 

Oppholdet så langt har bydd på mye utfordring, kunnskap og skapt nye relasjoner til dyktige folk, og noe av det gøyest med dette har vært å se hvordan en fremtidig arbeidsplass kan se ut for meg. Inkludert i dette er både det tekniske arbeidet som har blitt gjort, men også prosesser og samarbeid på arbeidsplassen.

#### Mehmet Eksi, 23 år
Det jeg har likt spesielt godt hos Sikri er hvor utfordrende det har vært. Jeg liker at vi har fått vårt eget sted å jobbe på innenfor kontoret til Sikri som gjør det mer motiverende å jobbe istedenfor å være hjemme eller på skolen. Jeg liker at vi koder i språk som blir brukt ofte i andre bedrifter og at vi jobber med å bygge noe ut ifra et faktisk system. Jeg liker spesielt å kode i front-end i forhold til backend fordi jeg føler jeg mestrer det mest. Jeg har lært så langt hvordan MVC fungerer i ASP.NET og deler av backend for systemet vi holder på å lage.

Jeg har hatt bruk for alt av det jeg har lært fra programmeringsfag som Objektorientert programmering og programmeringsprosjekt fordi det vi holder på tar i bruk store deler av disse fagene. Gøyeste jeg har gjort er å få systemet til å printe ut på skjermen og få ting til å kommunisere med hverandre. Det tok en god del tid for meg både å forstå og få dette til å fungere som vi ønsket sammen med gruppen.

#### Håvard Sommer Rosenlund, 27 år
Det er mange ting som er svært artig og interessant hos sikri. Blant annet at man får prøvd seg i det virkelige arbeidslivet, samt at man får oppgaver som man ser nytten av. Det er også en god opplevelse å være en del av kontoret. Med sin egen arbeidsplass og miljø. Setter svært stor pris på måten Sikri har tatt oss studenter imot. Hos Sikri så har jeg lært svært mye. Har satt meg inn i et helt nytt kodespråk C#, satt meg inn i .NET, React, ASP.NET. Fått en bedre forståelse på hvordan databaser fungere og kommuniserer samt mye mer. Det jeg har hatt mest bruk fra mitt studie så lang er forståelsen på hvordan et kodespråk er bygget opp. med dette blir det enklere å lære seg ett nytt ett. Samt min kunnskap om databaser fra før av.

Det gøyeste jeg har gjort så lang er å se fremgang på at ting fungere sammen med gruppen i form av backend og frontend. Synes også det er artig å vise fram hva vi har klart å gjøre til prosjektveileder.


### Avsluttende Refleksjon






