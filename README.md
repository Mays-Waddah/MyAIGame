# 🎮 Number Guessing Game

Welcome to the **Number Guessing Game**! This is a simple yet fun Python game where the computer picks a random number between 1 and 100, and your goal is to guess it correctly. 🕹️

## 📋 Features
- **Random Number Generation**: The computer picks a number between 1 and 100 using Python's `random` module.
- **Player Hints**: Receive hints if your guess is too low or too high.
- **Simple Gameplay**: Keep guessing until you find the correct number.

## 🚀 Getting Started

### **Prerequisites**
- Python installed on your computer. If you don't have Python, you can download it from [Python's official website](https://www.python.org/downloads/).

### **Installation Steps**
1. Clone the repository to your local machine:
    ```bash
    git clone https://github.com/Mays-Waddah/MyAIGame.git
    ```
2. Navigate to the project directory:
    ```bash
    cd "My AI Powered game"
    ```

### **Running the Game**
1. Open the project in **Visual Studio**.
2. Locate the **My AI Powered game.sln** solution file and open it.
3. In Visual Studio, click on **Start** or press `F5` to build and run the project.
    
## 🎮 How to Play
1. The computer picks a random number between 1 and 100.
2. Enter your guess when prompted.
3. You'll receive a hint if your guess is too low or too high.
4. Keep guessing until you find the correct number and win! 🏆

## 📦 Requirements
No external libraries are needed; the game uses Python's built-in `random` module.

## 📄 License
This project is open-source and available under the MIT License.

## 💬 Feedback
If you have any suggestions or improvements, feel free to open an issue or submit a pull request.

🌟 Enjoy playing and happy guessing! 😊

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
