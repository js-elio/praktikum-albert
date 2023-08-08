## ***Level 18:***  <span style="color: lightgreen">***Gefährdete Burl***



![MyImage](Welt-2-Level-18.png)

```Javascript
while (true) {
    var enemy = hero.findNearestEnemy();
    if (enemy.type == "burl") {
        hero.say("Ich greife diesen Burl da nicht an!");
    }
    if (enemy.type == "munchkin") {
        hero.attack(enemy);
    }
    if (enemy.type == "ogre") {
        hero.moveXY(41, 47);
    }
    if (enemy.type == "thrower") {
        hero.attack(enemy);
    }
}
```