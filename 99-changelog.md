# Endringslogg

Her finnes en oversikt over de viktigste endringene i funksjonalitet mellom versjonene.

## Versjon 2.1 (dato ikke bestemt)

* Mulighet for å slette forskningsobjekter
* Mulighet for å deaktivere og slette tilgangsenheter
* Forbedringer rundt visning av tilgangsenhet
* Bedre funksjonalitet for å styre hvilke funksjoner som er tilgjengelig på ulike tilgangsenheter innad en database
* ePROM: Nytt valg i skjemabygger for å ikke sende kopi av besvart skjema til utfyller sin Helsenorge-konto eller digitale postkasse
* ePROM: når papirskjema i posten ikke kommer frem til mottaker og blir returneret (grunnet feil adresse f.eks.) blir status på bestillingen nå "Feilet" istedenfor tidligere "Utgått", da status "Utgått" kun burde brukes for digitale bestillinger der mottaker har hatt en mulighet til å svare.
* ePROM: flere muligheter for å spesifisere tekst i melding som går til Digipost og Helsenorge
* ePROM: mulighet ved bestilling å forhindre bestilling hvis forskningsobjektet allerede har et skjema eller en aktiv (status: planlagt eller bestilt) bestilling av valgt skjematype
* Skjemabygger: mulighet for  å flytte til topp eller bunn av gruppe
* Separat applikasjon for å lese brukermanualen
* Forbedret grensesnitt rundt redigering av rekkefølge på felter. Fikset feil ved lagring av ny rekkefølge
* Monitorfunksjon?

## Versjon 2.0 (16. desember 2019)

* Mulighet for å sende ut brev (PDF) til personer i personregisteret (helsenorge, sikker digital postkasse eller i posten)
* Nytt system for samtykkehåndtering
* System for hendelsesovervåking
* Mulighet for å skjule fjernede felter i skjemabygger
* Mulighet for å styre muligheten for å bestille skjemautfyllelse (ePROM) per tilgangsenhet
* Stratifisert blokkrandomisering: utvidet mulig felter som kan brukes som stratifiseringskategorier til også å gjelde avkryssningsfelt, samtykkefelt og det systemutfylte feltet "registrerende tilgangenhets ID"
* Ny hendelseslogg på forskningsobjekter, vist som tidslinje
* Mulighet for å ha registrering av klokkeslett på datofelt
* Mulighet for å sammenligne med tallfelt på "Vis hvis" regler
* Nytt systemutfylt felt: Formel
* ePROM: Bedre mulighet for å styre tekster i Helsenorge og sikker digital postkasse i skjemabyggeren
* ePROM: Mulighet for å skjule fremdriftindikator i ePROM skjema
* ePROM: Ny regel for å kunne skjule utfyllingshjelp på papirskjema
* ePROM: Mulighet for å bestille ePROM utfylling via E-post og SMS hentet fra kontaktregisteret. 
* ePROM: Forbedret valg av varlingskanaler ved ePROM bestilling
* ePROM: Forbedret funksjonalitet for automatiske ePROM bestillinger
* ePROM: Forbedret søkefiltre for bestillinger
* Nye regler på datofelt: fortid, mindre enn (verdi), mindre enn annet felt, mindre enn eller lik (verdi), mindre enn eller lik annet felt, større enn (verdi), større enn annet felt, større enn eller lik (verdi), større enn eller lik annet felt, lik (verdi), ulik  (verdi)
* Nye regler på tallfelt: mindre enn (verdi), mindre enn annet felt, mindre enn eller lik (verdi), mindre enn eller lik annet felt, større enn (verdi), større enn annet felt, større enn eller lik (verdi), større enn eller lik annet felt, lik (verdi), ulik (verdi)
* Ny regel på avkryssningfelt: påkrevd svar
* Nye kommunenummer for 2020 ved personsøk
#### Kjente feil
* Kan ikke se hendelser med rollen dataansvarlig
* Feil ved lagring av sortering av felter inne på en skjematype

## Versjon 1.2 (8. oktober 2019)

* Forbedringer i "Finn forskningsobjekt" funksjon. Kan nå laste opp fil med IDer. Antall samtidige i visning er satt til 1 000.
* Nye systemutfylte felter: Forskningsobjektets navn, Forskningsobjektets poststed ved skjemaopprettelse, Forskningsobjektets bostedsgate ved skjemaopprettelse, Brukeren som opprettet skjemaet sitt navn
* Mulighet for stikkordsøk i brukermanual
* Tekstlig visning av skjemadata, kopierbar til andre systemer
* Forbedringer ved validering av variabelnavn
* Forbedringer i skjemabygger rundt forhåndsvisning og tillegging av systemutfylte felter

## Versjon 1.1 (26. august 2019)

eFORSK lanseres, pilotperiode avsluttes.

* Mulighet for identifiserbar eksport av ePROM bestillinger
* Mulighet for å låse skjemaversjoner, slik at skjemaer utfylt i versjonen ikke kan endres
* Mulighet for å se verdien til skjulte elementer på et skjema inne i eFORSK
* Bedre støtte for varsler: Databaseansvarlig kan opprette varsler som vises for alle brukere av databasen. Brukes også for å varsle oppgradering av eFORSK.
* ePROM Personinitiert utfyllelse tilgjengelig for alle med ePROM aktivert
* Mulighet for verdier fra felter inn i informasjonstekst til mottaker ved ePROM bestilling
* Kan nå slå opp forskningsobjektet med dens unike nøkkel

#### Feilretting

* Rettet feil med funksjonen "Slå opp unik nøkkel" på skjema-siden
* Rettet feil der skjemastatus og sist oppdaterttidspunkt ikke ble oppdatert ved status "til kontroll" på skjema.
* Rettet feil med funksjonen "last ned skjematype metadata" under verktøy

## Versjon 1.0 (17. juni 2019)

* Løsning for flervalgsfelt
* Mulighet for å legge ePROM bestillinger frem i tid
* Mulighet for eksport av ePROM bestillinger til regneark
* ePROM Personinitiert utfyllelse (tilgjengelig kun ved forespørsel)
* Automatiserte ePROM bestillinger (tilgjengelig kun ved forespørsel)
* Mulighet for å etterspørre samtykke ved ePROM bestilling selv om samtykke allerede foreligger
* Import av skjemadata (tilgjengelig kun ved forespørsel)
* Diverse rettelser for nettleseren Edge
* Rettet visning av tidspunkter i systemutfylte felter til å ha korrekt tidssone
* Roller i Falk på plass
* Samtykketekst konfigureres nå per skjematypeversjon, og ikke felles for hele databasen

## Versjon 0.9 (mars 2019)

Dette er første versjon av eFORSK, til bruk for piloteringsprosjekter.
