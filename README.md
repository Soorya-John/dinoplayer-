A simple game console using arduino nano/promini + sh1106 1.3' display that plays the chrome dino game 
1- uncomment the display type you are going to use 
2- upload the code 
3- connect the buttons as in the code 

\\4-important\\ - replace R3 & R4 on the back of the sh1106 board ( usually 10k ohms ) with 1k or 4.7k ohm resistors so that we can run i2c @ 800khz 

A4 is Serial Data & A5 is serial clock 
