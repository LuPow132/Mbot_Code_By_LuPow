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


## flowchart
<div class="mxgraph" style="max-width:100%;border:1px solid transparent;" data-mxgraph="{&quot;highlight&quot;:&quot;#0000ff&quot;,&quot;nav&quot;:true,&quot;resize&quot;:true,&quot;toolbar&quot;:&quot;zoom layers tags lightbox&quot;,&quot;edit&quot;:&quot;_blank&quot;,&quot;xml&quot;:&quot;&lt;mxfile host=\&quot;app.diagrams.net\&quot; modified=\&quot;2022-09-07T06:57:57.326Z\&quot; agent=\&quot;5.0 (X11; Linux x86_64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/104.0.0.0 Safari/537.36\&quot; etag=\&quot;0lPtjbBOsiFHlSqi9nOd\&quot; version=\&quot;20.2.8\&quot; type=\&quot;github\&quot;&gt;&lt;diagram id=\&quot;-oDwmSD7BLOCyvhqM90-\&quot; name=\&quot;หน้า-1\&quot;&gt;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&lt;/diagram&gt;&lt;/mxfile&gt;&quot;}"></div>
<script type="text/javascript" src="https://viewer.diagrams.net/js/viewer-static.min.js"></script>
