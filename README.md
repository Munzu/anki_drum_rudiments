# Drum rudiments Anki deck

**All 40 drum rudiments** with the corresponding **music notation** (SVG) and **sound examples** (OGG).

This deck is **not intended for memorization but for practice**. Practice the rudiments as they come up in Anki and rate the difficulty with the answer buttons. Tweak the deck options to fit your practice routine.

Each hand corresponds to one side of the staff line (above and below, respectively). Stickings with the hands switched are shown where needed.
All time signatures are 4/4 unless stated otherwise. 
Sound examples are played on a clave at 60bpm.

The notation is modeled after [drumeo](https://www.drumeo.com/beat/rudiments/), except for the 46 Drag Paradiddle 1, where I found the notation shown by [Vic Firth](https://vicfirth.zildjian.com/education/40-essential-rudiments.html) to be more intuitive.

Notation and sound were done in [Musescore](https://musescore.org/en).

Both light and dark theme are supported.

## Install
Get it [here](https://ankiweb.net/shared/info/35413279) from AnkiWeb.

## Preview
![image](https://user-images.githubusercontent.com/31477160/179700959-ba7deb23-f81f-4c95-9dea-89e17b909a9c.png)

## Template

### Front
```html
<br>
{{Name}}
<br><br>
{{Notation}}
{{#Hands switched}}
<br>
{{Hands switched}}
{{/Hands switched}}
<br>
```

### Back
```html
{{FrontSide}}
</br>
<hr id=answer>
</br>
{{Sound Example}}
```

### Styling
```css
.card {
 font-family: arial;
 font-size: 30px;
 text-align: center;
 color: black;
 background-color: white;
}

.night_mode img {
 filter: invert(1); -webkit-filter:invert(1);
}
```

# Issues

I created this deck for myself so I'm in no way an expert. Please report errors, bugs, suggestions, and other concerns as [issues](https://github.com/Munzu/anki_drum_rudiments/issues) on this GitHub repository.
