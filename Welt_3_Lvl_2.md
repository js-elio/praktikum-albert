## ***Level 2:***  <span style="color: orange">***Das Gewaltige Sandyak***



![MyImage](<Welt 3 Level 2.png>)

```Javascript
while (true) {
    var x = hero.pos.x;
    var y = hero.pos.y;
    var yak = hero.findNearestEnemy();
    if (hero.distanceTo(yak) < 10) {
        x = x + 10;
        hero.moveXY(x, y);
    }
}
```