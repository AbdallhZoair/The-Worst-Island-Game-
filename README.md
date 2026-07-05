# The Worst Island Game 🏝️

Just a small text adventure game I made in Python to practice input(), if/elif/else, and while loops.

## Story
You land on an island and there are 2 doors: red and blue.
- Pick blue -> you lose right away.
- Pick red -> you get 3 chests to choose from: white, black, green.
  - White = treasure, you win 🎉
  - Black = full of spiders 🕷️ (you die)
  - Green = full of snakes 🐍 (you die)

## How to run it
```bash
python3 game.py
```
Just follow the prompts and type what it asks you (red door / blue door, then white / black / green).

## Bugs I fixed
When I first wrote this, replaying the game (typing Y to play again) kept using the same door I picked the first time — it never asked me again. Took me a while to notice it. Fixed it by moving the door input so it only asks again if you actually choose to play again (R == "Y").

## Notes to self / possible upgrades later
- add a score counter
- maybe more doors/chests
- try building a GUI version with tkinter
