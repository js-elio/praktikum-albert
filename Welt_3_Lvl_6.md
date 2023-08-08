## ***Level 6:***  <span style="color: orange">***Kreuzung***



![MyImage](<Welt 3 Level 6.png>)

```Javascript
while (true) {
    var enemy = hero.findNearestEnemy();
    if (enemy) {
        if (enemy.pos.x < hero.pos.x) {
            hero.buildXY("fire-trap", 25, 34);
        } else if (enemy.pos.x > hero.pos.x) {
            hero.buildXY("fire-trap", 55, 34);
        } else if (enemy.pos.y < hero.pos.y) {
            hero.buildXY("fire-trap", 40, 19);
        } else if (enemy.pos.y > hero.pos.y) {
            hero.buildXY("fire-trap", 40, 49);
        }
    }
    hero.moveXY(40, 34);
}
```