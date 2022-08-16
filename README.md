# Raspberry-Pi-4-vs-Arduino-Mega-2560 (December 2021)
Execution time and speed up comparison between microprocessor and microcontroller

Performance Analysis between Arduino Mega 2560 and Raspberry Pi 4 Jeremy Hester, Jason Farrell, John-Luke Speight
To run the Pi code:
LED: “pilight.c” -Open the “Geany” program  -Select the “Build” tab -Within “C Commands” -Copy and paste below into the “Command” portion of “1. Compile”  “gcc -Wall -c”%f" -lpigpio -lpthread -lm -lrt -lwiringPi“ -Copy and paste below into the”Command" portion of “2. Build” “gcc -Wall -o”%e" “%f” -lpigpio -lpthread -lm -lrt -lwiringPi"
-Within Linux Terminal compile with below “gcc -o pilight pilight.c” -Run program with below “time ./pilight”
Matrix: -Save “MathMatrix.cpp” , “MatrixMath.h” , and “matrix.cpp” into the same file
Run the Mega Code:
LED:
Matrix: 
