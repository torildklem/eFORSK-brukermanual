# Versjoner

Man kan lage nye versjoner av en skjematype og innføre endringer som ikke vil forstyrre tidligere versjoner som allerede er tatt i bruk.

Ved opprettelse av en ny versjon starter man med en kopi av den forrige versjonen til skjematypen. Man kan kun opprette ny versjon av den siste eksisterende versjonen.

Flere versjoner kan være publisert samtidig, men kun en versjon kan være i kladd om gangen. Grunnen til dette er at versjonene er kronologiske, en ny versjon opprettes som en kopi av den forrige versjonen. Kunne man endret versjoner tilbake i rekken, ville dette påvirket alle etterkommende versjoner.

Versjonene får navn V*X*, der *X* er versjonsnummeret. Det anbefales å i tillegg gi versjonen et navn for å enklere skille den fra andre versjoner. Dette gjøres i skjemabyggeren på høyre side.

## Versjonsstatus

### Kladd

Det er kun i status kladd at innholdet i en versjon kan endres. Når en versjon har forlatt status kladd kan den aldri returnere tilbake til denne statusen, versjonen blir altså låst for endringer.

### Publisert

Når en versjon er publisert kan det opprettes nye skjemaer av denne versjonen, og bestilles utfyllelse hvis ePROM er aktivert og godkjent. En publisert versjon kan avpubliseres eller låses.

### Avpublisert

Når en verjson er avpublisert kan det ikke opprettes nye skjemaer eller bestilles utfyllelse av versjonen. Allerede opprettede skjemaer kan man fortsatt endre på, og eventuelle svar på skjemabestillinger vil fortsette å komme inn. Avpubliserte versjoner kan publiseres på nytt eller låses.

### Låst *(ikke utviklet ennå)*

Når en versjon er låst, kan man verken opprette nye skjemaer, bestille utfyllelse eller endre på eksisterende skjemaer. Tilstanden er låst. Eventuelle svar på skjemabestillinger vil fortsatt komme inn, ønsker man ikke dette må man sørge for at alle ubesvarte bestillinger har løpt ut på tid. Merk at bestillinger som har blitt sendt som papirskjema i posten ikke har en utløpstid. Bruker man personinitiert ePROM må man sørge for at lenken til skjemaet ikke blir distribuert mer. Låste versjoner kan publiseres på nytt eller avpubliseres.
