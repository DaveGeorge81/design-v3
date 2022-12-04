---
Title: Load times
Description: This is our index page.
---

Load times
=========================
I den här rapporten kommer jag titta på tre olika webbplatser och hur snabbt dessa laddas. Jag kommer även titta på eventuella förbättringar som kan göras för att korta ned laddningstiden.

Urval
--------------------------
Jag har valt tre olika webbplatser som av olika karaktär. Skolverket.se är en statlig sida, mcdonalds.se är inriktad på mat och dn.se är en nyhetssida tillhörande dagstidningen Dagens nyheter. Anledningen till att jag valde dessa sidor är att jag ville ha olika inriktningar på innehållet och att jag både ville ha sidor som använder sig av reklamannonser och sidor som inte gör det.

Metod
--------------------------
För att kunna mäta hur snabbt de olika sidorna laddas har jag valt att köra dem genom Google pagespeed, som ger ett resultat mellan 1 - 100, där kontrolleras både mobil- och desktopvarianten av sidan. Jag kollar även på sidorna via webbläsarens webtools där jag kan se vad som laddas, hur snabbt det går samt hur mycket data som tas emot.

Resultat
--------------------------
I tabellen nedan finns det resulat jag kommit fram till:
<div class="sheet">
<iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vR5EH9CWV4etPtWBl6DuI0TSJYrEQXmFQ25kJOwa4YB2qbhUjHKHOhCqHUOerbAFmp7rZqROITuYdP4/pubhtml?gid=0&amp;single=true&amp;widget=true&amp;headers=false"></iframe></div>

<p>Skolverket:</p>
<a href="%base_url%/image/skolverket.png"><img src="%base_url%/image/skolverket.png?save-as=jpg&w=200" alt="skolverket"></a>
<p>Det främsta som skulle kunna förbättras här är enligt pagespeed att ta bort resurser som blockerar renderingen, som onödiga css-filer och javascript som inte används.</p>

<p>McDonalds:</p>
<a href="%base_url%/image/mcd.png"><img src="%base_url%/image/mcd.png?save-as=jpg&w=200" alt="McDonalds"></a>
<p>Mcdonalds.se skulle kunna förbättra sin inladdningstid genom att komprimera bilder till ett mindre format.</p>

<p>DN.se</p>
<a href="%base_url%/image/dn.png"><img src="%base_url%/image/dn.png?save-as=jpg&w=200" alt="dn"></a>
<p> Enligt pagespeed så är det som skulle påverka inladdningstiden mest att skjuta upp inläsningen av javascript tills att de ska användas.</p>

Analys
--------------------------
När jag har undersökt dessa tre webbplatser närmare så verkar generellt de mobila varianterna av sidorna långsammare än desktops versionen. Samtliga tre får låga betyg från pagespeed i mobilt läge, men DN.se är trots detta betydligt högre än de andra två. Skolverkets hemsida är den som är minst resurskrävande, och borde då rimligen vara snabbare, men så är inte fallet. Vid testerna som gjordes var skolverket.se den sida med längst laddningstid. Det rör sig dock inte om några jättelånga tider, utan sträcker sig knappt till 1,5 sekunder. Något jag noterade var att det laddas väldigt mycket css-filer, vilket även pagespeed anmärkte på. Att minska på detta skulle möjligen kunna sänka laddningstiden något.

McDonalds.se var den sida som överförde mest data av de tre sidorna, likväl var detta den sida som hade kortast laddningtid generellt. Deras mobilvariant var dock den som presterade lägst på pagespeed med endast 24/100. Sidan innehåller många onödigt stora bilder, som med fördel kunde minskats eller sänkt kvaliteten på. 

DN.ses desktopvariant får ett väldigt bra betyg av pagespeed med 96 av hundra. Pagespeed har inte mycket att anmärka på, förutom att det finns lite onödiga javascript som inte används. Jag hade en tanke om att eftersom detta var en sida med reklamannonser skulle det ta längre tid att ladda in, men min tes stämde dåligt, då sidan laddar relativt fort med ett snittvärde en dryg sekund.

Förbättringspotentialen hos samtliga sidor verkar främst ligga på att optimera koden, att inte köra några onödiga skript eller att komprimera bilder till ett mindre eller snabbare format. Rent statistiskt sett så skulle jag rangordna dem som DN först, följt av Skolverket och sist McDonalds. Samtliga sidor anser jag dock laddar godkänt snabbt. Jag skulle uppskatta en webbplats som snabb om den laddar på runt 1-1,5 sekunder. En webbplats jag skulle uppleva som långsam är en sida som tar upp emot 3-4 sekunder att ladda. Det låter inte som en särskilt lång tid, men när de flesta sidor verkar ligga mellan 1-2 sekunder upplevs det dubbla som stor skillnad.

Referenser
--------------------------
Datan har uppmäts med hjälp av pagespeed (https://pagespeed.web.dev/)


Övrigt
--------------------------
Jag som skrivit rapporten heter David Dahlgren.