## ***Level 20:***  <span style="color: lightgreen">***Hit And Freeze***



![MyImage](Welt-2-Level-20.png)

```Javascript
function inAttackRange(enemy) {
    var distance = hero.distanceTo(enemy);
    if (distance <= 3) {
        return true;
    } else {
        return false;
    }
}
while (true) {
    var enemy = hero.findNearestEnemy();
    var canAttack = inAttackRange(enemy);
    if (inAttackRange(enemy)) {
        hero.attack(enemy);
    }
}

```