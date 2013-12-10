Grove_LED_Bar
=============

This is a fork over the original LED_Bar library adapted for allowing custom wiring pins setup.  
It achieves so at the cost of using ```digitalWrite()``` and ```digitalRead()``` instead port mapping, so if
performance is critical for you, I advise you to implement directly the (small) LED_Bar library into your code.
