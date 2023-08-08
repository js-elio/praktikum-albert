## ***Level 15:***  <span style="color: lightgreen">***Freund Und Feind***



![MyImage](Welt-2-Level-15.png)

```Javascript
while (true) {
    var friend = hero.findNearestFriend();
    if (friend) {
        hero.say("To battle, " + friend.id + "!");
    }
    var enemy = hero.findNearestEnemy();
    if (enemy) {
        hero.say("Verschwinde!" + enemy.id);
    }
}
```