# project_1_game_mastermine

Alberto Abreu N.

Data Analytics, Barcelona 26-06-2019

## Content

- Project Description
- Workflow
- Organization
- Links

### Project Description
My project consist on coding a Mastermine game where you (the codebreaker) play against the system (the codemaker) to try to guess the pattern chosen randomly by the codemaker. 

I choose to code this game because it will involve functions.

Users:

Codemaker: The code maker is the person who chooses a pattern of four code strings and provide feedback to the Codebreaker.

Codebraker: The codebreaker tries to guess the pattern, in both order and color, within twelve (or ten, or eight) turns.

The game is played using:

1- A “decoding board” with a shield cover one of the ends of the board protecting the four code pegs created by the Codemaker and and twelve (or ten, or eight, or six) additional rows containing four large holes next to a set of four small holes.

2- Code list of six different colors strings. [ ‘green’, ‘red’, ‘yellow’, ‘blue’, ‘purple’, ‘pink’ ]

3- Key strings in a list, some “black” , some “white” .

The flow:

1- The Codemaker creates the pattern which is a list of four elements (i.e. [ ‘green’, ‘red’, ‘yellow’, ‘red’ ] ). This is created by the computer and you will not be able to see it, it is hidden from you. 

2- The Codebreaker decides the difficulty of the game by choosing how many rounds. More rounds increases the chances of winning the game by decoding the code. 

3- The Codebreaker writes down the pattern for the first time (i.e. [ ‘red’, ‘yellow’, ‘purple’, ‘red’ ] ).

4- The Codemaker provides feedback by returning a list of “black” and “whites” strings indicating:

	4.1. “Black” means that you guess the color and the index of the element in the pattern but does not tell you which element. 
	4.2. “White” means that you guess the color but not the location but does not tell you which element. 
    4.3. " - " means that the color is not part of the codomaker code. 
    
(i.e. [ ' - ', "white", ' - ', 'black' ] ).

5 - Step 3 and 4 are repeated sequentially until the Codebreaker solve the code or the number of rounds reached the limit. 

6- If the Codebreaker solve the code before the number of rounds then he wins, and if not, the Codemaker wins. 

### Workflow
Outline the workflow you used in your project. What were the steps you went through?


### Organization
How did you organize yourself? Did you use any tools?


### Links

Repository
Slides
Trello

