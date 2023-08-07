## ***Level 18:***  <span style="color: red">***Das Finale Kith-Labyrinth***


![MyImage](Welt-1-Level-18.png)


```Javascript
while (true) {
    hero.moveRight();
    hero.moveUp();
    var enemy = hero.findNearestEnemy();
    hero.attack(enemy);
    hero.moveRight();
    hero.moveDown(2);
    hero.moveUp();
}
```