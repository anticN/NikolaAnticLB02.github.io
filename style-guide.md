# Front-end Style Guide

## Farben

### Hauptfarben

- Bright orange: `hsl(31, 77%, 52%)`
- Dark cyan: `hsl(184, 100%, 22%)`
- Very dark cyan: `hsl(179, 100%, 13%)`

### Neutrale Farben

- Transparent white (Fliesstexte): `hsla(0, 0%, 100%, 0.75)`
- Very light gray (Hintergrund, Titel, Buttons): `hsl(0, 0%, 95%)`

## Typographie

### Schriftgrösse

- Font size Fliesstext: 15px
- Font size Titel: 45px


### Schriftart

- Family: [Lexend Deca](https://fonts.google.com/specimen/Lexend+Deca)
- Weights: 400

- Family: [Big Shoulders Display](https://fonts.google.com/specimen/Big+Shoulders+Display)
- Weights: 700

Die Fonts können im CSS mit folgendem Code importiert werden:
- `@import url('https://fonts.googleapis.com/css2?family=Big+Shoulders+Display:wght@700&family=Lexend+Deca&display=swap');`

Die Fonts können im CSS folgendermassen verwendet werden:
- `font-family: 'Lexend Deca';`
- `font-family: "Big Shoulders Display";`

## Button
Der Button soll die Maus als `pointer` anzeigen. 
Und soll bei `hover` eine Animation `transition: all .5s ease-in-out;` anzeigen