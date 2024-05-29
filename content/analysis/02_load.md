Load
=======================


I denna uppgift har tre webbplatser valts ut för analys. För att samla in mätvärden används verktyg som Google PageSpeed Insights och webbläsarens utvecklarverktyg.

För varje webbplats tas en snapshot och prestandan mäts med Google PageSpeed Insights för både mobila och stationära enheter. Dessutom mäts laddningstider, antalet resurser och sidans totala storlek med webbläsarens utvecklarverktyg. Mätningarna utförs tre gånger för varje sida, samt för både mobil och desktop, och ett snitt tas av resulterande mätvärden.

Alla mätvärden dokumenteras i ett google sheet och inbeddas sedan in i analysrapporten för tydlighet. För varje webbplats diskuteras möjliga förbättringar baserat på mätresultaten.

Efter att ha genomfört analysen för varje webbplats sammanfattas resultaten och de vanligaste förbättringsåtgärderna diskuteras. Webbplatserna rangordnas baserat på deras mätvärden och en vinnare utses.


Urval
-----------------------

De webbplatser som valts ut för denna analys är:

1. [Mazda](https://www.mazda.se/)
2. [Volkswagen](https://www.volkswagen.se/)
3. [BMW](https://www.bmw.se/)

Urvalet gjordes genom att välja tre webbplatser från bilindustrin. Dessa webbplatser är jämförbara eftersom de alla tillhör samma bransch och har liknande innehåll och målgrupper. Att jämföra liknande webbplatser gör det lättare att dra slutsatser om deras prestanda och potentiella förbättringar då innehållet kan förväntas vara relativt liknande.

Genom att fokusera på en specifik typ av webbsida kan man identifiera specifika prestandaproblem som är unika för det ämnesområdet. Till exempel, om man jämför flera nyhetssajter kan man upptäcka gemensamma utmaningar relaterade till hantering av dynamiskt innehåll och snabba uppdateringar. Denna inriktade analys ger insikter som kan leda till prestandaförbättringar som är relevanta för den specifika typen av webbplats.

Samtidigt kan en bredare analys av olika typer av webbplatser hjälpa till att identifiera allmänna prestandaproblem som är vanliga över flera branscher. Genom att inkludera en mångfald av webbplatser i analysen kan man upptäcka problem som är mer utbredda. Denna bredare analys kan leda till insikter och lösningar som är användbara för en större mängd webbplatser, vilket i sin tur kan höja den övergripande webbkvaliteten, fast detta är någonting som bör göras på en större skala
och därav tycker inte jag att det är passande för just nu.

Metod
-----------------------

För att utföra undersökningen har följande metod använts:

1. **Google PageSpeed Insights:** Används för att mäta prestandan för både mobila och stationära enheter. Mätningar utförs tre gånger och ett snitt tas av resultaten.
2. **Webbläsarens utvecklarverktyg:** Används för att mäta laddningstider, antalet resurser och sidans totala storlek. Även här utförs mätningarna tre gånger och ett snitt tas.
3. **Google Sheet:** Alla mätvärden dokumenteras och visualiseras för att tydligt kunna jämföra resultaten.

Resultat
-----------------------

**Genom analysen av Mazda, BMW och Volkswagen webbplatser på både mobila och desktopplattformar, kan flera slutsatser och resultat dras:**

Prestandaoptimering: Samtliga tre webbplatser presterar relativt oimponerande inom denna kategori, speciellt när det kommer till mobilupplevelsen. Ett medel på 43 på mobil är lite väl lågt. 

Relativt bra med snabba laddningstider, särskilt på mobila enheter.

Tillgänglighet: Tillgänglighetspoängen är varierande över de olika webbplatserna men ligger överlag på en medelgod till hög nivå. Det finns dock här också fortfarande utrymme för att förbättra tillgängligheten.

Bästa Praxis och SEO: Alla tre webbplatser visar god efterlevnad av bästa praxis för webbutveckling och har starka SEO-prestanda. Detta är viktigt för att säkerställa att webbplatserna ger en bra användarupplevelse.

Resursanvändning: Genomsnittliga överförda resursmängder och totala resursstorlekar varierar över webbplatserna, men det finns en tendens till att de är relativt höga. Det finns därmed utrymme för optimering av resursanvändningen för att minska belastningen på nätverket och förbättra laddningstiderna ytterligare.

Webbplatsstruktur: Antalet förfrågningar varierar också mellan webbplatserna, vilket tyder på olika komplexitetsnivåer i webbplatsstrukturen. Det kan finnas möjligheter att förenkla och effektivisera webbplatsstrukturen för att minska antalet förfrågningar och förbättra prestandan.


#### Sammafattningsvis:

Baserat på analyserna av Mazda, BMW och Volkswagens webbplatser, är det svårt att utse en klar vinnare bland dem. Valet beror helt på vilka kriterier som man tycker bör prioriteras vid bedömningen av sidorna. Alla tre har områden som kan förbättras och kräver uppmärksamhet, men överlag är alla sidorna välgjorda. Prestandaoptimering, tillgänglighet, bästa praxis och SEO är alla områden där det finns utrymme för förbättringar. Men det är tydligt att alla tre varumärkena lägger stor vikt vid att erbjuda en god användarupplevelse online.

Analys
-----------------------

För alla sidor jämfördes startsidan utan att interagera med något innehåll.

<iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vQLlY4t6CkvFWu5K-iK5eL8w7zUMdm2Z4GQXr4GG8yFUOm7SeqXM1MtD52X8-XJkdH-ch0tgJE4-brp/pubhtml?gid=0&amp;single=true&amp;widget=true&amp;headers=false" class="excel-arch"></iframe>


## Mazda

<img src="%assets_url%/img/analysis/mazda.png" class="snapshot" alt="mazda" width="400">

### Mobil
Mazdas webbplats presterar relativt bra på mobila enheter med en genomsnittlig laddningstid på 0,717 sekunder och en First Contentful Paint (FCP) på 0,422 sekunder,
vilket innebär att innehållet visas snabbt. Dock är prestandapoängen låg, 30,33, vilket tyder på att det finns stora möjligheter till optimering, särskilt vad gäller
hanteringen av JavaScript och andra resurser. Tillgänglighetspoängen är medelgod på 66, vilket indikerar att det finns betydande tillgänglighetsproblem att åtgärda.
Bästa praxis-poängen är 82, vilket är bra men kan förbättras genom att följa etablerade webbutvecklingsprinciper. SEO-prestandan är utmärkt med en poäng på 92,
vilket visar att webbplatsen är väloptimerad för sökmotorer. Med en genomsnittlig överförd resursmängd på 2,2 MB och en total resursstorlek på 6,8 MB, är webbplatsen
relativt tung, vilket tyder på att ytterligare optimering av media kan vara nödvändig. Det höga antalet förfrågningar, 116, kan också optimeras genom att kombinera filer
och minska beroenden.

### Desktop
På desktop presterar Mazdas webbplats bättre än på mobila enheter. Med en genomsnittlig laddningstid på 0,988 sekunder och en FCP på 0,614 sekunder, är webbplatsen
fortfarande snabb. Prestandapoängen är betydligt högre på 76,33, vilket indikerar att webbplatsen är bättre optimerad för desktopanvändning. Tillgänglighetspoängen är
något bättre än på mobil, 66,67, men samma problem kvarstår. Bästa praxis-poängen är högre på 91, vilket visar en bra efterlevnad av bästa praxis. SEO-poängen är lika
hög som på mobil, 92. Dock är den genomsnittliga överförda resursmängden något högre på 3 MB, vilket tyder på tyngre resurser eller mindre effektiv kompression. Den
totala resursstorleken är densamma som på mobil, 6,8 MB, vilket indikerar att samma resursbas används. Antalet förfrågningar är något lägre än på mobil, 112, vilket
tyder på en något enklare struktur.

## BMW

<img src="%assets_url%/img/analysis/bmw.png" class="snapshot" alt="bmw" width="400">

### Mobil
BMWs webbplats presterar mycket bra på mobila enheter med en mycket snabb laddningstid på 0,591 sekunder. FCP är dock något långsammare på 0,671 sekunder, vilket kan
påverka den initiala användarupplevelsen. Prestandapoängen är bättre än Mazdas, 41, men det finns fortfarande utrymme för förbättringar. Tillgänglighetspoängen är
perfekt, 100, vilket indikerar utmärkt tillgänglighet. Bästa praxis-poängen är relativt låg på 74, vilket tyder på att många bästa praxis inte följs. SEO-poängen är bra
men kan förbättras, 86. Den genomsnittliga överförda resursmängden är 2,3 MB, vilket är rimligt och bidrar till snabba laddningstider. Den totala resursstorleken är 6,1 MB,
något mindre än Mazdas, vilket indikerar bättre optimering. Antalet förfrågningar är lägre än på Mazdas webbplats, 86, vilket tyder på en enklare webbplatsstruktur.

### Desktop
BMWs webbplats presterar också mycket bra på desktop med en genomsnittlig laddningstid på 0,798 sekunder. FCP är snabbare än på mobil, 0,539 sekunder, vilket säkerställer
en snabb initial rendering. Prestandapoängen är hög på 82,67, vilket indikerar bra optimering. Tillgänglighetspoängen är perfekt, samma som på mobil, 100. Bästa praxis-poängen
är samma som på mobil, 74, vilket indikerar att samma problem kvarstår. SEO-poängen är något lägre än på mobil, 83, vilket tyder på vissa SEO-problem specifika för
desktopversionen. Den genomsnittliga överförda resursmängden är betydligt lägre än på mobil, 1,2 MB, vilket indikerar effektiv resursanvändning. Den totala resursstorleken
är densamma som på mobil, 6,8 MB, vilket indikerar samma resursbas. Antalet förfrågningar är samma som på mobil, 86, vilket tyder på en väloptimerad webbplatsstruktur.

## Volkswagen

<img src="%assets_url%/img/analysis/volkswagen.png" class="snapshot" alt="volkswagen" width="400">

### Mobil
Volkswagens webbplats presterar också bra på mobila enheter med en snabb laddningstid på 0,693 sekunder och en mycket snabb FCP på 0,206 sekunder, vilket säkerställer
en utmärkt initial användarupplevelse. Prestandapoängen är bäst bland de tre webbplatserna, 58, men det finns fortfarande utrymme för förbättring. Tillgänglighetspoängen
är hög, 94, vilket indikerar god efterlevnad av tillgänglighetsstandarder. Bästa praxis-poängen är utmärkt, 96. SEO-poängen är bra men kan förbättras, 85. Den genomsnittliga
överförda resursmängden är 2,4 MB, vilket är liknande andra webbplatser och bidrar till snabba laddningstider. Den totala resursstorleken är den största bland webbplatserna,
7 MB, vilket tyder på potential för optimering. Antalet förfrågningar är betydligt lägre än på de andra webbplatserna, 37, vilket tyder på en enklare webbplatsstruktur.

### Desktop
På desktop presterar Volkswagens webbplats bra med en genomsnittlig laddningstid på 0,737 sekunder och en mycket snabb FCP på 0,217 sekunder, vilket säkerställer en
snabb initial rendering. Prestandapoängen är bra men lägre än på mobilversionen, 55,33, vilket indikerar utrymme för förbättring. Tillgänglighetspoängen är hög, samma
som på mobil, 94. Bästa praxis-poängen är också hög, 96. SEO-poängen är samma som på mobil, 85. Den genomsnittliga överförda resursmängden är något högre än på mobil,
3 MB, vilket tyder på tyngre resurser. Den totala resursstorleken är densamma som på mobil, 7 MB, vilket indikerar samma resursbas. Antalet förfrågningar är samma som
på mobil, 37, vilket tyder på en väloptimerad webbplatsstruktur.




Referenser
-----------------------

<h4>Verktyg:</h4>
<ul>
    <li><a href="https://pagespeed.web.dev/">Page Speed</a></li>
    <li>Brave Devtools</li>
</ul>

<h4>Webbsidor:</h4>
<ul>
    <li><a href="https://www.mazda.se/">Mazda</a></li>
    <li><a href="https://www.volkswagen.se/">VolksWagen</a></li>
    <li><a href="https://www.bmw.se/">BMW</a></li>
</ul>

Övrigt
-----------------------

Rapport av josf23 - Joel Sjölund
