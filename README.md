# Bingo Bame
This module is designed for implementation in CPLD modules. by CADcom from SKEL 4273 UTM, supervised by AP. Muhammad Munim Ahmad Zabidi

What is Bingo Game?

# Description of Game

This Bingo game is 2 players game where a random 8 bit number will be generated when the game start. A range of number will be display to the players and players can only input the numbers within the range. Each players will take turn to guess the generated random number to win the game.
There are 3 major states for this game:
1.	Idle State
2.	Input state. The system will wait for the input from the user.
3.	Checking State. The system will compare the input with the random number generated. If the input not equal to the random number generated, the system will jump back to state 2 and the games continues on. If the input is the same as the random number generated, the system will jump to state 1 and the games end.

# Output Simulation
![image](https://user-images.githubusercontent.com/87294236/125234475-6860f300-e313-11eb-9977-854b71a607c2.png)

# Rtl-ASM chart

![image](https://user-images.githubusercontent.com/87294236/125233842-fe941980-e311-11eb-97b4-d3c578309894.png)

# Functional block diagram

![image](https://user-images.githubusercontent.com/87294236/125234160-b6c1c200-e312-11eb-8895-091b55b456e7.png)

# Datapath Unit

![image](https://user-images.githubusercontent.com/87294236/125234280-fa1c3080-e312-11eb-818b-9ed5e6f3f90c.png)

# Control Unit

![image](https://user-images.githubusercontent.com/87294236/125234345-1e780d00-e313-11eb-852e-f7c7f2403eb8.png)

