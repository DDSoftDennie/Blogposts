# AI op het Copenhagen Developer Festival 2023

## Inleiding

Ik ging naar een festival, ik ging naar een conferentie. Een conferentie op een festival. Een festival op een conferentie. Van 30 augustus tot 1 september 2023 ging ik naar het Copenhagen Developer Festival georganiseerd door NDC Conferences. NDC, ook wel ‘Norwegian Developers Conference’, begon als een conferentie voor programmeurs in Oslo, Noorwegen en is uitgegroeid tot een organisatie met conferenties bijna over de hele wereld.

NDC Conferences zal altijd een speciale plek in mijn hart hebben. Waarom? In 2017 begon mijn carrière als conferentie spreker op NDC Sydney.

Maar deze was speciaal. Copenhagen Developer Festival is de eerste conferentie die ze organiseerden (voor zover ik weet) zonder de naam NDC {Naam_van_de_stad} of een variant bijvoorbeeld: NDC {Security_naam_van_de_stad}. Ze experimenteerden met 3 dagen softwareconferentie en 2 avonden festival. Het festival had de bekende Linebreakers, comedy acts, keynotes over ruimte, luchtballonnen maken, gitaaraoke (karaoke met gitaren), muziekbands en meer.

Hoewel, voor de rest van deze blog zal ik me richten op AI-praatjes op het conferentiegedeelte.

## AI

Ik woonde enkele praatjes bij over de verbazingwekkende huidige tijden en toekomst van AI. Ik koos ervoor om AI-praatjes bij te wonen omdat ik echt geloof dat AI de wereld beter kan maken. Hoewel, ik weet dat er ook enkele gevaren zijn. Laten we de gevaren erkennen en leren hoe AI intern werkt, maar ons richten op de mogelijkheden die AI aan de wereld kan bieden. 

FOTO
Scott Hanselman presenteert zijn Keynote op Stage 1. Het is een foto van Scott. De foto bevat geen dia’s. Iron Man of Ultron: Is AI hier om ons te helpen of te schaden?

Als een AI-liefhebber en -voorstander is het geweldig om te zien dat de enige echte Scott Hanselman, Vice President of Developer Community bij Microsoft, zijn nieuwe keynote presenteerde: “Iron Man of Ultron: Is AI hier om ons te helpen of te schaden?”. In deze sessie presenteerde Scott hoe AI zowel goed als kwaad kan zijn. Hoe menselijke interacties zullen bepalen of de wereld een betere of slechtere plaats gaat worden. De technische focus lag meer op de nieuwere vormen van AI zoals LLM’s (Large Language Models - of Grote Taalmodellen) en GenAI (Generatieve AI). Hier zal ik wat dieper ingaan op 2 specifieke onderwerpen waar Scott het over had. Grote taalmodellen

Grote taalmodellen (of LLM’s) zijn grote modellen die getraind zijn op veel data en kunnen worden gebruikt om tekst te genereren. De bekendste LLM is GPT-3 en GPT-4 is al geboren. GPT-3 is een model getraind op 175 miljard parameters. Die parameters zijn data van het openbare internet: veel e-books, artikelen, blogs, tweets, etc. Het wordt getraind door grote bedrijven of startups. Bijvoorbeeld GPT-3/GPT-4 is gebouwd door OpenAI, een bedrijf uit de VS.

Microsoft heeft een partnerschap met OpenAI en biedt via Azure toegang tot de LLM-diensten van OpenAI in het Azure OpenAI Portal. Wanneer je een instantie van ‘Azure OpenAI’ Service aanmaakt, kun je naar een specifiek portaal gaan.

### Temperatuur

Met het begrijpen van wat moderne AI-oplossingen zoals LLM-technologie zijn, weet je niet het antwoord of de AI ons zal helpen of schaden. Om dit specifieke onderwerp te begrijpen, moet ik je introduceren met temperatuurinstellingen zoals Scott dat voor ons deed in zijn keynote.

Wanneer je een OpenAI-instantie op Microsoft Azure opstart en naar het specifieke portaal gaat is het eerste wat je doet is een model implementeren. Eenmaal geïmplementeerd, kun je het gaan finetunen in de Playground (Playground is een onderdeel van het Azure OpenAI Portal). Een van de belangrijke instellingen heet ‘Temperatuur’. Temperatuur is een instelling die kan worden gebruikt om de willekeurigheid van de gegenereerde tekst te regelen. Hoe hoger de temperatuur, hoe willekeuriger de gegenereerde tekst zal zijn. Hoe lager de temperatuur, hoe precieser de gegenereerde tekst zal zijn. Scott presenteerde dit concept met een mooie metafoor. Kijk naar temperatuur als in de temperatuur van water. Als je het op het maximum zet (onthoud: water kookt bij 100 graden Celsius) Het zal eruit spatten! Het zal overkoken! Het zal willekeurige hallucinaties genereren.

En natuurlijk kun je de temperatuur op het maximum zetten, de LLM laten hallucineren en een artikel publiceren over hoe kwaadaardig (Ultron in de talk) AI is. Of moet je de temperatuur finetunen, zodat de AI zich gedraagt om mensen te helpen en we leven met een Iron Man als onze eigen copiloot? Kijk naar temperatuur als in de temperatuur van water. Als je het op het maximum zet, zal het eruit spatten! Het zal overkoken! Het zal willekeurige hallucinaties genereren.

Scott Hanselman (foto)

## Grote taalmodellen: Een overzicht en integratie in uw workflow

