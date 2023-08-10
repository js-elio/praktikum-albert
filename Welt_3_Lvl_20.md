## ***Level 20:***  <span style="color: orange">***Schleicher***



![MyImage](<Welt 3 Level 20.png>)
```Javascript
var enemies = hero.findEnemies();
var enemyIndex = 0;
while (enemyIndex < enemies.length) {
    var enemy = enemies[enemyIndex];
    if (enemy.type == 'shaman') {
        while (enemy.health > 0) {
            hero.attack(enemy);
        }
    }
    enemyIndex = enemyIndex + 1;
}
```