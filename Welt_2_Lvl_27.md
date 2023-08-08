## ***Level 27:***  <span style="color: green">***Coinucopia***

***Dieses Level unterscheidet sich von allen anderen, denn man kann währenddessen sich die Spielfigur bewegt, Flaggen plazieren, um der Spielfigur den Weg zu weisen.***

![MyImage](<Welt 2 Level 27.png>)

```Javascript
 while(true) {
    var flag = hero.findFlag();
    if (flag) {
        hero.pickUpFlag(flag);
    }
    else {
        hero.say("Platziere die Flagge für mich, um mir den Weg zu weisen.");
    }
}
```