Om nog meer te leren over Large Language Models/ Grote taalmodellen (LLM) technologie ging ik naar Ben Hall & Barbara Fushinka’s praatje genaamd: ‘Large Language Models: An Overview and Integration into Your Workflow’. Als softwareontwikkelaars, als bedrijven, organisaties en bedrijven gaat het niet alleen om naar een website van een openbare AI-provider te gaan, maar om de (niet zo?) magie in je eigen applicaties en workflows te implementeren. Deze lezing ging helemaal over dit proces. Ik zal dieper ingaan op de technologiefamilie waar LLM’s wonen: Transformers. 

### Transformers

Alles begint met het Model. Om dit concept uit te leggen ga ik een paar jaar terug in de tijd toen ‘reguliere’ AI opdook in cloudplatforms en hoe softwareontwikkelaars zoals ik leerden over het concept van AI vergeleken met reguliere softwareontwikkeling. Als je een programma schrijft, schrijf je de logica. Wanneer applicaties draaien, stroomt er een invoer door jouw geschreven logica en geeft je de uitvoer. In feite kun je hier zeggen dat jouw programma de invoer transformeert via jouw geschreven logica naar de uitvoer.

AI is anders. Je schrijft het programma (of gebruik een andere naam: het model) niet. Je selecteert een voorgeprogrammeerd model en laat het model zichzelf verfijnen via veel invoer. Dit proces wordt ‘Training’ genoemd. Tijdens de trainingsfase verzamel je de uitvoer en meet je of het resultaat goed is. Als het resultaat wenselijk is, prijs je het model, als het resultaat niet goed is straf je het model. Dit alles doe je op een cloud en je laat de training draaien tot het zichzelf heeft verfijnd.

Alle modellen hebben een architectuur, net zoals er verschillen en architectuur zijn in  software programmeer talen. Transformers zijn een specifieke architectuur van modellen. Het Large Language Model GPT is een Transformer omdat het gewoon in de naam staat! Generative Pretrained Transformer. Een groot Transformer-model dat voorgeprogrammeerd is op veel data om tekst te genereren. Deze pretraining wordt gedaan door grote bedrijven zoals OpenAI.

 ## Toegepaste AI en toegankelijkheid om op nieuwe manieren te spelen

En omdat ik geloof dat een betere wereld gecreëerd met AI een meer inclusieve en toegankelijke wereld is, heb ik het geluk dat Alex Dunn zijn lezing presenteerde: ‘Toegepaste AI en toegankelijkheid om op nieuwe manieren te spelen’.

Alex was een werknemer bij een softwarebedrijf. Na een tijdje had hij het geluk om zijn eigen bedrijf te vormen vanuit een hobbyproject dat hem nauw aan het hart lag. Alex is een gamer en heeft een neefje met een beperking. Alex’ passie voor gaming en liefde voor zijn neefje maakte dat hij een hobbyproject creëerde om gaming toegankelijker te maken. Met AI-modellen ving hij gebaren op en vertaalde ze naar toetsenbord- en muisinvoer om games te besturen. 

FOTO:
Alex achter de presentatiedesk en de titelzijde met een foto van een kind met een handicap en de tekst: Toegepaste AI en toegankelijkheid. Spelen met je gezicht en stem. 

## Hackathons

 Het project kreeg een boost toen Alex zich inschreef voor een hackathon. Een hackathon is een wedstrijd waarbij je een softwareoplossing creëert voor een probleem. Zoals in elke goede competitie, winnen winnaars een prijs. Wat ik in deze sessie leerde, is dat het echt mogelijk is om aardig wat geld te winnen als je een hackathon wint. Het winnen van de hackathon in combinatie met zijn passie maakte dat hij zijn eigen bedrijf begon.

### De Oplossing

De oplossing die hij bouwde was het trainen van een model dat specifieke gebaren herkent via de camera op je computer/smartphone en audio-invoer en dit koppelt aan macro’s, snelkoppelingen en verschillende soorten besturingen. Een persoon die niet in staat is om toetsenbord, muis, touchscreen of controller op de reguliere manier te gebruiken, kan deze oplossing gebruiken om games te spelen en veel plezier te hebben.

Het maakt gebruik van Azure Cognitive Services, spraakassistentiediensten, aangepaste Web API’s en SignalR-diensten van de Microsoft Azure Cloud.

### Gebruiksscenario’s

Je kunt glimlachen, je hoofd naar links of rechts bewegen, naar je apparaat schreeuwen via een computer of laptop. Er is zelfs een experiment die werkt via Snapchat. En natuurlijk: De huidige dagen vereisen dat het speelbaar is via Twitch. Natuurlijk doet Alex’ oplossing dit ook! Nog meer: verschillende gamers kunnen elkaar helpen door specifieke Twitch-commando’s in de chat te geven.

Gaming kan kwaliteit van leven bieden aan mensen. Dus, waarom zouden we dit wegnemen bij mensen met een beperking? Alex’s oplossing is een geweldig voorbeeld van hoe AI de wereld beter kan maken.

### Conclusie

In deze blog heb ik geschreven over AI-gesprekken op het Copenhagen Developers Festival van NDC Conferences. Ik begon met een korte introductie over het festival en de conferentie. Ik heb 3 AI-gesprekken bijgewoond: Scott Hanselman’s keynote over hoe AI goed en kwaad kan zijn. Ik ging dieper in op de technologie van Large Language Models met de lezing van Ben Hall & Barbara Fushinka. Ik toonde een use case hoe AI een oplossing kan zijn om een betere wereld te creëren voor mensen met een beperking met Alex Dunn’s lezing over hoe hij een oplossing heeft gecreëerd om gaming toegankelijker te maken voor mensen met een beperking.
