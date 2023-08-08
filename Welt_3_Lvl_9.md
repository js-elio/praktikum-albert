## ***Level 9:***  <span style="color: orange">***Unter Heilender Aufsicht***



![MyImage](<Welt 3 Level 9.png>)

```Javascript
while (true) {
    var currentHealth = hero.health;
    var healingThreshold = hero.maxHealth / 2;
    if (healingThreshold) {
        hero.moveXY(65, 46);
        hero.say("heal me");
        var enemy = hero.findNearestEnemy();
        if (enemy) {
            hero.attack(enemy);
        }
    }
}
```