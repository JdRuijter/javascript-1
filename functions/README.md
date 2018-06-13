# Functions

Functions, are one of the most powerful and essential notions in programming.

Functions like mathematical functions perform transformations, they take input values called **arguments** and **return** an output value.

Normalisatie waarde Voorraad
Lijst gegevens
Titel
Datum
Locatie
Product
Type
Fabriek
Aantal
Prijs
Waarde inkoop Waarde verkoop Totaal locatie Totaal
0e normaalvorm
vast gegeven procesgegeven elementair gegeven elementair gegeven elementair gegeven elementair gegeven elementair gegeven elementair gegeven procesgegeven procesgegeven procesgegeven procesgegeven
Locatiecode, locatie RG (productcode, product, type, fabriek, aantal, prijs)
1e normaalvorm
Locatiecode, locatie
Locatiecode, productcode, product, type, fabriek, aantal, prijs
2e normaalvorm
Locatiecode, locatie
Locatiecode, productcode, aantal Productcode, product, type, fabriek, prijs
3
               3e normaalvorm
Locatie Voorraad Artikel Fabriek
Locatiecode, locatie
Locatiecode, productcode, aantal Productcode, product, type, fabriekscode, prijs Fabriekscode, fabriek
         Normalisatie Bestellijst
Lijst gegevens
Titel
Datum
Locatie
Product
Type
Fabriek
Telefoon
Aantal te bestellen
0e normaalvorm
vast gegeven procesgegeven elementair gegeven elementair gegeven elementair gegeven elementair gegeven elementair gegeven procesgegeven
Locatiecode, locatie RG (productcode, product, type, fabriek, telefoon)
1e normaalvorm
Locatiecode, locatie
Locatiecode, productcode, product, type, fabriek, telefoon
2e normaalvorm
Locatiecode, locatie
Locatiecode, productcode
Productcode, product, type, fabriek, telefoon
               
3e normaalvorm
Locatie LocatieProduct Artikel
Fabriek
Locatiecode, locatie
Locatiecode, productcode
Productcode, product, type, fabriekscode Fabriekscode, fabriek, telefoon
4
         Voorraad ToolsForEver
Lijst gegevens
Titel
Datum Locatie Product Type Fabriek Aantal Inkoopprijs Verkoopprijs
0e normaalvorm
vast gegeven procesgegeven elementair gegeven elementair gegeven elementair gegeven elementair gegeven elementair gegeven elementair gegeven elementair gegeven
Locatiecode, locatie RG (productcode, product, type, fabriek, aantal, inkoopprijs, verkoopprijs)
1e normaalvorm
Locatiecode, locatie
Locatiecode, productcode, product, type, fabriek, aantal, inkoopprijs, verkoopprijs
2e normaalvorm
Locatiecode, locatie
Locatiecode, productcode, aantal
Productcode, product, type, fabriek, inkoopprijs, verkoopprijs
               3e normaalvorm
Locatie Voorraad Artikel Fabriek
Locatiecode, locatie
Locatiecode, productcode, aantal
Productcode, product, type, fabriekscode, inkoopprijs, verkoopprijs Fabriekscode, fabriek
         Samenvoeging
3e normaalvorm Waarde voorraad
Locatie Voorraad Artikel Fabriek
Locatiecode, locatie
Locatiecode, productcode, aantal Productcode, product, type, fabriekscode, prijs Fabriekscode, fabriek
         3e normaalvorm Bestellijst
Locatie LocatieProduct Artikel
Fabriek
Locatiecode, locatie
Locatiecode, productcode
Productcode, product, type, fabriekscode Fabriekscode, fabriek, telefoon
         3e normaalvorm Voorraad ToolsForEver
Locatie Voorraad Artikel Fabriek
Locatiecode, locatie
Locatiecode, productcode, aantal
Productcode, product, type, fabriekscode, inkoopprijs, verkoopprijs Fabriekscode, fabriek
         
3e normaalvorm Samenvoeging
Locatie Voorraad Artikel Fabriek
Locatiecode, locatie
Locatiecode, productcode, aantal
Productcode, product, type, fabriekscode, inkoopprijs, verkoopprijs Fabriekscode, fabriek, telefoon
