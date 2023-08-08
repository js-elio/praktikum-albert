## ***Level 33:***  <span style="color: green">***Belagerung Der Steinfestung***



![MyImage](<Welt 2 Level 33.png>)

```Javascript
while (true) {
    var flag = hero.findFlag();
    var enemy = hero.findNearestEnemy();
    if (flag) {
        hero.pickUpFlag(flag);
    } else if (enemy) {
        hero.attack(enemy);
    }
}
```