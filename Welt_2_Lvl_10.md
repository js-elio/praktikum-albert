## ***Level 10:***  <span style="color: green">***Manische Zwerge***



![MyImage](Welt-2-Level-10.png)


```Javascript
while (true) {
    var enemy = hero.findNearestEnemy();
    var distance = hero.distanceTo(enemy);
    if (hero.isReady("cleave")) {
        hero.cleave(enemy);
    } else if (distance < 5) {
        hero.attack(enemy);
    } else {
        hero.attack("Chest");
    }
}
```