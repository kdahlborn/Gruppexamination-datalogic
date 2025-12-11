# AI-seminarium

## AI och datalogiskt tänkande

### 1 - Datalogiska delprocesser

Prompt: _Hjälp mig att bryta ner vardagsproblemet att laga stuvade makaroner i de fyradelprocesserna: decomposition, mönsterigenkänning, abstraktion och algoritm design._

Vi testade Aizo med olika inställningar men kom fram till samma slutsats – Aizo gav ett väldigt kortfattat svar medan ChatGPT gav en detaljerad redovisning och beskriver varje steg. Dessutom uppmuntrar ChatGPT till att man ska fortsätta konversationen. Den erbjuder också att generera svaret i exempelvis tabellform, en lista eller skriva om det till pseudokod. Det finns ett begränsat antal ord som en prompt kan bestå av när man använder Aizo, vilket kan tolkas som en nackdel. Aizo avslutade sitt svar med “hoppas att detta hjälpte dig” medan ChatGPT ständigt frågar användaren om den är nöjd med svaret eller om den ska vidareutveckla svaret. ChatGPT varnar för att man kan bränna sig, vilket får användaren att uppleva att den bryr sig om en. ChatGPT är dessutom alltid artig och ber om ursäkt om man inte är nöjd med svaret. Aizo på medel nivå inkluderar dock emojis i sina svar, vilket också är ett försök att vara vänlig mot användaren.

Aizo förklarar hur man ska tänka för att lösa problemet medan ChatGPT ger en lösning direkt. ChatGPT känns mer pedagogisk men samtidigt kan det bli överväldigande med all information. Aizo känns mer som en lärare. Aizo förklarar att Decomposition innebär att man delar upp processen i hanterbara steg medan ChatGPT tar upp de exakta stegen. Därför är det lättare att veta hur detaljerade stegen ska vara med hjälp av ChatGPT, medan det kan vara svårare att tyda baserat på Aizo:s svar.

---

### 2 – Från delprocesser till pseudokod

Vi tog ChatGPT:s svar och bad ChatGPT och Aizo (medel nivå, kortfattat svar) att göra om det till pseudokod. ChatGPT:s version liknar mer verklig kod med “while” och “if” etc. Medan Aizo’s var mer kortfattad och liknade mer ett vanligt recept.

#### ChatGPT

```
BEGIN

  // Förbered ingredienser
  GET makaroner
  GET mjölk
  GET salt

  // Börja tillagningen
  POUR mjölk INTO kastrull
  HEAT mjölk UNTIL almost_boiling

  ADD makaroner TO kastrull
  SET heat TO low_or_medium

  // Sjuda och röra
  WHILE makaroner NOT creamy
      STIR
      WAIT 30 seconds
  END WHILE

  // Smaksättning
  TASTE
  IF needs_salt THEN
      ADD salt
  END IF

  SERVE

END

```

---

## AI som studiekamrat

### 3 - Var går gränsen

AI kan ha svårt för att hänga med om man skickar flera kodfiler och man ställer frågor i text mellan filerna. Om man då ber AI-modellen att referera till den “senaste kodfilen” kan det uppstå problem – att den inte förstår vilken fil man menar. Det händer att AI-modeller inte alltid läser igenom de frågor man ställer och därför inte genererar passande svar. Detta kan vara ett problem med logik. Vår uppfattning är att AI-modeller kan ha svårt att hantera stora projekt, då modellen saknar kontext. Vi upplever det som att de glömmer bort information som man har angett, medan den ibland minns viss information väldigt tydligt. I samband med stora projekt finns det risk för att AI-modeller använder tekniker som användaren inte har efterfrågat. AI-modeller förstår inte alltid vad användaren menar, exempelvis om användaren anger att modellen ska bortse från en specifik sak följt av att modellen inte gör det.

---

### 4 - Förklara kod

ChatGPT beskriver koden utförligt och inkluderar en sammanfattning i slutet. Aizo beskriver koden på ett enklare sätt, men denna gång frågade den vad användaren menade och erbjöd att förtydliga beskrivningen. ChatGPT inkluderar både en rubrik och en beskrivning av varje värde medan Aizo endast ger en kortare beskrivning. Aizo buntar ihop kod genom att placera båda värdena med storleken 12px bredvid varandra, till skillnad från ChatGPT som beskriver värdena separat.

