# Visie en scope

## Visie

### Huidige situatie

De huidige databases van voeding houden een immens grote hoeveelheid aan informatie vast. Dit is niet de essentie die nodig is om een verandering in een levensstijl teweeg te brengen en heeft vaak het tegenovergestelde effect, mensen raken zoek in wat belangrijk is en wat randinformatie is.

### Gewenste situatie

De website en desktopapplicatie die ontwikkeld gaan worden, zal deze overflow aan informatie wegwerken en enkel een focus op de essentiële informatie leggen, zijnde calorieën en macronutriënten. Aan de hand van deze korte informatieve gegevens zullen de gebruikers in staat zijn zelf een correct voedingspatroon op te bouwen en zo hun levensstijl in positieve zin te veranderen.

### Businessrequirements

Het bedrijf wilt een applicatie ontwikkelen waarbij essentiële informatie bijgehouden kan worden door de klant. Ook moeten klanten zelf voeding kunnen toevoegen en andere reeds bestaande voeding kunnen valideren. Dit geldt voor zowel voedingswaarden als voor de prijs. Het systeem zal een simpele 'thumbs up' of 'thumbs down' zijn die aangeklikt kan worden bij het bekijken van de voeding. Op deze manier zal de meest correcte data als eerst weergegeven kunnen worden (hoe meer positieve validatie er is, hoe hoger het product scoort).

## Belanghebbenden

### Eindgebruikers

Klant
    Iedereen met als doel om te veranderen. Zij moeten de mogelijkheid hebben om persoonlijke gegevens in te voeren (doelen: gewicht verminderen, bijkomen of op gewicht blijven, huidig gewicht, leeftijd en lengte). Er moet voeding uit de voedingsmiddelendatabase geselecteerd kunnen worden. Zij kunnen een product met foute informatie rapporteren ('thumbs down' geven) of een product met juiste informatie bevestigen ('thumbs up' geven, wanneer meerdere mensen eenzelfde product bevestigen, zal het hoger scoren en dus bovenaan geplaatst worden wanneer anderen naar ditzelfde product zoeken. Ze moeten in de mogelijkheid zijn om voedingsmiddelen toe te voegen, alsook de prijs (afhankelijk per winkel, dit zijn de dagdagelijkse prijzen en niet de reclameprijzen) van het voedingsmiddel moet geregistreerd kunnen worden.
Administrator
    Enkelingen die zorgen voor manuele verificatie en definitieve bevestiging over de waarden van een product. Dit zal voornamelijk gebeuren op producten met een hoge score (veel 'thumbs up'). Zij hebben een aparte interface waar deze acties in plaats kunnen vinden.

### Gebruikersomgeving

Alle Nederlandstaligen die voedsel- en/of prijsbewust zijn, met toegang tot een pc, tablet of smartphone. De front-end zal ontwikkeld worden in de vorm van een responsieve website om op een eenvoudige manier een platform te hebben dat op alle mogelijke manieren bezocht kan worden.

### Overige belanghebbenden

Bedrijven (verkopers)
    Door aanwezig te zijn op de applicatie, kunnen ze kopers naar hun winkel leiden indien ze de goedkoopste producten hebben. Ook kunnen ze hun eigen producten vergelijken ten opzichte van andere verkopers.

## Systeemscope

### Omschrijving van het systeem

Het systeem dient om bestaande databases te implementeren. Ook moet de mogelijkheid er zijn om als klant handmatig voeding in te voeren (voedingswaarden, plaats van aankoop en prijs). Klanten kunnen niet-geverifieerde voeding verifiëren door middel van het 'thumbs up/thumbs down'-systeem. Wanneer een product veel 'thumbs up' ontvangen heeft, zal dit product hoger scoren dan een gelijkaardig product met vele 'thumbs down'. Dit zorgt voor een systeem waarbij foutieve informatie minder vindbaar is en zal de eindgebruiker dus altijd het meest relevante product vinden om toe te voegen aan zijn/haar log.

Mensen kunnen aangeven naar welke winkels ze willen gaan om te winkelen, deze winkels zullen geselecteerd worden uit een lijst van winkels die geregistreerd zijn bij de voeding. Hierna geven ze aan welke producten ze willen kopen. De applicatie zal op basis van deze informatie aangeven in welke winkel het product het goedkoopste is. Deze functie is vooral gericht op studenten of gezinnen die liefst zo weinig mogelijk spenderen aan voeding.

### Positionering van het systeem

Het systeem zal draaien op de servers van Hostgator, deze zijn schaalbaar naarmate er meer dataverkeer is. Er zijn verder geen directe technische beperkingen.

### Globale gebruikersrequirements

Een klant wil via een apparaat naar keuze zijn dagdagelijkse voeding bijhouden of zijn winkellijstje opstellen om zo goedkoop mogelijke inkopen te doen.

### Niet-functionele requirements

Het systeem moet altijd correcte voedingswaarden weergeven. Bij het inloggen moet het wachtwoord altijd niet leesbaar zijn.

## Voorlopige planning

### Risico's

De applicatie moet opboksen tegen grotere al bestaande applicaties, het komt mogelijk traag op gang. Hierop wordt ingespeeld door alle overbodige informatie van reeds bestaande applicaties niet te registreren en een interessante extra functionaliteit toe te voegen (winkelwagentje maken om de goedkoopste producten te vinden).

### Huidig kennisniveau

Er is geen grote basiskennis nodig. Het kunnen gebruiken van een pc, tablet of smartphone en hiermee capabel zijn om het web te doorzoeken is voldoende.

### Plan van aanpak

We gaan dit project aanpakken door middel van SCRUM toe te passen als werkmethdologie. De eerste deelprojecten zullen de focus leggen op het aanmaken van de database en de interactie tussen de database en de back-end.

De taakverdeling gebeurd op basis van de kennis van de leden. Per deelproject zal mogelijk iedereen een andere taak krijgen.

### Bronnen

http://www.ncbi.nlm.nih.gov/pubmed - Huidige aanbevelingen van macronutriënten
http://www.bodydedication.com - Advies vragen uit de praktijk omtrent voeding
https://msdn.microsoft.com - Hoofdbron van het .NET-framework
http://stackoverflow.com - Secundaire bron bij codeerproblemen