# In this project, an alarm clock is implemented by controlling the DS3231 module, a buzzer and an interface converter.
 
Next, I will show the CubeMX settings, the project uses DMA, I2C and UART and EXTI0

![image](https://github.com/TeXniKsueta/Watch-Alarm/assets/152018745/24906734-e0ff-420a-9bda-6615b5558c29)

DMA:

![image](https://github.com/TeXniKsueta/Watch-Alarm/assets/152018745/df4cc548-42cd-4617-81d7-1ecfcac48d3f)


EXTI0 PB0:
![image](https://github.com/TeXniKsueta/Watch-Alarm/assets/152018745/0f9f8ec3-5b19-4fc5-af8a-3c6c8a82cde3)


UART:
![image](https://github.com/TeXniKsueta/Watch-Alarm/assets/152018745/ed990b04-7d4c-4038-9be1-2b0cb4349705)

Next, you need to copy the code from main.c and it.c, connect all the modules and your watch will work.

The connection and operation can be seen on the video by clicking on the link: https://drive.google.com/drive/folders/14wbfqX2OmuQX8ZiUsAEA7bbL9cBXti1W?usp=drive_link

there is also a transistor and a resistor on the breadboard in order to remove the constant squeak from the squeaker (the transistor is connected according to a typical scheme)

If you have done all the steps correctly, then everything should work for you. If not, then try to take my folder and run the project through it.
You also need to install the Terminal program: https://drive.google.com/drive/folders/17aCevMOOStPuHU7tEcSeP55rm7H6wih6?usp=drive_link

Co-author: https://github.com/grish-kov
