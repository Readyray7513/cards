# Card Shuffle Program

## Overview
This program simulates the shuffling and displaying of a deck containing three specific cards: 'jack', 'queen', and 'king'. The cards are shuffled randomly, and the shuffled deck is displayed after the shuffle.

## Features
- The program initializes a deck with three cards: 'jack', 'queen', and 'king'.
- The `random.shuffle()` function is used to shuffle the deck.
- The shuffled deck is displayed by printing the cards one by one.

## Example Usage
```
$ python card_shuffle.py
['queen', 'jack', 'king']
['king', 'jack', 'queen']
['jack', 'queen', 'king']
```

## How to Run
1. Run the program by executing:
   ```
   python card_shuffle.py
   ```
2. The cards will be shuffled and printed multiple times.

## Notes
- The program shuffles the deck and prints the list in its shuffled state after each iteration.
- For a more meaningful output, the program could print the shuffled deck once after the shuffle instead of repeatedly printing it for each card.
