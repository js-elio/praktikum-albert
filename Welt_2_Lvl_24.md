## ***Level 24:***  <span style="color: lightgreen">***Auf Der Durchreise***



![MyImage](<Welt 2 Level 24.png>)

```Javascript
while (true) {
    var item = hero.findNearestItem();
    if (item) {
        if (item.type != "gem") {
            hero.moveXY(pet.pos.x, pet.pos.y);
        }
        if (item && item.type == "gem") {
            hero.moveXY(item.pos.x, item.pos.y);
        }
    }
}
```