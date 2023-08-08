## ***Level 1:***  <span style="color: orange">***Die Dünen***



![MyImage](<Welt 3 Level 1.png>)

```Javascript
while (true) {
    var enemy = hero.findNearestEnemy();
    var item = hero.findNearestItem();
    if (enemy) {
        if (enemy.type == "sand-yak" || enemy.type == "burl") {
            hero.moveXY(item.pos.x, item.pos.y);
        } else {
            if (enemy.type == "thrower" || enemy.type == "ogre") {
                hero.attack(enemy);
            }
        }
    } else if (item) {
        hero.moveXY(item.pos.x, item.pos.y);
    } else {
        hero.moveXY(41, 31);
    }
}
```