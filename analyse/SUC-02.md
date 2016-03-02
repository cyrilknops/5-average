# Use Case ID: SUC-02

**Actoren**: Gebruiker
**Trigger**: Gebruiker wilt zich inloggen in het systeem

## Omschrijving

De gebruiker heeft de mogelijknheid om zich aan te melden op de applicatie. Dit kan zowel met een Facebook-account als met een account die de gebruiker eerder geregistreerd heeft. Bij het registreren geeft hij/zij
persoonlijke gegevens door, onder andere voornaam, achternaam en e-mailadres.

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
3a3. Het systeem stuurt een e-mail naar de gebruiker met een nieuw wachtwoord en een link om het wachtwoord te veranderen

## Inclusief

/
