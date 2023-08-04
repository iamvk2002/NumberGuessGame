# NumberGuessGame
# GuessTheNumber Game in C++

## Description

GuessTheNumber is a simple number guessing game implemented in C++. The game randomly selects a secret number within a specified range, and the player's objective is to guess the correct number within a limited number of attempts. The player can choose from three difficulty levels: easy, medium, and difficult. Each level offers a different number of attempts to find the secret number. Can you guess the right number and win the game? Give it a try and test your guessing skills!

## How to Play

1. Clone the repository or download the source code files to your local machine.

2. Open the terminal or command prompt and navigate to the project directory.

3. Compile the code using a C++ compiler:

   ```
   g++ number_guessing_game.cpp -o number_guessing_game
   ```

4. Run the game executable:

   ```
   ./number_guessing_game
   ```

5. The game will display a welcome message and prompt you to choose the difficulty level.

6. Enter the number corresponding to the difficulty level you want to play:

   - `1` for easy (10 attempts)
   - `2` for medium (7 attempts)
   - `3` for difficult (5 attempts)
   - `0` to end the game

7. After selecting the difficulty level, the game will generate a secret number between 1 and 100.

8. Make your guesses by entering numbers within the specified range.

9. The game will provide feedback on whether your guess is correct or not and whether the secret number is greater or smaller than your guess.

10. Keep guessing until you find the correct number or run out of attempts.

11. If you guess the correct number within the allowed attempts, you win! Otherwise, the game will reveal the secret number, and you can choose to play again.

## Sample Gameplay

```
Welcome to GuessTheNumber game!
You have to guess a number between 1 and 100. You'll have limited choices based on the level you choose. Good Luck!

Enter the difficulty level:
1 for easy!     2 for medium!   3 for difficult!   0 for ending the game!

Enter the number: 2

You have 7 choices for finding the secret number between 1 and 100.

Enter the number: 50
Nope, 50 is not the right number
The secret number is smaller than the number you have chosen
6 choices left.

Enter the number: 25
Nope, 25 is not the right number
The secret number is greater than the number you have chosen
5 choices left.

Enter the number: 35
Nope, 35 is not the right number
The secret number is smaller than the number you have chosen
4 choices left.

Enter the number: 30
Well played! You won, 30 is the secret number
                 Thanks for playing....

Play the game again with us!!
```

## Contributing

If you want to contribute to this project or report any issues, feel free to open an issue or submit a pull request. All contributions are welcome!

