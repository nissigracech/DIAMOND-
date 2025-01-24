Diamonds
Welcome to the Diamonds Card Game! This is a console-based card game where three players compete to win diamond cards and score points. The game evaluates the winner of each round and declares the final winner at the end.

**Features**

- 🎴 Banker creates a deck of 13 diamond cards.

- 🃏 Players have their respective suits (♠️ Spades, ♥️ Hearts, and ♣️ Clubs).

- 🔀 Cards are shuffled before each round.

- 🏆 Points are awarded based on the diamond card displayed.

- 🕹️ Players compete in 13 rounds, and the final winner is determined based on the total scores.

- 🔄 Option to replay the game.

**How to Play**

- 🖥️ Run the script.

- ✍️ Enter the names of the three players.

- 🎮 Play through 13 rounds:

- ♦️ A diamond card is displayed.

- 🃏 Each player draws a card from their shuffled deck.

- 🏅 Points are awarded to the player(s) with the highest card value compared to the displayed diamond card.
- 📊 After 13 rounds, the final scores are calculated, and the winner is announced.
- 🔄 You can choose to replay the game or exit.

**Game Rules**
- *Point System for Diamond Cards:*
   - 🔢 Cards with values 2-10: 3 points
   - 👑 Royals (J, Q, K): 10 points
   - 🅰️ Ace (A): 20 points

- *Winner Determination in Each Round:*
    - 🥇 The player with the highest card value wins the diamond card and the corresponding points.
    - 🤝 If two players have the same highest card value, the points are split equally.
    - ⚖️ If all three players have the same highest card value, the points are divided among them.
-🔁 The game proceeds for 13 rounds or until a player chooses to quit.

**Prerequisites**

- 🐍 Python 3.x
- 📦 colorama module
    - Install the colorama module using pip if not already installed:
    - pip install colorama
      
**Code Overview**

  *Main Classes*
  1. Banker:🃏 Creates a diamond suit with values 2, 3, 4, ..., 10, J, Q, K, A.
  2. Players:🃏 Creates suits for Spades (♠️), Hearts (♥️), and Clubs (♣️).

  *Main Functions*
  1. 🔀 Shuffle(cards):Shuffles the given deck of cards.
  2. 🃏 Pop_cards(cards):Pops a card from the given deck.
  3. 🏅 points_evaluation(card):Awards points based on the diamond card value.
  4. 🥇 final_winner(p1, p2, p3):Determines the final winner based on total scores.
  5. 🎮 player_scores():Manages the gameplay, scoring, and declaring round winners.

**How to Run**
  1. 💾 Save the script as diamonds_game.py.
  2. 📂 Open a terminal and navigate to the directory containing the script.
  3. ▶️ Run the script using the command:python diamonds_game.py
  4. 📋 Follow the on-screen instructions to play the game.

     
