# Hoe kies je toegankelijke kleuren?

Als we websites, digitale infogrammen, grafieken, etc... maken is het belangrijk dat de inhoud van deze te gebruiken en te begrijpen is voor iedereen. Het is belangrijk om ervoor zorgen dat iedereen toegang tot de informatie heeft, ook mensen met een beperking. Dit heet een toegankelijk ontwerp. Als ik denk aan een toegankelijk kleurengebruik, dan denk ik aan mensen die kleurenblind zijn en mensen met een verminderd zicht.

Je kan deze blogpost op twee manieren gebruiken:

- Je leest eerst de theorie over kleuren, en leest daarna hoe je praktisch hiermee aan de slag kan door deze blog vanaf boven te lezen.
- Je leest enkel het praktische stuk.


## Hoe we kleuren zien

Ik begin met een stukje theorie over hoe we kleuren zien. Ik leg jullie uit hoe we als mensen kleuren interpreteren via de magische samenwerking van onze ogen en hersenen. Deze kennis is belangrijk om te begrijpen waarom sommige kleurencombinaties moeilijk te onderscheiden zijn voor heel wat mensen.

Uiteraard leg ik later in deze blog nog uit hoe je deze kennis kan gebruiken om je inhoud te testen op toegankelijke kleurencombinaties.

### In het begin was er licht

Alles wat we zien is licht, licht dat weerkaatst wordt door een object. Dit licht komt in onze ogen terecht en wordt door onze ogen omgezet in signalen die naar onze hersenen worden gestuurd. Onze hersenen interpreteren deze signalen als kleuren.

Het licht komt de ogen binnen via de hoornvlies, de lens, pupil tot op het netvlies. Het netvlies is een dunne laag van lichtgevoelige cellen die het licht omzetten in signalen die naar de hersenen worden gestuurd. Het netvlies bevat twee soorten cellen die verantwoordelijk zijn voor het zien van kleuren: kegels en staafjes.

De signalen worden via elektrische golven naar de hersenen gestuurd. De hersenen interpreteren deze signalen als kleuren. 

### Kleurkegels

De kegels zijn verantwoordelijk voor het zien van kleuren. Er zijn drie soorten kegels die elk gevoelig zijn voor een bepaald deel van het lichtspectrum. De ene soort kegel is gevoelig voor rood licht, de andere voor groen licht en de derde voor blauw licht. De hersenen combineren de signalen van deze drie soorten kegels om alle kleuren te kunnen zien.

### Helderheid

De kleuren zien we in een bepaalde helderheid. Helderheid is de lichtintensiteit van een kleur. De helderheid van een kleur wordt bepaald door de hoeveelheid licht die door de kegels wordt opgevangen. Hoe meer licht er door de kegels wordt opgevangen, hoe helderder de kleur.

## Kleurcontrast

Kleurcontrast is het verschil in helderheid tussen twee kleuren. Een goed kleurcontrast is belangrijk om tekst leesbaar te maken. Als de tekstkleur en de achtergrondkleur te weinig contrast hebben, dan is de tekst moeilijk te lezen. Dit is vooral een probleem voor mensen met een verminderd zicht en de (1 op de 12) mannen die kleurenblind zijn.

Naast kleurcontrast voor tekst, is het ook belangrijk dat grafieken, infogrammen, etc... een goed kleurcontrast hebben. Dit is belangrijk voor mensen die kleurenblind zijn.


### Contrast ratio: De helderheid in nummers

De contrast ratio is een getal dat de helderheid van twee kleuren weergeeft. De contrast ratio wordt berekend door de helderheid van de voorgrondkleur te delen door de helderheid van de achtergrondkleur. De contrast ratio is een getal tussen 1 en 21. Hoe hoger de contrast ratio, hoe beter het kleurcontrast.

De contrast ratio wordt berekend met de volgende formule:

```math
contrast ratio = (L1 + 0.05) / (L2 + 0.05)
```

Waarbij `L1` de helderheid van de lichtste kleur is en `L2` de helderheid van de donkerste kleur. De helderheid van een kleur wordt berekend met de volgende formule:

```math

helderheid = 0.2126 * R + 0.7152 * G + 0.0722 * B
```

Waarbij `R`, `G` en `B` de rode, groene en blauwe componenten van de kleur zijn. De helderheid van een kleur is een getal tussen 0 en 1. Hoe hoger de helderheid, hoe lichter de kleur.

