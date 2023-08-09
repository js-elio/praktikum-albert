## ***Level 19:***  <span style="color: orange">***Banküberfall***



![MyImage](<Welt 3 Level 19-1.png>)
```Javascript
while (true) {
    var enemies = hero.findEnemies();
    var enemyIndex = 0;
    while (enemyIndex < enemies.length) {
        var enemy = enemies[enemyIndex];
        hero.attack(enemy);
        enemyIndex++;
    }
    var coins = hero.findItems();
    var coinIndex = 0;
    while (coinIndex < coins.length) {
        var coin = coins[coinIndex];
        hero.moveXY(coin.pos.x, coin.pos.y);
        coinIndex++;
    }
}
```