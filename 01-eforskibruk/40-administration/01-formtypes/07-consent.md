# Samtykkehåndtering

*Dette er planlagt funksjonalitet og er ikke tilgjengelig ennå.*

Ønsker man å innhente samtykke gjøres dette med skjemaer. Man kan lage egen skjematype for samtykke, som kun har som oppgave å etterspørre samtykke. Man kan også inkludere samtykkeinnhenting i skjematyper med andre spørsmål som skal besvares for å minimere antall utsendelser.

For å komme i gang må man huke av for "Aktiver samtykkehåndtering" på skjemaversjonen man ønsker forespørsel om samtykke på.

Det er ulike krav til samtykkeinnehentelse:

Noen steder er det godkjent at selve besvarelsen av et skjema er godkjent som et samtykke. 
Man trenger da ikke gjøre noe annet enn å aktivere samtykkehåndtering, men man bør nevne med tekst et sted at man samtykker ved å besvare skjema.

Noen steder kreves det at man aktivt må besvare et spørsmål om man samtykker. 
Dette løses med å legge til elementet "Samtykkefelt" i skjemabyggeren. 
Man kan legge til flere "Samtykkefelt", slik at man kan innhente flere ulike samtykker på ett og samme skjema.
Videre kan man for eksempel legge på "vis hvis" regler som viser frem spørsmålene kun hvis man velger at man samtykker.

Noen steder kreves det også signering, da må man krysse av for "Innhent signatur ved ePROM besvarelse".
For digital besvarelse må man signere med BankID (medfører en kostnad), for papirskjema
vil det komme et felt for signering på slutten av skjemaet. 
Man signerer da for alle eventuelle samtykker gitt i skjemaet.
