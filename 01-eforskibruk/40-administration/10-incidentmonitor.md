# Hendelsesovervåking

Dette er et system for å lytte på hendelser i eFORSK og varsle om dette.

En hendelsesovervåking kan varsle en gang per objekt som utløser en hendelse. Eksempelvis, 
hvis man overvåker skjema som får status "til kontroll", 
vil hendelsesovervåkingen kun varsle første gangen skjemaet får status "til kontroll", men ikke de påfølgende gangene.



## Typer overvåking

Når man lager en ny hendelsesovervåking må man velge hvilken type objekter man vil overvåke. 
Man kan lytte på hendelser fra følgende objekter:

### Skjema



Eksempel på hendelse: Skjema oppnår statusen "til kontroll".

Eksempel på hendelse: Ferdigstilt skjema med forskningsobjektets kjønn lik mann og forskningsobjektets alder over 90 år.


### ePROM bestillinger

Eksempel på hendelse: Bestilling oppnår status "utgått".

## Varsling

## Forsinkelse

Overvåkingen har en forsinkelse på ett minutt før den sjekker et oppdatert objekt. 
Eksempelvis kan et skjema være innom statusen "til kontroll", men blir dette endret før det har gått ett minutt 
vil ikke hendelsesovervåkingen rapportere en hendelse.
