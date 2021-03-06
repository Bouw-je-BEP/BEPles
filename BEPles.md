```package
Bouw je BEP=github:bouw-je-bep/bouw-je-bep
```
# Bouw je BEP

## 1. Daar gaan we! @unplugged

In de volgende stappen gaan we aan de slag met programmeren. Lees alle stappen goed door. 

Let's go! 
![BEP figuur](HYPERLINK NAAR AFBEELDING ONLINE)

## 2. Geef BEP een hart! @showhint

Sleep uit ``||basic:Basis||`` het blokje ``||basic:toon lichtjes||`` en zet hem in de ``||basic:de hele tijd||`` blok en teken een hart!

![An animation that shows how to drag a block and paint a heart](/static/mb/projects/flashing-heart/showleds.gif)

```namespace```
Het komt er dan zoals hieronder uit te zien!
```

```blocks
basic.forever(function() {
    basic.showLeds(`
        . # . # .
        # # # # #
        # # # # #
        . # # # .
        . . # . .`);
})
```

## 3. Geef BEP een naam! @showhint
Sleep nu uit ``||basic:Basis||`` het blokje ``||basic:toon tekens||`` en zet deze in ``||basic:bij opstarten||``. Schrijf in dit nieuwe blok de naam van jouw BEP.

```blocks
basic.showString("typ hier de naam van jouw BEP")
})
```

## 4. Controleer je code! @showhint
Je zou nu links bij de 'test' @boardname@ op je scherm, 1x BEP's naam moeten zien en daarna het hart.

Dat komt door de twee start blokken ``||basic:bij opstarten||`` en ``||basic:de hele tijd||``
Als de micro:bit aangaat zal deze eerst alle blokjes uit de ``||basic:bij opstarten||`` uitvoeren en daarna herhaald de micro:bit de blokjes uit ``||basic:de hele tijd||``

Als dit is gelukt gaan we dit nu op jouw BEP programmeren!
```blocks
basic.showString("BEP")
basic.forever(function() {
    basic.showLeds(`
        . # . # .
        # # # # #
        # # # # #
        . # # # .
        . . # . .`);
})
```

## 5. De code naar BEP sturen
Zoals je hebt gemerkt werkt je geprogrammeerde code niet direct op jouw BEP. Daarvoor moeten we hem eerst ``|Download|`` naar de micro:bit. 
Als je de @boardname@ aan hebt gesloten met de USB kabel op je chromebook mag je op ``|Download|`` klikken om jouw code naar BEP te sturen!
