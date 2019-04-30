# Hovedskjematype og underskjematype

Hvis et skjema av en skjematype (B) krever eksistensen av et skjema av en annen skjematype (A), er det god praksis å opprette skjematypen B som en underskjematype av skjematypen A. Man får da et metadatafelt på skjematype B med den unike nøkkelen til skjematype A som kan være nyttig ved dataaggregering.

I noen prosjekt kan det være ønskelig med oppfølgingsskjema, og dette kan løses ved å opprette en underskjematype av en hovedskjematype.

Ved opprettelse av en underskjematype må denne kobles til en eksisterende skjematype. Man kan ha flere nivå med underskjematyper.

Disse koblingene reflekteres også ved utfylling av disse skjematypene; utfylling av en underskjematype for et forskningsobjekt må kobles til et foreldreskjema som er fylt ut for samme forskningsobjekt.
