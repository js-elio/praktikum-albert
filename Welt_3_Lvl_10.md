## ***Level 10:***  <span style="color: orange">***Zeit Anzeigen***

***In dem Level habe ich den neuen hero.time Befehl kennengelernt.***

![MyImage](<Welt 3 Level 10.png>)

```Javascript
while (true) {
    if (hero.time < 10) {
        var enemy = hero.findNearestEnemy();
        if (enemy) {
            hero.attack(enemy);
        }
    } else if (hero.time < 35) {
        var item = hero.findNearestItem();
        hero.moveXY(item.pos.x, item.pos.y);
    } else {
        var enemy = hero.findNearestEnemy();
        if (enemy) {
            hero.attack(enemy);
        }
    }
}
```