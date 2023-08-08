## ***Level 32:***  <span style="color: green">***Reicher Wildhüter***



![MyImage](<Welt 2 Level 32.png>)

```Javascript
while (true) {
    var flag = hero.findFlag();
    var enemy = hero.findNearestEnemy();
    var item = hero.findNearestItem();
    if (flag) {
        hero.pickUpFlag(flag);
    } else if (enemy) {
        hero.attack(enemy);
    } else if (item) {
        hero.moveXY(item.pos.x, item.pos.y);
    }
}
```