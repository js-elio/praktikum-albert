## ***Level 12:***  <span style="color: orange">***Lockvogel Drill***



![MyImage](<Welt 3 Level 12.png>)

```Javascript
var decoysBuilt = 0;
while (true) {
    var coin = hero.findNearestItem();
    if (coin) {
        hero.moveXY(coin.pos.x, coin.pos.y);
    }
    if (hero.gold >= 25) {
        hero.buildXY("decoy", hero.pos.x, hero.pos.y);
        decoysBuilt = decoysBuilt + 1;
    }
    if (decoysBuilt == 4) {
        break;
    }
}
hero.say("Errichten von Lockvögel erledigt!");
hero.moveXY(14, 36);
hero.say(decoysBuilt);
```