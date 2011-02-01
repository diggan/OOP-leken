# OOP-leken - [*Nu kör vi ett strukturerat projekt!*](https://www.flashback.org/showthread.php?p=28609926)

## Todo

### Strukturering och uppbyggnad av databas

Vi börjar med en databas.
En tabell som håller i alla böcker. Varje bok har självklart ett unikt ID, men jag tycker att man även ska använda ISBN-nummer. Med hjälp av detta kanske man senare kan hämta information beroende på ISBN vid inregistrering av en ny bok - så att man sparar tid vid inregistrering.

Vi bör även komma överens om en namnstandard, när det gäller tabeller (och självklart på klasser och metoder). Mitt förslag till tabellnamn är att varje tabell ska hantera ett objekt, som då får objektets namn i plural. Varje fält har sedan objektets namn i singular följt av vad fältet ska innehålla. Dessutom ska allt vara på engelska.