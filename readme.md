Simple Game AI for Rock-Paper-Scissors
Problem Statement
Rock-Paper-Scissors is a simple hand game played between two players. The objective of this project is to develop an AI opponent that can play against a human player. The AI should not just make random moves but should adapt and improve its strategy based on the opponent’s past choices.
Approach
This project implements a rule-based AI for Rock-Paper-Scissors with a basic learning mechanism. The AI follows these steps:
Random Choice at Start: If the AI has no data on the opponent’s moves, it chooses randomly.
Learning from History: The AI records the opponent’s previous choices and predicts their next move based on frequency.
Counter Strategy: The AI selects the move that would counter the predicted choice to maximize its chances of winning.
Implementation Details
⦁	The game supports user input (rock, paper, or scissors).
⦁	The AI makes a decision based on opponent history.
⦁	The AI's choices are updated dynamically to improve performance.
⦁	The game runs in a loop until the user exits.
How to Run the Program
Ensure you have Python installed.
Save the provided Python script as rock_paper_scissors_ai.py.
Open a terminal or command prompt and run: 
python rock_paper_scissors_ai.py
Enter your choice (rock, paper, or scissors) and play against the AI.
Type quit to exit the game.
Reference
⦁	Rock-Paper-Scissors Game Theory : https://en.wikipedia.org/wiki/Rock_paper_scissors
⦁	Machine Learning in Game : https://www.analyticsvidhya.com/blog/2023/03/ml-and-ai-in-game-development/