## ***Level 30:***  <span style="color: green">***Denke An Die Falle***



![MyImage](<Welt 2 Level 30.png>)

```Javascript
while (true) {
    var flag = hero.findFlag();
    var enemy = hero.findNearestEnemy();
    if (flag) {
        hero.pickUpFlag(flag);
        hero.say("Ich sollte die Flagge holen.");
    } else if (enemy) {
        var distance = hero.distanceTo(enemy);
        if (distance < 10) {
            hero.attack(enemy);
        }
    }
}
```