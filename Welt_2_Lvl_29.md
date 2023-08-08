## ***Level 29:***  <span style="color: lightgreen">***Lass Die Flagge Fallen***

***Hier musste ich Flaggen plazieren wenn ein Gegner kommt, damit er mit der platzierten Falle stirbt.***

![MyImage](<Welt 2 Level 29.png>)

```Javascript
while (true) {
    var flag = hero.findFlag();
    if (flag) {
        var flagPos = flag.pos;
        var flagX = flagPos.x;
        var flagY = flagPos.y;
        hero.buildXY("fire-trap", flagX, flagY);
        hero.pickUpFlag(flag);
    } else {
        var item = hero.findNearestItem();
        if (item) {
            var itemPos = item.pos;
            var itemX = itemPos.x;
            var itemY = itemPos.y;
            hero.moveXY(itemX, itemY);
        }
    }
}
```