# Indices

So you have your array of data elements, but what if you want to access a specific element? That is where indices come in. An **index** refers to a spot in the array. indices logically progress one by one, but it should be noted that the first index in an array is 0, as it is in most languages. Brackets [] are used to signify you are referring to an index of an array.

```javascript
// This is an array of strings
var fruits = ["apple", "banana", "pineapple", "strawberry"];

// We set the variable banana to the value of the second element of
// the fruits array. Remember that indices start at 0, so 1 is the
// second element. Result: banana = "banana"
var banana = fruits[1];
```

{% exercise %}
Define the variables using the indices of the array
{% initial %}
var cars = ["Mazda", "Honda", "Chevy", "Ford"]
var honda =
var ford =
var chevy =
var mazda =
{% solution %}
var cars = ["Mazda", "Honda", "Chevy", "Ford"]
var honda = cars[1];
var ford = cars[3];
var chevy = cars[2];
var mazda = cars[0];
{% validation %}
assert(honda === "Honda");
assert(ford === "Ford");
assert(chevy === "Chevy");
assert(mazda === "Mazda");
{% endexercise %}

De kern van het project
ToolsForEver, groothandel in gereedschappen, heeft aan FastDevelopment gevraagd een nieuwe webapplicatie
te ontwikkelen om het beheer van de voorraad te automatiseren. De belangrijkste functionaliteiten van deze applicatie zijn als volgt.
 Het geven van inzicht aan de directie in de waarde van de voorraad
 Het tonen van de voorraad van een artikel aan de buitendienst
Verder waarschuwt het systeem dat het aantal exemplaren van een artikel beneden een bepaald aantal komt.

ToolsForEver
ToolsForEver heeft op dit moment drie locaties, te weten Rotterdam, Almere en Eindhoven. Het bedrijf is van
plan binnenkort een nieuwe locatie te openen. Op alle locaties is voorraad aanwezig. De directie wil een nieuwe website om de voorraad bij te houden en waar, in een latere fase, klanten zelf hun bestellingen kunnen doen en zij gefactureerd kunnen worden. Eerst wil de directie het voorraadbeheer goed automatiseren.

Aanleiding
De huidige applicatie waarmee de voorraad wordt beheerd, kan niet omgaan met verschillende locaties.
Daarom moet er een nieuwe applicatie worden ontwikkeld waarmee per locatie de voorraad beheerd kan worden.
Algemene beschrijving van de website
De homepage is een openbare pagina van de website. Daarop staat globale informatie over de groothandel
ToolsForEver. Medewerkers kunnen op deze pagina inloggen. Daarnaast is er een openbare pagina met contactinformatie als de vestigingsadressen van de locaties, het postadres, het e-mailadres en de telefoonnummers.
De andere pagina’s zijn alleen voor de medewerkers bestemd. Met die pagina’s kan de voorraad bijgehouden worden en kunnen overzichten worden opgevraagd. Gegevens van de artikelen en de locaties kunnen worden bijgehouden. De buitendienst kan aan de hand van een van de pagina’s zien of een artikel op welke locatie op voorraad is. Ook de gegevens van de locaties zelf kunnen worden bijgehouden.

Doelen van de website
Het doel van de website is voorraadbeheer, zodat per locatie bekend is wat op voorraad is. Daarnaast moeten
medewerkers van de buitendienst snel kunnen zien of gereedschap op voorraad is en op welke locatie, zodat een klant zo snel mogelijk geholpen kan worden.

Doelgroepen van de website
De directie wil op de hoogte zijn van de waarde van de verschillende voorraden. De medewerkers in de
buitendienst willen snel weten of een artikel voorradig is of niet en hoeveel exemplaren er aanwezig zijn op een bepaalde locatie. Andere medewerkers van ToolsForEver moeten de gegevens van de voorraad en van de locaties bijhouden.

Vormgeving
Het logo van ToolsForEver staat links boven. De titel van de pagina komt midden boven en is blauw van kleur.
Onder de titel en het logo komt de inhoud van de pagina. Op de pagina’s waar medewerkers zijn ingelogd, komt de naam van de medewerker rechts boven en er komt een knop om uit te loggen. De achtergrondkleur is zachtgeel.

Informatie op de website
Er komt niet veel informatie op de website. Alleen op de homepage komt wat informatie over het bedrijf
ToolsForEver, omdat die pagina openbaar is. Er staat een korte tekst over ToolsForEver met een foto van het hoofdkantoor en contactinformatie als het postadres, de telefoonnummers en het e-mailadres.

