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

### Avsluttende Refleksjon






