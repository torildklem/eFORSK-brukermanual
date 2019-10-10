# Hendelsesovervåking

*Dette er funksjonalitet som kommer i versjon 2.0*

Dette er et system for å lytte på hendelser i eFORSK og varsle om dette.

## Typer overvåking

Når man lager en ny hendelsesovervåking må man velge hvilken type objekter og hvilke skjematype man vil overvåke. 
Man kan lytte på hendelser fra følgende objekter:

### Skjema

For skjema kan man velge hvilke skjemastatus og hvilke verdier skjemaet skal ha for å utløse en hendelse.

Eksempel på hendelse: Skjema oppnår statusen "til kontroll".

Eksempel på hendelse: Ferdigstilt skjema med forskningsobjektets kjønn lik mann og forskningsobjektets alder over 90 år.


### ePROM bestillinger

For ePROM bestillinger kan man velge hvilken status og hvilken varslingskanal bestillingen skal ha for å utløse en hendelse.

Eksempel på hendelse: Bestilling oppnår status "utgått".

Eksempel på hendelse: Bestilling sendt som fysisk post oppnår status "besvart".

## Hendelse

Hendelser opprettes under "Verktøy" i eFORSK. Dette kan leses om tilsvarende sted i brukermanualen.

## Varsling

Utover hendelsesvisningen kan man opprette varsling når en hendelse oppstår. Varsling kan gjøres via:
* Varslinger i eFORSK (brukeren får beskjed når man jobber inne i eFORSK)
* E-post
* SMS

Man kan velge at brukeren som opprettet objektet blir varslet. 
Ellers kan også velge blandt brukerene som har vært pålogget databasen.
I tillegg kan man legge til hvilken e-post adresse eller telefonnummer som skal varsles.

## Begrensninger

En hendelsesovervåking kan varsle en gang per objekt som utløser en hendelse. Eksempelvis, 
hvis man overvåker skjema som får status "til kontroll", 
vil hendelsesovervåkingen kun varsle første gangen skjemaet får status "til kontroll", men ikke de påfølgende gangene.

Overvåkingen har en forsinkelse på ett minutt før den sjekker et oppdatert objekt. 
Eksempelvis kan et skjema være innom statusen "til kontroll", men blir dette endret til en annen status før det har gått ett minutt 
vil ikke hendelsesovervåking på denne statusen rapportere en hendelse.
