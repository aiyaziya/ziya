SEND "What is the temperature" TO DISPLAY
RECEIVE temperature from keyboard
IF temperature <18° THEN
SEND "too cold! the temperature for sleep is 18° to 21°" TO DISPLAY
RECEIVE temperature from keyboard
IF temperature <21° THEN
SEND "no! the perfect temperature for sleep is 18° to 21°" TO DISPLAY
ELSE IF GUESS temperature >21° THEN
SEND "perfect!" TO DISPLAY
ENDIF
ENDIF
