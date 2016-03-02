# Use Case ID: SUC-01

**Actoren**: Gebruiker
**Trigger**: Gebruiker wilt zich registreren in het systeem

## Omschrijving

Gebruiker registreert zich op het systeem.

## Precondities

1. Gebruiker moet de website geopend hebben.

## Postcondities

1. De gebruiker krijgt toegang tot de website. 

## Normale flow

1. De gebruiker opent de website.
2. Gebruiker drukt op registreren.
3. Gebruiker vult zijn persoonsgegevens in.
4. Gebruiker vult 2 keer zijn gewenste wachtwoord in.
5. Gebruiker drukt op registreerknop.
6. Systeem controleert de gebruikersgegevens.
7. Een e-mail wordt verstuurd naar de gebruiker.
8. Gebruiker verifieert zijn e-mail.
9. Gebruiker komt op beginpagina.

## Uitzonderingen

3a. De gebruiker vergeet een veld in te vullen.
3a1. Een melding verschijnt op het scherm dat het veld niet is ingevuld.
4a. Het wachtwoord voldoet niet aan de vereisten.
4a1. Een melding verschijnt op het scherm dat het wachtwoord niet voldoet.
6a. De gebruiker is al geregistreerd in het systeem.
6a1. Er wordt gevraagd om een ander e-mailadres te gebruiken of om aan te melden met dat account.

# Use Case ID: SUC-02

**Actoren**: Gebruiker
**Trigger**: Gebruiker wilt zich inloggen in het systeem

## Omschrijving

De gebruiker heeft de mogelijknheid om zich aan te melden op de applicatie.
Dit kan zowel met een Facebook-account als met een account die de gebruiker eerder geregistreerd heeft.
Bij het registreren geeft hij/zij persoonlijke gegevens door, onder andere voornaam, achternaam en e-mailadres.

## Precondities

1. Ofwel een geregistreerde account hebben, ofwel een Facebook-account.

## Postcondities

1. Er is authenticatie gebeurd en heeft toegang verkregen tot de applicatie.

## Normale flow

1. De gebruiker bezoekt de website.
2. De gebruiker vult gebruikersnaam in in het vakje voor de gebruikersnaam.
3. De gebruiker vult zijn/haar wachtwoord in in het vakje voor het wachtwoord.
4. De gebruiker klikt op de inlogknop.
5. Systeem controleert de gebruikersgegevens en wordt doorverwezen naar de indexpagina.

## Alternatieve flow

1. De gebruiker bezoekt de website.
2. De gebruiker klikt op 'Inloggen met Facebook'.
3. Systeem logt de gebruiker in.

## Uitzonderingen op normale flow

4a. Wanneer een gebruiker een veld vergeet in te vullen.
4a1. Komt er een melding op het scherm dat het veld niet is ingevuld.
3a. Als de gebruiker zijn wachtwoord vergeten is.
3a1. Klikt de gebruiker op "wachtwoord vergeten?"-link.
3a2. Het systeem vraagt naar het e-mailadres van de gebruiker en de gebruiker voert deze in en klikt op 'bevestigen'.
3a3. Het systeem stuurt een e-mail naar de gebruiker met een nieuw wachtwoord en een link om het wachtwoord te veranderen.

# Use Case ID: SUC-03

**Actoren**: Gebruiker en administrator 
**Trigger**: De gebruiker wil nieuwe voeding toevoegen aan de lijst, de admin wilt nieuwe voeding toevoegen aan de lijst

## Omschrijving

Via deze module gaat de gebruiker/admin een nieuw item toevoegen aan de database met voeding.

## Precondities

1. Ingelogd zijn.
2. Gebruiker bevindt zich in de voedingslijst (de database).

## Postcondities

1. De gebruiker heeft voeding toegevoegd en krijgt een korte weergaven van het item dat toegevoegd is. 

## Normale flow

1. De gebruiker klikt op het tabblad 'database'.
2. De gebruiker klikt op toevoegen.
3. De gebruiker vult de gevraagde informatie in.
4. De gebruiker klikt op verzenden.
5. De gebruiker krijgt bevestiging over het succesvol toevoegen van het product.

## Uitzonderingen

3a. Onvolledige informatie.
3a1. De gebruiker wordt gevraagd de informatie aan te vullen.

# Use Case ID: SUC-04

**Actoren**: Gebruiker  
**Trigger**: Gebruiker drukt op toevoegen wanneer hij kijkt naar de producten

## Omschrijving

Gebruiker kan zijn voedingslog samenstellen door deze toe te voegen wanneer hij de producten aan het bekijken is in de database.

## Precondities

1. Gebruiker moet aangemeld zijn.

## Postcondities

1. Gebruiker ziet zijn voedingslog.

## Normale flow

1. Gebruiker drukt op tabblad 'producten'.
2. Gebruiker drukt op een product dat hij wilt toevoegen aan zijn log.
3. Gebruiker kan hier kiezen voor 'toevoegen'.
4. Gebruiker zijn product wordt toegevoegd aan zijn voedingslog.

## Inclusief

SUC-03

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

# Use Case ID: SUC-06

**Actoren**: Gebruiker
**Trigger**: De klant wil een lijst maken met gewenste voedingsproducten 

## Omschrijving

Via deze module gaat de gebruiker items selecteren uit de database.

## Precondities

1. Ingelogd zijn.
2. Op het tabblad 'winkelwagen' geklikt hebben.

## Postcondities

1. Beste prijs per product weergeven en in welke winkel dit product te halen is.

## Normale flow

1. De gebruiker klikt op het tabblad 'winkelwagen'.
2. De gebruiker selecteert welke winkels aanwezig zijn in de buurt, dit wordt weergegeven in een lijstje met beschikbare winkels.
3. De gebruiker selecteert uit een lijst welk product hij/zij wilt.
4. Gelijkaardige producten worden vergeleken per winkel en de goedkoopste wordt weergegeven.
5. De gebruiker klikt op toevoegen, het product wordt aan de winkelwagen toegevoegd.

## Uitzonderingen

2. Er zijn geen winkels uit de lijst aanwezig in de buurt van de gebruiker.
2a. Normale flow stopt, gebruiker wordt teruggestuurd naar hoofdscherm.


