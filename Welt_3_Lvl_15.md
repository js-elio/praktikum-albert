## ***Level 15:***  <span style="color: orange">***Zick, Zack und Boom***



![MyImage](<Welt 3 Level 15.png>)
```Javascript
function mod15(n) {
    while (n >= 15) {
        n -= 15;
    }
    return n;
}
function mod9(n) {
    while (n >= 9) {
        n -= 9;
    }
    return n;
}
while (true) {
    var time = hero.time;
    var x, y;
    if (time < 30) {
        y = 10 + 3 * mod15(time);
    } else {
        y = 20 + 3 * mod9(time);
    }
    x = 10 + time;
    hero.moveXY(x, y);
}
```