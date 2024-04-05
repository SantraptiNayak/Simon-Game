# Simon-Game
Implementation of the Simon game using HTML, CSS, and JavaScript/jQuery


# Working
The provided jQuery code is for implementing the Simon game, a memory-based game where players need to repeat a sequence of colors generated by the game. The game logic is primarily managed through jQuery events and functions.

Upon pressing any key on the document, the game initiates by updating the level title to display "Level 1" and calling the nextSequence() function to generate the first random color pattern. A boolean variable, started, ensures that the game only starts once per keypress. Each color button in the game is associated with a specific sound, and when a button is clicked, its corresponding sound is played using the playSound() function.

The checkAnswer() function evaluates the user's input against the generated game pattern. If the user correctly repeats the sequence up to the current level, the game proceeds to the next level with an additional color. If the user makes a mistake, the game ends, the background flashes red to indicate a game-over state, and the level title updates to "Game Over, Press Any Key to Restart". After a brief delay, the game resets using the startOver() function.

The nextSequence() function is responsible for generating the next color pattern. It chooses a random color from an array of possible colors (buttonColours), adds it to the game pattern, and animates the corresponding button with fadeIn and fadeOut effects. The chosen color's sound is played using playSound().

Button clicks are also enhanced with an animation effect through the animatePress() function. When a button is clicked, it temporarily changes appearance to indicate a pressed state before reverting to its original state after a short delay.

# snapshots:


![1](https://github.com/SantraptiNayak/Simon-Game/assets/107788748/9a2fc099-7562-4e3b-897d-e67060d18dd5)


![2](https://github.com/SantraptiNayak/Simon-Game/assets/107788748/4a0962e6-acf5-46e7-ab78-a239d0e20710)


![3](https://github.com/SantraptiNayak/Simon-Game/assets/107788748/613ce18f-e656-47b8-81d5-b1c39e9364bf)


# link: https://santraptinayak.github.io/Simon-Game/

