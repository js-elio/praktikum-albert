## ***Level 13:***  <span style="color: orange">***Doppelwange***



![MyImage](<Welt 3 Level 13.png>)
```Javascript
var defeatedOgres = 0;
while (defeatedOgres < 6) {
    var enemy = hero.findNearestEnemy();
    if (enemy) {
        hero.attack(enemy);
        defeatedOgres += 1;
    } else {
        hero.say("Ogres!");
    }
}
hero.moveXY(49, 36);
while (hero.gold < 30) {
    var item = hero.findNearestItem();
    if (item && item.type == "coin") {
        hero.moveXY(item.pos.x, item.pos.y);
    }
}
hero.moveXY(76, 32);
```