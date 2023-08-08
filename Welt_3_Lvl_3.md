## ***Level 3:***  <span style="color: orange">***Oase***



![MyImage](<Welt 3 Level 3.png>)

```Javascript
while (true) {
    var x = hero.pos.x;
    var y = hero.pos.y;
    var enemy = hero.findNearestEnemy();
    if (enemy && hero.distanceTo(enemy) < 10) {
        x = x - 10;
        hero.moveXY(x, y);
    } else {
        x = x + 10;
        hero.moveXY(x, y);
    }
}
```