## ***Level 16:***  <span style="color: orange">***Hetze Nicht, Sei Still***



![MyImage](<Welt 3 Level 16.png>)
```Javascript
function mod30(n) {
    if (n >= 30) {
        return n - 30;
    } else {
        return n;
    }
}
function mod40(n) {
    if (n >= 40) {
        return n - 40;
    } else {
        return n;
    }
}
while (true) {
    var time = hero.time;
    var x = mod30(time) + 25;
    var y = mod40(time) + 10;
    hero.moveXY(x, y);
}
```