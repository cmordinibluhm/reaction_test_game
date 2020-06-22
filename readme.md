# Reaction Test Game 

This is a project completed for UCLA's Electronics for Physics Measurement course (Physics 117) in Winter Quarter 2019. 

The game is simple. Player 1 presses their button, and the clock starts. Player 2 presses their button  
as quickly as they can after Player 1, and the clock stops. The game is reset by holding down both buttons for 1 second. 

A short demo of the game can be seen below, in which the timer is started and stopped several times and then reset. 

![](reaction_game_box_demo.gif)

Upper circuit constructed by myself:  

![alt text](https://github.com/cmordinibluhm/reaction_test_game/blob/master/display_board.png "Reaction Game Circuit Diagram")

Lower circuit constructed by my partner:  

![alt text](https://github.com/cmordinibluhm/reaction_test_game/blob/master/game_board.png "Reaction Game Circuit Diagram")

Below is a demo of a prototype of the game on a breadboard.  

![](reaction_test_game_breadboard.gif)

Below is a complete circuit diagram of the game, created with Google Drawings.

![alt text](https://github.com/cmordinibluhm/reaction_test_game/blob/master/reaction_game_diagram.jpg "Reaction Game Circuit Diagram")

## Components Used 

    2 buttons  
    3 seven-segment displays  
    3 decade counter chips (CD4026)  
    2 D-type flip-flop chips (74HCT74)  
    2 AND gate chips (75HCT08)  
    1 standard inverter chip (74HCT04)  
    1 inverter chip with Schmitt trigger inputs (74HCT14)  
    1 555 timer chip (LM555)  
    1 LED  
    Various resistors  
        24 kOhm resistor      
        10 kOhm resistors       
        1 kOhm resistors        
        740 Ohm resistor  
        500 Ohm resistor  
        270 Ohm resistors  
        200 Ohm resistor  
    Various capacitors  
        1 microFarad capacitors  
        0.1 microFarad capacitors  
