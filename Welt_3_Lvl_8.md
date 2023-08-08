## ***Level 8:***  <span style="color: orange">***Operation 'Killdeer'***



![MyImage](<Welt 3 Level 8.png>)

```Javascript
function shouldRun() {
    if (hero.health < hero.maxHealth / 2) {
        return true;
    } else {
        return false;
    }
}
while (true) {
    if (shouldRun() === true) {
        hero.moveXY(75, 37);
    } else {
        var enemy = hero.findNearestEnemy();
        hero.attack(enemy);
    }
}
```