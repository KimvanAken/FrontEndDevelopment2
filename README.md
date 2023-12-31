# Procesverslag

Markdown is een simpele manier om HTML te schrijven.  
Markdown cheat cheet: [Hulp bij het schrijven van Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).

Nb. De standaardstructuur en de spartaanse opmaak van de README.md zijn helemaal prima. Het gaat om de inhoud van je procesverslag. Besteedt de tijd voor pracht en praal aan je website.

Nb. Door _open_ toe te voegen aan een _details_ element kun je deze standaard open zetten. Fijn om dat steeds voor de relevante stuk(ken) te doen.

## Jij

<details open>
  <summary>uitwerken voor kick-off werkgroep</summary>

### Auteur:

Kim van Aken

#### Je startniveau:

Blauw

#### Je focus:

Surface plane

</details>

## Je website

<details open>
  <summary>uitwerken voor kick-off werkgroep</summary>

### Je opdracht:

[Neopets](https://neopets.com/)

#### Screenshot(s) van de eerste pagina (small screen):

Homepage  
 <img src="readme-images/Screenshot_Homepage.png" width="375px" alt="De Huidige homepagina van Neopets.">

#### Screenshot(s) van de tweede pagina (small screen):

Pagina 2  
 <img src="readme-images/Screenshot_Page2.png" width="375px" alt="Pagina twee van de Neopets website, Fearie's Hope.">

</details>

## Toegankelijkheidstest 1/2 (week 1)

<details>
  <summary>uitwerken na test in 2<sup>e</sup> werkgroep</summary>

### Test 1: Voice Over Bevindingen:

Lijst met je bevindingen die in de test naar voren kwamen:

- Hij begint met het voorlezen van de header links.
- Bij het deel over Friends en Foes loops hij vast. (Ik kan niet makkelijk door alle personage's heen scrollen.)
- Omdat sommige objecten worden weergegeven met een link en een plaatje, wordt de link twee kee opgelezen ondanks dat het de link voor hetzelfde is.
- Bij het zijwaartse scrolldeel geeft de narrator alleen "link" aan.
- De H en D knoppen doen niets bij de homepage. H hoort ervoor te zorgen dat je naar de volgende header kan, en de D hoort naar de volgende "Landmark" of "Container" te gaan, dat gebeurt niet op de pagina.

### Test 2: WCAG Checklist Bevindingen:

Gevonden fouten:

- Content:
  Geen fouten.
  <br>
- Global code:
  Geen, de enige gevonden error is het volgende:
  <br>
  <img src="readme-images/enige-error-html.jpg" width="300px" alt="form field element should have an id or name attribute error">
  <br>
- Keyboard
  Er is een focus stijl, maar die kan iets beter geimplementeerd worden.
  Sommige elementen worden overgeslagen bij keyboard focus.
  Zie bijvoorbeeld de button focus:
  <br>
  <img src="readme-images/buttons-focus-state.png" width="300px" alt="Image die de button focus states vergelijkt.">
  <br>
- Mobile and touch
  De scrollbook section op de pagina is een beetje vervormt en erg lang op mobile.
  <br>
  <img src="readme-images/scrollbook-section.png" width="300px" alt="Scrollbook section Neopets.com">
  <br>
- Headings
  Geen fouten.  
  <br>
- Lists:
  Geen fouten.
  <br>
- Images:
  De alt van de images is vaak niet specifiek genoeg. Als er een karakter is die "Walter" heet, is de alt text gewoon "Walter". Mensen die neit kunnen zien weten niet hoe Walter er uitziet.
  <br>
- Media:
  De carrousels op de pagina kunnen niet op pauze.
  <br>
- Controls:
  Links die in broodtekst staan kunnen duidelijker worden aangegeven.
  Buttons zijn a'tjes met een button class, i.p.v. een button.
  <br>
- Appearance:
  Dark mode is niet supported.
  Hoog contrast mode is aanwezig, maar kan beter geimplementeerd worden, zie het volgende:
  <br>
  <img src="readme-images/hoogcontrast1.jpg" width="300px" alt="Broodtekst met hoog contrast.">
  <br>
  <img src="readme-images/hoogcontrast2.jpg" width="300px" alt="Button see more met hoog contrast">
  <br>
- Animation:
  De animaties zijn subtiel, maar dueren zoms erg lang, elementen die "inschuiven" schuiven ook weer langzaam weg als je wegscrollt, misschien beter om te laten staan?
  <br>
- Color contrast:
  Geen fouten.
  <br>

### Kleurenblindheid bevindingen:

- Blue Cone Monochramacy / Achromatomaly:
  Geen problemen met het gebruik van de website
- Monochramacy / Achromatopsia:
  Ook geen problemen, het contrast van de plaatjes en knoppen is goed genoeg om te zien wat er gebeurt.
- Green-Weak / Deuteranamaloy:
  Geen opmerkingen
- Green-blind / Deuteranopia:
  Geen opmerkingen
- Red-weak / Protanomaly:
  Geen opmerkingen
- Red-blind / Protanopia:
  Geen opmerkingen
- Blue-weak / Tritanomaly:
  Geen opmerkingen
- Blue-blind / Tritanopia:
  Geen opmerkingen.

Bij het gebruik van de website heb ik geen momenten gevonden waar kleurenblindheid de effectiviteit van de website tegenhoudt.

### Andere opmerkingen:

De captcha button zit voor elke elementen. Dit is vooral erg irritant op Mobile.
<br>
<img src="readme-images/captcha-button.png" width="240px" alt="Voorbeeld captcha button uitschuiven">
<br>
Sommige secties van de website laden erg sloom. (Bijv de scroll / book section)

</details>

## Breakdownschets (week 1)

<details>
  <summary>uitwerken na afloop 3<sup>e</sup> werkgroep</summary>

### de hele pagina:

  <img src="readme-images/dummy-plaatje.jpg" width="375px" alt="breakdown van de hele pagina">

### dynamisch deel (bijv menu):

  <img src="readme-images/dummy-plaatje.jpg" width="375px" alt="breakdown van een dynamisch deel">

### wellicht nog een dynamisch deel (bijv filter):

  <img src="readme-images/dummy-plaatje.jpg" width="375px" alt="breakdown van nog een dynamisch deel">

</details>

## Voortgang 1 (week 2)

<details>
  <summary>uitwerken voor 1<sup>e</sup> voortgang</summary>

### Stand van zaken

Ik ben veel van HTML vergeten dus ik weet vaak niet of je dingen in een section moeten zetten, of bij in een nieuwe section aan de onderkant.

### Agenda voor meeting

| Leanne                                                                | Chimene                                                  | Martin                                                                               |
| --------------------------------------------------------------------- | -------------------------------------------------------- | ------------------------------------------------------------------------------------ | --------------------------------------------- |
| Hoe maak je een afbeelding van het logo ook een hidden H1 in de HTML? | Hoe kan ik knoppen/afbeeldingen downloaden v.d. website? | Hoe houdt ik een icoon altijd op dezelfde plek in het scherm?                        |
| Moet er voor de ul een nav?                                           | dit als er tijd is                                       | Hoe krijg ik het lettertype van de website in mijn css?                              | Hoe zorg ik dat iets verdwijnt als ik scroll? |
| Bij H2 "Populair, waar die je de img tag?                             | Maakt het uit welk formaat afbeelding je gebruikt?       | Welke waardes zijn het handigst om te gebruiken als je alles responsive wilt houden? |
| Hoe schrijf ik een bepaald stukje in de HTML van de footer?           | Meerdere links stijlen in css. Kan dit zonder classes?   |

| Kim                                                         | Rosalie                                                                         |
| ----------------------------------------------------------- | ------------------------------------------------------------------------------- |
| Hoe maak je een pauze knop voor een carrousel?              | Hoe laat ik een uitklapmenu groeien                                             |
| Hoe maak ik de gekleurde ronde onderkanten bij de sections? | hoe vergroot ik een image binnen een bepaalde box zonder dat die er buiten komt |
| Hoe loop je een animatie?                                   |
| Waarvoor mocht je nou precies wel een class voor gebruiken? |
| Hoe maak ik een dropdown in een nav link menu?              |

### Verslag van meeting

hier na afloop snel de uitkomsten van de meeting vastleggen

- Hebben het font mysterie niet kunnen oplossen (?) Want hij staat goed gelinkt maar hij is niet zichtbaar.

</details>

## Voortgang 2 (week 3)

<details>
  <summary>uitwerken voor 2<sup>e</sup> voortgang</summary>

### Stand van zaken

Ik loop nog erg achter :"D

### Agenda voor meeting

Leanne:

- Hoe connect ik mijn tweede CSS bestand juist aan de HTML?
- Hoe laat ik de Nav werken?
- Hoe importeer ik het juiste lettertype?
- Hoe verwijder je iets op GitHub?

Chimène:

- hoe krijg ik twee a’tjes naast elkaar als button
- bij een section werkt flex niet
- hoe moet ik column toepassen op een bepaalde section
- menu knop snap ik niet hoe die werkt

Kim:

- Lettertype toepassen werkt niet bij de H2 (?)
- background-size: cover; geeft error aan?
- Hoe fix ik de nav button
- Text shadow krijg ik niet hetzelfde?
- Hoe krijg ik de h2 hetzelfde?

Martin:

- Hoe krijg ik dit icoon helemaal links
  -Hoe maak ik dit carousel
- Hoe is dit handig om te maken met grid.
- Moeten alle buttons naar iets leiden?

### Verslag van meeting

hier na afloop snel de uitkomsten van de meeting vastleggen

- punt 1
- punt 2
- nog een punt
- ...

</details>

## Toegankelijkheidstest 2/2 (week 4)

<details>
  <summary>uitwerken na test in 9<sup>e</sup> werkgroep</summary>

### Bevindingen

Lijst met je bevindingen die in de test naar voren kwamen (geef ook aan wat er verbeterd is):

</details>

## Voortgang 3 (week 4)

<details>
  <summary>uitwerken voor 3<sup>e</sup> voortgang</summary>

### Stand van zaken

<summary>Website screenshot:<summary>

<details> <img src="readme-images/voortgang3.png" width="240px" alt="Voorbeeld captcha button uitschuiven"></details>

Wat goed ging: voortgang met CSS
waar ik nog tegen op kijk maar nog niet heb geprobeerd: Javascript
dit heb ik bijvoorbeeld nodig voor de carrousel, en om animaties te krijgen bij het inladen van sections.

### Agenda voor meeting

**Leanne:**

- Het juiste lettertype werkt niet
- Hoe doe je de zoekbalk in de header een rij naar onder
- Hoe zet ik de H2 en A (Tickets) op de goede positie
- Hoe verander ik volgorde van afbeelding + plaatje? Met flex? Bij “Uitgelicht”
- Het paarse lijntje onder “Recent bekeken” en “Populair” hoe kan ik dat het beste doen?
- Hoe kan ik het beste het zwarte randje in de header maken? Met <p>?

**Chimène:**
Chimène is vandaag niet aanwezig, maar ik heb alsnog haar vragen opgeschreven:

- meer uitleg over @media Queries.
- wil een border om mijn element, maar ik krijg het niet voor elkaar.
- Jusitify conent lijkt niet te werken
- Hoe krijg ik een afbeelding links en tekst rechts met flex?

**Kim:**

- Hoe fix ik de padding bij de icoontjes in de NAV?
- Hoe voeg ik een back to top button toe
- Hoe zat het ook en weer met de 2e pagina en de stylesheets?
- -webkit-background-clip: text; geeft een error, is dat OK?
- Waar kan ik het beste terecht als ik hierna tegen problemen oploop met Javascript?

**Martin:**

- Hoe zorg ik ervoor dat de nav bar blijft staan
- Mag ik hier classes gebruiken?
- Gebruik van pixels

### Verslag van meeting

uitkomsten van de meeting:

Mijn vragen + antwoorden
**- Hoe fix ik de padding bij de icoontjes in de NAV?**
Gefixt met hulp van Sanne

**- Hoe voeg ik een back to top button toe**
Behandelt samen, code hier: https://codepen.io/shooft/pen/xxMKwob
De scroll-behaviour: smooth is handig alleen voor wanneer mensen animaties aanhebben.

**- Hoe zat het ook en weer met de 2e pagina en de stylesheets?**
1 algemene styling: header + footer
1 voor main pagina 1
1 voor main pagina 2

**- -webkit-background-clip: text; geeft een error, is dat OK?**
Het moet eigenlijk zo:
-webkit-background-clip: text; >chromium
background-clip: text; (is voor firefox)
color: transparent;

**- Waar kan ik het beste terecht als ik hierna tegen problemen oploop met Javascript?**
Bij Luuk Brauckmann of Quinesha van Burgh! (s)

</details>

## Eindgesprek (week 5)

<details>
  <summary>uitwerken voor eindgesprek</summary>

### Je uitkomst - karakteristiek screenshots:

  <img src="readme-images/screenshot-hele-pagina-voortgang-eingoplevering.png" width="375px" alt="uitkomst opdracht 1">

### Dit ging goed/Heb ik geleerd:

Ik heb best een pittige website gekozen en toch voelt het wel mogelijk.

### Dit was lastig/Is niet gelukt:

Javascript! Ik heb geprobeerd bepaalde elementen te implementeren zoals de carroussel. Ik heb geprobeerd de code aan te passen omdat ik bijvoorbeeld buttons gebruik i.p.v. links, maar zelfs met de hulp van chatGPT die mij probeerde uit te leggen wat de problemen konden zijn lukte het niet.

  <img src="readme-images/dummy-plaatje.jpg" width="375px" alt="bummer">
</details>

## Herkansing

<details>
  <summary>Voor de herkansing uitgewerkt</summary>

Toegepaste Surface Plane Elementen:

- Dark / Lightmode
- Formulieren
- Advanced Positioning
  (geprobeert:) Scroll animaties

### Je uitkomst - karakteristiek screenshots:

Pagina 1 Licht en Dark:
<img src="readme-images/page1-final-lightmode.png" width="375px" alt="Pagina 1 Lichte Modus">
<img src="readme-images/page1-final-darkmode.png" width="375px" alt="Pagina 1 Donkere Modus">
Nav:
<img src="readme-images/navmenu-final-uitgeklapt.jpg" width="375px" alt="navmenu wanneer uitgeklapt">

Pagina 2 Licht en Dark:
<img src="readme-images/page2-final-lightmode.png" width="375px" alt="Pagina 2 Lichte Modus">
<img src="readme-images/page2-final-darkmode.png" width="375px" alt="Pagina 2 Donkere Modus">

Voor de herkansing heb ik nog bepaalde onderwerpen met Sanne besproken.

De opgeloste problemen:

- navbutton animatie
- cloudbanner verdubbeling weggehaalt
- inladen wanneer scrollen voorgedaan, alleen lukte het toepassen niet alleen
- navicons passend gemaakt op pagina 2

Verder heb ik zelf nog deze problemen opgelost:

- darkmode toegevoegd
- heel pagina 2 afgemaakt
- font groottes aangepast
- Alt tekst toegevoegd voor elke image
- errors in HTML en css weggewerkt
- alle bronnen toegevoegd
- Alle afters toegevoegd bij de titels en sections van de pagina's

Wat lukte niet?

- Inladen met scrollen
- eerste carroussel toevoegen
- Kwast onderkant decoratietoegepast maken bij section 2
- alle states voor elke buttons

## Bronnenlijst

<details open>
  <summary>continu bijhouden terwijl je werkt</summary>

1. Linear-gradient: https://developer.mozilla.org/en-US/docs/Web/CSS/gradient/linear-gradient
2. .visually-hidden class en implementatie: https://css-tricks.com/comparing-various-ways-to-hide-things-in-css/
3. nth-of-type(-n + 4 ) selector: https://stackoverflow.com/questions/18672625/how-to-select-first-2-li-elements-using-css
4. Social media buttons in nav en footer source: Met Sanne in de les
5. Font-border source voor letter effect: https://stackoverflow.com/questions/2570972/css-font-border
6. gradient tekst: https://cssgradient.io/blog/css-gradient-text/
7. border-radius in niet-pixels: https://stackoverflow.com/questions/29966499/border-radius-in-percentage-and-pixels-px-or-em*/
8. gradient-background-image: https://w3schools.com/cssref/pr_background-image.php
9. Bewegende cloud banner in section 2: Vriend die Todd heet
10. Carrousel (door mij): Van Sanne https://codepen.io/shooft/pen/mdBOZLz
11. button styling weghalen: https://stackoverflow.com/questions/2460100/remove-the-complete-styling-of-an-html-button-submit
12. flex-items niet te lang maken: https://stackoverflow.com/questions/33887051/prevent-flex-items-from-stretching
13. Tekst van button op 1 line houden ipv 2: https://stackoverflow.com/questions/5232310/how-can-i-force-div-contents-to-stay-in-one-line-with-html-and-css
14. grid-row: span 2: https://stackoverflow.com/questions/53199146/make-element-take-two-columns*
15. Image als achtergrond bij section 1: https://w3schools.com/cssref/pr_background-image.php
16. embedden van Youtube, accesible: https://www.200ok.nl/tips/youtube-embed/
17. List style bullets veranderen: https://www.w3schools.com/howto/howto_css_bullet_color.asp
18. Aspect ratio calculator voor before en afters: https://andrew.hedges.name/experiments/aspect_ratio/ aspect ratio calculator
19. Images afsnijden met clippy: https://bennettfeely.com/clippy/
20. px naar rem converter: https://nekocalc.com/px-to-rem-converter
21. object-fit: contain in de nav pagina 2: https://sentry.io/answers/how-do-i-auto-resize-an-image-to-fit-a-div-container/
22. background-image op sections: https://w3schools.com/cssref/pr_background-image.php
23. background-attachment: (achtergrond niet laten bewegen section 1 pagina 2): https://www.w3schools.com/cssref/pr_background-attachment.php
24. youtube video responsive laten scalen: https://stackoverflow.com/questions/15844500/shrink-a-youtube-video-to-responsive-width /
25. section laten invliegen (alleen niet gelukt) van Sanne: https://codepen.io/shooft/pen/NWoYKZN

 </details>
