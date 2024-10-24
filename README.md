# The Client - Website (Tumi Mundo)

## Inhoudsopgave: 
* #### [- Inleiding](https://github.com/Lutrian1/all-human-accessible-website/blob/main/README.md#kenmerken)
* #### [- Beschrijving](https://github.com/Lutrian1/all-human-accessible-website/blob/main/README.md#kenmerken)
* #### [- Kenmerken](https://github.com/Lutrian1/all-human-accessible-website/blob/main/README.md#kenmerken)
* #### [- Bronnen](https://github.com/Lutrian1/all-human-accessible-website/blob/main/README.md#bronnen)

## Inleiding

### Doel
Het doel van deze review is om feedback te krijgen op het werk dat is gemaakt, en de opdrachthgever op de hoogte te houden van het werk. 
### Intro
Tumi Mundo is een app/site dat bedoeld is om verhaaltjes in de vorm van audio met nadruk op klanken af te spelen voor kinderen tussen de 6 maanden en 5 jaar. De app stimuleert een 2 talige opvoeding wat uit onderzoek helpt met hersenopbouw. 
## Beschrijving
In deze sprint was het van belang om de gemaakte site van vorige sprint (of een nieuwe), volledig toegangkelijk te maken. Dit betekent dat iedereen met welke fysieke beperking dan ook, onze site zou moeten kunnen navigeren. Dit moesten wij volgens de [A11Y Richtlijnen](https://www.a11yproject.com/checklist/#color-contrast) doen. Met een aantal tools konden wij erachter komen wat moest worden gedaan om dit voor elkaar te krijgen. Zelf hebben we ook tests uitgevoerd om zo de flow van onze website te zien. 

<img width="495" alt="inclusive-microsoft-design-toolkit" src="https://github.com/user-attachments/assets/6e8fb515-23db-4a12-8d3c-5417e28bf69d">

### Lighthouse test
Een Lighthouse test is eigenlijk een snelle toegangkelijkheids test van de A11Y richtlijnen. Ipv dat je al deze richtlijnen 1 voor 1 checked, doet de lighthouse test deze stappen voor je (niet alle, na de test moet ook handmatig worden getest). Tijdens [Mijn eerste test](https://github.com/Lutrian1/all-human-accessible-website/issues/5) behaalde de site een prima score, maar er waren een aantal dingen wat ik kon verbeteren, zoals bijvoorbeeld de volgorde van de HTML. Eenmaal na deze te hebben verwerkt was hij volgens lighthouse 100% toegangkelijk.

<img width="1228" alt="image" src="https://github.com/user-attachments/assets/eec0ff2b-93f5-4148-862e-75cb6546616d">

### Contrast van site
<img width="1238" alt="image" src="https://github.com/user-attachments/assets/2752af50-6254-44f9-8405-f53b1e89b88c">
<img width="1244" alt="image" src="https://github.com/user-attachments/assets/d5193484-1d2b-43ea-8ca9-c6394771e7e7">
<img width="1236" alt="image" src="https://github.com/user-attachments/assets/f53e93e9-d0b7-4dd5-a683-d684cc7d0527">

Ik had ervoor gekozen om de kleuren van de site te veranderen. Toen ik hem op blauw testte, behaalde hij een slecht contrast. Dus zocht ik naar de kleuren die nog enigsinds in het spectrum zaten van het schema die jullie hadden gestuurd via whatsapp. [Hier nog een korte uitleg](https://github.com/Lutrian1/all-human-accessible-website/wiki/Keuze-voor-kleur-wijzeging-(Tumi-Mundo))
### Contrast Themes Windows
Tegenwoordig bied HTML en CSS een optie voor contrast themes binnen windows. Contrast themes is de vervanging van het oude 'hoog contrast modus'. Deze modus zet eigenlijk alles op een hoog contrast wat er dus voor zorgt dat bij velle kleuren de site niet meer toegangkelijk is. 

<img width="875" alt="image" src="https://github.com/user-attachments/assets/41ae0f7c-4f8e-460c-811b-e0ccfa02b9b5">

In mijn site had ik dit verwerkt door middel van de line: 

<img width="400" alt="image" src="https://github.com/user-attachments/assets/d188ac0a-c6dc-422d-a1ff-4c4a9013ffb0">

Deze line zorgt ervoor dat de tekst wit blijft, maar de achtergrond zich nog aanpast volgens de contrast themas:

<img width="1245" alt="image" src="https://github.com/user-attachments/assets/58d0dfe1-15ce-4a76-9786-b702327be135">

## Kenmerken
* Donkere kleuren zodat het contrast voor iedereen toegangkelijk is.
* Nieuwe media queries dat helpen hierbij
* Aria labels dat helpen met screenreader
* Logische volgorde in HTML

## Bronnen

Figma: https://github.com/fdnd-agency/tumi-mundo

Link naar site: [Site](https://lutrian1.github.io/all-human-accessible-website/)

Gesprek Sprint-Review: 

https://github.com/user-attachments/assets/11ecf845-9c9d-471c-a349-c7e87283cf61




