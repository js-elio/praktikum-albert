## ***Level 17:***  <span style="color: lightgreen">***Münzenkrümel***



![MyImage](Welt-2-Level-17.png)

```Javascript
while (true) {
    var item = hero.findNearestItem();
    if (item) {
        var itemPosition = item.pos;
        var itemX = itemPosition.x;
        var itemY = itemPosition.y;
        hero.moveXY(itemX, itemY);
    }
}
```