## ***Level 23:***  <span style="color: lightgreen">***Gewöhnlicher Tag***



![MyImage](<Welt 2 Level 23.png>)

```Javascript
while (true) {
    var enemy = hero.findNearestEnemy();
    if (enemy && enemy.type == "munchkin") {
        hero.attack(enemy);
    }
    var item = hero.findNearestItem();
    if (item && item.type == "coin") {
        hero.moveXY(item.pos.x, item.pos.y);
    }
}
```