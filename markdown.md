
# Exercise Grid Intro #
```
Display Grid is een mooie manier om een custom lay-out te maken. 

```

Je hebt nu al gewerkt met flexboxes. Soms zijn er echter scenario's te bedenken, waarbij het werken met flexboxes het onnodig ingewikkeld maakt. Een mogelijke optie is dan om gebruik te maken van display: grid;

Om gebruik te maken van de grid, dien je net als bij flexboxes de parentcontainer de display property te geven.

```css

.parent{
    display: grid;
    grid-template-columns: 200px 200px 200px;
    grid-template-rows: 200px 200px 200px;
}

.child:nth-child(odd){
    background-color: black;
}

```

In bovenstaande voorbeeld wordt er een grid gemaakt van in totaal 9 vakken van 200px bij 200px. Elk oneven element in de grid, krijgt hier een zwarte achtergrondkleur. Je kan op deze manier bijvoorbeeld een schaak- of dambord maken (wat in feite natuurlijk ook een grid is).

Bonusvraag: 
Waarom is het met de huidige css-selector makkelijker om een schaakbord te maken voor bijvoorbeeld "Dragonfly" i.p.v. de standaard variant?
https://en.wikipedia.org/wiki/Dragonfly_(chess_variant)



STUKJE TEKST TOEVOEGEN
Nieuwe Technieken
- display grid: https://developer.mozilla.org/en-US/docs/Web/CSS/grid

- grid-template-columns: https://developer.mozilla.org/en-US/docs/Web/CSS/grid-template-columns

- grid-template-rows: https://developer.mozilla.org/en-US/docs/Web/CSS/grid-template-rows  


Maak dit dragonfly schaakbord nu met de aangeleverde html. Deze dient NIET aangepast te worden.
Gebruik grid fractions om deze responsive te maken

<!-- !Verwachte uitkomst: -->
<!-- !IMAGE -->


# sp


# Exercise Grid Spans #

Als je naar een grid kijkt zie je daar verschillende lijnen in.
Denk bijvoorbeeld aan het spel: "Boter, kaas en eieren". Hierbij heb je een grid van 3 x 3

<!--
------------ <-- eerste lijn
|O | O | x |
------------ <-- tweede lijn
|  | X |   |
------------ <-- derde lijn
|O |   |   |
------------ <-- vierde lijn
-->
*IMAGE uit recources "gridlijnen.png"*

Ditzelfde kun je zien bij de kolommen. Deze lijnen kunnen we gebruiken om aan te geven waar onze objecten willen plaatsen en hoeveel ruimte ze innemen.

```warning
Let op! We beginnen met tellen van gridlijnen bij 1.
```

Maak bij deze opdracht de verwachte uitkomst na met de nieuwe technieken. De kleuren hoeven niet perfect te matchen, maar er hoort wel een duidelijk verschil aanwezig te zijn.

Nieuwe Technieken
- grid-column-start: https://developer.mozilla.org/en-US/docs/Web/CSS/grid-column-start
- grid-row-end: https://developer.mozilla.org/en-US/docs/Web/CSS/grid-row-end


# Exercise Grid Responsive

Een standaard fixed grid is leuk, maar tegenwoordig gebeurt 80% van alle webrequests via een telefoon op tablet. Het is dus ook aan ons als webdevelopers om hier rekening mee te houden.

Zorg ervoor dat de exercise van de vorige opdracht nu de layout aanpast naar een versie die er ook goed uitziet op een telefoon. Kijk naar de verwachte uitkomst wat hier precies mee bedoelt wordt.

Nieuwe Technieken
- media-queries: https://developer.mozilla.org/en-US/docs/Web/CSS/@media
KIJKEN NAAR EXTRA EXERCISE(S)

Verwachte Uitkomst:
*IMAGE uit recources "grid-template-area-mobile.png"*


# Exercise Named areas #

Schrijf de vorige opdracht nu om naar het gebruik met Named Areas. Maak hierbij geen gebruik van template-rows en template-columns.

```warning
Er hoort op het grid alleen een display, (min-)height, gap en nog 1 te gebruiken

Op de elementen in het grid staan geen andere properties dan  naam en kleur!
```

Nieuwe Technieken
- grid-template-area: https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout/Grid_Template_Areas


# Exercise Grid Placement #

Nieuwe Technieken
- justify-items: https://developer.mozilla.org/en-US/docs/Web/CSS/justify-items
- align-items: https://developer.mozilla.org/en-US/docs/Web/CSS/align-items
