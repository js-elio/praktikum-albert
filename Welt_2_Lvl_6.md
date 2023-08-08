## ***Level 6:***  <span style="color: green">***Waldland Hackebeil***

***Mit der neuen attacke cleave konnte ich nun mehrere  Gegner auf einmal besiegen.***


![MyImage](Welt-2-Level-6.png)


```Javascript
hero.moveXY(23, 23);
while (true) {
    var enemy = hero.findNearestEnemy();
    if (hero.isReady("cleave")) {
        hero.cleave(enemy);
    } else {
        hero.attack(enemy);
    }
}
```