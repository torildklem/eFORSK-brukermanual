# Skjematype

En skjematype er oppsettet og egenskaper av felter og regler det skal registreres på. 
Man kan velge å opprette en ny skjematype, kopiere en allerede eksisterende skjematype eller importere en standardskjematype.

## Arkitektur

Man bør planlegge nøye innholdet i skjematypene og avhengigheten i mellom disse. Skal man ha avhengigheter kan man benytte seg av hoved- og under-skjematyper.

## Opprettelse

Når man skal bygge ny skjematype må man gjøre noen valg i starten som ikke kan endres etterpå.

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
