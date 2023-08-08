## ***Level 11:***  <span style="color: orange">***Gold Anhäufen***

***In diesem Level habe ich gelernt, nur eine bestimmte Anzahl an Münzen zu nehmen mit dem Befehl "totalGold" und "break".***


![MyImage](<Welt 3 Level 11.png>)

```Javascript
var totalGold = 0;
while (true) {
    var coin = hero.findNearestItem();
    if (coin) {
        hero.moveXY(coin.pos.x, coin.pos.y);
        totalGold += coin.value;
    }
    if (totalGold >= 25) {
        break;
    }
}
hero.moveXY(58, 33);
hero.say("" + totalGold + "gold!");
```