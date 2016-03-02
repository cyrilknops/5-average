# Use Case ID: SUC-05

**Actoren**: Gebruiker, administrator
**Trigger**: Toevoegen van voeding aan voedingslog

## Omschrijving

Wanneer de gebruiker voeding toevoegt aan zijn voedingslog, zoekt hij/zij het gewenste voedingsmiddel op in de database. De voeding met de hoogste score zal van boven
geplaatst worden in de lijst. Wanneer hij/zij een voedingsmiddel selecteert, zal ook hij/zij de optie krijgen om deze te valideren.

Op basis van hoeveel positieve validaties een voedingsmiddel ontvangen heeft, zal deze hoger of lager geplaatst worden bij het zoeken naar dat voedingsmiddel.

## Precondities

1. Er is een internetverbinding nodig om de database te raadplegen.
2. Gebruiker/administrator moet ingelogd zijn.
3. Gezochte voeding moet aanwezig zijn in de database.

## Postcondities

1. Voeding is aan de log toegevoegd.
2. Gebruiker heeft optie gekregen om voeding te valideren.

## Normale flow

1. De gebruiker klikt op 'voeding loggen'.
2. De gebruiker typt een zoekterm in en het systeem geeft de zoekresultaten weer.
3. De gebruiker duidt een product aan om toe te voegen en krijgt de optie om te valideren.

## Uitzonderingen

1. De gebruiker klikt op 'voeding loggen'.
2. De gebruiker typt een zoekterm in en het systeem heeft geen resultaten.
3. Het systeem geeft een doorverwijzing naar 'voeding registreren'.

## Inclusief

SUC-04
