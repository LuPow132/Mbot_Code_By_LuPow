# Mbot_Code_By_LuPow
this is code for mblock explorer.

Ahhh I love coding 
This read me just to explain some of keyblind and setup ok?
Just to make sure you understand all of it.

## First of all
You turn on the robot and wait it to start up
and setup all the varible and other stupid things.
It will go into menu mode to select auto 
You can use joystick to select the program
and then press play to start the program you select
but if you want to start manual you can press box

## AUTO STATE🤖
Depend on what side you choose or is there any cube on the way
you can change to manual state instance using "R2" button on controller

The program will start by walking forward a bit
and reload the shooter to standby shooter
it will walk follow the line untill it found the line as(1111) which mean the cube will be right there and start grab cube state
(if you choose no cube the program will keep walking until ultrasonic has found that the distance is less than 6 cm it will start Grab balls state)

### Grab Cube
It will walk forward a bit just to make sure the it close enough to grab it and lift the cube a bit then it will rotate 90 degree(which side is depend on what you choose)
and walk to the cube place box and put it right there and walk backward a bit just to make sure it won't crash the cube.
Then i will rotate and go back to the line using timer and follow a line untill the distance between it is less that 6 cm.
and start Grab Ball state

### Grab Ball 
It will walk forward a bit just to make sure it close enough to grab it and the grab it walk backward a bit.
Turn 90 degree(depend on what side do you choose) and then shoot the balls and stand still

after all of auto state done it will auto change to manual state and standby wait for user to interact with controller

## Manual state🎮
LY,LX = walk left right forward backward
RX = rotate arm left right
RY = lift arm up or down
1 = shoot
2 = move the arm to the fixed position grab the balls that close to the ultrasonic and grab it
3 = lift up and release the ball on the shooter
4 = nothing yet

That's it 
I wanna cry ;-;
cya

![alt text](https://viewer.diagrams.net/embed2.js?&fetch=https%3A%2F%2Fraw.githubusercontent.com%2Frakky33%2FMbot_Code_By_LuPow%2Fmain%2FMbot_Mbot)
