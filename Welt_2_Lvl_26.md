## ***Level 26:***  <span style="color: green">***Rückkehr Zur Dornenbusch-Farm***



![MyImage](<Welt 2 Level 26.png>)

```Javascript
 function maybeBuildTrap(x, y) {
    hero.moveXY(x, y);
    var enemy = hero.findNearestEnemy();
    if (enemy) {
        hero.buildXY("fire-trap", x, y);
    }
}
while (true) {
    maybeBuildTrap(43, 50);
    maybeBuildTrap(25, 34);
    maybeBuildTrap(43, 20);
}
```