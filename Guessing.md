```mermaid
flowchart TD 

A[Start] --> B{What number am I thinking?}
B --> |guess #1| C[7]
B --> |guess #2| D[10]
C --> E[You guessed it! =2pts]
D --> F[Better luck next time! =0pts]
E --> G{What number am I thinking?}
F --> G{What number am I thinking?}
G --> |guess #1| H[3]
G --> |guess #2| I[5]
H --> [Better luck next time! =0pts]
I --> [You guessed it! =2pts]
I --> J|Congratualtions Winner!|
J --> K[END] 

  My mermaid diagram is a flowchart top-down for a number guessing game. The point of my numbering guessing game is to guess "what number am I thinking" between 2 given number options. If you select the correct number, then you are rewarded 2 pts. If you select the incorrect number, then you are rewarded no points.The objective of the game is to win 20 pts overall. The only way to win the 20pts is to guess the correct number enough times. Each correct guess is worth up to 2pts and each incorrect guess is worth 0pts. If you guess correctly, a message is shown that the correct number was guessed and you have been rewarded 2pts. If the number was guessed incorrectly, a message is shown that the number was guesssed incorrectly and new points were rewarded. The flowchart above is an example or (sample) of what the game would look like. This is now the game in its entirety. 
