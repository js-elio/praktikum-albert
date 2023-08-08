## ***Level 14:***  <span style="color: green">***Überlass´ Es Dem Cleaver***



![MyImage](Welt-2Level-14.png)

```Javascript
while (true) {
    var enemy = hero.findNearestEnemy();
    if (enemy) {
        cleaveWhenClose(enemy);
        hero.attack(enemy);
    }
}
function cleaveWhenClose(target) {
    if (hero.distanceTo(target) < 5) {
        hero.attack(enemy);
        hero.cleave(enemy);
        if (enemy) {
        }
    }
}
var enemy = hero.findNearestEnemy();
if (enemy) {
    cleaveWhenClose(enemy);
}
```