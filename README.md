# Uppgift: Splitta notan

Splitta notan räknar ut hur mycket varje vän ska betala på exempelvis en restaurang när notan kommer. Användaren matar in summan, antal vänner och sedan dricks (**som skrivs i decimalform d.v.s 10% blir 0.10**).

## Instruktioner

1. Koppla js-filen index.js till html-filen index.html
2. Använd document.getElementById för att hämta värden för Summa, Antal vänner och Dricks. Tilldela vardera värde till variabel i index.js. Tänk på att ange relevant namngivning på variabler.
3. När användaren trycker på RÄKNA
   1. Räkna ut vad varje person ska betala m.h.a av de variabler du deklarerat.
   2. Visa resultatet i elementet med id="friendSum"
   3. Dölj elementet med id="inputForm" och visa elementet med id="ShowSum". Använd av document.getElementByID("lämpligt ID").classList.toggle('hide') som lägger till/tar bort klassnamnet på/från elementet, d.v.s togglar. I css ska du använda .hide {display: node} som döljer ett element.
4. Styla formuläret för mobil. Jag förväntar mig ett snyggt och användbart UI!
5. Publicera på Github Pages (fråga läraren om hjälp). Utvärdera din app på din egen mobil!

Lycka till!