---

### 5 - Förslagsbeteenden hos AI

- Det händer att AI-modeller glömmer bort delar av ett chattflöde. De kan ha svårt att skilja på kod som i princip är snarlika varandra. Det kan resultera i att den svarar genom att ange den ursprungliga koden som användaren först skrev in. Det är möjligt att användaren inte ger en bra förklaring för vad den vill att modellen ska göra.
- En tänkbar anledning till varför den anger en äldre lösning är det faktum att den hämtar information från nätet. En äldre lösning förekommer förmodligen betydligt oftare på nätet än mer uppdaterade lösningar. Därför kan den få för sig att det är den mest optimala lösningen, då uppdaterade lösningar inte alls är dokumenterade i samma utsträckning.

---

### 6 - Anpassning av AI

Utan anpassning känns svaren mer formella och informativa. Med anpassningen blev svaret mindre utförligt men mer pedagogiskt. Den gör även liknelser till olika scenarion som användaren kan tänkas känna igen sig i, exempelvis “Det är lite som att förklara något för en vän…”. Svaren är lite mindre tekniska och den lyfter fram liknelser till bussar, cyklar och lastbilar. Med andra ord gör modellen mer liknelser till vardagliga ting. Om man vill förstå sig på helheten av ett koncept så kan anpassningen vara till nytta. Om man däremot vill få rå information och gå ner på detaljnivå inom ett område är anpassningen inte så fördelaktig.

---

### 7 - Effekten av anpassning

Med anpassningen förklarar den hur man ska tänka utan att ge något svar. Utan anpassningen ger den rå kod som användaren direkt kan klistra in i sin IDE. Koden förklaras inte lika utförligt utan anpassningen. Det finns några kommentarer men det är all förklaring som ges. Med anpassningen har den skapat upp en numrerad lista med tips på hur man ska tänka, vilket underlättar för läsningen. Den avslutar med en sammanfattning av punkterna som presenteras i en punktlista. Den anger också hur man kan gå tillväga för att komma igång med programmet.

---

### 8 - När är AI okej?

AI är smidigt att använda när man vill bolla idéer, felsöka. Andra tänkbara scenarion är när man vill kontrollera stavning eller formulering. Den kan också vara händig om man vill generera pseudokod och när man vill ställa frågor och få synpunkter om allt möjligt. Det är praktiskt att man kan förklara sin specifika situation och fråga AI om tips. Då finns det en chans att man får ett bättre svar än vad man skulle kunna hitta på nätet. Det kan vara allt från frågor som kan komma på arbetsintervjuer till koduppgifter. Man bör dock vara medveten om att den kan göra fel och att det den säger inte alltid stämmer.

---

### 9 - Tre största riskerna

Vi anser att de största fallgroparna är bristande förståelse, övertro och beroende. Det krävs att man förstår lösningen som modellen kommer på. Annars finns det risk för att man befinner sig i en situation där man inte kan förklara vad man har gjort. Om man lämnar in en skoluppgift som AI har skrivit är det snarare modellen som blir betygsatt och inte en själv. Då får man ingen uppfattning av vilken nivå man ligger på och det kan bli jobbigt när man inte har tillgång till AI-stöd. Det är också väsentligt att man är medveten om att AI inte alltid har rätt och att den brukar ge för många komplimanger. Då finns det risk för att man utvecklar en övertro på AI. Det faktum att folk vänder sig till AI för självdiagnotisering kan vara skadligt om man utgår från att den alltid har rätt. Det är viktigt att man inte blir för beroende av AI-stöd eftersom man blir begränsad i olika sammanhang.

---

## AI som kodkompis

### 10 - Copilot: styrkor och svagheter

Det är smidigt att man får lösningsförslag som man kan välja att godkänna eller inte. Det är också händigt att den förklarar vad som är fel och att man kan skriva vad man vill få hjälp med direkt i koden. Det är också smidigt att man får flera lösningsförslag. Risken är att man blir för lat och bekväm och inte genomskådar, utan accepterar direkt. Det finns risk för att man överanvänder funktionerna och inte förstår vad man gör. Det finns också risk för att man råkar klicka för fort och råkar acceptera ett förslag. Som student finns det risk att man går miste om nyttig kunskap.

