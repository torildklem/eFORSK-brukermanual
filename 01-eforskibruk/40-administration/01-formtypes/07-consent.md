# Samtykkehåndtering

*Dette er planlagt funksjonalitet og er ikke tilgjengelig ennå.*

Ønsker man å innhente samtykke gjøres dette med skjemaer. Man kan lage egen skjematype for samtykke, som kun har som oppgave å etterspørre samtykke. Man kan også inkludere samtykkeinnhenting i skjematyper med andre spørsmål som skal besvares for å minimere antall utsendelser.

Ved skjemabygging av skjemaversjon man ønsker lagring av samtykke på må man krysse av for "Aktiver samtykkehåndtering".

Det er ulike krav til samtykkeinnehentelse:

Noen steder er det godkjent at selve besvarelsen av et skjema er godkjent som et samtykke. 
Man trenger da ikke gjøre noe annet enn å aktivere samtykkehåndtering, men man bør nevne med tekst et sted at man samtykker ved besvarelse.

Noen steder kreves det at man aktivt må besvare et spørsmål om man samtykker. 
Dette løses med å legge til elementet "Samtykkefelt" i skjemabyggeren. 
Dette muligjør også at man kan legge til flere spørsmål om ulike samtykke. 
Videre kan man for eksempel legge på "vis hvis" regler som viser frem spørsmålene kun hvis man velger at man samtykker.

Noen steder kreves det også signering, da må man krysse av for "innhent signatur". 
For digital besvarelse må man signere med BankID (medfører en kostnad), for papirskjema
vil det komme et felt for signering på slutten av skjemaet. Man signerer da for alle eventuelle samtykker gitt i skjemaet.
