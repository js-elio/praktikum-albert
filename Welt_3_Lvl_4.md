## ***Level 4:***  <span style="color: orange">***Wilde Flucht Aus Dem Talkessel***



![MyImage](<Welt 3 Level 4.png>)

```Javascript
while (true) {
    var enemy = hero.findNearestEnemy();
    var xPos = hero.pos.x + 5;
    var yPos = 17;
    if (enemy) {
        if (enemy.pos.y > hero.pos.y) {
            y = y - 3;
        } else if (enemy.pos.y < hero.pos.y) {
            y = y + 3;
        }
    }
    hero.moveXY(xPos, yPos);
}
```