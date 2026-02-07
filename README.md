# Gamber Mode

## What the Game Is
Gamber Mode is a terminal-based Python game where the player guesses numbers to earn coins. The goal is to maximize your coins and keep your streak going without running out of coins.

---

## How the Game Works

1. You are given a list of **15–17 random numbers** between 1 and 100.
2. You will be asked to **enter a number**.
3. If your number **matches one in the list**, you gain **65–80 coins**.
4. If your number **does not match**, you lose **30–40 coins**.
5. You start with a random number of coins (between 475–525).
6. If your coins reach 0, the game ends — you lose.
7. After every round, your **balance, streak, and success percentage ("Gamber Mode")** are displayed.

---

## Rules

- Enter **only integers** between 1 and 100.
- Try to guess numbers that might appear in the list to increase your coins.
- Your **streak increases** every time you succeed.
- The **success rate** is calculated as:
  
Gamber Mode = (Successes / (Successes + Fails)) * 100

- The game ends automatically if coins = 0.

---

## Win / Lose Conditions

- **Win:** There’s no fixed "win" — the game is endless and tests your streak and coin management skills.  
- **Lose:** Your coin balance reaches **0**. The game ends and stats are displayed.

---

## Features

- Tracks **successes, fails, and streaks**.
- Shows a **history bar** of past outcomes (green = success, red = fail).
- Random coin increments/decrements to simulate risk and reward.
- Terminal color codes for immersive experience.

---

## How to Play

1. Download the repo or go to Google Colab.
