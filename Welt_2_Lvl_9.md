## ***Level 9:***  <span style="color: green">***Beschützer Des Bauern***



![MyImage](Welt-2-Level-9.png)


```Javascript
while (true) {
    var enemy = hero.findNearestEnemy();
    var distance = hero.distanceTo(enemy);
    if (distance < 10) {
        hero.attack(enemy);
    } else {
        hero.moveXY(40, 42);
    }
}
```