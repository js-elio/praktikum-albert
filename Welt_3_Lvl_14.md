## ***Level 14:***  <span style="color: orange">***Wüstengefecht***



![MyImage](<Welt 3 Level 14.png>)
```Javascript
var ordersGiven = 0;
while (ordersGiven < 5) {
    var y = hero.pos.y;
    var x = hero.pos.x;
    y = y - 10;
    hero.moveXY(x, y);
    hero.say("Attack!");
    ordersGiven = ordersGiven + 1;
}
while (true) {
    var enemy = hero.findNearestEnemy();
    hero.attack(enemy);
}
```