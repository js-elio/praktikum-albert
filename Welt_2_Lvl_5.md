## ***Level 5:***  <span style="color: lightgreen">***Rücken An Rücken***


![MyImage](Welt-2-Level-5.png)


```Javascript
while (true) {
    var enemy = hero.findNearestEnemy();
    if (enemy) {
        hero.attack(enemy);
    } else {
        hero.moveXY(40, 35);
    }
}
```