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