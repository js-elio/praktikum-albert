## ***Level 31:***  <span style="color: lightgreen">***Signalleiche***



![MyImage](<Welt 2 Level 31.png>)

```Javascript
while (true) {
    var green = hero.findFlag("green");
    var black = hero.findFlag("black");
    var nearest = hero.findNearestEnemy();
    var enemy = hero.findNearestEnemy();
    if (green) {
        hero.pickUpFlag(green);
    } else if (black && hero.isReady("cleave")) {
        hero.pickUpFlag(black);
        hero.cleave(enemy);
    } else if (nearest && hero.distanceTo(nearest) < 10) {
        hero.attack(enemy);
    }
}
```