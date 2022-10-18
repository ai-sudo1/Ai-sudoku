# Ai-sudoku
61 lines (40 sloc)  3.37 KB

Sudoko AI

Once you start training machine learning models, it's easy to forget that not all AI needs to use a model trained on a GPU. Training neural networks to solve difficult problems is really cool, but I think it's become common for people to over-engineer simple problems. This repository is a good example of an AI that requires zero training data and can solve the puzzles quickly and with 100% accuracy.

What is Sudoku

Sudoku was created in 1979 by Howard Garns, a semi-retired puzzle creator from Indiana. The earlist predecessor to Sudoku was a game called Numbers, which appeared in French newspapers throughout the 1800s. While similar to Sudoku, Numbers involved arithmatic instead of logic to solve and there were sometimes double-digit numbers.

Unfortunately, Howard Garns died before his invention took off. In the mid-late 1980s a Japenese newspaper started publishing the puzzle regularly and Maki Kaji gave it the name Sudoku. It wasn't until the late 1990s and early 2000s that Sudoku made its way back to the States and spread throughout the rest of the world.

How do you play

Sudoku is played on a 9x9 grid which is also separated into 9 3x3 sections. The objective of the game is to figure out how to put the digits 1-9 on the grid so that each digit appears exactly once in each row, column, and 3x3 section. The game will start off with a handful of squared filled out; these are locked in. In general, the fewer sections that start off filled, the more difficult the game is. Of course, there is a critical point whereby once you get down to too few squares filled out there becomes many correct solutions and the game becomes easier again.
