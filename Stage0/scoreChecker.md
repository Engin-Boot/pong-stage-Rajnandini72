# scoreChecker

## Feature

Count the Score of both players

## Acceptance Criteria
Both players are ready to play and ball speed is already declared
Player 1 or paddle1: Computer Robot
Player 2 or paddle2: User

## Variables:
scoreOfPlayer1=0
scoreOfPlayer2=0

### Scenario: Count Player2 Score

  Given :Player 1 has hit the ball 
  
  When :Ball has not entered the opoosite side or gone out of boundary from same side

  Then :Increment the scoreOfPlayer2

### Scenario: Count Player1 Score

  Given :Player 2 has hit the ball 
  
  When :Ball has not entered the opoosite side or gone out of boundary from same side

  Then :Increment the scoreOfPlayer1



