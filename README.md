
# Guess the Number Game (Java)

## Project Description
This project is a simple **Guess the Number** game developed using Java.  
The program generates a random number between **1 and 100**, and the player tries to guess it.  
The game gives hints if the guessed number is too high or too low until the correct number is found.

---

## Technologies Used
- Java
- Scanner class (for user input)
- Random class (to generate random numbers)

---

## How the System Works
1. The program generates a random number between 1 and 100.
2. The user enters a number as a guess.
3. The program checks the guess:
   - If the guess is lower, it shows **Too low**
   - If the guess is higher, it shows **Too high**
   - If the guess is correct, the game ends
4. All user guesses are stored in an array.
5. At the end, the program displays:
   - Total number of attempts
   - All guessed numbers

---

## How to Run the Project
1. Install Java on your system.
2. Save the file as `GuessNumberArray.java`.
3. Open the terminal or command prompt.
4. Compile the program:
   ```bash
   javac GuessNumberArray.java
````

5. Run the program:

   ```bash
   java GuessNumberArray
   ```

---

## Sample Output

```
Guess the Number Game
Guess a number between 1 and 100
Enter your guess: 40
Too high! Try again.
Enter your guess: 20
Too low! Try again.
Enter your guess: 30
Congratulations!
You guessed the number in 3 attempts.

Your guesses were:
40 20 30
```

---
```
## Features

* Random number generation
* User-friendly messages
* Stores all guesses in an array
* Displays number of attempts
* Simple and easy to play

---
```
## Conclusion

This project helps in understanding basic Java concepts such as loops, arrays, conditional statements, and user input.
It is a good beginner-friendly project for learning Java programming.

```
##Developed By
Pruthviraj Gyanchand Gaikwad
```
