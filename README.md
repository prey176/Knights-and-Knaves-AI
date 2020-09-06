# Knights-and-Knaves-AI

## Introduction to the Game Knights

In 1978, logician Raymond Smullyan published “What is the name of this book?”, a book of logical puzzles. Among the puzzles in the book were a class of puzzles that Smullyan called “Knights and Knaves” puzzles.

In a Knights and Knaves puzzle, the following information is given: Each character is either a knight or a knave. A knight will always tell the truth: if knight states a sentence, then that sentence is true. Conversely, a knave will always lie: if a knave states a sentence, then that sentence is false.

The objective of the puzzle is, given a set of sentences spoken by each of the characters, determine, for each character, whether that character is a knight or a knave.

For example, consider a simple puzzle with just a single character named A. A says “I am both a knight and a knave.”

Logically, we might reason that if A were a knight, then that sentence would have to be true. But we know that the sentence cannot possibly be true, because A cannot be both a knight and a knave – we know that each character is either a knight or a knave, but not both. So, we could conclude, A must be a knave.

That puzzle was on the simpler side. With more characters and more sentences, the puzzles can get trickier! 

## About AI

The major contribution towards the puzzles were formulating it as propositional logic, then using brute solver to check for predictions. logic.py contains the porpositional logic functions, the puzzle.py contains the puzzles and their logic representaions. The major template was taken from the course cs50.


We targeted specific puzzles to solve, the puzzles are the following - 

# Puzzle 0
A says "I am both a knight and a knave."

# Puzzle 1
A says "We are both knaves."

B says nothing.

# Puzzle 2
A says "We are the same kind."

B says "We are of different kinds."

# Puzzle 3
A says either "I am a knight." or "I am a knave.", but you don't know which.

B says "A said 'I am a knave'."

B says "C is a knave."

C says "A is a knight."
