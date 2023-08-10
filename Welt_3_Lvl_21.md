## ***Level 21:***  <span style="color: orange">***Sandiger Schäfer***



![MyImage](<Welt 3 Level 21.png>)
```Javascript
while (true) {
    var enemy = hero.findNearestEnemy();
    if (enemy && enemy.type != "sand-yak") {
        hero.attack(enemy);
    }
}
```