## ***Level 12:***  <span style="color: lightgreen">***Dorfvagabund***



![MyImage](Welt-2-Level-12.png)

```Javascript
function findAndAttackEnemy() {
    var enemy = hero.findNearestEnemy();
    if (enemy) {
        hero.attack(enemy);
    }
}
while (true) {
    hero.moveXY(35, 34);
    findAndAttackEnemy();
    hero.moveXY(60, 31);
    findAndAttackEnemy();
}
```