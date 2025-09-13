# Snark_simulators
**This repo is my coding playground: fun simulators with personality, used to practice C++ and Python fundamentals like functions, loops, input validation, and class design.**

What is included: 

## Back to Primary school Alpha 1.0
This is a basic program to add 2 numbers togther, using a function to keep the code modulated. 

### Features
- Simple user input 
- Simple function to add 2 numbers together
- Snark injected to add personality

### Updates
#### Back_to_Primary_School Alpha 1.1
- Conditionals added - snark message depending on number input
- Are you Proud? Question - challenging users for picking a number between 1-100
- Additional personality added - engage users further

#### Back_to_Primary_School Alpha 1.2
- Do_while loop have been intergrated for the input of the first number and the Are you proud question with the intention to trap users 
- Users are now forced to answer the questions specifically 
- Bug: Infinite loop triggered if user answers wrong

#### Back_to_Primary_School Beta 1.0
- Program has been restructured into a series of functions, allowing feasible expansions
- More robust program - now integrated arrays to allow multiplie variations of Yes and no 
- Cleaner main
- Bug: Program will loop infinitely if the user answers with a junk value

#### Back_to_Primary_School Beta 1.1
- User input limited: Buffer cleaning prototype was integrated into the program (prevents users from entering unaccepted values, fostering a fully robust design)
- Bug fixed: no infinite loops caused through incorrect value input

## Dice Simulator Beta 1.0
It's a dice throwing game, all roll triggering a pleasant... or unpleasant surprise

### Features
- A dice class that allows for multiplie dices being easily added through vectors in a future update
- A simple single 6 sided dice thrown
- An array in the main containing the message

### Updates
#### Dice Simulator Beta 1.01
- A continue prompt has been integrated in the dice class allowing users to choose to continue or not

## How to Compile & Run

```bash
g++ src/BacktoPrimarySchool.cpp -o BacktoPrimarySchool
./BacktoPrimarySchool
Copy the code and paste it onto an online compiler, for instance Programiz Online Compiler
