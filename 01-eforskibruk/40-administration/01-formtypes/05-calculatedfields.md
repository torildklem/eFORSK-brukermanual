# Systemutfylte felt

Et systemutfylt felt vil automatisk fylles ut ved opprettelse, endring eller ferdigstillelse.
Vedkommende som fyller ut skjema har ikke muligheten til å fylle ut eller endre disse feltene. 
Dette er typisk brukt for metadata som skjemaets unike nøkkel, alder, kjønn og lignende.

## Formel

*Dette er funksjonalitet som ikke er tilgjengelig enda*

I formler kan man hente inn verdier fra andre felter. Hvis man har et tallfelt med variabelnavn Tall, skriver man \[\_Tall\_\] i formelen for å få feltets verdi. Har ikke feltet en verdi (ubesvart/tomt), vil den beregnes med verdien 0 i formelen.

Datoer vil transformeres til antall sekunder siden 1970 slik at dem kan brukes i formler, se eksempel under.

Lager man en formel (B) som skal hente verdien fra en annen formel (A), er det viktig at feltet med formel (A) opprettes før formel (B).

<a href="https://github.com/pieterderycke/Jace/wiki" target="_blank">Detaljert informasjon om bygging av formler</a>

#### Eksempel 1: enkel formel
`([_Tall1_] + [_Tall2_]) / [_Tall3_]`

#### Eksempel 2: funksjonen max()
`max([_Tall1_], [_Tall2_], [_Tall3_])`

Gir høyeste verdi av de tre feltene

#### Eksempel 3: bruk av datoer
`([_Datofelt2_] - [_Datofelt1_]) / 86400`

Antall dager mellom datoene Datofelt1 og Datofelt2
