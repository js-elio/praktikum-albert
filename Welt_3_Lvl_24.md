## ***Level 24:***  <span style="color: orange">***Sandschlangen***



![MyImage](<Welt 3 Level 24.png>)
```Javascript
while (true) {
    var coins = hero.findItems();
    var coinIndex = 0;
    var nearest = null;
    var nearestDistance = 9999;
    while (coinIndex < coins.length) {
        var coin = coins[coinIndex];
        coinIndex++;
        var distance = hero.distanceTo(coin);
        if (distance < nearestDistance) {
            nearest = coin;
            nearestDistance = distance;
        }
    }
    hero.moveXY(nearest.pos.x, nearest.pos.y);
}
```