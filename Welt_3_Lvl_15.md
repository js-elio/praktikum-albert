## ***Level 15:***  <span style="color: orange">***Staub***



![MyImage](<Welt 3 Level 15.png>)
```Javascript
var attacks = 0;
while (attacks < 10) {
    var enemy = hero.findNearestEnemy();
    hero.attack(enemy);
    attacks += 1;
}
hero.say("I should retreat!");
hero.moveXY(79, 32);
```