## ***Level 23:***  <span style="color: orange">***Verrückter Maxer***



![MyImage](<Welt 3 Level 23.png>)
```Javascript
while (true) {
    var farthest = null;
    var maxDistance = 0;
    var enemyIndex = 0;
    var enemies = hero.findEnemies();
    while (enemyIndex < enemies.length) {
        var target = enemies[enemyIndex];
        enemyIndex += 1;
        var distance = hero.distanceTo(target);
        if (distance > maxDistance) {
            maxDistance = distance;
            farthest = target;
        }
    }
    if (farthest) {
        var enemy = hero.findNearestEnemy();
        if (hero.health > 0) {
            hero.attack(enemy);
        }
    }
}
```