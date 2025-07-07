A simple game console using arduino nano/promini + sh1106 1.3' display that plays the chrome dino game { N0T MY OWN CODE ALL THANKS TO ALEX IM JUS DESIGNING HARDWERE }

1- uncomment the display type you are going to use 
2- upload the code 
3- connect the buttons as in the code 

\\4-important\\ - replace R3 & R4 on the back of the sh1106 board ( usually 10k ohms ) with 1k or 4.7k ohm resistors so that we can run i2c @ 800khz 

A4 is Serial Data & A5 is serial clock 


![replaced ![sch-sh1106](https://github.com/user-attachments/assets/c806dae0-2a1b-4d97-a558-2eaaafca5938)
1k](https://github.com/user-attachments/assets/4f09bd53-aaf2-4c2a-9cfd-5bd6f58aee31)

this is what it should look like 

![WhatsApp Image 2025-07-07 at 23 19 11_76a36930](https://github.com/user-attachments/assets/d15015f9-6934-4044-bdcb-cad4f5507c66)
![WhatsApp Image 2025-07-07 at 23 19 10_ceb0997a](https://github.com/user-attachments/assets/ba20a567-995a-4081-9853-d8fff7b14032)
![WhatsApp Image 2025-07-07 at 23 19 10_bfc2d2c2](https://github.com/user-attachments/assets/23237203-4f64-4916-ae0b-bb746e0b7876)
![WhatsApp Image 2025-07-07 at 23 19 09_3e08c7ff](https://github.com/user-attachments/assets/5e834eba-a2b7-48da-bb9a-983639c435b0)

