Utvärdera webbplatsers laddningstid och användbarhet
=======================

Detta är en rapport som avser att utvärdera och undersöka tre hemsidors laddningstid och användbarhet.

Urval
-----------------------

Jag har valt att undersöka Wikipedia, Netflix och Expressen.se. Jag valde dessa för att kunna jämföra hemsidor som skiljer sig ifrån varandra. Jag är medveten från början att de förmodligen kommer att skilja sig i laddningstid på grund av innehållet på dem. Wikipedia innehåller mycket text, Netflix mycket bilder och rörligt material (videos) och expressen mycket bilder och annonser. 

Metod
-----------------------

Jag kommer att gå in på respektive sida och analysera hemsidan via ett verktyg som mäter laddningstid (GTmetrix). Har även använt devtools för att se storleken på sidorna och hur lång tid de tar att ladda. Resultaten finns sammanställda under denna länk: <a href="https://docs.google.com/spreadsheets/d/1dy17d2R60LFClkEez8Wwz_qVxXuSzYh07f9ND-NUFfo/edit?usp=sharing" alt="länk">Länk</a>

Resultat
-----------------------
<img src="../assets/wikipedia.png" class="max-width" alt="Wikipedia" />
Wikipedia
<p>
Wikipedias desktop sida är helt omptimerad och får ett overall resultat på 99 (av 100) vilket visar på snabb och effektiv laddningstid. Mobilversionen har något långsammare resultat, 84 (av 100). Det mest kritiska var att time to interactive var 5,s s på mobilen vilket är ganska lång tid. Med devtools kan man se att wikipedia har 175 kB resurser som laddas på 1,42 sek. 
</p>

<img src="../assets/netflix.png" class="max-width" alt="Netflix" />
Netflix
<p>
Netflix desktop version har ett overall betyg på laddningdtiden av 73 (av 100) och mobilversionen har ett betyg på 25 (av 100). Time to interactive mobilversion 10s. Mest tid skulle sparas på att ta bort resurser som blockerar renderingen. Med devtools kan man se att Netflix har 3,5 MB som laddas på 7,20 sek.
</p>

<img src="../assets/expressen2.png" class="max-width" alt="Expressen" />
Expressen
<p>
Overall betyget för desktop versionen av Expressen landade på 71 (av 100), mobilversionen landade på 51(av 100). Time to interactive på mobilen är 11,4 s (pga en annanons på startsidan som tar tid att stänga ner).
Time to interactive på desktop är 3,1 s. Med devtools så laddas 6,4 MB resurser på 1,3 min. 
</p>

Analys
-----------------------
Något man kan säga om samtliga sidors laddningstid är att de mobilversionen är långsammare, overallbetyget är sämre en desktopversionen på samtliga sidor. Vi kan se att Wikipedia hemsidan är snabbast, denna innehåller mycket text. Netflixsidan kommer på andra plats, förmodligen för att den innehåller mer information och tar längre tid att ladda. Allra längst tid tar Expressen som har många annonser och bilder som ska laddas igenom. På ett sätt tror jag att laddningstiden på mobil är längre för wikipedia och netflix för att de flesta användare sitter på en desktop. Expressen hade helt ok högt score på mobilversionen i jämförelse med desktopversionen, förmodligen för att de har många användare på mobilversionen. Ett problem som dök upp för samtliga var att det fanns onödig javascript på sidorna, på netflix kan man ta bort resurser som blockerar renderingen och på expressen skulle få bättre score om annonsen som dyker upp på hela startsidan bli bättre om den togs bort. 

Tycker att Wikipedia har en snabb laddningstid 1,42 sek, Netflix har helt okej laddningstid på 7,2 sek. Dock tycker jag Expressen har en riktigt dålig laddnings tid. På sammanlagt 1,3 min för att ladda hela sidan. Skulle säga att allt under 5 sek (beroende på vad det är för sida) är ok.


Övrigt
-----------------------

Skriven av Viktoria Silfverskiöld