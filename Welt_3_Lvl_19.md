## ***Level 19:***  <span style="color: orange">***Sandiger Retter***



![MyImage](<Welt 3 Level 19.png>)
```Javascript
var friendNames = [
    "Joan",
    "Ronan",
    "Nikita",
    "Augustus"
];
var friendIndex = 0;
while (friendIndex < friendNames.length) {
    var friendName = friendNames[friendIndex];
    hero.say(friendName + ", go home!");
    friendIndex = friendIndex + 1;
}
hero.moveXY(20, 30);
hero.buildXY("fence", 30, 30);
```