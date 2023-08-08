## ***Level 5:***  <span style="color: orange">***Sandige Straße***



![MyImage](<Welt 3 Level 5.png>)

```Javascript
while (true) {
    var enemy = hero.findNearestEnemy();
    if (enemy) {
        hero.attack(enemy);
    }
    if (!enemy) {
        hero.moveXY(55, 55);
    }
}
```