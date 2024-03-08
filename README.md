# McMaster_Chem-E_Car_Braking_Datalogging_22-23_Car_Code
A temporary datalogging codebase for the McMaster Chem-E Car Team Braking Sub-Team.

This project uses an Arduino UNO microcontroller programmed in the Arduino programming language. It is based on the McMaster Chem-E Car 23-24 Codebase but adapted to run only the datalogging essentials and on the previous year's car dubbed Lightning MACQueen. Uses the new Kalman filtering algorithm to reduce noise in data implemented on the newer car alongside several other features, but adapted to run on the Arduino UNO from last year. It uses the old car as a stationary platform so that they can complete their testing of the reaction temporarily while the Mechanical sub-team continues to work on getting this year's car chassis fabricated. The code is taken piece-meal from the current code, but adapted to work with the UNO and an L298N motor driver for the stirring mechanism. It also uses a micro-servo for the reactant dumping mechanism, 8 AA batteries to provide a 12 V power source to the L298N and for the stirring motor, a potentiometer to vary the stirring speed, and a DS18B20 temperature sensor. All data is output via serial to Excel Data Streamer.

The major components used are as follows:<br />
1 - 12V 3000 RPM Brushed DC Motor taken from Iintllab Stir Plate (for stirring mechanism)<br />
1 - Micro Servo Motor (for initially mixing reactants)<br />
1 - L298N Motor Driver<br />
1 - DS18B20 Temperature Sensor (for monitoring stopping reaction progress)<br />
1 - Arduino UNO R3 Microcontroller<br />
8 - AA Alkaline Batteries (to generate 12V for motor & driver)<br />

The main objective of the competition is to design a small car to carry a certain amount of weight a set distance while powering and stopping the vehicle with a chemical reaction. The distance and weight vary each year. The compectition is hosted by the American Institute of Chemical Engineers (AIChE). See the corresponding repository for the current year's car codebase for more information on this year's setup.
