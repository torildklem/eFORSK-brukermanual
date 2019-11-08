# Systemutfylte felt

Et systemutfylt felt vil automatisk fylles ut ved opprettelse, endring eller ferdigstillelse.
Vedkommende som fyller ut skjema har ikke muligheten til å fylle ut eller endre disse feltene. 
Dette er typisk brukt for metadata som skjemaets unike nøkkel, alder, kjønn og lignende.

## Formel

*Dette er funksjonalitet som ikke er tilgjengelig enda*

I formler kan man hente inn verdier fra andre felter. Hvis man har et tallfelt med variabelnavn Tall, skriver man \[\_Tall\_\] i formelen for å få feltets verdi.

Eksempel på formel: max(\[\_Tall1\_\], \[\_Tall2\_\], \[\_Tall3\_\]) / 2E-3

Lager man en formel (B) som skal hente verdien fra en annen formel (A), er det viktig at feltet med formel (A) opprettes først.

<a href="https://github.com/pieterderycke/Jace/wiki" target="_blank">Detaljert informasjon om bygging av formler</a>
