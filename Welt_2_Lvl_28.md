## ***Level 28:***  <span style="color: green">***Kupferwiesen***



![MyImage](<Welt 2 Level 28.png>)

```Javascript
 while (true) {
    var flag = hero.findFlag();
    if (flag) {
        // Hebe die Flagge auf.
        hero.pickUpFlag(flag);
    } else {
        var item = hero.findNearestItem();
        if (item) {
            var position = item.pos;
            var x = position.x;
            var y = position.y;
            hero.moveXY(x, y);
        }
    }
}
```