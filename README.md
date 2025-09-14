
# 🎰 Slot Machine Game (Node.js)

## 📌 Overview
This is a **command-line Slot Machine game** built using **Node.js**.  
The player deposits money, places bets on lines, spins the slot machine, and wins or loses based on the outcome.  

The game continues until the player decides to quit or runs out of money.

---

## 🚀 Features
- Deposit money before playing.  
- Bet on **1–3 lines**.  
- Spin a **3x3 slot machine** with random symbols.  
- Winning lines are calculated based on matching symbols.  
- Different symbols have different payout values.  
- Option to **play again** until balance runs out.  

---

## 🛠️ Technologies Used
- **Node.js**  
- **prompt-sync** (for user input in the terminal)

---

## 📂 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/slot-machine-game.git
   cd slot-machine-game
   ```

2. Install dependencies:
   ```bash
   npm install prompt-sync
   ```

3. Run the game:
   ```bash
   node index.js
   ```

---

## 🎮 Gameplay Flow
1. Enter a **deposit amount**.  
2. Choose the **number of lines** to bet on (1–3).  
3. Enter your **bet per line**.  
4. Spin the slot machine and check results.  
5. If you win → winnings are added to your balance.  
6. Decide whether to **play again** or quit.  

---

## 💡 Example Run
```
Enter a deposit amount: 100
Enter the number of lines to bet on (1-3): 2
Enter the bet per line: 5

A | B | C
C | A | D
B | B | A

You won, $20
Do you want to play again (y/n)? y
```

---

## 📌 Future Improvements
- Add more symbol types and animations.  
- Implement jackpot / bonus rounds.  
- Save user balance history.  

---

## 📜 License
This project is open-source under the MIT License.  
