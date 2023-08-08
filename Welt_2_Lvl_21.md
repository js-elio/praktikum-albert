## ***Level 21:***  <span style="color: lightgreen">***Versalzene Erde***



![MyImage](<Welt 2 Level 21.png>)

```Javascript
while (true) {
    var enemy = hero.findNearestEnemy();
    if (enemy.type == "munchkin" || enemy.type == "thrower") {
        hero.attack(enemy);
    }
    var item = hero.findNearestItem();
    var coin = item.type == "coin";
    var gem = item.type == "gem";
    if (coin || gem) {
        // Then move and pick it up:
        hero.moveXY(item.pos.x, item.pos.y);
    }
}
```