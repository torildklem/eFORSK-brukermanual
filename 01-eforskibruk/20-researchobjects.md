# Forskningsobjekter

Skjemaer i eFORSK tilhører det vi kaller forskningsobjekter. Forskningsobjekter tilhører en forskningsobjekttype.

Personer fra Personregisteret ligger inne som standardtype for forskningsobjekt, 
men en bruker med rollen *databaseansvarlig* kan også opprette andre typer av forskningsobjekt når data man samler inn ikke kommer fra mennesker. 
Andre typer kan for eksempel være legemidler, lab-rotter eller lignende. 
Bruker man ikke standardtypen personer fra Personregisteret kan man ikke bestille skjema til utfyllelse via ePROM.

Ved opprettelse av en skjematype låses den til en spesifikk forskningsobjekttype og kan ikke endres senere.

Under "Forskningsobjekter" kan man se de siste forskningsobjektene som er behandlet skjema på i databasen, samt søke opp eller opprette nye forskningsobjekter. 

## Samtykke

Hvordan samtykkehåndering fungerer kan leses under "Administrasjon/Skjematype/Samtykkehåndtering".

Alle forskningsobjektets samtykker vises på forskningsobjektets side. Merk at skjemaer i kladd ikke telles som samtykker.

## Sletting

*Funksjonalitet for sletting kommer i versjon 2.1.*

Databaseansvarlige har tilgang til å slette forskningsobjekter. Dette gjøres eksempelvis hvis et forskningsobjekt trekker sitt samtykke.

Ved sletting beholdes all hendelseslogg på forskningsobjektet for å overholde krav om sporing, men all skjemadata registrert på forskningsobjektet vil slettes. Sletting av skjemadata skjer automatisk påfølgende natt etter man har slettet forskningsobjektet (årsaken er at et program med forhøyede rettigheter må kjøres for å slette historisk loggførte data).

Hvis forskningsobjektet er en person fra personregisteret: 
Slettes et slikt forskningsobjekt, fjernes koblingen mot personregistrert. Man kan likevel finne tilbake til forskningsobjektet via dens unike nøkkel. 
Bemerk at hvis man i etterkant av sletting søker opp den samme personen, på navn eller fødselsnummer, vil et helt nytt forskningsobjekt opprettes.

