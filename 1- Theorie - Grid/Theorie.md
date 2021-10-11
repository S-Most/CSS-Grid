# Wat is grid?

Grid is een manier waarop je de layout op je webpagina aangeeft. Net als bij flexboxes wordt de display property gebruikt op de parent van de items die je in het grid wilt positioneren. Het grote verschil is dat je niet puur kijkt naar een rij of een kolom, maar naar een raster van rijen en kolommen. <br>

Om grid te gebruiken defineer je eerst deze kolommen en rijen en geef je vervolgens aan waar je wilt dat je content geplaatst wordt.

Laten we kijken naar een voorbeeld:

```CSS
.parent {
    display: grid;
    grid-template-columns: 200px 200px 200px;
    grid-template-rows: 200px 200px 200px;
    gap: 12px;
}

.child {
    background-color: chocolate;
}
```

_In bovenstaand voorbeeld is een grid gemaakt van 3 x 3. Elke cell is hierbij 200 x 200 pixels. Ook is er een spacing van 12px toegevoegd._


## Wanneer gebruik je grid?

Wanneer de structuur op je pagina wat complexer wordt, kunnen grids je hier mooi bij helpen. Je kan met grid namelijk gemakkelijk een gebied targeten met een bepaalde grootte. De inhoud van het grid mag zelfs overlappen. Zo kan je bijvoorbeeld mooi een tekst over een afbeelding heen positioneren, of een eigen fotogallerij maken. Daar zit de echte kracht van grid!

GRID VS FLEXBOX TOEVOEGEN

## Voordat we aan de slag gaan..

Voor dat je zelf aan de gang gaat, wijs ik je graag nogmaals op de developer tools. Zowel Chrome, als Firefox hebben mooie tools om je grid te visualiseren. De shortcuts om die te benaderen zijn hieronder in de tabel weergegeven.
<br>

|         | Windows                                             | MacOS                                            |
| ------: | :-------------------------------------------------- | :----------------------------------------------- |
|  Chrome | RightClick > Inspect <br> Ctrl + Shift + I <br> F12 | RightClick > Inspect <br> Opt + Cmd + I <br> F12 |
| Firefox | RightClick > Inspect <br> Ctrl + Shift + C <br> F12 | RightClick > Inspect <br> Opt + Cmd + I <br> F12 |

<br>

| Begrip | Betekenis                                                                                |
| -------------- | ---------------------------------------------------------------------------------------- |
| Grid           | Raster van kolommen en rijen                                                             |
| Grid-items     | De elementen in het grid-element                                                         |
| Cell           | Losse cell in het grid                                                                   |
| Track          | Gebied van cellen bestaande uit 1 kolom en meerdere rijen, of 1 rij en meerdere kolommen |
| Area           | Gebied van cellen bestaande uit meerdere kolommen en rijen                               |
