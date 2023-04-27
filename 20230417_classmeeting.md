# April 17th Class Meeting Notes

ezButton Library - debouncing etc. pretty simple library.

ex:
 if (digitalRead(4) == LOW && lastButtonState =+ HIGH && millis() - lastButtonTimestamp > 50){
      trackNumber = 81;
    Serial.write(trackNumber)
    lastButtonState = LOW;
    lastButtonTimestamp = millis();
 }

unsigned long > when using time.

relief cuts. Band saw, there are limits on how tight of a circle you can cut depends on the blade thickness and length. relief cuts are made so that the outer pieces will fall off as you cut them, so that the blade has room to move.

## April 19

Capacitors on the motor. This lessens the noise that affects the circuit.

7805 > voltage needs to be above ~6.5 in order to convert into 5v in arduino.

Atmel is now Microchip flip.
.01-.1 UF capacitors

I soldiered the pins onto the motor drivers.

I also received the capacitors for my two DC motors that I can soldier on later.
