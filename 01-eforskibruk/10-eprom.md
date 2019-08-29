# ePROM

En skjematype kan bestilles utfylt av personer i Personregisteret via det eksterne systemet ePROM.
ePROM ligger åpent på internett og sørger for å tilgjengeliggjøre skjema for alle innbyggere i Norge,
enten digitalt eller via papirskjema sendt i posten. Digital utfylling er tilpasset mobile enheter.

Skjemaet vil bli opprettet i databasen når personen besvarer skjemaet. 
I samme prosess må vedkommende velge å samtykke til at data lagres i databasen, hvis samtykke ikke allerede foreligger. 

## Status på bestillinger

En bestilling kan ha følge statuser:

#### Planlagt
En bestilling vil skje frem i tid. Tidligste tidspunkt for bestilling er gitt under "bestillingstidspunkt". De planlagte bestillingene blir kjørt ca hver hele time, og et maksimum på 1 000 bestillinger blir prosessert hver time. Har man mer enn 1 000 bestillinger med passert planlagt bestillingstidspunkt, blir disse posjonert utover de kommende timene.

#### Bestiller
En bestilling er levert til ePROM systemet, og det ventes på en tilbakemelding om hvilken varslingskanal bestillingen sendes på. Det kan ta opptil 48 timer å få svar. 

#### Bestilt
Bestillingen er sendt ut, og det ventes på svar.

#### Besvart
Et svar har ankommet eFORSK.

#### Utgått
Bestilling er ikke besvart innen utløpsfristen. Merk at en ubesvart papirskjemabestilling aldri løper ut på dato, svaret kan komme inn når som helst frem i tid. Et unntak er hvis brevet til mottaker kommer i retur på grunn av feil adresse, bestillingen vil da i eFORSK få statusen "utløpt" med en kommentar.

#### Feilet
Se mer spesifikk feilmelding ved siden av statusen.

#### Avbrutt
Bestillingen har hatt status "planlagt", men den har blitt avbrutt før den har blitt forsøkt bestilt.

## Testmodus

Man kan teste bestilling av skjemautfyllelse i testmodus. Testpersoner man kan bestille utfyllelse av kan man finne under egen artikkel om testmodus i brukermanualen. Her er det spesielle testpersoner som har fått satt opp helsenorge.no og Digipost konto.

Utsendelse av papirskjema er naturligvis vanskelig å teste. Her vil man i testmodus etter en stund få et tilfeldig generert svar tilbake. Laster man ned den skannede PDF-fila, vil denne ikke være utfylt.

## Papirskjema (fysisk post)

Papirskjema blir tolket av en skanner, det er viktig å sammenligne den innskannede PDFen med de tolkede svarene i skjemaet at det faktisk er tolket riktig. Skanneren tolker alt annet enn avkryssning veldig dårlig. Skjema kan gjenåpnes og endres.


