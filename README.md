# Penguin Game 
A penguin game allows users to play under two different modes. One is called a flying penguin game, and the other is called
a jumping penguin game. There are three Python files, that are, `menu.py`, `flyPenguinGame.py`, and `jumpPenguin.py`. The 
`menu.py` file implemented a menu interface, which provided users with visually displayed choices and a structured view 
of the game. When users selected ‘Flying Penguin’ mode, `flyPenguinGame.py` would run. By contrast, if users selected the 
other mode, `jumpPenguin.py` would run and allow users to play a penguin game with jumping status. The game could be 
terminated by a ‘Quit’ or a close button. More details can be found in the `Group7_report.pdf` file.



## Built With
* Python 3.7


## Further Improvement Suggestions 
Further improvements stem from the collision design, the UI design, the speed acceleration function, and the user experience. 

The collision design can be optimized by team self-created images of penguins and obstacles. In the current collusion design, 
sometimes the penguin does not look like having a collision with obstacles when health points decline by 1. This is because 
the algorithm for collisions is computed based on the width and height of the image. Each image is regarded as a rectangle, 
but in fact, the image the user sees is irregular like a lodge obstacle. 

As for the UI design, the menu interface can be more attractive with further adjustments. Concerning the speed acceleration 
function, speed acceleration is currently limited. There is a lot of room for improvement in acceleration algorithms. 
Furthermore, more penguin dynamic features can be added to improve the user experience. For instance, the penguin could 
flutter its wings during flying, or the penguin would roll its eyes once it hits an obstacle, or a little ghost-like 
penguin’s shaded color would rise from the penguin’s body once it has lost all health points. 


## Author

Dai Luqiao

Jonathan Then

Hu Xuanzheng


## Reference 
1. Collision Detection in PyGame - GeeksforGeeks. (n.d.). GeeksforGeeks. https://www.geeksforgeeks.org/collision-detection-in-pygame/ 
 
2. Collision Detection in PyGame - GeeksforGeeks. (n.d.). GeeksforGeeks. https://www.geeksforgeeks.org/collision-detection-in-pygame/ 
 
3. Flappy Bird In Python Pygame With Source Code - Page 7 Of 8 - CopyAssignment. (n.d.). CopyAssignment. https://copyassignment.com/flappy-bird-in-python-pygame-with-source-code/7/ 

4. How can I make one python file run another?(n.d.). Stack 
Overflow. https://stackoverflow.com/questions/7974849/how-can-i-make-one-python-file-run-another 

5. How to make Flappy Bird Game in Pygame? - GeeksforGeeks. (n.d.). GeeksforGeeks. https://www.geeksforgeeks.org/how-to-make-flappy-bird-game-in-pygame/ 

6. pygame-menu — pygame-menu 4.2.8 Documentation. (n.d.). pygame-menu — pygame-menu 4.2.8 Documentation. https://pygame-menu.readthedocs.io/en/4.2.8/

7. Python pygame font ffont | Learn-codes.net. (n.d.). Programming Tutorial & Code Examples. https://www.learn-codes.net/javascript/python-pygame-font-ffont/

