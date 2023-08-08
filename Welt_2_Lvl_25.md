## ***Level 25:***  <span style="color: lightgreen">***Logischer Pfad***



![MyImage](<Welt 2 Level 25.png>)

```Javascript
hero.moveXY(14, 24);
var secretA = hero.findNearestFriend().getSecretA();
var secretB = hero.findNearestFriend().getSecretB();
var secretC = secretA && secretB;
if (secretC) {
    hero.moveXY(20, 33);
} else {
    hero.moveXY(20, 15);
}
hero.moveXY(26, 24);
hero.moveXY(32, 33);
hero.moveXY(38, 24);
hero.moveXY(44, 15);
hero.moveXY(50, 24);
```