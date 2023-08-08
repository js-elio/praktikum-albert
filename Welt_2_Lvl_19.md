## ***Level 19:***  <span style="color: green">***Blinder Abstand***



![MyImage](Welt-2-Level-19.png)

```Javascript
function nearestEnemyDistance() {
    var enemy = hero.findNearestEnemy();
    var result = 0;
    if (enemy) {
        result = hero.distanceTo(enemy);
    }
    return result;
}
while (true) {
    var enemyDistance = nearestEnemyDistance();
    if (enemyDistance < 10) {
        hero.say("10");
    }
}
```