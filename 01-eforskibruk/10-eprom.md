# ePROM

En skjematype kan bestilles utfylt av personer i Personregisteret via det eksterne systemet ePROM.
ePROM ligger åpent på internett og sørger for å tilgjengeliggjøre skjema for alle innbyggere i Norge,
enten digitalt eller via papirskjema sendt i posten. Digital utfylling er tilpasset mobile enheter.

Skjemaet vil bli opprettet i databasen når personen besvarer skjemaet. 
I samme prosess må vedkommende velge å samtykke til at data lagres i databasen, hvis samtykke ikke allerede foreligger. 

## Varslingskanaler

Ved bestilling av skjemautfyllelse bestemmer man om man vil varsle mottaker selv eller om ePROM skal sende ut varsel. Mottaker kan forsøkes nås på følgende kanaler i prioritert rekkefølge via ePROM:

#### 1. Helsenorge

Hvis mottaker har registrert seg på Helsenorge er dette den høyest prioriterte kanalen, da denne er sikker og ikke medfører kostnader. 
I Helsenorge kan mottaker ha satt opp varsling på SMS eller e-post når det kommer en melding.

#### 2. Sikker digital postkasse

Dette er også en sikker kanal, og består av tjenestene Digipost og E-box. Hvis mottaker har registrert seg på noen av disse vil dette brukes som varslingskanal.
I sikker digital postkasse kan mottaker ha satt opp varsling på SMS eller e-post når det kommer en melding. Bruk av denne kanalen medfører kostnader.

#### 3. E-post *(kommer i v2.0)*

Denne kanalen kan nyttes hvis mottaker har en e-postadresse oppført i kontaktregistret (difi).
E-post er en usikret kanal, og informasjonen som sendes hit er veldig begrenset. Den er prioritert over SMS da det er mulighet for mer tekst i en e-post. 
Les mer om hvordan e-post er utformet: <a href="https://eprom.hemit.org/PasientskjemaViaEpostSms" target="_blank">ePROM dokumentasjon</a>.

#### 4. SMS *(kommer i v2.0)*

Denne kanalen kan nyttes hvis mottaker har et telefonnummer oppført i kontaktregistret (difi).
SMS er som e-post en usikret kanal, og hit sendes det en veldig kort tekst.
Les mer om hvordan SMSen er utformet: <a href="https://eprom.hemit.org/PasientskjemaViaEpostSms" target="_blank">ePROM dokumentasjon</a>.

#### 5. Papirskjema i posten

For å kunne bruke denne kanalen må man ha aktivert papirskjema ved skjemabygging.
Denne kanalen er prioritert nederst da det er den mest kostbare måten å nå mottaker på.
Sist kjente bosted i personregisteret brukes som adresse.

## Status på bestillinger

En bestilling kan ha følge statuser:

#### Planlagt
En bestilling vil skje frem i tid. Tidligste tidspunkt for bestilling er gitt under "bestillingstidspunkt". De planlagte bestillingene blir kjørt ca hver hele time. Har man mer enn 1 000 bestillinger med passert planlagt bestillingstidspunkt, blir kun 1 000 av disse bestilt hver kommende time frem til alle er bestilt.

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

Papirskjema blir tolket av en skanner hos ekstern leverandør, det er viktig å sammenligne den innskannede PDFen med de tolkede svarene i skjemaet at det faktisk er tolket riktig. Skanneren tolker alt annet enn avkryssning veldig dårlig. Skjema kan gjenåpnes og rettes i eFORSK i etterkant.

Veiledning for besvarelse av papirskjema:
*	Ikke returner forsiden
*	Bruk blå penn, ikke rød penn
*	Sett tydelige kryss
*	Hvis du har krysset av feil, skraver feltet og sett et nytt kryss på riktig sted
*	Skjemaet tolkes automatisk, håndskrevne tekster og vedlagte lapper blir ikke tatt hensyn til
*	Vi setter pris på om du leverer alle arkene riktig orientert

Papirskjema vil alltid komme tilbake til eFORSK med status "Til kontroll".

## Kostnader

Informasjon om kostnader rundt ePROM utsendelse kommer.

