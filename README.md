# 🎮 Number Guessing Game

Welcome to the **Number Guessing Game**! This is a simple yet fun Python game where the computer picks a random number between 1 and 100, and your goal is to guess it correctly. 🕹️

## 📋 Features
- **Random Number Generation**: The computer picks a number between 1 and 100 using Python's `random` module.
- **Player Hints**: Receive hints if your guess is too low or too high.
- **Simple Gameplay**: Keep guessing until you find the correct number.

## 🚀 Getting Started

### **Prerequisites**
- Python installed on your computer. If you don't have Python, you can download it from [Python's official website](https://www.python.org/downloads/).

### **Installation**
1. Clone the repository to your local machine:
    ```bash
    git clone https://github.com/Mays-Waddah/MyAIGame.git
    ```
2. Navigate to the project directory:
    ```bash
    cd MyAIGame
    ```

### **How to Run**
1. Open your terminal or command prompt.
2. Run the game script:
    ```bash
    python number_guessing_game.py
    ```

## 🎮 How to Play
1. The computer picks a random number between 1 and 100.
2. Enter your guess when prompted.
3. You'll receive a hint if your guess is too low or too high.
4. Keep guessing until you find the correct number and win! 🏆

## 📝 Code Overview

```python
import random

number = random.randint(1, 100)  # Randomly selects a number between 1 and 100
guess = None

while guess != number:
    guess = int(input("Guess the number (between 1 and 100): "))
    if guess < number:
        print("Too low! Try again.")
    elif guess > number:
        print("Too high! Try again.")
    else:
        print("Congratulations! You guessed the number.")

📦 Requirements
No external libraries are needed; the game uses Python's built-in random module.

📄 License
This project is open-source and available under the MIT License.

💬 Feedback
If you have any suggestions or improvements, feel free to open an issue or submit a pull request.

🌟 Enjoy playing and happy guessing! 😊
