## ***Level 11:***  <span style="color: lightgreen">***Waldfeuertanz***

***In diesem Level habe ich gelernt den Feuerbällen auszuweichen.***

![MyImage](Welt-2-Level-11.png)

```Javascript
while (true) {
    var evilstone = hero.findNearestItem();
    if (evilstone) {
        var pos = evilstone.pos;
        if (pos.x == 34) {
            hero.moveXY(46, 22);
        } else {
            hero.moveXY(34, 22);
        }
    } else {
        hero.moveXY(40, 22);
    }
}
```