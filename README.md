# 2nd-Milestone
This is my second milestone project as a learning part in python journey

##  War Card Game – Python (OOP Project)
A complete Object-Oriented Programming (OOP) implementation of the classic War Card Game using Python.
This project uses four main components:

Card Class
Deck Class
Player Class
Game Logic
It is designed as a milestone project to practice OOP design, game logic, lists, loops, and modular coding.

## Project Overview
The War Card Game is a two-player automated card game.
Each round, players draw the top card from their deck:

Higher card wins
Winner collects both cards
If the cards have equal value → WAR

### In War:

Both players place extra cards
A new battle decides the winner
Winner takes all cards in the “war pile”
The game continues until one player has all 52 cards.

##  Project Structure
war-card-game/
│
├── card.py        # Card class (rank, suit, value)
├── deck.py        # Deck class (creates, shuffles, deals)
├── player.py      # Player class (card storage, add/remove)
├── game.py        # Main game logic / loop
│
└── README.md      # Project documentation

##  Classes Explanation
🔹 1. Card Class
Represents a single card with:
Suit (Hearts, Diamonds, Clubs, Spades)
Rank (2–Ace)
Value (used in comparison)

Purpose:
Creating objects that can be compared in the game.

🔹 2. Deck Class
Manages a standard deck of 52 Card objects.

Features:
Creates all cards
Shuffles cards
Deals cards one at a time
Used in the beginning to split the deck between players.

🔹 3. Player Class
Represents each player.

Features:
Stores player name
Holds list of cards
Removes top card
Adds won cards
Tracks number of remaining cards

## How the Game Works

New deck is created and shuffled
Deck is split equally between Player 1 and Player 2

Each round:
Both players play a card
Higher value wins
If equal values → WAR
Game ends when one player has all 52 cards

##  Concepts Practiced

Object-Oriented Programming (OOP)
Class design & relationships
Game simulation logic
Lists, loops, and functions
Python modules & imports

## Author 
Mail to: (lakhanmishra.ai@gmail.com)
Github:(https://github.com/lakhanmishra.ai)
Linked In:(www.linkedin.com/in/lakhan-mishra-bab866229)