Moeten we nu allemaal wiskundige rocksterren worden om de contrast ratio te berekenen en te testen of onze inhoud toegankelijk is? Gelukkig niet. Er zijn tools die ons hierbij helpen.

Naast tools zijn er ook een paar eenvoudige technieken om aan te voelen als de kleuren die je gebruikt een goed contrast hebben. Eerst leg ik de tools uit en daarna een paar basistechnieken.

## Toegankelijkheid

Het WCAG (Web Content Accessibility Guidelines) is een internationale standaard voor toegankelijkheid van websites. Deze standaard bevat richtlijnen voor het ontwerpen van toegankelijke websites. Er zijn veel richtlijnen om alle aspecten van toegankelijkheid te dekken, waaronder kleurcontrast, waar we in deze blogpost dieper op ingaan.

Zoals je in de introductie tot toegankelijkheid (in deze blog)[https://ware.ddsoft.be/nl/shock-de-kennis-over-toegankelijkheidsstandaarden/] kan zien zijn er 4 grote categorieën die belangrijk zijn om websites toegankelijk te maken. Kleurcontrast valt onder de categorie "Perceivable" of wel "Waarneembaarheid". In de nummering van de WCAG valt dit onder 1. Onder deze categorie vallen verschillende subcategorieën. De vierde categorie heet "Distinguishable" of "Onderscheidbaarheid". Als je deze nummers combineert heb je 1.4. Alle richtlijnen rond kleurgebruik vallen onder de categorie 1.4.

### Wat zeggen de richtlijnen over kleurcontrast?

Er zijn verschillende richtlijnen rond kleurcontrast. Al deze richtlijnen hebben spreken over het kleurcontrast via de contrast ratio. Hierboven heb ik al uitgelegd hoe je de contrast ratio kan berekenen. Concreet is dit het wiskundig model waarop ze gebaseerd zijn. Uiteraard hoeft u geen wiskundige superster te zijn. In het laatste hoofdstuk "praktisch" leg ik uit hoe je dit kan testen via gratis tools.

Er zijn 3 belangrijke contrast ratio's die je moet onthouden:

- **4.5:1**: Dit is het minimum contrast ratio voor normale tekst. Dit is de tekst die niet vetgedrukt is en kleiner dan 18pt.
- **3:1**: Dit is het minimum contrast ratio voor grote tekst. Dit is de tekst die groter is dan 18pt of vetgedrukt.
- **7:1**: Dit is het minimum contrast ratio voor tekst die belangrijk is. Dit is de tekst die belangrijk is voor de gebruiker, zoals de tekst in een knop.



## Praktisch

Zoals ik u beloofde hoeft u geen rekenwonder te zijn om te testen of uw kleurencombinaties een goed contrast hebben. Er zijn verschillende tools die u hierbij helpen. Ik geef u een overzicht van de tools die ik het handigst vind:

- Microsoft Accessibility Insights
- WCAG Contrast Checker

### Extensies installeren

Beide tools zijn extensies voor je browser. Dit kan Google Chrome, Firefox, Edge, ... zijn. Ik raad aan om deze extensies te installeren in de browser die je het meest gebruikt.

Je installeert de extensies door naar de instellingen te gaan en te zoeken naar "extensies". Daar kan je zoeken naar de extensie die je wilt installeren. Als je de extensie hebt gevonden, klik je op "installeren". De extensies zoek je in een "store" die bij je browser hoort. Voor Google Chrome is dit de Chrome Web Store, voor Firefox is dit de Firefox Add-ons, .... Als je Microsoft Edge gebruikt kan je de extensies van de Chrome Web Store installeren.

### Microsoft Accessibility Insights

Fouten in kleurcontrast ratio's kan je eenvoudig testen via de optie "Color contrast". Je kan deze optie vinden in de "FastPass" van de extensie. Fast Pass is een snelle manier om de toegankelijkheid van je website te testen. Je kan deze optie vinden in de extensie door op het icoontje van de extensie te klikken en dan op "FastPass" te klikken.

Nadat de test is uitgevoerd, krijg je een overzicht van de fouten. Je kan de fouten bekijken door op de fout te klikken. Je krijgt dan meer informatie over de fout en hoe je deze kan oplossen. Fouten in kleurcontrast ratio's worden weergegeven met het het volgende stukje in het vet "color-contrast". Alle kleurcontrast fouten komen in deze tab terecht. Je kan dan op het pijltje naast het nummer van het aantal fouten klikken om de fouten in detail te bekijken.

Per contrast fout krijg je de volgende informatie:
- Path: Dit is de locatie van de fout in de HTML code.
- Snippet: Dit is een stukje van de HTML code waar de fout zich bevindt.
- How to fix: Dit is een korte uitleg over hoe je de fout kan oplossen.

Bij "how to fix" staat er vermeld wat de huidige contrast ratio is en wat de minimum contrast ratio is. Als de huidige contrast ratio lager is dan de minimum contrast ratio krijg je voorstellen naar andere kleuren die wel een goed contrast hebben.

Weet dat, mocht dit te technisch zijn, je altijd op ons beroep kan doen: [Consulting Toegankelijkheid](https://ware.ddsoft.be/nl/consulting-toegankelijkheid/).


### WCAG Contrast Checker

De WCAG Contrast Checker is een tool die je helpt om de contrast ratio van twee kleuren te berekenen. Je kan deze tool gebruiken om de contrast ratio van de tekstkleur en de achtergrondkleur te berekenen. Je kan de tool vinden in de extensie door op het icoontje van de extensie te klikken en dan op "Contrast Checker" te klikken.

Als deze tool geopend is komt er aan de linker op kant van je scherm een paneel (of "panel" in het Engels). In dit paneel zie je de contrast ratio's en zie je een groen vinkje of een rood kruisje als deze aan de WCAG richtlijnen voldoen. Er Wordt getest op het level "AA", dit is het level die vereist is voor de meeste wetten volgens het European Accessibility Act. Deze richtlijnen bereiken al een groot deel van de bevolking. Als je de contrast ratio's wilt testen voor het level "AAA" kan je dit instellen via de linkse combobox genoemd "Level". Dit kan handig zijn als je een website maakt voor een specifieke doelgroep die een hogere toegankelijkheid vereist.

Weet dat, mocht dit te technisch zijn, je altijd op ons beroep kan doen: [Consulting Toegankelijkheid](https://ware.ddsoft.be/nl/consulting-toegankelijkheid/).


### Shortlist foute kleurencombinaties

Ik geef je een shortlist van kleurencombinaties die je best vermijdt. Deze kleurencombinaties zijn moeilijk te onderscheiden voor mensen die kleurenblind zijn. Deze shortlist is gebaseerd op de meest voorkomende vorm van kleurenblindheid, de rood-groen kleurenblindheid. Deze vorm van kleurenblindheid komt voor bij 1 op de 12 mannen.

- Rood en groen
- Groen en bruin
- Blauw en paars
- Groen en blauw
- Licht groen en geel
- Licht groen en wit
- Blauw en grijs
- Groen en grijs
- Groen en zwart
- Blauw en zwart
- Rood en zwart
- Geel en wit
- Licht groen en wit
- Lichtgrijs en wit
- Donkergrijs en zwart

Het is dus belangrijk dat je deze kleuren niet op elkaar plaatst. Hiermee bedoel ik de tekstkleur en de achtergrondkleur. Als je deze kleuren op elkaar plaatst, dan is de tekst moeilijk te lezen voor mensen die kleurenblind zijn.

Ook is het sterk afgeraden deze kleuren te combineren in een grafiek of infogram. Als je deze kleuren combineert in een grafiek of infogram, dan is de grafiek of infogram moeilijk te lezen voor mensen die kleurenblind zijn.


## Conclusie

In deze blogpost heb ik jullie bijgeleerd over hoe we kleuren zien en hoe we kleuren interpreteren. Ik heb jullie ook bijgeleerd over het belang van kleurcontrast en hoe je kleurcontrast kan testen volgens officiële standaarden. Ik heb jullie ook een shortlist gegeven van kleurencombinaties die je best vermijdt. Deze kleurencombinaties zijn moeilijk te onderscheiden voor mensen die kleurenblind zijn.

Verder kunnen jullie altijd beroep doen op onze Consulting Toegankelijkheid en/ of een [vorming volgen rond kleurtoegengelijkheid] (https://ware.ddsoft.be/nl/vormingen/error-404-kleur-niet-gevonden/) 

## Bronnen

Voor die persoonlijk leiderschap beaamt vind ik het belangrijk om aan bronvermelding te doen.
Ik heb de volgende bronnen geraadpleegd om deze blog te schrijven:

https://www.colourblindawareness.org/
https://github.com/DDSoftDennie/SlideDecks/blob/master/Error%20404%20Color%20not%20found%20JFS.pdf
https://www.theinkrag.com/colour_blindness/monochromacy.html
https://www.w3.org/Translations/WCAG21-nl/




