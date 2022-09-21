SET mystNumb TO 3
SEND "please enter guess number" TO DISPLAY
RECEIVE guess FROM KEYBOARD
IF guess > 10 THEN
SEND "too high! Your guess must be between 1 and 10" TO DISPLAY
ELSE IF GUESS = mystNumb THEN
SEND "Well done! You guessed correctly." TO DISPLAY
ELSE SEND "Badluck! The correct number is +mystNumb" TO DISPLAY
ENDIF 
ENDIF
