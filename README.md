# Project 1 - Mastermind Game

Alberto Abreu N.

Data Analytics, Barcelona 26-06-2019

## Contents

- Project Description
- Workflow
- Organization
- Links

### Project Description

My project consist on coding a Mastermine game where you (the codebreaker) play against the system (the codemaker) to try to guess the pattern chosen randomly by the codemaker. 

I choose to code this game because it will involve functions and nested functions. And because I used to play this game with my mom all the time.

### Users:

**Codemaker**: The codemaker is the person who chooses a pattern of four code strings and provide feedback to the Codebreaker.

**Codebraker**: The codebreaker tries to guess the pattern, in both order and color, within twelve (or ten, or eight) turns.


### The Game  flow:

1- The Codemaker creates the pattern which is a list of four elements (i.e. [ ‘green’, ‘red’, ‘yellow’, ‘red’ ] ). This is created by the computer and you will not be able to see it, it is hidden from you. 

2- The Codebreaker decides the difficulty of the game (easy, medium or hard). Depending on the difficulty level you play more or less rounds.

3- The Codebreaker writes down the pattern for the first time (i.e. [ ‘red’, ‘yellow’, ‘purple’, ‘red’ ] ).

4- The Codemaker provides feedback by returning a list of **“black”, “whites” or " - "** strings indicating:

	4.1. “Black” means that you guess the color and the index of the element in the pattern but does not tell you which element. 
	4.2. “White” means that you guess the color but not the location but does not tell you which element. 
    4.3. " - " means that the color is not part of the codomaker code. 
    
(i.e. [ ' - ', "white", ' - ', 'black' ] ).

5 - Step 3 and 4 are repeated sequentially until the Codebreaker solve the code or the number of rounds reached the limit. 

6- If the Codebreaker solve the code before the number of rounds then he wins, and if not, the Codemaker wins. 

### Workflow

1- First of all I planed my proyect in trello, writing down all the activities to achieved the objective.

2- Looked for the game rules and variations.

3- Sketch in paper how I wanted to achieved the game code.

4- Started coding by doing programming functions for every step of my structure. Once I had all my functions, I create a game() function containing all the functions from previous steps. This function will play the game and return the winner of it. 

        1- DEFINING A FUNCTION TO LET THE CODEBREAKER CHOOSE THE DIFFICULTY LEVEL VIA INPUT THUS THE ROUNDS OF THE GAME.
        2- DEFINING THE CODEMAKER CODE PATTERN IN A RANDOM WAY.
        3- DEFINING THE CODEBREAKER GUESS VIA INPUT.
        4- DEFINING A FUNCTION TO COMPARE THE CODEBREAKER GUESS WITH THE CODEMAKER CODE PATTERN.
        5- DEFINING THE GAME FLOW FUNCTION, RETURNING THE WINNER OF THE GAME.

5- Error handling to avoid wrong entries from the user or codebreaker.

6- Test my code by myself repeatedly and I also asked coallegues to try it as well.

7- Fixing bugs and making the UI/UX user friendly.


### Organization

##### Tools:

1- Trello: for proyect management.

2- Github as my repository platform.

3- iterm as my terminal.

4- Jupyter notebook as my python platform.

5- Slides as my presentation tool.


### Links

Repository: https://github.com/albertoabreu91/project_1_game_mastermine

Slides: https://slides.com/albertoabreu/deck/edit

Trello: https://trello.com/b/shc7VAUJ/project-1-create-your-own-game

