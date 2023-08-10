## ***Level 22:***  <span style="color: orange">***Goldsammler***



![MyImage](<Welt 3 Level 22.png>)
```Javascript
while (true) {
    var coins = hero.findItems();
    var coinIndex = 0;
    while (coinIndex < coins.length) {
        var coin = coins[coinIndex];
        coinIndex += 1;
        if (coin.value == 3) {
            hero.moveXY(coin.pos.x, coin.pos.y);
        }
    }
}
```