Interactie van de website
 Medewerkers van ToolsForEver moeten kunnen in- en uitloggen.
 De directie of medewerkers namens de directie moeten de verschillende rapportages kunnen opvragen (zie
hieronder de rapportages).
 Medewerkers van de buitendienst moeten op elk moment kunnen opvragen of een artikel op voorraad is
en op welke locatie.
 De voorraad moet bijgehouden kunnen worden als er een bestelling plaatsvindt of als er nieuwe voorraad
binnenkomt.
 Gegevens van artikelen moeten toegevoegd, gewijzigd en verwijderd kunnen worden.
 Gegevens van locaties moeten toegevoegd, gewijzigd en verwijderd kunnen worden.
 Gegevens van medewerkers moeten toegevoegd, gewijzigd en verwijderd kunnen worden.
Overzichten en rapportages
 
                 Waarde voorraad ToolsForEver
datum: 17-01-2013
4
 
Product
  
 
Type
  
 
Fabriek
  
 
Aantal
 
  
Prijs
  
 
Waarde inkoop
  
 
Waarde verkoop
 
 
Locatie Rotterdam
 
Accuboorhamer
WX 382
Worx
10
€ 69,95
€ 699,50
€ 1117,50
4-in-1 schuurmachine
KA 280 K
 
Black & Decker
15
 
€ 55,95
 
€ 839,25
 
€ 1019,25
Verstekzaag
BT-MS 2112
 Einhell
2
 
€ 49,95
 
€ 99,90
€ 134,98
Totaal locatie
 
€ 1638,65
€ 2271,73
 
Locatie Almere
 
Alleszuiger
WD2.200
Kärcher
4
€ 29,95
€ 119,80
€ 191,84
Accuboorhamer
WX 382
Worx
11
€ 69,95
€ 769,45
€ 1229,25
Accuboormachine
PSR 14.4
Bosch
12
€ 59,95
€ 719,40
€ 816,00
33-delige borenset
 
Sencys
54
 
€ 9,95
 
€ 537,30
€ 820,80
Totaal locatie
 
€ 2145,95
€ 3057,89
 
Locatie Eindhoven
 
Workmate
WM 536
Black & Decker
14
€ 49,95
€ 699,30
€ 884,80
Kruislijnlaserset
PCL 20
 
Bosch
11
 
€ 99,95
 
€ 1099,45
 
€ 1346,40
Accuboorhamer
WX 382
Worx
11
€ 69,95
€ 769,45
€ 1229,25
Accuboormachine
 
PSR 14.4
 
Bosch
 
12
 
 
€ 59,95
 
 
€ 719,40
 
€ 816,00
Totaal locatie
€ 3287,60
 
€ 4276,45
 
Eindtotaal
€ 7072,20
€ 9606,07
Bestellijst
Voorraad ToolsForEver
datum: 17-01-2013
  Product
  Type
  
Fabriek
  
Minimumaantal
  
Aantal te bestellen
  Locatie Rotterdam
Verstekzaag
 
BT-MS 2112
 
 
Einhell
 
 
10
 
8
  
Locatie Almere
Alleszuiger
 
WD2.200
 
Kärcher
 
10
6
Accuboorhamer
WX 382
Worx
21
9
  Locatie Eindhoven
Accuboorhamer
WX 382
Worx
20
9
Accuboormachine
PSR 14.4
Bosch
20
8
datum 17-01-2013
  Product
 
  Type
 
  Fabriek
 
  Aantal
 
  Inkoopsprijs
 
  Verkoopsprijs
 
  
Locatie Rotterdam
Accuboorhamer
WX 382
Worx
10
€ 69,95
€ 111,75
4-in-1 schuurmachine
KA 280 K
Black & Decker
15
€ 55,95
€ 67,95
Verstekzaag
BT-MS 2112
Einhell
2
€ 49,95
€ 67,49
  Locatie Almere
Alleszuiger
WD2.200
Kärcher
4
€ 29,95
€ 47,96
Accuboorhamer
WX 382
Worx
11
€ 69,95
€ 111,75
Accuboormachine
PSR 14.4
Bosch
12
€ 59,95
€ 68,00
33-delige borenset
Sencys
54
€ 9,95
€ 15,20
  
Locatie Eindhoven
Workmate
WM 536
Black&Decker
14
€ 49,95
€ 63,20
Kruislijnlaserset
PCL 20
Bosch
11
€ 99,95
€ 122,40
Accuboorhamer
WX 382
Worx
11
€ 69,95
€ 111,75
Accuboormachine
PSR 14.4
Bosch
12
€ 59,95
€ 68,00
