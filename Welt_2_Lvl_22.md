## ***Level 22:***  <span style="color: lightgreen">***Frühlingsdonner***

***Mit Item.value kann ich nun nach blauen Edelsteinen und Silbermünzen suchen und einsammeln, da diese nicht vom Blitz getroffen werden.***

![MyImage](<Welt 2 Level 22.png>)

```Javascript
while (true) {
    var item = hero.findNearestItem();
    if (item.type == "coin" && item.value == 2) {
        hero.moveXY(item.pos.x, item.pos.y);
    }
    if (item.type == "gem" && item.value == 10) {
        hero.moveXY(item.pos.x, item.pos.y);
    }
}
```