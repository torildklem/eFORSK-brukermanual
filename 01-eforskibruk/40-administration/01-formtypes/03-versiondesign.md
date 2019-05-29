# Skjemautforming, felter og regler

Under bygging av skjematyper skal man legge til elementer. Dette kan være grupper, informasjonstekst, felter eller regler.
                    
## Grupper
Grupper brukes for å samle elementer. Gruppen vil få en overskrift som vil utheves i skjemaet. "Vis hvis" regler kan legges på grupper for å styre visning av alle dens elementer.

## Informasjonstekst
Informasjonstekst kan legges til hvor man ønsker i skjemaet, eksempelvis for en ekstra forklaring til den som skal fylle ut skjemaet.
                    
## Felter
Feltene er det som skal besvares i et skjema. Felttypene som støttes er **tallfelt**, **avkrysningsfelt**, **datofelt**, **tekstfelt**, **valgfelt** og **randomiseringsfelt**. 

Det finnes ikke en egen felttype for **flervalgsfelt**, da analyse av eksportert data blir vanskelig om et svar på en variabel inneholder flere verdier. Men, man kan lage illusjonen av et flervalgsfelt ved å ha en gruppe med avkrysningsfelt for hvert alternativ. På gruppen legger man på regelen "Vis som flervalgsfelt", som gjør at den vises som ett felt.

Alle felt vil ha et variabelnavn som brukes ved eksport, og en visningstekst som gjør det enkelt for bruker å vite hva som skal fylles ut.

### Randomiseringsfelt
Et randomiseringsfelt fungerer på samme måte som et valgfelt, hvor man kan opprette flere alternativer. Forskjellen ligger i grensesnittet ved utfylling av skjema; man får en knapp for randomisering som gir et tilfeldig valgt alternativ (enkel randomisering/myntkast). Denne handlingen kan ikke angres.

I de tilfellene et randomiseringsfelt er lagt til en skjematype som kan bestilles utfylt (ePROM), så vil ikke feltet være synlig for vedkommende som skal fylle ut. Feltet vil bli randomisert ved bestilling. I de tilfellene hvor det er papirbesvarelse, så vil feltet bli randomisert ved leveranse tilbake til databasen.

### Systemutfylte felt
Man har også muligheten til å legge til systemutfylte felt. Et systemutfylt felt vil automatisk fylles ut ved opprettelse, endring eller ferdigstillelse. Vedkommende som fyller ut skjema har ikke muligheten til å fylle ut eller endre disse feltene. Dette er typisk brukt for metadata som skjemaets unike nøkkel, alder, kjønn og lignende.

## Skjemaregler
Skjemaregler omfavner både validerings- og vis/skjul-regler. Reglene kan på lik linje med felter opprettes på en versjon, og fjernes i senere versjoner.

Man kan teste reglene i forhåndsvisning av skjematypen under bygging.
