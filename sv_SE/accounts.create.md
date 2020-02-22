**Kostnadskonto**

Skapa kostnadskonton endast för platser du spenderar pengar.

**Intäktskonton**

Skapa intäktskonton endast för platser du får pengar ifrån.

**Tillgångskonton**

Om du skapar ett tillgångskonto, bör du fylla i "öppningsbalansen" och det tillhörande datumet. Väldigt få som börjar använda Firefly III har 0,00 i balans. Istället, så har de redan pengar på sina konton. Ta fram din administration, kontrollera den nuvarande balansen på kontona du lägger till och fyll i dessa.

Rollerna som finns tillgängliga:

- Use "default asset account" for your own accounts.
- Använd "delade tillgångskonton" för hushållskonton.
- Använd "sparkonton" för konton där du sparar pengar.
- Använd "kreditkort" för kreditkort. Du kan lägga till detaljer senare.

**Skulder**

Firefly III har stöd för skulder. Du kan lägga till skuld, lån och övriga skulder som sätt att spåra dessa. För varje skuld kan ni lägga in det belopp ni är skyldig och räntan som betalas.

*Skulder och belopp*

Säg till exempel du är skyldig 1000:-. Det bästa sättet att spåra beloppet är genom att lagra en ny skuld i Firefly III i mängden "-1000". På så sätt påverkas ditt nettovärde och du kan flytta pengar till skulden för att betala av dem. När den når noll, kan du markera kontot som inaktivt och vara stolt över att betalat den.

Andra sättet är om någon är skyldig dig 1000:-. I sådant fall är det **också** en bra idé att spara skulden som ett negativt belopp. När allt kommer omkring har du inte pengar just nu och när den personen betalar dig kommer det att påverka ditt nettovärde positivt.

*Virtuell balans*

Låt oss säga du har en minimum balans på $100;- alla gånger. Ange "-100" så tar Firefly III balansen på 100:- som noll. Om du skapar ett kreditkort konto, lägg då in gränsen för ditt kreditkort (exempelvis 1000:-). Firefly III kommer att visa hur långt din kredit har nått.

Om du vill läsa mer om konton, se då [officiell dokumentation om konton](https://docs.firefly-iii.org/concepts/accounts).