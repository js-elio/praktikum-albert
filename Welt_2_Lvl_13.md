## ***Level 13:***  <span style="color: green">***Hinterwäder-Gabelung***

***Mit dem Befehl checkAndAttack kann ich nun Gegner finden und angreifen.***

![MyImage](Welt-2-Level-13.png)

```Javascript
function checkAndAttack(target) {
    if (target) {
        hero.attack(target);
    }
    hero.moveXY(43, 34);
}
while (true) {
    hero.moveXY(58, 52);
    var topEnemy = hero.findNearestEnemy();
    checkAndAttack(topEnemy);
    // Gehe zur unteren X-Markierung.
    hero.moveXY(58, 17);
    var bottomenemy = hero.findNearestEnemy();
    checkAndAttack(bottomenemy);
}
```