## ***Level 7:***  <span style="color: orange">***Donnerhufe***



![MyImage](<Welt 3 Level 7-1.png>)

```Javascript
while (true) {
    var yak = hero.findNearestEnemy();
    if (yak) {
        if (yak.pos.y > hero.pos.y) {
            hero.buildXY("fence", yak.pos.x, yak.pos.y - 10);
        } else {
            hero.buildXY("fence", yak.pos.x, yak.pos.y + 10);
        }
    } else {
        hero.moveXY(hero.pos.x + 10, hero.pos.y);
    }
}
```