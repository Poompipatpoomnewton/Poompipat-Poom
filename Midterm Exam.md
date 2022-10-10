Start
SET Please TEMP TO DISPLAY
SEND Please TEMP TO DISPLAY
RECIEVE TEMP TO DISPLAY
SEND TEMP TO KEYBOARD
RECIEVE TEMP TO KEYBOARD
  Else TEMP More than 18 degree celcius
    SEND "Cold,the perfect temperature for sleep is 18-21 degrees." TO DISPLAY
    RECIEVE "Cold,the perfect temperature for sleep is 18-21 degrees." TO DISPLAY
    SEND "Cold,the perfect temperature for sleep is 18-21 degrees." TO KEYBOARD
    RECIEVE "Cold,the perfect temperature for sleep is 18-21 degrees." TO KEYBOARD
      IF TEMP less than 21 degree celcius
      SEND "Perfect!" TO DISPLAY
      RECIEVE "Perfect" TO DISPLAY
      SEND "Perfect" TO KEYBOARD
      RECIEVE "Perfect" TO KEYBOARD
        SEND "NO!, the perfect temperature for sleep is 18-21 degrees." TO DISPLAY
        RECIEVE "NO!, the perfect temperature for sleep is 18-21 degrees." TO DISPLAY
        SEND "NO!, the perfect temperature for sleep is 18-21 degrees." TO KEYBOARD
        RECIEVE "NO!, the perfect temperature for sleep is 18-21 degrees. TO KEYBOARD
END