---

### 11 - När är Copilot okej att använda?

Copilot är passande att använda för att skapa boilerplates, bolla idéer, felsöka, skriva kommentarer som förklarar koden och beskriva vad fel beror på. Copilot har mer förståelse för koden och kan förmodligen därför ge bättre förklaringar än exempelvis ChatGPT. Det krävs att man har en övergripande förståelse för koden och att man förstår hur man ska formulera en fråga som kan omvandlas till kod, exempelvis pseudokod. Ju bättre man formulerar en fråga, desto bättre blir resultatet.

---

### 12 - Vad verkar mest användbart?

Snabbheten är det som vi bedömer lockar mest. Det är dock en kombination av snabbhet, bra förslag och att den är välstrukturerad. Det är också lockande att den har kodkontext direkt och att man därför slipper skicka kod. Till skillnad från ChatGPT kan den inte glömma bort kod eftersom Copilot är sammanlänkad med all kod man har skrivit. Den har flera funktioner såsom vanlig chatt, inline chat och ghost text, vilket är lockande.

---

### 13 - Utvecklarrollen i framtiden

Vi är överens om att AI kommer att förändra framtida arbetsuppgifter för utvecklare. Eftersom utvecklare blir mer effektiva med hjälp av AI lär utvecklare bli tilldelade fler arbetsuppgifter. Utvecklare kommer förmodligen att skriva mindre mängd kod men fler prompter. Utvecklare kan bli mer värdefulla genom att de blir mer effektiva och produktiva. Om man har bra förståelse för AI och vet när man har bra användning av AI så kommer man vara intressant för marknaden. Det känns som att utvecklarna kommer vara väldigt värdefulla när det gäller samtal med kunder. Det är svårt att tänka sig att kunder skulle vilja förklara vad de vill beställa för en AI-modell. En AI-modell har inte alltid rätt och kan inte alltid komma på de bästa lösningarna. Det finns risk för att AI-modeller inte skriver kod på det enklaste eller det mest optimala sättet. Det känns som att mänskliga utvecklare krävs för att kunna bedöma om en webbplats är fullständigt tillgänglig eller inte.

---

### 14 - Risker i professionellt bruk

Om en utvecklare använder AI till databaser som används inom en arbetsplats finns det risk för att den läcks ut. Det resulterar i säkerhetsbrister. Det känns riskabelt att förlita sig för mycket på AI. Det finns risk för att AI missar hot och brister i säkerhet som en mänsklig utvecklare skulle notera. Eftersom AI-modeller inte alltid har rätt finns det risk för att de skriver felaktig kod och kanske bryter mot någon licens.

---

## AI generellt

### 15 - Relevanta AI-tjänster

- **Cursor AI** är AI-driven kodeditor som baseras på VS-Code. Ger smarta förslag, autokomplettering, skapar dokumentation, föreslår lösningar och mycket mer. Likt Github Copilot fungerar det som en intelligent assistent som sparar tid, minskar buggar och gör kodningen mer interaktiv.

- **Jira AI Assistant** kan hantera ärendebeskrivningar genom att sammanfatta, översätta eller redigera innehållet. Den kan också generera strukturerade Jira-ärenden baserat på naturligt språk. Med hjälp av naturligt språk kan utvecklare söka efter ärenden och information. Syftet med AI-modellen är att minska den manuella administrationen så att teamet kan lägga ner tid på mer meningsfulla och innovativa arbetsuppgifter.

- **Figma AI** förenklar designprocessen som att byta namn på lager automatiskt för bättre struktur. Det går även att kopiera element som behåller elementets justeringar och proportioner. Med AI kan du som designer arbeta snabbare, smartare och mer kreativt.

---

### 16 - Vad ger mest nytta?

ChatGPT känns nödvändig eftersom den är så anpassningsbar och för att den är gratis. Copilot känns mest relevant inom denna bransch, främst inom yrkeslivet men även under studierna. Det beror på att den är sammanlänkad med koden och att den därför har mest förståelse för koden. Dessutom är den användbar för att den kan hitta och förklara fel. Utvecklaren kan också lära sig nya tekniker med hjälp av Copilot:s lösningsförslag som den dessutom kan förklara.

---
