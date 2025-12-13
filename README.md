# Console Based Quiz Game (C++)

This is a **console-based quiz game** written in **C++**.
The game runs in the **command prompt / terminal** and uses text files for questions and high scores.

---

## Features

* Three difficulty levels

  * Easy
  * Medium
  * Hard

* Four quiz subjects

  * Science
  * Maths
  * Sports
  * History

* Timer based questions (10 seconds per question)

* Skip and Swap options (limited)

* Bonus points for correct answer streaks

* Leaderboard saved in a file

* Random questions every time

---

## How the Game Works

1. Run the program
2. Choose:

   * Start Quiz
   * View Leaderboard
   * Exit
3. Enter your name
4. Select difficulty and subject
5. Answer MCQs by pressing **A, B, C, or D**
6. You can:

   * Press **S** to skip a question (limited)
   * Press **W** to swap a question (limited)
7. Final score is shown and saved if it is high enough

---

## Files Required

Make sure these files are in the **same folder** as the program:

### Question Files

* easy_science.txt

* easy_maths.txt

* easy_sports.txt

* easy_history.txt

* med_science.txt

* med_maths.txt

* med_sports.txt

* med_history.txt

* hard_science.txt

* hard_maths.txt

* hard_sports.txt

* hard_history.txt

Each question must be written in **this format**:

```
Question text
A) option
B) option
C) option
D) option
: X
```

### High Score File

* high_scorers.txt

Example:

```
ali,15
ahmed,20
sara,18
fatima,12
hassan,10
```

---

## How to Compile and Run

### Using Dev-C++ (Windows)

1. Open the `.cpp` file
2. Compile and Run

### Using Command Prompt (Windows)

```
g++ quiz.cpp -o quiz
quiz
```

---

## Requirements

* Windows OS
* C++ Compiler (GCC / Dev-C++)
* `<windows.h>` and `<conio.h>` (Windows only)

---

## Notes

* Timer input uses keyboard hit detection
* Works only on Windows due to system libraries
* Scores can go negative on wrong answers
* Leaderboard stores top 5 scores

---

## Author

Made as a **console-based C++ project** for learning:

* File handling
* Arrays and strings
* Functions
* Randomization
* Game logic

---

* Help you upload this properly on GitHub
