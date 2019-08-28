# Skjematype

En skjematype er oppsettet og egenskaper av felter og regler det skal registreres på. 
Man kan velge å opprette en ny skjematype, kopiere en allerede eksisterende skjematype eller bruke standardskjematyper.

## Opprettelse

Når man skal bygge ny skjematype må man gjøre noen valg som ikke kan gjøres om på senere. Unntaket er skjematypens navn, dette kan når som helst endres etter opprettelse.

### Utgangspunkt

#### Ny skjematype
Her får man et tomt utgangspunkt, kun med noen foreslåtte systemutfylte felter

#### Kopi av eksisterende skjematype
Her kan man velge en eksisterende versjon av en skjematype, og få gjenskapt en kopi av denne

#### Bruk standardskjematyper
Standardskjematyper er et sett med ferdigdefinerte skjematyper som ligger i ePROM løsningen.

Ved bruk av flere standardskjematyper som skal besvares samtidig, eksempelvis EQ5D og RAND12, er det i eFORSK anbefalt å samle disse i en skjematype. Ved bestilling av utfyllelse (via ePROM) kan mottaker da besvare alt samtidig, istedenfor å motta flere separate skjemaer som øker terskelen for å fullføre utfyllelsen.

Husk at ved bruk av standardskjematyper er man selv ansvarlig for å overholde eventuelle lisenser disse måtte ha.

#### Importer fra fil
Her kan man laste opp fil som tidligere er eksportert fra en eksisterende skjematype, under valget "Eksporter skjemadefinisjon". Dette gjør at man kan flytte skjematyper mellom databaser.

### Skjematypen skal være underskjematype av

Hvis man har avhengigheter i mellom skjematyper, kan man velge at en skjematype er underskjematype av en annen. Da får man et ekstra systemutfylt felt som har den unike nøkkelen til foreldreskjemaet, som kan nyttes for å koble data. 

Et typisk eksempel er at skjematypen "Spørreskjema 30 dager etter utskrivelse" er en tilknyttet skjematype til "Inklusjonsskjema". Her kan man for eksempel sette opp automatisk utsendelse av spørreskjemaet 30 dager etter at inklusjonsskjemaet er opprettet.

### Type forskningsobjekt

Skjemaer som fylles ut av skjematypen må være tilknyttet en forskningsobjekttype. Forskningsobjekttyper settes opp under "Administrasjon". Skal man samle inn data på medisiner, må man opprette en forskningsobjekttype som heter "Medisiner", og deretter velge denne ved opprettelse av skjematypen. Skal man bruke ePROM er man nødt til å velge "Personer fra personregisteret". "Personer fra personregisteret" gir også en del ekstra muligheter for data med systemutfylte felter, for eksempel kjønn og adresse.
